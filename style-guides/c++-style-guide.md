# C++ Style Guide

### Overview

We start with Google's C++ style guide at [https://google.github.io/styleguide/cppguide.html](https://google.github.io/styleguide/cppguide.html), the remainder of this document describe the differences with Google's guidelines.

If you work in a third party's code base follow their style unless it is genuinely unclear what style they use.

### Indentation&#x20;

Use the following bash script to clang-format all cpp files in a directory:

```
# Assumes ham is around
LINT_CPP_DIR=src # The directory with the code to lint
(set -e ; find "$LINT_CPP_DIR" \
             \( -name '*.c' \
             -o -name '*.cc' \
             -o -name '*.cpp' \
             -o -name '*.h' \
             -o -name '*.hh' \
             -o -name '*.hpp' \
             -o -name '*.inl' \) -print0 | xargs -t -0 -n 10 -P ${HAM_NUM_JOBS:-8} run-for-xargs clang-format ${PARAMS[@]})

```

Use the following .clang-format:

```
#
# Documentation at https://clang.llvm.org/docs/ClangFormatStyleOptions.html
#
Language: Cpp
BasedOnStyle: Google
SortIncludes: false
IndentWidth: 2
ContinuationIndentWidth: 2
PPIndentWidth: 2
ColumnLimit: 88
MaxEmptyLinesToKeep: 1
IndentGotoLabels: false
IndentWrappedFunctionNames: false
ReflowComments: false
ConstructorInitializerAllOnOneLineOrOnePerLine: true
AllowAllConstructorInitializersOnNextLine: true
UseTab: false
UseCRLF: false
DeriveLineEnding: false
AllowShortBlocksOnASingleLine: Never
AllowShortCaseLabelsOnASingleLine: false
AllowShortEnumsOnASingleLine: false
AllowShortFunctionsOnASingleLine: false
AllowShortIfStatementsOnASingleLine: false
AllowShortLambdasOnASingleLine: Inline
AllowShortLoopsOnASingleLine: false
BreakBeforeBraces: Custom
BraceWrapping:
  BeforeElse: true
  AfterFunction: false
BreakStringLiterals: false
BreakConstructorInitializers: BeforeComma
PackConstructorInitializers: Never
BinPackArguments: false
BinPackParameters: false
AllowAllArgumentsOnNextLine: true
AllowAllParametersOfDeclarationOnNextLine: true
AlignConsecutiveBitFields: true
BreakBeforeTernaryOperators: true
AlignAfterOpenBracket: AlwaysBreak
AlignOperands: Align
BreakBeforeBinaryOperators: None
ForEachMacros: ["niLoop","niLoopr","niLoopit","niLooprit","niExec","niExec_","niSubmit","niSubmit_"]
SpaceBeforeParens: ControlStatementsExceptControlMacros
AlignEscapedNewlines: Left
AlignTrailingComments: true
```

### Usage of std

We use the `std` namespace in this style guide, however if you use niLang use the `astl` namespace when available.

At the time of writing `astl` is based of EASTL and has exactly the same behaviour on all supported platforms as-well as allowing to specify custom memory allocators. `astl` can fairly easily be aliased to `std` if necessary - except of course when you use features not present in `std`.

### Interop/reflection

Interop refers to interoperability with other languages, but also features that require language reflection such as serialization & RPC.

### Variables

* `gGlobalVariable`
* `kGlobalConstant`
* `aFunctionArgument`&#x20;
* `_memberVariable` or legacy `mMemberVariable`
* `localVariable`

Use only the following Hungarian notation. It is mandatory for global variables, constants, function arguments & member variables. Right now these are allowed and encouraged:

* `n` for integer numbers
* `f` for floating point numbers - regardless of precision
* `sz` for zero terminated strings
* `str` for string objects: `std::string`, `ni::cString`
* `p` for raw pointers: `Foo*`
* `ptr` for smart pointers: `std::shared_ptr`, `ni::Ptr`
* `w` for weak pointers: `std::weak_ptr`, `ni::WeakPtr`
* `u` for unique pointers, `std::unique_ptr`, `ni::UniquePtr`
* `map` for sorted map containers & `hmap` for hashed map containers: `std::map`, `astl::hash_map`
* `set` for sorted set containers & `hset` for hashed set containers: `std::set`, `astl::hash_set`
* `lst` for list containers: `std::list`
* `deq` for deque containers: `std::deque`
* legacy: `v` for vector container, prefer the plural form to denote arrays & vectors: `std::vector`
* `v` for mathematical vector types: `ni::sVec2f`, `ni::sVec4i`
* `mtx` for mathematical matrix types: `ni::sMatrixf`
* `uuid` for 128-bits GUID / UUID types: `ni::tUUID`

### Constants

Always specify `static const` and its initialization value.

```
static const ni::tI32 knValue = 123;
```

### Struct & Classes

TODO

```
struct sMyStructure {
};

class cMyClass {
}
```

### Enums

By default prefer interoperable enums.

All the values in an enum should be explicitly specified.

#### Interoperable enums

```
// Interop compatible enumeration
enum eFoo {
  eFoo_Alpha = 0,
  eFoo_Beta = 1,
  eFoo_Gamma = 2,
  eFoo_Last = 3
};

// Interop compatible flags (32 flags / bits maximum)
enum eFooFlags {
  eFooFlags_Un = niBit(0),
  eFooFlags_Dos = niBit(1),
  eFooFlags_Tres = niBit(2),
};
```

#### Private typed enums

```
enum eFoo : ni::tU32 {
  kAlpha = 0,
  kBeta = 1,
  kGamma = 2
};
```

### Namespaces

Deep namespace hierarchies in C++ leak in a lot of places and make general interop quite difficult (interop is other languages, serialization, RPC, etc...).

For example in the Flecs explorer you're going to see `rdd::ecs::component::Position` which is unnecessarily long. This will leak into serialization, and then they often get stripped in debuggers\&logs which makes the actual struct/class concerned hard to identity at a glance ; C++ namespaces are generally not very well handled by various tools. Keeping the nature of the struct/class in its name is a lot simpler to side step those issues.

In general use namespaces for these two cases:

1. for the root like `std`, `ni`, `astl`. This is meant to avoid symbol conflicts in C++, but not really anything else.
2. to hide implementation details so something like `boost::detail` (used in boost), `impl`, etc...

### Pointers & references

Raw pointers (`Foo*`) and references (`Foo&`) should only be used in parameters and return values.

For storage (local, member & global variables) your must understand the ownership requirements.

For the general internal code use `shared_ptr, weak_ptr or unique_ptr` (from the `astl` namespace if using niLang or from `std` otherwise, they have the same APIs).

For public interface which gets exposed through niLang's interop your class should inherit from `ni::iUnknown` (most of the time through `public ni::cIUnknownImpl<ni::iUnknown>`) and then stored with `ni::Ptr<> / ni::WeakPtr<>`.

