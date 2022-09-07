# Module niLang
Generated on 2022-09-07T10:09:41+08:00

- name: niLang
- desc: niLang module
- version: 1,0,0
- author: niLang Authors
- copyright: (c) 2022 The niLang Authors

## interface ni::iIterator
Collection iterator interface. 

### Parents:
- iUnknown

### Methods:
- __iIterator::GetCollection__() -> _iCollection\*_: Get the collection in which the iterator operates. 
- __iIterator::HasNext__() -> _tBool_: Check whether their is more elements to iterate. 
- __iIterator::Next__() -> _const Var&_: Get the next value. 
- __iIterator::Key__() -> _const Var&_: Get the current key. 
- __iIterator::Value__() -> _const Var&_: Get the current value. 

## interface ni::iCollection
Immutable Collection interface. 

### Parents:
- iUnknown

### Methods:
- __iCollection::GetKeyType__() -> _tType_: Get the collection's key type. 
- __iCollection::GetValueType__() -> _tType_: Get the collection's value type. 
- __iCollection::IsEmpty__() -> _tBool_: Returns true if this collection contains no elements. 
- __iCollection::GetSize__() -> _tU32_: Returns the number of elements in this collection. 
- __iCollection::Contains__(_const Var&_ aVar) -> _tBool_: Returns true if this collection contains the specified key. 
- __iCollection::ContainsAll__(_const iCollection\*_ apCollection) -> _tBool_: Returns true if this collection contains all of the elements in the specified collection. 
- __iCollection::Iterator__() -> _iIterator\*_: Returns an iterator over the elements in this collection. 
- __iCollection::Find__(_const Var&_ aVar) -> _iIterator\*_: Returns an iterator over starting at the specified elements in this collection. 
- __iCollection::Get__(_const Var&_ aKey) -> _Var_: Returns the value to which the specified key is mapped, or null if this map contains no mapping for the key. 
- __iCollection::GetFirst__() -> _Var_: Returns the first value in the container. 
- __iCollection::GetLast__() -> _Var_: Returns the last value in the container. 

## interface ni::iMutableCollection
Mutable Collection interface. 

### Parents:
- iCollection

### Methods:
- __iMutableCollection::Clear__() -> _tBool_: Removes all of the elements from this collection. 
- __iMutableCollection::Copy__(_const iCollection\*_ apCollection) -> _tBool_: Copy a collection of the same type in this collection. 
- __iMutableCollection::Reserve__(_tU32_ anSize) -> _tBool_: Reserve memory for the specified number of elements. 
- __iMutableCollection::Resize__(_tU32_ anSize) -> _tBool_: Resize the collection to the specified number of elements. 
- __iMutableCollection::Add__(_const Var&_ aVar) -> _tBool_: Ensures that this collection contains the specified key. 
- __iMutableCollection::AddAll__(_const iCollection\*_ apCollection) -> _tBool_: Adds all of the elements in the specified collection to this collection. 
- __iMutableCollection::Remove__(_const Var&_ aVar) -> _tBool_: Removes a single instance of the specified key from this collection, if it is present (optional operation). 
- __iMutableCollection::RemoveIterator__(_iIterator\*_ apIterator) -> _tBool_: Removes the element pointed by the specified iterator. 
- __iMutableCollection::RemoveAll__(_const iCollection\*_ apCollection) -> _tBool_: Removes all of this collection's elements that are also contained in the specified collection. 
- __iMutableCollection::RemoveFirst__() -> _tBool_: Retrieve and remove the first element of the container. 
- __iMutableCollection::RemoveLast__() -> _tBool_: Retrieve and remove the last element of the container. 
- __iMutableCollection::Put__(_const Var&_ aKey, _const Var&_ aValue) -> _tBool_: Associates the specified value with the specified key. 
- __iMutableCollection::SetFirst__(_const Var&_ aValue) -> _tBool_: Sets the first value in the container. 
- __iMutableCollection::SetLast__(_const Var&_ aValue) -> _tBool_: Sets the last value in the container. 
- __iMutableCollection::GetDataPtr__() -> _tPtr_: Get a pointer to continous memory that can be read/written directly. 
- __iMutableCollection::GetDataSize__() -> _tSize_: Get the size in bytes of the memory pointed by the data pointer. 

## interface ni::iIterator
Collection iterator interface. 

### Parents:
- iUnknown

### Methods:
- __iIterator::GetCollection__() -> _iCollection\*_: Get the collection in which the iterator operates. 
- __iIterator::HasNext__() -> _tBool_: Check whether their is more elements to iterate. 
- __iIterator::Next__() -> _const Var&_: Get the next value. 
- __iIterator::Key__() -> _const Var&_: Get the current key. 
- __iIterator::Value__() -> _const Var&_: Get the current value. 

## interface ni::iIterator
Collection iterator interface. 

### Parents:
- iUnknown

### Methods:
- __iIterator::GetCollection__() -> _iCollection\*_: Get the collection in which the iterator operates. 
- __iIterator::HasNext__() -> _tBool_: Check whether their is more elements to iterate. 
- __iIterator::Next__() -> _const Var&_: Get the next value. 
- __iIterator::Key__() -> _const Var&_: Get the current key. 
- __iIterator::Value__() -> _const Var&_: Get the current value. 

## interface ni::iCollection
Immutable Collection interface. 

### Parents:
- iUnknown

### Methods:
- __iCollection::GetKeyType__() -> _tType_: Get the collection's key type. 
- __iCollection::GetValueType__() -> _tType_: Get the collection's value type. 
- __iCollection::IsEmpty__() -> _tBool_: Returns true if this collection contains no elements. 
- __iCollection::GetSize__() -> _tU32_: Returns the number of elements in this collection. 
- __iCollection::Contains__(_const Var&_ aVar) -> _tBool_: Returns true if this collection contains the specified key. 
- __iCollection::ContainsAll__(_const iCollection\*_ apCollection) -> _tBool_: Returns true if this collection contains all of the elements in the specified collection. 
- __iCollection::Iterator__() -> _iIterator\*_: Returns an iterator over the elements in this collection. 
- __iCollection::Find__(_const Var&_ aVar) -> _iIterator\*_: Returns an iterator over starting at the specified elements in this collection. 
- __iCollection::Get__(_const Var&_ aKey) -> _Var_: Returns the value to which the specified key is mapped, or null if this map contains no mapping for the key. 
- __iCollection::GetFirst__() -> _Var_: Returns the first value in the container. 
- __iCollection::GetLast__() -> _Var_: Returns the last value in the container. 

## interface ni::iMutableCollection
Mutable Collection interface. 

### Parents:
- iCollection

### Methods:
- __iMutableCollection::Clear__() -> _tBool_: Removes all of the elements from this collection. 
- __iMutableCollection::Copy__(_const iCollection\*_ apCollection) -> _tBool_: Copy a collection of the same type in this collection. 
- __iMutableCollection::Reserve__(_tU32_ anSize) -> _tBool_: Reserve memory for the specified number of elements. 
- __iMutableCollection::Resize__(_tU32_ anSize) -> _tBool_: Resize the collection to the specified number of elements. 
- __iMutableCollection::Add__(_const Var&_ aVar) -> _tBool_: Ensures that this collection contains the specified key. 
- __iMutableCollection::AddAll__(_const iCollection\*_ apCollection) -> _tBool_: Adds all of the elements in the specified collection to this collection. 
- __iMutableCollection::Remove__(_const Var&_ aVar) -> _tBool_: Removes a single instance of the specified key from this collection, if it is present (optional operation). 
- __iMutableCollection::RemoveIterator__(_iIterator\*_ apIterator) -> _tBool_: Removes the element pointed by the specified iterator. 
- __iMutableCollection::RemoveAll__(_const iCollection\*_ apCollection) -> _tBool_: Removes all of this collection's elements that are also contained in the specified collection. 
- __iMutableCollection::RemoveFirst__() -> _tBool_: Retrieve and remove the first element of the container. 
- __iMutableCollection::RemoveLast__() -> _tBool_: Retrieve and remove the last element of the container. 
- __iMutableCollection::Put__(_const Var&_ aKey, _const Var&_ aValue) -> _tBool_: Associates the specified value with the specified key. 
- __iMutableCollection::SetFirst__(_const Var&_ aValue) -> _tBool_: Sets the first value in the container. 
- __iMutableCollection::SetLast__(_const Var&_ aValue) -> _tBool_: Sets the last value in the container. 
- __iMutableCollection::GetDataPtr__() -> _tPtr_: Get a pointer to continous memory that can be read/written directly. 
- __iMutableCollection::GetDataSize__() -> _tSize_: Get the size in bytes of the memory pointed by the data pointer. 

## interface ni::iIterator
Collection iterator interface. 

### Parents:
- iUnknown

### Methods:
- __iIterator::GetCollection__() -> _iCollection\*_: Get the collection in which the iterator operates. 
- __iIterator::HasNext__() -> _tBool_: Check whether their is more elements to iterate. 
- __iIterator::Next__() -> _const Var&_: Get the next value. 
- __iIterator::Key__() -> _const Var&_: Get the current key. 
- __iIterator::Value__() -> _const Var&_: Get the current value. 

## interface ni::iRunnable
Runnable interface. 

### Parents:
- iUnknown

### Methods:
- __iRunnable::Run__() -> _Var_

## interface ni::iCallback
Callback interface. 

### Parents:
- iRunnable

### Remarks:
- A callback is similar to a runnable excepted that it accepts up to two parameters. If it used as a runnable both parameters are set to null. 

### Methods:
- __iCallback::RunCallback__(_const Var&_ avarA, _const Var&_ avarB) -> _Var_

## interface ni::iRunnableQueue
Runnable queue interface. 

### Parents:
- iUnknown

### Methods:
- __iRunnableQueue::GetThreadID__() -> _tU64_: Get the runnable queue's owner thread. 
- __iRunnableQueue::GetSize__() -> _tU32_: Get the number of runnable currently in the queue. 
- __iRunnableQueue::IsEmpty__() -> _tBool_: Check whether any runnable is in the queue. 
- __iRunnableQueue::Add__(_iRunnable\*_ apRunnable) -> _tBool_: Queue a runnable. 
- __iRunnableQueue::Peek__() -> _Ptr<iRunnable>_: Retrieves, but does not remove, the head of this queue, or returns null if this queue is empty or if called from another thread than the owner thread. 
- __iRunnableQueue::Poll__() -> _Ptr<iRunnable>_: Retrieves and removes the head of this queue, or returns null if this queue is empty or if called from another thread than the owner thread. 
- __iRunnableQueue::WaitForRunnable__(_tU32_ anTimeOut) -> _tBool_: Wait for a runnable to be in the queue. 

## interface ni::iMessageHandler
Message handler interface. 

### Parents:
- iUnknown

### Methods:
- __iMessageHandler::GetThreadID__() -> _tU64_: Get the message handler's owner thread. That is the thread where HandleMessage will be called. 
- __iMessageHandler::HandleMessage__(_const tU32_ anMsg, _const Var&_ avarA, _const Var&_ avarB) -> _void_: Called when a message should be handled. 

## interface ni::iMessageDesc
Message description interface. 

### Parents:
- iUnknown

### Methods:
- __iMessageDesc::GetHandler__() -> _iMessageHandler\*_: Get the message handler. 
- __iMessageDesc::GetID__() -> _tU32_: Get the message id. 
- __iMessageDesc::GetA__() -> _const Var&_: Get the message parameter A. 
- __iMessageDesc::GetB__() -> _const Var&_: Get the message parameter B. 

## interface ni::iMessageQueue
Message queue interface. 

### Parents:
- iUnknown

### Methods:
- __iMessageQueue::GetThreadID__() -> _tU64_: Get the message queue's owner thread. 
- __iMessageQueue::GetSize__() -> _tU32_: Get the number of message currently in the queue. 
- __iMessageQueue::IsEmpty__() -> _tBool_: Check whether any message is in the queue. 
- __iMessageQueue::Add__(_iMessageHandler\*_ apHandler, _tU32_ anMsg, _const Var&_ avarA, _const Var&_ avarB) -> _tBool_: Queue a message. 
- __iMessageQueue::Peek__(_sMessageDesc\*_ apMessageDesc) -> _tBool_: Retrieves, but does not remove, the head of this queue, or returns eFalse if this queue is empty or if called from another thread than the owner thread. 
- __iMessageQueue::PeekDesc__() -> _Ptr<iMessageDesc>_: Same as \see Peek but returns a new iMessageDesc object. 
- __iMessageQueue::Poll__(_sMessageDesc\*_ apMessageDesc) -> _tBool_: Retrieves and removes the head of this queue, or returns eFalse if this queue is empty or if called from another thread than the owner thread. 
- __iMessageQueue::PollDesc__() -> _Ptr<iMessageDesc>_: Same as \see Poll but returns a new iMessageDesc object. 
- __iMessageQueue::PollAndDispatch__() -> _tBool_: Retrieves, removes and call the message handler of the head of this queue, or returns eFalse if this queue is empty or if called from another thread than the owner thread. 
- __iMessageQueue::WaitForMessage__(_tU32_ anTimeOut) -> _tBool_: Wait for a message to be in the queue. 

## interface ni::iFuture
Future interface.  A Future represents the result of an asynchronous computation. Methods are provided to check if the computation is complete, to wait for its completion, and to retrieve the result of the computation. 

### Parents:
- iUnknown

### Methods:
- __iFuture::Cancel__() -> _void_: Cancel the task associated with the future. 
- __iFuture::GetIsCancelled__() -> _tBool_: Check whether the task has been cancelled. 
- __iFuture::GetIsDone__() -> _tBool_: Return true if this task completed. 
- __iFuture::Wait__(_tU32_ anTimeOut) -> _tBool_: Wait for the value to be set. 
- __iFuture::GetValue__() -> _Var_: Return the result of the computation, returns null if the task is not completed. 

## interface ni::iFutureValue
Future value. 

### Parents:
- iFuture

### Methods:
- __iFutureValue::SetValue__(_const Var&_ aValue) -> _void_: Sets and signal the future. 
- __iFutureValue::Reset__() -> _void_: Reset the future to the unset & not-canceled state. 

## interface ni::iExecutor
Executes the submitted iRunnable tasks.  This interface provides a way of decoupling task submission from the mechanism of how each task will be run, including the details of thread use, scheduling, etc.  An executor is normally used instead of explicitly creating threads. However the it does not strictly require the execution to be asynchronous. 

### Parents:
- iUnknown

### Methods:
- __iExecutor::GetIsShutdown__() -> _tBool_: Returns true if this executor has been shut down. 
- __iExecutor::GetIsTerminated__() -> _tBool_: Returns true if all tasks have completed following shut down. 
- __iExecutor::Execute__(_iRunnable\*_ aRunnable) -> _ni::tBool_: Executes the given runnable at some time in the future.  The runnable might execute in a new thread, a thread pool, or in the calling thread, at the discretion of the executor implementation.  
- __iExecutor::Submit__(_iRunnable\*_ aRunnable) -> _Ptr<ni::iFuture>_: Executes the given runnable at some time in the future.  The runnable might execute in a new thread, a thread pool, or in the calling thread, at the discretion of the executor implementation.  
- __iExecutor::Shutdown__(_tU32_ anTimeOut) -> _tBool_: Initiates an orderly shutdown in which previously submitted tasks are executed, but no new tasks will be accepted. Blocks until all tasks have completed execution or the timeout occurs. 
- __iExecutor::ShutdownNow__(_tU32_ anTimeOut) -> _tBool_: Attempts to cancel all actively executing tasks, halts the processing of waiting tasks. Blocks until all tasks have completed execution or the timeout occurs. 
- __iExecutor::Update__(_tU32_ anTimeSliceInMs) -> _tU32_: Update the executor. 

## interface ni::iConcurrent


### Parents:
- iUnknown

### Methods:
- __iConcurrent::GetMainThreadID__() -> _tU64_
- __iConcurrent::GetCurrentThreadID__() -> _tU64_
- __iConcurrent::CreateRunnableQueue__(_tU64_ aThreadID, _tU32_ aMaxItems) -> _iRunnableQueue\*_: Create a runnable queue for the specified thread. 
- __iConcurrent::CreateExecutorCooperative__(_tU64_ aThreadID, _tU32_ aMaxItems) -> _iExecutor\*_: Create a cooperative executor. 
- __iConcurrent::CreateExecutorImmediate__() -> _iExecutor\*_: Create an immediate executor. 
- __iConcurrent::CreateExecutorThreadPool__(_tI32_ aNumThreads) -> _iExecutor\*_: Create a threaded executor. 
- __iConcurrent::GetExecutorCPU__() -> _iExecutor\*_: Get the default executor.  The default executor is created with one thread for 2 logical cores, with at least one thread. It should be used for CPU intensive tasks.  
- __iConcurrent::GetExecutorIO__() -> _iExecutor\*_: Get the IO executor.  The IO executor is created with 2 threads per logical core. It should be used for IO bound tasks.  
- __iConcurrent::GetExecutorMain__() -> _iExecutor\*_: Get the cooperative executor bound to the main thread. 
- __iConcurrent::ThreadRun__(_iRunnable\*_ apRunnable) -> _Ptr<iFuture>_: Creates a new thread and run the runnable in it. 
- __iConcurrent::CreateFutureValue__() -> _iFutureValue\*_: Create a future value object. 
- __iConcurrent::CreateMessageDesc__(_iMessageHandler\*_ apHandler, _tU32_ anMsg, _const Var&_ avarA, _const Var&_ avarB) -> _Ptr<iMessageDesc>_: Create a message desc object. 
- __iConcurrent::CreateMessageQueue__(_tU64_ anThreadID, _tU32_ aMaxItems) -> _Ptr<iMessageQueue>_: Create a message queue for the specified thread. 
- __iConcurrent::GetMessageQueue__(_tU64_ anThreadID) -> _Ptr<iMessageQueue>_: Get the message queue associated with the specified thread. 
- __iConcurrent::SendMessage__(_iMessageHandler\*_ apHandler, _tU32_ anMsg, _const Var&_ avarA, _const Var&_ avarB) -> _tBool_: Send a message to the specified message handler. 
- __iConcurrent::QueueMessage__(_iMessageHandler\*_ apHandler, _tU32_ anMsg, _const Var&_ avarA, _const Var&_ avarB) -> _tBool_: Queue a message in the messge queue of the message handler's thread. 

## interface ni::iRunnable
Runnable interface. 

### Parents:
- iUnknown

### Methods:
- __iRunnable::Run__() -> _Var_

## interface ni::iCommandSink
Command sink. 

### Parents:
- iUnknown

### Methods:
- __iCommandSink::GetName__() -> _const achar\*_: Name of the command. 
- __iCommandSink::GetNamespace__() -> _const achar\*_: Namespace of the command. 
- __iCommandSink::GetDescription__() -> _const achar\*_: Description of the command 
- __iCommandSink::OnRun__(_const tStringCVec\*_ avArgs, _iConsole\*_ apConsole) -> _tBool_: Run the command. 

## interface ni::iConsoleSink
Console sink. 

### Parents:
- iUnknown

### Methods:
- __iConsoleSink::OnConsoleSink_NamespaceVariableChanged__(_const achar\*_ aaszName, _const achar\*_ aaszValue) -> _void_: Called when a variable value changed 
- __iConsoleSink::OnConsoleSink_BeforeRunCommand__(_const achar\*_ aaszCmd) -> _tBool_: Called before a console command is ran. 
- __iConsoleSink::OnConsoleSink_AfterRunCommand__(_const achar\*_ aaszCmd) -> _void_: Called after a console command is ran. 
- __iConsoleSink::OnConsoleSink_BeforeRunScript__(_iScriptingHost\*_ apHost, _const achar\*_ aaszCmd) -> _tBool_: Called before a script command is ran. 
- __iConsoleSink::OnConsoleSink_AfterRunScript__(_iScriptingHost\*_ apHost, _const achar\*_ aaszCmd) -> _void_: Called after a script command is ran. 

## interface ni::iConsole
Console interface. 

### Parents:
- iUnknown

### Methods:
- __iConsole::GetSinkList__() -> _tConsoleSinkLst\*_: Get the console sink list. 
- __iConsole::AddNamespace__(_const achar\*_ aszNamespace) -> _void_: Add a namespace. 
- __iConsole::RemoveNamespace__(_const achar\*_ aszNamespace) -> _tBool_: Remove a namespace. Delete all sinks, commands and variables in the namespace. 
- __iConsole::AddVariable__(_const achar\*_ aszName, _const achar\*_ aszValue) -> _tBool_: Add a new string variable. 
- __iConsole::RemoveVariable__(_const achar\*_ aszName) -> _tBool_: Remove a variable. 
- __iConsole::SetVariable__(_const achar\*_ aszName, _const achar\*_ aszValue) -> _tBool_: Set the string value of a variable. 
- __iConsole::GetVariable__(_const achar\*_ aszName) -> _cString_: Get the string value of a variable. 
- __iConsole::CommandExists__(_const achar\*_ aszName) -> _tBool_: Return eTrue if the given command exists. 
- __iConsole::AddCommand__(_iCommandSink\*_ pCmd) -> _tBool_: Add a command in the console. 
- __iConsole::RemoveCommand__(_const achar\*_ aszName) -> _tBool_: Remove a command of the console. 
- __iConsole::GetCommandDescription__(_const achar\*_ aszCommand) -> _cString_: Get the description of a command. 
- __iConsole::RunCommand__(_const achar\*_ aszCommand) -> _tBool_: Run a command. 
- __iConsole::CompleteCommandLine__(_const achar\*_ aaszCmd, _tBool_ abNext) -> _cString_: Complete the given command line. 
- __iConsole::GetNumCommands__() -> _tU32_: Get the number of commands in the queue. 
- __iConsole::PushCommand__(_const achar\*_ aszCommand) -> _tBool_: Queue a command to be run later on. 
- __iConsole::PopCommand__() -> _cString_: Pop a command from the queue. 
- __iConsole::PopAndRunAllCommands__() -> _tU32_: Pop and run all commands in the queue. 

## interface ni::iCommandSink
Command sink. 

### Parents:
- iUnknown

### Methods:
- __iCommandSink::GetName__() -> _const achar\*_: Name of the command. 
- __iCommandSink::GetNamespace__() -> _const achar\*_: Namespace of the command. 
- __iCommandSink::GetDescription__() -> _const achar\*_: Description of the command 
- __iCommandSink::OnRun__(_const tStringCVec\*_ avArgs, _iConsole\*_ apConsole) -> _tBool_: Run the command. 

## interface ni::iCryptoRand
Crypto random number generator. 

### Parents:
- iUnknown

### Methods:
- __iCryptoRand::SetEntropyLength__(_tSize_ anEntropyLen) -> _void_
- __iCryptoRand::SetReseedInterval__(_tInt_ anInterval) -> _void_
- __iCryptoRand::SetPredictionResistance__(_tBool_ abPR) -> _void_
- __iCryptoRand::Reseed__(_iFile\*_ apFile, _tSize_ anAddSize) -> _tBool_
- __iCryptoRand::ReseedRaw__(_const tPtr_ apData, _tSize_ anAddSize) -> _tBool_
- __iCryptoRand::Update__(_iFile\*_ apFile, _tSize_ anAddSize) -> _tBool_
- __iCryptoRand::UpdateRaw__(_const tPtr_ apAdd, _tSize_ anAddSize) -> _tBool_
- __iCryptoRand::RandFile__(_iFile\*_ apFile, _tSize_ anOutLen) -> _tSize_
- __iCryptoRand::RandRaw__(_tPtr_ apOut, _tSize_ anOutLen) -> _tSize_
- __iCryptoRand::RandInt__() -> _tI64_
- __iCryptoRand::RandFloat__() -> _tF64_
- __iCryptoRand::RandUUID__() -> _tUUID_

## interface ni::iCrypto


### Parents:
- iUnknown

### Methods:
- __iCrypto::Digest__(_const achar\*_ aaszData, _const achar\*_ aType, _eRawToStringEncoding_ aEncoding) -> _cString_: Compute the hash of the specified string. Does not include the end zero. 
- __iCrypto::DigestRaw__(_const tPtr_ apData, _tSize_ anSize, _const achar\*_ aType, _eRawToStringEncoding_ aEncoding) -> _cString_: Compute the hash of the specified data. 
- __iCrypto::DigestFile__(_iFile\*_ apFile, _tSize_ anSize, _const achar\*_ aType, _eRawToStringEncoding_ aEncoding) -> _cString_: Compute the hash of the specified data read from the specified file. 
- __iCrypto::CreateRand__() -> _iCryptoRand\*_: Create a new random number generator. 
- __iCrypto::GetRand__() -> _iCryptoRand\*_: Get the default crypto random number generator. 
- __iCrypto::KDFGenSaltBlowfish__(_iCryptoRand\*_ apRand, _tU32_ aRounds) -> _cString_: Generate a salt for KDFCrypt. \see CryptoKDFGenSaltBlowfish 
- __iCrypto::KDFCrypt__(_const achar\*_ aKey, _const achar\*_ aSalt) -> _cString_: Calculates a crypt(3)-style hash of password. \see CryptoKDFCrypt 
- __iCrypto::SigVerify__(_const achar\*_ signatureHex, _const achar\*_ publicKeyPEM, _const achar\*_ payload) -> _tBool_: Verify a RSA signature for a specified payload. 
- __iCrypto::HmacSignature__(_const achar\*_ aAlgo, _ni::iFile\*_ apOutput, _ni::iFile\*_ apPayload, _ni::tSize_ aPayloadSize, _const achar\*_ aSecret, _ni::eRawToStringEncoding_ aSecretFormat) -> _ni::iFile\*_: Generate a keyed hash value using the HMAC method. 

## interface ni::iCryptoHash
Secure hash interface. 

### Parents:
- iUnknown

### Methods:
- __iCryptoHash::GetHashType__() -> _const achar\*_: Get the hash type. 
- __iCryptoHash::GetDigestSize__() -> _tU32_: Get the digest size. 
- __iCryptoHash::Restart__() -> _tBool_: Ends the calculation of the current digest and reset the states for a new calculation. 
- __iCryptoHash::Update__(_iFile\*_ apFile, _tI64_ aSize) -> _tBool_: Adds data to the hash calculation, from the current file position for size bytes. 
- __iCryptoHash::UpdateBlock__(_iFile\*_ apFile, _tI64_ aStart, _tI64_ aSize) -> _tBool_: Adds data to the hash calculation, specifing a data range. 
- __iCryptoHash::UpdateRaw__(_tPtr_ apData, _tSize_ aSize) -> _tBool_: Adds raw data to the hash calculation. 
- __iCryptoHash::FinalString__(_eRawToStringEncoding_ aEncoding) -> _cString_: Ends the calculation of the current digest, return the digest as a string. 
- __iCryptoHash::FinalFile__(_iFile\*_ apOutput) -> _tSize_: Ends the calculation of the current digest, put the digest in the specified file. 
- __iCryptoHash::FinalRaw__(_tPtr_ apData, _tSize_ anSize) -> _tSize_: Ends the calculation of the current digest, put the digest in the specified raw memory. 

## interface ni::iCryptoRand
Crypto random number generator. 

### Parents:
- iUnknown

### Methods:
- __iCryptoRand::SetEntropyLength__(_tSize_ anEntropyLen) -> _void_
- __iCryptoRand::SetReseedInterval__(_tInt_ anInterval) -> _void_
- __iCryptoRand::SetPredictionResistance__(_tBool_ abPR) -> _void_
- __iCryptoRand::Reseed__(_iFile\*_ apFile, _tSize_ anAddSize) -> _tBool_
- __iCryptoRand::ReseedRaw__(_const tPtr_ apData, _tSize_ anAddSize) -> _tBool_
- __iCryptoRand::Update__(_iFile\*_ apFile, _tSize_ anAddSize) -> _tBool_
- __iCryptoRand::UpdateRaw__(_const tPtr_ apAdd, _tSize_ anAddSize) -> _tBool_
- __iCryptoRand::RandFile__(_iFile\*_ apFile, _tSize_ anOutLen) -> _tSize_
- __iCryptoRand::RandRaw__(_tPtr_ apOut, _tSize_ anOutLen) -> _tSize_
- __iCryptoRand::RandInt__() -> _tI64_
- __iCryptoRand::RandFloat__() -> _tF64_
- __iCryptoRand::RandUUID__() -> _tUUID_

## enum ni::eDataTablePropertyType
Data table property types. 

### Values:
- __eDataTablePropertyType_Unknown__ = __eType_Null__
- __eDataTablePropertyType_String__ = __eType_String__
- __eDataTablePropertyType_Int__ = __eType_I64__
- __eDataTablePropertyType_Int32__ = __eType_I32__
- __eDataTablePropertyType_Int64__ = __eType_I64__
- __eDataTablePropertyType_Bool__ = __eType_I8__
- __eDataTablePropertyType_Float__ = __eType_F64__
- __eDataTablePropertyType_Float32__ = __eType_F32__
- __eDataTablePropertyType_Float64__ = __eType_F64__
- __eDataTablePropertyType_Vec2__ = __eType_Vec2f__
- __eDataTablePropertyType_Vec3__ = __eType_Vec3f__
- __eDataTablePropertyType_Vec4__ = __eType_Vec4f__
- __eDataTablePropertyType_Matrix__ = __eType_Matrixf__
- __eDataTablePropertyType_IUnknown__ = __eType_IUnknown|eTypeFlags_Pointer__

## enum ni::eDataTableCopyFlags
Data table copy mode. 

### Values:
- __eDataTableCopyFlags_Default__ = __0__: No special flags, will overwrite properties, and wont be recursive. 
- __eDataTableCopyFlags_Skip__ = __niBit(0)__: If a property is already in the destination it'll be left as is. 
- __eDataTableCopyFlags_Recursive__ = __niBit(1)__: Recursive, children tables will be copied as well (and their own children). 
- __eDataTableCopyFlags_AppendAllChildren__ = __niBit(2)__: All children of the source will be appended. By default children which are in the same sequential order and have the same name as the destination are merged. 
- __eDataTableCopyFlags_UniqueChild__ = __niBit(3)__: Each child data table has a unique name. 
- __eDataTableCopyFlags_Clone__ = __niBit(4)__: Clone all appended children tables. 

## interface ni::iDataTableSink
Data table sink. 

### Parents:
- iUnknown

### Methods:
- __iDataTableSink::OnDataTableSink_SetName__(_iDataTable\*_ apDT) -> _void_: The name of the data table has been set. 
- __iDataTableSink::OnDataTableSink_AddChild__(_iDataTable\*_ apDT, _iDataTable\*_ apChild) -> _void_: A child data table has been added. 
- __iDataTableSink::OnDataTableSink_RemoveChild__(_iDataTable\*_ apDT, _iDataTable\*_ apChild) -> _void_: A child data table has been removed. 
- __iDataTableSink::OnDataTableSink_SetProperty__(_iDataTable\*_ apDT, _tU32_ anProperty) -> _void_: A property has been set. 
- __iDataTableSink::OnDataTableSink_SetMetadata__(_iDataTable\*_ apDT, _tU32_ anProperty) -> _void_: A property's meta-data has been set. 
- __iDataTableSink::OnDataTableSink_RemoveProperty__(_iDataTable\*_ apDT, _tU32_ anProperty) -> _void_: A property is going to be removed. 
- __iDataTableSink::OnDataTableSink_GetProperty__(_iDataTable\*_ apDT, _tU32_ anProperty) -> _Var_: Get the value of the specified property. 

## interface ni::iDataTable
Data table. 

### Parents:
- iUnknown

### Methods:
- __iDataTable::SetName__(_const achar\*_ aaszName) -> _void_: Set the table name. 
- __iDataTable::GetName__() -> _const achar\*_: Get the table name. 
- __iDataTable::GetRoot__() -> _iDataTable\*_: Get the root table. 
- __iDataTable::GetParent__() -> _iDataTable\*_: Get the parent table. 
- __iDataTable::GetPrevSibling__() -> _iDataTable\*_: Get the previous sibling of this data table. 
- __iDataTable::GetNextSibling__() -> _iDataTable\*_: Get the next sibling of this data table. 
- __iDataTable::GetIndex__() -> _tU32_: Get the index of this datatable. 
- __iDataTable::Clone__() -> _iDataTable\*_: Clone this table. 
- __iDataTable::CloneEx__(_tDataTableCopyFlags_ aMode) -> _iDataTable\*_: Clone this table. 
- __iDataTable::Copy__(_const iDataTable\*_ apSource, _tDataTableCopyFlags_ aMode) -> _tBool_: Copy the source table inside this table. 
- __iDataTable::Clear__() -> _void_: Clear the children datatables and properties. 
- __iDataTable::GetHasSink__() -> _tBool_: Check if any sink is inside the data table. 
- __iDataTable::GetSinkList__() -> _tDataTableSinkLst\*_: Get the data table's sink list. 
- __iDataTable::ClearChildren__() -> _void_: Clear the child tables. 
- __iDataTable::GetNumChildren__() -> _tU32_: Get the number of child tables. 
- __iDataTable::GetChildIndex__(_const achar\*_ aaszName) -> _tU32_: Get the index of the first child table with the specified name. 
- __iDataTable::GetChild__(_const achar\*_ aaszName) -> _iDataTable\*_: Get the child table with the specified name. 
- __iDataTable::GetChildFromIndex__(_tU32_ anIndex) -> _iDataTable\*_: Get the child table at the specified index. 
- __iDataTable::AddChild__(_iDataTable\*_ apTable) -> _tBool_: Append a child table. 
- __iDataTable::RemoveChild__(_tU32_ anIndex) -> _tBool_: Remove the child table at the specified index. 
- __iDataTable::ClearProperties__() -> _void_: Clear the properties. 
- __iDataTable::RemoveProperty__(_const achar\*_ aaszName) -> _tBool_: Remove the property with the specified name. 
- __iDataTable::RemovePropertyFromIndex__(_tU32_ anIndex) -> _tBool_: Remove the property at the specified index. 
- __iDataTable::GetNumProperties__() -> _tU32_: Get the number of properties in the table. 
- __iDataTable::GetPropertyIndex__(_const achar\*_ aaszName) -> _tU32_: Get the index of the specified property. 
- __iDataTable::GetPropertyName__(_tU32_ anIndex) -> _const achar\*_: Get the name of the property at the specified index. 
- __iDataTable::GetPropertyType__(_const achar\*_ aaszProp) -> _eDataTablePropertyType_: Get the type of a property. 
- __iDataTable::GetPropertyTypeFromIndex__(_tU32_ anIndex) -> _eDataTablePropertyType_: Get the type of the property at the specified index. 
- __iDataTable::HasProperty__(_const achar\*_ aaszName) -> _tBool_: Check whether the data table has a property with the specified name. 
- __iDataTable::SetMetadata__(_const achar\*_ aaszProp, _iHString\*_ ahspData) -> _tBool_: Set a property meta-data. 
- __iDataTable::GetMetadata__(_const achar\*_ aaszProp) -> _Ptr<iHString>_: Get a property meta-data. 
- __iDataTable::SetMetadataFromIndex__(_tU32_ anIndex, _iHString\*_ ahspData) -> _tBool_: Set a property meta-data. 
- __iDataTable::GetMetadataFromIndex__(_tU32_ anIndex) -> _Ptr<iHString>_: Get a property meta-data. 
- __iDataTable::GetVar__(_const achar\*_ aaszName) -> _Var_: Get a Var property. 
- __iDataTable::GetVarFromIndex__(_tU32_ anIndex) -> _Var_: Get a Var property from the specified index. 
- __iDataTable::GetVarDefault__(_const achar\*_ aaszName, _const Var&_ v) -> _Var_: Get a Var property. 
- __iDataTable::GetString__(_const achar\*_ aaszName) -> _cString_: Get a String property. 
- __iDataTable::GetStringFromIndex__(_tU32_ anIndex) -> _cString_: Get a String property from the specified index. 
- __iDataTable::GetStringDefault__(_const achar\*_ aaszName, _const achar\*_ v) -> _cString_: Get a String property. 
- __iDataTable::GetHString__(_const achar\*_ aaszName) -> _Ptr<iHString>_: Get a HString property. 
- __iDataTable::GetHStringFromIndex__(_tU32_ anIndex) -> _Ptr<iHString>_: Get a HString property from the specified index. 
- __iDataTable::GetHStringDefault__(_const achar\*_ aaszName, _iHString\*_ v) -> _Ptr<iHString>_: Get a HString property. 
- __iDataTable::GetInt__(_const achar\*_ aaszName) -> _tI64_: Get a Int property. 
- __iDataTable::GetIntFromIndex__(_tU32_ anIndex) -> _tI64_: Get a Int property from the specified index. 
- __iDataTable::GetIntDefault__(_const achar\*_ aaszName, _tI64_ v) -> _tI64_: Get a Int property. 
- __iDataTable::GetBool__(_const achar\*_ aaszName) -> _tBool_: Get a Bool property. 
- __iDataTable::GetBoolFromIndex__(_tU32_ anIndex) -> _tBool_: Get a Bool property from the specified index. 
- __iDataTable::GetBoolDefault__(_const achar\*_ aaszName, _tBool_ v) -> _tBool_: Get a Bool property. 
- __iDataTable::GetFloat__(_const achar\*_ aaszName) -> _tF64_: Get a Float property. 
- __iDataTable::GetFloatFromIndex__(_tU32_ anIndex) -> _tF64_: Get a Float property from the specified index. 
- __iDataTable::GetFloatDefault__(_const achar\*_ aaszName, _tF64_ v) -> _tF64_: Get a Float property. 
- __iDataTable::GetVec2__(_const achar\*_ aaszName) -> _sVec2f_: Get a Vec2 property. 
- __iDataTable::GetVec2FromIndex__(_tU32_ anIndex) -> _sVec2f_: Get a Vec2 property from the specified index. 
- __iDataTable::GetVec2Default__(_const achar\*_ aaszName, _const sVec2f&_ v) -> _sVec2f_: Get a Vec2 property. 
- __iDataTable::GetVec3__(_const achar\*_ aaszName) -> _sVec3f_: Get a Vec3 property. 
- __iDataTable::GetVec3FromIndex__(_tU32_ anIndex) -> _sVec3f_: Get a Vec3 property from the specified index. 
- __iDataTable::GetVec3Default__(_const achar\*_ aaszName, _const sVec3f&_ v) -> _sVec3f_: Get a Vec3 property. 
- __iDataTable::GetVec4__(_const achar\*_ aaszName) -> _sVec4f_: Get a Vec4 property. 
- __iDataTable::GetVec4FromIndex__(_tU32_ anIndex) -> _sVec4f_: Get a Vec4 property from the specified index. 
- __iDataTable::GetVec4Default__(_const achar\*_ aaszName, _const sVec4f&_ v) -> _sVec4f_: Get a Vec4 property. 
- __iDataTable::GetCol3__(_const achar\*_ aaszName) -> _sVec3f_: Get a Color3 property. 
- __iDataTable::GetCol3FromIndex__(_tU32_ anIndex) -> _sVec3f_: Get a Color3 property from the specified index. 
- __iDataTable::GetCol4__(_const achar\*_ aaszName) -> _sVec4f_: Get a Color4 property. 
- __iDataTable::GetCol4FromIndex__(_tU32_ anIndex) -> _sVec4f_: Get a Color4 property from the specified index. 
- __iDataTable::GetMatrix__(_const achar\*_ aaszName) -> _sMatrixf_: Get a Matrix property. 
- __iDataTable::GetMatrixFromIndex__(_tU32_ anIndex) -> _sMatrixf_: Get a Matrix property from the specified index. 
- __iDataTable::GetMatrixDefault__(_const achar\*_ aaszName, _const sMatrixf&_ v) -> _sMatrixf_: Get a Matrix property. 
- __iDataTable::GetIUnknown__(_const achar\*_ aaszName) -> _iUnknown\*_: Get a IUnknown property. 
- __iDataTable::GetIUnknownFromIndex__(_tU32_ anIndex) -> _iUnknown\*_: Get a IUnknown property from the specified index. 
- __iDataTable::GetIUnknownDefault__(_const achar\*_ aaszName, _iUnknown\*_ v) -> _iUnknown\*_: Get a IUnknown property. 
- __iDataTable::GetEnum__(_const achar\*_ aaszName, _const sEnumDef\*_ apEnumDef, _tEnumToStringFlags_ aFlags) -> _tU32_: Get a Enum property. 
- __iDataTable::GetEnumFromIndex__(_tU32_ anIndex, _const sEnumDef\*_ apEnumDef, _tEnumToStringFlags_ aFlags) -> _tU32_: Get a Enum property from the specified index. 
- __iDataTable::GetEnumDefault__(_const achar\*_ aaszName, _const sEnumDef\*_ apEnumDef, _tEnumToStringFlags_ aFlags, _tU32_ v) -> _tU32_: Get a Enum property. 
- __iDataTable::SetVar__(_const achar\*_ aaszName, _const Var&_ v) -> _tU32_: Set a Var property. 
- __iDataTable::SetVarFromIndex__(_tU32_ anIndex, _const Var&_ v) -> _void_: Set a Var property from the specified index. 
- __iDataTable::SetString__(_const achar\*_ aaszName, _const achar\*_ v) -> _tU32_: Set a String property. 
- __iDataTable::SetStringFromIndex__(_tU32_ anIndex, _const achar\*_ v) -> _void_: Set a String property from the specified index. 
- __iDataTable::SetHString__(_const achar\*_ aaszName, _iHString\*_ v) -> _tU32_: Set a HString property. 
- __iDataTable::SetHStringFromIndex__(_tU32_ anIndex, _iHString\*_ v) -> _void_: Set a HString property from the specified index. 
- __iDataTable::SetInt__(_const achar\*_ aaszName, _tI64_ v) -> _tU32_: Set a Int property. 
- __iDataTable::SetIntFromIndex__(_tU32_ anIndex, _tI64_ v) -> _void_: Set a Int property from the specified index. 
- __iDataTable::SetBool__(_const achar\*_ aaszName, _tBool_ v) -> _tU32_: Set a Bool property. 
- __iDataTable::SetBoolFromIndex__(_tU32_ anIndex, _tBool_ v) -> _void_: Set a Bool property from the specified index. 
- __iDataTable::SetFloat__(_const achar\*_ aaszName, _tF64_ v) -> _tU32_: Set a Float property. 
- __iDataTable::SetFloatFromIndex__(_tU32_ anIndex, _tF64_ v) -> _void_: Set a Float property from the specified index. 
- __iDataTable::SetVec2__(_const achar\*_ aaszName, _const sVec2f&_ v) -> _tU32_: Set a Vec2 property. 
- __iDataTable::SetVec2FromIndex__(_tU32_ anIndex, _const sVec2f&_ v) -> _void_: Set a Vec2 property from the specified index. 
- __iDataTable::SetVec3__(_const achar\*_ aaszName, _const sVec3f&_ v) -> _tU32_: Set a Vec3 property. 
- __iDataTable::SetVec3FromIndex__(_tU32_ anIndex, _const sVec3f&_ v) -> _void_: Set a Vec3 property from the specified index. 
- __iDataTable::SetVec4__(_const achar\*_ aaszName, _const sVec4f&_ v) -> _tU32_: Set a Vec4 property. 
- __iDataTable::SetVec4FromIndex__(_tU32_ anIndex, _const sVec4f&_ v) -> _void_: Set a Vec4 property from the specified index. 
- __iDataTable::SetMatrix__(_const achar\*_ aaszName, _const sMatrixf&_ v) -> _tU32_: Set a Matrix property. 
- __iDataTable::SetMatrixFromIndex__(_tU32_ anIndex, _const sMatrixf&_ v) -> _void_: Set a Matrix property from the specified index. 
- __iDataTable::SetIUnknown__(_const achar\*_ aaszName, _iUnknown\*_ v) -> _tU32_: Set a IUnknown property. 
- __iDataTable::SetIUnknownFromIndex__(_tU32_ anIndex, _iUnknown\*_ v) -> _void_: Set a IUnknown property from the specified index. 
- __iDataTable::SetEnum__(_const achar\*_ aaszName, _const sEnumDef\*_ apEnumDef, _tEnumToStringFlags_ aFlags, _tU32_ anVal) -> _tU32_: Set an Enum property. 
- __iDataTable::SetEnumFromIndex__(_tU32_ anIndex, _const sEnumDef\*_ apEnumDef, _tEnumToStringFlags_ aFlags, _tU32_ anVal) -> _void_: Set an Enum property from the specified index. 
- __iDataTable::SetRawVar__(_const achar\*_ aaszName, _const Var&_ v) -> _tU32_: Set a Var property without ever calling the callback sink. 
- __iDataTable::SetRawVarFromIndex__(_tU32_ anIndex, _const Var&_ v) -> _void_: Set a Var property from the specified index without ever calling the callback sink. 
- __iDataTable::GetRawVar__(_const achar\*_ aaszName) -> _Var_: Get a Var property without ever calling the callback sink. 
- __iDataTable::GetRawVarFromIndex__(_tU32_ anIndex) -> _Var_: Get a Var property from the specified index without ever calling the callback sink.. 
- __iDataTable::GetRawVarDefault__(_const achar\*_ aaszName, _const Var&_ v) -> _Var_: Get a Var property without ever calling the callback sink. 
- __iDataTable::NewVarFromPath__(_const achar\*_ aPath, _const Var&_ aVal) -> _tBool_: Set a new variant property. Property name being a path. 
- __iDataTable::SetVarFromPath__(_const achar\*_ aPath, _const Var&_ aVal) -> _tBool_: Set a variant property. Property name being a path. Return false if the path doesnt exist. 
- __iDataTable::GetVarFromPath__(_const achar\*_ aPath, _const Var&_ aDefault) -> _Var_: Get a variant property. Property name being a path. 

## interface ni::iDataTableReadStack
Data table read stack interface. 

### Parents:
- iUnknown

### Methods:
- __iDataTableReadStack::GetTop__() -> _iDataTable\*_: Get the top of the data table stack. 
- __iDataTableReadStack::GetName__() -> _const achar\*_: Get the name of the top data table. 
- __iDataTableReadStack::GetNumChildren__() -> _tU32_: Get the number of child data table of the top data table. 
- __iDataTableReadStack::PushChild__(_tU32_ anIndex) -> _tBool_: Push the specified child data table on top of the stack. Push a NULL data table if it doesn't exists. 
- __iDataTableReadStack::PushChildFail__(_tU32_ anIndex) -> _tBool_: Push the specified child data table on top of the stack. Do not push a data table if it doesn't exists and returns eFalse. 
- __iDataTableReadStack::Push__(_const achar\*_ aaszName) -> _tBool_: Push the specified data table on top of the stack. Push a NULL data table if it doesn't exists. 
- __iDataTableReadStack::PushFail__(_const achar\*_ aaszName) -> _tBool_: Push the specified data table on top of the stack. Do not push a data table if it doesn't exists and returns eFalse. 
- __iDataTableReadStack::PushEx__(_const achar\*_ aaszName, _const achar\*_ aaszProp, _const achar\*_ aaszVal) -> _tBool_: Push the specified data table on top of the stack. Push a NULL data table if it doesn't exists. 
- __iDataTableReadStack::PushFailEx__(_const achar\*_ aaszName, _const achar\*_ aaszProp, _const achar\*_ aaszVal) -> _tBool_: Push the specified data table on top of the stack. Do not push a data table if it doesn't exists and returns eFalse. 
- __iDataTableReadStack::Pop__() -> _tBool_: Pop the top data table. 
- __iDataTableReadStack::HasProperty__(_const achar\*_ aaszName) -> _tBool_: Check whether the top data table has a property with the specified name. 
- __iDataTableReadStack::RemoveProperty__(_const achar\*_ aaszName) -> _tBool_: Remove a property of the top data table. 
- __iDataTableReadStack::GetString__(_const achar\*_ aaszName) -> _cString_: Get a String of the top data table. 
- __iDataTableReadStack::GetStringDefault__(_const achar\*_ aaszName, _const achar\*_ v) -> _cString_: Get a String of the top data table. 
- __iDataTableReadStack::GetHString__(_const achar\*_ aaszName) -> _Ptr<iHString>_: Get a HString of the top data table. 
- __iDataTableReadStack::GetHStringDefault__(_const achar\*_ aaszName, _iHString\*_ v) -> _Ptr<iHString>_: Get a HString of the top data table. 
- __iDataTableReadStack::GetInt__(_const achar\*_ aaszName) -> _tI64_: Get a Int of the top data table. 
- __iDataTableReadStack::GetIntDefault__(_const achar\*_ aaszName, _tI64_ v) -> _tI64_: Get a Int of the top data table. 
- __iDataTableReadStack::GetBool__(_const achar\*_ aaszName) -> _tBool_: Get a Bool of the top data table. 
- __iDataTableReadStack::GetBoolDefault__(_const achar\*_ aaszName, _tBool_ v) -> _tBool_: Get a Bool of the top data table. 
- __iDataTableReadStack::GetFloat__(_const achar\*_ aaszName) -> _tF64_: Get a Float of the top data table. 
- __iDataTableReadStack::GetFloatDefault__(_const achar\*_ aaszName, _tF64_ v) -> _tF64_: Get a Float of the top data table. 
- __iDataTableReadStack::GetVec2__(_const achar\*_ aaszName) -> _sVec2f_: Get a Vec2 of the top data table. 
- __iDataTableReadStack::GetVec2Default__(_const achar\*_ aaszName, _const sVec2f&_ v) -> _sVec2f_: Get a Vec2 of the top data table. 
- __iDataTableReadStack::GetVec3__(_const achar\*_ aaszName) -> _sVec3f_: Get a Vec3 of the top data table. 
- __iDataTableReadStack::GetVec3Default__(_const achar\*_ aaszName, _const sVec3f&_ v) -> _sVec3f_: Get a Vec3 of the top data table. 
- __iDataTableReadStack::GetVec4__(_const achar\*_ aaszName) -> _sVec4f_: Get a Vec4 of the top data table. 
- __iDataTableReadStack::GetVec4Default__(_const achar\*_ aaszName, _const sVec4f&_ v) -> _sVec4f_: Get a Vec4 of the top data table. 
- __iDataTableReadStack::GetCol3__(_const achar\*_ aaszName) -> _sVec3f_: Get a Color3 of the top data table. 
- __iDataTableReadStack::GetCol4__(_const achar\*_ aaszName) -> _sVec4f_: Get a Color4 of the top data table. 
- __iDataTableReadStack::GetMatrix__(_const achar\*_ aaszName) -> _sMatrixf_: Get a Matrix of the top data table. 
- __iDataTableReadStack::GetMatrixDefault__(_const achar\*_ aaszName, _const sMatrixf&_ v) -> _sMatrixf_: Get a Matrix of the top data table. 
- __iDataTableReadStack::GetIUnknown__(_const achar\*_ aaszName) -> _iUnknown\*_: Get a IUnknown of the top data table. 
- __iDataTableReadStack::GetIUnknownDefault__(_const achar\*_ aaszName, _iHString\*_ v) -> _iUnknown\*_: Get a IUnknown of the top data table. 
- __iDataTableReadStack::GetEnum__(_const achar\*_ aaszName, _const sEnumDef\*_ apEnumDef, _tEnumToStringFlags_ aFlags) -> _tU32_: Get a Enum of the top data table. 
- __iDataTableReadStack::GetEnumDefault__(_const achar\*_ aaszName, _const sEnumDef\*_ apEnumDef, _tEnumToStringFlags_ aFlags, _tU32_ v) -> _tU32_: Get a Enum of the top data table. 
- __iDataTableReadStack::GetMetadata__(_const achar\*_ aaszProp) -> _Ptr<iHString>_: Get a property meta-data. 

## interface ni::iDataTableWriteStack
Data table write stack interface. 

### Parents:
- iUnknown

### Methods:
- __iDataTableWriteStack::GetTop__() -> _iDataTable\*_: Get the top of the data table stack. 
- __iDataTableWriteStack::SetName__(_const achar\*_ aaszName) -> _void_: Set the name of the top data table. 
- __iDataTableWriteStack::GetName__() -> _const achar\*_: Get the name of the top data table. 
- __iDataTableWriteStack::GetNumChildren__() -> _tU32_: Get the number of child data table of the top data table. 
- __iDataTableWriteStack::PushChild__(_tU32_ anIndex) -> _tBool_: Push the specified child data table on top of the stack. Push a NULL data table if it doesn't exists. 
- __iDataTableWriteStack::PushChildFail__(_tU32_ anIndex) -> _tBool_: Push the specified child data table on top of the stack. Do not push a data table if it doesn't exists and returns eFalse. 
- __iDataTableWriteStack::Push__(_const achar\*_ aaszName) -> _tBool_: Push a data table with the given name on top of the stack. If a child data table with the given name doesn't exists, creates it. 
- __iDataTableWriteStack::PushFail__(_const achar\*_ aaszName) -> _tBool_: Push a data table with the given name on top of the stack. If a child data table with the given name doesn't exists, return eFalse. 
- __iDataTableWriteStack::PushNew__(_const achar\*_ aaszName) -> _tBool_: Push a new data table on top of the stack. 
- __iDataTableWriteStack::PushAppend__(_iDataTable\*_ apDT) -> _tBool_: Append the given data table, and push it on top of the stack. 
- __iDataTableWriteStack::PushEx__(_const achar\*_ aaszName, _const achar\*_ aaszProp, _const achar\*_ aaszVal) -> _tBool_: Push the specified data table on top of the stack. Push a NULL data table if it doesn't exists. 
- __iDataTableWriteStack::PushFailEx__(_const achar\*_ aaszName, _const achar\*_ aaszProp, _const achar\*_ aaszVal) -> _tBool_: Push the specified data table on top of the stack. Do not push a data table if it doesn't exists and returns eFalse. 
- __iDataTableWriteStack::Pop__() -> _tBool_: Pop the top data table. 
- __iDataTableWriteStack::HasProperty__(_const achar\*_ aaszName) -> _tBool_: Check whether the top data table has a property with the specified name. 
- __iDataTableWriteStack::RemoveProperty__(_const achar\*_ aaszName) -> _tBool_: Remove a property of the top data table. 
- __iDataTableWriteStack::SetString__(_const achar\*_ aaszName, _const achar\*_ v) -> _void_: Set a String in the top data table. 
- __iDataTableWriteStack::SetHString__(_const achar\*_ aaszName, _iHString\*_ v) -> _void_: Set a HString in the top data table. 
- __iDataTableWriteStack::SetInt__(_const achar\*_ aaszName, _tI64_ v) -> _void_: Set a Int in the top data table. 
- __iDataTableWriteStack::SetBool__(_const achar\*_ aaszName, _tBool_ v) -> _void_: Set a Bool in the top data table. 
- __iDataTableWriteStack::SetFloat__(_const achar\*_ aaszName, _tF64_ v) -> _void_: Set a Float in the top data table. 
- __iDataTableWriteStack::SetVec2__(_const achar\*_ aaszName, _const sVec2f&_ v) -> _void_: Set a Vec2 in the top data table. 
- __iDataTableWriteStack::SetVec3__(_const achar\*_ aaszName, _const sVec3f&_ v) -> _void_: Set a Vec3 in the top data table. 
- __iDataTableWriteStack::SetVec4__(_const achar\*_ aaszName, _const sVec4f&_ v) -> _void_: Set a Vec4 in the top data table. 
- __iDataTableWriteStack::SetMatrix__(_const achar\*_ aaszName, _const sMatrixf&_ v) -> _void_: Set a Matrix in the top data table. 
- __iDataTableWriteStack::SetIUnknown__(_const achar\*_ aaszName, _iUnknown\*_ v) -> _void_: Set a IUnknown in the top data table. 
- __iDataTableWriteStack::SetEnum__(_const achar\*_ aaszName, _const sEnumDef\*_ apEnumDef, _tEnumToStringFlags_ aFlags, _tU32_ anVal) -> _void_: Set a Enum in the top data table. 
- __iDataTableWriteStack::SetMetadata__(_const achar\*_ aaszProp, _iHString\*_ ahspData) -> _tBool_: Set a property meta-data. 

## enum ni::eDataTablePropertyType
Data table property types. 

### Values:
- __eDataTablePropertyType_Unknown__ = __eType_Null__
- __eDataTablePropertyType_String__ = __eType_String__
- __eDataTablePropertyType_Int__ = __eType_I64__
- __eDataTablePropertyType_Int32__ = __eType_I32__
- __eDataTablePropertyType_Int64__ = __eType_I64__
- __eDataTablePropertyType_Bool__ = __eType_I8__
- __eDataTablePropertyType_Float__ = __eType_F64__
- __eDataTablePropertyType_Float32__ = __eType_F32__
- __eDataTablePropertyType_Float64__ = __eType_F64__
- __eDataTablePropertyType_Vec2__ = __eType_Vec2f__
- __eDataTablePropertyType_Vec3__ = __eType_Vec3f__
- __eDataTablePropertyType_Vec4__ = __eType_Vec4f__
- __eDataTablePropertyType_Matrix__ = __eType_Matrixf__
- __eDataTablePropertyType_IUnknown__ = __eType_IUnknown|eTypeFlags_Pointer__

## interface ni::iDeviceResource
Device resource interface. 

### Parents:
- iUnknown

### Methods:
- __iDeviceResource::GetDeviceResourceName__() -> _iHString\*_: Get the resource's name. 
- __iDeviceResource::HasDeviceResourceBeenReset__(_tBool_ abClearFlag) -> _tBool_: Check whether the device resource has just been reset. 
- __iDeviceResource::ResetDeviceResource__() -> _tBool_: Reset the device resource. 
- __iDeviceResource::Bind__(_iUnknown\*_ apDevice) -> _iDeviceResource\*_: Called when the resource is going to be used by the device. 

## interface ni::iDeviceResourceManager
Device resource manager interface. 

### Parents:
- iUnknown

### Remarks:
- When the inteface is released it invalidates all the device resources contained. 

### Methods:
- __iDeviceResourceManager::GetType__() -> _iHString\*_: Resource type. 
- __iDeviceResourceManager::Clear__() -> _void_: Clear the resource manager and invalidate all resources. 
- __iDeviceResourceManager::GetSize__() -> _tU32_: Get the number of resources in the manager. 
- __iDeviceResourceManager::GetFromName__(_iHString\*_ ahspName) -> _iDeviceResource\*_: Get a resource in the manager. 
- __iDeviceResourceManager::GetFromIndex__(_tU32_ anIndex) -> _iDeviceResource\*_: Get the resource at the specified index. 
- __iDeviceResourceManager::Register__(_iDeviceResource\*_ apRes) -> _tBool_: Register a resource in the manager. 
- __iDeviceResourceManager::Unregister__(_iDeviceResource\*_ apRes) -> _tBool_: Unregister a resource in the manager. 

## interface ni::iDeviceResource
Device resource interface. 

### Parents:
- iUnknown

### Methods:
- __iDeviceResource::GetDeviceResourceName__() -> _iHString\*_: Get the resource's name. 
- __iDeviceResource::HasDeviceResourceBeenReset__(_tBool_ abClearFlag) -> _tBool_: Check whether the device resource has just been reset. 
- __iDeviceResource::ResetDeviceResource__() -> _tBool_: Reset the device resource. 
- __iDeviceResource::Bind__(_iUnknown\*_ apDevice) -> _iDeviceResource\*_: Called when the resource is going to be used by the device. 

## enum ni::eExpressionVariableType
Expression variables types. 

### Values:
- __eExpressionVariableType_Float__ = __0__: Real number variable type. Constructors: -x, x, x.y, -x.y 
- __eExpressionVariableType_Vec2__ = __1__: 2D vector variable type. Constructors: Vec2() 
- __eExpressionVariableType_Vec3__ = __2__: 3D vector variable type. Constructors: Vec3(), RGB() 
- __eExpressionVariableType_Vec4__ = __3__: 4D vector variable type. Constructors: Vec4(), RGBA(), Quat(), Plane() 
- __eExpressionVariableType_Matrix__ = __4__: Matrix variable type. Constructors: Matrix() 
- __eExpressionVariableType_String__ = __5__: String type. Constructors: "string", 'string' 

## enum ni::eExpressionVariableFlags
Expression variables flags. 

### Values:
- __eExpressionVariableFlags_Default__ = __0__: Default flags value. 
- __eExpressionVariableFlags_Reserved__ = __niBit(0)__: Variable is reserved. 
- __eExpressionVariableFlags_Constant__ = __niBit(1)__: Constant variable, read-only. 
- __eExpressionVariableFlags_Color__ = __niBit(2)__: Variable is the result of a color function. 
- __eExpressionVariableFlags_Quat__ = __niBit(3)__: Variable is the result of a quaternion function. 

## interface ni::iExpressionVariable
Expression variable interface. 

### Parents:
- iUnknown

### Methods:
- __iExpressionVariable::SetName__(_iHString\*_ ahspString) -> _void_: Set the variable name. 
- __iExpressionVariable::GetName__() -> _iHString\*_: Get the variable name. 
- __iExpressionVariable::Copy__(_const iExpressionVariable\*_ apVar) -> _tBool_: Copy the specified variable. 
- __iExpressionVariable::Clone__() -> _iExpressionVariable\*_: Clone this variable. 
- __iExpressionVariable::GetType__() -> _eExpressionVariableType_: Get the variable's type. 
- __iExpressionVariable::GetFlags__() -> _tExpressionVariableFlags_: Get the variable's flags. 
- __iExpressionVariable::SetFloat__(_tF64_ aV) -> _void_: Set the float value of the variable. 
- __iExpressionVariable::GetFloat__() -> _tF64_: Get the float value of the variable. 
- __iExpressionVariable::SetVec2__(_const sVec2f&_ aV) -> _void_: Set the vector2 value of the variable. 
- __iExpressionVariable::GetVec2__() -> _sVec2f_: Get the vector2 value of the variable. 
- __iExpressionVariable::SetVec3__(_const sVec3f&_ aV) -> _void_: Get the vector3 value of the variable. 
- __iExpressionVariable::GetVec3__() -> _sVec3f_: Get the vector3 value of the variable. 
- __iExpressionVariable::SetVec4__(_const sVec4f&_ aV) -> _void_: Get the vector4 value of the variable. 
- __iExpressionVariable::GetVec4__() -> _sVec4f_: Get the vector4 value of the variable. 
- __iExpressionVariable::SetMatrix__(_const sMatrixf&_ aV) -> _void_: Get the matrix value of the variable. 
- __iExpressionVariable::GetMatrix__() -> _sMatrixf_: Get the matrix value of the variable. 
- __iExpressionVariable::SetString__(_const cString&_ aV) -> _void_: Get the string value of the variable. 
- __iExpressionVariable::GetString__() -> _cString_: Get the string value of the variable. 

## interface ni::iExpression
Expression interface. 

### Parents:
- iUnknown

### Methods:
- __iExpression::Eval__() -> _Ptr<iExpressionVariable>_: Eval the expression and returns the result. 
- __iExpression::GetEvalResult__() -> _iExpressionVariable\*_: Get the result returned by the last Eval. 
- __iExpression::GetContext__() -> _iExpressionContext\*_: Get the context. 

## interface ni::iExpressionURLResolver
Expression URL resolver interface. 

### Parents:
- iUnknown

### Methods:
- __iExpressionURLResolver::ResolveURL__(_const achar\*_ aURL) -> _Var_

## interface ni::iExpressionContext
Expression context. 

### Parents:
- iUnknown

### Methods:
- __iExpressionContext::GetParentContext__() -> _iExpressionContext\*_: Get the parent context. 
- __iExpressionContext::CreateContext__() -> _iExpressionContext\*_: Create a child context. 
- __iExpressionContext::CreateVariable__(_const achar\*_ aaszName, _eExpressionVariableType_ aType, _tExpressionVariableFlags_ aFlags) -> _iExpressionVariable\*_: Create a new variable. 
- __iExpressionContext::CreateVariableFromExpr__(_const achar\*_ aaszName, _const achar\*_ aaszExpr, _tExpressionVariableFlags_ aFlags) -> _iExpressionVariable\*_: Create a variable from an expression. 
- __iExpressionContext::CreateVariableFromRunnable__(_const achar\*_ aaszName, _eExpressionVariableType_ aType, _iRunnable\*_ apRunnable, _tExpressionVariableFlags_ aFlags) -> _iExpressionVariable\*_: Create a variable whos value is fetched from a runnable. 
- __iExpressionContext::CreateVariableFromVar__(_const achar\*_ aaszName, _const Var&_ aInitialValue, _tExpressionVariableFlags_ aFlags) -> _iExpressionVariable\*_: Create a variable initialized with the value of the specified variant. 
- __iExpressionContext::AddVariable__(_iExpressionVariable\*_ apVar) -> _tBool_: Add a variable to the expression context. 
- __iExpressionContext::RemoveVariable__(_iExpressionVariable\*_ apVariable) -> _tBool_: Remove a variable from the expression context. 
- __iExpressionContext::FindVariable__(_iHString\*_ ahspName) -> _iExpressionVariable\*_: Find the variable with the specified name. 
- __iExpressionContext::CreateExpression__(_const achar\*_ aaszExpr) -> _iExpression\*_: Create a new expression. 
- __iExpressionContext::Eval__(_const achar\*_ aaszExpr) -> _Ptr<iExpressionVariable>_: Evaluate an expression. 
- __iExpressionContext::GetUnknownSymbols__(_const achar\*_ aaszExpr, _tStringCVec\*_ apList) -> _tBool_: Get the unknown symbols into the specified expression. 
- __iExpressionContext::SetGlobalEnumSearch__(_tBool_ abEnabled) -> _void_: Allows the parser to search in all registered modules enumerations. 
- __iExpressionContext::GetGlobalEnumSearch__() -> _tBool_: Get the global enum search status. 
- __iExpressionContext::AddEnumDef__(_const sEnumDef\*_ apEnumDef) -> _tBool_: Add an enumeration definition. 
- __iExpressionContext::GetEnumDef__(_const achar\*_ aaszName) -> _const sEnumDef\*_: Get the specified enumeration. 
- __iExpressionContext::SetDefaultEnumDef__(_const sEnumDef\*_ apEnumDef) -> _void_: Set the default enumeration definition. 
- __iExpressionContext::GetDefaultEnumDef__() -> _const sEnumDef\*_: Get the default enumeration definition. 
- __iExpressionContext::GetEnumValueString__(_tU32_ anValue) -> _cString_: Get an enumeration value string. 
- __iExpressionContext::GetEnumFlagsString__(_tU32_ anValue) -> _cString_: Get an enumeration flags string. 
- __iExpressionContext::RegisterURLResolver__(_const achar\*_ aaszProtocol, _iExpressionURLResolver\*_ apResolver) -> _tBool_
- __iExpressionContext::UnregisterURLResolver__(_const achar\*_ aaszProtocol) -> _tBool_
- __iExpressionContext::FindURLResolver__(_const achar\*_ aaszProtocol) -> _iExpressionURLResolver\*_

## enum ni::eExpressionVariableType
Expression variables types. 

### Values:
- __eExpressionVariableType_Float__ = __0__: Real number variable type. Constructors: -x, x, x.y, -x.y 
- __eExpressionVariableType_Vec2__ = __1__: 2D vector variable type. Constructors: Vec2() 
- __eExpressionVariableType_Vec3__ = __2__: 3D vector variable type. Constructors: Vec3(), RGB() 
- __eExpressionVariableType_Vec4__ = __3__: 4D vector variable type. Constructors: Vec4(), RGBA(), Quat(), Plane() 
- __eExpressionVariableType_Matrix__ = __4__: Matrix variable type. Constructors: Matrix() 
- __eExpressionVariableType_String__ = __5__: String type. Constructors: "string", 'string' 

## enum ni::eTextEncodingFormat
Text encoding formats. 

### Values:
- __eTextEncodingFormat_Unknown__ = __eInvalidHandle__: Text encoding format header is unknown/invalid. 
- __eTextEncodingFormat_UTF8__ = __0__: UTF8 encoding. 
- __eTextEncodingFormat_UTF8BOM__ = __1__: UTF8 encoding, with explicit BOM. 
- __eTextEncodingFormat_UTF16LE__ = __2__: UTF16 Little Endian. 
- __eTextEncodingFormat_UTF16BE__ = __3__: UTF16 Big Endian. 
- __eTextEncodingFormat_UTF32LE__ = __4__: UTF32 Little Endian. 
- __eTextEncodingFormat_UTF32BE__ = __5__: UTF32 Big Endian. 
- __eTextEncodingFormat_BitStream__ = __6__: Bit stream encoding. 
- __eTextEncodingFormat_Unicode__ = __eTextEncodingFormat_UTF32LE__
- __eTextEncodingFormat_Native__ = __eTextEncodingFormat_UTF8__: Native encoding. 

## interface ni::iFileEnumSink
Callback interface used by the FileEnum() method of the iLang interface. 

### Parents:
- iUnknown

### Methods:
- __iFileEnumSink::OnFound__(_const achar\*_ aszFile, _tU32_ aFileAttrs, _tI64_ anFileSize) -> _tBool_

## variable ni::kfccSerializedObject

## enum ni::eFileFlags
File flags. 

### Values:
- __eFileFlags_Read__ = __niBit(0)__: File can be read. 
- __eFileFlags_Write__ = __niBit(1)__: File can be written. 
- __eFileFlags_Append__ = __niBit(2)__: File opened in append mode. 
- __eFileFlags_PartialRead__ = __niBit(16)__: The previous read operation read past the end of the file (could not read all bytes). 
- __eFileFlags_PartialWrite__ = __niBit(17)__: The previous write operation could not write all bytes to the file. 
- __eFileFlags_Encoder__ = __niBit(18)__: The file is an encoder/decoder (compressor/decompressor/encryptor/decryptor). 
- __eFileFlags_NoSeek__ = __niBit(19)__: Seek, SeekSet and SeekEnd are not supported and will always fail. 
- __eFileFlags_Dummy__ = __niBit(20)__: The file is a dummy, it wont really read or write anything. 
- __eFileFlags_Stream__ = __niBit(21)__: The file is based on a stream. 

## interface ni::iFileBase
Base file interface. 

### Parents:
- iUnknown

### Methods:
- __iFileBase::GetFileFlags__() -> _tFileFlags_: Get the file flags. 
- __iFileBase::GetSourcePath__() -> _const achar\*_: Get the path from where this file has been opened. 
- __iFileBase::Seek__(_tI64_ offset) -> _tBool_: Moves the file pointer from the current position. 
- __iFileBase::SeekSet__(_tI64_ offset) -> _tBool_: Set the file pointer position from the begining of the file. 
- __iFileBase::ReadRaw__(_void\*_ apOut, _tSize_ anSize) -> _tSize_: Read data from the file. 
- __iFileBase::WriteRaw__(_const void\*_ apIn, _tSize_ anSize) -> _tSize_: Write data in the file. 
- __iFileBase::Tell__() -> _tI64_: Tell the current cursor position in the file in bytes. 
- __iFileBase::GetSize__() -> _tI64_: Get the size of the file. 
- __iFileBase::SeekEnd__(_tI64_ offset) -> _tBool_: Moves the file pointer from the end of the file. 
- __iFileBase::Flush__() -> _tBool_: Flush the file content. 
- __iFileBase::GetTime__(_eFileTime_ aFileTime, _iTime\*_ apTime) -> _tBool_: Get the file time. 
- __iFileBase::SetTime__(_eFileTime_ aFileTime, _const iTime\*_ apTime) -> _tBool_: Set the file time. 
- __iFileBase::Resize__(_tI64_ newSize) -> _tBool_: Resize the file. 

## interface ni::iFile
File interface. 

### Parents:
- iUnknown

### Methods:
- __iFile::GetFileBase__() -> _iFileBase\*_: Get the file base. 
- __iFile::GetSourcePath__() -> _const achar\*_: Get the path from where this file has been opened. 
- __iFile::Seek__(_tI64_ offset) -> _tBool_: Moves the file pointer from the current position. 
- __iFile::SeekSet__(_tI64_ offset) -> _tBool_: Set the file pointer position from the begining of the file. 
- __iFile::ReadRaw__(_void\*_ pOut, _tSize_ nSize) -> _tSize_: Read data from the file. 
- __iFile::WriteRaw__(_const void\*_ pIn, _tSize_ nSize) -> _tSize_: Write data in the file. 
- __iFile::Tell__() -> _tI64_: Tell the current cursor position in the file in bytes. 
- __iFile::GetSize__() -> _tI64_: Get the size of the file. 
- __iFile::SeekEnd__(_tI64_ offset) -> _tBool_: Moves the file pointer from the end of the file. 
- __iFile::Flush__() -> _tBool_: Flush the file content. 
- __iFile::GetTime__(_eFileTime_ aFileTime, _iTime\*_ apTime) -> _tBool_: Get the file time. 
- __iFile::SetTime__(_eFileTime_ aFileTime, _const iTime\*_ apTime) -> _tBool_: Set the file time. 
- __iFile::Resize__(_tI64_ newSize) -> _tBool_: Resize the file. 
- __iFile::GetBase__() -> _tPtr_: Get the base pointer. 
- __iFile::GetHere__() -> _tPtr_: Get the here/current position pointer. 
- __iFile::GetStop__() -> _tPtr_: Get the stop/end pointer. 
- __iFile::SetMemPtr__(_tPtr_ apMem, _tSize_ anSize, _tBool_ abFree, _tBool_ abKeepHere) -> _tBool_: Set the memory buffer to use with this file. 
- __iFile::Reset__() -> _void_: Reset the file. Put it at the begining, and set the memory size to 0 if it's a dynamic memory file. 
- __iFile::WriteFile__(_iFileBase\*_ apFile, _tI64_ anSize) -> _tI64_: Write another file in this file 
- __iFile::GetFileFlags__() -> _tFileFlags_: Get the file flags. 
- __iFile::GetCanRead__() -> _tBool_: Check whether file can be read. 
- __iFile::GetCanWrite__() -> _tBool_: Check whether File can be written. 
- __iFile::GetCanSeek__() -> _tBool_: Check whether the file supports seeking. 
- __iFile::GetPartialRead__() -> _tBool_: Check whether the previous read operation could not read all bytes. 
- __iFile::GetPartialWrite__() -> _tBool_: Check whether the previous write operation could not write all bytes to the file. 
- __iFile::GetIsEncoder__() -> _tBool_: Check whether the file is an encoder/decoder. 
- __iFile::GetIsDummy__() -> _tBool_: Check whether the file is a dummy. 
- __iFile::GetIsMemory__() -> _tBool_: Check if the file is a memory file (implements iFileMemory). 
- __iFile::GetIsStream__() -> _tBool_: Check whether the file is a stream. 
- __iFile::ReadF32__() -> _tF32_: Read a 32 bits float and move the file pointer forward of 4 bytes. 
- __iFile::ReadF64__() -> _tF64_: Read a 64 bits float and move the file pointer forward of 8 bytes. 
- __iFile::Read8__() -> _tU8_: Read a single byte (8 bits integer) and move the file pointer forward of 1 byte. 
- __iFile::ReadLE16__() -> _tU16_: Read a 16 bits little endian interger and move the file pointer forward of 2 bytes. 
- __iFile::ReadBE16__() -> _tU16_: Read a 16 bits big endian interger and move the file pointer forward of 2 bytes. 
- __iFile::ReadLE32__() -> _tU32_: Read a 32 bits little endian interger and move the file pointer forward of 4 bytes. 
- __iFile::ReadBE32__() -> _tU32_: Read a 32 bits big endian interger and move the file pointer forward of 4 bytes. 
- __iFile::ReadLE64__() -> _tU64_: Read a 64 bits little endian interger and move the file pointer forward of 8 bytes. 
- __iFile::ReadBE64__() -> _tU64_: Read a 64 bits big endian interger and move the file pointer forward of 8 bytes. 
- __iFile::ReadF32Array__(_tF32\*_ apOut, _tSize_ anNumElements) -> _tSize_: Read a 32 bits float array and move the file pointer forward of 4 bytes * anNumElements. 
- __iFile::ReadF64Array__(_tF64\*_ apOut, _tSize_ anNumElements) -> _tSize_: Read a 64 bits float array and move the file pointer forward of 8 bytes * anNumElements. 
- __iFile::ReadLE16Array__(_tU16\*_ apOut, _tSize_ anNumElements) -> _tSize_: Read a 16 bits little endian interger array and move the file pointer forward of 2 bytes * anNumElements. 
- __iFile::ReadBE16Array__(_tU16\*_ apOut, _tSize_ anNumElements) -> _tSize_: Read a 16 bits big endian interger array and move the file pointer forward of 2 bytes * anNumElements. 
- __iFile::ReadLE32Array__(_tU32\*_ apOut, _tSize_ anNumElements) -> _tSize_: Read a 32 bits little endian interger array and move the file pointer forward of 4 bytes * anNumElements. 
- __iFile::ReadBE32Array__(_tU32\*_ apOut, _tSize_ anNumElements) -> _tSize_: Read a 32 bits big endian interger array and move the file pointer forward of 4 bytes * anNumElements. 
- __iFile::ReadLE64Array__(_tU64\*_ apOut, _tSize_ anNumElements) -> _tSize_: Read a 64 bits little endian interger array and move the file pointer forward of 8 bytes * anNumElements. 
- __iFile::ReadBE64Array__(_tU64\*_ apOut, _tSize_ anNumElements) -> _tSize_: Read a 64 bits big endian interger array and move the file pointer forward of 8 bytes * anNumElements. 
- __iFile::WriteF32__(_tF32_ v) -> _tSize_: Write a 32 bits float and move the file pointer forward of 4 bytes. 
- __iFile::WriteF64__(_tF64_ v) -> _tSize_: Write a 64 bits float and move the file pointer forward of 8 bytes. 
- __iFile::Write8__(_tU8_ v) -> _tSize_: Write a single byte (8 bits integer) and move the file pointer forward of one byte. 
- __iFile::WriteLE16__(_tU16_ v) -> _tSize_: Write a little endian 16 bits integer and move the file pointer forward of 2 bytes. 
- __iFile::WriteBE16__(_tU16_ v) -> _tSize_: Write a big endian 16 bits integer and move the file pointer forward of 2 bytes. 
- __iFile::WriteLE32__(_tU32_ v) -> _tSize_: Write a little endian 32 bits integer and move the file pointer forward of 4 bytes. 
- __iFile::WriteBE32__(_tU32_ v) -> _tSize_: Write a big endian 32 bits integer and move the file pointer forward of 4 bytes. 
- __iFile::WriteLE64__(_tU64_ v) -> _tSize_: Write a little endian 64 bits integer and move the file pointer forward of 8 bytes. 
- __iFile::WriteBE64__(_tU64_ v) -> _tSize_: Write a big endian 64 bits integer and move the file pointer forward of 8 bytes. 
- __iFile::WriteF32Array__(_const tF32\*_ apIn, _tU32_ anNumElements) -> _tSize_: Write a 32 bits float array and move the file pointer forward of 4 bytes * anNumElements. 
- __iFile::WriteF64Array__(_const tF64\*_ apIn, _tU32_ anNumElements) -> _tSize_: Write a 64 bits float and move the file pointer forward of 8 bytes * anNumElements. 
- __iFile::WriteLE16Array__(_const tU16\*_ apIn, _tU32_ anNumElements) -> _tSize_: Write a little endian 16 bits integer and move the file pointer forward of 2 bytes * anNumElements. 
- __iFile::WriteBE16Array__(_const tU16\*_ apIn, _tU32_ anNumElements) -> _tSize_: Write a big endian 16 bits integer and move the file pointer forward of 2 bytes * anNumElements. 
- __iFile::WriteLE32Array__(_const tU32\*_ apIn, _tU32_ anNumElements) -> _tSize_: Write a little endian 32 bits integer and move the file pointer forward of 4 bytes * anNumElements. 
- __iFile::WriteBE32Array__(_const tU32\*_ apIn, _tU32_ anNumElements) -> _tSize_: Write a big endian 32 bits integer and move the file pointer forward of 4 bytes * anNumElements. 
- __iFile::WriteLE64Array__(_const tU64\*_ apIn, _tU32_ anNumElements) -> _tSize_: Write a little endian 64 bits integer and move the file pointer forward of 8 bytes * anNumElements. 
- __iFile::WriteBE64Array__(_const tU64\*_ apIn, _tU32_ anNumElements) -> _tSize_: Write a big endian 64 bits integer and move the file pointer forward of 8 bytes * anNumElements. 
- __iFile::GetTextEncodingFormat__() -> _eTextEncodingFormat_: Get the text encoding format. 
- __iFile::SetTextEncodingFormat__(_eTextEncodingFormat_ aFormat) -> _void_: Set the text encoding format. 
- __iFile::BeginTextFileRead__(_tBool_ abSeekSetZero) -> _tBool_: Read text file header. 
- __iFile::BeginTextFileWrite__(_eTextEncodingFormat_ aFormat, _tBool_ abSeekSetZero) -> _tBool_: Write text file header. 
- __iFile::ReadString__() -> _cString_: Read a string. 
- __iFile::ReadStringLine__() -> _cString_: Read a string line. 
- __iFile::WriteString__(_const achar\*_ aaszString) -> _tSize_: Write a string. 
- __iFile::WriteStringZ__(_const achar\*_ aaszString) -> _tSize_: Write a string with a end zero. 
- __iFile::ReadChar__() -> _tU32_: Read a character with the current encoding. 
- __iFile::WriteChar__(_tU32_ anChar) -> _tSize_: Write a character with the current encoding. 
- __iFile::ReadStringEx__(_eTextEncodingFormat_ aFmt) -> _cString_: Read a string. 
- __iFile::ReadStringLineEx__(_eTextEncodingFormat_ aFmt) -> _cString_: Read a string line. 
- __iFile::WriteStringEx__(_eTextEncodingFormat_ aFmt, _const achar\*_ aaszString) -> _tSize_: Write a string. 
- __iFile::WriteStringZEx__(_eTextEncodingFormat_ aFmt, _const achar\*_ aaszString) -> _tSize_: Write a string with a end zero. 
- __iFile::ReadCharEx__(_eTextEncodingFormat_ aFmt) -> _tU32_: Read a character with the current encoding. 
- __iFile::WriteCharEx__(_eTextEncodingFormat_ aFmt, _tU32_ anChar) -> _tSize_: Write a character with the current encoding. 
- __iFile::BeginWriteBits__() -> _void_
- __iFile::EndWriteBits__() -> _tSize_
- __iFile::IsWriteBitsBegan__() -> _tBool_
- __iFile::WriteBit__(_tBool_ abBit) -> _void_
- __iFile::WriteBits__(_tPtr_ apData, _tU32_ anBits, _tBool_ abInvertBytesOrder) -> _void_
- __iFile::WriteBits8__(_tU8_ anData, _tU32_ anBits) -> _void_
- __iFile::WriteBits16__(_tU16_ anData, _tU32_ anBits) -> _void_
- __iFile::WriteBits32__(_tU32_ anData, _tU32_ anBits) -> _void_
- __iFile::WriteBits64__(_tU64_ anData, _tU32_ anBits) -> _void_
- __iFile::BeginReadBits__() -> _void_
- __iFile::EndReadBits__() -> _tSize_
- __iFile::IsReadBitsBegan__() -> _tBool_
- __iFile::ReadBit__() -> _tBool_
- __iFile::ReadBits__(_tPtr_ apData, _tU32_ anBits, _tBool_ abInvertBytesOrder) -> _void_
- __iFile::ReadBitsU8__(_tU32_ anBits) -> _tU8_
- __iFile::ReadBitsU16__(_tU32_ anBits) -> _tU16_
- __iFile::ReadBitsU32__(_tU32_ anBits) -> _tU32_
- __iFile::ReadBitsU64__(_tU32_ anBits) -> _tU64_
- __iFile::ReadBitsI8__(_tU32_ anBits) -> _tI8_
- __iFile::ReadBitsI16__(_tU32_ anBits) -> _tI16_
- __iFile::ReadBitsI32__(_tU32_ anBits) -> _tI32_
- __iFile::ReadBitsI64__(_tU32_ anBits) -> _tI64_
- __iFile::GetMinNumBitsU32__(_tU32_ anNumber) -> _tU32_
- __iFile::GetMinNumBitsI32__(_tI32_ anNumber) -> _tU32_
- __iFile::GetMinNumBitsU64__(_tU64_ anNumber) -> _tU32_
- __iFile::GetMinNumBitsI64__(_tI64_ anNumber) -> _tU32_
- __iFile::WriteBitsPackedU64__(_tU64_ anNumber) -> _void_
- __iFile::WriteBitsPackedU48__(_tU64_ anNumber) -> _void_
- __iFile::WriteBitsPackedU32__(_tU32_ anNumber) -> _void_
- __iFile::WriteBitsPackedU24__(_tU32_ anNumber) -> _void_
- __iFile::WriteBitsPackedU16__(_tU16_ anNumber) -> _void_
- __iFile::WriteBitsPackedU8__(_tU8_ anNumber) -> _void_
- __iFile::ReadBitsPackedU64__() -> _tU64_
- __iFile::ReadBitsPackedU48__() -> _tU64_
- __iFile::ReadBitsPackedU32__() -> _tU32_
- __iFile::ReadBitsPackedU24__() -> _tU32_
- __iFile::ReadBitsPackedU16__() -> _tU16_
- __iFile::ReadBitsPackedU8__() -> _tU8_
- __iFile::WriteBitsPackedI64__(_tI64_ anNumber) -> _void_
- __iFile::WriteBitsPackedI48__(_tI64_ anNumber) -> _void_
- __iFile::WriteBitsPackedI32__(_tI32_ anNumber) -> _void_
- __iFile::WriteBitsPackedI24__(_tI32_ anNumber) -> _void_
- __iFile::WriteBitsPackedI16__(_tI16_ anNumber) -> _void_
- __iFile::WriteBitsPackedI8__(_tI8_ anNumber) -> _void_
- __iFile::ReadBitsPackedI64__() -> _tI64_
- __iFile::ReadBitsPackedI48__() -> _tI64_
- __iFile::ReadBitsPackedI32__() -> _tI32_
- __iFile::ReadBitsPackedI24__() -> _tI32_
- __iFile::ReadBitsPackedI16__() -> _tI16_
- __iFile::ReadBitsPackedI8__() -> _tI8_
- __iFile::ReadBitsString__() -> _cString_
- __iFile::WriteBitsString__(_const achar\*_ aaszIn) -> _tSize_
- __iFile::WriteVar__(_const Var&_ aVar) -> _tBool_: Write a variant. 
- __iFile::ReadVar__() -> _Var_: Read a variant. 
- __iFile::ReadVarEx__(_Var&_ aVar) -> _tBool_: Read a variant. 
- __iFile::WriteBitsPackedVar__(_const Var&_ aVar) -> _tBool_: Write a variant. 
- __iFile::ReadBitsPackedVar__() -> _Var_: Read a variant. 
- __iFile::ReadBitsPackedVarEx__(_Var&_ aVar) -> _tBool_: Read a variant. 
- __iFile::ReadRawToString__(_eRawToStringEncoding_ aFormat, _tInt_ anNumBytes) -> _cString_: Reads the specified number of bytes and return them encoded as a string. 
- __iFile::WriteRawFromString__(_eRawToStringEncoding_ aFormat, _const achar\*_ aaszString) -> _tInt_: Write bytes encoded in a string. 
- __iFile::ReadQuotedLine__() -> _ni::cString_: Reads a line of text that potentially use quotes " and escaped quotes "" & \" to join a single 'line' with embedded newlines inside. 

## interface ni::iFileMemory
Memory file. 

### Parents:
- iUnknown

### Methods:
- __iFileMemory::GetBase__() -> _tPtr_: Get the base pointer. 
- __iFileMemory::GetHere__() -> _tPtr_: Get the here/current position pointer. 
- __iFileMemory::GetStop__() -> _tPtr_: Get the stop/end pointer. 
- __iFileMemory::SetMemPtr__(_tPtr_ apMem, _tSize_ anSize, _tBool_ abFree, _tBool_ abKeepHere) -> _tBool_: Set the memory buffer to use with this file. 
- __iFileMemory::Reset__() -> _void_: Reset the file. Put it at the begining, and set the memory size to 0 if it's a dynamic memory file. 

## interface ni::iURLFileHandler
URL File handler interface. 

### Parents:
- iUnknown

### Methods:
- __iURLFileHandler::URLOpen__(_const achar\*_ aURL) -> _iFile\*_: Open a synchronous stream to the specified URL. 
- __iURLFileHandler::URLExists__(_const achar\*_ aURL) -> _tBool_: Validates the specified URL and if possible checks whether the resource the URL points to actually exists. 

## interface ni::iBufferEncoder
Buffer encoder 

### Parents:
- iUnknown

### Methods:
- __iBufferEncoder::EncodeMarker__() -> _tU32_: Get the encoder's buffer marker. 
- __iBufferEncoder::EncodeMaxDestSize__(_tU32_ anSrcSize) -> _tSize_: Get the maximum size that could be required by the specified buffer size. 
- __iBufferEncoder::EncodeBuffer__(_tPtr_ apDest, _tSize_ anDestSize, _tPtr_ apSrc, _tSize_ anSrcSize) -> _tSize_: Encodes the specified data buffer in the specified output buffer. 

## interface ni::iBufferDecoder
Buffer decoder 

### Parents:
- iUnknown

### Methods:
- __iBufferDecoder::DecodeMarker__() -> _tU32_: Get the decoder's buffer marker. 
- __iBufferDecoder::DecodeMaxDestSize__(_tU32_ anSrcSize) -> _tSize_: Get the maximum size that could be required by the specified buffer size. 
- __iBufferDecoder::DecodeBuffer__(_tPtr_ apDest, _tSize_ anDestSize, _tPtr_ apSrc, _tSize_ anSrcSize) -> _tSize_: Decodes the specified data buffer in the specified output buffer. 

## enum ni::eTextEncodingFormat
Text encoding formats. 

### Values:
- __eTextEncodingFormat_Unknown__ = __eInvalidHandle__: Text encoding format header is unknown/invalid. 
- __eTextEncodingFormat_UTF8__ = __0__: UTF8 encoding. 
- __eTextEncodingFormat_UTF8BOM__ = __1__: UTF8 encoding, with explicit BOM. 
- __eTextEncodingFormat_UTF16LE__ = __2__: UTF16 Little Endian. 
- __eTextEncodingFormat_UTF16BE__ = __3__: UTF16 Big Endian. 
- __eTextEncodingFormat_UTF32LE__ = __4__: UTF32 Little Endian. 
- __eTextEncodingFormat_UTF32BE__ = __5__: UTF32 Big Endian. 
- __eTextEncodingFormat_BitStream__ = __6__: Bit stream encoding. 
- __eTextEncodingFormat_Unicode__ = __eTextEncodingFormat_UTF32LE__
- __eTextEncodingFormat_Native__ = __eTextEncodingFormat_UTF8__: Native encoding. 

## enum ni::eFileSystemRightsFlags
File system rights. 

### Values:
- __eFileSystemRightsFlags_Enum__ = __niBit(0)__: Right to enumerate files. 
- __eFileSystemRightsFlags_Read__ = __niBit(1)__: Right to read from files. 
- __eFileSystemRightsFlags_Write__ = __niBit(2)__: Right to write in files, but not to create files. 
- __eFileSystemRightsFlags_Create__ = __niBit(3)__: Right to create files. 
- __eFileSystemRightsFlags_Delete__ = __niBit(4)__: Right to delete files. 
- __eFileSystemRightsFlags_Execute__ = __niBit(5)__: Right to execute files. 
- __eFileSystemRightsFlags_ReadOnly__ = __eFileSystemRightsFlags_Enum|eFileSystemRightsFlags_Read__: Read-only system 
- __eFileSystemRightsFlags_WriteOnly__ = __eFileSystemRightsFlags_Write__: Write-only system 
- __eFileSystemRightsFlags_ReadWriteOnly__ = __eFileSystemRightsFlags_Enum|eFileSystemRightsFlags_Read|eFileSystemRightsFlags_Write__: Read-Write-only system 
- __eFileSystemRightsFlags_IOOnly__ = __eFileSystemRightsFlags_Read|eFileSystemRightsFlags_Enum|eFileSystemRightsFlags_Write|eFileSystemRightsFlags_Create|eFileSystemRightsFlags_Delete__: IO rights only. All excepted execution. 
- __eFileSystemRightsFlags_All__ = __eFileSystemRightsFlags_Read|eFileSystemRightsFlags_Enum|eFileSystemRightsFlags_Write|eFileSystemRightsFlags_Create|eFileSystemRightsFlags_Delete|eFileSystemRightsFlags_Execute__: All rights 

## interface ni::iFileSystemEnumerator
File system enumerator interface. 

### Parents:
- iUnknown

### Methods:
- __iFileSystemEnumerator::GetFileSystem__() -> _iFileSystem\*_: Get the owner file system. 
- __iFileSystemEnumerator::FindFirst__(_const achar\*_ aaszFilePattern) -> _tBool_: Find the first file matching the specified pattern. 
- __iFileSystemEnumerator::FindNext__() -> _tBool_: Find the next file matching the specified pattern. 
- __iFileSystemEnumerator::GetFileName__() -> _const achar\*_: Get the current file name. 
- __iFileSystemEnumerator::GetFileSize__() -> _tI64_: Get the current file size. 
- __iFileSystemEnumerator::GetFileAttributes__() -> _tFileAttrFlags_: Get the current file attributes. 
- __iFileSystemEnumerator::GetFileTime__() -> _iTime\*_: Get the current file last write time. 

## interface ni::iFileSystem
File system interface. 

### Parents:
- iUnknown

### Methods:
- __iFileSystem::GetRightsFlags__() -> _tFileSystemRightsFlags_: Get the file system's rights. 
- __iFileSystem::GetBaseContainer__() -> _const achar\*_: Get the file system's base container. 
- __iFileSystem::FileMakeDir__(_const achar\*_ aszDir) -> _tBool_: Create a directory. 
- __iFileSystem::FileDeleteDir__(_const achar\*_ aszDir) -> _tBool_: Delete a directory. 
- __iFileSystem::FileCopy__(_const achar\*_ aszDest, _const achar\*_ aszSrc) -> _tBool_: Copy a file. 
- __iFileSystem::FileMove__(_const achar\*_ aszDest, _const achar\*_ aszSrc) -> _tBool_: Move a file. 
- __iFileSystem::FileDelete__(_const achar\*_ aszFile) -> _tBool_: Delete a file. 
- __iFileSystem::FileEnum__(_const achar\*_ aszFile, _tU32_ aAttribs, _iFileEnumSink\*_ pSink) -> _tU32_: Enumerate files in the specified directory. \see ni::FileEnum 
- __iFileSystem::FileExists__(_const achar\*_ aszFile, _tU32_ aAttribs) -> _tU32_: Checks if a file exists. 
- __iFileSystem::FileSize__(_const achar\*_ aszFile) -> _tI64_: Get the size of a file. 
- __iFileSystem::FileOpen__(_const achar\*_ aszFile, _eFileOpenMode_ aMode) -> _iFile\*_: Open a file for a read and/or write operation. 
- __iFileSystem::FileBaseOpen__(_const achar\*_ aszFile, _eFileOpenMode_ aMode) -> _iFileBase\*_: Open a file for a read and/or write operation. 
- __iFileSystem::GetAbsolutePath__(_const achar\*_ aaszFile) -> _cString_: Get the absolute path of the given file or directory. 
- __iFileSystem::CreateEnumerator__() -> _iFileSystemEnumerator\*_: Create a file system enumerator. 

## enum ni::eFileSystemRightsFlags
File system rights. 

### Values:
- __eFileSystemRightsFlags_Enum__ = __niBit(0)__: Right to enumerate files. 
- __eFileSystemRightsFlags_Read__ = __niBit(1)__: Right to read from files. 
- __eFileSystemRightsFlags_Write__ = __niBit(2)__: Right to write in files, but not to create files. 
- __eFileSystemRightsFlags_Create__ = __niBit(3)__: Right to create files. 
- __eFileSystemRightsFlags_Delete__ = __niBit(4)__: Right to delete files. 
- __eFileSystemRightsFlags_Execute__ = __niBit(5)__: Right to execute files. 
- __eFileSystemRightsFlags_ReadOnly__ = __eFileSystemRightsFlags_Enum|eFileSystemRightsFlags_Read__: Read-only system 
- __eFileSystemRightsFlags_WriteOnly__ = __eFileSystemRightsFlags_Write__: Write-only system 
- __eFileSystemRightsFlags_ReadWriteOnly__ = __eFileSystemRightsFlags_Enum|eFileSystemRightsFlags_Read|eFileSystemRightsFlags_Write__: Read-Write-only system 
- __eFileSystemRightsFlags_IOOnly__ = __eFileSystemRightsFlags_Read|eFileSystemRightsFlags_Enum|eFileSystemRightsFlags_Write|eFileSystemRightsFlags_Create|eFileSystemRightsFlags_Delete__: IO rights only. All excepted execution. 
- __eFileSystemRightsFlags_All__ = __eFileSystemRightsFlags_Read|eFileSystemRightsFlags_Enum|eFileSystemRightsFlags_Write|eFileSystemRightsFlags_Create|eFileSystemRightsFlags_Delete|eFileSystemRightsFlags_Execute__: All rights 

## enum ni::eGameCtrlAxis
Game controller axis 

### Values:
- __eGameCtrlAxis_LX__ = __0__: Left X Axis. 
- __eGameCtrlAxis_LY__ = __1__: Left Y Axis. 
- __eGameCtrlAxis_LZ__ = __2__: Left Z Axis. 
- __eGameCtrlAxis_RX__ = __3__: Right X Axis. 
- __eGameCtrlAxis_RY__ = __4__: Right Y Axis. 
- __eGameCtrlAxis_RZ__ = __5__: Right Z AXis. 
- __eGameCtrlAxis_Last__ = __6__: \internal 

## enum ni::eGameCtrlButton
Game controller buttons. 

### Values:
- __eGameCtrlButton_A__ = __0__: A 
- __eGameCtrlButton_B__ = __1__: B 
- __eGameCtrlButton_X__ = __2__: X 
- __eGameCtrlButton_Y__ = __3__: Y 
- __eGameCtrlButton_LeftBlock__ = __4__: Left Block 
- __eGameCtrlButton_RightBlock__ = __5__: Right Block 
- __eGameCtrlButton_Back__ = __6__: Back 
- __eGameCtrlButton_Start__ = __7__: Start 
- __eGameCtrlButton_LeftThumb__ = __8__: Left Thumb 
- __eGameCtrlButton_RightThumb__ = __9__: Right Thumb 
- __eGameCtrlButton_LeftTrigger__ = __10__: LeftTrigger 
- __eGameCtrlButton_RightTrigger__ = __11__: RightTrigger 
- __eGameCtrlButton_DPadUp__ = __12__: Up 
- __eGameCtrlButton_DPadDown__ = __13__: Down 
- __eGameCtrlButton_DPadLeft__ = __14__: Left 
- __eGameCtrlButton_DPadRight__ = __15__: Right 

## interface ni::iGameCtrl
Game controller interface. 

### Parents:
- iUnknown

### Methods:
- __iGameCtrl::Update__() -> _tBool_: Update the device states. 
- __iGameCtrl::GetIsConnected__() -> _tBool_: Return eTrue if the device is connected. 
- __iGameCtrl::GetName__() -> _const achar\*_: Name of the input device. 
- __iGameCtrl::GetIndex__() -> _tU32_: Get the index of the game controller. 
- __iGameCtrl::GetNumButtons__() -> _tU32_: Return the number of buttons of the game controller. 
- __iGameCtrl::GetButton__(_tU32_ ulButton) -> _tF32_: Return the force applied on the button. 
- __iGameCtrl::GetNumAxis__() -> _tU32_: Return the number of axis of the game controller. 
- __iGameCtrl::GetAxis__(_eGameCtrlAxis_ axis) -> _tF32_: Return the position of the given axis 
- __iGameCtrl::GetCanVibrate__() -> _tBool_: Get whether the game controller can vibrate. 
- __iGameCtrl::Vibrate__(_const sVec2f&_ aSpeed) -> _void_: Set the left & right motor vibrations. 
- __iGameCtrl::GetHasBattery__() -> _tBool_: Get whether the controller has a battery. 
- __iGameCtrl::GetBatteryLevel__() -> _tF32_: Get the battery level. 

## enum ni::eGameCtrlAxis
Game controller axis 

### Values:
- __eGameCtrlAxis_LX__ = __0__: Left X Axis. 
- __eGameCtrlAxis_LY__ = __1__: Left Y Axis. 
- __eGameCtrlAxis_LZ__ = __2__: Left Z Axis. 
- __eGameCtrlAxis_RX__ = __3__: Right X Axis. 
- __eGameCtrlAxis_RY__ = __4__: Right Y Axis. 
- __eGameCtrlAxis_RZ__ = __5__: Right Z AXis. 
- __eGameCtrlAxis_Last__ = __6__: \internal 

## interface ni::iHString
HString interface. 

### Parents:
- iUnknown

### Methods:
- __iHString::GetChars__() -> _const achar\*_: Get the string's characters. 
- __iHString::GetLength__() -> _tU32_: Get the string's length. 
- __iHString::Cmp__(_const iHString\*_ ahspString) -> _tI32_: Compare this string with another HString. 
- __iHString::ICmp__(_const iHString\*_ ahspString) -> _tI32_: Case insensitive compare with another HString. 
- __iHString::GetLocalized__() -> _iHString\*_: Get the string localized in the default locale. 
- __iHString::GetLocalizedEx__(_iHString\*_ locale) -> _iHString\*_: Get the string localized in the specified locale. 
- __iHString::IsLocalized__(_iHString\*_ locale) -> _tBool_: Get the whether the string is localized in the specified locale. 
- __iHString::CreateCharIt__(_tU32_ offset) -> _iHStringCharIt\*_: Return a character iterator to iterate over the string starting at the specified byte offset. 
- __iHString::CreateRangeIt__(_tU32_ offset, _tU32_ size) -> _iHStringCharIt\*_: Return a character iterator to iterate over the specifed byte range in the string. 

## interface ni::iHStringCharIt
HString character iterator interface. 

### Parents:
- iUnknown

### Methods:
- __iHStringCharIt::GetString__() -> _iHString\*_: Get the string being iterated. 
- __iHStringCharIt::Clone__() -> _iHStringCharIt\*_: Clone the iterator. 
- __iHStringCharIt::GetIsStart__() -> _tBool_: Get whether the current position is the start of the iterator. 
- __iHStringCharIt::GetIsEnd__() -> _tBool_: Get whether the current position is the end of the iterator. 
- __iHStringCharIt::GetPosition__() -> _tU32_: Get the current position from the start of the iterator in bytes. 
- __iHStringCharIt::ToStart__() -> _void_: Move the iterator to its starting point. 
- __iHStringCharIt::ToEnd__() -> _tSize_: Move the iterator to its end point. 
- __iHStringCharIt::GetNumChars__() -> _tSize_: Get the number of characters covered by the iterator. 
- __iHStringCharIt::GetNumBytes__() -> _tSize_: Get the number of bytes covered by the iterator. 
- __iHStringCharIt::PeekNext__() -> _tU32_: Return the next character in the string without moving the iterator. 
- __iHStringCharIt::Next__() -> _tU32_: Return the next character in the string moving the iterator forward. 
- __iHStringCharIt::PeekPrior__() -> _tU32_: Return the previous character in the string without moving the iterator. 
- __iHStringCharIt::Prior__() -> _tU32_: Return the next character in the string moving the iterator backward. 
- __iHStringCharIt::PeekAdvance__(_tU32_ fwd) -> _tU32_: Return the nth character in the string without moving the iterator. 
- __iHStringCharIt::Advance__(_tU32_ n) -> _tU32_: Return the nth character in the string moving the iterator forward. 
- __iHStringCharIt::PeekRewind__(_tU32_ back) -> _tU32_: Return the nth previous character in the string without moving the iterator. 
- __iHStringCharIt::Rewind__(_tU32_ n) -> _tU32_: Return the nth previous character in the string moving the iterator backward. 
- __iHStringCharIt::ToPosition__(_tU32_ anOffsetInBytes) -> _void_: Move the iterator to the specified position in bytes. 

## interface ni::iHString
HString interface. 

### Parents:
- iUnknown

### Methods:
- __iHString::GetChars__() -> _const achar\*_: Get the string's characters. 
- __iHString::GetLength__() -> _tU32_: Get the string's length. 
- __iHString::Cmp__(_const iHString\*_ ahspString) -> _tI32_: Compare this string with another HString. 
- __iHString::ICmp__(_const iHString\*_ ahspString) -> _tI32_: Case insensitive compare with another HString. 
- __iHString::GetLocalized__() -> _iHString\*_: Get the string localized in the default locale. 
- __iHString::GetLocalizedEx__(_iHString\*_ locale) -> _iHString\*_: Get the string localized in the specified locale. 
- __iHString::IsLocalized__(_iHString\*_ locale) -> _tBool_: Get the whether the string is localized in the specified locale. 
- __iHString::CreateCharIt__(_tU32_ offset) -> _iHStringCharIt\*_: Return a character iterator to iterate over the string starting at the specified byte offset. 
- __iHString::CreateRangeIt__(_tU32_ offset, _tU32_ size) -> _iHStringCharIt\*_: Return a character iterator to iterate over the specifed byte range in the string. 

## enum ni::eJsonType
Json value types 

### Values:
- __eJsonType_Syntax__ = __0__: Syntax parsing. 
- __eJsonType_Name__ = __1__: Pair Name (string) 
- __eJsonType_String__ = __2__: String 
- __eJsonType_Number__ = __3__: Number 
- __eJsonType_True__ = __4__: true 
- __eJsonType_False__ = __5__: false 
- __eJsonType_Null__ = __6__: null 
- __eJsonType_ObjectBegin__ = __7__: Object begining 
- __eJsonType_ObjectEnd__ = __8__: Object end 
- __eJsonType_ArrayBegin__ = __9__: Array begining 
- __eJsonType_ArrayEnd__ = __10__: Array end 

## interface ni::iJsonParserSink
Json parser sink interface. 

### Parents:
- iUnknown

### Methods:
- __iJsonParserSink::OnJsonParserSink_Error__(_const achar\*_ aaszReason, _tU32_ anLine, _tU32_ anCol) -> _void_: Json parser sink interface. Called when a parsing error occured. 
- __iJsonParserSink::OnJsonParserSink_Value__(_eJsonType_ aType, _const achar\*_ aValue) -> _void_: Called when a value is parsed 

## interface ni::iJsonWriterSink
Json writer sink interface. 

### Parents:
- iUnknown

### Methods:
- __iJsonWriterSink::OnJsonWriterSink_Error__(_const achar\*_ aaszReason) -> _void_: Json writer sink interface. Called when there's a writting error. 
- __iJsonWriterSink::OnJsonWriterSink_Write__(_eJsonType_ aValue, _const achar\*_ aaszString) -> _tBool_: Called when to write a value. 

## interface ni::iJsonWriter
Json writer interface. 

### Parents:
- iUnknown

### Methods:
- __iJsonWriter::Reset__() -> _void_: Reset the writer's content. 
- __iJsonWriter::ArrayBegin__() -> _tBool_: Begin an array. 
- __iJsonWriter::ArrayEnd__() -> _tBool_: Ends an array. 
- __iJsonWriter::ObjectBegin__() -> _tBool_: Begin an object. 
- __iJsonWriter::ObjectEnd__() -> _tBool_: Ends an object. 
- __iJsonWriter::Name__(_const achar\*_ aName) -> _tBool_: Append a key name. 
- __iJsonWriter::ValueString__(_const achar\*_ aStr) -> _tBool_: Append a string in the current array/object. 
- __iJsonWriter::ValueNumber__(_const achar\*_ aStr) -> _tBool_: Append an integer in the current array/object. 
- __iJsonWriter::ValueBool__(_tBool_ abItem) -> _tBool_: Append a boolean in the current array/object. 
- __iJsonWriter::ValueNull__() -> _tBool_: Append a null value in the current array/object. 
- __iJsonWriter::ObjectString__(_const achar\*_ aName, _const achar\*_ aStr) -> _tBool_: Write a string property in the current object. 
- __iJsonWriter::ObjectNumber__(_const achar\*_ aName, _const achar\*_ aStr) -> _tBool_: Write a number property in the current object. 
- __iJsonWriter::ObjectBool__(_const achar\*_ aName, _tBool_ abValue) -> _tBool_: Write a boolean property in the current object. 
- __iJsonWriter::ObjectNull__(_const achar\*_ aName) -> _tBool_: Write a null property in the current object. 

## enum ni::eJsonType
Json value types 

### Values:
- __eJsonType_Syntax__ = __0__: Syntax parsing. 
- __eJsonType_Name__ = __1__: Pair Name (string) 
- __eJsonType_String__ = __2__: String 
- __eJsonType_Number__ = __3__: Number 
- __eJsonType_True__ = __4__: true 
- __eJsonType_False__ = __5__: false 
- __eJsonType_Null__ = __6__: null 
- __eJsonType_ObjectBegin__ = __7__: Object begining 
- __eJsonType_ObjectEnd__ = __8__: Object end 
- __eJsonType_ArrayBegin__ = __9__: Array begining 
- __eJsonType_ArrayEnd__ = __10__: Array end 

## enum ni::eEnumToStringFlags
Enum to string flags 

### Values:
- __eEnumToStringFlags_Full__ = __niBit(0)__: Dont use the specified enum as default enumeration (will fully qualify the enumeration value's name). 
- __eEnumToStringFlags_Flags__ = __niBit(1)__: Handle the enumeration as a set of flags. 
- __eEnumToStringFlags_GlobalSearch__ = __niBit(2)__: Search all registered enumerations if the specified fully qualified enumeration can't be found. 

## enum ni::eSystemMessage
System messages id. 

### Values:
- __eSystemMessage_Exit__ = __niMessageID('_','S','Y','S','x')__: The application exits. 
- __eSystemMessage_SetupParentWindow__ = __niMessageID('_','S','Y','S','W')__: Sent to a child process to notify which is the actual parent window. 
- __eSystemMessage_SetupClientWindow__ = __niMessageID('_','S','Y','S','w')__: Sent to a parent process to notify which is the actual child window created. 
- __eSystemMessage_Log__ = __niMessageID('_','S','Y','S','L')__: Log message. 
- __eSystemMessage_OpenFile__ = __niMessageID('_','S','Y','S','O')__: Open file. 

## enum ni::eClipboardType
Clipboard types 

### Values:
- __eClipboardType_System__ = __0__: System clipboard. 
- __eClipboardType_Memory1__ = __1__: Memory clipboard 1. 
- __eClipboardType_Memory2__ = __2__: Memory clipboard 2. 
- __eClipboardType_Memory3__ = __3__: Memory clipboard 3. 
- __eClipboardType_Memory4__ = __4__: Memory clipboard 4. 
- __eClipboardType_Memory5__ = __5__: Memory clipboard 5. 
- __eClipboardType_Memory6__ = __6__: Memory clipboard 6. 
- __eClipboardType_Memory7__ = __7__: Memory clipboard 7. 
- __eClipboardType_Memory8__ = __8__: Memory clipboard 8. 
- __eClipboardType_Memory9__ = __9__: Memory clipboard 9. 
- __eClipboardType_Memory10__ = __10__: Memory clipboard 10. 
- __eClipboardType_Last__ = __11__: \internal 

## interface ni::iLang


### Parents:
- iUnknown

### Methods:
- __iLang::GetProcessManager__() -> _iOSProcessManager\*_: Get the platform's process manager. 
- __iLang::Exit__(_tU32_ aulErrorCode) -> _void_: Forcefully exit the application. 
- __iLang::OnExit__(_iRunnable\*_ apRunnable) -> _tBool_: Adds a runnable that will be called when the application exits through iLang::Exit(). 
- __iLang::FatalError__(_const achar\*_ aszMsg) -> _void_: Show an error message box then exit. 
- __iLang::SetEnv__(_const achar\*_ aaszEnv, _const achar\*_ aaszValue) -> _void_: Set an OS environment variable. 
- __iLang::GetEnv__(_const achar\*_ aaszEnv) -> _cString_: Get an OS environment variable. 
- __iLang::GetProperties__() -> _const tStringCMap\*_: Get the system properties. 
- __iLang::HasProperty__(_const achar\*_ aaszName) -> _tBool_: Check whether the specified system property exists. 
- __iLang::SetProperty__(_const achar\*_ aaszName, _const achar\*_ aaszValue) -> _void_: Set the specified system property. 
- __iLang::GetProperty__(_const achar\*_ aaszName) -> _cString_: Get the specified system property. 
- __iLang::RegisterModuleDef__(_const iModuleDef\*_ apDef) -> _tBool_: Register a module definition. 
- __iLang::GetNumModuleDefs__() -> _tU32_: Get the number of modules registered. 
- __iLang::GetModuleDef__(_tU32_ anIndex) -> _const iModuleDef\*_: Get the module at the specified index. 
- __iLang::GetModuleDefIndex__(_const achar\*_ aaszName) -> _tU32_: Get the index of the module with the specified name. 
- __iLang::LoadModuleDef__(_const achar\*_ aName, _const achar\*_ aaszFile) -> _const iModuleDef\*_: Load a module definition from a DLL. 
- __iLang::GetCreateInstanceMap__() -> _tCreateInstanceCMap\*_: Create instance map. 
- __iLang::CreateInstance__(_const achar\*_ aOID, _const Var&_ aVarA, _const Var&_ aVarB) -> _iUnknown\*_: Create instance of the specified object type. 
- __iLang::GetGlobalInstanceMap__() -> _tGlobalInstanceCMap\*_: Get the global instance map. 
- __iLang::SetGlobalInstance__(_const achar\*_ aaszName, _iUnknown\*_ apInstance) -> _tBool_: Set a global instance. 
- __iLang::GetGlobalInstance__(_const achar\*_ aaszName) -> _iUnknown\*_: Get a global instance. 
- __iLang::RegisterEnumDef__(_const sEnumDef\*_ apEnumDef) -> _tBool_: Register an enumeration definition. 
- __iLang::GetEnumDef__(_const achar\*_ aEID) -> _const sEnumDef\*_: Get an enum definition from the specified name. 
- __iLang::GetInterfaceName__(_const tUUID&_ aUUID) -> _iHString\*_: Get the name of the interface with the specified UUID. 
- __iLang::GetInterfaceUUID__(_iHString\*_ ahspStr) -> _const tUUID&_: Get the UUID of the interface with the specified name. 
- __iLang::GetInterfaceDefFromUUID__(_const tUUID&_ aUUID) -> _const sInterfaceDef\*_: Get the interface definition from the specified UUID. 
- __iLang::SetDefaultLocale__(_iHString\*_ ahspLocale) -> _void_: Set the default locale. 
- __iLang::GetDefaultLocale__() -> _iHString\*_: Get the default locale. 
- __iLang::GetNumLocales__() -> _tU32_: Return the number of locales that have at least one localized string. 
- __iLang::GetLocale__(_tU32_ abIndex) -> _iHString\*_: Return the name of the locale at the specified index. 
- __iLang::ClearLocalization__(_iHString\*_ ahspLocale) -> _tBool_: Remove all localized strings of the specified locale. 
- __iLang::SetLocalization__(_iHString\*_ ahspLocale, _iHString\*_ ahspNative, _iHString\*_ ahspLocalized) -> _tBool_: Set the localization of the specified 'native' string. 
- __iLang::SetLocalizationMap__(_iHString\*_ ahspLocale, _const tStringCMap\*_ apLocalizationMap) -> _tBool_: Set the localization of the specified of all strings in the specified map. 
- __iLang::GetLocalizationMap__(_iHString\*_ ahspLocale, _tStringCMap\*_ apLocalizedMap) -> _tU32_: Get all localized strings of the specified locale. 
- __iLang::SetMarkMissingLocalization__(_tBool_ abMarkMissing) -> _void_: Set whether the string table should mark missing locale translations. 
- __iLang::GetMarkMissingLocalization__() -> _tBool_: Get whether the string table should mark missing locale translations. 
- __iLang::GetMissingLocalization__(_iHString\*_ locale) -> _tStringCVec\*_: Get all missing strings of the specified locale. 
- __iLang::CreateLocalUUID__() -> _tUUID_: Create a local UUID. 
- __iLang::CreateGlobalUUID__() -> _tUUID_: Create a global UUID. 
- __iLang::SetLogFilter__(_tU32_ exclude) -> _void_: Set the log filter. 
- __iLang::GetLogFilter__() -> _tU32_: Get the log filter. 
- __iLang::Log__(_tLogFlags_ type, _const achar\*_ file, _const achar\*_ func, _tU32_ line, _const achar\*_ msg) -> _void_: Log a message. 
- __iLang::GetRootFS__() -> _iFileSystem\*_: Get the root file system. 
- __iLang::CreateFileSystemDir__(_const achar\*_ aaszDir, _tFileSystemRightsFlags_ aRights) -> _iFileSystem\*_: Create a directory file system. 
- __iLang::CreateFileSystemHashed__(_const iFileSystem\*_ apFS) -> _iFileSystem\*_: Creates a file system that store the file using its hashed file name. 
- __iLang::CreateFile__(_iFileBase\*_ apBase) -> _iFile\*_: Create a file from the specified file base. 
- __iLang::CreateFileBaseWriteDummy__() -> _iFileBase\*_: Create a dummy file base. 
- __iLang::CreateFileWriteDummy__() -> _iFile\*_: Create a dummy file. 
- __iLang::CreateFileBaseMemory__(_tPtr_ apMem, _tSize_ anSize, _tBool_ abFree, _const achar\*_ aszPath) -> _iFileBase\*_: Create a memory file base. 
- __iLang::CreateFileMemory__(_tPtr_ apMem, _tSize_ anSize, _tBool_ abFree, _const achar\*_ aszPath) -> _iFile\*_: Create a memory file. 
- __iLang::CreateFileBaseMemoryAlloc__(_tSize_ anSize, _const achar\*_ aszPath) -> _iFileBase\*_: Create a memory file base. 
- __iLang::CreateFileMemoryAlloc__(_tSize_ anSize, _const achar\*_ aszPath) -> _iFile\*_: Create a memory file. 
- __iLang::CreateFileBaseDynamicMemory__(_tSize_ anSize, _const achar\*_ aszPath) -> _iFileBase\*_: Create a dynamic memory file base. 
- __iLang::CreateFileDynamicMemory__(_tSize_ anSize, _const achar\*_ aszPath) -> _iFile\*_: Create a dynamic memory file. 
- __iLang::CreateFileBaseWindow__(_iFileBase\*_ apBase, _tI64_ anBase, _tI64_ anSize, _const achar\*_ aaszPath, _tBool_ abAutoSeekSet) -> _iFileBase\*_: Create a file base window. 
- __iLang::CreateFileWindow__(_iFileBase\*_ apBase, _tI64_ anBase, _tI64_ anSize, _const achar\*_ aaszPath, _tBool_ abAutoSeekSet) -> _iFile\*_: Create a file window. 
- __iLang::CreateFileBaseBufferEncoder__(_iFileBase\*_ apBase, _iBufferEncoder\*_ apEnc) -> _iFileBase\*_: Create a file base buffer encoder. 
- __iLang::CreateFileBufferEncoder__(_iFileBase\*_ apBase, _iBufferEncoder\*_ apEnc) -> _iFile\*_: Create a file buffer encoder. 
- __iLang::CreateFileBaseBufferDecoder__(_iFileBase\*_ apBase, _iBufferDecoder\*_ apDec, _tSize_ aDecodedSize) -> _iFileBase\*_: Create a file base buffer decoder. 
- __iLang::CreateFileBufferDecoder__(_iFileBase\*_ apBase, _iBufferDecoder\*_ apDec, _tSize_ aDecodedSize) -> _iFile\*_: Create a file buffer decoder. 
- __iLang::FileBufferEncode__(_iBufferEncoder\*_ apEnc, _iFile\*_ apSrc, _tSize_ anSrcSize, _iFile\*_ apDest) -> _tSize_: Encodes a file using the specified buffer encoder. 
- __iLang::FileBufferDecode__(_iBufferDecoder\*_ apDec, _iFile\*_ apSrc, _tSize_ anSrcSize, _iFile\*_ apDest, _tSize_ anDestSize) -> _tSize_: Decodes a file using the specified buffer decoder. 
- __iLang::RunCommand__(_const achar\*_ aaszCmd) -> _tI32_: Run the specified OS command. 
- __iLang::StartPath__(_const achar\*_ aaszFile) -> _tI32_: Start the specified file/path. 
- __iLang::GetCurrentTime__() -> _const iTime\*_: Get the current time. 
- __iLang::TimerInSeconds__() -> _tF64_: Get the current value of the lowest level timer available in seconds. 
- __iLang::ResetFrameTime__() -> _void_: Reset the frame time. 
- __iLang::UpdateFrameTime__(_const tF64_ afElapsedTime) -> _tBool_: Update the frame. 
- __iLang::GetTotalFrameTime__() -> _tF64_: Get the total time since the last ResetFrameTime. 
- __iLang::GetFrameTime__() -> _tF64_: Get the time taken by the last frame. 
- __iLang::GetFrameNumber__() -> _tU32_: Get the current frame number. 
- __iLang::GetFrameRate__() -> _tF32_: Get the frame rate. 
- __iLang::GetAverageFrameRate__() -> _tU32_: Get the average frame rate per seconds. 
- __iLang::JsonParseFile__(_ni::iFile\*_ apFile, _ni::iJsonParserSink\*_ apSink) -> _ni::tBool_: Parse Json contained in the specified file. 
- __iLang::JsonParseString__(_const ni::cString&_ aString, _ni::iJsonParserSink\*_ apSink) -> _ni::tBool_: Parse Json contained in the specified string. 
- __iLang::CreateJsonSinkWriter__(_ni::iJsonWriterSink\*_ apSink, _ni::tBool_ abPrettyPrint) -> _ni::iJsonWriter\*_: Create a Json writer to write to the specified sink. 
- __iLang::CreateJsonFileWriter__(_ni::iFile\*_ apFile, _ni::tBool_ abPrettyPrint) -> _ni::iJsonWriter\*_: Create a Json writer to write to the specified file. 
- __iLang::XmlParseFile__(_ni::iFile\*_ apFile, _ni::iXmlParserSink\*_ apSink) -> _ni::tBool_: Parse Xml contained in the specified file. 
- __iLang::XmlParseString__(_const ni::cString&_ aString, _ni::iXmlParserSink\*_ apSink) -> _ni::tBool_: Parse Xml contained in the specified string. 
- __iLang::GetExpressionContext__() -> _iExpressionContext\*_: Get the root expression context. 
- __iLang::CreateExpressionContext__() -> _iExpressionContext\*_: Create a new expression context. 
- __iLang::Eval__(_const achar\*_ aaszExpr) -> _Ptr<iExpressionVariable>_: Evaluate the specified expression. 
- __iLang::EnumToString__(_tU32_ anValue, _const sEnumDef\*_ apEnumDef, _tEnumToStringFlags_ aFlags) -> _cString_: Convert an enum value to an expression string. 
- __iLang::StringToEnum__(_const achar\*_ aExpr, _const sEnumDef\*_ apEnumDef, _tEnumToStringFlags_ aFlags) -> _tU32_: Convert an expression string to an enum value. 
- __iLang::AddScriptingHost__(_iHString\*_ ahspName, _iScriptingHost\*_ apHost) -> _tBool_: Add a scripting host. 
- __iLang::RemoveScriptingHost__(_iHString\*_ ahspName) -> _tBool_: Remove a scripting host. 
- __iLang::GetNumScriptingHosts__() -> _tU32_: Get the number of scripting hosts. 
- __iLang::GetScriptingHostName__(_tU32_ anIndex) -> _iHString\*_: Get the name of the scripting host at the specified index. 
- __iLang::GetScriptingHost__(_tU32_ anIndex) -> _iScriptingHost\*_: Get the scripting host at the specified index. 
- __iLang::GetScriptingHostFromName__(_iHString\*_ ahspName) -> _iScriptingHost\*_: Get the scripting host from the specified name. 
- __iLang::GetScriptingHostIndex__(_iScriptingHost\*_ apHost) -> _tU32_: Get the index of the specified scripting host. 
- __iLang::ServiceAllScriptingHosts__(_tBool_ abForceGC) -> _void_: Service all scripting hosts. 
- __iLang::FindScriptingHost__(_iHString\*_ ahspContext, _iHString\*_ ahspCodeResource) -> _iScriptingHost\*_: Get the first scripting host that can evaluate the code resources. 
- __iLang::GetProf__() -> _iProf\*_: Get the profiler instance. 
- __iLang::URLGetProtocol__(_const achar\*_ aURL) -> _cString_: Get the protocol that will be used to access the specified URL. 
- __iLang::URLGetHandler__(_const achar\*_ aURL) -> _iURLFileHandler\*_: Get the URL file handler that will be used to access the specified URL. 
- __iLang::URLOpen__(_const achar\*_ aURL) -> _iFile\*_: Open a synchronous stream to the specified URL. 
- __iLang::URLExists__(_const achar\*_ aURL) -> _tBool_: Validates the specified URL and if possible checks whether the resource the URL points to actually exists. 
- __iLang::URLFindFilePath__(_const achar\*_ aszRes, _const achar\*_ aszBasePath, _const achar\*_ aLoaderPrefix) -> _cString_: Find the path/url matching the specified resource, basepath and with the extensions derived from the specified loader prefix. 
- __iLang::CreateHString__(_const cString&_ aStr) -> _Ptr<iHString>_: Create a new HString. 
- __iLang::LoadLocalization__(_iDataTable\*_ apDT) -> _tBool_: Load a localization table. 
- __iLang::IsSerializedObject__(_iFile\*_ apFile, _const achar\*_ aID, _tI64\*_ apObjSize) -> _tBool_: Check if the file contains an object of the specified type. 
- __iLang::SerializeObject__(_iFile\*_ apFile, _iUnknown\*_ apObject, _eSerializeMode_ aMode, _tI64\*_ apObjSize) -> _iUnknown\*_: Serialize an object. 
- __iLang::ReadSerializationHeader__(_iFile\*_ apFile, _cString\*_ apID, _tI64\*_ apSize) -> _tI64_: Read serialization header. 
- __iLang::WriteSerializationHeader__(_iFile\*_ apFile, _const achar\*_ apID, _tI64_ anSize) -> _tI64_: Write serialization header. 
- __iLang::CreateDeviceResourceManager__(_const achar\*_ aszType) -> _iDeviceResourceManager\*_: Create a new device resource manager. 
- __iLang::GetSystemMessageHandlers__() -> _tMessageHandlerSinkLst\*_: Get the system message targets. 
- __iLang::CreateDataTable__(_const achar\*_ aaszName) -> _iDataTable\*_: Create a data table. 
- __iLang::SerializeDataTable__(_const achar\*_ aaszType, _eSerializeMode_ aMode, _iDataTable\*_ apTable, _iFile\*_ apFile) -> _tBool_: Serialize the specified data table. 
- __iLang::CreateDataTableWriteStack__(_iDataTable\*_ apDT) -> _iDataTableWriteStack\*_: Create a data table write stack. 
- __iLang::CreateDataTableWriteStackFromName__(_const achar\*_ aaszName) -> _iDataTableWriteStack\*_: Create a data table write stack. 
- __iLang::CreateDataTableReadStack__(_iDataTable\*_ apDT) -> _iDataTableReadStack\*_: Create a data table read stack. 
- __iLang::GetAbsoluteDataTablePath__(_iDataTable\*_ apDT, _tU32_ anPropIndex) -> _cString_: Build an absolute path to the specified datatable and property. 
- __iLang::SetClipboard__(_eClipboardType_ aType, _iDataTable\*_ apDT) -> _tBool_: Set the data of the specified clipboard. 
- __iLang::GetClipboard__(_eClipboardType_ aType) -> _iDataTable\*_: Get the data of the specified clipboard. 
- __iLang::GetNumMonitors__() -> _tU32_: Get the number of monitors connected to the comptuer. 
- __iLang::GetMonitorIndex__(_tIntPtr_ aHandle) -> _tU32_: Get the index of the monitor with the specified OS handle. 
- __iLang::GetMonitorHandle__(_tU32_ anIndex) -> _tIntPtr_: Get the OS handle to the monitor at the specified index. 
- __iLang::GetMonitorName__(_tU32_ anIndex) -> _const achar\*_: Get the name of the monitor at the specified index. 
- __iLang::GetMonitorRect__(_tU32_ anIndex) -> _sRecti_: Get the rectangle of the monitor at the specified index. 
- __iLang::GetMonitorFlags__(_tU32_ anIndex) -> _tOSMonitorFlags_: Get the flags of the monitor at the specified index. 
- __iLang::CreateWindow__(_iOSWindow\*_ apParent, _const achar\*_ aaszTitle, _const sRecti&_ aRect, _tOSWindowCreateFlags_ aCreate, _tOSWindowStyleFlags_ aStyle) -> _iOSWindow\*_: Create a new OS window. 
- __iLang::CreateWindowEx__(_tIntPtr_ aOSWindowHandle, _tOSWindowCreateFlags_ aCreate) -> _iOSWindow\*_: Create a an OS window from a generic OS window handle. 
- __iLang::MessageBox__(_iOSWindow\*_ apParent, _const achar\*_ aaszTitle, _const achar\*_ aaszText, _tOSMessageBoxFlags_ aFlags) -> _eOSMessageBoxReturn_: Displays a native modal message box. 
- __iLang::OpenFileDialog__(_iOSWindow\*_ aParent, _const achar\*_ aTitle, _const achar\*_ aFilter, _const achar\*_ aInitDir) -> _cString_: Displays a native file open dialog box. 
- __iLang::SaveFileDialog__(_iOSWindow\*_ aParent, _const achar\*_ aTitle, _const achar\*_ aFilter, _const achar\*_ aInitDir) -> _cString_: Displays a native file save dialog box. 
- __iLang::PickDirectoryDialog__(_iOSWindow\*_ aParent, _const achar\*_ aTitle, _const achar\*_ aInitDir) -> _cString_: Displays a native directory picker dialog box. 
- __iLang::GetNumGameCtrls__() -> _tU32_: Get the number of game controllers available on the system. 
- __iLang::GetGameCtrl__(_tU32_ aulIdx) -> _iGameCtrl\*_: Get a game controller input device interface. 

## enum ni::eEnumToStringFlags
Enum to string flags 

### Values:
- __eEnumToStringFlags_Full__ = __niBit(0)__: Dont use the specified enum as default enumeration (will fully qualify the enumeration value's name). 
- __eEnumToStringFlags_Flags__ = __niBit(1)__: Handle the enumeration as a set of flags. 
- __eEnumToStringFlags_GlobalSearch__ = __niBit(2)__: Search all registered enumerations if the specified fully qualified enumeration can't be found. 

## enum ni::eClassify
Values returned by the classification functions 

### Remarks:
- Classification values can be combined as flags. 

### Values:
- __eClassify_Front__ = __niBit(0)__
- __eClassify_Back__ = __niBit(1)__
- __eClassify_Coplanar__ = __niBit(2)__
- __eClassify_Spanned__ = __niBit(3)__

## interface ni::iMath
Math interface. 

### Parents:
- iUnknown

### Remarks:
- The simple operations, +, -, *, /, ==, etc. are not implemented in this interface, they are expected to be implemented natively into the target language. 

### Methods:
- __iMath::Sqrt__(_tF64_ v) -> _tF64_: Square root. 
- __iMath::Sin__(_tF64_ v) -> _tF64_: Sinus. 
- __iMath::Cos__(_tF64_ v) -> _tF64_: Cosinus. 
- __iMath::ASin__(_tF64_ v) -> _tF64_: Arc Sinus. 
- __iMath::ACos__(_tF64_ v) -> _tF64_: Arc Cosinus. 
- __iMath::Tan__(_tF64_ v) -> _tF64_: Tan. 
- __iMath::ATan__(_tF64_ v) -> _tF64_: Arc Tangent. 
- __iMath::ATan2__(_tF64_ x, _tF64_ y) -> _tF64_: Arc Tangent 2. 
- __iMath::LogX__(_tF64_ v, _tF64_ n) -> _tF64_: Log base N. 
- __iMath::LogE__(_tF64_ v) -> _tF64_: Log base E. 
- __iMath::Log2__(_tF64_ v) -> _tF64_: Log base 2. 
- __iMath::Log10__(_tF64_ v) -> _tF64_: Log base 10. 
- __iMath::Pow__(_tF64_ v, _tF64_ e) -> _tF64_: Power. 
- __iMath::Floor__(_tF64_ v) -> _tF64_: Floor. 
- __iMath::Ceil__(_tF64_ v) -> _tF64_: Ceil. 
- __iMath::Exp__(_tF64_ v) -> _tF64_: Exponential. 
- __iMath::Abs__(_tF64_ v) -> _tF64_: Absolute value. 
- __iMath::ToRad__(_tF64_ afDeg) -> _tF64_: Convert degree to radian. 
- __iMath::ToDeg__(_tF64_ afRad) -> _tF64_: Convert radian to degree. 
- __iMath::Min__(_tF64_ a, _tF64_ b) -> _tF64_: Minimum between a and b. 
- __iMath::Min3__(_tF64_ a, _tF64_ b, _tF64_ c) -> _tF64_: Minimum between a, b and c. 
- __iMath::Max__(_tF64_ a, _tF64_ b) -> _tF64_: Maximum between a and b. 
- __iMath::Max3__(_tF64_ a, _tF64_ b, _tF64_ c) -> _tF64_: Maximum between a, b and c. 
- __iMath::Clamp__(_tF64_ v, _tF64_ afMin, _tF64_ afMax) -> _tF64_: Clamp the specified number between min and max. 
- __iMath::ClampZeroOne__(_tF64_ a) -> _tF64_: Clamp the specified number between zero and one. 
- __iMath::Lerp__(_tF64_ a, _tF64_ b, _tF64_ f) -> _tF64_: Linear interpolation between a and b. 
- __iMath::BlendIntoAccumulator__(_tF64_ accumulator, _tF64_ newValue, _tF64_ smoothRate) -> _tF64_: Blends new values into an accumulator to produce a smoothed time series.  
- __iMath::RandSeed__(_tU32_ ulSeed) -> _void_: Randomize. 
- __iMath::RandInt__() -> _tI32_: Compute a random integer number. 
- __iMath::RandIntRange__(_tI32_ aMin, _tI32_ aMax) -> _tI32_: Compute a random integer number between a specified range. 
- __iMath::RandFloat__() -> _tF32_: Compute a random float number. 
- __iMath::RandFloatRange__(_tF32_ afMin, _tF32_ afMax) -> _tF32_: Compute a random float number between a specified range. 
- __iMath::RandNormal__(_tF32_ sigma) -> _tF32_: Compute a random number with a normal distribution. 
- __iMath::RandomDirection__(_const sVec3f&_ vN) -> _sVec3f_: Generates a random direction in the upper hemisphere. 
- __iMath::RandomDirectionEx__(_const sVec3f&_ avN, _tF32_ afDeviAngle) -> _sVec3f_: Generates a random direction in the upper hemisphere. 
- __iMath::RotateRay__(_const sVec3f&_ avIn, _const sVec3f&_ avN) -> _sVec3f_: Rotates a ray to have avN as basis. 
- __iMath::RandColorA__(_tU8_ aA) -> _tU32_: Return a random color with a specified alpha. 
- __iMath::RandColorAf__(_tF32_ aA) -> _tU32_: Return a random 32 bit color with specified alpha. 
- __iMath::RandColor__() -> _tU32_: Return a random 32 bit color. 
- __iMath::Vec2Add__(_const sVec2f&_ aLeft, _const sVec2f&_ aRight) -> _sVec2f_: Add. 
- __iMath::Vec2Sub__(_const sVec2f&_ aLeft, _const sVec2f&_ aRight) -> _sVec2f_: Subtract. 
- __iMath::Vec2Mul__(_const sVec2f&_ aLeft, _const sVec2f&_ aRight) -> _sVec2f_: Multiply. 
- __iMath::Vec2Div__(_const sVec2f&_ aLeft, _const sVec2f&_ aRight) -> _sVec2f_: Divide. 
- __iMath::Vec2Scale__(_const sVec2f&_ aLeft, _tF32_ afRight) -> _sVec2f_: Scale. 
- __iMath::Vec2Compare__(_const sVec2f&_ aLeft, _const sVec2f&_ aRight) -> _tI32_: Compare. 
- __iMath::Vec2Length__(_const sVec2f&_ aV) -> _tF32_: Length. 
- __iMath::Vec2LengthSq__(_const sVec2f&_ aV) -> _tF32_: Length squared. 
- __iMath::Vec2Normalize__(_const sVec2f&_ aV) -> _sVec2f_: Normalize. 
- __iMath::Vec2IsNormal__(_const sVec2f&_ aV) -> _tBool_: Return eTrue if it's a normal vector. 
- __iMath::Vec2Dot__(_const sVec2f&_ aLeft, _const sVec2f&_ aRight) -> _tF32_: Dot product. 
- __iMath::Vec2Lerp__(_const sVec2f&_ aLeft, _const sVec2f&_ aRight, _tF32_ afF) -> _sVec2f_: Lerp. 
- __iMath::Vec2Lerp2__(_const sVec2f&_ aLeft, _const sVec2f&_ aRight, _const sVec2f&_ aF) -> _sVec2f_: Lerp. 
- __iMath::Vec2BlendIntoAccumulator__(_const sVec2f&_ accumulator, _const sVec2f&_ newValue, _tF32_ smoothRate) -> _sVec2f_: Blends new values into an accumulator to produce a smoothed time series.  
- __iMath::Vec2Abs__(_const sVec2f&_ aV) -> _sVec2f_: Abs. 
- __iMath::Vec2Min__(_const sVec2f&_ aLeft, _const sVec2f&_ aRight) -> _sVec2f_: Min. 
- __iMath::Vec2Max__(_const sVec2f&_ aLeft, _const sVec2f&_ aRight) -> _sVec2f_: Max. 
- __iMath::Vec2CatmullRom__(_const sVec2f&_ V1, _const sVec2f&_ V2, _const sVec2f&_ V3, _const sVec2f&_ V4, _tF32_ s) -> _sVec2f_: CatmullRom spline. 
- __iMath::Vec2Hermite__(_const sVec2f&_ V1, _const sVec2f&_ V2, _const sVec2f&_ V3, _const sVec2f&_ V4, _tF32_ s) -> _sVec2f_: Hermite spline. 
- __iMath::Vec2BaryCentric__(_const sVec2f&_ V1, _const sVec2f&_ V2, _const sVec2f&_ V3, _tF32_ u, _tF32_ v) -> _sVec2f_: BaryCentric. 
- __iMath::Vec2Transform__(_const sVec2f&_ aVec, _const sMatrixf&_ aMatrix) -> _sVec4f_: Transform by the specified matrix. 
- __iMath::Vec2TransformCoord__(_const sVec2f&_ aVec, _const sMatrixf&_ aMatrix) -> _sVec2f_: Transform by the specified matrix. 
- __iMath::Vec2TransformNormal__(_const sVec2f&_ aVec, _const sMatrixf&_ aMatrix) -> _sVec2f_: Transform by the specified matrix. 
- __iMath::Vec2TransformCoordArray__(_tVec2fCVec\*_ apVecs, _const sMatrixf&_ aMatrix) -> _void_: Transform an array by the specified matrix. 
- __iMath::Vec2TransformNormalArray__(_tVec2fCVec\*_ apVecs, _const sMatrixf&_ aMatrix) -> _void_: Transform an array by the specified matrix. 
- __iMath::Vec3Add__(_const sVec3f&_ aLeft, _const sVec3f&_ aRight) -> _sVec3f_: Add. 
- __iMath::Vec3Sub__(_const sVec3f&_ aLeft, _const sVec3f&_ aRight) -> _sVec3f_: Subtract. 
- __iMath::Vec3Mul__(_const sVec3f&_ aLeft, _const sVec3f&_ aRight) -> _sVec3f_: Multiply. 
- __iMath::Vec3Div__(_const sVec3f&_ aLeft, _const sVec3f&_ aRight) -> _sVec3f_: Divide. 
- __iMath::Vec3Scale__(_const sVec3f&_ aLeft, _tF32_ afRight) -> _sVec3f_: Scale. 
- __iMath::Vec3Compare__(_const sVec3f&_ aLeft, _const sVec3f&_ aRight) -> _tI32_: Compare. 
- __iMath::Vec3Length__(_const sVec3f&_ aV) -> _tF32_: Length. 
- __iMath::Vec3LengthSq__(_const sVec3f&_ aV) -> _tF32_: Length squared. 
- __iMath::Vec3Normalize__(_const sVec3f&_ aV) -> _sVec3f_: Normalize. 
- __iMath::Vec3IsNormal__(_const sVec3f&_ aV) -> _tBool_: Return eTrue if it's a normal vector. 
- __iMath::Vec3Dot__(_const sVec3f&_ aLeft, _const sVec3f&_ aRight) -> _tF32_: Dot product. 
- __iMath::Vec3Cross__(_const sVec3f&_ aLeft, _const sVec3f&_ aRight) -> _sVec3f_: Cross product. 
- __iMath::Vec3Lerp__(_const sVec3f&_ aLeft, _const sVec3f&_ aRight, _tF32_ afF) -> _sVec3f_: Lerp. 
- __iMath::Vec3Lerp2__(_const sVec3f&_ aLeft, _const sVec3f&_ aRight, _const sVec3f&_ aF) -> _sVec3f_: Lerp. 
- __iMath::Vec3BlendIntoAccumulator__(_const sVec3f&_ accumulator, _const sVec3f&_ newValue, _tF32_ smoothRate) -> _sVec3f_: Blends new values into an accumulator to produce a smoothed time series.  
- __iMath::Vec3Abs__(_const sVec3f&_ aV) -> _sVec3f_: Abs. 
- __iMath::Vec3Min__(_const sVec3f&_ aLeft, _const sVec3f&_ aRight) -> _sVec3f_: Min. 
- __iMath::Vec3Max__(_const sVec3f&_ aLeft, _const sVec3f&_ aRight) -> _sVec3f_: Max. 
- __iMath::Vec3CatmullRom__(_const sVec3f&_ V1, _const sVec3f&_ V2, _const sVec3f&_ V3, _const sVec3f&_ V4, _tF32_ s) -> _sVec3f_: CatmullRom spline. 
- __iMath::Vec3Hermite__(_const sVec3f&_ V1, _const sVec3f&_ V2, _const sVec3f&_ V3, _const sVec3f&_ V4, _tF32_ s) -> _sVec3f_: Hermite spline. 
- __iMath::Vec3BaryCentric__(_const sVec3f&_ V1, _const sVec3f&_ V2, _const sVec3f&_ V3, _tF32_ u, _tF32_ v) -> _sVec3f_: BaryCentric. 
- __iMath::Vec3Transform__(_const sVec3f&_ aVec, _const sMatrixf&_ aMatrix) -> _sVec4f_: Transform by the specified matrix. 
- __iMath::Vec3TransformCoord__(_const sVec3f&_ aVec, _const sMatrixf&_ aMatrix) -> _sVec3f_: Transform by the specified matrix. 
- __iMath::Vec3TransformNormal__(_const sVec3f&_ aVec, _const sMatrixf&_ aMatrix) -> _sVec3f_: Transform by the specified matrix. 
- __iMath::Vec3TransformCoordArray__(_tVec3fCVec\*_ apVecs, _const sMatrixf&_ aMatrix) -> _void_: Transform an array by the specified matrix. 
- __iMath::Vec3TransformNormalArray__(_tVec3fCVec\*_ apVecs, _const sMatrixf&_ aMatrix) -> _void_: Transform an array by the specified matrix. 
- __iMath::Vec3Unproject__(_const sVec3f&_ avIn, _const sRectf&_ aVP, _const sMatrixf&_ amtxViewProj) -> _sVec3f_: Unproject a vector. 
- __iMath::Vec3Project__(_const sVec3f&_ avPos, _const sMatrixf&_ amtxWVP, _const sRectf&_ aRect) -> _sVec3f_: Project a vector. 
- __iMath::Vec3ProjectRHW__(_const sVec3f&_ avPos, _const sMatrixf&_ amtxWVP, _const sRectf&_ aRect) -> _sVec4f_: Project a vector. 
- __iMath::Vec3Reflect__(_const sVec3f&_ Dir, _const sVec3f&_ Normal) -> _sVec3f_: Returns a vector reflected about the plane indicated by the specified normal. 
- __iMath::Vec4Add__(_const sVec4f&_ aLeft, _const sVec4f&_ aRight) -> _sVec4f_: Add. 
- __iMath::Vec4Sub__(_const sVec4f&_ aLeft, _const sVec4f&_ aRight) -> _sVec4f_: Subtract. 
- __iMath::Vec4Mul__(_const sVec4f&_ aLeft, _const sVec4f&_ aRight) -> _sVec4f_: Multiply. 
- __iMath::Vec4Div__(_const sVec4f&_ aLeft, _const sVec4f&_ aRight) -> _sVec4f_: Divide. 
- __iMath::Vec4Scale__(_const sVec4f&_ aLeft, _tF32_ afRight) -> _sVec4f_: Scale. 
- __iMath::Vec4Compare__(_const sVec4f&_ aLeft, _const sVec4f&_ aRight) -> _tI32_: Compare. 
- __iMath::Vec4Length__(_const sVec4f&_ aV) -> _tF32_: Length. 
- __iMath::Vec4LengthSq__(_const sVec4f&_ aV) -> _tF32_: Length squared. 
- __iMath::Vec4Normalize__(_const sVec4f&_ aV) -> _sVec4f_: Normalize. 
- __iMath::Vec4IsNormal__(_const sVec4f&_ aV) -> _tBool_: Return eTrue if it's a normal vector. 
- __iMath::Vec4Dot__(_const sVec4f&_ aLeft, _const sVec4f&_ aRight) -> _tF32_: Dot product. 
- __iMath::Vec4Cross__(_const sVec4f&_ aA, _const sVec4f&_ aB, _const sVec4f&_ aC) -> _sVec4f_: Cross product. 
- __iMath::Vec4Lerp__(_const sVec4f&_ aLeft, _const sVec4f&_ aRight, _tF32_ afF) -> _sVec4f_: Lerp. 
- __iMath::Vec4Lerp2__(_const sVec4f&_ aLeft, _const sVec4f&_ aRight, _const sVec4f&_ aF) -> _sVec4f_: Lerp. 
- __iMath::Vec4BlendIntoAccumulator__(_const sVec4f&_ accumulator, _const sVec4f&_ newValue, _tF32_ smoothRate) -> _sVec4f_: Blends new values into an accumulator to produce a smoothed time series.  
- __iMath::Vec4Abs__(_const sVec4f&_ aV) -> _sVec4f_: Abs. 
- __iMath::Vec4Min__(_const sVec4f&_ aLeft, _const sVec4f&_ aRight) -> _sVec4f_: Min. 
- __iMath::Vec4Max__(_const sVec4f&_ aLeft, _const sVec4f&_ aRight) -> _sVec4f_: Max. 
- __iMath::Vec4CatmullRom__(_const sVec4f&_ V1, _const sVec4f&_ V2, _const sVec4f&_ V3, _const sVec4f&_ V4, _tF32_ s) -> _sVec4f_: CatmullRom spline. 
- __iMath::Vec4Hermite__(_const sVec4f&_ V1, _const sVec4f&_ V2, _const sVec4f&_ V3, _const sVec4f&_ V4, _tF32_ s) -> _sVec4f_: Hermite spline. 
- __iMath::Vec4BaryCentric__(_const sVec4f&_ V1, _const sVec4f&_ V2, _const sVec4f&_ V3, _tF32_ u, _tF32_ v) -> _sVec4f_: BaryCentric. 
- __iMath::Vec4Transform__(_const sVec4f&_ aVec, _const sMatrixf&_ aMatrix) -> _sVec4f_: Transform by the specified matrix. 
- __iMath::Vec4TransformArray__(_tVec4fCVec\*_ apVecs, _const sMatrixf&_ aMatrix) -> _void_: Transform an array by the specified matrix. 
- __iMath::MatrixIdentity__() -> _sMatrixf_: Get the identity matrix. 
- __iMath::MatrixIsIdentity__(_const sMatrixf&_ M) -> _tBool_: Check if a matrix is identity. 
- __iMath::MatrixAdd__(_const sMatrixf&_ aLeft, _const sMatrixf&_ aRight) -> _sMatrixf_: Add. 
- __iMath::MatrixSub__(_const sMatrixf&_ aLeft, _const sMatrixf&_ aRight) -> _sMatrixf_: Subtract. 
- __iMath::MatrixScale__(_const sMatrixf&_ aLeft, _tF32_ afRight) -> _sMatrixf_: Scale. 
- __iMath::MatrixLerp__(_const sMatrixf&_ A, _const sMatrixf&_ B, _tF32_ fFac) -> _sMatrixf_: Lerp. 
- __iMath::MatrixCompare__(_const sMatrixf&_ aLeft, _const sMatrixf&_ aRight) -> _tI32_: Compare. 
- __iMath::MatrixMultiply__(_const sMatrixf&_ M1, _const sMatrixf&_ M2) -> _sMatrixf_: Multiply two matrix. 
- __iMath::MatrixDeterminant2__(_const sMatrixf&_ M) -> _tF32_: Compute the top left 2x2 matrix determinant. 
- __iMath::MatrixDeterminant3__(_const sMatrixf&_ M) -> _tF32_: Compute the top left 3x3 matrix determinant. 
- __iMath::MatrixDeterminant__(_const sMatrixf&_ M) -> _tF32_: Compute matrix determinant. 
- __iMath::MatrixGetHandeness__(_const sMatrixf&_ M) -> _tF32_: Compute matrix handeness. 
- __iMath::MatrixInverse__(_const sMatrixf&_ M) -> _sMatrixf_: Inverse the given matrix. 
- __iMath::MatrixTransformInverse__(_const sMatrixf&_ M) -> _sMatrixf_: Inverse the transformation part. Means transpose the rotation and negate the translation. 
- __iMath::MatrixLookAtRH__(_const sVec3f&_ Eye, _const sVec3f&_ At, _const sVec3f&_ Up) -> _sMatrixf_: Make a right handed look at matrix. 
- __iMath::MatrixLookAtLH__(_const sVec3f&_ Eye, _const sVec3f&_ At, _const sVec3f&_ Up) -> _sMatrixf_: Make a left handed look at matrix. 
- __iMath::MatrixOrthoRH__(_tF32_ w, _tF32_ h, _tF32_ zn, _tF32_ zf) -> _sMatrixf_: Make a right handed orthogonal projection matrix. 
- __iMath::MatrixOrthoLH__(_tF32_ w, _tF32_ h, _tF32_ zn, _tF32_ zf) -> _sMatrixf_: Make a left handed orthogonal projection matrix. 
- __iMath::MatrixOrthoOffCenterRH__(_tF32_ l, _tF32_ r, _tF32_ t, _tF32_ b, _tF32_ zn, _tF32_ zf) -> _sMatrixf_: Make a right handed orthogonal projection matrix. 
- __iMath::MatrixOrthoOffCenterLH__(_tF32_ l, _tF32_ r, _tF32_ t, _tF32_ b, _tF32_ zn, _tF32_ zf) -> _sMatrixf_: Make a left handed orthogonal projection matrix. 
- __iMath::MatrixPerspectiveRH__(_tF32_ w, _tF32_ h, _tF32_ zn, _tF32_ zf) -> _sMatrixf_: Make a right handed perspective projection matrix. 
- __iMath::MatrixPerspectiveLH__(_tF32_ w, _tF32_ h, _tF32_ zn, _tF32_ zf) -> _sMatrixf_: Make a left handed perspective projection matrix. 
- __iMath::MatrixPerspectiveFovRH__(_tF32_ fovy, _tF32_ aspect, _tF32_ zn, _tF32_ zf) -> _sMatrixf_: Make a right handed perspective projection matrix. 
- __iMath::MatrixPerspectiveFovLH__(_tF32_ fovy, _tF32_ aspect, _tF32_ zn, _tF32_ zf) -> _sMatrixf_: Make a left handed perspective projection matrix. 
- __iMath::MatrixPerspectiveOffCenterRH__(_tF32_ l, _tF32_ r, _tF32_ t, _tF32_ b, _tF32_ zn, _tF32_ zf) -> _sMatrixf_: Make a right handed perspective projection matrix. 
- __iMath::MatrixPerspectiveOffCenterLH__(_tF32_ l, _tF32_ r, _tF32_ t, _tF32_ b, _tF32_ zn, _tF32_ zf) -> _sMatrixf_: Make a left handed perspective projection matrix. 
- __iMath::MatrixReflect__(_const sPlanef&_ Plane) -> _sMatrixf_: Make a reflection matrix. 
- __iMath::MatrixRotationAxis__(_const sVec3f&_ V, _tF32_ angle) -> _sMatrixf_: Make a rotation matrix. 
- __iMath::MatrixRotationQuat__(_const sQuatf&_ Q) -> _sMatrixf_: Make a rotation matrix. 
- __iMath::MatrixRotationX__(_tF32_ angle) -> _sMatrixf_: Make a rotation matrix. 
- __iMath::MatrixRotationY__(_tF32_ angle) -> _sMatrixf_: Make a rotation matrix. 
- __iMath::MatrixRotationZ__(_tF32_ angle) -> _sMatrixf_: Make a rotation matrix. 
- __iMath::MatrixRotationYawPitchRoll__(_tF32_ yaw, _tF32_ pitch, _tF32_ roll) -> _sMatrixf_: Make a rotation matrix. 
- __iMath::MatrixDecomposeYawPitchRoll__(_const sMatrixf&_ M) -> _sVec3f_: Extract the rotation contained in the provided matrix as yaw/heading/Y, pitch/X and roll/bank/Z in radians. \see MatrixRotationYawPitchRoll 
- __iMath::MatrixScaling__(_const sVec3f&_ V) -> _sMatrixf_: Make a scaling matrix. 
- __iMath::MatrixVecScale__(_const sMatrixf&_ M, _const sVec3f&_ V) -> _sMatrixf_: Scale a matrix. 
- __iMath::MatrixShadow__(_const sVec4f&_ vLight, _const sPlanef&_ Plane) -> _sMatrixf_: Make a shadow projection matrix. 
- __iMath::MatrixTranslation__(_const sVec3f&_ V) -> _sMatrixf_: Make a translation matrix. 
- __iMath::MatrixTranspose__(_const sMatrixf&_ M) -> _sMatrixf_: Transpose a matrix. 
- __iMath::MatrixTranspose3x3__(_const sMatrixf&_ M) -> _sMatrixf_: Transpose a matrix. 
- __iMath::MatrixTextureOffset__(_tF32_ fBias, _tI32_ nTexW, _tI32_ nTexH) -> _sMatrixf_: Texture offset matrix. 
- __iMath::MatrixTextureOffset2__(_tF32_ fBias, _tI32_ nTexW, _tI32_ nTexH, _tI32_ nDepthBits) -> _sMatrixf_: Texture offset matrix that takes in account a bit depth. 
- __iMath::MatrixGetForward__(_const sMatrixf&_ M) -> _sVec3f_: Get the forward vector of a matrix. 
- __iMath::MatrixGetUp__(_const sMatrixf&_ M) -> _sVec3f_: Get the up vector of a matrix. 
- __iMath::MatrixGetRight__(_const sMatrixf&_ M) -> _sVec3f_: Get the right vector of a matrix. 
- __iMath::MatrixGetTranslation__(_const sMatrixf&_ M) -> _sVec3f_: Get the translation vector of a matrix. 
- __iMath::MatrixSetForward__(_const sMatrixf&_ M, _const sVec3f&_ V) -> _sMatrixf_: Set the forward vector of a matrix. 
- __iMath::MatrixSetUp__(_const sMatrixf&_ M, _const sVec3f&_ V) -> _sMatrixf_: Set the up vector of a matrix. 
- __iMath::MatrixSetRight__(_const sMatrixf&_ M, _const sVec3f&_ V) -> _sMatrixf_: Set the right vector of a matrix. 
- __iMath::MatrixSetTranslation__(_const sMatrixf&_ M, _const sVec3f&_ V) -> _sMatrixf_: Set the translation vector of a matrix. 
- __iMath::MatrixIsNormal__(_const sMatrixf&_ M) -> _tBool_: Check if a matrix is normalized. 
- __iMath::MatrixIsOrthogonal__(_const sMatrixf&_ M) -> _tBool_: Check if a matrix is orthogonal. 
- __iMath::MatrixIsOrthoNormal__(_const sMatrixf&_ M) -> _tBool_: Check if a matrix is orthonormal. 
- __iMath::MatrixSetRotation__(_const sMatrixf&_ In, _const sMatrixf&_ RotM) -> _sMatrixf_: Set the rotation part of a matrix. 
- __iMath::MatrixToEuler__(_const sMatrixf&_ M) -> _sVec3f_: Get euler angles from a rotation matrix. 
- __iMath::MatrixToCoordinateSystem__(_const sVec3f&_ avRight, _const sVec3f&_ avUp, _const sVec3f&_ avFwd, _const sVec3f&_ avOrg) -> _sMatrixf_: Make a coordinate system conversion matrix. 
- __iMath::MatrixGetProjectedTranslation__(_const sMatrixf&_ In) -> _sVec3f_: Get the translation by 'unprojecting' the translation from the matrix's axis (translation of inverse matrix). 
- __iMath::MatrixSetProjectedTranslation__(_const sMatrixf&_ In, _const sVec3f&_ avT) -> _sMatrixf_: Set the translation by projecting it onto the matrix's axis. 
- __iMath::MatrixSetNotRotation__(_const sMatrixf&_ In, _const sMatrixf&_ M) -> _sMatrixf_: Set the non-rotation part of the matrix. 
- __iMath::MatrixRotate__(_const sMatrixf&_ M1, _const sMatrixf&_ M2) -> _sMatrixf_: Rotate the matrix, this affects only the 3x3 top-left rotation part of the matrix. 
- __iMath::MatrixViewport__(_const sVec4f&_ aVP, _tF32_ afMinZ, _tF32_ afMaxZ) -> _sMatrixf_: Compute a viewport matrix. 
- __iMath::MatrixAdjustViewport__(_const sVec4f&_ aContextVP, _const sVec4f&_ aVirtualVP, _tF32_ afMinZ, _tF32_ afMaxZ) -> _sMatrixf_: Compute a matrix that will compensate the projection matrix to fit into a viewport which is different of the context/physical viewport. 
- __iMath::MatrixDecomposeGetTranslation__(_const sMatrixf&_ aMatrix) -> _sVec3f_: Get the translation part of a matrix. 
- __iMath::MatrixDecomposeGetZYX__(_const sMatrixf&_ aMatrix) -> _sVec3f_: Get the rotation part of a matrix as euler angle in the Z*Y*X rotation order. 
- __iMath::MatrixDecomposeGetQuat__(_const sMatrixf&_ aMatrix) -> _sQuatf_: Get the rotation part of a matrix as a quaternion. 
- __iMath::MatrixDecomposeGetScale__(_const sMatrixf&_ aMatrix) -> _sVec4f_: Get the local scaling part of a matrix (x,y,z,handness) 
- __iMath::MatrixCompose__(_const sVec3f&_ aT, _const sVec3f&_ aZYX, _const sVec4f&_ aS) -> _sMatrixf_: Build a matrix from a translation, zyx euler rotation and scale. 
- __iMath::MatrixComposeQ__(_const sVec3f&_ aT, _const sQuatf&_ aQ, _const sVec4f&_ aS) -> _sMatrixf_: Build a matrix from a translation, rotation quaternion and scale. 
- __iMath::QuatIdentity__() -> _sQuatf_: Get the identity quaternion. 
- __iMath::QuatIsIdentity__(_const sQuatf&_ Q) -> _tBool_: Check if the quaternion is identity. 
- __iMath::QuatAdd__(_const sQuatf&_ aLeft, _const sQuatf&_ aRight) -> _sQuatf_: Add. 
- __iMath::QuatSub__(_const sQuatf&_ aLeft, _const sQuatf&_ aRight) -> _sQuatf_: Subtract. 
- __iMath::QuatScale__(_const sQuatf&_ aLeft, _tF32_ afRight) -> _sQuatf_: Scale. 
- __iMath::QuatCompare__(_const sQuatf&_ aLeft, _const sQuatf&_ aRight) -> _tI32_: Compare. 
- __iMath::QuatBaryCentric__(_const sQuatf&_ Q1, _const sQuatf&_ Q2, _const sQuatf&_ Q3, _tF32_ f, _tF32_ g) -> _sQuatf_: BaryCenter. 
- __iMath::QuatConjugate__(_const sQuatf&_ Q) -> _sQuatf_: Quat conjugate. 
- __iMath::QuatDot__(_const sQuatf&_ Q1, _const sQuatf&_ Q2) -> _tF32_: Quat dot. 
- __iMath::QuatExp__(_const sQuatf&_ Q) -> _sQuatf_: Quat exponentials. 
- __iMath::QuatInverse__(_const sQuatf&_ Q) -> _sQuatf_: Quat inverse. 
- __iMath::QuatLength__(_const sQuatf&_ Q) -> _tF32_: Quat length. 
- __iMath::QuatLengthSq__(_const sQuatf&_ Q) -> _tF32_: Quat length squared. 
- __iMath::QuatLn__(_const sQuatf&_ Q) -> _sQuatf_: Calculates the natural logarithm. 
- __iMath::QuatMultiply__(_const sQuatf&_ Q1, _const sQuatf&_ Q2) -> _sQuatf_: Quat multiply. 
- __iMath::QuatNormalize__(_const sQuatf&_ Q) -> _sQuatf_: Quat normalize. 
- __iMath::QuatRotationAxis__(_const sVec3f&_ V, _tF32_ angle) -> _sQuatf_: Rotation quaternion. 
- __iMath::QuatRotationX__(_tF32_ angle) -> _sQuatf_: Rotation quaternion. 
- __iMath::QuatRotationY__(_tF32_ angle) -> _sQuatf_: Rotation quaternion. 
- __iMath::QuatRotationZ__(_tF32_ angle) -> _sQuatf_: Rotation quaternion. 
- __iMath::QuatRotationXYZ__(_const sVec3f&_ V) -> _sQuatf_: Rotation quaternion. 
- __iMath::QuatRotationMatrix__(_const sMatrixf&_ M) -> _sQuatf_: Rotation quaternion. 
- __iMath::QuatRotationYawPitchRoll__(_const tF32_ yaw, _const tF32_ pitch, _const tF32_ roll) -> _sQuatf_: Rotation quaternion. 
- __iMath::QuatRotationVector__(_const sVec3f&_ vFrom, _const sVec3f&_ vTo) -> _sQuatf_: Rotation quaternion. 
- __iMath::QuatSlerp__(_const sQuatf&_ Q1, _const sQuatf&_ Q2, _tF32_ t, _eQuatSlerp_ mode) -> _sQuatf_: Quat slerp. 
- __iMath::QuatSquad__(_const sQuatf&_ Q1, _const sQuatf&_ Q2, _const sQuatf&_ Q3, _const sQuatf&_ Q4, _tF32_ t) -> _sQuatf_: Quat squad. 
- __iMath::QuatToAxisAngle__(_const sQuatf&_ Q) -> _sVec4f_: Quat to axis angle. 
- __iMath::QuatToEuler__(_const sQuatf&_ Q) -> _sVec3f_: Quat to euler. 
- __iMath::PlaneDot__(_const sPlanef&_ P, _const sVec4f&_ V) -> _tF32_: 4D dot product between a plane and a 4d vector. 
- __iMath::PlaneDotCoord__(_const sPlanef&_ P, _const sVec3f&_ V) -> _tF32_: 4D dot product between a plane and a 3d vector (w is assumed 1). 
- __iMath::PlaneDotNormal__(_const sPlanef&_ P, _const sVec3f&_ V) -> _tF32_: 3D dot product between a plane and a 3d vector. 
- __iMath::PlaneDistance__(_const sPlanef&_ P, _const sVec3f&_ V) -> _tF32_: Distance between a plane and the specified point. 
- __iMath::PlaneFromPointNormal__(_const sVec3f&_ vPoint, _const sVec3f&_ vNormal) -> _sPlanef_: Construct a plane from a point and a normal. 
- __iMath::PlaneFromPoints__(_const sVec3f&_ V1, _const sVec3f&_ V2, _const sVec3f&_ V3) -> _sPlanef_: Construct a plane from three points. 
- __iMath::PlaneIntersectLine__(_const sPlanef&_ P, _const sVec3f&_ V1, _const sVec3f&_ V2) -> _sVec4f_: Compute the intersection between a plane and a line. 
- __iMath::PlaneIntersectRay__(_const sPlanef&_ P, _const sVec3f&_ avRayPos, _const sVec3f&_ avRayDir) -> _sVec4f_: Compute the intersection between a plane and a ray. 
- __iMath::PlaneNormalize__(_const sPlanef&_ P) -> _sPlanef_: Normalize the specified plane. 
- __iMath::PlaneTransform__(_const sPlanef&_ P, _const sMatrixf&_ M) -> _sPlanef_: Transform the plane by the specified matrix. 
- __iMath::PlaneTransformInversedMatrix__(_const sPlanef&_ P, _const sMatrixf&_ M) -> _sPlanef_: Transform the plane by the inverse of the specified matrix. 
- __iMath::PlaneIntersection__(_const sPlanef&_ PA, _const sPlanef&_ PB, _const sPlanef&_ PC) -> _sVec3f_: Get the intersection point between 3d planes. 
- __iMath::PlaneClosest__(_const sPlanef&_ P, _const sVec3f&_ A) -> _sVec3f_: Get the closest point on the plane to the specified vector. 
- __iMath::PlaneType__(_const sPlanef&_ Plane) -> _ePlaneType_: Get the type of plane. 
- __iMath::PlaneMaxType__(_const sPlanef&_ Plane) -> _ePlaneType_: Get the type of plane's maximum component. 
- __iMath::PlaneExtractCoordinateSystem__(_const sPlanef&_ Plane, _const sVec3f&_ avFwdDir) -> _sMatrixf_: Extract a coordinate system from the plane. 
- __iMath::PlaneIntersectSphere__(_const sPlanef&_ plane, _const sVec3f&_ avCenter, _const tF32_ afRadius) -> _tBool_: Check if the specified sphere intersect the specified plane. 
- __iMath::TriangleAreaNormal__(_const sVec3f&_ V0, _const sVec3f&_ V1, _const sVec3f&_ V2) -> _sVec4f_: Compute the normal and area of a triangle. 
- __iMath::TriangleIsDegenerate__(_const sVec3f&_ V0, _const sVec3f&_ V1, _const sVec3f&_ V2) -> _tBool_: Check whether the triangle is degenerated. 
- __iMath::TriangleIntersectTriangle__(_const sVec3f&_ V0, _const sVec3f&_ V1, _const sVec3f&_ V2, _const sVec3f&_ U0, _const sVec3f&_ U1, _const sVec3f&_ U2) -> _tBool_: Check triangle-triangle intersection. 
- __iMath::TriangleIntersectRay__(_const sVec3f&_ avOrigin, _const sVec3f&_ avDir, _const sVec3f&_ V0, _const sVec3f&_ V1, _const sVec3f&_ V2) -> _sVec3f_: Check triangle-ray intersection. 
- __iMath::TriangleIntersectRayCull__(_const sVec3f&_ avOrigin, _const sVec3f&_ avDir, _const sVec3f&_ V0, _const sVec3f&_ V1, _const sVec3f&_ V2) -> _sVec3f_: Check triangle-ray intersection with culling. 
- __iMath::TriangleIntersectAABB__(_const sVec3f&_ V0, _const sVec3f&_ V1, _const sVec3f&_ V2, _const sVec3f&_ avMin, _const sVec3f&_ avMax) -> _tBool_: Check triangle-aabb intersection. 
- __iMath::TriangleBaryCentric__(_const sVec3f&_ A, _const sVec3f&_ B, _const sVec3f&_ C, _const sVec3f&_ P) -> _sVec3f_: Compute the barycentric coordinates of the specified point. 
- __iMath::WrapFloat__(_tF32_ aX, _tF32_ aMin, _tF32_ aMax) -> _tF32_: Wrap a floating value between the specified min and max values. 
- __iMath::WrapInt__(_tI32_ aX, _tI32_ aMin, _tI32_ aMax) -> _tI32_: Wrap an integer value between the specified min and max values. 
- __iMath::WrapRad__(_tF32_ aX) -> _tF32_: Wrap a radian between 0 and 2pi. 
- __iMath::WrapRad2__(_tF32_ aX) -> _tF32_: Wrap a radian between -pi and pi. 
- __iMath::GetAngleFromPoints2D__(_const sVec2f&_ aStartPos, _const sVec2f&_ aGoalPos) -> _tF32_: Get the angle between two 2d vectors, returns an angle in [0;2pi] 
- __iMath::GetAngleFromPoints3D__(_const sVec3f&_ aStartPos, _const sVec3f&_ aGoalPos) -> _sVec2f_: Get the angles between two 3d vectors. 
- __iMath::ClassifyPoint__(_const sPlanef&_ plane, _const sVec3f&_ point) -> _eClassify_: Check whether a point is in-front, behind or on a plane. 
- __iMath::IsPointInsideEdge__(_const sVec3f&_ A, _const sVec3f&_ B, _const sVec3f&_ P) -> _tBool_: Check whether a point is on the specified edge. 
- __iMath::ClosestPointOnLine__(_const sVec3f&_ A, _const sVec3f&_ B, _const sVec3f&_ P) -> _sVec3f_: Return the closest point to the specified vector P on the specified AB line. 
- __iMath::ClosestPointOnTriangle__(_const sVec3f&_ A, _const sVec3f&_ B, _const sVec3f&_ C, _const sVec3f&_ P) -> _sVec3f_: Return the closest point to the specified vector P on the specified ABC triangle. 
- __iMath::GetAngularDifference__(_tF32_ afA, _tF32_ afB) -> _tF32_: Get the shortest 'distance' (angular difference) between two angles, no matter if the angles are in the [0;pi][-0;-pi] range or the [0;2pi] range. 
- __iMath::GetScreenPosition__(_const sVec3f&_ avPos, _const sMatrixf&_ mtxVP, _const sRectf&_ aRect) -> _sVec3f_: Get the screen position of the specified 3d world position. 
- __iMath::Vec3SphericalToCartesian__(_const sVec3f&_ avS) -> _sVec3f_: Convert a 3d spherical coordinate to a 3d cartesian coordinate. 
- __iMath::Vec3CartesianToSpherical__(_const sVec3f&_ avC) -> _sVec3f_: Convert a 3d cartesian coordinate to a 3d spherical coordinate. 
- __iMath::Vec3OrbitPitch__(_const sVec3f&_ aTarget, _const sVec3f&_ aPos, _tF32_ afPitch) -> _sVec3f_: Orbit/rotate a 3d position of the specified yaw (Y-axis) angle around the specified target. 
- __iMath::Vec3OrbitYaw__(_const sVec3f&_ aTarget, _const sVec3f&_ aPos, _tF32_ afYaw) -> _sVec3f_: Orbit/rotate a 3d position of the specified pitch (X-axis) angle around the specified target. 
- __iMath::Vec3OrbitYawPitch__(_const sVec3f&_ aTarget, _const sVec3f&_ aPos, _tF32_ afYaw, _tF32_ afPitch) -> _sVec3f_: Orbit/rotate a 3d position of the specified yaw (Y-axis) and then pitch (X-axis) angle around the specified target. 
- __iMath::ComputePixelScaleX__(_const sVec3f&_ aPos, _const sMatrixf&_ amtxWorldView, _const sMatrixf&_ amtxProj, _const sRectf&_ aVP) -> _tF32_: Compute a pixel to world unit scale value, based on the X-axis delta. 
- __iMath::ComputePixelScaleY__(_const sVec3f&_ aPos, _const sMatrixf&_ amtxWorldView, _const sMatrixf&_ amtxProj, _const sRectf&_ aVP) -> _tF32_: Compute a pixel to world unit scale value, based on the Y-axis delta. 
- __iMath::ComputePixelWorldSizeX__(_const tF32_ afPixelSize, _const sVec3f&_ avPos, _const sMatrixf&_ mtxWorldView, _const sMatrixf&_ mtxProj, _const sRectf&_ aVP) -> _tF32_: Compute the world size of the given pixel size, scale based on the X-axis delta. 
- __iMath::ComputePixelWorldSizeY__(_const tF32_ afPixelSize, _const sVec3f&_ avPos, _const sMatrixf&_ mtxWorldView, _const sMatrixf&_ mtxProj, _const sRectf&_ aVP) -> _tF32_: Compute the world size of the given pixel size, scale based on the Y-axis delta. 
- __iMath::ComputePixelWorldSizeVec2__(_const tF32_ afPixelSize, _const sVec3f&_ avPos, _const sMatrixf&_ mtxWorldView, _const sMatrixf&_ mtxProj, _const sRectf&_ aVP) -> _sVec2f_: Compute the world size of the given pixel size, scale based on the X and Y axis delta. 
- __iMath::ComputePixelWorldSize__(_const tF32_ afPixelSize, _const sVec3f&_ avPos, _const sMatrixf&_ amtxWorldView, _const sMatrixf&_ amtxProj, _const sRectf&_ aVP) -> _tF32_: Compute the world size of the give pixel size, scale based on the axis with the highest resolution. 
- __iMath::Det2x2f__(_const tF32_ a, _const tF32_ b, _const tF32_ c, _const tF32_ d) -> _tF32_: Computes a 2x2 matrix determinant. 
- __iMath::Det3x3f__(_const tF32_ a0, _const tF32_ a1, _const tF32_ a2, _const tF32_ a3, _const tF32_ a4, _const tF32_ a5, _const tF32_ a6, _const tF32_ a7, _const tF32_ a8) -> _tF32_: Computes a 3x3 matrix determinant. 
- __iMath::Det4x4f__(_const tF32_ a0, _const tF32_ a1, _const tF32_ a2, _const tF32_ a3, _const tF32_ a4, _const tF32_ a5, _const tF32_ a6, _const tF32_ a7, _const tF32_ a8, _const tF32_ a9, _const tF32_ a10, _const tF32_ a11, _const tF32_ a12, _const tF32_ a13, _const tF32_ a14, _const tF32_ a15) -> _tF32_: Computes a 4x4 matrix determinant. 
- __iMath::Det2x2d__(_const tF64_ a, _const tF64_ b, _const tF64_ c, _const tF64_ d) -> _tF64_: Computes a 2x2 matrix determinant. 
- __iMath::Det3x3d__(_const tF64_ a0, _const tF64_ a1, _const tF64_ a2, _const tF64_ a3, _const tF64_ a4, _const tF64_ a5, _const tF64_ a6, _const tF64_ a7, _const tF64_ a8) -> _tF64_: Computes a 3x3 matrix determinant. 
- __iMath::Det4x4d__(_const tF64_ a0, _const tF64_ a1, _const tF64_ a2, _const tF64_ a3, _const tF64_ a4, _const tF64_ a5, _const tF64_ a6, _const tF64_ a7, _const tF64_ a8, _const tF64_ a9, _const tF64_ a10, _const tF64_ a11, _const tF64_ a12, _const tF64_ a13, _const tF64_ a14, _const tF64_ a15) -> _tF64_: Computes a 4x4 matrix determinant. 
- __iMath::FovHzToVt__(_tF32_ afHFov, _tF32_ afWbyHAspect) -> _tF32_: Convert an horizontal fov to a vertical fov. 
- __iMath::FovVtToHz__(_tF32_ afVFov, _tF32_ afWbyHAspect) -> _tF32_: Convert a vertical fov to an horizontal fov. 
- __iMath::ClampT__(_tF64_ aX, _tF64_ aMin, _tF64_ aMax) -> _tF64_
- __iMath::RepeatT__(_tF64_ aX, _tF64_ aMin, _tF64_ aMax) -> _tF64_
- __iMath::MirrorT__(_tF64_ aX, _tF64_ aMin, _tF64_ aMax) -> _tF64_
- __iMath::CycleT__(_tF64_ aX, _tF64_ aMin, _tF64_ aMax) -> _tF64_
- __iMath::CurveStep__(_tF64_ a, _tF64_ b, _tF64_ t) -> _tF64_
- __iMath::CurveLinear__(_tF64_ V1, _tF64_ V2, _tF64_ s) -> _tF64_
- __iMath::CurveCos__(_tF64_ a, _tF64_ b, _tF64_ t) -> _tF64_
- __iMath::CurveHermite__(_tF64_ V1, _tF64_ T1, _tF64_ V2, _tF64_ T2, _tF64_ s) -> _tF64_
- __iMath::CurveCatmullRom__(_tF64_ V1, _tF64_ V2, _tF64_ V3, _tF64_ V4, _tF64_ s) -> _tF64_
- __iMath::CurveCardinal__(_tF64_ V1, _tF64_ V2, _tF64_ s, _tF64_ a) -> _tF64_
- __iMath::CurveCardinal4__(_tF64_ V1, _tF64_ V2, _tF64_ V3, _tF64_ V4, _tF64_ s, _tF64_ a) -> _tF64_
- __iMath::CycleLinear__(_tF64_ aX, _tF64_ aMin, _tF64_ aMax) -> _tF64_
- __iMath::CycleCos__(_tF64_ aX, _tF64_ aMin, _tF64_ aMax) -> _tF64_
- __iMath::CycleCardinal__(_tF64_ aX, _tF64_ aMin, _tF64_ aMax, _tF64_ a) -> _tF64_
- __iMath::ProbSum__(_tF64CVec\*_ apProbs) -> _tF64_
- __iMath::ProbNormalize__(_tF64CVec\*_ apProbs) -> _tBool_
- __iMath::ProbSampleBuildAliasMethodArrays__(_const tF64CVec\*_ apProbs, _tF64CVec\*_ apAMQ, _tU32CVec\*_ apAMA) -> _tBool_
- __iMath::ProbSampleAliasMethod__(_tU32CVec\*_ apResults, _const tF64CVec\*_ apAMQ, _const tU32CVec\*_ apAMA) -> _tBool_

## enum ni::eClassify
Values returned by the classification functions 

### Remarks:
- Classification values can be combined as flags. 

### Values:
- __eClassify_Front__ = __niBit(0)__
- __eClassify_Back__ = __niBit(1)__
- __eClassify_Coplanar__ = __niBit(2)__
- __eClassify_Spanned__ = __niBit(3)__

## enum ni::eOSProcessSpawnFlags
OS Process spawning flags. 

### Values:
- __eOSProcessSpawnFlags_None__ = __0__: No flags/default 
- __eOSProcessSpawnFlags_StdFiles__ = __niBit(0)__: Create stdin/out/err. 
- __eOSProcessSpawnFlags_DifferentStdOutAndStdErr__ = __niBit(1)__: Indicates that we want different pipes for StdOut and StdErr. 
- __eOSProcessSpawnFlags_SandBox__ = __niBit(2)__: Create the process in sand boxed environment. 
- __eOSProcessSpawnFlags_Detached__ = __niBit(3)__: Create the process an independant process. 

## enum ni::eOSProcessFile
OS Process standard file objects. 

### Values:
- __eOSProcessFile_StdIn__ = __0__: Stdin file object. 
- __eOSProcessFile_StdOut__ = __1__: Stdout file object. 
- __eOSProcessFile_StdErr__ = __2__: Stderr file object. 
- __eOSProcessFile_Last__ = __3__: \internal 

## interface ni::iOSProcess
OS Process object interface. 

### Parents:
- iUnknown

### Methods:
- __iOSProcess::GetExePath__() -> _const ni::achar\*_: Get the path of the executable from which the process has been spawned. 
- __iOSProcess::GetCommandLine__() -> _const ni::achar\*_: Get the command line used to spawn the process. 
- __iOSProcess::GetPID__() -> _tInt_: Get the process's PID. 
- __iOSProcess::GetParentPID__() -> _tInt_: Get the parent process's PID. 
- __iOSProcess::IsParentProcess__(_tInt_ aParentPID) -> _tU32_: Check whether the parent process is a parent of this process. 
- __iOSProcess::GetIsCurrent__() -> _tBool_: Get whether the process is the current process. 
- __iOSProcess::GetDidCrash__() -> _tBool_: Get the termination status (exit code) of the process and return true if the status indicates that the process crashed. 
- __iOSProcess::Kill__(_tInt_ anExitCode, _tBool_ abWait) -> _tBool_: Attempts to kill the process, giving it a specified exit code. 
- __iOSProcess::Wait__(_tU32_ anTimeoutMs) -> _tBool_: Wait for the process to exit. 
- __iOSProcess::WaitForExitCode__(_tU32_ anTimeoutMs) -> _sVec2i_: Waits for process to exit. In POSIX systems, if the process hasn't been signaled then returns the exit code; otherwise it's considered a failure. On Windows the exit code is always returned. 
- __iOSProcess::Terminate__(_tInt_ aResultCode) -> _void_: Terminates the process with extreme prejudice. The given result code will be the exit code of the process. If the process has already exited, this will do nothing. 
- __iOSProcess::GetFile__(_eOSProcessFile_ aFile) -> _iFile\*_: Get a standard file object beloging to the process. 

## interface ni::iOSProcessEnumSink
OS Process enum sink. 

### Parents:
- iUnknown

### Methods:
- __iOSProcessEnumSink::OnOSProcessEnumSink__(_tIntPtr_ aPID, _tIntPtr_ aParentPID, _const ni::achar\*_ aaszExeName) -> _ni::tBool_: Called when a process has been found. 

## interface ni::iOSProcessManager
OS Process Manager 

### Parents:
- iUnknown

### Methods:
- __iOSProcessManager::GetCurrentProcessID__() -> _tInt_: Return the id of the current process. 
- __iOSProcessManager::GetCurrentProcess__() -> _iOSProcess\*_: Return a process object of the current process. 
- __iOSProcessManager::CreateProcess__(_tInt_ aPID) -> _iOSProcess\*_: Create a process object from the specified process id. 
- __iOSProcessManager::SpawnProcess__(_const ni::achar\*_ aaszCmdLine, _tOSProcessSpawnFlags_ aSpawn) -> _iOSProcess\*_: Spawn a new process. \see ni::iOSProcessManager::SpawnProcessEx 
- __iOSProcessManager::SpawnProcessEx__(_const ni::achar\*_ aaszCmdLine, _const achar\*_ aaszWorkDir, _const tStringCMap\*_ apEnvs, _tOSProcessSpawnFlags_ aSpawn) -> _iOSProcess\*_: Spawn a new process with the specified working directory and environment variables. 
- __iOSProcessManager::EnumProcesses__(_ni::iRegex\*_ apFilter, _iOSProcessEnumSink\*_ apSink) -> _tU32_: Enumerates all processes. 
- __iOSProcessManager::GetCwd__() -> _cString_: Get the current working directory. 
- __iOSProcessManager::GetEnvs__() -> _Ptr<tStringCMap>_: Get the current environment variables. 

## enum ni::eOSProcessSpawnFlags
OS Process spawning flags. 

### Values:
- __eOSProcessSpawnFlags_None__ = __0__: No flags/default 
- __eOSProcessSpawnFlags_StdFiles__ = __niBit(0)__: Create stdin/out/err. 
- __eOSProcessSpawnFlags_DifferentStdOutAndStdErr__ = __niBit(1)__: Indicates that we want different pipes for StdOut and StdErr. 
- __eOSProcessSpawnFlags_SandBox__ = __niBit(2)__: Create the process in sand boxed environment. 
- __eOSProcessSpawnFlags_Detached__ = __niBit(3)__: Create the process an independant process. 

## enum ni::eKey
Key codes 

### Values:
- __eKey_Unknown__ = __0x00__
- __eKey_Escape__ = __0x01__
- __eKey_n1__ = __0x02__
- __eKey_n2__ = __0x03__
- __eKey_n3__ = __0x04__
- __eKey_n4__ = __0x05__
- __eKey_n5__ = __0x06__
- __eKey_n6__ = __0x07__
- __eKey_n7__ = __0x08__
- __eKey_n8__ = __0x09__
- __eKey_n9__ = __0x0A__
- __eKey_n0__ = __0x0B__
- __eKey_Minus__ = __0x0C__
- __eKey_Equals__ = __0x0D__
- __eKey_BackSpace__ = __0x0E__
- __eKey_Tab__ = __0x0F__
- __eKey_Q__ = __0x10__
- __eKey_W__ = __0x11__
- __eKey_E__ = __0x12__
- __eKey_R__ = __0x13__
- __eKey_T__ = __0x14__
- __eKey_Y__ = __0x15__
- __eKey_U__ = __0x16__
- __eKey_I__ = __0x17__
- __eKey_O__ = __0x18__
- __eKey_P__ = __0x19__
- __eKey_LBracket__ = __0x1A__
- __eKey_RBracket__ = __0x1B__
- __eKey_Enter__ = __0x1C__
- __eKey_LControl__ = __0x1D__
- __eKey_A__ = __0x1E__
- __eKey_S__ = __0x1F__
- __eKey_D__ = __0x20__
- __eKey_F__ = __0x21__
- __eKey_G__ = __0x22__
- __eKey_H__ = __0x23__
- __eKey_J__ = __0x24__
- __eKey_K__ = __0x25__
- __eKey_L__ = __0x26__
- __eKey_Semicolon__ = __0x27__
- __eKey_Apostrophe__ = __0x28__
- __eKey_Grave__ = __0x29__
- __eKey_Tilde__ = __0x29__
- __eKey_LShift__ = __0x2A__
- __eKey_BackSlash__ = __0x2B__
- __eKey_Z__ = __0x2C__
- __eKey_X__ = __0x2D__
- __eKey_C__ = __0x2E__
- __eKey_V__ = __0x2F__
- __eKey_B__ = __0x30__
- __eKey_N__ = __0x31__
- __eKey_M__ = __0x32__
- __eKey_Comma__ = __0x33__
- __eKey_Period__ = __0x34__
- __eKey_Slash__ = __0x35__
- __eKey_RShift__ = __0x36__
- __eKey_NumPadStar__ = __0x37__
- __eKey_LAlt__ = __0x38__
- __eKey_Space__ = __0x39__
- __eKey_CapsLock__ = __0x3A__
- __eKey_F1__ = __0x3B__
- __eKey_F2__ = __0x3C__
- __eKey_F3__ = __0x3D__
- __eKey_F4__ = __0x3E__
- __eKey_F5__ = __0x3F__
- __eKey_F6__ = __0x40__
- __eKey_F7__ = __0x41__
- __eKey_F8__ = __0x42__
- __eKey_F9__ = __0x43__
- __eKey_F10__ = __0x44__
- __eKey_NumLock__ = __0x45__
- __eKey_Scroll__ = __0x46__
- __eKey_NumPad7__ = __0x47__
- __eKey_NumPad8__ = __0x48__
- __eKey_NumPad9__ = __0x49__
- __eKey_NumPadMinus__ = __0x4A__
- __eKey_NumPad4__ = __0x4B__
- __eKey_NumPad5__ = __0x4C__
- __eKey_NumPad6__ = __0x4D__
- __eKey_NumPadPlus__ = __0x4E__
- __eKey_NumPad1__ = __0x4F__
- __eKey_NumPad2__ = __0x50__
- __eKey_NumPad3__ = __0x51__
- __eKey_NumPad0__ = __0x52__
- __eKey_NumPadPeriod__ = __0x53__
- __eKey_OEM_102__ = __0x56__
- __eKey_F11__ = __0x57__
- __eKey_F12__ = __0x58__
- __eKey_F13__ = __0x64__
- __eKey_F14__ = __0x65__
- __eKey_F15__ = __0x66__
- __eKey_Kana__ = __0x70__
- __eKey_ABNT_C1__ = __0x73__
- __eKey_Convert__ = __0x79__
- __eKey_NoConvert__ = __0x7B__
- __eKey_Yen__ = __0x7D__
- __eKey_ABNT_C2__ = __0x7E__
- __eKey_NumPadEquals__ = __0x8D__
- __eKey_Circumflex__ = __0x90__
- __eKey_PrevTrack__ = __0x90__
- __eKey_AT__ = __0x91__
- __eKey_Colon__ = __0x92__
- __eKey_Underline__ = __0x93__
- __eKey_Kanji__ = __0x94__
- __eKey_Stop__ = __0x95__
- __eKey_AX__ = __0x96__
- __eKey_Unlabeled__ = __0x97__
- __eKey_NextTrack__ = __0x99__
- __eKey_NumPadEnter__ = __0x9C__
- __eKey_RControl__ = __0x9D__
- __eKey_Mute__ = __0xA0__
- __eKey_Calculator__ = __0xA1__
- __eKey_PlayPause__ = __0xA2__
- __eKey_MediaStop__ = __0xA4__
- __eKey_VolumeDown__ = __0xAE__
- __eKey_VolumeUp__ = __0xB0__
- __eKey_WebHome__ = __0xB2__
- __eKey_NumPadComma__ = __0xB3__
- __eKey_NumPadSlash__ = __0xB5__
- __eKey_SysRQ__ = __0xB7__
- __eKey_PrintScreen__ = __0xB7__
- __eKey_RAlt__ = __0xB8__
- __eKey_AltGr__ = __0xB8__
- __eKey_Pause__ = __0xC5__
- __eKey_Home__ = __0xC7__
- __eKey_Up__ = __0xC8__
- __eKey_PgUp__ = __0xC9__
- __eKey_Left__ = __0xCB__
- __eKey_Right__ = __0xCD__
- __eKey_End__ = __0xCF__
- __eKey_Down__ = __0xD0__
- __eKey_PgDn__ = __0xD1__
- __eKey_Insert__ = __0xD2__
- __eKey_Delete__ = __0xD3__
- __eKey_LWin__ = __0xDB__
- __eKey_RWin__ = __0xDC__
- __eKey_Apps__ = __0xDD__
- __eKey_Power__ = __0xDE__
- __eKey_Sleep__ = __0xDF__
- __eKey_Wake__ = __0xE3__
- __eKey_WebSearch__ = __0xE5__
- __eKey_WebFavorites__ = __0xE6__
- __eKey_WebRefresh__ = __0xE7__
- __eKey_WebStop__ = __0xE8__
- __eKey_WebForward__ = __0xE9__
- __eKey_WebBack__ = __0xEA__
- __eKey_MyComputer__ = __0xEB__
- __eKey_Mail__ = __0xEC__
- __eKey_MediaSelect__ = __0xED__
- __eKey_Last__ = __0xFF__

## enum ni::eKeyMod
Key modifier 

### Remarks:
- Starts at bit 16 so that it can be or'ed with a eKey value 

### Values:
- __eKeyMod_Control__ = __niBit(16)__
- __eKeyMod_Shift__ = __niBit(17)__
- __eKeyMod_Alt__ = __niBit(18)__
- __eKeyMod_AltGr__ = __niBit(19)__
- __eKeyMod_NumLock__ = __niBit(20)__
- __eKeyMod_CapsLock__ = __niBit(21)__
- __eKeyMod_ScrollLock__ = __niBit(22)__

## enum ni::ePointerButton
Pointer buttons 

### Values:
- __ePointerButton_Bt0__ = __0__
- __ePointerButton_Bt1__ = __1__
- __ePointerButton_Bt2__ = __2__
- __ePointerButton_Bt3__ = __3__
- __ePointerButton_Bt4__ = __4__
- __ePointerButton_Bt5__ = __5__
- __ePointerButton_Bt6__ = __6__
- __ePointerButton_Bt7__ = __7__
- __ePointerButton_Last__ = __8__
- __ePointerButton_Left__ = __ePointerButton_Bt0__
- __ePointerButton_Right__ = __ePointerButton_Bt1__
- __ePointerButton_Middle__ = __ePointerButton_Bt2__

## enum ni::ePointerAxis
Pointer axis 

### Values:
- __ePointerAxis_X__ = __0__: Pointer relative X axis. 
- __ePointerAxis_Y__ = __1__: Pointer relative Y axis. 
- __ePointerAxis_Z__ = __2__: Pointer relative Z axis. 
- __ePointerAxis_Absolute__ = __3__: Pointer absolute X/Y cursor position. 
- __ePointerAxis_Last__ = __4__: \internal 

## enum ni::eGestureState
Gesture states 

### Values:
- __eGestureState_Unknown__ = __0__: Unknown gesture state. 
- __eGestureState_Began__ = __1__: The gesture began. 
- __eGestureState_Updated__ = __2__: The gesture updated. 
- __eGestureState_Ended__ = __3__: The gesture ended. 
- __eGestureState_Cancelled__ = __4__: The gesture was cancelled. 

## enum ni::eOSWindowMessage
OS Window messages. 

### Values:
- __eOSWindowMessage_Close__ = __niMessageID('_','O','W','S','O')__: The close button of the window has been pressed. 
- __eOSWindowMessage_SwitchIn__ = __niMessageID('_','O','W','S','s')__: The window becomes active. 
- __eOSWindowMessage_SwitchOut__ = __niMessageID('_','O','W','S','S')__: The window becomes inactive. 
- __eOSWindowMessage_Drop__ = __niMessageID('_','O','W','S','r')__: Something has been dropped on the window. 
- __eOSWindowMessage_Paint__ = __niMessageID('_','O','W','P','p')__: The client should be painted. 
- __eOSWindowMessage_Size__ = __niMessageID('_','O','W','Z','z')__: The window has been resized. 
- __eOSWindowMessage_Move__ = __niMessageID('_','O','W','Z','m')__: The widnow has been moved. 
- __eOSWindowMessage_KeyDown__ = __niMessageID('_','O','W','K','d')__: A key has been pressed. 
- __eOSWindowMessage_KeyUp__ = __niMessageID('_','O','W','K','D')__: A key has been release. 
- __eOSWindowMessage_KeyChar__ = __niMessageID('_','O','W','K','c')__: A character has been entered. 
- __eOSWindowMessage_MouseMove__ = __niMessageID('_','O','W','I','m')__: The mouse has moved in the client area. 
- __eOSWindowMessage_RelativeMouseMove__ = __niMessageID('_','O','W','I','R')__: The mouse pointer has been moved. 
- __eOSWindowMessage_MouseButtonDown__ = __niMessageID('_','O','W','I','d')__: A mouse button has been pressed in the client area. 
- __eOSWindowMessage_MouseButtonUp__ = __niMessageID('_','O','W','I','u')__: A mouse button has been release in the client area. 
- __eOSWindowMessage_MouseButtonDoubleClick__ = __niMessageID('_','O','W','I','k')__: A mouse button has been double-clicked in the client area. 
- __eOSWindowMessage_MouseWheel__ = __niMessageID('_','O','W','I','w')__: The mouse wheel has move in the client area. 
- __eOSWindowMessage_LostFocus__ = __niMessageID('_','O','W','I','f')__: The window lost input focus. 
- __eOSWindowMessage_SetFocus__ = __niMessageID('_','O','W','I','F')__: The window gained input focus. 
- __eOSWindowMessage_FingerDown__ = __niMessageID('_','O','W','F','d')__: Finger down 
- __eOSWindowMessage_FingerUp__ = __niMessageID('_','O','W','F','u')__: Finger up 
- __eOSWindowMessage_FingerMove__ = __niMessageID('_','O','W','F','m')__: Finger moved 
- __eOSWindowMessage_FingerRelativeMove__ = __niMessageID('_','O','W','F','r')__: Finger relative move 
- __eOSWindowMessage_Pinch__ = __niMessageID('_','O','W','G','p')__: Pinch gesture. 

## enum ni::eOSWindowStyleFlags
OS Window style. 

### Values:
- __eOSWindowStyleFlags_Regular__ = __niBit(0)__: Regular window, with a title and the regular minimize, maximized, close buttons. 
- __eOSWindowStyleFlags_Overlay__ = __niBit(1)__: Overlay window, window without borders, buttons nor title. 
- __eOSWindowStyleFlags_Toolbox__ = __niBit(2)__: Toolbox window, smaller title bar, only with a close button, doesn't show in the taskbar. 
- __eOSWindowStyleFlags_FixedSize__ = __niBit(3)__: Ask the window to not be resizable, no resizing borders. 
- __eOSWindowStyleFlags_ClientArea__ = __niBit(4)__: Client area covering window. 
- __eOSWindowStyleFlags_NoTitle__ = __niBit(5)__: Never display a title bar. 
- __eOSWindowStyleFlags_FullBright__ = __niBit(6)__: Full bright. 
- __eOSWindowStyleFlags_FullScreen__ = __eOSWindowStyleFlags_Overlay|eOSWindowStyleFlags_FixedSize__: Fullscreen window, non-resizable overlay. 
- __eOSWindowStyleFlags_FullScreenNoTaskBar__ = __eOSWindowStyleFlags_Toolbox|eOSWindowStyleFlags_FixedSize|eOSWindowStyleFlags_NoTitle__: Fullscreen window, non-resizable overlay, doesn't appear in the taskbar. 

## enum ni::eOSWindowCreateFlags
OS Window create. 

### Values:
- __eOSWindowCreateFlags_NoThread__ = __niBit(0)__: The window's message pooling is done synchronously in iOSWindow::UpdateWindow(). 
- __eOSWindowCreateFlags_OwnHandle__ = __niBit(1)__: For CreateWindowEx, the handle passed is owned by the window object, meaning that the OS window will be destroyed when the window object is released. 
- __eOSWindowCreateFlags_SetWindowProc__ = __niBit(2)__: For CreateWindowEx, set our window proc as the window's message handler. 

## enum ni::eOSWindowShowFlags
OS Window show flags. 

### Values:
- __eOSWindowShowFlags_Hide__ = __niBit(0)__: Hide the window. 
- __eOSWindowShowFlags_Show__ = __niBit(1)__: Show the window and activate it. 
- __eOSWindowShowFlags_ShowNoActivate__ = __niBit(2)__: Show the window but dont active it. 
- __eOSWindowShowFlags_Maximize__ = __niBit(3)__: Maximize the window. 
- __eOSWindowShowFlags_Minimize__ = __niBit(4)__: Minimize the window. 
- __eOSWindowShowFlags_Restore__ = __niBit(5)__: Restore the window to it's original size (after being minimized). 

## enum ni::eOSWindowZOrder
OS Window ZOrder. 

### Values:
- __eOSWindowZOrder_Bottom__ = __0__: Put the window below all others. 
- __eOSWindowZOrder_Normal__ = __1__: Normal ZOrder. 
- __eOSWindowZOrder_TopMost__ = __2__: Put the window on top of all others. 

## enum ni::eOSCursor
OS Cursor 

### Values:
- __eOSCursor_None__ = __0__: No cursor. 
- __eOSCursor_Arrow__ = __1__: Arrow cursor. 
- __eOSCursor_Wait__ = __2__: Wait cursor. 
- __eOSCursor_ResizeVt__ = __3__: Vertical (North-South) resize cursor. 
- __eOSCursor_ResizeHz__ = __4__: Horizontal (East-West) resize cursor. 
- __eOSCursor_ResizeDiag__ = __5__: Diagnoal resize cursor. 
- __eOSCursor_Hand__ = __6__: Hand cursor. 
- __eOSCursor_Text__ = __7__: Text input cursor. 
- __eOSCursor_Help__ = __8__: Help cursor. 
- __eOSCursor_Custom__ = __100__: Use the custom cursor \see ni::iOSWindow::InitCustomCursor. 

## enum ni::eOSMonitorFlags
OS Monitor flags. 

### Values:
- __eOSMonitorFlags_Primary__ = __niBit(0)__: Primary monitor. 

## enum ni::eOSMessageBoxFlags
OS Message box flags. 

### Values:
- __eOSMessageBoxFlags_Ok__ = __niBit(0)__: Message box with one [OK] button. 
- __eOSMessageBoxFlags_OkCancel__ = __niBit(1)__: Message box with a [OK] and a [CANCEL] button. 
- __eOSMessageBoxFlags_YesNo__ = __niBit(2)__: Message box with a [YES] and a [NO] button. 
- __eOSMessageBoxFlags_IconInfo__ = __niBit(3)__: Message box with an information mark icon. 
- __eOSMessageBoxFlags_IconQuestion__ = __niBit(4)__: Message box with a question mark icon. 
- __eOSMessageBoxFlags_IconWarning__ = __niBit(5)__: Message box with a warning icon. 
- __eOSMessageBoxFlags_IconError__ = __niBit(6)__: Message box with an error icon. 
- __eOSMessageBoxFlags_IconHand__ = __niBit(7)__: Message box with a hand icon. 
- __eOSMessageBoxFlags_IconStop__ = __niBit(8)__: Message box with a stop icon. 
- __eOSMessageBoxFlags_NotTopMost__ = __niBit(9)__: Message box which doesn't stay over all other windows. 
- __eOSMessageBoxFlags_FatalError__ = __niBit(10)__: Message box will display a fatal error. 

## enum ni::eOSMessageBoxReturn
eOSMessageBoxReturn 

### Values:
- __eOSMessageBoxReturn_Error__ = __0__: Message box couldn't be displayed. 
- __eOSMessageBoxReturn_Yes__ = __1__: Yes/Ok button pressed. 
- __eOSMessageBoxReturn_OK__ = __1__: Yes/Ok button pressed. 
- __eOSMessageBoxReturn_No__ = __2__: No/Cancel button pressed. 
- __eOSMessageBoxReturn_Cancel__ = __2__: No/Cancel button pressed. 

## enum ni::eOSWindowSwitchReason
OS Window switch reason. 

### Values:
- __eOSWindowSwitchReason_Activated__ = __'a'__
- __eOSWindowSwitchReason_Deactivated__ = __'A'__
- __eOSWindowSwitchReason_LostFocus__ = __'f'__
- __eOSWindowSwitchReason_SetFocus__ = __'F'__
- __eOSWindowSwitchReason_EnterMenu__ = __'m'__
- __eOSWindowSwitchReason_LeaveMenu__ = __'M'__
- __eOSWindowSwitchReason_Minimized__ = __'z'__
- __eOSWindowSwitchReason_User__ = __256__

## interface ni::iOSGraphicsAPI
A graphics API. 

### Parents:
- iUnknown

### Methods:
- __iOSGraphicsAPI::GetName__() -> _const achar\*_

## interface ni::iOSWindow
OS Window interface. 

### Parents:
- iUnknown

### Methods:
- __iOSWindow::GetParent__() -> _iOSWindow\*_: Get the parent window if any. 
- __iOSWindow::SetClientAreaWindow__(_tIntPtr_ aHandle) -> _void_: Set a child window that should always be set to cover the window's client area. 
- __iOSWindow::GetClientAreaWindow__() -> _tIntPtr_: Get the client area window of this window. 
- __iOSWindow::GetPID__() -> _tIntPtr_: Get the process that created this window. 
- __iOSWindow::GetHandle__() -> _tIntPtr_: Get the os handle of the window. 
- __iOSWindow::GetIsHandleOwned__() -> _tBool_: Get whether the handle of the window is owned (aka will be destroyed) by the window object. 
- __iOSWindow::ActivateWindow__() -> _void_: Activate the window if the application is in the foreground. 
- __iOSWindow::GetIsActive__() -> _tBool_: Get whether the window is active or not. 
- __iOSWindow::SwitchIn__(_tU32_ anReason) -> _tBool_: Send a switch in message and set the window in active state. 
- __iOSWindow::SwitchOut__(_tU32_ anReason) -> _tBool_: Send a switch out message and set the window in inactive state. 
- __iOSWindow::SetTitle__(_const achar\*_ aaszTitle) -> _void_: Set the window's title. 
- __iOSWindow::GetTitle__() -> _const achar\*_: Get the window's title. 
- __iOSWindow::SetStyle__(_tOSWindowStyleFlags_ aStyle) -> _void_: Set the window's style. 
- __iOSWindow::GetStyle__() -> _tOSWindowStyleFlags_: Get the window's style. 
- __iOSWindow::SetShow__(_tOSWindowShowFlags_ aStyle) -> _void_: Set the window shown status. 
- __iOSWindow::GetShow__() -> _tOSWindowShowFlags_: Get the window shown status. 
- __iOSWindow::SetZOrder__(_eOSWindowZOrder_ aZOrder) -> _void_: Set the window's ZOrder. 
- __iOSWindow::GetZOrder__() -> _eOSWindowZOrder_: Get the window's ZOrder. 
- __iOSWindow::SetSize__(_const sVec2i&_ avSize) -> _void_: Set the window's size. 
- __iOSWindow::GetSize__() -> _sVec2i_: Get the window's size. 
- __iOSWindow::SetPosition__(_const sVec2i&_ avPos) -> _void_: Set the window's position. 
- __iOSWindow::GetPosition__() -> _sVec2i_: Get the window's position. 
- __iOSWindow::SetRect__(_const sRecti&_ aRect) -> _void_: Set the window's rectangle. 
- __iOSWindow::GetRect__() -> _sRecti_: Get the window's rectangle. 
- __iOSWindow::SetClientSize__(_const sVec2i&_ avSize) -> _void_: Set the window's client size. 
- __iOSWindow::GetClientSize__() -> _sVec2i_: Get the window's client size. 
- __iOSWindow::GetContentsScale__() -> _tF32_: Get the contents' scale factor. 
- __iOSWindow::GetMessageHandlers__() -> _tMessageHandlerSinkLst\*_: Get the window's message handlers. 
- __iOSWindow::UpdateWindow__(_tBool_ abBlockingMessages) -> _tBool_: Update the window's message pump and others. 
- __iOSWindow::CenterWindow__() -> _void_: Center the window in the middle of the current screen/parent window. 
- __iOSWindow::GetRequestedClose__() -> _tBool_: Get whether window closing has been requested. 
- __iOSWindow::SetRequestedClose__(_tBool_ abRequested) -> _void_: Set the close requested flags. 
- __iOSWindow::SetCursor__(_eOSCursor_ aCursor) -> _void_: Set the current OS cursor. 
- __iOSWindow::GetCursor__() -> _eOSCursor_: Get the current OS cursor. 
- __iOSWindow::InitCustomCursor__(_tIntPtr_ aID, _tU32_ anWidth, _tU32_ anHeight, _tU32_ anHotSpotX, _tU32_ anHotSpotY, _const tU32\*_ apData) -> _tBool_: Initialize the custom cursor. 
- __iOSWindow::GetCustomCursorID__() -> _tIntPtr_: Get the custom cursor user id. 
- __iOSWindow::SetCursorPosition__(_const sVec2i&_ avCursorPos) -> _void_: Set the cursor position. 
- __iOSWindow::GetCursorPosition__() -> _sVec2i_: Get the last recorded cursor position. 
- __iOSWindow::SetCursorCapture__(_tBool_ abCapture) -> _void_: Set the cursor capture. 
- __iOSWindow::GetCursorCapture__() -> _tBool_: Get the cursor capture state. 
- __iOSWindow::GetIsCursorOverClient__() -> _tBool_: Get whether the mouse cursor is in the client area of the window. 
- __iOSWindow::TryClose__() -> _void_: Try to close the window (this is equivalent to pressing the close button on the window). 
- __iOSWindow::SetDropTarget__(_tBool_ abDropTarget) -> _void_: Set whether the window is a drop target. 
- __iOSWindow::GetDropTarget__() -> _tBool_: Get whether the window is a drop target. 
- __iOSWindow::Clear__() -> _void_: Explicitly clear the window's content. 
- __iOSWindow::RedrawWindow__() -> _tBool_: Force redraw of the full window 
- __iOSWindow::GetMonitor__() -> _tU32_: Get the monitor index the window is on. 
- __iOSWindow::SetFullScreen__(_tU32_ anMonitor) -> _tBool_: Set the window to fullsreen, set to eInvalidHandle to return to windowed. 
- __iOSWindow::GetFullScreen__() -> _tU32_: Get the monitor on which the window is fullscreend, eInvalidHandle if it's not fullscreen. 
- __iOSWindow::GetIsMinimized__() -> _tBool_: Get whether the window is currently minimized. 
- __iOSWindow::GetIsMaximized__() -> _tBool_: Get whether the window is currently maximzed. 
- __iOSWindow::SetFocus__() -> _void_: Set focus on this window. 
- __iOSWindow::GetHasFocus__() -> _tBool_: Get whether the window has focus. 
- __iOSWindow::SetRefreshTimer__(_tF32_ afTime) -> _void_: Set the rate of the refresh timer in seconds. 
- __iOSWindow::GetRefreshTimer__() -> _tF32_: Get the rate of the refresh timer. 
- __iOSWindow::GetParentHandle__() -> _tIntPtr_: Get the parent window handle if any. 
- __iOSWindow::IsParentWindow__(_tIntPtr_ aHandle) -> _tU32_: Check whether the specified window is a parent window of this window. 
- __iOSWindow::AttachGraphicsAPI__(_iOSGraphicsAPI\*_ apAPI) -> _tBool_: Attach a graphics API to the window. 
- __iOSWindow::GetGraphicsAPI__() -> _iOSGraphicsAPI\*_: Get the graphics API attached to the window. 

## interface ni::iOSWindowGeneric
Generic window. 

### Parents:
- iUnknown

### Methods:
- __iOSWindowGeneric::GenericInputString__(_const achar\*_ aaszString) -> _void_: Send an input string to the window. 
- __iOSWindowGeneric::GenericSendMessage__(_tU32_ anMsg, _const Var&_ avarA, _const Var&_ avarB) -> _void_: Send a message to the window. 
- __iOSWindowGeneric::SetContentsScale__(_tF32_ afContentsScale) -> _void_: Set the window's content scale. 

## interface ni::iOSWindowWindowsSink
Windows window's sink. 

### Parents:
- iUnknown

### Methods:
- __iOSWindowWindowsSink::OnOSWindowWindowsSink_WndProc__(_tIntPtr_ hWnd, _tU32_ message, _tIntPtr_ wParam, _tIntPtr_ lParam) -> _tIntPtr_: Called when a message is received by the window, return TRUE to override the default implementation. 

## interface ni::iOSWindowWindows
Windows window. 

### Parents:
- iUnknown

### Methods:
- __iOSWindowWindows::GetWindowsWindowSinkList__() -> _tOSWindowWindowsSinkList\*_: Get the window's sink list. 
- __iOSWindowWindows::WindowsTranslateKey__(_ni::tU32_ wParam, _ni::tU32_ lParam, _ni::tBool_ abDown) -> _ni::tU32_: Translate a windows KEYDOWN/KEYUP message to a eKey code. 
- __iOSWindowWindows::WndProc__(_tIntPtr_ hWnd, _tU32_ message, _tIntPtr_ wParam, _tIntPtr_ lParam) -> _tIntPtr_: Default window proc 

## interface ni::iOSWindowOSX
OSX window. 

### Parents:
- iUnknown

### Methods:
- __iOSWindowOSX::GetNSWindow__() -> _void\*_: Get the window's NS window. 

## interface ni::iOSWindowQNX
QNX window. 

### Parents:
- iUnknown

### Methods:
- __iOSWindowQNX::GetScreenHandle__() -> _void\*_: Get the native screen handle 

## enum ni::eKey
Key codes 

### Values:
- __eKey_Unknown__ = __0x00__
- __eKey_Escape__ = __0x01__
- __eKey_n1__ = __0x02__
- __eKey_n2__ = __0x03__
- __eKey_n3__ = __0x04__
- __eKey_n4__ = __0x05__
- __eKey_n5__ = __0x06__
- __eKey_n6__ = __0x07__
- __eKey_n7__ = __0x08__
- __eKey_n8__ = __0x09__
- __eKey_n9__ = __0x0A__
- __eKey_n0__ = __0x0B__
- __eKey_Minus__ = __0x0C__
- __eKey_Equals__ = __0x0D__
- __eKey_BackSpace__ = __0x0E__
- __eKey_Tab__ = __0x0F__
- __eKey_Q__ = __0x10__
- __eKey_W__ = __0x11__
- __eKey_E__ = __0x12__
- __eKey_R__ = __0x13__
- __eKey_T__ = __0x14__
- __eKey_Y__ = __0x15__
- __eKey_U__ = __0x16__
- __eKey_I__ = __0x17__
- __eKey_O__ = __0x18__
- __eKey_P__ = __0x19__
- __eKey_LBracket__ = __0x1A__
- __eKey_RBracket__ = __0x1B__
- __eKey_Enter__ = __0x1C__
- __eKey_LControl__ = __0x1D__
- __eKey_A__ = __0x1E__
- __eKey_S__ = __0x1F__
- __eKey_D__ = __0x20__
- __eKey_F__ = __0x21__
- __eKey_G__ = __0x22__
- __eKey_H__ = __0x23__
- __eKey_J__ = __0x24__
- __eKey_K__ = __0x25__
- __eKey_L__ = __0x26__
- __eKey_Semicolon__ = __0x27__
- __eKey_Apostrophe__ = __0x28__
- __eKey_Grave__ = __0x29__
- __eKey_Tilde__ = __0x29__
- __eKey_LShift__ = __0x2A__
- __eKey_BackSlash__ = __0x2B__
- __eKey_Z__ = __0x2C__
- __eKey_X__ = __0x2D__
- __eKey_C__ = __0x2E__
- __eKey_V__ = __0x2F__
- __eKey_B__ = __0x30__
- __eKey_N__ = __0x31__
- __eKey_M__ = __0x32__
- __eKey_Comma__ = __0x33__
- __eKey_Period__ = __0x34__
- __eKey_Slash__ = __0x35__
- __eKey_RShift__ = __0x36__
- __eKey_NumPadStar__ = __0x37__
- __eKey_LAlt__ = __0x38__
- __eKey_Space__ = __0x39__
- __eKey_CapsLock__ = __0x3A__
- __eKey_F1__ = __0x3B__
- __eKey_F2__ = __0x3C__
- __eKey_F3__ = __0x3D__
- __eKey_F4__ = __0x3E__
- __eKey_F5__ = __0x3F__
- __eKey_F6__ = __0x40__
- __eKey_F7__ = __0x41__
- __eKey_F8__ = __0x42__
- __eKey_F9__ = __0x43__
- __eKey_F10__ = __0x44__
- __eKey_NumLock__ = __0x45__
- __eKey_Scroll__ = __0x46__
- __eKey_NumPad7__ = __0x47__
- __eKey_NumPad8__ = __0x48__
- __eKey_NumPad9__ = __0x49__
- __eKey_NumPadMinus__ = __0x4A__
- __eKey_NumPad4__ = __0x4B__
- __eKey_NumPad5__ = __0x4C__
- __eKey_NumPad6__ = __0x4D__
- __eKey_NumPadPlus__ = __0x4E__
- __eKey_NumPad1__ = __0x4F__
- __eKey_NumPad2__ = __0x50__
- __eKey_NumPad3__ = __0x51__
- __eKey_NumPad0__ = __0x52__
- __eKey_NumPadPeriod__ = __0x53__
- __eKey_OEM_102__ = __0x56__
- __eKey_F11__ = __0x57__
- __eKey_F12__ = __0x58__
- __eKey_F13__ = __0x64__
- __eKey_F14__ = __0x65__
- __eKey_F15__ = __0x66__
- __eKey_Kana__ = __0x70__
- __eKey_ABNT_C1__ = __0x73__
- __eKey_Convert__ = __0x79__
- __eKey_NoConvert__ = __0x7B__
- __eKey_Yen__ = __0x7D__
- __eKey_ABNT_C2__ = __0x7E__
- __eKey_NumPadEquals__ = __0x8D__
- __eKey_Circumflex__ = __0x90__
- __eKey_PrevTrack__ = __0x90__
- __eKey_AT__ = __0x91__
- __eKey_Colon__ = __0x92__
- __eKey_Underline__ = __0x93__
- __eKey_Kanji__ = __0x94__
- __eKey_Stop__ = __0x95__
- __eKey_AX__ = __0x96__
- __eKey_Unlabeled__ = __0x97__
- __eKey_NextTrack__ = __0x99__
- __eKey_NumPadEnter__ = __0x9C__
- __eKey_RControl__ = __0x9D__
- __eKey_Mute__ = __0xA0__
- __eKey_Calculator__ = __0xA1__
- __eKey_PlayPause__ = __0xA2__
- __eKey_MediaStop__ = __0xA4__
- __eKey_VolumeDown__ = __0xAE__
- __eKey_VolumeUp__ = __0xB0__
- __eKey_WebHome__ = __0xB2__
- __eKey_NumPadComma__ = __0xB3__
- __eKey_NumPadSlash__ = __0xB5__
- __eKey_SysRQ__ = __0xB7__
- __eKey_PrintScreen__ = __0xB7__
- __eKey_RAlt__ = __0xB8__
- __eKey_AltGr__ = __0xB8__
- __eKey_Pause__ = __0xC5__
- __eKey_Home__ = __0xC7__
- __eKey_Up__ = __0xC8__
- __eKey_PgUp__ = __0xC9__
- __eKey_Left__ = __0xCB__
- __eKey_Right__ = __0xCD__
- __eKey_End__ = __0xCF__
- __eKey_Down__ = __0xD0__
- __eKey_PgDn__ = __0xD1__
- __eKey_Insert__ = __0xD2__
- __eKey_Delete__ = __0xD3__
- __eKey_LWin__ = __0xDB__
- __eKey_RWin__ = __0xDC__
- __eKey_Apps__ = __0xDD__
- __eKey_Power__ = __0xDE__
- __eKey_Sleep__ = __0xDF__
- __eKey_Wake__ = __0xE3__
- __eKey_WebSearch__ = __0xE5__
- __eKey_WebFavorites__ = __0xE6__
- __eKey_WebRefresh__ = __0xE7__
- __eKey_WebStop__ = __0xE8__
- __eKey_WebForward__ = __0xE9__
- __eKey_WebBack__ = __0xEA__
- __eKey_MyComputer__ = __0xEB__
- __eKey_Mail__ = __0xEC__
- __eKey_MediaSelect__ = __0xED__
- __eKey_Last__ = __0xFF__

## enum ni::eProfilerReportMode
Profiler report modes 

### Values:
- __eProfilerReportMode_SelfTime__ = __0__
- __eProfilerReportMode_HierTime__ = __1__
- __eProfilerReportMode_CallGraph__ = __2__
- __eProfilerReportMode_Last__ = __3__

## interface ni::iProfDraw


### Parents:
- iUnknown

### Methods:
- __iProfDraw::BeginDraw__(_tBool_ abTranslucent) -> _void_
- __iProfDraw::EndDraw__() -> _void_
- __iProfDraw::DrawRect__(_tF32_ x0, _tF32_ y0, _tF32_ x1, _tF32_ y1, _tU32_ anColor) -> _void_
- __iProfDraw::DrawLine__(_tF32_ x0, _tF32_ y0, _tF32_ x1, _tF32_ y1, _tU32_ anColor) -> _void_
- __iProfDraw::GetTextHeight__() -> _tF32_
- __iProfDraw::GetTextWidth__(_const achar\*_ aText) -> _tF32_
- __iProfDraw::BeginText__() -> _void_
- __iProfDraw::EndText__() -> _void_
- __iProfDraw::Text__(_tF32_ x, _tF32_ y, _const achar\*_ aText, _tU32_ anColor) -> _void_

## interface ni::iProf
Profiler interface 

### Parents:
- iUnknown

### Methods:
- __iProf::SetRecord__(_tBool_ abRecord) -> _void_: Set whether to record profiling infos or not during the next update. 
- __iProf::GetRecord__() -> _tBool_: Get whether to record profiling infos or not during the next update. 
- __iProf::Update__() -> _void_: Update the profiler, once per frame. 
- __iProf::GetZoneStackDummy__() -> _sProfilerZoneStack\*_
- __iProf::GetZoneStack__() -> _sProfilerZoneStack\*\*_
- __iProf::SetZoneStack__(_sProfilerZoneStack\*_ apZoneStack) -> _void_
- __iProf::StackAppend__(_sProfilerZone\*_ apZoneStack) -> _sProfilerZoneStack\*_
- __iProf::GetTimeStamp__(_tI64\*_ apTimeStamp) -> _void_
- __iProf::SetReportMode__(_eProfilerReportMode_ aMode) -> _void_
- __iProf::GetReportMode__() -> _eProfilerReportMode_
- __iProf::InputMoveCursor__(_tI32_ anDelta) -> _void_
- __iProf::InputSelect__() -> _void_
- __iProf::InputSelectParent__() -> _void_
- __iProf::InputMoveFrame__(_tI32_ anDelta) -> _void_
- __iProf::InputSetFrame__(_tI32_ anFrame) -> _void_
- __iProf::InputSetCursor__(_tI32_ anLine) -> _void_
- __iProf::TextReport__(_tU32_ cols, _tU32_ rows) -> _cString_
- __iProf::DrawTable__(_ni::iProfDraw\*_ drawer, _tF32_ sx, _tF32_ sy, _tF32_ full_width, _tF32_ height, _tI32_ precision) -> _tBool_
- __iProf::DrawGraph__(_ni::iProfDraw\*_ drawer, _tF32_ sx, _tF32_ sy, _tF32_ x_spacing, _tF32_ y_spacing) -> _tBool_

## enum ni::eProfilerReportMode
Profiler report modes 

### Values:
- __eProfilerReportMode_SelfTime__ = __0__
- __eProfilerReportMode_HierTime__ = __1__
- __eProfilerReportMode_CallGraph__ = __2__
- __eProfilerReportMode_Last__ = __3__

## enum ni::ePCREOptionsFlags
PCRE option flags 

### Values:
- __ePCREOptionsFlags_Caseless__ = __0x00000001__: Do caseless (case insensitive) matching. 
- __ePCREOptionsFlags_Multiline__ = __0x00000002__: '^' and '$' match newlines within data. 
- __ePCREOptionsFlags_DotAll__ = __0x00000004__: '.' matches anything including NL. 
- __ePCREOptionsFlags_Extended__ = __0x00000008__: Ignore whitespace and # comments. 
- __ePCREOptionsFlags_Anchored__ = __0x00000010__: Force pattern anchoring. 
- __ePCREOptionsFlags_DollarEndOnly__ = __0x00000020__: '$' not to match newline at end. 
- __ePCREOptionsFlags_Extra__ = __0x00000040__: PCRE extra features (not much use currently). 
- __ePCREOptionsFlags_NotBOL__ = __0x00000080__: This option specifies that first character of the subject string is not the beginning of a line, so the circumflex metacharacter should not match before it. Setting this without MULTILINE (at compile time) causes circumflex never to match. This option affects only the behaviour of the circumflex metacharacter. It does not affect '\\A'. 
- __ePCREOptionsFlags_NotEOL__ = __0x00000100__: This option specifies that the end of the subject string is not the end of a line, so the dollar metacharacter should not match it nor (except in multiline mode) a newline immediately before it. Setting this without PCRE_MULTILINE (at compile time) causes dollar never to match. This option affects only the behaviour of the dollar metacharacter. It does not affect '\\Z' or '\\z'. 
- __ePCREOptionsFlags_Ungreedy__ = __0x00000200__: Invert greediness of quantifiers. 
- __ePCREOptionsFlags_NotEmpty__ = __0x00000400__: An empty string is not considered to be a valid match if this option is set. If there are alternatives in the pattern, they are tried. If all the alternatives match the empty string, the entire match fails. For example, if the pattern. "a?b?" is applied to a string not beginning with "a" or "b", it matches the empty string at the start of the subject. With NOTEMPTY set, this match is not valid, so PCRE searches further into the string for occurrences of "a" or "b". 
- __ePCREOptionsFlags_UTF8__ = __0x00000800__: Run in UTF-8 mode. 
- __ePCREOptionsFlags_NoAutoCapture__ = __0x00001000__: Disable numbered capturing parentheses (named ones available). 
- __ePCREOptionsFlags_NoUTF8Check__ = __0x00002000__: Do not check the pattern for UTF-8 validity. 
- __ePCREOptionsFlags_AutoCallout__ = __0x00004000__: Compile automatic callouts. 
- __ePCREOptionsFlags_DFAShortest__ = __0x00010000__: Setting this option causes the matching algorithm to stop as soon as it has found one match. Because of the way the alternative algorithm works, this is necessarily the shortest possible match at the first possible matching point in the subject string. 
- __ePCREOptionsFlags_FirstLine__ = __0x00040000__: Force matching to be before newline. 
- __ePCREOptionsFlags_DupNames__ = __0x00080000__: Allow duplicate names for subpatterns. 
- __ePCREOptionsFlags_NewLineCR__ = __0x00100000__: Set CR as the newline sequence. 
- __ePCREOptionsFlags_NewLineLF__ = __0x00200000__: Set LF as the newline sequence. 
- __ePCREOptionsFlags_NewLineCRLF__ = __0x00300000__: Set CRLF as the newline sequence. 
- __ePCREOptionsFlags_NewLineAny__ = __0x00400000__: Recognize any Unicode newline sequence. 
- __ePCREOptionsFlags_NewLineAnyCRLF__ = __0x00500000__: Recognize CR, LF, and CRLF as newline sequences. 
- __ePCREOptionsFlags_BsrAnyCRLF__ = __0x00800000__: '\\R' matches only CR, LF, or CRLF. 
- __ePCREOptionsFlags_BsrUnicode__ = __0x01000000__: '\\R' matches all Unicode line endings 
- __ePCREOptionsFlags_Global__ = __niBit(30)__: Global regular expression. 
- __ePCREOptionsFlags_Optimize__ = __niBit(31)__: Optimize the regular expression. 

## enum ni::ePCREError
PCRE compilation error 

### Values:
- __ePCREError_OK__ = __0__
- __ePCREError_NoMatch__ = __(-1)__
- __ePCREError_Null__ = __(-2)__
- __ePCREError_BadOption__ = __(-3)__
- __ePCREError_BadMagic__ = __(-4)__
- __ePCREError_UnknownOpcode__ = __(-5)__
- __ePCREError_NoMemory__ = __(-6)__
- __ePCREError_NoSubstring__ = __(-7)__
- __ePCREError_MatchLimit__ = __(-8)__
- __ePCREError_Callout__ = __(-9)__
- __ePCREError_BadUTF8__ = __(-10)__
- __ePCREError_BadUTF8Offset__ = __(-11)__
- __ePCREError_Partial__ = __(-12)__
- __ePCREError_BadPartial__ = __(-13)__
- __ePCREError_Internal__ = __(-14)__
- __ePCREError_BadCount__ = __(-15)__
- __ePCREError_DFA_UITEM__ = __(-16)__
- __ePCREError_DFA_UCOND__ = __(-17)__
- __ePCREError_DFA_UMLIMIT__ = __(-18)__
- __ePCREError_DFA_WSSIZE__ = __(-19)__
- __ePCREError_DFA_RECURSE__ = __(-20)__
- __ePCREError_RecursionLimit__ = __(-21)__
- __ePCREError_NullWSLimit__ = __(-22)__
- __ePCREError_BadNewLine__ = __(-23)__
- __ePCREError_LoopLimit__ = __(-24)__
- __ePCREError_BadRegexString__ = __(-1000)__

## interface ni::iRegex
Generic regular expression interface. 

### Parents:
- iUnknown

### Methods:
- __iRegex::GetImplType__() -> _const achar\*_: Get the implementation type of the regular experssion. 
- __iRegex::DoesMatch__(_const achar\*_ aaszText) -> _tBool_: Search for the next match of the expression. 

## interface ni::iPCRE
PCRE Regular Expression interface. 

### Parents:
- iRegex

### Methods:
- __iPCRE::Compile__(_const achar\*_ aaszRegEx, _const achar\*_ aaszOpt) -> _ePCREError_: Compile a regular expression. 
- __iPCRE::Compile2__(_const achar\*_ aaszRegEx, _tPCREOptionsFlags_ aOpt) -> _ePCREError_: Compile a regular expression. 
- __iPCRE::GetIsCompiled__() -> _tBool_: Get whether the last compile has been successfull. 
- __iPCRE::GetLastCompileError__() -> _ePCREError_: Get the last compilation error code. 
- __iPCRE::GetLastCompileErrorDesc__() -> _const achar\*_: Get the last compilation error description. 
- __iPCRE::GetLastCompileErrorOffset__() -> _tU32_: Get the last compilation error offset. 
- __iPCRE::GetOptions__() -> _tPCREOptionsFlags_: Get the options used during the last compilation. 
- __iPCRE::Reset__() -> _void_: Resets the regex object. 
- __iPCRE::GetNumMarkers__() -> _tU32_: Get the number of matches returned by the last Match/Sub call. 
- __iPCRE::GetMarker__(_tU32_ anIndex) -> _sVec2i_: Get the range of the last match. 
- __iPCRE::GetString__(_tU32_ anIndex) -> _cString_: Get the substring in string matched at the specified index. 
- __iPCRE::GetNumNamed__() -> _tU32_: Get the number of named subpatterns. 
- __iPCRE::GetNamedName__(_tU32_ anIndex) -> _const achar\*_: Get the name of the subpattern at the specified index. 
- __iPCRE::GetNamedMarker__(_const achar\*_ aaszName) -> _sVec2i_: Get the range of a named match. 
- __iPCRE::GetNamedString__(_const achar\*_ aaszName) -> _cString_: Get the substring in string matched at the specified index. 
- __iPCRE::GetNamedIndex__(_const achar\*_ aaszName) -> _tU32_: Get the index of a named subpattern. 
- __iPCRE::MatchRaw__(_const achar\*_ aaszString) -> _tI32_: Match against this regular expression. 
- __iPCRE::Match__(_iHString\*_ ahspString, _tU32_ anOffset) -> _tI32_: Match against this regular expression. 
- __iPCRE::Split__(_const achar\*_ aaszString, _tI32_ anMaxFields) -> _tI32_: Splits based on delimiters matching the regex. 
- __iPCRE::Sub__(_const achar\*_ aaszString, _const achar\*_ aaszReplacement, _tBool_ abDoDollarSub) -> _cString_: Substitues out whatever matches the regex for the second parameter. 

## enum ni::ePCREOptionsFlags
PCRE option flags 

### Values:
- __ePCREOptionsFlags_Caseless__ = __0x00000001__: Do caseless (case insensitive) matching. 
- __ePCREOptionsFlags_Multiline__ = __0x00000002__: '^' and '$' match newlines within data. 
- __ePCREOptionsFlags_DotAll__ = __0x00000004__: '.' matches anything including NL. 
- __ePCREOptionsFlags_Extended__ = __0x00000008__: Ignore whitespace and # comments. 
- __ePCREOptionsFlags_Anchored__ = __0x00000010__: Force pattern anchoring. 
- __ePCREOptionsFlags_DollarEndOnly__ = __0x00000020__: '$' not to match newline at end. 
- __ePCREOptionsFlags_Extra__ = __0x00000040__: PCRE extra features (not much use currently). 
- __ePCREOptionsFlags_NotBOL__ = __0x00000080__: This option specifies that first character of the subject string is not the beginning of a line, so the circumflex metacharacter should not match before it. Setting this without MULTILINE (at compile time) causes circumflex never to match. This option affects only the behaviour of the circumflex metacharacter. It does not affect '\\A'. 
- __ePCREOptionsFlags_NotEOL__ = __0x00000100__: This option specifies that the end of the subject string is not the end of a line, so the dollar metacharacter should not match it nor (except in multiline mode) a newline immediately before it. Setting this without PCRE_MULTILINE (at compile time) causes dollar never to match. This option affects only the behaviour of the dollar metacharacter. It does not affect '\\Z' or '\\z'. 
- __ePCREOptionsFlags_Ungreedy__ = __0x00000200__: Invert greediness of quantifiers. 
- __ePCREOptionsFlags_NotEmpty__ = __0x00000400__: An empty string is not considered to be a valid match if this option is set. If there are alternatives in the pattern, they are tried. If all the alternatives match the empty string, the entire match fails. For example, if the pattern. "a?b?" is applied to a string not beginning with "a" or "b", it matches the empty string at the start of the subject. With NOTEMPTY set, this match is not valid, so PCRE searches further into the string for occurrences of "a" or "b". 
- __ePCREOptionsFlags_UTF8__ = __0x00000800__: Run in UTF-8 mode. 
- __ePCREOptionsFlags_NoAutoCapture__ = __0x00001000__: Disable numbered capturing parentheses (named ones available). 
- __ePCREOptionsFlags_NoUTF8Check__ = __0x00002000__: Do not check the pattern for UTF-8 validity. 
- __ePCREOptionsFlags_AutoCallout__ = __0x00004000__: Compile automatic callouts. 
- __ePCREOptionsFlags_DFAShortest__ = __0x00010000__: Setting this option causes the matching algorithm to stop as soon as it has found one match. Because of the way the alternative algorithm works, this is necessarily the shortest possible match at the first possible matching point in the subject string. 
- __ePCREOptionsFlags_FirstLine__ = __0x00040000__: Force matching to be before newline. 
- __ePCREOptionsFlags_DupNames__ = __0x00080000__: Allow duplicate names for subpatterns. 
- __ePCREOptionsFlags_NewLineCR__ = __0x00100000__: Set CR as the newline sequence. 
- __ePCREOptionsFlags_NewLineLF__ = __0x00200000__: Set LF as the newline sequence. 
- __ePCREOptionsFlags_NewLineCRLF__ = __0x00300000__: Set CRLF as the newline sequence. 
- __ePCREOptionsFlags_NewLineAny__ = __0x00400000__: Recognize any Unicode newline sequence. 
- __ePCREOptionsFlags_NewLineAnyCRLF__ = __0x00500000__: Recognize CR, LF, and CRLF as newline sequences. 
- __ePCREOptionsFlags_BsrAnyCRLF__ = __0x00800000__: '\\R' matches only CR, LF, or CRLF. 
- __ePCREOptionsFlags_BsrUnicode__ = __0x01000000__: '\\R' matches all Unicode line endings 
- __ePCREOptionsFlags_Global__ = __niBit(30)__: Global regular expression. 
- __ePCREOptionsFlags_Optimize__ = __niBit(31)__: Optimize the regular expression. 

## interface ni::iScriptingHost
Scripting host interface. 

### Parents:
- iUnknown

### Remarks:
- The context is an indicator of a 'group/class' of object/implementation. 

### Methods:
- __iScriptingHost::EvalString__(_iHString\*_ ahspContext, _const ni::achar\*_ aaszCode) -> _tBool_: Evaluate the specified string. 
- __iScriptingHost::CanEvalImpl__(_iHString\*_ ahspContext, _iHString\*_ ahspCodeResource) -> _tBool_: Check whether the scripting host can evaluate the specified code resource. 
- __iScriptingHost::EvalImpl__(_iHString\*_ ahspContext, _iHString\*_ ahspCodeResource, _const tUUID&_ aIID) -> _iUnknown\*_: Evaluate the specified implementation from the specified 'code resource'. 
- __iScriptingHost::Service__(_tBool_ abForceGC) -> _void_: Service the scripting host. 

## interface ni::iScriptingHost
Scripting host interface. 

### Parents:
- iUnknown

### Remarks:
- The context is an indicator of a 'group/class' of object/implementation. 

### Methods:
- __iScriptingHost::EvalString__(_iHString\*_ ahspContext, _const ni::achar\*_ aaszCode) -> _tBool_: Evaluate the specified string. 
- __iScriptingHost::CanEvalImpl__(_iHString\*_ ahspContext, _iHString\*_ ahspCodeResource) -> _tBool_: Check whether the scripting host can evaluate the specified code resource. 
- __iScriptingHost::EvalImpl__(_iHString\*_ ahspContext, _iHString\*_ ahspCodeResource, _const tUUID&_ aIID) -> _iUnknown\*_: Evaluate the specified implementation from the specified 'code resource'. 
- __iScriptingHost::Service__(_tBool_ abForceGC) -> _void_: Service the scripting host. 

## enum ni::eSerializeFlags
Serialization flags. 

### Values:
- __eSerializeFlags_Write__ = __niBit(0)__: Serialize write. 
- __eSerializeFlags_Read__ = __niBit(1)__: Serialize read. 
- __eSerializeFlags_Category1__ = __niBit(2)__: Serialization category 1. 
- __eSerializeFlags_Category2__ = __niBit(3)__: Serialization category 2. 
- __eSerializeFlags_Category3__ = __niBit(4)__: Serialization category 3. 
- __eSerializeFlags_Category4__ = __niBit(5)__: Serialization category 4. 
- __eSerializeFlags_Category5__ = __niBit(6)__: Serialization category 5. 
- __eSerializeFlags_Category6__ = __niBit(7)__: Serialization category 6. 
- __eSerializeFlags_Category7__ = __niBit(8)__: Serialization category 7. 
- __eSerializeFlags_Category8__ = __niBit(9)__: Serialization category 8. 
- __eSerializeFlags_CategoryBase__ = __eSerializeFlags_Category1|eSerializeFlags_Category2|eSerializeFlags_Category3|eSerializeFlags_Category4__: Serialization category 1 to 4 (base). 
- __eSerializeFlags_CategoryExtended__ = __eSerializeFlags_Category5|eSerializeFlags_Category6|eSerializeFlags_Category7|eSerializeFlags_Category8__: Serialization category 4 to 8 (extended). 
- __eSerializeFlags_CategoryAll__ = __eSerializeFlags_CategoryBase|eSerializeFlags_CategoryExtended__: Serialization all category. 
- __eSerializeFlags_TypeInfoMetadata__ = __niBit(10)__: Serialize write will also write type information metadata. 
- __eSerializeFlags_Raw__ = __niBit(11)__: Raw serialization, dont put object serialization header. 

## enum ni::eSerializeMode
Serialization mode 

### Values:
- __eSerializeMode_Write__ = __eSerializeFlags_Write__: Write mode. 
- __eSerializeMode_WriteRaw__ = __eSerializeFlags_Write|eSerializeFlags_Raw__: Write raw mode. 
- __eSerializeMode_Read__ = __eSerializeFlags_Read__: Read mode. 
- __eSerializeMode_ReadRaw__ = __eSerializeFlags_Read|eSerializeFlags_Raw__: Read raw mode. 

## interface ni::iSerializable
iSerializable interface. 

### Parents:
- iUnknown

### Methods:
- __iSerializable::GetSerializeObjectTypeID__() -> _const achar\*_: Get the object type ID. 
- __iSerializable::Serialize__(_iFile\*_ apFile, _eSerializeMode_ aMode) -> _tSize_: Serialize the object. 

## enum ni::eSerializeFlags
Serialization flags. 

### Values:
- __eSerializeFlags_Write__ = __niBit(0)__: Serialize write. 
- __eSerializeFlags_Read__ = __niBit(1)__: Serialize read. 
- __eSerializeFlags_Category1__ = __niBit(2)__: Serialization category 1. 
- __eSerializeFlags_Category2__ = __niBit(3)__: Serialization category 2. 
- __eSerializeFlags_Category3__ = __niBit(4)__: Serialization category 3. 
- __eSerializeFlags_Category4__ = __niBit(5)__: Serialization category 4. 
- __eSerializeFlags_Category5__ = __niBit(6)__: Serialization category 5. 
- __eSerializeFlags_Category6__ = __niBit(7)__: Serialization category 6. 
- __eSerializeFlags_Category7__ = __niBit(8)__: Serialization category 7. 
- __eSerializeFlags_Category8__ = __niBit(9)__: Serialization category 8. 
- __eSerializeFlags_CategoryBase__ = __eSerializeFlags_Category1|eSerializeFlags_Category2|eSerializeFlags_Category3|eSerializeFlags_Category4__: Serialization category 1 to 4 (base). 
- __eSerializeFlags_CategoryExtended__ = __eSerializeFlags_Category5|eSerializeFlags_Category6|eSerializeFlags_Category7|eSerializeFlags_Category8__: Serialization category 4 to 8 (extended). 
- __eSerializeFlags_CategoryAll__ = __eSerializeFlags_CategoryBase|eSerializeFlags_CategoryExtended__: Serialization all category. 
- __eSerializeFlags_TypeInfoMetadata__ = __niBit(10)__: Serialize write will also write type information metadata. 
- __eSerializeFlags_Raw__ = __niBit(11)__: Raw serialization, dont put object serialization header. 

## interface ni::iSinkList
Sink list interface. 

### Parents:
- iCollection

### Methods:
- __iSinkList::GetSinkUUID__() -> _const tUUID&_: Get the UUID of the sink. 
- __iSinkList::Clear__() -> _void_: Remove all the sinks. 
- __iSinkList::HasSink__(_iUnknown\*_ apSink) -> _tBool_: Check whether the specified sink has already been added. 
- __iSinkList::AddSink__(_iUnknown\*_ apSink) -> _tBool_: Add a sink to the sink list. 
- __iSinkList::RemoveSink__(_iUnknown\*_ apSink) -> _tBool_: Remove a sink from the sink list. 
- __iSinkList::AddFrontSink__(_iUnknown\*_ apSink) -> _tBool_: Add a sink to the front of the sink list. 
- __iSinkList::SetMute__(_tBool_ abMute) -> _void_: Mute the sink. 
- __iSinkList::GetMute__() -> _tBool_: Get the muted status of the sink. 

## interface ni::iSinkList
Sink list interface. 

### Parents:
- iCollection

### Methods:
- __iSinkList::GetSinkUUID__() -> _const tUUID&_: Get the UUID of the sink. 
- __iSinkList::Clear__() -> _void_: Remove all the sinks. 
- __iSinkList::HasSink__(_iUnknown\*_ apSink) -> _tBool_: Check whether the specified sink has already been added. 
- __iSinkList::AddSink__(_iUnknown\*_ apSink) -> _tBool_: Add a sink to the sink list. 
- __iSinkList::RemoveSink__(_iUnknown\*_ apSink) -> _tBool_: Remove a sink from the sink list. 
- __iSinkList::AddFrontSink__(_iUnknown\*_ apSink) -> _tBool_: Add a sink to the front of the sink list. 
- __iSinkList::SetMute__(_tBool_ abMute) -> _void_: Mute the sink. 
- __iSinkList::GetMute__() -> _tBool_: Get the muted status of the sink. 

## enum ni::eStringTokenizerCharType
Char type returned by the methods of the tokenizer interface. 

### Values:
- __eStringTokenizerCharType_Normal__ = __0__: The char is normal and will be added to the current token. 
- __eStringTokenizerCharType_Skip__ = __1__: The char will be skipped. 
- __eStringTokenizerCharType_Splitter__ = __2__: The char mark a split. 
- __eStringTokenizerCharType_SplitterStart__ = __3__: The char mark a split that include this character at the begining of the next token. 
- __eStringTokenizerCharType_SplitterEnd__ = __4__: The char mark a split that include this character at the end of the current token. 
- __eStringTokenizerCharType_SplitterAndToken__ = __5__: The char mark a split and is a token. 

## interface ni::iStringTokenizer
iStringTokenizer interface 

### Parents:
- iUnknown

### Methods:
- __iStringTokenizer::GetCharType__(_tU32_ c) -> _eStringTokenizerCharType_
- __iStringTokenizer::OnNewLine__() -> _void_

## enum ni::eStringTokenizerCharType
Char type returned by the methods of the tokenizer interface. 

### Values:
- __eStringTokenizerCharType_Normal__ = __0__: The char is normal and will be added to the current token. 
- __eStringTokenizerCharType_Skip__ = __1__: The char will be skipped. 
- __eStringTokenizerCharType_Splitter__ = __2__: The char mark a split. 
- __eStringTokenizerCharType_SplitterStart__ = __3__: The char mark a split that include this character at the begining of the next token. 
- __eStringTokenizerCharType_SplitterEnd__ = __4__: The char mark a split that include this character at the end of the current token. 
- __eStringTokenizerCharType_SplitterAndToken__ = __5__: The char mark a split and is a token. 

## enum ni::eTimeZone
Time zone enumeration 

### Values:
- __eTimeZone_UTC__ = __0__: Coordinated Universal Time Europe UTC 
- __eTimeZone_WET__ = __0__: Western European Time Europe UTC 
- __eTimeZone_GMT__ = __0__: Greenwich Mean Time Europe UTC 
- __eTimeZone_A__ = __+1*3600__: Alpha Time Zone Military UTC + 1 hour 
- __eTimeZone_ADT__ = __-3*3600__: Atlantic Daylight Time North America UTC - 3 hours 
- __eTimeZone_AKDT__ = __-8*3600__: Alaska Daylight Time North America UTC - 8 hours 
- __eTimeZone_AKST__ = __-9*3600__: Alaska Standard Time North America UTC - 9 hours 
- __eTimeZone_AST__ = __-4*3600__: Atlantic Standard Time North America UTC - 4 hours 
- __eTimeZone_B__ = __+2*3600__: Bravo Time Zone Military UTC + 2 hours 
- __eTimeZone_BST__ = __+1*3600__: British Summer Time Europe UTC + 1 hour 
- __eTimeZone_C__ = __+3*3600__: Charlie Time Zone Military UTC + 3 hours 
- __eTimeZone_CDT__ = __-5*3600__: Central Daylight Time North America UTC - 5 hours 
- __eTimeZone_CEDT__ = __+2*3600__: Central European Daylight Time Europe UTC + 2 hours 
- __eTimeZone_CEST__ = __+2*3600__: Central European Summer Time Europe UTC + 2 hours 
- __eTimeZone_CET__ = __+1*3600__: Central European Time Europe UTC + 1 hour 
- __eTimeZone_CST__ = __-6*3600__: Central Standard Time North America UTC - 6 hours 
- __eTimeZone_D__ = __+4*3600__: Delta Time Zone Military UTC + 4 hours 
- __eTimeZone_E__ = __+5*3600__: Echo Time Zone Military UTC + 5 hours 
- __eTimeZone_EDT__ = __-4*3600__: Eastern Daylight Time North America UTC - 4 hours 
- __eTimeZone_EEDT__ = __+3*3600__: Eastern European Daylight Time Europe UTC + 3 hours 
- __eTimeZone_EEST__ = __+3*3600__: Eastern European Summer Time Europe UTC + 3 hours 
- __eTimeZone_EET__ = __+2*3600__: Eastern European Time Europe UTC + 2 hours 
- __eTimeZone_EST__ = __-5*3600__: Eastern Standard Time North America UTC - 5 hours 
- __eTimeZone_F__ = __+6*3600__: Foxtrot Time Zone Military UTC + 6 hours 
- __eTimeZone_G__ = __+7*3600__: Golf Time Zone Military UTC + 7 hours 
- __eTimeZone_H__ = __+8*3600__: Hotel Time Zone Military UTC + 8 hours 
- __eTimeZone_HAA__ = __-3*3600__: Heure Avancee de l'Atlantique North America UTC - 3 hours 
- __eTimeZone_HAC__ = __-5*3600__: Heure Avancee du Centre North America UTC - 5 hours 
- __eTimeZone_HADT__ = __-9*3600__: Hawaii-Aleutian Daylight Time North America UTC - 9 hours 
- __eTimeZone_HAE__ = __-4*3600__: Heure Avancee de l'Est North America UTC - 4 hours 
- __eTimeZone_HAP__ = __-7*3600__: Heure Avancee du Pacifique North America UTC - 7 hours 
- __eTimeZone_HAR__ = __-6*3600__: Heure Avancee des Rocheuses North America UTC - 6 hours 
- __eTimeZone_HAST__ = __-10*3600-1800__: Hawaii-Aleutian Standard Time North America UTC - 10 hours 
- __eTimeZone_HAT__ = __-2*3600-1800__: Heure Avancee de Terre-Neuve North America UTC - 2:30 hours 
- __eTimeZone_HAY__ = __-8*3600__: Heure Avancee du Yukon North America UTC - 8 hours 
- __eTimeZone_HNA__ = __-4*3600__: Heure Normale de l'Atlantique North America UTC - 4 hours 
- __eTimeZone_HNC__ = __-6*3600__: Heure Normale du Centre North America UTC - 6 hours 
- __eTimeZone_HNE__ = __-5*3600__: Heure Normale de l'Est North America UTC - 5 hours 
- __eTimeZone_HNP__ = __-8*3600__: Heure Normale du Pacifique North America UTC - 8 hours 
- __eTimeZone_HNR__ = __-7*3600__: Heure Normale des Rocheuses North America UTC - 7 hours 
- __eTimeZone_HNT__ = __-3*3600-1800__: Heure Normale de Terre-Neuve North America UTC - 3:30 hours 
- __eTimeZone_HNY__ = __-9*3600__: Heure Normale du Yukon North America UTC - 9 hours 
- __eTimeZone_I__ = __+9*3600__: India Time Zone Military UTC + 9 hours 
- __eTimeZone_IST__ = __+1*3600__: Irish Summer Time Europe UTC + 1 hour 
- __eTimeZone_K__ = __+10*3600__: Kilo Time Zone Military UTC + 10 hours 
- __eTimeZone_L__ = __+11*3600__: Lima Time Zone Military UTC + 11 hours 
- __eTimeZone_M__ = __+12*3600__: Mike Time Zone Military UTC + 12 hours 
- __eTimeZone_MDT__ = __-6*3600__: Mountain Daylight Time North America UTC - 6 hours 
- __eTimeZone_MESZ__ = __+2*3600__: Mitteleuroaische Sommerzeit Europe UTC + 2 hours 
- __eTimeZone_MEZ__ = __+1*3600__: Mitteleuropaische Zeit Europe UTC + 1 hour 
- __eTimeZone_MST__ = __-7*3600__: Mountain Standard Time North America UTC - 7 hours 
- __eTimeZone_N__ = __-1*3600__: November Time Zone Military UTC - 1 hour 
- __eTimeZone_NDT__ = __-2*3600-1800__: Newfoundland Daylight Time North America UTC - 2:30 hours 
- __eTimeZone_NST__ = __-3*3600-1800__: Newfoundland Standard Time North America UTC - 3:30 hours 
- __eTimeZone_O__ = __-2*3600__: Oscar Time Zone Military UTC - 2 hours 
- __eTimeZone_P__ = __-3*3600__: Papa Time Zone Military UTC - 3 hours 
- __eTimeZone_PDT__ = __-7*3600__: Pacific Daylight Time North America UTC - 7 hours 
- __eTimeZone_PST__ = __-8*3600__: Pacific Standard Time North America UTC - 8 hours 
- __eTimeZone_Q__ = __-4*3600__: Quebec Time Zone Military UTC - 4 hours 
- __eTimeZone_R__ = __-5*3600__: Romeo Time Zone Military UTC - 5 hours 
- __eTimeZone_S__ = __-6*3600__: Sierra Time Zone Military UTC - 6 hours 
- __eTimeZone_T__ = __-7*3600__: Tango Time Zone Military UTC - 7 hours 
- __eTimeZone_U__ = __-8*3600__: Uniform Time Zone Military UTC - 8 hours 
- __eTimeZone_V__ = __-9*3600__: Victor Time Zone Military UTC - 9 hours 
- __eTimeZone_W__ = __-10*3600__: Whiskey Time Zone Military UTC - 10 hours 
- __eTimeZone_WEDT__ = __+1*3600__: Western European Daylight Time Europe UTC + 1 hour 
- __eTimeZone_WEST__ = __+1*3600__: Western European Summer Time Europe UTC + 1 hour 
- __eTimeZone_X__ = __-11*3600__: X-ray Time Zone Military UTC - 11 hours 
- __eTimeZone_Y__ = __-12*3600__: Yankee Time Zone Military UTC - 12 hours 
- __eTimeZone_Z__ = __0__: Zulu Time Zone Military UTC 

## variable ni::knTimeYearRange

## variable ni::knTimeSecsPerMinute

## variable ni::knTimeMinPerHour

## variable ni::knTimeSecsPerHour

## variable ni::knTimeHoursPerDay

## variable ni::knTimeMinPerDay

## variable ni::knTimeSecsPerDay

## interface ni::iTime
Time interface. 

### Parents:
- iUnknown

### Methods:
- __iTime::UpdateFromCurrentSystemTime__() -> _void_: Update the time class from the current system's time. 
- __iTime::SetYear__(_tI32_ anYear) -> _void_: Set the year. 
- __iTime::GetYear__() -> _tI32_: Get the year. 
- __iTime::SetMonth__(_tU8_ anMonth) -> _void_: Set the month. 
- __iTime::GetMonth__() -> _tU8_: Get the month. 
- __iTime::SetDay__(_tU8_ anDay) -> _void_: Set the day. 
- __iTime::GetDay__() -> _tU8_: Get the day. 
- __iTime::GetWeekday__() -> _tU8_: Get the weekday. 
- __iTime::SetHour__(_tU8_ anHour) -> _void_: Set the hour. 
- __iTime::GetHour__() -> _tU8_: Get the hour. 
- __iTime::SetMinute__(_tU8_ anMinute) -> _void_: Set the minute. 
- __iTime::GetMinute__() -> _tU8_: Get the minute. 
- __iTime::SetSecond__(_tU8_ anSecond) -> _void_: Set the second. 
- __iTime::GetSecond__() -> _tU8_: Get the second. 
- __iTime::Copy__(_const iTime\*_ apTime) -> _tBool_: Copy the specified time. 
- __iTime::Clone__() -> _iTime\*_: Creates a clone of this time. 
- __iTime::SetDayLightSaving__(_ni::tBool_ abDayLightSaving) -> _void_: Set whether the time contains day light saving. 
- __iTime::GetDayLightSaving__() -> _tBool_: Get whether the time contains day light saving. 
- __iTime::SetTimeZone__(_tI32_ anTimeZone) -> _void_: Set the time zone. 
- __iTime::GetTimeZone__() -> _tI32_: Get the time zone. 
- __iTime::SetUnixTimeSecs__(_tI64_ anFmt) -> _void_: Set the time from the unix time. 
- __iTime::GetUnixTimeSecs__() -> _tI64_: Get the unix time. 
- __iTime::Compare__(_const iTime\*_ apTime) -> _tI32_: Compare to another time object. 
- __iTime::ParseString__(_const achar\*_ szString, _const achar\*_ aszFormat) -> _iTime\*_: Parse a time string. 
- __iTime::Format__(_const achar\*_ aszFormat) -> _cString_: Format time. 
- __iTime::AddSeconds__(_tI64_ anSeconds) -> _iTime\*_: Add seconds to this time. 

## enum ni::eTimeZone
Time zone enumeration 

### Values:
- __eTimeZone_UTC__ = __0__: Coordinated Universal Time Europe UTC 
- __eTimeZone_WET__ = __0__: Western European Time Europe UTC 
- __eTimeZone_GMT__ = __0__: Greenwich Mean Time Europe UTC 
- __eTimeZone_A__ = __+1*3600__: Alpha Time Zone Military UTC + 1 hour 
- __eTimeZone_ADT__ = __-3*3600__: Atlantic Daylight Time North America UTC - 3 hours 
- __eTimeZone_AKDT__ = __-8*3600__: Alaska Daylight Time North America UTC - 8 hours 
- __eTimeZone_AKST__ = __-9*3600__: Alaska Standard Time North America UTC - 9 hours 
- __eTimeZone_AST__ = __-4*3600__: Atlantic Standard Time North America UTC - 4 hours 
- __eTimeZone_B__ = __+2*3600__: Bravo Time Zone Military UTC + 2 hours 
- __eTimeZone_BST__ = __+1*3600__: British Summer Time Europe UTC + 1 hour 
- __eTimeZone_C__ = __+3*3600__: Charlie Time Zone Military UTC + 3 hours 
- __eTimeZone_CDT__ = __-5*3600__: Central Daylight Time North America UTC - 5 hours 
- __eTimeZone_CEDT__ = __+2*3600__: Central European Daylight Time Europe UTC + 2 hours 
- __eTimeZone_CEST__ = __+2*3600__: Central European Summer Time Europe UTC + 2 hours 
- __eTimeZone_CET__ = __+1*3600__: Central European Time Europe UTC + 1 hour 
- __eTimeZone_CST__ = __-6*3600__: Central Standard Time North America UTC - 6 hours 
- __eTimeZone_D__ = __+4*3600__: Delta Time Zone Military UTC + 4 hours 
- __eTimeZone_E__ = __+5*3600__: Echo Time Zone Military UTC + 5 hours 
- __eTimeZone_EDT__ = __-4*3600__: Eastern Daylight Time North America UTC - 4 hours 
- __eTimeZone_EEDT__ = __+3*3600__: Eastern European Daylight Time Europe UTC + 3 hours 
- __eTimeZone_EEST__ = __+3*3600__: Eastern European Summer Time Europe UTC + 3 hours 
- __eTimeZone_EET__ = __+2*3600__: Eastern European Time Europe UTC + 2 hours 
- __eTimeZone_EST__ = __-5*3600__: Eastern Standard Time North America UTC - 5 hours 
- __eTimeZone_F__ = __+6*3600__: Foxtrot Time Zone Military UTC + 6 hours 
- __eTimeZone_G__ = __+7*3600__: Golf Time Zone Military UTC + 7 hours 
- __eTimeZone_H__ = __+8*3600__: Hotel Time Zone Military UTC + 8 hours 
- __eTimeZone_HAA__ = __-3*3600__: Heure Avancee de l'Atlantique North America UTC - 3 hours 
- __eTimeZone_HAC__ = __-5*3600__: Heure Avancee du Centre North America UTC - 5 hours 
- __eTimeZone_HADT__ = __-9*3600__: Hawaii-Aleutian Daylight Time North America UTC - 9 hours 
- __eTimeZone_HAE__ = __-4*3600__: Heure Avancee de l'Est North America UTC - 4 hours 
- __eTimeZone_HAP__ = __-7*3600__: Heure Avancee du Pacifique North America UTC - 7 hours 
- __eTimeZone_HAR__ = __-6*3600__: Heure Avancee des Rocheuses North America UTC - 6 hours 
- __eTimeZone_HAST__ = __-10*3600-1800__: Hawaii-Aleutian Standard Time North America UTC - 10 hours 
- __eTimeZone_HAT__ = __-2*3600-1800__: Heure Avancee de Terre-Neuve North America UTC - 2:30 hours 
- __eTimeZone_HAY__ = __-8*3600__: Heure Avancee du Yukon North America UTC - 8 hours 
- __eTimeZone_HNA__ = __-4*3600__: Heure Normale de l'Atlantique North America UTC - 4 hours 
- __eTimeZone_HNC__ = __-6*3600__: Heure Normale du Centre North America UTC - 6 hours 
- __eTimeZone_HNE__ = __-5*3600__: Heure Normale de l'Est North America UTC - 5 hours 
- __eTimeZone_HNP__ = __-8*3600__: Heure Normale du Pacifique North America UTC - 8 hours 
- __eTimeZone_HNR__ = __-7*3600__: Heure Normale des Rocheuses North America UTC - 7 hours 
- __eTimeZone_HNT__ = __-3*3600-1800__: Heure Normale de Terre-Neuve North America UTC - 3:30 hours 
- __eTimeZone_HNY__ = __-9*3600__: Heure Normale du Yukon North America UTC - 9 hours 
- __eTimeZone_I__ = __+9*3600__: India Time Zone Military UTC + 9 hours 
- __eTimeZone_IST__ = __+1*3600__: Irish Summer Time Europe UTC + 1 hour 
- __eTimeZone_K__ = __+10*3600__: Kilo Time Zone Military UTC + 10 hours 
- __eTimeZone_L__ = __+11*3600__: Lima Time Zone Military UTC + 11 hours 
- __eTimeZone_M__ = __+12*3600__: Mike Time Zone Military UTC + 12 hours 
- __eTimeZone_MDT__ = __-6*3600__: Mountain Daylight Time North America UTC - 6 hours 
- __eTimeZone_MESZ__ = __+2*3600__: Mitteleuroaische Sommerzeit Europe UTC + 2 hours 
- __eTimeZone_MEZ__ = __+1*3600__: Mitteleuropaische Zeit Europe UTC + 1 hour 
- __eTimeZone_MST__ = __-7*3600__: Mountain Standard Time North America UTC - 7 hours 
- __eTimeZone_N__ = __-1*3600__: November Time Zone Military UTC - 1 hour 
- __eTimeZone_NDT__ = __-2*3600-1800__: Newfoundland Daylight Time North America UTC - 2:30 hours 
- __eTimeZone_NST__ = __-3*3600-1800__: Newfoundland Standard Time North America UTC - 3:30 hours 
- __eTimeZone_O__ = __-2*3600__: Oscar Time Zone Military UTC - 2 hours 
- __eTimeZone_P__ = __-3*3600__: Papa Time Zone Military UTC - 3 hours 
- __eTimeZone_PDT__ = __-7*3600__: Pacific Daylight Time North America UTC - 7 hours 
- __eTimeZone_PST__ = __-8*3600__: Pacific Standard Time North America UTC - 8 hours 
- __eTimeZone_Q__ = __-4*3600__: Quebec Time Zone Military UTC - 4 hours 
- __eTimeZone_R__ = __-5*3600__: Romeo Time Zone Military UTC - 5 hours 
- __eTimeZone_S__ = __-6*3600__: Sierra Time Zone Military UTC - 6 hours 
- __eTimeZone_T__ = __-7*3600__: Tango Time Zone Military UTC - 7 hours 
- __eTimeZone_U__ = __-8*3600__: Uniform Time Zone Military UTC - 8 hours 
- __eTimeZone_V__ = __-9*3600__: Victor Time Zone Military UTC - 9 hours 
- __eTimeZone_W__ = __-10*3600__: Whiskey Time Zone Military UTC - 10 hours 
- __eTimeZone_WEDT__ = __+1*3600__: Western European Daylight Time Europe UTC + 1 hour 
- __eTimeZone_WEST__ = __+1*3600__: Western European Summer Time Europe UTC + 1 hour 
- __eTimeZone_X__ = __-11*3600__: X-ray Time Zone Military UTC - 11 hours 
- __eTimeZone_Y__ = __-12*3600__: Yankee Time Zone Military UTC - 12 hours 
- __eTimeZone_Z__ = __0__: Zulu Time Zone Military UTC 

## enum ni::eRawToStringEncoding


### Values:
- __eRawToStringEncoding_Hex__ = __0__
- __eRawToStringEncoding_Base64__ = __1__
- __eRawToStringEncoding_Base32__ = __2__

## interface ni::iToString
iToString interface. 

### Parents:
- iUnknown

### Methods:
- __iToString::ToString__() -> _ni::cString_: Convert the object to a string. 

## enum ni::eRawToStringEncoding


### Values:
- __eRawToStringEncoding_Hex__ = __0__
- __eRawToStringEncoding_Base64__ = __1__
- __eRawToStringEncoding_Base32__ = __2__

## enum ni::eXmlParserNodeType
Xml parser node types. 

### Values:
- __eXmlParserNodeType_ElementBegin__ = __0__: A xml element, like \<foo> 
- __eXmlParserNodeType_ElementEnd__ = __1__: End of an xml element, like \</foo> 
- __eXmlParserNodeType_Text__ = __2__: Text within a xml element: \<foo> this is the text. \</foo> 
- __eXmlParserNodeType_EmptyText__ = __3__: Empty Text within a xml element: \<foo> \</foo> 
- __eXmlParserNodeType_Comment__ = __4__: An xml comment like &lt;!-- I am a comment --&gt; or a DTD definition. 
- __eXmlParserNodeType_CDATA__ = __5__: An xml cdata section like &lt;![CDATA[ this is some CDATA ]]&gt; 

## interface ni::iXmlParserSink
Xml parser sink interface. 

### Parents:
- iUnknown

### Methods:
- __iXmlParserSink::OnXmlParserSink_Node__(_eXmlParserNodeType_ aType, _const ni::achar\*_ aNameOrData) -> _tBool_: Xml parser sink interface. 
- __iXmlParserSink::OnXmlParserSink_Attribute__(_const ni::achar\*_ aName, _const ni::achar\*_ aValue) -> _tBool_

## enum ni::eXmlParserNodeType
Xml parser node types. 

### Values:
- __eXmlParserNodeType_ElementBegin__ = __0__: A xml element, like \<foo> 
- __eXmlParserNodeType_ElementEnd__ = __1__: End of an xml element, like \</foo> 
- __eXmlParserNodeType_Text__ = __2__: Text within a xml element: \<foo> this is the text. \</foo> 
- __eXmlParserNodeType_EmptyText__ = __3__: Empty Text within a xml element: \<foo> \</foo> 
- __eXmlParserNodeType_Comment__ = __4__: An xml comment like &lt;!-- I am a comment --&gt; or a DTD definition. 
- __eXmlParserNodeType_CDATA__ = __5__: An xml cdata section like &lt;![CDATA[ this is some CDATA ]]&gt; 

## interface ni::iZipArchWrite
Zip archive writer 

### Parents:
- iUnknown

### Methods:
- __iZipArchWrite::AddFileBlock__(_const achar\*_ aaszName, _iFile\*_ apFile, _tI64_ aSize) -> _tBool_: Adds a file block to the archive. 
- __iZipArchWrite::AddRawBlock__(_const achar\*_ aaszName, _tPtr_ apData, _tSize_ aSize) -> _tBool_: Adds a block of raw data as a file. 

## interface ni::iZip
Zip interface. 

### Parents:
- iUnknown

### Methods:
- __iZip::ZipUncompressBuffer__(_tPtr_ apDest, _tU32_ anDestSize, _tPtr_ apSrc, _tU32_ anSrcSize) -> _tBool_
- __iZip::ZipUncompressBufferInFile__(_iFile\*_ apDest, _tU32_ anDestSize, _tPtr_ apSrc, _tU32_ anSrcSize) -> _tBool_
- __iZip::ZipUncompressFile__(_iFile\*_ apDest, _tU32_ anDestSize, _iFile\*_ apSrc, _tU32_ anSrcSize) -> _tBool_
- __iZip::ZipUncompressFileInBuffer__(_tPtr_ apDest, _tU32_ anDestSize, _iFile\*_ apSrc, _tU32_ anSrcSize) -> _tBool_
- __iZip::ZipInflateFileInBuffer__(_tPtr_ apDest, _tU32_ anDestSize, _iFile\*_ apSrc) -> _tBool_
- __iZip::ZipCompressBuffer__(_tPtr_ apDest, _tPtr_ apSrc, _tU32_ anSrcSize, _tU32_ anLevel) -> _tU32_: The destination buffer must be at least 20% bigger than the source. 
- __iZip::ZipCompressBufferInFile__(_iFile\*_ apDest, _tPtr_ apSrc, _tU32_ anSrcSize, _tU32_ anLevel) -> _tU32_
- __iZip::ZipCompressFile__(_iFile\*_ apDest, _iFile\*_ apSrc, _tU32_ anSrcSize, _tU32_ anLevel) -> _tU32_
- __iZip::UnzOpen__(_ni::iFile\*_ apFile) -> _tHandle_
- __iZip::UnzClose__(_tHandle_ file) -> _tI32_
- __iZip::UnzGetGlobalInfo__(_tHandle_ file, _unz_global_info\*_ pglobal_info) -> _tI32_
- __iZip::UnzGetGlobalComment__(_tHandle_ file, _cString&_ strComment) -> _tI32_
- __iZip::UnzGoToFirstFile__(_tHandle_ file) -> _tI32_
- __iZip::UnzGoToNextFile__(_tHandle_ file) -> _tI32_
- __iZip::UnzLocateFile__(_tHandle_ file, _const achar\*_ szFileName, _tBool_ bCaseSensitivity) -> _tI32_
- __iZip::UnzLocateFileInc__(_tHandle_ file, _tU32_ num, _tU32_ pos) -> _tI32_
- __iZip::UnzGetCurrentFileInfo__(_tHandle_ file, _unz_file_info\*_ pfile_info, _cString&_ strFileName, _cString&_ strExtraField, _cString&_ strComment) -> _tI32_
- __iZip::UnzOpenCurrentFile__(_tHandle_ file, _const achar\*_ pwd) -> _tI32_
- __iZip::UnzCloseCurrentFile__(_tHandle_ file) -> _tI32_
- __iZip::UnzReadCurrentFile__(_tHandle_ file, _tPtr_ buf, _tU32_ len) -> _tI32_
- __iZip::Unztell__(_tHandle_ file) -> _tI32_
- __iZip::Unzeof__(_tHandle_ file) -> _tI32_
- __iZip::UnzGetLocalExtrafield__(_tHandle_ file, _tPtr_ buf, _tU32_ len) -> _tI32_
- __iZip::ZlibVersion__() -> _const achar\*_
- __iZip::Deflate__(_z_streamp_ strm, _tI32_ flush) -> _tI32_
- __iZip::DeflateEnd__(_z_streamp_ strm) -> _tI32_
- __iZip::Inflate__(_z_streamp_ strm, _tI32_ flush) -> _tI32_
- __iZip::InflateEnd__(_z_streamp_ strm) -> _tI32_
- __iZip::DeflateSetDictionary__(_z_streamp_ strm, _const tU8\*_ dictionary, _tI32_ dictLength) -> _tI32_
- __iZip::DeflateCopy__(_z_streamp_ dest, _z_streamp_ source) -> _tI32_
- __iZip::DeflateReset__(_z_streamp_ strm) -> _tI32_
- __iZip::DeflateParams__(_z_streamp_ strm, _tI32_ level, _tI32_ strategy) -> _tI32_
- __iZip::DeflateTune__(_z_streamp_ strm, _tI32_ good_length, _tI32_ max_lazy, _tI32_ nice_length, _tI32_ max_chain) -> _tI32_
- __iZip::DeflateBound__(_z_streamp_ strm, _tU32_ sourceLen) -> _tU32_
- __iZip::DeflatePrime__(_z_streamp_ strm, _tI32_ bits, _tI32_ value) -> _tI32_
- __iZip::DeflateSetHeader__(_z_streamp_ strm, _gz_headerp_ head) -> _tI32_
- __iZip::InflateSetDictionary__(_z_streamp_ strm, _const tU8\*_ dictionary, _tI32_ dictLength) -> _tI32_
- __iZip::InflateSync__(_z_streamp_ strm) -> _tI32_
- __iZip::InflateCopy__(_z_streamp_ dest, _z_streamp_ source) -> _tI32_
- __iZip::InflateReset__(_z_streamp_ strm) -> _tI32_
- __iZip::InflatePrime__(_z_streamp_ strm, _tI32_ bits, _tI32_ value) -> _tI32_
- __iZip::InflateGetHeader__(_z_streamp_ strm, _gz_headerp_ head) -> _tI32_
- __iZip::InflateBack__(_z_streamp_ strm, _zlib_in_func_ aIn, _void\*_ in_desc, _zlib_out_func_ aOut, _void\*_ out_desc) -> _tI32_
- __iZip::InflateBackEnd__(_z_streamp_ strm) -> _tI32_
- __iZip::ZlibCompileFlags__() -> _tU32_
- __iZip::Compress__(_tU8\*_ dest, _tU32\*_ destLen, _const tU8\*_ source, _tU32_ sourceLen) -> _tI32_
- __iZip::Compress2__(_tU8\*_ dest, _tU32\*_ destLen, _const tU8\*_ source, _tU32_ sourceLen, _tI32_ level) -> _tI32_
- __iZip::CompressBound__(_tU32_ sourceLen) -> _tU32_
- __iZip::Uncompress__(_tU8\*_ dest, _tU32\*_ destLen, _const tU8\*_ source, _tU32_ sourceLen) -> _tI32_
- __iZip::Adler32__(_tU32_ adler, _const tU8\*_ buf, _tI32_ len) -> _tU32_
- __iZip::Adler32Combine__(_tU32_ adler1, _tU32_ adler2, _tSize_ len2) -> _tU32_
- __iZip::Crc32__(_tU32_ crc, _const tU8\*_ buf, _tI32_ len) -> _tU32_
- __iZip::Crc32Combine__(_tU32_ crc1, _tU32_ crc2, _tSize_ len2) -> _tU32_
- __iZip::DeflateInit__(_z_streamp_ strm, _tI32_ level) -> _tI32_
- __iZip::InflateInit__(_z_streamp_ strm) -> _tI32_
- __iZip::DeflateInit2__(_z_streamp_ strm, _tI32_ level, _tI32_ method, _tI32_ windowBits, _tI32_ memLevel, _tI32_ strategy) -> _tI32_
- __iZip::InflateInit2__(_z_streamp_ strm, _tI32_ windowBits) -> _tI32_
- __iZip::InflateBackInit__(_z_streamp_ strm, _tI32_ windowBits, _tU8\*_ window) -> _tI32_
- __iZip::ZError__(_tI32_ err) -> _const achar\*_
- __iZip::InflateSyncPoint__(_z_streamp_ z) -> _tI32_
- __iZip::GetCRCTable__() -> _const tU32\*_
- __iZip::CreateZipBufferEncoder__(_tU32_ anCLevel) -> _iBufferEncoder\*_: Create a Zip buffer encoder. 
- __iZip::CreateZipBufferDecoder__() -> _iBufferDecoder\*_: Create a Zip buffer decoder. 
- __iZip::CreateFileZipBufferEncoder__(_iFileBase\*_ apBaseFile, _tU32_ anCLevel) -> _iFile\*_: Create a Zip buffer encoder file. 
- __iZip::CreateFileZipBufferDecoder__(_iFileBase\*_ apBaseFile, _tSize_ aDecodedSize) -> _iFile\*_: Create a Zip buffer decoder file. \see iLang::CreateFileBufferDecoder 
- __iZip::CreateRawBufferEncoder__() -> _iBufferEncoder\*_: Create a Raw buffer encoder. 
- __iZip::CreateRawBufferDecoder__() -> _iBufferDecoder\*_: Create a Raw buffer decoder. 
- __iZip::CreateFileRawBufferEncoder__(_iFileBase\*_ apBaseFile) -> _iFile\*_: Create a Raw buffer encoder file. 
- __iZip::CreateFileRawBufferDecoder__(_iFileBase\*_ apBaseFile, _tSize_ aDecodedSize) -> _iFile\*_: Create a Raw buffer decoder file. \see iLang::CreateFileBufferDecoder 
- __iZip::CreateZipArchive__(_iFile\*_ apDest, _const achar\*_ aaszPwd, _const tStringCVec\*_ apStoredExtensions) -> _iZipArchWrite\*_: Create a new zip archive writter. 
- __iZip::GZipOpen__(_iFileBase\*_ apFile, _tU32_ aulCompressionMode) -> _iFile\*_: Open a file which can write or read directly in a zip file. 
- __iZip::ZipOpen__(_iFileBase\*_ apFile, _tU32_ aulCompressionMode) -> _iFile\*_: Open a file which can write or read directly in a zip file. 

## interface ni::iZipArchWrite
Zip archive writer 

### Parents:
- iUnknown

### Methods:
- __iZipArchWrite::AddFileBlock__(_const achar\*_ aaszName, _iFile\*_ apFile, _tI64_ aSize) -> _tBool_: Adds a file block to the archive. 
- __iZipArchWrite::AddRawBlock__(_const achar\*_ aaszName, _tPtr_ apData, _tSize_ aSize) -> _tBool_: Adds a block of raw data as a file. 

## interface ni::iObjectTypeDef
Object type definition interface. 

### Parents:
- iUnknown

### Methods:
- __iObjectTypeDef::GetName__() -> _const achar\*_: Get the object type's name. 
- __iObjectTypeDef::CreateInstance__(_const Var&_ aVarA, _const Var&_ aVarB) -> _iUnknown\*_: Create an instance of the object. 

## interface ni::iModuleDef
Module definition interface. 

### Parents:
- iUnknown

### Methods:
- __iModuleDef::GetName__() -> _const achar\*_: Get the module's name. 
- __iModuleDef::GetVersion__() -> _const achar\*_: Get the module's version. 
- __iModuleDef::GetDesc__() -> _const achar\*_: Get the module's description. 
- __iModuleDef::GetAuthor__() -> _const achar\*_: Get the module's author. 
- __iModuleDef::GetCopyright__() -> _const achar\*_: Get the module's copyright. 
- __iModuleDef::GetNumDependencies__() -> _const tU32_: Get the number of dependencies. 
- __iModuleDef::GetDependency__(_tU32_ anIndex) -> _const achar\*_: Get the dependency at the given index. 
- __iModuleDef::GetNumInterfaces__() -> _const tU32_: Get the number of interfaces. 
- __iModuleDef::GetInterface__(_tU32_ anIndex) -> _const sInterfaceDef\*_: Get the interface at the given index. 
- __iModuleDef::GetNumEnums__() -> _const tU32_: Get the number of enumerations. 
- __iModuleDef::GetEnum__(_tU32_ anIndex) -> _const sEnumDef\*_: Get the enumeration at the given index. 
- __iModuleDef::GetNumConstants__() -> _const tU32_: Get the number of constants. 
- __iModuleDef::GetConstant__(_tU32_ anIndex) -> _const sConstantDef\*_: Get the constant at the given index. 
- __iModuleDef::GetNumObjectTypes__() -> _const tU32_: Get the number of object types. 
- __iModuleDef::GetObjectType__(_tU32_ anIndex) -> _const iObjectTypeDef\*_: Get the object type at the given index, 

## interface ni::iObjectTypeDef
Object type definition interface. 

### Parents:
- iUnknown

### Methods:
- __iObjectTypeDef::GetName__() -> _const achar\*_: Get the object type's name. 
- __iObjectTypeDef::CreateInstance__(_const Var&_ aVarA, _const Var&_ aVarB) -> _iUnknown\*_: Create an instance of the object. 

## enum ni::eStrFindFlags
Str find flags 

### Values:
- __eStrFindFlags_Forward__ = __0__
- __eStrFindFlags_Reversed__ = __niBit(0)__
- __eStrFindFlags_ICmp__ = __niBit(1)__
- __eStrFindFlags_ForwardI__ = __eStrFindFlags_Forward|eStrFindFlags_ICmp__
- __eStrFindFlags_ReversedI__ = __eStrFindFlags_Reversed|eStrFindFlags_ICmp__

## enum ni::eUCPCategory
Unicode code point general character categories 

### Values:
- __eUCPCategory_Other__ = __0__
- __eUCPCategory_Letter__ = __1__
- __eUCPCategory_Mark__ = __2__
- __eUCPCategory_Number__ = __3__
- __eUCPCategory_Punctuation__ = __4__
- __eUCPCategory_Symbol__ = __5__
- __eUCPCategory_Separator__ = __6__

## enum ni::eUCPCharType
Unicode code point particular character types 

### Values:
- __eUCPCharType_Cc__ = __0__: Control 
- __eUCPCharType_Cf__ = __1__: Format 
- __eUCPCharType_Cn__ = __2__: Unassigned 
- __eUCPCharType_Co__ = __3__: Private use 
- __eUCPCharType_Cs__ = __4__: Surrogate 
- __eUCPCharType_Ll__ = __5__: Lower case letter 
- __eUCPCharType_Lm__ = __6__: Modifier letter 
- __eUCPCharType_Lo__ = __7__: Other letter 
- __eUCPCharType_Lt__ = __8__: Title case letter 
- __eUCPCharType_Lu__ = __9__: Upper case letter 
- __eUCPCharType_Mc__ = __10__: Spacing mark 
- __eUCPCharType_Me__ = __11__: Enclosing mark 
- __eUCPCharType_Mn__ = __12__: Non-spacing mark 
- __eUCPCharType_Nd__ = __13__: Decimal number 
- __eUCPCharType_Nl__ = __14__: Letter number 
- __eUCPCharType_No__ = __15__: Other number 
- __eUCPCharType_Pc__ = __16__: Connector punctuation 
- __eUCPCharType_Pd__ = __17__: Dash punctuation 
- __eUCPCharType_Pe__ = __18__: Close punctuation 
- __eUCPCharType_Pf__ = __19__: Final punctuation 
- __eUCPCharType_Pi__ = __20__: Initial punctuation 
- __eUCPCharType_Po__ = __21__: Other punctuation 
- __eUCPCharType_Ps__ = __22__: Open punctuation 
- __eUCPCharType_Sc__ = __23__: Currency symbol 
- __eUCPCharType_Sk__ = __24__: Modifier symbol 
- __eUCPCharType_Sm__ = __25__: Mathematical symbol 
- __eUCPCharType_So__ = __26__: Other symbol 
- __eUCPCharType_Zl__ = __27__: Line separator 
- __eUCPCharType_Zp__ = __28__: Paragraph separator 
- __eUCPCharType_Zs__ = __29__: Space separator 

## enum ni::eUCPScript
Unicode code point script identifications 

### Values:
- __eUCPScript_Arabic__ = __0__
- __eUCPScript_Armenian__ = __1__
- __eUCPScript_Bengali__ = __2__
- __eUCPScript_Bopomofo__ = __3__
- __eUCPScript_Braille__ = __4__
- __eUCPScript_Buginese__ = __5__
- __eUCPScript_Buhid__ = __6__
- __eUCPScript_Canadian_Aboriginal__ = __7__
- __eUCPScript_Cherokee__ = __8__
- __eUCPScript_Common__ = __9__
- __eUCPScript_Coptic__ = __10__
- __eUCPScript_Cypriot__ = __11__
- __eUCPScript_Cyrillic__ = __12__
- __eUCPScript_Deseret__ = __13__
- __eUCPScript_Devanagari__ = __14__
- __eUCPScript_Ethiopic__ = __15__
- __eUCPScript_Georgian__ = __16__
- __eUCPScript_Glagolitic__ = __17__
- __eUCPScript_Gothic__ = __18__
- __eUCPScript_Greek__ = __19__
- __eUCPScript_Gujarati__ = __20__
- __eUCPScript_Gurmukhi__ = __21__
- __eUCPScript_Han__ = __22__
- __eUCPScript_Hangul__ = __23__
- __eUCPScript_Hanunoo__ = __24__
- __eUCPScript_Hebrew__ = __25__
- __eUCPScript_Hiragana__ = __26__
- __eUCPScript_Inherited__ = __27__
- __eUCPScript_Kannada__ = __28__
- __eUCPScript_Katakana__ = __29__
- __eUCPScript_Kharoshthi__ = __30__
- __eUCPScript_Khmer__ = __31__
- __eUCPScript_Lao__ = __32__
- __eUCPScript_Latin__ = __33__
- __eUCPScript_Limbu__ = __34__
- __eUCPScript_Linear_B__ = __35__
- __eUCPScript_Malayalam__ = __36__
- __eUCPScript_Mongolian__ = __37__
- __eUCPScript_Myanmar__ = __38__
- __eUCPScript_New_Tai_Lue__ = __39__
- __eUCPScript_Ogham__ = __40__
- __eUCPScript_Old_Italic__ = __41__
- __eUCPScript_Old_Persian__ = __42__
- __eUCPScript_Oriya__ = __43__
- __eUCPScript_Osmanya__ = __44__
- __eUCPScript_Runic__ = __45__
- __eUCPScript_Shavian__ = __46__
- __eUCPScript_Sinhala__ = __47__
- __eUCPScript_Syloti_Nagri__ = __48__
- __eUCPScript_Syriac__ = __49__
- __eUCPScript_Tagalog__ = __50__
- __eUCPScript_Tagbanwa__ = __51__
- __eUCPScript_Tai_Le__ = __52__
- __eUCPScript_Tamil__ = __53__
- __eUCPScript_Telugu__ = __54__
- __eUCPScript_Thaana__ = __55__
- __eUCPScript_Thai__ = __56__
- __eUCPScript_Tibetan__ = __57__
- __eUCPScript_Tifinagh__ = __58__
- __eUCPScript_Ugaritic__ = __59__
- __eUCPScript_Yi__ = __60__
- __eUCPScript_Balinese__ = __61__
- __eUCPScript_Cuneiform__ = __62__
- __eUCPScript_Nko__ = __63__
- __eUCPScript_Phags_Pa__ = __64__
- __eUCPScript_Phoenicia__ = __65__

## enum ni::eStrFindFlags
Str find flags 

### Values:
- __eStrFindFlags_Forward__ = __0__
- __eStrFindFlags_Reversed__ = __niBit(0)__
- __eStrFindFlags_ICmp__ = __niBit(1)__
- __eStrFindFlags_ForwardI__ = __eStrFindFlags_Forward|eStrFindFlags_ICmp__
- __eStrFindFlags_ReversedI__ = __eStrFindFlags_Reversed|eStrFindFlags_ICmp__

## enum ni::


### Values:
- __eTrue__ = __1__
- __eFalse__ = __0__
- __eTrueInDebug__ = __0__
- __eFalseInDebug__ = __1__

## variable ni::kFeatures

## variable ni::kTrue

## variable ni::kFalse

## variable ni::eInvalidHandle

## variable ni::kInvalidHandle

## variable ni::kMaxI8

## variable ni::kMinI8

## variable ni::kMaxU8

## variable ni::kMinU8

## variable ni::kMaxI16

## variable ni::kMinI16

## variable ni::kMaxU16

## variable ni::kMinU16

## variable ni::kMaxI32

## variable ni::kMinI32

## variable ni::kMaxU32

## variable ni::kMinU32

## variable ni::kMaxI64

## variable ni::kMinI64

## variable ni::kMaxU64

## variable ni::kMinU64

## variable ni::kMaxF32

## variable ni::kMinF32

## variable ni::kEpsilonF32

## variable ni::kMaxExpF32

## variable ni::kMinExpF32

## variable ni::kMaxF64

## variable ni::kMinF64

## variable ni::kEpsilonF64

## variable ni::kMaxExpF64

## variable ni::kMinExpF64

## variable ni::knTypeStringMaxSizeInChar

## variable ni::knUUIDSize

## variable ni::kuuidZero

## enum ni::eTypeFlags
Type flags. 

### Values:
- __eTypeFlags_Constant__ = __0x00000100__
- __eTypeFlags_Pointer__ = __0x00000200__
- __eTypeFlags_Collectable__ = __0x00000400__
- __eTypeFlags_Numeric__ = __0x00000800__
- __eTypeFlags_FUNCPROTO__ = __0x00001000__
- __eTypeFlags_STRING__ = __0x00002000__
- __eTypeFlags_TABLE__ = __0x00004000__
- __eTypeFlags_ARRAY__ = __0x00008000__
- __eTypeFlags_USERDATA__ = __0x00010000__
- __eTypeFlags_CLOSURE__ = __0x00020000__
- __eTypeFlags_NATIVECLOSURE__ = __0x00040000__
- __eTypeFlags_MethodOptional__ = __0x00080000__
- __eTypeFlags_MethodSetter__ = __0x00100000__
- __eTypeFlags_MethodGetter__ = __0x00200000__
- __eTypeFlags_MethodStatic__ = __0x00400000__

## enum ni::eType
Base types enumeration. 

### Values:
- __eType_Null__ = __0__
- __eType_IUnknown__ = __1__
- __eType_FirstGroup4__ = __0x10__
- __eType_I8__ = __eType_FirstGroup4+0__
- __eType_U8__ = __eType_FirstGroup4+1__
- __eType_I16__ = __eType_FirstGroup4+2__
- __eType_U16__ = __eType_FirstGroup4+3__
- __eType_I32__ = __eType_FirstGroup4+4__
- __eType_U32__ = __eType_FirstGroup4+5__
- __eType_F32__ = __eType_FirstGroup4+6__
- __eType_AChar__ = __eType_FirstGroup4+7__
- __eType_LastGroup4__ = __0x1F__
- __eType_FirstGroup8__ = __0x20__
- __eType_I64__ = __eType_FirstGroup8+0__
- __eType_U64__ = __eType_FirstGroup8+1__
- __eType_F64__ = __eType_FirstGroup8+2__
- __eType_Vec2f__ = __eType_FirstGroup8+3__
- __eType_Vec2i__ = __eType_FirstGroup8+4__
- __eType_LastGroup8__ = __0x2F__
- __eType_FirstGroup12__ = __0x30__
- __eType_Vec3f__ = __eType_FirstGroup12+0__
- __eType_Vec3i__ = __eType_FirstGroup12+1__
- __eType_String__ = __eType_FirstGroup12+2__
- __eType_LastGroup12__ = __0x3F__
- __eType_FirstGroup16__ = __0x40__
- __eType_Vec4f__ = __eType_FirstGroup16+0__
- __eType_Vec4i__ = __eType_FirstGroup16+1__
- __eType_UUID__ = __eType_FirstGroup16+2__
- __eType_LastGroup16__ = __0x4F__
- __eType_FirstExtended__ = __0x50__
- __eType_Matrixf__ = __eType_FirstExtended+0__
- __eType_Variant__ = __eType_FirstExtended+1__
- __eType_LastExtended__ = __0x7F__
- __eType_Enum__ = __eType_U32__
- __eType_Ptr__ = __eType_U32__
- __eType_Size__ = __eType_U32__
- __eType_Offset__ = __eType_U32__
- __eType_IntPtr__ = __eType_I32__
- __eType_UIntPtr__ = __eType_U32__
- __eType_Int__ = __eType_I32__
- __eType_UInt__ = __eType_U32__
- __eType_ASZ__ = __eType_AChar|eTypeFlags_Constant|eTypeFlags_Pointer__
- __eType_IUnknownPtr__ = __eType_IUnknown|eTypeFlags_Pointer__

## variable ni::knMaxSizeOfTypeRetByValue

## variable ni::knTypeRawNumBits

## variable ni::knTypeMask

## enum ni::


### Values:
- __eTrue__ = __1__
- __eFalse__ = __0__
- __eTrueInDebug__ = __0__
- __eFalseInDebug__ = __1__

## enum ni::eLogFlags
Log flags. 

### Values:
- __eLogFlags_Raw__ = __niBit(0)__: Raw type, log the message as-is without any formatting. 
- __eLogFlags_Debug__ = __niBit(1)__: Debug log. 
- __eLogFlags_Info__ = __niBit(2)__: Info log. 
- __eLogFlags_Warning__ = __niBit(3)__: Warning log. 
- __eLogFlags_Error__ = __niBit(4)__: Error log. 
- __eLogFlags_All__ = __0xFFFF__: All types. (max 16 bits) 
- __eLogFlags_FormatMSVC__ = __niBit(16)__: Format as a MSVC error message. 
- __eLogFlags_NoCallbackOutput__ = __niBit(17)__: Do not call the log callback. 
- __eLogFlags_NoRegularOutput__ = __niBit(18)__: Do not output to the regular loggers, only the log callback can be called. 
- __eLogFlags_NoNewLine__ = __niBit(19)__: If possible, do not append a new line. 
- __eLogFlags_Stdout__ = __niBit(20)__: Outputs to stdout. Stderr is the default when not specified. 
- __eLogFlags_NoLogTypePrefix__ = __niBit(21)__: Do not prefix with the log type. 

## enum ni::eLogFlags
Log flags. 

### Values:
- __eLogFlags_Raw__ = __niBit(0)__: Raw type, log the message as-is without any formatting. 
- __eLogFlags_Debug__ = __niBit(1)__: Debug log. 
- __eLogFlags_Info__ = __niBit(2)__: Info log. 
- __eLogFlags_Warning__ = __niBit(3)__: Warning log. 
- __eLogFlags_Error__ = __niBit(4)__: Error log. 
- __eLogFlags_All__ = __0xFFFF__: All types. (max 16 bits) 
- __eLogFlags_FormatMSVC__ = __niBit(16)__: Format as a MSVC error message. 
- __eLogFlags_NoCallbackOutput__ = __niBit(17)__: Do not call the log callback. 
- __eLogFlags_NoRegularOutput__ = __niBit(18)__: Do not output to the regular loggers, only the log callback can be called. 
- __eLogFlags_NoNewLine__ = __niBit(19)__: If possible, do not append a new line. 
- __eLogFlags_Stdout__ = __niBit(20)__: Outputs to stdout. Stderr is the default when not specified. 
- __eLogFlags_NoLogTypePrefix__ = __niBit(21)__: Do not prefix with the log type. 

## variable ni::kfE

## variable ni::kPi

## variable ni::kPi2

## variable ni::kPi4

## variable ni::k2Pi

## variable ni::k1ByPi

## variable ni::kInfinity

## variable ni::kEpsilon

## variable ni::kvec2fZero

## variable ni::kvec2lZero

## variable ni::kvec3fZero

## variable ni::kvec3lZero

## variable ni::kvec4fZero

## variable ni::kvec4lZero

## variable ni::kmtxfZero

## variable ni::kmtxfIdentity

## enum ni::ePlaneType
Plane type. 

### Values:
- __ePlaneType_X__ = __0__
- __ePlaneType_YZ__ = __ePlaneType_X__
- __ePlaneType_Y__ = __1__
- __ePlaneType_XZ__ = __ePlaneType_Y__
- __ePlaneType_Z__ = __2__
- __ePlaneType_XY__ = __ePlaneType_Z__
- __ePlaneType_NonAxial__ = __3__

## enum ni::eQuatSlerp
Quat slerp mode 

### Values:
- __eQuatSlerp_Short__ = __0__: The rotation will be less than 180 degrees, default. 
- __eQuatSlerp_Long__ = __1__: Rotation will be greater than 180 degrees. 
- __eQuatSlerp_NoCorrection__ = __2__: No correction is applied to garantee either a short or long path when doing the slerp. 

## enum ni::eRectCorners
Rect corners. 

### Values:
- __eRectCorners_TopLeft__ = __niBit(0)__: Top left rectangle corner. 
- __eRectCorners_TopRight__ = __niBit(1)__: Top right rectangle corner. 
- __eRectCorners_BottomRight__ = __niBit(2)__: Bottom right rectangle corner. 
- __eRectCorners_BottomLeft__ = __niBit(3)__: Bottom left rectangle corner. 
- __eRectCorners_Top__ = __eRectCorners_TopLeft|eRectCorners_TopRight__: Top rectangle corners. 
- __eRectCorners_Right__ = __eRectCorners_TopRight|eRectCorners_BottomRight__: Right rectangle corners. 
- __eRectCorners_Bottom__ = __eRectCorners_BottomRight|eRectCorners_BottomLeft__: Bottom rectangle corners. 
- __eRectCorners_Left__ = __eRectCorners_TopLeft|eRectCorners_BottomLeft__: Left rectangle corners, 
- __eRectCorners_All__ = __eRectCorners_TopLeft|eRectCorners_TopRight|eRectCorners_BottomRight|eRectCorners_BottomLeft__: All rectangle corners. 

## enum ni::eRectEdges
Rect edges. 

### Values:
- __eRectEdges_Top__ = __niBit(0)__: Top rectangle edge. 
- __eRectEdges_Right__ = __niBit(1)__: Right rectangle edge. 
- __eRectEdges_Bottom__ = __niBit(2)__: Bottom rectangle edge. 
- __eRectEdges_Left__ = __niBit(3)__: Left rectangle edge. 
- __eRectEdges_Vertical__ = __eRectEdges_Left|eRectEdges_Right__: Vertical rectangle edges. 
- __eRectEdges_Horizontal__ = __eRectEdges_Top|eRectEdges_Bottom__: Horizontal rectangle edges, 
- __eRectEdges_All__ = __eRectEdges_Vertical|eRectEdges_Horizontal__: All rectangle edges. 

## enum ni::eRectFrameFlags
Rect frame flags 

### Values:
- __eRectFrameFlags_TopEdge__ = __niBit(0)__: Top rectangle edge. 
- __eRectFrameFlags_RightEdge__ = __niBit(1)__: Right rectangle edge. 
- __eRectFrameFlags_BottomEdge__ = __niBit(2)__: Bottom rectangle edge. 
- __eRectFrameFlags_LeftEdge__ = __niBit(3)__: Left rectangle edge. 
- __eRectFrameFlags_TopLeftCorner__ = __niBit(4)__: Top left corner. 
- __eRectFrameFlags_TopRightCorner__ = __niBit(5)__: Top right corner. 
- __eRectFrameFlags_BottomLeftCorner__ = __niBit(6)__: Top left corner. 
- __eRectFrameFlags_BottomRightCorner__ = __niBit(7)__: Top left corner. 
- __eRectFrameFlags_Center__ = __niBit(8)__: Center of the rectangle 
- __eRectFrameFlags_TopSide__ = __eRectFrameFlags_TopEdge|eRectFrameFlags_TopLeftCorner|eRectFrameFlags_TopRightCorner__: Top side 
- __eRectFrameFlags_BottomSide__ = __eRectFrameFlags_BottomEdge|eRectFrameFlags_BottomLeftCorner|eRectFrameFlags_BottomRightCorner__: Bottom side 
- __eRectFrameFlags_LeftSide__ = __eRectFrameFlags_LeftEdge|eRectFrameFlags_TopLeftCorner|eRectFrameFlags_BottomLeftCorner__: Left side 
- __eRectFrameFlags_RightSide__ = __eRectFrameFlags_RightEdge|eRectFrameFlags_TopRightCorner|eRectFrameFlags_BottomRightCorner__: Right side 
- __eRectFrameFlags_VerticalSides__ = __eRectFrameFlags_LeftSide|eRectFrameFlags_RightSide__: Vertidcal sides 
- __eRectFrameFlags_HorizontalSides__ = __eRectFrameFlags_TopSide|eRectFrameFlags_BottomSide__: Horizontal sides 
- __eRectFrameFlags_Edges__ = __eRectFrameFlags_VerticalSides|eRectFrameFlags_HorizontalSides__: All edges 
- __eRectFrameFlags_All__ = __eRectFrameFlags_VerticalSides|eRectFrameFlags_HorizontalSides|eRectFrameFlags_Center__: The all frame 

## variable ni::kfE

## variable ni::kNiCopyright

## variable ni::kNiCopyright

## variable ni::kbIsBigEndian

## variable ni::kbIsLittleEndian

## variable ni::kbIsBigEndian

## variable ni::kiidIUnknown

## enum ni::eListInterfacesFlags


### Values:
- __eListInterfacesFlags_All__ = __0__: List all interfaces 
- __eListInterfacesFlags_NoDynamic__ = __niBit(1)__: Don't list 'dynamic' interfaces (interfaces in sink that extend the object). 
- __eListInterfacesFlags_DynamicOnly__ = __niBit(2)__: Only list 'dynamic' interfaces (interfaces in sink that extend the object). 

## interface ni::iUnknown
iUnknown interface 

### Remarks:
- iUnknown is the base of all ni interfaces. It support reference counting and sanity check throught the IsOK() method. 

### Methods:
- __iUnknown::IsOK__() -> _tBool_: Check if the object is valid. 
- __iUnknown::AddRef__() -> _tI32_: Signal that one more reference of the object has been created. 
- __iUnknown::Release__() -> _tI32_: Release a reference of the object. 
- __iUnknown::DeleteThis__() -> _void_: Bypass any reference counting and delete this object. 
- __iUnknown::Invalidate__() -> _void_: Invalidate the object. 
- __iUnknown::QueryInterface__(_const tUUID&_ aIID) -> _iUnknown\*_: Query an interface. 
- __iUnknown::ListInterfaces__(_iMutableCollection\*_ apLst, _tU32_ anFlags) -> _void_: Fill a UUID list containing the UUIDs of the implemented interfaces. 
- __iUnknown::SetNumRefs__(_tI32_ anNumRefs) -> _tI32_: Set the reference counter directly. 
- __iUnknown::GetNumRefs__() -> _tI32_: Get the number of references to this object. 

## interface ni::iDispatch
IDispatch interface. 

### Parents:
- iUnknown

### Methods:
- __iDispatch::InitializeMethods__(_const sMethodDef\* const\*_ apMethods, _ni::tU32_ anNumMethods) -> _tBool_: Initialize the methods. 
- __iDispatch::CallMethod__(_const sMethodDef\* const_ apMethodDef, _ni::tU32_ anMethodIndex, _const Var\*_ apParameters, _tU32_ anNumParameters, _Var\*_ apRet) -> _tBool_: Call the specified method. 

## variable ni::kiidIUnknown

## variable ni::eVMRet_OK

## variable ni::eVMRet_InvalidArgCount

## variable ni::eVMRet_InvalidMethod

## variable ni::eVMRet_InvalidArg

## variable ni::eVMRet_InvalidRet

## variable ni::eVMRet_InvalidNullArg

## variable ni::eVMRet_OutOfMemory

## variable ni::eVMRet_OK

## enum ni::eFileAttrFlags
File attributes 

### Values:
- __eFileAttrFlags_File__ = __niBit(0)__: File. 
- __eFileAttrFlags_Directory__ = __niBit(1)__: Directory. 
- __eFileAttrFlags_Archive__ = __niBit(3)__: Archive. 
- __eFileAttrFlags_ReadOnly__ = __niBit(4)__: Read only. 
- __eFileAttrFlags_Hidden__ = __niBit(5)__: Hidden attribute. 
- __eFileAttrFlags_System__ = __niBit(6)__: System attribute. 
- __eFileAttrFlags_Virtual__ = __niBit(7)__: The file is 'virtual', aka it is not stored in the standard OS's file system, most likely it is stored within an archive or a-like. 
- __eFileAttrFlags_Device__ = __niBit(8)__: Device attribute. 
- __eFileAttrFlags_DeviceFixed__ = __eFileAttrFlags_Device|niBit(15)__: Fixed device attribute. 
- __eFileAttrFlags_DeviceRemovable__ = __eFileAttrFlags_Device|niBit(16)__: Removable device attribute. 
- __eFileAttrFlags_DeviceRAM__ = __eFileAttrFlags_Device|niBit(17)__: RAM drive device attribute. 
- __eFileAttrFlags_DeviceRemote__ = __eFileAttrFlags_Device|niBit(18)__: Remote device attribute. 
- __eFileAttrFlags_DeviceFloppy__ = __eFileAttrFlags_Device|eFileAttrFlags_DeviceRemovable|niBit(19)__: Floppy device attribute. 
- __eFileAttrFlags_DeviceCDRom__ = __eFileAttrFlags_Device|eFileAttrFlags_DeviceRemovable|niBit(20)__: CDRom device attribute. 
- __eFileAttrFlags_DeviceReserved0__ = __eFileAttrFlags_Device|niBit(21)__: Reserved0 device attribute. 
- __eFileAttrFlags_DeviceReserved1__ = __eFileAttrFlags_Device|niBit(22)__: Reserved1 device attribute. 
- __eFileAttrFlags_DeviceReserved2__ = __eFileAttrFlags_Device|niBit(23)__: Reserved2 device attribute. 
- __eFileAttrFlags_DeviceReserved3__ = __eFileAttrFlags_Device|niBit(24)__: Reserved3 device attribute. 
- __eFileAttrFlags_DeviceReserved4__ = __eFileAttrFlags_Device|niBit(25)__: Reserved4 device attribute. 
- __eFileAttrFlags_DeviceReserved5__ = __eFileAttrFlags_Device|niBit(26)__: Reserved5 device attribute. 
- __eFileAttrFlags_DeviceReserved6__ = __eFileAttrFlags_Device|niBit(27)__: Reserved6 device attribute. 
- __eFileAttrFlags_DeviceReserved7__ = __eFileAttrFlags_Device|niBit(28)__: Reserved7 device attribute. 
- __eFileAttrFlags_DeviceReserved8__ = __eFileAttrFlags_Device|niBit(29)__: Reserved8 device attribute. 
- __eFileAttrFlags_DeviceReserved9__ = __eFileAttrFlags_Device|niBit(30)__: Reserved9 device attribute. 
- __eFileAttrFlags_DeviceReserved10__ = __eFileAttrFlags_Device|niBit(31)__: Reserved10 device attribute. 
- __eFileAttrFlags_All__ = __eFileAttrFlags_File|eFileAttrFlags_Directory__: All. 
- __eFileAttrFlags_AllFiles__ = __eFileAttrFlags_File__: All files. 
- __eFileAttrFlags_AllDirectories__ = __eFileAttrFlags_Directory__: All directories. 

## enum ni::eFileTime
File time. 

### Values:
- __eFileTime_Creation__ = __0__: Creation file time. 
- __eFileTime_LastAccess__ = __1__: Last access file time. 
- __eFileTime_LastWrite__ = __2__: Last write file time. 

## enum ni::eFileOpenMode
File open mode. 

### Values:
- __eFileOpenMode_Read__ = __niBit(0)__: Read open mode. 
- __eFileOpenMode_Write__ = __niBit(1)__: Write open mode. 
- __eFileOpenMode_Append__ = __niBit(2)|eFileOpenMode_Write__: Append open mode. 
- __eFileOpenMode_Random__ = __niBit(3)__: Optimized form random access. 

## enum ni::eFileAttrFlags
File attributes 

### Values:
- __eFileAttrFlags_File__ = __niBit(0)__: File. 
- __eFileAttrFlags_Directory__ = __niBit(1)__: Directory. 
- __eFileAttrFlags_Archive__ = __niBit(3)__: Archive. 
- __eFileAttrFlags_ReadOnly__ = __niBit(4)__: Read only. 
- __eFileAttrFlags_Hidden__ = __niBit(5)__: Hidden attribute. 
- __eFileAttrFlags_System__ = __niBit(6)__: System attribute. 
- __eFileAttrFlags_Virtual__ = __niBit(7)__: The file is 'virtual', aka it is not stored in the standard OS's file system, most likely it is stored within an archive or a-like. 
- __eFileAttrFlags_Device__ = __niBit(8)__: Device attribute. 
- __eFileAttrFlags_DeviceFixed__ = __eFileAttrFlags_Device|niBit(15)__: Fixed device attribute. 
- __eFileAttrFlags_DeviceRemovable__ = __eFileAttrFlags_Device|niBit(16)__: Removable device attribute. 
- __eFileAttrFlags_DeviceRAM__ = __eFileAttrFlags_Device|niBit(17)__: RAM drive device attribute. 
- __eFileAttrFlags_DeviceRemote__ = __eFileAttrFlags_Device|niBit(18)__: Remote device attribute. 
- __eFileAttrFlags_DeviceFloppy__ = __eFileAttrFlags_Device|eFileAttrFlags_DeviceRemovable|niBit(19)__: Floppy device attribute. 
- __eFileAttrFlags_DeviceCDRom__ = __eFileAttrFlags_Device|eFileAttrFlags_DeviceRemovable|niBit(20)__: CDRom device attribute. 
- __eFileAttrFlags_DeviceReserved0__ = __eFileAttrFlags_Device|niBit(21)__: Reserved0 device attribute. 
- __eFileAttrFlags_DeviceReserved1__ = __eFileAttrFlags_Device|niBit(22)__: Reserved1 device attribute. 
- __eFileAttrFlags_DeviceReserved2__ = __eFileAttrFlags_Device|niBit(23)__: Reserved2 device attribute. 
- __eFileAttrFlags_DeviceReserved3__ = __eFileAttrFlags_Device|niBit(24)__: Reserved3 device attribute. 
- __eFileAttrFlags_DeviceReserved4__ = __eFileAttrFlags_Device|niBit(25)__: Reserved4 device attribute. 
- __eFileAttrFlags_DeviceReserved5__ = __eFileAttrFlags_Device|niBit(26)__: Reserved5 device attribute. 
- __eFileAttrFlags_DeviceReserved6__ = __eFileAttrFlags_Device|niBit(27)__: Reserved6 device attribute. 
- __eFileAttrFlags_DeviceReserved7__ = __eFileAttrFlags_Device|niBit(28)__: Reserved7 device attribute. 
- __eFileAttrFlags_DeviceReserved8__ = __eFileAttrFlags_Device|niBit(29)__: Reserved8 device attribute. 
- __eFileAttrFlags_DeviceReserved9__ = __eFileAttrFlags_Device|niBit(30)__: Reserved9 device attribute. 
- __eFileAttrFlags_DeviceReserved10__ = __eFileAttrFlags_Device|niBit(31)__: Reserved10 device attribute. 
- __eFileAttrFlags_All__ = __eFileAttrFlags_File|eFileAttrFlags_Directory__: All. 
- __eFileAttrFlags_AllFiles__ = __eFileAttrFlags_File__: All files. 
- __eFileAttrFlags_AllDirectories__ = __eFileAttrFlags_Directory__: All directories. 
