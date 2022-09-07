# Module niUI
Generated on 2022-09-07T10:09:42+08:00

- name: niUI
- desc: UI module
- version: 1,0,0
- author: niLang Authors
- copyright: (c) 2022 The niLang Authors

## enum ni::eColorSpace
Color spaces 

### Values:
- __eColorSpace_RGB__ = __0__: RGB color space 
- __eColorSpace_CMY__ = __1__: CMY color space 
- __eColorSpace_CMYK__ = __2__: CMYK color space 
- __eColorSpace_HSV__ = __3__: HSV color space 
- __eColorSpace_HSL__ = __4__: HSL color space 
- __eColorSpace_XYZ__ = __5__: XYZ color space 
- __eColorSpace_Yxy__ = __6__: Yxy color space 
- __eColorSpace_HunterLab__ = __7__: Hunter lab color space 
- __eColorSpace_CIELab__ = __8__: CIE Lab color space 
- __eColorSpace_CIELCH__ = __9__: CIE LCH color space 
- __eColorSpace_CIELuv__ = __10__: CIE Luv color space 
- __eColorSpace_YIQ__ = __11__: YIQ color space (NTSC/USA TV). 
- __eColorSpace_YUV__ = __12__: YUV color space (PAL/Europe TV). 
- __eColorSpace_YCbCr__ = __13__: YCbCr color space. 
- __eColorSpace_YPbPr__ = __14__: YPbPr color space (HDTV). 
- __eColorSpace_YCoCg__ = __15__: YCoCg color space (H264 & AVT). 
- __eColorSpace_Last__ = __16__: \internal 

## enum ni::eColor


### Values:
- __eColor_aliceblue__ = __niBuildColor(240,248,255,255)__
- __eColor_antiquewhite__ = __niBuildColor(250,235,215,255)__
- __eColor_aqua__ = __niBuildColor(0,255,255,255)__
- __eColor_aquamarine__ = __niBuildColor(127,255,212,255)__
- __eColor_azure__ = __niBuildColor(240,255,255,255)__
- __eColor_beige__ = __niBuildColor(245,245,220,255)__
- __eColor_bisque__ = __niBuildColor(255,228,196,255)__
- __eColor_black__ = __niBuildColor(0,0,0,255)__
- __eColor_blanchedalmond__ = __niBuildColor(255,235,205,255)__
- __eColor_blue__ = __niBuildColor(0,0,255,255)__
- __eColor_blueviolet__ = __niBuildColor(138,43,226,255)__
- __eColor_brown__ = __niBuildColor(165,42,42,255)__
- __eColor_burlywood__ = __niBuildColor(222,184,135,255)__
- __eColor_cadetblue__ = __niBuildColor(95,158,160,255)__
- __eColor_chartreuse__ = __niBuildColor(127,255,0,255)__
- __eColor_chocolate__ = __niBuildColor(210,105,30,255)__
- __eColor_coral__ = __niBuildColor(255,127,80,255)__
- __eColor_cornflowerblue__ = __niBuildColor(100,149,237,255)__
- __eColor_cornsilk__ = __niBuildColor(255,248,220,255)__
- __eColor_crimson__ = __niBuildColor(220,20,60,255)__
- __eColor_cyan__ = __niBuildColor(0,255,255,255)__
- __eColor_darkblue__ = __niBuildColor(0,0,139,255)__
- __eColor_darkcyan__ = __niBuildColor(0,139,139,255)__
- __eColor_darkgoldenrod__ = __niBuildColor(184,134,11,255)__
- __eColor_darkgray__ = __niBuildColor(169,169,169,255)__
- __eColor_darkgreen__ = __niBuildColor(0,100,0,255)__
- __eColor_darkgrey__ = __niBuildColor(169,169,169,255)__
- __eColor_darkkhaki__ = __niBuildColor(189,183,107,255)__
- __eColor_darkmagenta__ = __niBuildColor(139,0,139,255)__
- __eColor_darkolivegreen__ = __niBuildColor(85,107,47,255)__
- __eColor_darkorange__ = __niBuildColor(255,140,0,255)__
- __eColor_darkorchid__ = __niBuildColor(153,50,204,255)__
- __eColor_darkred__ = __niBuildColor(139,0,0,255)__
- __eColor_darksalmon__ = __niBuildColor(233,150,122,255)__
- __eColor_darkseagreen__ = __niBuildColor(143,188,143,255)__
- __eColor_darkslateblue__ = __niBuildColor(72,61,139,255)__
- __eColor_darkslategray__ = __niBuildColor(47,79,79,255)__
- __eColor_darkslategrey__ = __niBuildColor(47,79,79,255)__
- __eColor_darkturquoise__ = __niBuildColor(0,206,209,255)__
- __eColor_darkviolet__ = __niBuildColor(148,0,211,255)__
- __eColor_deeppink__ = __niBuildColor(255,20,147,255)__
- __eColor_deepskyblue__ = __niBuildColor(0,191,255,255)__
- __eColor_dimgray__ = __niBuildColor(105,105,105,255)__
- __eColor_dimgrey__ = __niBuildColor(105,105,105,255)__
- __eColor_dodgerblue__ = __niBuildColor(30,144,255,255)__
- __eColor_firebrick__ = __niBuildColor(178,34,34,255)__
- __eColor_floralwhite__ = __niBuildColor(255,250,240,255)__
- __eColor_forestgreen__ = __niBuildColor(34,139,34,255)__
- __eColor_fuchsia__ = __niBuildColor(255,0,255,255)__
- __eColor_gainsboro__ = __niBuildColor(220,220,220,255)__
- __eColor_ghostwhite__ = __niBuildColor(248,248,255,255)__
- __eColor_gold__ = __niBuildColor(255,215,0,255)__
- __eColor_goldenrod__ = __niBuildColor(218,165,32,255)__
- __eColor_gray__ = __niBuildColor(128,128,128,255)__
- __eColor_green__ = __niBuildColor(0,128,0,255)__
- __eColor_greenyellow__ = __niBuildColor(173,255,47,255)__
- __eColor_grey__ = __niBuildColor(128,128,128,255)__
- __eColor_honeydew__ = __niBuildColor(240,255,240,255)__
- __eColor_hotpink__ = __niBuildColor(255,105,180,255)__
- __eColor_indianred__ = __niBuildColor(205,92,92,255)__
- __eColor_indigo__ = __niBuildColor(75,0,130,255)__
- __eColor_ivory__ = __niBuildColor(255,255,240,255)__
- __eColor_khaki__ = __niBuildColor(240,230,140,255)__
- __eColor_lavender__ = __niBuildColor(230,230,250,255)__
- __eColor_lavenderblush__ = __niBuildColor(255,240,245,255)__
- __eColor_lawngreen__ = __niBuildColor(124,252,0,255)__
- __eColor_lemonchiffon__ = __niBuildColor(255,250,205,255)__
- __eColor_lightblue__ = __niBuildColor(173,216,230,255)__
- __eColor_lightcoral__ = __niBuildColor(240,128,128,255)__
- __eColor_lightcyan__ = __niBuildColor(224,255,255,255)__
- __eColor_lightgoldenrodyellow__ = __niBuildColor(250,250,210,255)__
- __eColor_lightgray__ = __niBuildColor(211,211,211,255)__
- __eColor_lightgreen__ = __niBuildColor(144,238,144,255)__
- __eColor_lightgrey__ = __niBuildColor(211,211,211,255)__
- __eColor_lightpink__ = __niBuildColor(255,182,193,255)__
- __eColor_lightsalmon__ = __niBuildColor(255,160,122,255)__
- __eColor_lightseagreen__ = __niBuildColor(32,178,170,255)__
- __eColor_lightskyblue__ = __niBuildColor(135,206,250,255)__
- __eColor_lightslategray__ = __niBuildColor(119,136,153,255)__
- __eColor_lightslategrey__ = __niBuildColor(119,136,153,255)__
- __eColor_lightsteelblue__ = __niBuildColor(176,196,222,255)__
- __eColor_lightyellow__ = __niBuildColor(255,255,224,255)__
- __eColor_lime__ = __niBuildColor(0,255,0,255)__
- __eColor_limegreen__ = __niBuildColor(50,205,50,255)__
- __eColor_linen__ = __niBuildColor(250,240,230,255)__
- __eColor_magenta__ = __niBuildColor(255,0,255,255)__
- __eColor_maroon__ = __niBuildColor(128,0,0,255)__
- __eColor_mediumaquamarine__ = __niBuildColor(102,205,170,255)__
- __eColor_mediumblue__ = __niBuildColor(0,0,205,255)__
- __eColor_mediumorchid__ = __niBuildColor(186,85,211,255)__
- __eColor_mediumpurple__ = __niBuildColor(147,112,219,255)__
- __eColor_mediumseagreen__ = __niBuildColor(60,179,113,255)__
- __eColor_mediumslateblue__ = __niBuildColor(123,104,238,255)__
- __eColor_mediumspringgreen__ = __niBuildColor(0,250,154,255)__
- __eColor_mediumturquoise__ = __niBuildColor(72,209,204,255)__
- __eColor_mediumvioletred__ = __niBuildColor(199,21,133,255)__
- __eColor_midnightblue__ = __niBuildColor(25,25,112,255)__
- __eColor_mintcream__ = __niBuildColor(245,255,250,255)__
- __eColor_mistyrose__ = __niBuildColor(255,228,225,255)__
- __eColor_moccasin__ = __niBuildColor(255,228,181,255)__
- __eColor_navajowhite__ = __niBuildColor(255,222,173,255)__
- __eColor_navy__ = __niBuildColor(0,0,128,255)__
- __eColor_oldlace__ = __niBuildColor(253,245,230,255)__
- __eColor_olive__ = __niBuildColor(128,128,0,255)__
- __eColor_olivedrab__ = __niBuildColor(107,142,35,255)__
- __eColor_orange__ = __niBuildColor(255,165,0,255)__
- __eColor_orangered__ = __niBuildColor(255,69,0,255)__
- __eColor_orchid__ = __niBuildColor(218,112,214,255)__
- __eColor_palegoldenrod__ = __niBuildColor(238,232,170,255)__
- __eColor_palegreen__ = __niBuildColor(152,251,152,255)__
- __eColor_paleturquoise__ = __niBuildColor(175,238,238,255)__
- __eColor_palevioletred__ = __niBuildColor(219,112,147,255)__
- __eColor_papayawhip__ = __niBuildColor(255,239,213,255)__
- __eColor_peachpuff__ = __niBuildColor(255,218,185,255)__
- __eColor_peru__ = __niBuildColor(205,133,63,255)__
- __eColor_pink__ = __niBuildColor(255,192,203,255)__
- __eColor_plum__ = __niBuildColor(221,160,221,255)__
- __eColor_powderblue__ = __niBuildColor(176,224,230,255)__
- __eColor_purple__ = __niBuildColor(128,0,128,255)__
- __eColor_red__ = __niBuildColor(255,0,0,255)__
- __eColor_rosybrown__ = __niBuildColor(188,143,143,255)__
- __eColor_royalblue__ = __niBuildColor(65,105,225,255)__
- __eColor_saddlebrown__ = __niBuildColor(139,69,19,255)__
- __eColor_salmon__ = __niBuildColor(250,128,114,255)__
- __eColor_sandybrown__ = __niBuildColor(244,164,96,255)__
- __eColor_seagreen__ = __niBuildColor(46,139,87,255)__
- __eColor_seashell__ = __niBuildColor(255,245,238,255)__
- __eColor_sienna__ = __niBuildColor(160,82,45,255)__
- __eColor_silver__ = __niBuildColor(192,192,192,255)__
- __eColor_skyblue__ = __niBuildColor(135,206,235,255)__
- __eColor_slateblue__ = __niBuildColor(106,90,205,255)__
- __eColor_slategray__ = __niBuildColor(112,128,144,255)__
- __eColor_slategrey__ = __niBuildColor(112,128,144,255)__
- __eColor_snow__ = __niBuildColor(255,250,250,255)__
- __eColor_springgreen__ = __niBuildColor(0,255,127,255)__
- __eColor_steelblue__ = __niBuildColor(70,130,180,255)__
- __eColor_tan__ = __niBuildColor(210,180,140,255)__
- __eColor_teal__ = __niBuildColor(0,128,128,255)__
- __eColor_thistle__ = __niBuildColor(216,191,216,255)__
- __eColor_tomato__ = __niBuildColor(255,99,71,255)__
- __eColor_turquoise__ = __niBuildColor(64,224,208,255)__
- __eColor_violet__ = __niBuildColor(238,130,238,255)__
- __eColor_wheat__ = __niBuildColor(245,222,179,255)__
- __eColor_white__ = __niBuildColor(255,255,255,255)__
- __eColor_whitesmoke__ = __niBuildColor(245,245,245,255)__
- __eColor_yellow__ = __niBuildColor(255,255,0,255)__
- __eColor_yellowgreen__ = __niBuildColor(154,205,50,255)__
- __eColor_zzzzzzzzzzz__ = __niBuildColor(0,0,0,0)__
- __eColor_zzzz__ = __niBuildColor(0,0,0,0)__

## variable ni::kcolXYZRef2D65

## variable ni::kvColorLuminanceR21G71B07

## variable ni::kvColorLuminanceR27G67B06

## enum ni::eColorSpace
Color spaces 

### Values:
- __eColorSpace_RGB__ = __0__: RGB color space 
- __eColorSpace_CMY__ = __1__: CMY color space 
- __eColorSpace_CMYK__ = __2__: CMYK color space 
- __eColorSpace_HSV__ = __3__: HSV color space 
- __eColorSpace_HSL__ = __4__: HSL color space 
- __eColorSpace_XYZ__ = __5__: XYZ color space 
- __eColorSpace_Yxy__ = __6__: Yxy color space 
- __eColorSpace_HunterLab__ = __7__: Hunter lab color space 
- __eColorSpace_CIELab__ = __8__: CIE Lab color space 
- __eColorSpace_CIELCH__ = __9__: CIE LCH color space 
- __eColorSpace_CIELuv__ = __10__: CIE Luv color space 
- __eColorSpace_YIQ__ = __11__: YIQ color space (NTSC/USA TV). 
- __eColorSpace_YUV__ = __12__: YUV color space (PAL/Europe TV). 
- __eColorSpace_YCbCr__ = __13__: YCbCr color space. 
- __eColorSpace_YPbPr__ = __14__: YPbPr color space (HDTV). 
- __eColorSpace_YCoCg__ = __15__: YCoCg color space (H264 & AVT). 
- __eColorSpace_Last__ = __16__: \internal 

## enum ni::eColorSpace
Color spaces 

### Values:
- __eColorSpace_RGB__ = __0__: RGB color space 
- __eColorSpace_CMY__ = __1__: CMY color space 
- __eColorSpace_CMYK__ = __2__: CMYK color space 
- __eColorSpace_HSV__ = __3__: HSV color space 
- __eColorSpace_HSL__ = __4__: HSL color space 
- __eColorSpace_XYZ__ = __5__: XYZ color space 
- __eColorSpace_Yxy__ = __6__: Yxy color space 
- __eColorSpace_HunterLab__ = __7__: Hunter lab color space 
- __eColorSpace_CIELab__ = __8__: CIE Lab color space 
- __eColorSpace_CIELCH__ = __9__: CIE LCH color space 
- __eColorSpace_CIELuv__ = __10__: CIE Luv color space 
- __eColorSpace_YIQ__ = __11__: YIQ color space (NTSC/USA TV). 
- __eColorSpace_YUV__ = __12__: YUV color space (PAL/Europe TV). 
- __eColorSpace_YCbCr__ = __13__: YCbCr color space. 
- __eColorSpace_YPbPr__ = __14__: YPbPr color space (HDTV). 
- __eColorSpace_YCoCg__ = __15__: YCoCg color space (H264 & AVT). 
- __eColorSpace_Last__ = __16__: \internal 

## enum ni::eColor


### Values:
- __eColor_aliceblue__ = __niBuildColor(240,248,255,255)__
- __eColor_antiquewhite__ = __niBuildColor(250,235,215,255)__
- __eColor_aqua__ = __niBuildColor(0,255,255,255)__
- __eColor_aquamarine__ = __niBuildColor(127,255,212,255)__
- __eColor_azure__ = __niBuildColor(240,255,255,255)__
- __eColor_beige__ = __niBuildColor(245,245,220,255)__
- __eColor_bisque__ = __niBuildColor(255,228,196,255)__
- __eColor_black__ = __niBuildColor(0,0,0,255)__
- __eColor_blanchedalmond__ = __niBuildColor(255,235,205,255)__
- __eColor_blue__ = __niBuildColor(0,0,255,255)__
- __eColor_blueviolet__ = __niBuildColor(138,43,226,255)__
- __eColor_brown__ = __niBuildColor(165,42,42,255)__
- __eColor_burlywood__ = __niBuildColor(222,184,135,255)__
- __eColor_cadetblue__ = __niBuildColor(95,158,160,255)__
- __eColor_chartreuse__ = __niBuildColor(127,255,0,255)__
- __eColor_chocolate__ = __niBuildColor(210,105,30,255)__
- __eColor_coral__ = __niBuildColor(255,127,80,255)__
- __eColor_cornflowerblue__ = __niBuildColor(100,149,237,255)__
- __eColor_cornsilk__ = __niBuildColor(255,248,220,255)__
- __eColor_crimson__ = __niBuildColor(220,20,60,255)__
- __eColor_cyan__ = __niBuildColor(0,255,255,255)__
- __eColor_darkblue__ = __niBuildColor(0,0,139,255)__
- __eColor_darkcyan__ = __niBuildColor(0,139,139,255)__
- __eColor_darkgoldenrod__ = __niBuildColor(184,134,11,255)__
- __eColor_darkgray__ = __niBuildColor(169,169,169,255)__
- __eColor_darkgreen__ = __niBuildColor(0,100,0,255)__
- __eColor_darkgrey__ = __niBuildColor(169,169,169,255)__
- __eColor_darkkhaki__ = __niBuildColor(189,183,107,255)__
- __eColor_darkmagenta__ = __niBuildColor(139,0,139,255)__
- __eColor_darkolivegreen__ = __niBuildColor(85,107,47,255)__
- __eColor_darkorange__ = __niBuildColor(255,140,0,255)__
- __eColor_darkorchid__ = __niBuildColor(153,50,204,255)__
- __eColor_darkred__ = __niBuildColor(139,0,0,255)__
- __eColor_darksalmon__ = __niBuildColor(233,150,122,255)__
- __eColor_darkseagreen__ = __niBuildColor(143,188,143,255)__
- __eColor_darkslateblue__ = __niBuildColor(72,61,139,255)__
- __eColor_darkslategray__ = __niBuildColor(47,79,79,255)__
- __eColor_darkslategrey__ = __niBuildColor(47,79,79,255)__
- __eColor_darkturquoise__ = __niBuildColor(0,206,209,255)__
- __eColor_darkviolet__ = __niBuildColor(148,0,211,255)__
- __eColor_deeppink__ = __niBuildColor(255,20,147,255)__
- __eColor_deepskyblue__ = __niBuildColor(0,191,255,255)__
- __eColor_dimgray__ = __niBuildColor(105,105,105,255)__
- __eColor_dimgrey__ = __niBuildColor(105,105,105,255)__
- __eColor_dodgerblue__ = __niBuildColor(30,144,255,255)__
- __eColor_firebrick__ = __niBuildColor(178,34,34,255)__
- __eColor_floralwhite__ = __niBuildColor(255,250,240,255)__
- __eColor_forestgreen__ = __niBuildColor(34,139,34,255)__
- __eColor_fuchsia__ = __niBuildColor(255,0,255,255)__
- __eColor_gainsboro__ = __niBuildColor(220,220,220,255)__
- __eColor_ghostwhite__ = __niBuildColor(248,248,255,255)__
- __eColor_gold__ = __niBuildColor(255,215,0,255)__
- __eColor_goldenrod__ = __niBuildColor(218,165,32,255)__
- __eColor_gray__ = __niBuildColor(128,128,128,255)__
- __eColor_green__ = __niBuildColor(0,128,0,255)__
- __eColor_greenyellow__ = __niBuildColor(173,255,47,255)__
- __eColor_grey__ = __niBuildColor(128,128,128,255)__
- __eColor_honeydew__ = __niBuildColor(240,255,240,255)__
- __eColor_hotpink__ = __niBuildColor(255,105,180,255)__
- __eColor_indianred__ = __niBuildColor(205,92,92,255)__
- __eColor_indigo__ = __niBuildColor(75,0,130,255)__
- __eColor_ivory__ = __niBuildColor(255,255,240,255)__
- __eColor_khaki__ = __niBuildColor(240,230,140,255)__
- __eColor_lavender__ = __niBuildColor(230,230,250,255)__
- __eColor_lavenderblush__ = __niBuildColor(255,240,245,255)__
- __eColor_lawngreen__ = __niBuildColor(124,252,0,255)__
- __eColor_lemonchiffon__ = __niBuildColor(255,250,205,255)__
- __eColor_lightblue__ = __niBuildColor(173,216,230,255)__
- __eColor_lightcoral__ = __niBuildColor(240,128,128,255)__
- __eColor_lightcyan__ = __niBuildColor(224,255,255,255)__
- __eColor_lightgoldenrodyellow__ = __niBuildColor(250,250,210,255)__
- __eColor_lightgray__ = __niBuildColor(211,211,211,255)__
- __eColor_lightgreen__ = __niBuildColor(144,238,144,255)__
- __eColor_lightgrey__ = __niBuildColor(211,211,211,255)__
- __eColor_lightpink__ = __niBuildColor(255,182,193,255)__
- __eColor_lightsalmon__ = __niBuildColor(255,160,122,255)__
- __eColor_lightseagreen__ = __niBuildColor(32,178,170,255)__
- __eColor_lightskyblue__ = __niBuildColor(135,206,250,255)__
- __eColor_lightslategray__ = __niBuildColor(119,136,153,255)__
- __eColor_lightslategrey__ = __niBuildColor(119,136,153,255)__
- __eColor_lightsteelblue__ = __niBuildColor(176,196,222,255)__
- __eColor_lightyellow__ = __niBuildColor(255,255,224,255)__
- __eColor_lime__ = __niBuildColor(0,255,0,255)__
- __eColor_limegreen__ = __niBuildColor(50,205,50,255)__
- __eColor_linen__ = __niBuildColor(250,240,230,255)__
- __eColor_magenta__ = __niBuildColor(255,0,255,255)__
- __eColor_maroon__ = __niBuildColor(128,0,0,255)__
- __eColor_mediumaquamarine__ = __niBuildColor(102,205,170,255)__
- __eColor_mediumblue__ = __niBuildColor(0,0,205,255)__
- __eColor_mediumorchid__ = __niBuildColor(186,85,211,255)__
- __eColor_mediumpurple__ = __niBuildColor(147,112,219,255)__
- __eColor_mediumseagreen__ = __niBuildColor(60,179,113,255)__
- __eColor_mediumslateblue__ = __niBuildColor(123,104,238,255)__
- __eColor_mediumspringgreen__ = __niBuildColor(0,250,154,255)__
- __eColor_mediumturquoise__ = __niBuildColor(72,209,204,255)__
- __eColor_mediumvioletred__ = __niBuildColor(199,21,133,255)__
- __eColor_midnightblue__ = __niBuildColor(25,25,112,255)__
- __eColor_mintcream__ = __niBuildColor(245,255,250,255)__
- __eColor_mistyrose__ = __niBuildColor(255,228,225,255)__
- __eColor_moccasin__ = __niBuildColor(255,228,181,255)__
- __eColor_navajowhite__ = __niBuildColor(255,222,173,255)__
- __eColor_navy__ = __niBuildColor(0,0,128,255)__
- __eColor_oldlace__ = __niBuildColor(253,245,230,255)__
- __eColor_olive__ = __niBuildColor(128,128,0,255)__
- __eColor_olivedrab__ = __niBuildColor(107,142,35,255)__
- __eColor_orange__ = __niBuildColor(255,165,0,255)__
- __eColor_orangered__ = __niBuildColor(255,69,0,255)__
- __eColor_orchid__ = __niBuildColor(218,112,214,255)__
- __eColor_palegoldenrod__ = __niBuildColor(238,232,170,255)__
- __eColor_palegreen__ = __niBuildColor(152,251,152,255)__
- __eColor_paleturquoise__ = __niBuildColor(175,238,238,255)__
- __eColor_palevioletred__ = __niBuildColor(219,112,147,255)__
- __eColor_papayawhip__ = __niBuildColor(255,239,213,255)__
- __eColor_peachpuff__ = __niBuildColor(255,218,185,255)__
- __eColor_peru__ = __niBuildColor(205,133,63,255)__
- __eColor_pink__ = __niBuildColor(255,192,203,255)__
- __eColor_plum__ = __niBuildColor(221,160,221,255)__
- __eColor_powderblue__ = __niBuildColor(176,224,230,255)__
- __eColor_purple__ = __niBuildColor(128,0,128,255)__
- __eColor_red__ = __niBuildColor(255,0,0,255)__
- __eColor_rosybrown__ = __niBuildColor(188,143,143,255)__
- __eColor_royalblue__ = __niBuildColor(65,105,225,255)__
- __eColor_saddlebrown__ = __niBuildColor(139,69,19,255)__
- __eColor_salmon__ = __niBuildColor(250,128,114,255)__
- __eColor_sandybrown__ = __niBuildColor(244,164,96,255)__
- __eColor_seagreen__ = __niBuildColor(46,139,87,255)__
- __eColor_seashell__ = __niBuildColor(255,245,238,255)__
- __eColor_sienna__ = __niBuildColor(160,82,45,255)__
- __eColor_silver__ = __niBuildColor(192,192,192,255)__
- __eColor_skyblue__ = __niBuildColor(135,206,235,255)__
- __eColor_slateblue__ = __niBuildColor(106,90,205,255)__
- __eColor_slategray__ = __niBuildColor(112,128,144,255)__
- __eColor_slategrey__ = __niBuildColor(112,128,144,255)__
- __eColor_snow__ = __niBuildColor(255,250,250,255)__
- __eColor_springgreen__ = __niBuildColor(0,255,127,255)__
- __eColor_steelblue__ = __niBuildColor(70,130,180,255)__
- __eColor_tan__ = __niBuildColor(210,180,140,255)__
- __eColor_teal__ = __niBuildColor(0,128,128,255)__
- __eColor_thistle__ = __niBuildColor(216,191,216,255)__
- __eColor_tomato__ = __niBuildColor(255,99,71,255)__
- __eColor_turquoise__ = __niBuildColor(64,224,208,255)__
- __eColor_violet__ = __niBuildColor(238,130,238,255)__
- __eColor_wheat__ = __niBuildColor(245,222,179,255)__
- __eColor_white__ = __niBuildColor(255,255,255,255)__
- __eColor_whitesmoke__ = __niBuildColor(245,245,245,255)__
- __eColor_yellow__ = __niBuildColor(255,255,0,255)__
- __eColor_yellowgreen__ = __niBuildColor(154,205,50,255)__
- __eColor_zzzzzzzzzzz__ = __niBuildColor(0,0,0,0)__
- __eColor_zzzz__ = __niBuildColor(0,0,0,0)__

## variable ni::kcolXYZRef2D65

## variable ni::kvColorLuminanceR21G71B07

## variable ni::kvColorLuminanceR27G67B06

## enum ni::eColorSpace
Color spaces 

### Values:
- __eColorSpace_RGB__ = __0__: RGB color space 
- __eColorSpace_CMY__ = __1__: CMY color space 
- __eColorSpace_CMYK__ = __2__: CMYK color space 
- __eColorSpace_HSV__ = __3__: HSV color space 
- __eColorSpace_HSL__ = __4__: HSL color space 
- __eColorSpace_XYZ__ = __5__: XYZ color space 
- __eColorSpace_Yxy__ = __6__: Yxy color space 
- __eColorSpace_HunterLab__ = __7__: Hunter lab color space 
- __eColorSpace_CIELab__ = __8__: CIE Lab color space 
- __eColorSpace_CIELCH__ = __9__: CIE LCH color space 
- __eColorSpace_CIELuv__ = __10__: CIE Luv color space 
- __eColorSpace_YIQ__ = __11__: YIQ color space (NTSC/USA TV). 
- __eColorSpace_YUV__ = __12__: YUV color space (PAL/Europe TV). 
- __eColorSpace_YCbCr__ = __13__: YCbCr color space. 
- __eColorSpace_YPbPr__ = __14__: YPbPr color space (HDTV). 
- __eColorSpace_YCoCg__ = __15__: YCoCg color space (H264 & AVT). 
- __eColorSpace_Last__ = __16__: \internal 

## variable ni::kMaxVertexSize

## enum ni::eFVF
FVF components 

### Values:
- __eFVF_Position__ = __0x00000002__: 3D Position (float3). 
- __eFVF_PositionB1__ = __0x00000006__: 3D Position (float3), and one weight (float1). 
- __eFVF_PositionB2__ = __0x00000008__: 3D Position (float3), and two weights (float2). 
- __eFVF_PositionB3__ = __0x0000000a__: 3D Position (float3), and three weights (float3). 
- __eFVF_PositionB4__ = __0x0000000c__: 3D Position (float3), and four weights (float4). 
- __eFVF_Normal__ = __0x00000010__: 3D Normal (float3). 
- __eFVF_PointSize__ = __0x00000020__: Point size (float). 
- __eFVF_ColorA__ = __0x00000040__: ColorA (ULColor). 
- __eFVF_Reserved1__ = __0x00000080__: Reserved (was ColorB). 
- __eFVF_Tex1__ = __0x00000100__: First texture coordinate (index 0). 
- __eFVF_Tex2__ = __0x00000200__: Second texture coordinate (index 1). 
- __eFVF_Tex3__ = __0x00000300__: Third texture coordinate (index 2). 
- __eFVF_Tex4__ = __0x00000400__: Fourth texture coordinate (index 3). 
- __eFVF_Tex5__ = __0x00000500__: Fifth texture coordinate (index 4). 
- __eFVF_Tex6__ = __0x00000600__: Sixth texture coordinate (index 5). 
- __eFVF_Tex7__ = __0x00000700__: Seventh texture coordinate (index 6). 
- __eFVF_Tex8__ = __0x00000800__: Eigth texture coordinate (index 7). 
- __eFVF_Indices__ = __0x00001000__: Indices (ULColor). 

## variable ni::knFVFTexCountMask

## variable ni::knFVFTexCountShift

## enum ni::eVertexFormat


### Values:
- __eVertexFormat_P__ = __eFVF_Position__
- __eVertexFormat_PA__ = __eFVF_Position|eFVF_ColorA__
- __eVertexFormat_PN__ = __eFVF_Position|eFVF_Normal__
- __eVertexFormat_PNA__ = __eFVF_Position|eFVF_Normal|eFVF_ColorA__
- __eVertexFormat_PNT1__ = __eFVF_Position|eFVF_Normal|eFVF_Tex1__
- __eVertexFormat_PNAT1__ = __eFVF_Position|eFVF_Normal|eFVF_ColorA|eFVF_Tex1__
- __eVertexFormat_PNT2__ = __eFVF_Position|eFVF_Normal|eFVF_Tex2__
- __eVertexFormat_PNAT2__ = __eFVF_Position|eFVF_Normal|eFVF_ColorA|eFVF_Tex2__
- __eVertexFormat_PB4INT1__ = __eFVF_PositionB4|eFVF_Indices|eFVF_Normal|eFVF_Tex1__
- __eVertexFormat_PB4INAT1__ = __eFVF_PositionB4|eFVF_Indices|eFVF_Normal|eFVF_ColorA|eFVF_Tex1__

## enum ni::eVertexStreamIndex


### Values:
- __eVertexStreamIndex_Position__ = __0__
- __eVertexStreamIndex_Weights__ = __11__
- __eVertexStreamIndex_Indices__ = __12__
- __eVertexStreamIndex_Normal__ = __9__
- __eVertexStreamIndex_ColorA__ = __10__
- __eVertexStreamIndex_Tex1__ = __1__
- __eVertexStreamIndex_Tex2__ = __2__
- __eVertexStreamIndex_Tex3__ = __3__
- __eVertexStreamIndex_Tex4__ = __4__
- __eVertexStreamIndex_Tex5__ = __5__
- __eVertexStreamIndex_Tex6__ = __6__
- __eVertexStreamIndex_Tex7__ = __7__
- __eVertexStreamIndex_Tex8__ = __8__

## variable ni::kMaxVertexSize

## enum ni::eGraphicsCaps
Graphics capabilites. 

### Values:
- __eGraphicsCaps_NumTextureUnits__ = __0__: Number of texture units. 
- __eGraphicsCaps_Resize__ = __1__: Return eTrue if the renderer support run-time window resize. 
- __eGraphicsCaps_MultiContext__ = __2__: Return eTrue if the renderer support the creation of more than one rendering context. 
- __eGraphicsCaps_Texture2DMaxSize__ = __3__: Maximum 2d texture size supported. Return 0 if textures are not supported. 
- __eGraphicsCaps_TextureCubeMaxSize__ = __4__: Maximum cube texture size supported. Return 0 if cube maps are not supported. 
- __eGraphicsCaps_Texture3DMaxSize__ = __5__: Maximum 3d texture size supported. . Return 0 if 3d textures are not supported. 
- __eGraphicsCaps_NumRenderTargetTextures__ = __6__: Return the number of simultaneous render target textures supported. 
- __eGraphicsCaps_DepthStencilTexture__ = __7__: Return eTrue if the renderer supports depth stencil as texture. 
- __eGraphicsCaps_StencilTwoSideded__ = __8__: Return eTrue if the renderer supports two sided stencil. 
- __eGraphicsCaps_StencilWrap__ = __9__: Return eTrue if the renderer supports Inc/Decr wrap stencil operation. 
- __eGraphicsCaps_OcclusionQueries__ = __10__: Return eTrue if the renderer supports occlusion queries. 
- __eGraphicsCaps_MaxPointSize__ = __11__: Return the maximum point size. (tF32) 
- __eGraphicsCaps_HardwareInstancing__ = __12__: Return wheter or not the hardware supports instancing. 
- __eGraphicsCaps_ScissorTest__ = __13__: Return wheter or not the hardware scissor test is supported. 
- __eGraphicsCaps_MaxVertexIndex__ = __14__: The maximum vertex index that can be used in an index array. 
- __eGraphicsCaps_OverlayTexture__ = __15__: Overlay textures supported. 
- __eGraphicsCaps_OrthoProjectionOffset__ = __16__: Get the orthogonal screen projection offset in screen pixel unit. (float) 
- __eGraphicsCaps_BlitBackBuffer__ = __17__: Whether we can blit the backbuffer to a texture with BlitTextureToTexture. 
- __eGraphicsCaps_Last__ = __18__: \internal 

## enum ni::eClearBuffersFlags
Buffer clearing flags. 

### Values:
- __eClearBuffersFlags_Color__ = __0x1__: Clear color buffer. 
- __eClearBuffersFlags_Depth__ = __0x2__: Clear depth buffer. 
- __eClearBuffersFlags_Stencil__ = __0x4__: Clear stencil buffer. 
- __eClearBuffersFlags_ColorDepth__ = __eClearBuffersFlags_Color|eClearBuffersFlags_Depth__: Clear the color and depth buffers. 
- __eClearBuffersFlags_ColorStencil__ = __eClearBuffersFlags_Color|eClearBuffersFlags_Stencil__: Clear the color and stencil buffers. 
- __eClearBuffersFlags_DepthStencil__ = __eClearBuffersFlags_Depth|eClearBuffersFlags_Depth__: Clear the depth and stencil buffers. 
- __eClearBuffersFlags_ColorDepthStencil__ = __eClearBuffersFlags_Color|eClearBuffersFlags_Depth|eClearBuffersFlags_Stencil__: Clear the color, depth and stencil buffers. 

## enum ni::eArrayUsage
Array usage. 

### Values:
- __eArrayUsage_Dynamic__ = __0__: Dynamic array, write only. 
- __eArrayUsage_DynamicReadWrite__ = __1__: Dynamic array, Read/Write. 
- __eArrayUsage_Static__ = __2__: Static array, write only. 
- __eArrayUsage_SystemMemory__ = __3__: System memory array. 

## enum ni::eLock
Lock. 

### Values:
- __eLock_Normal__ = __0__: Normal behavior. 
- __eLock_Discard__ = __niBit(0)__: The application overwrites (with a write-only operation) every location within the region being locked. This is a valid option when using dynamic textures, dynamic vertex arrays, and dynamic index arrays.  For vertex and index arrays, the application discards the entire buffer. A pointer to a new memory area is returned so that the dynamic memory access (DMA) and rendering from the previous area do not stall.  For textures, the application overwrites (with a write-only operation) every location within the region being locked. 
- __eLock_NoOverwrite__ = __niBit(1)__: The application promises not to overwrite any data in the vertex and index arrays. Specifying this flag allows the driver to return immediately and continue rendering, using this array. If this flag is not used, the driver must finish rendering before returning from locking. 
- __eLock_ReadOnly__ = __niBit(2)__: The application will not write to the buffer. 
- __eLock_ReadOnlyPosition__ = __eLock_ReadOnly|niBit(3)__: The application will read only the positions in the buffer. 

## enum ni::eShaderCompilerFlags
Shader compiler flags. 

### Values:
- __eShaderCompilerFlags_Debug__ = __niBit(0)__: Insert debug filename, line numbers, and type and symbol information during shader compile. 
- __eShaderCompilerFlags_SkipValidation__ = __niBit(1)__: Do not validate the generated code against known capabilities and constraints. This option is recommended only when compiling shaders that are known to work (that is, shaders that have compiled before without this option). Shaders are always validated by the runtime before they are set to the device. 
- __eShaderCompilerFlags_SkipOptimization__ = __niBit(2)__: Instruct the compiler to skip optimization steps during code generation. Unless you are trying to isolate a problem in your code and you suspect the compiler, using this option is not recommended. 
- __eShaderCompilerFlags_PackMatrixRowMajor__ = __niBit(3)__: Unless explicitly specified, matrices will be packed in row-major order (each vector will be in a single row) when passed to or from the shader. 
- __eShaderCompilerFlags_PackMatrixColumnMajor__ = __niBit(4)__: Unless explicitly specified, matrices will be packed in column-major order (each vector will be in a single column) when passed to and from the shader. This is generally more efficient because it allows vector-matrix multiplication to be performed using a series of dot products. 
- __eShaderCompilerFlags_PartialPrecision__ = __niBit(5)__: Force all computations in the resulting shader to occur at partial precision. This may result in faster evaluation of shaders on some hardware. 
- __eShaderCompilerFlags_AvoidFlowControl__ = __niBit(6)__: This is a hint to the compiler to avoid using flow-control instructions. 
- __eShaderCompilerFlags_PreferFlowControl__ = __niBit(7)__: This is a hint to the compiler to prefer using flow-control instructions. 
- __eShaderCompilerFlags_Save__ = __niBit(8)__: This will instruct the compiler to keep the data necessary to serialize the shader to a file. 
- __eShaderCompilerFlags_KeepCode__ = __niBit(9)__: This will instruct the driver to keep a copy of the source code used to compile the shader. That can be retrieved with ni::iShader::GetCode(). 
- __eShaderCompilerFlags_DebugLog__ = __niBit(10)__: This will instruct the driver to log the macros and other debugging informations when compiling. 

## enum ni::eGraphicsPrimitiveType
Graphics primitive types 

### Values:
- __eGraphicsPrimitiveType_PointList__ = __0__: List of isolated points. 
- __eGraphicsPrimitiveType_LineList__ = __1__: List of isolated straight line segments. 
- __eGraphicsPrimitiveType_LineStrip__ = __2__: List of vertices as a single polyline. 
- __eGraphicsPrimitiveType_TriangleList__ = __3__: List of vertices as a sequence of isolated triangles. Each group of three vertices defines a separate triangle. Culling is affected by the current culling rendering parameter. 
- __eGraphicsPrimitiveType_TriangleStrip__ = __4__: List of vertices as a triangle strip. The culling flag is automatically flipped on even-numbered triangles. 
- __eGraphicsPrimitiveType_LineListAdjacency__ = __5__: Line list with adjacency information. 
- __eGraphicsPrimitiveType_LineStripAdjacency__ = __6__: Line strip with adjacency information. 
- __eGraphicsPrimitiveType_TriangleListAdjacency__ = __7__: Triangle list with adjacency information. 
- __eGraphicsPrimitiveType_TriangleStripAdjacency__ = __8__: Triangle strip with adjacency information. 
- __eGraphicsPrimitiveType_BlitList__ = __9__: List of screen aligned rectangle blitting. 
- __eGraphicsPrimitiveType_Last__ = __10__: \internal 

## enum ni::eGraphicsDriverImplFlags
Graphics driver implementation details. 

### Values:
- __eGraphicsDriverImplFlags_VertexArrayObject__ = __niBit(0)__: Vertex array. 
- __eGraphicsDriverImplFlags_IndexArrayObject__ = __niBit(1)__: Index array. 
- __eGraphicsDriverImplFlags_ShaderConstantsObject__ = __niBit(2)__: Shader constants. 
- __eGraphicsDriverImplFlags_SystemMemoryTexture__ = __niBit(3)__: Can render using system memory textures. 
- __eGraphicsDriverImplFlags_CompileSamplerStates__ = __niBit(4)__: Compile sampler states. 
- __eGraphicsDriverImplFlags_CompileDepthStencilStates__ = __niBit(5)__: Compile DepthStencil states. 
- __eGraphicsDriverImplFlags_CompileRasterizerStates__ = __niBit(6)__: Compile rasterizer states. 

## enum ni::eSamplerFilter
Sampler filter. 

### Values:
- __eSamplerFilter_Smooth__ = __0__: Default, smooth filtering. 
- __eSamplerFilter_Sharp__ = __1__: Sharper filtering. Anisotropic filtering and/or a negative lod bias. 
- __eSamplerFilter_Point__ = __2__: Point filtering. 
- __eSamplerFilter_SharpPoint__ = __3__: Sharper point filtering. Anisotropic filtering and/or a negative lod bias. 
- __eSamplerFilter_Last__ = __4__: \internal 

## enum ni::eSamplerWrap
Texture wrapping modes. 

### Values:
- __eSamplerWrap_Repeat__ = __0__: The texture is repeated along the axis. default. 
- __eSamplerWrap_Clamp__ = __1__: The texture is clamped at the end and the rest of the polygon is filled with the content of the texture edge. 
- __eSamplerWrap_Mirror__ = __2__: Similar to eSamplerWrap_Repeat, except that the texture is flipped at every integer junction. For u values between 0 and 1, for example, the texture is addressed normally; between 1 and 2, the texture is flipped (mirrored); between 2 and 3, the texture is normal again, and so on. 
- __eSamplerWrap_Border__ = __3__: Border mode, the border color is used when outside of 0,1 range. 
- __eSamplerWrap_Last__ = __4__: \internal 

## enum ni::eGraphicsCompare
Graphics compare functions. 

### Values:
- __eGraphicsCompare_Never__ = __0__: Always fail the test. 
- __eGraphicsCompare_Equal__ = __1__: Accept the new pixel if its value equals the value of the current pixel. 
- __eGraphicsCompare_NotEqual__ = __2__: Accept the new pixel if its value does not equal the value of the current pixel. 
- __eGraphicsCompare_Less__ = __3__: Accept the new pixel if its value is less than the value of the current pixel. 
- __eGraphicsCompare_LessEqual__ = __4__: Accept the new pixel if its value is less than or equal to the value of the current pixel. 
- __eGraphicsCompare_Greater__ = __5__: Accept the new pixel if its value is greater than the value of the current pixel. 
- __eGraphicsCompare_GreaterEqual__ = __6__: Accept the new pixel if its value is greater than or equal to the value of the current pixel. 
- __eGraphicsCompare_Always__ = __7__: Always pass the test. 
- __eGraphicsCompare_Last__ = __8__: \internal 

## enum ni::eStencilMode
Stencil mode. 

### Values:
- __eStencilMode_None__ = __0__: Disable the stencil. 
- __eStencilMode_OneSided__ = __1__: One sided stencil. 
- __eStencilMode_TwoSided__ = __2__: Two sided stencil. 
- __eStencilMode_Last__ = __3__: \internal 

## enum ni::eStencilOp
Stencil operations. 

### Values:
- __eStencilOp_Keep__ = __0__: Do not update the entry in the stencil buffer. This is the default value. 
- __eStencilOp_Zero__ = __1__: Set the stencil-buffer entry to 0. 
- __eStencilOp_Replace__ = __2__: Replace the stencil-buffer entry with a reference value. 
- __eStencilOp_IncrWrap__ = __3__: Increment the stencil-buffer entry, wrapping to zero if the new value exceeds the maximum value. 
- __eStencilOp_DecrWrap__ = __4__: Decrement the stencil-buffer entry, wrapping to the maximum value if the new value is less than zero. 
- __eStencilOp_IncrSat__ = __5__: Increment the stencil-buffer entry, clamping to the maximum value. 
- __eStencilOp_DecrSat__ = __6__: Increment the stencil-buffer entry, clamping to zero. 
- __eStencilOp_Invert__ = __7__: Invert the bits in the stencil-buffer entry. 
- __eStencilOp_Last__ = __8__: \internal 

## enum ni::eBlendMode
Blending mode A*SrcColor + B*DestColor 

### Remarks:
- For material channel zero : SrcColor/Alpha is the channel 0 color, DestColor/Alpha is the color A 
- For material channel > zero : SrcColor/Alpha is the channel n color, DestColor/Alpha is the channel n-1 color 

### Values:
- __eBlendMode_NoBlending__ = __0__: Solid, no blending 
- __eBlendMode_ReplaceAlpha__ = __1__: Means that the current alpha will be replaced by the current stage's alpha. 
- __eBlendMode_Additive__ = __2__: Additive blending 
- __eBlendMode_Modulate__ = __3__: Modulate 
- __eBlendMode_Modulate2x__ = __4__: Modulate 2x 
- __eBlendMode_Translucent__ = __5__: Translucent blending 
- __eBlendMode_TranslucentInvAlpha__ = __6__: Translucent blending with inverted alpha 
- __eBlendMode_TintedGlass__ = __7__: Tinted blending 
- __eBlendMode_PreMulAlpha__ = __8__: Premultiplied alpha light blending. 
- __eBlendMode_ModulateReplaceAlpha__ = __9__: Modulate RGB, replace alpha 
- __eBlendMode_Modulate2xReplaceAlpha__ = __10__: Modulate RGB 2x, replace alpha 
- __eBlendMode_Last__ = __11__: \internal 

## enum ni::eCullingMode
Culling mode 

### Values:
- __eCullingMode_None__ = __0__: Do not cull back faces. 
- __eCullingMode_CW__ = __1__: Cull back faces with clockwise vertices. 
- __eCullingMode_CCW__ = __2__: Cull back faces with counter clockwise vertices (default). 
- __eCullingMode_Last__ = __3__: \internal 

## enum ni::eColorWriteMask
Color write mask. 

### Values:
- __eColorWriteMask_None__ = __0x0__: Disable writting in the color buffer. 
- __eColorWriteMask_Alpha__ = __0x1__: Write only in the alpha buffer. 
- __eColorWriteMask_Red__ = __0x2__: Write only in the red channel of the color buffer. 
- __eColorWriteMask_Green__ = __0x4__: Write only in the green channel of the color buffer. 
- __eColorWriteMask_Blue__ = __0x8__: Write only in the blue channel of the color buffer. 
- __eColorWriteMask_RGB__ = __eColorWriteMask_Red|eColorWriteMask_Green|eColorWriteMask_Blue__: Write only in the rgb buffer. 
- __eColorWriteMask_All__ = __eColorWriteMask_RGB|eColorWriteMask_Alpha__: Normal, write in all channels. 

## enum ni::eGraphicsDisplayFlags
Graphics display flags 

### Values:
- __eGraphicsDisplayFlags_Skip__ = __niBit(0)__: Flush all rendering but do not show the back buffer. 
- __eGraphicsDisplayFlags_DoNotWait__ = __niBit(1)__
- __eGraphicsDisplayFlags_LinearContent__ = __niBit(2)__
- __eGraphicsDisplayFlags_Transparent__ = __niBit(3)__
- __eGraphicsDisplayFlags_Translucent__ = __niBit(4)__

## enum ni::eCompiledStates
Graphics built-in compiled states. \see GetCompiledStates 

### Values:
- __eCompiledStates_Invalid__ = __0__
- __eCompiledStates_RS_ColorWriteNone__ = __1__
- __eCompiledStates_RS_Filled__ = __2__
- __eCompiledStates_RS_Wireframe__ = __3__
- __eCompiledStates_RS_FilledScissor__ = __4__
- __eCompiledStates_RS_WireframeScissor__ = __5__
- __eCompiledStates_RS_NoCullingColorWriteNone__ = __6__
- __eCompiledStates_RS_NoCullingFilled__ = __7__
- __eCompiledStates_RS_NoCullingWireframe__ = __8__
- __eCompiledStates_RS_NoCullingFilledScissor__ = __9__
- __eCompiledStates_RS_NoCullingWireframeScissor__ = __10__
- __eCompiledStates_RS_CWCullingColorWriteNone__ = __11__
- __eCompiledStates_RS_CWCullingFilled__ = __12__
- __eCompiledStates_RS_CWCullingWireframe__ = __13__
- __eCompiledStates_RS_CWCullingFilledScissor__ = __14__
- __eCompiledStates_RS_CWCullingWireframeScissor__ = __15__
- __eCompiledStates_DS_NoDepthTest__ = __101__
- __eCompiledStates_DS_DepthTestAndWrite__ = __102__
- __eCompiledStates_DS_DepthTestOnly__ = __103__
- __eCompiledStates_SS_PointRepeat__ = __201__
- __eCompiledStates_SS_PointClamp__ = __202__
- __eCompiledStates_SS_PointMirror__ = __203__
- __eCompiledStates_SS_SmoothRepeat__ = __204__
- __eCompiledStates_SS_SmoothClamp__ = __205__
- __eCompiledStates_SS_SmoothMirror__ = __206__
- __eCompiledStates_SS_SharpRepeat__ = __207__
- __eCompiledStates_SS_SharpClamp__ = __208__
- __eCompiledStates_SS_SharpMirror__ = __209__
- __eCompiledStates_SS_SharpPointRepeat__ = __210__
- __eCompiledStates_SS_SharpPointClamp__ = __211__
- __eCompiledStates_SS_SharpPointMirror__ = __212__
- __eCompiledStates_Driver__ = __1000__: Driver compiled 

## enum ni::eGraphicsCaps
Graphics capabilites. 

### Values:
- __eGraphicsCaps_NumTextureUnits__ = __0__: Number of texture units. 
- __eGraphicsCaps_Resize__ = __1__: Return eTrue if the renderer support run-time window resize. 
- __eGraphicsCaps_MultiContext__ = __2__: Return eTrue if the renderer support the creation of more than one rendering context. 
- __eGraphicsCaps_Texture2DMaxSize__ = __3__: Maximum 2d texture size supported. Return 0 if textures are not supported. 
- __eGraphicsCaps_TextureCubeMaxSize__ = __4__: Maximum cube texture size supported. Return 0 if cube maps are not supported. 
- __eGraphicsCaps_Texture3DMaxSize__ = __5__: Maximum 3d texture size supported. . Return 0 if 3d textures are not supported. 
- __eGraphicsCaps_NumRenderTargetTextures__ = __6__: Return the number of simultaneous render target textures supported. 
- __eGraphicsCaps_DepthStencilTexture__ = __7__: Return eTrue if the renderer supports depth stencil as texture. 
- __eGraphicsCaps_StencilTwoSideded__ = __8__: Return eTrue if the renderer supports two sided stencil. 
- __eGraphicsCaps_StencilWrap__ = __9__: Return eTrue if the renderer supports Inc/Decr wrap stencil operation. 
- __eGraphicsCaps_OcclusionQueries__ = __10__: Return eTrue if the renderer supports occlusion queries. 
- __eGraphicsCaps_MaxPointSize__ = __11__: Return the maximum point size. (tF32) 
- __eGraphicsCaps_HardwareInstancing__ = __12__: Return wheter or not the hardware supports instancing. 
- __eGraphicsCaps_ScissorTest__ = __13__: Return wheter or not the hardware scissor test is supported. 
- __eGraphicsCaps_MaxVertexIndex__ = __14__: The maximum vertex index that can be used in an index array. 
- __eGraphicsCaps_OverlayTexture__ = __15__: Overlay textures supported. 
- __eGraphicsCaps_OrthoProjectionOffset__ = __16__: Get the orthogonal screen projection offset in screen pixel unit. (float) 
- __eGraphicsCaps_BlitBackBuffer__ = __17__: Whether we can blit the backbuffer to a texture with BlitTextureToTexture. 
- __eGraphicsCaps_Last__ = __18__: \internal 

## interface ni::iBitmap2D
2D Bitmap interface. 

### Parents:
- iBitmapBase

### Methods:
- __iBitmap2D::SetMemoryAddress__(_tPtr_ apAddr, _tBool_ abFreeData, _tU32_ anPitch) -> _tBool_: Set the memory address. 
- __iBitmap2D::GetPitch__() -> _tU32_: Get the number of bytes per line. 
- __iBitmap2D::GetData__() -> _tPtr_: Get the data pointer. 
- __iBitmap2D::GetSize__() -> _tU32_: Get the size in bytes. 
- __iBitmap2D::CreateResized__(_tI32_ nW, _tI32_ nH) -> _iBitmap2D\*_: Create a resized copy of this bitmap. 
- __iBitmap2D::CreateResizedEx__(_tI32_ nW, _tI32_ nH, _tBool_ abPreserveMipMaps) -> _iBitmap2D\*_: Create a resized copy of this bitmap. 
- __iBitmap2D::CreateCubeBitmap__(_tU32_ anWidth, _const sVec2i&_ avPX, _ePixelFormatBlit_ aBlitPX, _const sVec2i&_ avNX, _ePixelFormatBlit_ aBlitNX, _const sVec2i&_ avPY, _ePixelFormatBlit_ aBlitPY, _const sVec2i&_ avNY, _ePixelFormatBlit_ aBlitNY, _const sVec2i&_ avPZ, _ePixelFormatBlit_ aBlitPZ, _const sVec2i&_ avNZ, _ePixelFormatBlit_ aBlitNZ) -> _iBitmapCube\*_: Create a cube bitmap from the specified 6 rectangles. 
- __iBitmap2D::CreateCubeBitmapCross__() -> _iBitmapCube\*_: Create a cube bitmap from a vertical or horizontal cross unfolded cube. 
- __iBitmap2D::BeginUnpackPixels__() -> _tBool_: Begin unpacking pixels. 
- __iBitmap2D::EndUnpackPixels__() -> _void_: End unpacking pixels. 
- __iBitmap2D::GetMipMap__(_tU32_ ulIdx) -> _iBitmap2D\*_: Get the mipmap at the specified index. 
- __iBitmap2D::GetLevel__(_tU32_ anIndex) -> _iBitmap2D\*_: Get the bitmap at the specified level. 
- __iBitmap2D::Blit__(_const iBitmap2D\*_ src, _tI32_ xs, _tI32_ ys, _tI32_ xd, _tI32_ yd, _tI32_ w, _tI32_ h, _ePixelFormatBlit_ eBlit) -> _tBool_: Blit a bitmap in this bitmap. 
- __iBitmap2D::BlitStretch__(_const iBitmap2D\*_ src, _tI32_ xs, _tI32_ ys, _tI32_ xd, _tI32_ yd, _tI32_ ws, _tI32_ hs, _tI32_ wd, _tI32_ hd) -> _tBool_: Blit stretch a bitmap in this bitmap. 
- __iBitmap2D::BlitAlpha__(_const iBitmap2D\*_ src, _tI32_ xs, _tI32_ ys, _tI32_ xd, _tI32_ yd, _tI32_ w, _tI32_ h, _ePixelFormatBlit_ eBlit, _const sColor4f&_ acolSource, _const sColor4f&_ acolDest, _eBlendMode_ aBlendMode) -> _tBool_: Blit, with alpha blending, a bitmap in this bitmap. 
- __iBitmap2D::BlitAlphaStretch__(_const iBitmap2D\*_ src, _tI32_ xs, _tI32_ ys, _tI32_ xd, _tI32_ yd, _tI32_ ws, _tI32_ hs, _tI32_ wd, _tI32_ hd, _const sColor4f&_ acolSource, _const sColor4f&_ acolDest, _eBlendMode_ aBlendMode) -> _tBool_: Blit stretch, with alpha blending, a bitmap in this bitmap. 
- __iBitmap2D::PutPixel__(_tI32_ x, _tI32_ y, _tPtr_ col) -> _void_: Put a pixel at the specified position. 
- __iBitmap2D::GetPixel__(_tI32_ x, _tI32_ y, _tPtr_ pOut) -> _tPtr_: Get a pixel at the specified position. 
- __iBitmap2D::Clear__(_tPtr_ pColor) -> _void_: Clear the bitmap 
- __iBitmap2D::ClearRect__(_const sRecti&_ aRect, _tPtr_ pColor) -> _void_: Clear the bitmap 
- __iBitmap2D::PutPixelf__(_tI32_ x, _tI32_ y, _const sColor4f&_ avCol) -> _void_: Put a pixel at the specified position. 
- __iBitmap2D::GetPixelf__(_tI32_ x, _tI32_ y) -> _sColor4f_: Get a pixel at the specified position. 
- __iBitmap2D::Clearf__(_const sColor4f&_ avCol) -> _void_: Clear the bitmap. 
- __iBitmap2D::ClearRectf__(_const sRecti&_ aRect, _const sColor4f&_ avCol) -> _void_: Clear the bitmap. 

## interface ni::iBitmap2D
2D Bitmap interface. 

### Parents:
- iBitmapBase

### Methods:
- __iBitmap2D::SetMemoryAddress__(_tPtr_ apAddr, _tBool_ abFreeData, _tU32_ anPitch) -> _tBool_: Set the memory address. 
- __iBitmap2D::GetPitch__() -> _tU32_: Get the number of bytes per line. 
- __iBitmap2D::GetData__() -> _tPtr_: Get the data pointer. 
- __iBitmap2D::GetSize__() -> _tU32_: Get the size in bytes. 
- __iBitmap2D::CreateResized__(_tI32_ nW, _tI32_ nH) -> _iBitmap2D\*_: Create a resized copy of this bitmap. 
- __iBitmap2D::CreateResizedEx__(_tI32_ nW, _tI32_ nH, _tBool_ abPreserveMipMaps) -> _iBitmap2D\*_: Create a resized copy of this bitmap. 
- __iBitmap2D::CreateCubeBitmap__(_tU32_ anWidth, _const sVec2i&_ avPX, _ePixelFormatBlit_ aBlitPX, _const sVec2i&_ avNX, _ePixelFormatBlit_ aBlitNX, _const sVec2i&_ avPY, _ePixelFormatBlit_ aBlitPY, _const sVec2i&_ avNY, _ePixelFormatBlit_ aBlitNY, _const sVec2i&_ avPZ, _ePixelFormatBlit_ aBlitPZ, _const sVec2i&_ avNZ, _ePixelFormatBlit_ aBlitNZ) -> _iBitmapCube\*_: Create a cube bitmap from the specified 6 rectangles. 
- __iBitmap2D::CreateCubeBitmapCross__() -> _iBitmapCube\*_: Create a cube bitmap from a vertical or horizontal cross unfolded cube. 
- __iBitmap2D::BeginUnpackPixels__() -> _tBool_: Begin unpacking pixels. 
- __iBitmap2D::EndUnpackPixels__() -> _void_: End unpacking pixels. 
- __iBitmap2D::GetMipMap__(_tU32_ ulIdx) -> _iBitmap2D\*_: Get the mipmap at the specified index. 
- __iBitmap2D::GetLevel__(_tU32_ anIndex) -> _iBitmap2D\*_: Get the bitmap at the specified level. 
- __iBitmap2D::Blit__(_const iBitmap2D\*_ src, _tI32_ xs, _tI32_ ys, _tI32_ xd, _tI32_ yd, _tI32_ w, _tI32_ h, _ePixelFormatBlit_ eBlit) -> _tBool_: Blit a bitmap in this bitmap. 
- __iBitmap2D::BlitStretch__(_const iBitmap2D\*_ src, _tI32_ xs, _tI32_ ys, _tI32_ xd, _tI32_ yd, _tI32_ ws, _tI32_ hs, _tI32_ wd, _tI32_ hd) -> _tBool_: Blit stretch a bitmap in this bitmap. 
- __iBitmap2D::BlitAlpha__(_const iBitmap2D\*_ src, _tI32_ xs, _tI32_ ys, _tI32_ xd, _tI32_ yd, _tI32_ w, _tI32_ h, _ePixelFormatBlit_ eBlit, _const sColor4f&_ acolSource, _const sColor4f&_ acolDest, _eBlendMode_ aBlendMode) -> _tBool_: Blit, with alpha blending, a bitmap in this bitmap. 
- __iBitmap2D::BlitAlphaStretch__(_const iBitmap2D\*_ src, _tI32_ xs, _tI32_ ys, _tI32_ xd, _tI32_ yd, _tI32_ ws, _tI32_ hs, _tI32_ wd, _tI32_ hd, _const sColor4f&_ acolSource, _const sColor4f&_ acolDest, _eBlendMode_ aBlendMode) -> _tBool_: Blit stretch, with alpha blending, a bitmap in this bitmap. 
- __iBitmap2D::PutPixel__(_tI32_ x, _tI32_ y, _tPtr_ col) -> _void_: Put a pixel at the specified position. 
- __iBitmap2D::GetPixel__(_tI32_ x, _tI32_ y, _tPtr_ pOut) -> _tPtr_: Get a pixel at the specified position. 
- __iBitmap2D::Clear__(_tPtr_ pColor) -> _void_: Clear the bitmap 
- __iBitmap2D::ClearRect__(_const sRecti&_ aRect, _tPtr_ pColor) -> _void_: Clear the bitmap 
- __iBitmap2D::PutPixelf__(_tI32_ x, _tI32_ y, _const sColor4f&_ avCol) -> _void_: Put a pixel at the specified position. 
- __iBitmap2D::GetPixelf__(_tI32_ x, _tI32_ y) -> _sColor4f_: Get a pixel at the specified position. 
- __iBitmap2D::Clearf__(_const sColor4f&_ avCol) -> _void_: Clear the bitmap. 
- __iBitmap2D::ClearRectf__(_const sRecti&_ aRect, _const sColor4f&_ avCol) -> _void_: Clear the bitmap. 

## interface ni::iBitmap3D
3D Bitmap interface. 

### Parents:
- iBitmapBase

### Methods:
- __iBitmap3D::SetMemoryAddress__(_tPtr_ apAddr, _tBool_ abFreeData, _tU32_ anRowPitch, _tU32_ anSlicePitch) -> _tBool_: Set the memory address. 
- __iBitmap3D::GetRowPitch__() -> _tU32_: Get the number of bytes per row 
- __iBitmap3D::GetSlicePitch__() -> _tU32_: Get the number of bytes per slice 
- __iBitmap3D::GetSize__() -> _tU32_: Get the size in bytes. 
- __iBitmap3D::GetData__() -> _tPtr_: Get the data pointer. 
- __iBitmap3D::GetSlicePtr__(_tU32_ anSlice) -> _tPtr_: Get the slice data pointer. 
- __iBitmap3D::CreateSliceBitmap__(_tU32_ anSlice) -> _iBitmap2D\*_: Create a 2d bitmap which points to the memory of the specified slice. 
- __iBitmap3D::CreateResized__(_tU32_ anW, _tU32_ anH, _tU32_ anD) -> _iBitmap3D\*_: Create a resized copy of this bitmap. 
- __iBitmap3D::GetMipMap__(_tU32_ ulIdx) -> _iBitmap3D\*_: Get the indicated mip map. 
- __iBitmap3D::GetLevel__(_tU32_ anIndex) -> _iBitmap3D\*_: Get the bitmap at the specified level. 
- __iBitmap3D::BeginUnpackPixels__() -> _tBool_: Begin unpacking pixels. 
- __iBitmap3D::EndUnpackPixels__() -> _void_: End unpacking pixels. 
- __iBitmap3D::Blit__(_const iBitmap3D\*_ apSrc, _const sVec3i&_ avSrcMin, _const sVec3i&_ avDestMin, _const sVec3i&_ avSize) -> _tBool_: Blit a bitmap in this bitmap. 
- __iBitmap3D::PutPixel__(_const sVec3i&_ avPos, _tPtr_ col) -> _void_: Put a pixel at the specified position. 
- __iBitmap3D::GetPixel__(_const sVec3i&_ avPos, _tPtr_ pOut) -> _tPtr_: Get a pixel at the specified position. 
- __iBitmap3D::Clear__(_tPtr_ pColor) -> _void_: Clear the bitmap 
- __iBitmap3D::ClearBox__(_const sVec3i&_ avMin, _const sVec3i&_ avMax, _tPtr_ pColor) -> _void_: Clear the bitmap 
- __iBitmap3D::PutPixelf__(_const sVec3i&_ avPos, _const sColor4f&_ avCol) -> _void_: Put a pixel at the specified position. 
- __iBitmap3D::GetPixelf__(_const sVec3i&_ avPos) -> _sColor4f_: Get a pixel at the specified position. 
- __iBitmap3D::Clearf__(_const sColor4f&_ avCol) -> _void_: Clear the bitmap. 
- __iBitmap3D::ClearBoxf__(_const sVec3i&_ avMin, _const sVec3i&_ avMax, _const sColor4f&_ avCol) -> _void_: Clear the bitmap. 

## interface ni::iBitmap3D
3D Bitmap interface. 

### Parents:
- iBitmapBase

### Methods:
- __iBitmap3D::SetMemoryAddress__(_tPtr_ apAddr, _tBool_ abFreeData, _tU32_ anRowPitch, _tU32_ anSlicePitch) -> _tBool_: Set the memory address. 
- __iBitmap3D::GetRowPitch__() -> _tU32_: Get the number of bytes per row 
- __iBitmap3D::GetSlicePitch__() -> _tU32_: Get the number of bytes per slice 
- __iBitmap3D::GetSize__() -> _tU32_: Get the size in bytes. 
- __iBitmap3D::GetData__() -> _tPtr_: Get the data pointer. 
- __iBitmap3D::GetSlicePtr__(_tU32_ anSlice) -> _tPtr_: Get the slice data pointer. 
- __iBitmap3D::CreateSliceBitmap__(_tU32_ anSlice) -> _iBitmap2D\*_: Create a 2d bitmap which points to the memory of the specified slice. 
- __iBitmap3D::CreateResized__(_tU32_ anW, _tU32_ anH, _tU32_ anD) -> _iBitmap3D\*_: Create a resized copy of this bitmap. 
- __iBitmap3D::GetMipMap__(_tU32_ ulIdx) -> _iBitmap3D\*_: Get the indicated mip map. 
- __iBitmap3D::GetLevel__(_tU32_ anIndex) -> _iBitmap3D\*_: Get the bitmap at the specified level. 
- __iBitmap3D::BeginUnpackPixels__() -> _tBool_: Begin unpacking pixels. 
- __iBitmap3D::EndUnpackPixels__() -> _void_: End unpacking pixels. 
- __iBitmap3D::Blit__(_const iBitmap3D\*_ apSrc, _const sVec3i&_ avSrcMin, _const sVec3i&_ avDestMin, _const sVec3i&_ avSize) -> _tBool_: Blit a bitmap in this bitmap. 
- __iBitmap3D::PutPixel__(_const sVec3i&_ avPos, _tPtr_ col) -> _void_: Put a pixel at the specified position. 
- __iBitmap3D::GetPixel__(_const sVec3i&_ avPos, _tPtr_ pOut) -> _tPtr_: Get a pixel at the specified position. 
- __iBitmap3D::Clear__(_tPtr_ pColor) -> _void_: Clear the bitmap 
- __iBitmap3D::ClearBox__(_const sVec3i&_ avMin, _const sVec3i&_ avMax, _tPtr_ pColor) -> _void_: Clear the bitmap 
- __iBitmap3D::PutPixelf__(_const sVec3i&_ avPos, _const sColor4f&_ avCol) -> _void_: Put a pixel at the specified position. 
- __iBitmap3D::GetPixelf__(_const sVec3i&_ avPos) -> _sColor4f_: Get a pixel at the specified position. 
- __iBitmap3D::Clearf__(_const sColor4f&_ avCol) -> _void_: Clear the bitmap. 
- __iBitmap3D::ClearBoxf__(_const sVec3i&_ avMin, _const sVec3i&_ avMax, _const sColor4f&_ avCol) -> _void_: Clear the bitmap. 

## enum ni::eBitmapType
Bitmap type 

### Values:
- __eBitmapType_2D__ = __0__: 2D Bitmap. 
- __eBitmapType_Cube__ = __1__: Cube Bitmap. Six 2D Bitmaps. 
- __eBitmapType_3D__ = __2__: 3D Bitmap. 

## interface ni::iBitmapFormat
Bitmap format interface. 

### Parents:
- iUnknown

### Methods:
- __iBitmapFormat::Copy__(_const iBitmapFormat\*_ apFormat) -> _tBool_: Copy another bitmap format. 
- __iBitmapFormat::Clone__() -> _iBitmapFormat\*_: Clone the bitmap format. 
- __iBitmapFormat::Reset__() -> _void_: Reset the bitmap format to its default values. 
- __iBitmapFormat::SetType__(_eBitmapType_ aV) -> _void_: Set the bitmap type. (default eBitmapType_2D) 
- __iBitmapFormat::GetType__() -> _eBitmapType_: Get the bitmap type. 
- __iBitmapFormat::SetWidth__(_tU32_ aV) -> _void_: Set the texture width. (default 16) 
- __iBitmapFormat::GetWidth__() -> _tU32_: Get the texture width. (default 16) 
- __iBitmapFormat::SetHeight__(_tU32_ aV) -> _void_: Set the texture height. 
- __iBitmapFormat::GetHeight__() -> _tU32_: Get the texture height. 
- __iBitmapFormat::SetDepth__(_tU32_ aV) -> _void_: Set the texture depth. (default 0) 
- __iBitmapFormat::GetDepth__() -> _tU32_: Get the texture depth. 
- __iBitmapFormat::SetNumMipMaps__(_tU32_ aV) -> _void_: Set the number of mipmaps. (default 0) 
- __iBitmapFormat::GetNumMipMaps__() -> _tU32_: Get the number of mipmaps. 
- __iBitmapFormat::SetPixelFormat__(_iPixelFormat\*_ aV) -> _void_: Set the pixel format. (default R8G8B8A8) 
- __iBitmapFormat::GetPixelFormat__() -> _iPixelFormat\*_: Get the pixel format. 

## interface ni::iBitmapBase
Base bitmap interface. 

### Parents:
- iUnknown

### Methods:
- __iBitmapBase::GetType__() -> _eBitmapType_: Return the bitmap type. 
- __iBitmapBase::GetWidth__() -> _tU32_: Get the texture width. 
- __iBitmapBase::GetHeight__() -> _tU32_: Get the texture height. 
- __iBitmapBase::GetDepth__() -> _tU32_: Get the texture depth. 
- __iBitmapBase::GetPixelFormat__() -> _iPixelFormat\*_: Get the pixel format of the texture. 
- __iBitmapBase::CreateMipMaps__(_tU32_ anNumMipMaps, _tBool_ abCompute) -> _tBool_: Create the mipmaps. 
- __iBitmapBase::RemoveMipMaps__() -> _void_: Remove the mipmaps. 
- __iBitmapBase::GetNumMipMaps__() -> _tU32_: Get the number of mipmaps. 
- __iBitmapBase::Clone__(_ePixelFormatBlit_ eBlit) -> _iBitmapBase\*_: Create a copy of the bitmap. 
- __iBitmapBase::CreateConvertedFormat__(_const iPixelFormat\*_ pFmt) -> _iBitmapBase\*_: Create a copy of the bitmap that use the given format. 
- __iBitmapBase::CreateGammaCorrected__(_tF32_ factor) -> _iBitmapBase\*_: Create a gamma corrected bitmap. 
- __iBitmapBase::GammaCorrect__(_tF32_ factor) -> _tBool_: Correct gamma of the bitmap. 

## interface ni::iBitmapLoader
Bitmap Loader 

### Parents:
- iUnknown

### Methods:
- __iBitmapLoader::LoadBitmap__(_iGraphics\*_ apGraphics, _iFile\*_ apFile) -> _iBitmapBase\*_: Bitmap Loader 

## interface ni::iBitmapSaver
Bitmap Saver 

### Parents:
- iUnknown

### Methods:
- __iBitmapSaver::SaveBitmap__(_iGraphics\*_ apGraphics, _iFile\*_ apFile, _iBitmapBase\*_ apBmp, _tU32_ anCompression) -> _tBool_: Bitmap Saver 

## enum ni::eBitmapType
Bitmap type 

### Values:
- __eBitmapType_2D__ = __0__: 2D Bitmap. 
- __eBitmapType_Cube__ = __1__: Cube Bitmap. Six 2D Bitmaps. 
- __eBitmapType_3D__ = __2__: 3D Bitmap. 

## enum ni::eBitmapCubeFace
Bitmap cube faces. 

### Remarks:
- The coordinate system is Left-Handed as in DX7/8. 

### Values:
- __eBitmapCubeFace_PositiveX__ = __0__
- __eBitmapCubeFace_NegativeX__ = __1__
- __eBitmapCubeFace_PositiveY__ = __2__
- __eBitmapCubeFace_NegativeY__ = __3__
- __eBitmapCubeFace_PositiveZ__ = __4__
- __eBitmapCubeFace_NegativeZ__ = __5__

## interface ni::iBitmapCube
Cube bitmap interface. 

### Parents:
- iBitmapBase

### Methods:
- __iBitmapCube::GetFace__(_eBitmapCubeFace_ Face) -> _iBitmap2D\*_: Get the content of the indicated face. 
- __iBitmapCube::CreateResized__(_tI32_ nW) -> _iBitmapCube\*_: Create a resized cube map. 

## enum ni::eBitmapCubeFace
Bitmap cube faces. 

### Remarks:
- The coordinate system is Left-Handed as in DX7/8. 

### Values:
- __eBitmapCubeFace_PositiveX__ = __0__
- __eBitmapCubeFace_NegativeX__ = __1__
- __eBitmapCubeFace_PositiveY__ = __2__
- __eBitmapCubeFace_NegativeY__ = __3__
- __eBitmapCubeFace_PositiveZ__ = __4__
- __eBitmapCubeFace_NegativeZ__ = __5__

## enum ni::eBoundingVolumeType
Bounding volume type. 

### Values:
- __eBoundingVolumeType_AABB__ = __0__: AABB volume type. 
- __eBoundingVolumeType_Sphere__ = __1__: Sphere volume type. 
- __eBoundingVolumeType_ConvexHull__ = __2__: Convex hull volume type. 
- __eBoundingVolumeType_User__ = __2__: User volume type 

## interface ni::iBoundingVolume
Bounding volume interface. 

### Parents:
- iUnknown

### Methods:
- __iBoundingVolume::Copy__(_iBoundingVolume\*_ apSrc) -> _tBool_: Copy another bounding volume in this volume. 
- __iBoundingVolume::Clone__() -> _iBoundingVolume\*_: Create a copy of the bounding volume. 
- __iBoundingVolume::GetType__() -> _eBoundingVolumeType_: Get the bounding volume type. 
- __iBoundingVolume::Begin__(_tBool_ abReset) -> _tBool_: Begin the computation of the bounding volume. 
- __iBoundingVolume::End__() -> _tBool_: End the computation of the bounding volume. 
- __iBoundingVolume::AddPoint__(_const sVec3f&_ avPoint) -> _tBool_: Add a point inside the bounding volume. 
- __iBoundingVolume::SetCenter__(_const sVec3f&_ avPos) -> _tBool_: Set the center. 
- __iBoundingVolume::GetCenter__() -> _sVec3f_: Get the center. 
- __iBoundingVolume::SetRadius__(_tF32_ afRadius) -> _void_: Set the radius. 
- __iBoundingVolume::GetRadius__() -> _tF32_: Get the radius. 
- __iBoundingVolume::SetExtents__(_const sVec3f&_ avExtends) -> _void_: Set the extents. 
- __iBoundingVolume::GetExtents__() -> _sVec3f_: Get the extents. 
- __iBoundingVolume::SetSize__(_const sVec3f&_ avSize) -> _void_: Set the size. 
- __iBoundingVolume::GetSize__() -> _sVec3f_: Get the size. 
- __iBoundingVolume::SetMin__(_const sVec3f&_ avMin) -> _void_: Set the minimum value. 
- __iBoundingVolume::GetMin__() -> _sVec3f_: Get the minimum value. 
- __iBoundingVolume::SetMax__(_const sVec3f&_ avMax) -> _void_: Set the maximum value. 
- __iBoundingVolume::GetMax__() -> _sVec3f_: Get the maximum value. 
- __iBoundingVolume::Translate__(_const sVec3f&_ avV) -> _tBool_: Translate the bounding volume. 
- __iBoundingVolume::Rotate__(_const sMatrixf&_ amtxRotation) -> _tBool_: Rotate the bounding volume. 
- __iBoundingVolume::Transform__(_const sMatrixf&_ aMatrix) -> _tBool_: Transform by the specified matrix. 
- __iBoundingVolume::Inflate__(_tF32_ afPercent) -> _void_: Inflate the bounding volume by the given percentage. 
- __iBoundingVolume::IntersectAABB__(_iIntersection\*_ apResult, _const sVec3f&_ avMin, _const sVec3f&_ avMax) -> _eIntersectionResult_: Intersect with an AABB. 
- __iBoundingVolume::IntersectRay__(_iIntersection\*_ apResult, _const sVec3f&_ avOrg, _const sVec3f&_ avDir) -> _eIntersectionResult_: Intersect with a ray. 
- __iBoundingVolume::IntersectPoint__(_iIntersection\*_ apResult, _const sVec3f&_ aPosition) -> _eIntersectionResult_: Intersect with a point. 
- __iBoundingVolume::IntersectFrustum__(_iIntersection\*_ apResult, _const iFrustum\*_ apFrustum) -> _eIntersectionResult_: Intersect with a frustum. 

## enum ni::eBoundingVolumeType
Bounding volume type. 

### Values:
- __eBoundingVolumeType_AABB__ = __0__: AABB volume type. 
- __eBoundingVolumeType_Sphere__ = __1__: Sphere volume type. 
- __eBoundingVolumeType_ConvexHull__ = __2__: Convex hull volume type. 
- __eBoundingVolumeType_User__ = __2__: User volume type 

## enum ni::eCameraMoveType
Camera move type 

### Values:
- __eCameraMoveType_None__ = __0__: The camera view is set through the position, target & target up directly. 
- __eCameraMoveType_Fly__ = __1__: The camera simulates a flying object. 
- __eCameraMoveType_Orbit__ = __2__: The camera orbits around it's target. 
- __eCameraMoveType_FlyFixedTarget__ = __3__: The camera simulates a flying object with a fixed target. 
- __eCameraMoveType_SetMatrix__ = __4__: The camera view is set through SetViewMatrix directly. 

## enum ni::eCameraProjectionType
Camera projection type. 

### Values:
- __eCameraProjectionType_Perspective__ = __0__: Perspective camera. 
- __eCameraProjectionType_Orthogonal__ = __1__: Orthogonal with a free view pov. 
- __eCameraProjectionType_SetMatrix__ = __2__: The camera projection is set through SetProjectionMatrix directly. 

## interface ni::iCamera
Camera interface 

### Parents:
- iUnknown

### Methods:
- __iCamera::Copy__(_const iCamera\*_ pSrc) -> _void_: Copy the camera. 
- __iCamera::Clone__() -> _iCamera\*_: Clone the camera. 
- __iCamera::GetWorldMatrix__() -> _ni::sMatrixf_: Get the world matrix. 
- __iCamera::GetViewMatrix__() -> _ni::sMatrixf_: Get the view matrix. 
- __iCamera::GetProjectionMatrix__() -> _ni::sMatrixf_: Get the projection matrix. 
- __iCamera::GetFrustum__() -> _ni::iFrustum\*_: Get the frustum. 
- __iCamera::GetRay__(_ni::tF32_ afX, _ni::tF32_ afY, _const ni::sRectf&_ aRect) -> _ni::sVec3f_: Compute a ray from the given screen position and rectangle. 
- __iCamera::GetRayStart__() -> _sVec3f_: Get the starting point of the last ray 
- __iCamera::GetScreenPosition__(_const ni::sVec3f&_ avPos, _const ni::sRectf&_ aRect) -> _ni::sVec3f_: Get a screen position from the given 3d position. 
- __iCamera::SetViewMatrix__(_const sMatrixf&_ aViewMatrix) -> _void_: Set the view matrix directly. 
- __iCamera::SetProjectionMatrix__(_const sMatrixf&_ aProjMatrix) -> _void_: Set the projection matrix directly. 
- __iCamera::SetFromWorldMatrix__(_const ni::sMatrixf&_ aMatrix, _tBool_ abSetUp) -> _void_: Set the camera position, target and up vector from a matrix. 
- __iCamera::SetProjection__(_eCameraProjectionType_ aProjectionType) -> _void_: Set projection type. 
- __iCamera::GetProjection__() -> _eCameraProjectionType_: Get orthogonal projection. 
- __iCamera::SetViewport__(_const ni::sRectf&_ aRect) -> _void_: Set the camera's viewport rectangle. 
- __iCamera::GetViewport__() -> _ni::sRectf_: Get the camera's viewport rectangle. 
- __iCamera::SetFov__(_ni::tF32_ fFOV) -> _void_: Set the vertical field of view. 
- __iCamera::GetFov__() -> _ni::tF32_: Get the vertical field of view. 
- __iCamera::SetAspect__(_ni::tF32_ fAspect) -> _void_: Set the aspect ratio. 
- __iCamera::GetAspect__() -> _ni::tF32_: Get the aspect ratio. 
- __iCamera::GetAbsoluteAspect__() -> _ni::tF32_: Get the absolute aspect ratio. 
- __iCamera::SetNearClipPlane__(_ni::tF32_ afD) -> _void_: Set the near clipping plane. 
- __iCamera::GetNearClipPlane__() -> _ni::tF32_: Get the near clipping plane. 
- __iCamera::SetFarClipPlane__(_ni::tF32_ afD) -> _void_: Set the far clipping plane. 
- __iCamera::GetFarClipPlane__() -> _ni::tF32_: Get the far clipping plane. 
- __iCamera::SetOrthoSize__(_tF32_ afSize) -> _void_: Set the orthogonal projection size. 
- __iCamera::GetOrthoSize__() -> _ni::tF32_: Get the orthogonal projection size. 
- __iCamera::SetPosition__(_const ni::sVec3f&_ vPos) -> _void_: Set the position. 
- __iCamera::GetPosition__() -> _ni::sVec3f_: Get the position. 
- __iCamera::SetTarget__(_const ni::sVec3f&_ avTarget) -> _void_: Set the target. 
- __iCamera::GetTarget__() -> _ni::sVec3f_: Get the target. 
- __iCamera::SetTargetUp__(_const ni::sVec3f&_ avUp) -> _void_: Set the target up vector. 
- __iCamera::GetTargetUp__() -> _ni::sVec3f_: Get the target up vector. 
- __iCamera::SetTargetDistance__(_ni::tF32_ afDist) -> _void_: Set the distance between the camera and it's target by moving the target. 
- __iCamera::GetTargetDistance__() -> _ni::tF32_: Get the distance between the camera and it's target. 
- __iCamera::SetPositionDistance__(_ni::tF32_ afDist) -> _void_: Set the distance between the camera and it's target by moving the position. 
- __iCamera::GetPositionDistance__() -> _ni::tF32_: Get the distance between the camera and it's target. 
- __iCamera::SetTargetDirection__(_const ni::sVec3f&_ avDir) -> _void_: Set the direction of the target. 
- __iCamera::GetTargetDirection__() -> _ni::sVec3f_: Get the direction of the target. 
- __iCamera::SetMoveType__(_eCameraMoveType_ aMode) -> _void_: Set the camera move mode. 
- __iCamera::GetMoveType__() -> _eCameraMoveType_: Get the camera move mode. 
- __iCamera::MoveSidewards__(_ni::tF32_ delta) -> _void_: Move the camera sidewards relatively to itself. (X axis) 
- __iCamera::MoveUp__(_ni::tF32_ delta) -> _void_: Move the camera upward relatively to itself. (Y axis) 
- __iCamera::MoveForward__(_ni::tF32_ delta) -> _void_: Move the camera forward relatively to itself. (Y axis) 
- __iCamera::SetMove__(_const ni::sVec3f&_ avMove) -> _void_: Set the relative movement vector. (x+ sidewards, y+ upwards and z+ forward) 
- __iCamera::GetMove__() -> _ni::sVec3f_: Get the relative movement vector. 
- __iCamera::RotateTarget__(_ni::sVec3f_ avAxis, _ni::tF32_ afAngle) -> _void_: Rotates the target around the specified axis. 
- __iCamera::RotateTargetUp__(_ni::sVec3f_ avAxis, _ni::tF32_ afAngle) -> _void_: Rotates the target up around the specified axis. 
- __iCamera::AddYaw__(_ni::tF32_ a) -> _void_: Rotates the target up around the specified axis. Add yaw. 
- __iCamera::AddPitch__(_ni::tF32_ a) -> _void_: Add pitch. 
- __iCamera::AddRoll__(_ni::tF32_ a) -> _void_: Add roll. 
- __iCamera::OrbitUp__(_ni::tF32_ afA) -> _void_: Orbit up/down the position of the camera around the current target. 
- __iCamera::OrbitSidewards__(_ni::tF32_ afA) -> _void_: Orbit left/right the position of the camera around the current target. 
- __iCamera::GetForward__() -> _ni::sVec3f_: Get the forward vector. 
- __iCamera::GetRight__() -> _ni::sVec3f_: Get the right vector. 
- __iCamera::GetUp__() -> _ni::sVec3f_: Get the up vector. 

## enum ni::eCameraMoveType
Camera move type 

### Values:
- __eCameraMoveType_None__ = __0__: The camera view is set through the position, target & target up directly. 
- __eCameraMoveType_Fly__ = __1__: The camera simulates a flying object. 
- __eCameraMoveType_Orbit__ = __2__: The camera orbits around it's target. 
- __eCameraMoveType_FlyFixedTarget__ = __3__: The camera simulates a flying object with a fixed target. 
- __eCameraMoveType_SetMatrix__ = __4__: The camera view is set through SetViewMatrix directly. 

## enum ni::eBillboardModeFlags
Billboard mode flags. 

### Values:
- __eBillboardModeFlags_Disabled__ = __0__: Disabled billboard mode. 
- __eBillboardModeFlags_CustomCenter__ = __niBit(0)__: Custom center specified. 
- __eBillboardModeFlags_AnchorCenter__ = __niBit(1)__: Anchor at the center (default if anchor not specified). 

## interface ni::iCanvas
Canvas interface. 

### Parents:
- iUnknown

### Methods:
- __iCanvas::GetGraphicsContext__() -> _iGraphicsContext\*_: Get the parent graphics context. 
- __iCanvas::SetContentsScale__(_tF32_ afContentsScale) -> _void_: Set the canvas' contents scale. 
- __iCanvas::GetContentsScale__() -> _tF32_: Get the canva's contents scale. 
- __iCanvas::GetViewport__() -> _sRectf_: Get the viewport size in UI units. 
- __iCanvas::Flush__() -> _tBool_: Flush the rendering to the target immediatly. 
- __iCanvas::BlitFill__(_const sRectf&_ aDestRect, _tU32_ aColor) -> _tBool_
- __iCanvas::BlitFillAlpha__(_const sRectf&_ aDestRect, _tU32_ aColor) -> _tBool_
- __iCanvas::BlitStretch__(_const sRectf&_ aDestRect, _iTexture\*_ apSrc, _const sRectf&_ aSrcRect) -> _tBool_
- __iCanvas::BlitStretchAlpha__(_const sRectf&_ aDestRect, _iTexture\*_ apSrc, _const sRectf&_ aSrcRect) -> _tBool_
- __iCanvas::BlitStretchAlpha1__(_const sRectf&_ aDestRect, _iTexture\*_ apSrc, _const sRectf&_ aSrcRect, _tF32_ afAlpha) -> _tBool_
- __iCanvas::BlitOverlay__(_const sRectf&_ aDestRect, _iOverlay\*_ apOverlay) -> _tBool_
- __iCanvas::BlitOverlayFrame__(_const sRectf&_ aDestRect, _iOverlay\*_ apOverlay, _tRectFrameFlags_ aFrame) -> _tBool_
- __iCanvas::BlitLine__(_const sVec2f&_ aStart, _const sVec2f&_ aEnd, _tU32_ aColor) -> _tBool_
- __iCanvas::BlitLineAlpha__(_const sVec2f&_ aStart, _const sVec2f&_ aEnd, _tU32_ aColor) -> _tBool_
- __iCanvas::BlitRect__(_const sRectf&_ aDestRect, _tU32_ aColor) -> _tBool_
- __iCanvas::BlitRectAlpha__(_const sRectf&_ aDestRect, _tU32_ aColor) -> _tBool_
- __iCanvas::BlitText__(_iFont\*_ apFont, _const sRectf&_ aRect, _tFontFormatFlags_ aFormatFlags, _const achar\*_ aaszText) -> _sRectf_: Blit text with the specified font. 
- __iCanvas::ResetStates__() -> _void_: Reset the canvas states to the default states. 
- __iCanvas::GetHasVertices__() -> _tBool_: Check whether any vertex has been pushed in the rendering buffer. 
- __iCanvas::GetDrawOperation__() -> _iDrawOperation\*_: Get the canvas's draw operation. 
- __iCanvas::SetColorA__(_tU32_ anColor) -> _void_: Set the default color A of the canvas. (default is 0xFFFFFFFF - white) 
- __iCanvas::GetColorA__() -> _tU32_: Get the color A. 
- __iCanvas::SetNormal__(_const sVec3f&_ avNormal) -> _void_: Set the default normal of the canvas. (default sVec3f::YAxis()) 
- __iCanvas::GetNormal__() -> _sVec3f_: Get the default normal. 
- __iCanvas::SetLineConstantScreenSize__(_tBool_ abConstSize) -> _void_: Set whether line have a constant size in screen space. 
- __iCanvas::GetLineConstantScreenSize__() -> _tBool_: Get whether line have a constant size in screen space 
- __iCanvas::SetLineSize__(_tF32_ afSize) -> _void_: Set the line size. 
- __iCanvas::GetLineSize__() -> _tF32_: Get the line size. 
- __iCanvas::SetMaterial__(_iMaterial\*_ apMaterial) -> _void_: Set the drawop's material. 
- __iCanvas::GetMaterial__() -> _iMaterial\*_: Get the drawop's material. 
- __iCanvas::SetDefaultMaterial__(_iTexture\*_ apTexture, _eBlendMode_ aBlendMode, _tIntPtr_ aSamplerStates) -> _void_: Sets the default material as current material and sets its texture, blendmode and sampler states. 
- __iCanvas::SetMatrix__(_const sMatrixf&_ aMatrix) -> _void_: Set the current matrix. 
- __iCanvas::GetMatrix__() -> _sMatrixf_: Get the current matrix. 
- __iCanvas::SetBillboard__(_tBillboardModeFlags_ aMode) -> _void_: Set billboard mode. 
- __iCanvas::GetBillboard__() -> _tBillboardModeFlags_: Get billboard mode. 
- __iCanvas::SetBillboardRight__(_const sVec3f&_ avRight) -> _void_: Set the billboard right vector. 
- __iCanvas::GetBillboardRight__() -> _sVec3f_: Get the billboard right vector. 
- __iCanvas::SetBillboardUp__(_const sVec3f&_ avUp) -> _void_: Set the billboard up vector. 
- __iCanvas::GetBillboardUp__() -> _sVec3f_: Get the billboard up vector. 
- __iCanvas::SetBillboardCenter__(_const sVec3f&_ avCenter) -> _void_: Set the custom billboard center. 
- __iCanvas::GetBillboardCenter__() -> _sVec3f_: Get the custom billboard center. 
- __iCanvas::Rect__(_const sVec2f&_ avTL, _const sVec2f&_ avBR, _tF32_ afZ) -> _tBool_: Push an immediate mode rectangle. 
- __iCanvas::RectT__(_const sVec2f&_ avTL, _const sVec2f&_ avBR, _const sVec2f&_ avTLTex, _const sVec2f&_ avBRTex, _tF32_ afZ) -> _tBool_: Push an immediate mode rectangle, specifying the texture coordinates. 
- __iCanvas::RectA__(_const sVec2f&_ avTL, _const sVec2f&_ avBR, _tF32_ afZ, _tU32_ anColA) -> _tBool_: Push an immediate mode rectangle with color A. 
- __iCanvas::RectTA__(_const sVec2f&_ avTL, _const sVec2f&_ avBR, _const sVec2f&_ avTLTex, _const sVec2f&_ avBRTex, _tF32_ afZ, _tU32_ anColA) -> _tBool_: Push an immediate mode rectangle, specifying the texture coordinates and color A. 
- __iCanvas::RectTA2__(_const sVec2f&_ avTL, _const sVec2f&_ avBR, _const sVec2f&_ avTLTex, _const sVec2f&_ avBRTex, _tF32_ afZ, _tU32_ anTLColA, _tU32_ anTRColA, _tU32_ anBRColA, _tU32_ anBLColA) -> _tBool_: Push an immediate mode rectangle, specifying the texture coordinates, color A and Color B. 
- __iCanvas::QuadEx__(_const sVec3f&_ avTL, _const sVec3f&_ avTLN, _const sVec2f&_ avTLTex, _tU32_ anTLA, _const sVec3f&_ avTR, _const sVec3f&_ avTRN, _const sVec2f&_ avTRTex, _tU32_ anTRA, _const sVec3f&_ avBR, _const sVec3f&_ avBRN, _const sVec2f&_ avBRTex, _tU32_ anBRA, _const sVec3f&_ avBL, _const sVec3f&_ avBLN, _const sVec2f&_ avBLTex, _tU32_ anBLA) -> _tBool_: Push an immediate mode quad with 3d positions, normals, texture coordinates, color A and color B. 
- __iCanvas::Quad__(_const sVec3f&_ avTL, _const sVec3f&_ avTR, _const sVec3f&_ avBR, _const sVec3f&_ avBL) -> _tBool_: Push an immediate mode quad with 3d positions, texture coordinates, color A and color B. 
- __iCanvas::QuadA__(_const sVec3f&_ avTL, _const sVec3f&_ avTR, _const sVec3f&_ avBR, _const sVec3f&_ avBL, _tU32_ anColorA) -> _tBool_: Push an immediate mode quad with 3d positions, texture coordinates, color A and color B. 
- __iCanvas::QuadA2__(_const sVec3f&_ avTL, _tU32_ anTLColA, _const sVec3f&_ avTR, _tU32_ anTRColA, _const sVec3f&_ avBR, _tU32_ anBRColA, _const sVec3f&_ avBL, _tU32_ anBLColA) -> _tBool_: Push an immediate mode quad with 3d positions, texture coordinates, color A and color B. 
- __iCanvas::QuadT__(_const sVec3f&_ avTL, _const sVec2f&_ avTLTex, _const sVec3f&_ avTR, _const sVec2f&_ avTRTex, _const sVec3f&_ avBR, _const sVec2f&_ avBRTex, _const sVec3f&_ avBL, _const sVec2f&_ avBLTex) -> _tBool_: Push an immediate mode quad with 3d positions, texture coordinates, color A and color B. 
- __iCanvas::QuadTA__(_const sVec3f&_ avTL, _const sVec2f&_ avTLTex, _const sVec3f&_ avTR, _const sVec2f&_ avTRTex, _const sVec3f&_ avBR, _const sVec2f&_ avBRTex, _const sVec3f&_ avBL, _const sVec2f&_ avBLTex, _tU32_ anColorA) -> _tBool_: Push an immediate mode quad with 3d positions, texture coordinates, color A and color B. 
- __iCanvas::QuadTA2__(_const sVec3f&_ avTL, _const sVec2f&_ avTLTex, _tU32_ anTLColA, _const sVec3f&_ avTR, _const sVec2f&_ avTRTex, _tU32_ anTRColA, _const sVec3f&_ avBR, _const sVec2f&_ avBRTex, _tU32_ anBRColA, _const sVec3f&_ avBL, _const sVec2f&_ avBLTex, _tU32_ anBLColA) -> _tBool_: Push an immediate mode quad with 3d positions, texture coordinates, color A and color B. 
- __iCanvas::Frame__(_tRectFrameFlags_ aFrame, _const sVec4f&_ aFrameBorder, _const sVec2f&_ avTL, _const sVec2f&_ avBR, _tF32_ afZ) -> _tBool_: Push an immediate mode rectangle. 
- __iCanvas::FrameA__(_tRectFrameFlags_ aFrame, _const sVec4f&_ aFrameBorder, _const sVec2f&_ avTL, _const sVec2f&_ avBR, _tF32_ afZ, _tU32_ anColA) -> _tBool_: Push an immediate mode rectangle with the specified color. 
- __iCanvas::FrameT__(_tRectFrameFlags_ aFrame, _const sVec4f&_ aFrameBorder, _const sVec2f&_ avTL, _const sVec2f&_ avBR, _const sVec2f&_ avTLTex, _const sVec2f&_ avBRTex, _tF32_ afZ) -> _tBool_: Push an immediate mode rectangle, specifying the texture coordinates. 
- __iCanvas::FrameTA__(_tRectFrameFlags_ aFrame, _const sVec4f&_ aFrameBorder, _const sVec2f&_ avTL, _const sVec2f&_ avBR, _const sVec2f&_ avTLTex, _const sVec2f&_ avBRTex, _tF32_ afZ, _tU32_ anColA) -> _tBool_: Push an immediate mode rectangle, specifying the texture coordinates and color a. 
- __iCanvas::FrameTA2__(_tRectFrameFlags_ aFrame, _const sVec4f&_ aFrameBorder, _const sVec2f&_ avTL, _const sVec2f&_ avBR, _const sVec2f&_ avTLTex, _const sVec2f&_ avBRTex, _tF32_ afZ, _tU32_ anTLColA, _tU32_ anTRColA, _tU32_ anBRColA, _tU32_ anBLColA) -> _tBool_: Push an immediate mode rectangle, specifying the texture coordinates, color A and Color B. 
- __iCanvas::Line__(_const sVec3f&_ avStart, _const sVec3f&_ avEnd) -> _tBool_: Push a line. 
- __iCanvas::LineA__(_const sVec3f&_ avStart, _const sVec3f&_ avEnd, _tU32_ anCol) -> _tBool_: Push a line. 
- __iCanvas::LineEx__(_const sVec3f&_ avStart, _const sVec2f&_ avStartTex, _tF32_ afStartSize, _tU32_ anStartCol, _const sVec3f&_ avEnd, _const sVec2f&_ avEndTex, _tF32_ afEndSize, _tU32_ anEndCol) -> _tBool_: Push a line. 
- __iCanvas::LineGridXY__(_ni::tF32_ aX, _ni::tF32_ aY, _ni::tU32_ anNumColumns, _ni::tU32_ anNumRows) -> _void_: Push a XY grid made of lines. 
- __iCanvas::LineGridXZ__(_ni::tF32_ aX, _ni::tF32_ aZ, _ni::tU32_ anNumColumns, _ni::tU32_ anNumRows) -> _void_: Push a XZ grid made of lines. 
- __iCanvas::WireframeCircle__(_const sVec3f&_ avCenter, _tF32_ afRadius, _tU32_ aulNumDiv, _ePlaneType_ aPlane) -> _tBool_: Draw a circle. 
- __iCanvas::WireframeEllipse__(_const sVec3f&_ avCenter, _const sVec2f&_ avRadius, _tU32_ aulNumDiv, _ePlaneType_ aPlane) -> _tBool_: Draw an ellipse. 
- __iCanvas::WireframeAABB__(_const sVec3f&_ avMin, _const sVec3f&_ avMax) -> _tBool_: Draw wireframe AABB. 
- __iCanvas::WireframeSphere__(_const sVec3f&_ aCenter, _tF32_ afRadius, _tU32_ aulNumDiv) -> _tBool_: Draw wireframe sphere. 
- __iCanvas::WireframeSphereEx__(_const sVec3f&_ aCenter, _tF32_ afRadius, _tU32_ aulNumDiv, _tU32_ aulColorX, _tU32_ aulColorY, _tU32_ aulColorZ) -> _tBool_: Draw wireframe sphere. 
- __iCanvas::WireframeEllipsoid__(_const sVec3f&_ aCenter, _const sVec3f&_ avRadius, _tU32_ aulNumDiv) -> _tBool_: Draw wireframe ellipsoid. 
- __iCanvas::WireframeEllipsoidEx__(_const sVec3f&_ aCenter, _const sVec3f&_ avRadius, _tU32_ aulNumDiv, _tU32_ aulColorX, _tU32_ aulColorY, _tU32_ aulColorZ) -> _tBool_: Draw wireframe ellipsoid. 
- __iCanvas::WireframeCone__(_const sVec3f&_ avBaseCenter, _tF32_ afBaseRadius, _tF32_ afHeight, _tU32_ aulNumDiv, _ePlaneType_ aPlane) -> _tBool_: Draw a wireframe cone. 
- __iCanvas::VertexP__(_const sVec3f&_ avPosition) -> _tBool_: Push a vertex with position. 
- __iCanvas::VertexPN__(_const sVec3f&_ avPosition, _const sVec3f&_ avNormal) -> _tBool_: Push a vertex with position and normal. 
- __iCanvas::VertexPT__(_const sVec3f&_ avPosition, _const sVec2f&_ avTex) -> _tBool_: Push a vertex with position and a 2d texture coodinate. 
- __iCanvas::VertexPTA__(_const sVec3f&_ avPosition, _const sVec2f&_ avTex, _tU32_ anColorA) -> _tBool_: Push a vertex with position, a 2d texture coodinate and color A. 
- __iCanvas::VertexPNT__(_const sVec3f&_ avPosition, _const sVec3f&_ avNormal, _const sVec2f&_ avTex) -> _tBool_: Push a vertex with position, normal and texture coodinate. 
- __iCanvas::VertexPNTA__(_const sVec3f&_ avPosition, _const sVec3f&_ avNormal, _const sVec2f&_ avTex, _tU32_ anColorA) -> _tBool_: Push a vertex with position, normal, texture coodinate and color A. 
- __iCanvas::GetVGMaterial__() -> _iMaterial\*_: Get the VG path used for drawing. 
- __iCanvas::GetVGStyle__() -> _iVGStyle\*_: Get the VG style used for drawing. 
- __iCanvas::GetVGTransform__(_eVGTransform_ aTransform) -> _iVGTransform\*_: Get the VG transform used for drawing. 
- __iCanvas::DrawPath__(_const iVGPath\*_ apPath) -> _void_: Draw a VG path. 

## enum ni::eBillboardModeFlags
Billboard mode flags. 

### Values:
- __eBillboardModeFlags_Disabled__ = __0__: Disabled billboard mode. 
- __eBillboardModeFlags_CustomCenter__ = __niBit(0)__: Custom center specified. 
- __eBillboardModeFlags_AnchorCenter__ = __niBit(1)__: Anchor at the center (default if anchor not specified). 

## interface ni::iDampedSpring1
1D Damped spring interface. \see ni::DampedSpringAcceleration 

### Parents:
- iUnknown

### Methods:
- __iDampedSpring1::SetKd__(_tF32_ afD) -> _void_: Set the Kd constant. 
- __iDampedSpring1::GetKd__() -> _tF32_: Get the Kd constant. 
- __iDampedSpring1::SetKs__(_tF32_ afD) -> _void_: Set the Ks constant. 
- __iDampedSpring1::GetKs__() -> _tF32_: Get the Ks constant. 
- __iDampedSpring1::SetStiffnessAndDampingRatio__(_tF32_ afKs, _tF32_ afE) -> _void_: Set the value of Kd for the specified Ks that will result in a spring with the specified damping ratio. 
- __iDampedSpring1::SetDampingRatio__(_tF32_ afE) -> _void_: Set the spring's damping ratio. 
- __iDampedSpring1::GetDampingRatio__() -> _tF32_: Get the spring's damping ratio. 
- __iDampedSpring1::SetVelocity__(_tF32_ avVel) -> _void_: Set the spring's velocity. 
- __iDampedSpring1::GetVelocity__() -> _tF32_: Get the spring's velocity. 
- __iDampedSpring1::ComputeAcceleration__(_tF32_ avD) -> _tF32_: Compute the spring's acceleration for the specified displacement. 
- __iDampedSpring1::UpdateVelocity__(_ni::tF32_ afDeltaTime, _tF32_ avD) -> _void_: Update the spring's velocity from the specified displacement. 
- __iDampedSpring1::UpdateVelocityWithAcceleration__(_ni::tF32_ afDeltaTime, _tF32_ avAcc) -> _void_: Update the spring's velocity from the specified acceleration. 

## interface ni::iDampedSpring2
2D Damped spring interface. \see ni::DampedSpringAcceleration 

### Parents:
- iUnknown

### Methods:
- __iDampedSpring2::SetKd__(_tF32_ afD) -> _void_: Set the Kd constant. 
- __iDampedSpring2::GetKd__() -> _tF32_: Get the Kd constant. 
- __iDampedSpring2::SetKs__(_tF32_ afD) -> _void_: Set the Ks constant. 
- __iDampedSpring2::GetKs__() -> _tF32_: Get the Ks constant. 
- __iDampedSpring2::SetStiffnessAndDampingRatio__(_tF32_ afKs, _tF32_ afE) -> _void_: Set the value of Kd for the specified Ks that will result in a spring with the specified damping ratio. 
- __iDampedSpring2::SetDampingRatio__(_tF32_ afE) -> _void_: Set the spring's damping ratio. 
- __iDampedSpring2::GetDampingRatio__() -> _tF32_: Get the spring's damping ratio. 
- __iDampedSpring2::SetVelocity__(_const sVec2f&_ avVel) -> _void_: Set the spring's velocity. 
- __iDampedSpring2::GetVelocity__() -> _sVec2f_: Get the spring's velocity. 
- __iDampedSpring2::ComputeAcceleration__(_const sVec2f&_ avD) -> _sVec2f_: Compute the spring's acceleration for the specified displacement. 
- __iDampedSpring2::UpdateVelocity__(_ni::tF32_ afDeltaTime, _const sVec2f&_ avD) -> _void_: Update the spring's velocity from the specified displacement. 
- __iDampedSpring2::UpdateVelocityWithAcceleration__(_ni::tF32_ afDeltaTime, _const sVec2f&_ avAcc) -> _void_: Update the spring's velocity from the specified acceleration. 

## interface ni::iDampedSpring3
3D Damped spring interface. \see ni::DampedSpringAcceleration 

### Parents:
- iUnknown

### Methods:
- __iDampedSpring3::SetKd__(_tF32_ afD) -> _void_: Set the Kd constant. 
- __iDampedSpring3::GetKd__() -> _tF32_: Get the Kd constant. 
- __iDampedSpring3::SetKs__(_tF32_ afD) -> _void_: Set the Ks constant. 
- __iDampedSpring3::GetKs__() -> _tF32_: Get the Ks constant. 
- __iDampedSpring3::SetStiffnessAndDampingRatio__(_tF32_ afKs, _tF32_ afE) -> _void_: Set the value of Kd for the specified Ks that will result in a spring with the specified damping ratio. 
- __iDampedSpring3::SetDampingRatio__(_tF32_ afE) -> _void_: Set the spring's damping ratio. 
- __iDampedSpring3::GetDampingRatio__() -> _tF32_: Get the spring's damping ratio. 
- __iDampedSpring3::SetVelocity__(_const sVec3f&_ avVel) -> _void_: Set the spring's velocity. 
- __iDampedSpring3::GetVelocity__() -> _sVec3f_: Get the spring's velocity. 
- __iDampedSpring3::ComputeAcceleration__(_const sVec3f&_ avD) -> _sVec3f_: Compute the spring's acceleration for the specified displacement. 
- __iDampedSpring3::UpdateVelocity__(_ni::tF32_ afDeltaTime, _const sVec3f&_ avD) -> _void_: Update the spring's velocity from the specified displacement. 
- __iDampedSpring3::UpdateVelocityWithAcceleration__(_ni::tF32_ afDeltaTime, _const sVec3f&_ avAcc) -> _void_: Update the spring's velocity from the specified acceleration. 

## interface ni::iDampedSpring4
4D Damped spring interface. \see ni::DampedSpringAcceleration 

### Parents:
- iUnknown

### Methods:
- __iDampedSpring4::SetKd__(_tF32_ afD) -> _void_: Set the Kd constant. 
- __iDampedSpring4::GetKd__() -> _tF32_: Get the Kd constant. 
- __iDampedSpring4::SetKs__(_tF32_ afD) -> _void_: Set the Ks constant. 
- __iDampedSpring4::GetKs__() -> _tF32_: Get the Ks constant. 
- __iDampedSpring4::SetStiffnessAndDampingRatio__(_tF32_ afKs, _tF32_ afE) -> _void_: Set the value of Kd for the specified Ks that will result in a spring with the specified damping ratio. 
- __iDampedSpring4::SetDampingRatio__(_tF32_ afE) -> _void_: Set the spring's damping ratio. 
- __iDampedSpring4::GetDampingRatio__() -> _tF32_: Get the spring's damping ratio. 
- __iDampedSpring4::SetVelocity__(_const sVec4f&_ avVel) -> _void_: Set the spring's velocity. 
- __iDampedSpring4::GetVelocity__() -> _sVec4f_: Get the spring's velocity. 
- __iDampedSpring4::ComputeAcceleration__(_const sVec4f&_ avD) -> _sVec4f_: Compute the spring's acceleration for the specified displacement. 
- __iDampedSpring4::UpdateVelocity__(_ni::tF32_ afDeltaTime, _const sVec4f&_ avD) -> _void_: Update the spring's velocity from the specified displacement. 
- __iDampedSpring4::UpdateVelocityWithAcceleration__(_ni::tF32_ afDeltaTime, _const sVec4f&_ avAcc) -> _void_: Update the spring's velocity from the specified acceleration. 

## interface ni::iDampedSpringPosition1
1D Damped spring position interface. 

### Parents:
- iDampedSpring1

### Methods:
- __iDampedSpringPosition1::SetIdealPosition__(_tF32_ avPos) -> _void_: Set the ideal (target) position of the spring. 
- __iDampedSpringPosition1::GetIdealPosition__() -> _tF32_: Get the ideal (target) position of the spring. 
- __iDampedSpringPosition1::SetCurrentPosition__(_tF32_ avPos) -> _void_: Set the current position of the spring. 
- __iDampedSpringPosition1::GetCurrentPosition__() -> _tF32_: Get the current position of the spring. 
- __iDampedSpringPosition1::UpdatePosition__(_ni::tF32_ afDeltaTime) -> _tF32_: Update the current position of the spring. 
- __iDampedSpringPosition1::SetStep__(_tF32_ afD) -> _void_: Set the maximum update step size. 
- __iDampedSpringPosition1::GetStep__() -> _tF32_: Get the update step size. 
- __iDampedSpringPosition1::SetSpeed__(_tF32_ afD) -> _void_: Set the animation speed. 
- __iDampedSpringPosition1::GetSpeed__() -> _tF32_: Get the animation speed. 
- __iDampedSpringPosition1::SetEndThreshold__(_tF32_ afD) -> _void_: Set the end threshold. 
- __iDampedSpringPosition1::GetEndThreshold__() -> _tF32_: Get the end threshold. 
- __iDampedSpringPosition1::GetIsEnded__() -> _tBool_: Get the whether the distance between the ideal and the current positions are below the end threshold. 

## interface ni::iDampedSpringPosition2
2D Damped spring position interface. 

### Parents:
- iDampedSpring2

### Methods:
- __iDampedSpringPosition2::SetIdealPosition__(_const sVec2f&_ avPos) -> _void_: Set the ideal (target) position of the spring. 
- __iDampedSpringPosition2::GetIdealPosition__() -> _sVec2f_: Get the ideal (target) position of the spring. 
- __iDampedSpringPosition2::SetCurrentPosition__(_const sVec2f&_ avPos) -> _void_: Set the current position of the spring. 
- __iDampedSpringPosition2::GetCurrentPosition__() -> _sVec2f_: Get the current position of the spring. 
- __iDampedSpringPosition2::UpdatePosition__(_ni::tF32_ afDeltaTime) -> _sVec2f_: Update the current position of the spring. 
- __iDampedSpringPosition2::SetStep__(_tF32_ afD) -> _void_: Set the maximum update step size. 
- __iDampedSpringPosition2::GetStep__() -> _tF32_: Get the update step size. 
- __iDampedSpringPosition2::SetSpeed__(_tF32_ afD) -> _void_: Set the animation speed. 
- __iDampedSpringPosition2::GetSpeed__() -> _tF32_: Get the animation speed. 
- __iDampedSpringPosition2::SetEndThreshold__(_tF32_ afD) -> _void_: Set the end threshold. 
- __iDampedSpringPosition2::GetEndThreshold__() -> _tF32_: Get the end threshold. 
- __iDampedSpringPosition2::GetIsEnded__() -> _tBool_: Get the whether the distance between the ideal and the current positions are below the end threshold. 

## interface ni::iDampedSpringPosition3
3D Damped spring position interface. 

### Parents:
- iDampedSpring3

### Methods:
- __iDampedSpringPosition3::SetIdealPosition__(_const sVec3f&_ avPos) -> _void_: Set the ideal (target) position of the spring. 
- __iDampedSpringPosition3::GetIdealPosition__() -> _sVec3f_: Get the ideal (target) position of the spring. 
- __iDampedSpringPosition3::SetCurrentPosition__(_const sVec3f&_ avPos) -> _void_: Set the current position of the spring. 
- __iDampedSpringPosition3::GetCurrentPosition__() -> _sVec3f_: Get the current position of the spring. 
- __iDampedSpringPosition3::UpdatePosition__(_ni::tF32_ afDeltaTime) -> _sVec3f_: Update the current position of the spring. 
- __iDampedSpringPosition3::SetStep__(_tF32_ afD) -> _void_: Set the maximum update step size. 
- __iDampedSpringPosition3::GetStep__() -> _tF32_: Get the update step size. 
- __iDampedSpringPosition3::SetSpeed__(_tF32_ afD) -> _void_: Set the animation speed. 
- __iDampedSpringPosition3::GetSpeed__() -> _tF32_: Get the animation speed. 
- __iDampedSpringPosition3::SetEndThreshold__(_tF32_ afD) -> _void_: Set the end threshold. 
- __iDampedSpringPosition3::GetEndThreshold__() -> _tF32_: Get the end threshold. 
- __iDampedSpringPosition3::GetIsEnded__() -> _tBool_: Get the whether the distance between the ideal and the current positions are below the end threshold. 

## interface ni::iDampedSpringPosition4
4D Damped spring position interface. 

### Parents:
- iDampedSpring4

### Methods:
- __iDampedSpringPosition4::SetIdealPosition__(_const sVec4f&_ avPos) -> _void_: Set the ideal (target) position of the spring. 
- __iDampedSpringPosition4::GetIdealPosition__() -> _sVec4f_: Get the ideal (target) position of the spring. 
- __iDampedSpringPosition4::SetCurrentPosition__(_const sVec4f&_ avPos) -> _void_: Set the current position of the spring. 
- __iDampedSpringPosition4::GetCurrentPosition__() -> _sVec4f_: Get the current position of the spring. 
- __iDampedSpringPosition4::UpdatePosition__(_ni::tF32_ afDeltaTime) -> _sVec4f_: Update the current position of the spring. 
- __iDampedSpringPosition4::SetStep__(_tF32_ afD) -> _void_: Set the maximum update step size. 
- __iDampedSpringPosition4::GetStep__() -> _tF32_: Get the maximum update step size. 
- __iDampedSpringPosition4::SetSpeed__(_tF32_ afD) -> _void_: Set the animation speed. 
- __iDampedSpringPosition4::GetSpeed__() -> _tF32_: Get the animation speed. 
- __iDampedSpringPosition4::SetEndThreshold__(_tF32_ afD) -> _void_: Set the end threshold. 
- __iDampedSpringPosition4::GetEndThreshold__() -> _tF32_: Get the end threshold. 
- __iDampedSpringPosition4::GetIsEnded__() -> _tBool_: Get the whether the distance between the ideal and the current positions are below the end threshold. 

## interface ni::iDampedSpring1
1D Damped spring interface. \see ni::DampedSpringAcceleration 

### Parents:
- iUnknown

### Methods:
- __iDampedSpring1::SetKd__(_tF32_ afD) -> _void_: Set the Kd constant. 
- __iDampedSpring1::GetKd__() -> _tF32_: Get the Kd constant. 
- __iDampedSpring1::SetKs__(_tF32_ afD) -> _void_: Set the Ks constant. 
- __iDampedSpring1::GetKs__() -> _tF32_: Get the Ks constant. 
- __iDampedSpring1::SetStiffnessAndDampingRatio__(_tF32_ afKs, _tF32_ afE) -> _void_: Set the value of Kd for the specified Ks that will result in a spring with the specified damping ratio. 
- __iDampedSpring1::SetDampingRatio__(_tF32_ afE) -> _void_: Set the spring's damping ratio. 
- __iDampedSpring1::GetDampingRatio__() -> _tF32_: Get the spring's damping ratio. 
- __iDampedSpring1::SetVelocity__(_tF32_ avVel) -> _void_: Set the spring's velocity. 
- __iDampedSpring1::GetVelocity__() -> _tF32_: Get the spring's velocity. 
- __iDampedSpring1::ComputeAcceleration__(_tF32_ avD) -> _tF32_: Compute the spring's acceleration for the specified displacement. 
- __iDampedSpring1::UpdateVelocity__(_ni::tF32_ afDeltaTime, _tF32_ avD) -> _void_: Update the spring's velocity from the specified displacement. 
- __iDampedSpring1::UpdateVelocityWithAcceleration__(_ni::tF32_ afDeltaTime, _tF32_ avAcc) -> _void_: Update the spring's velocity from the specified acceleration. 

## interface ni::iDrawOperation
Draw operation interface. 

### Parents:
- iUnknown

### Methods:
- __iDrawOperation::Copy__(_const iDrawOperation\*_ apDO) -> _tBool_: Copy another draw operation. 
- __iDrawOperation::Clone__() -> _iDrawOperation\*_: Clone this draw operation. 
- __iDrawOperation::GetIsCompiled__() -> _tBool_: Return whether the draw operation is compiled (read-only) 
- __iDrawOperation::SetPriority__(_tU32_ anPriority) -> _void_: Set the priority. 
- __iDrawOperation::GetPriority__() -> _tU32_: Get the priority. 
- __iDrawOperation::SetVertexArray__(_iVertexArray\*_ apVertexArray) -> _void_: Set the vertex array. 
- __iDrawOperation::GetVertexArray__() -> _iVertexArray\*_: Get the vertex array. 
- __iDrawOperation::SetPrimitiveType__(_eGraphicsPrimitiveType_ aPrim) -> _void_: Set the primitive type. 
- __iDrawOperation::GetPrimitiveType__() -> _eGraphicsPrimitiveType_: Get the primitive type. 
- __iDrawOperation::SetIndexArray__(_iIndexArray\*_ apIndexArray) -> _void_: Set the index array. 
- __iDrawOperation::GetIndexArray__() -> _iIndexArray\*_: Get the index array. 
- __iDrawOperation::SetFirstIndex__(_tU32_ anIndex) -> _void_: Set the first index. 
- __iDrawOperation::GetFirstIndex__() -> _tU32_: Get the first index. 
- __iDrawOperation::SetNumIndices__(_tU32_ anNumIndices) -> _void_: Set the number of indices. 
- __iDrawOperation::GetNumIndices__() -> _tU32_: Get the number of indices. 
- __iDrawOperation::SetBaseVertexIndex__(_tU32_ anBaseVertexIndex) -> _void_: Set the base vertex index. 
- __iDrawOperation::GetBaseVertexIndex__() -> _tU32_: Get the base vertex index. 
- __iDrawOperation::SetMatrix__(_const sMatrixf&_ apMatrix) -> _void_: Set the matrix. 
- __iDrawOperation::GetMatrix__() -> _sMatrixf_: Get the matrix. 
- __iDrawOperation::SetMaterial__(_iMaterial\*_ apMaterial) -> _void_: Set the material. 
- __iDrawOperation::GetMaterial__() -> _iMaterial\*_: Get the material. 
- __iDrawOperation::SetLocalBoundingVolume__(_iBoundingVolume\*_ apBV) -> _void_: Set the bounding volume. 
- __iDrawOperation::GetLocalBoundingVolume__() -> _iBoundingVolume\*_: Get the bounding volume in local space. 
- __iDrawOperation::GetBoundingVolume__() -> _iBoundingVolume\*_: Get the bounding volume in world space. 
- __iDrawOperation::GetCenter__() -> _sVec3f_: Get the center position. 
- __iDrawOperation::GetFVF__() -> _tFVF_: Get the FVF of the draw operation. 

## interface ni::iDrawOperation
Draw operation interface. 

### Parents:
- iUnknown

### Methods:
- __iDrawOperation::Copy__(_const iDrawOperation\*_ apDO) -> _tBool_: Copy another draw operation. 
- __iDrawOperation::Clone__() -> _iDrawOperation\*_: Clone this draw operation. 
- __iDrawOperation::GetIsCompiled__() -> _tBool_: Return whether the draw operation is compiled (read-only) 
- __iDrawOperation::SetPriority__(_tU32_ anPriority) -> _void_: Set the priority. 
- __iDrawOperation::GetPriority__() -> _tU32_: Get the priority. 
- __iDrawOperation::SetVertexArray__(_iVertexArray\*_ apVertexArray) -> _void_: Set the vertex array. 
- __iDrawOperation::GetVertexArray__() -> _iVertexArray\*_: Get the vertex array. 
- __iDrawOperation::SetPrimitiveType__(_eGraphicsPrimitiveType_ aPrim) -> _void_: Set the primitive type. 
- __iDrawOperation::GetPrimitiveType__() -> _eGraphicsPrimitiveType_: Get the primitive type. 
- __iDrawOperation::SetIndexArray__(_iIndexArray\*_ apIndexArray) -> _void_: Set the index array. 
- __iDrawOperation::GetIndexArray__() -> _iIndexArray\*_: Get the index array. 
- __iDrawOperation::SetFirstIndex__(_tU32_ anIndex) -> _void_: Set the first index. 
- __iDrawOperation::GetFirstIndex__() -> _tU32_: Get the first index. 
- __iDrawOperation::SetNumIndices__(_tU32_ anNumIndices) -> _void_: Set the number of indices. 
- __iDrawOperation::GetNumIndices__() -> _tU32_: Get the number of indices. 
- __iDrawOperation::SetBaseVertexIndex__(_tU32_ anBaseVertexIndex) -> _void_: Set the base vertex index. 
- __iDrawOperation::GetBaseVertexIndex__() -> _tU32_: Get the base vertex index. 
- __iDrawOperation::SetMatrix__(_const sMatrixf&_ apMatrix) -> _void_: Set the matrix. 
- __iDrawOperation::GetMatrix__() -> _sMatrixf_: Get the matrix. 
- __iDrawOperation::SetMaterial__(_iMaterial\*_ apMaterial) -> _void_: Set the material. 
- __iDrawOperation::GetMaterial__() -> _iMaterial\*_: Get the material. 
- __iDrawOperation::SetLocalBoundingVolume__(_iBoundingVolume\*_ apBV) -> _void_: Set the bounding volume. 
- __iDrawOperation::GetLocalBoundingVolume__() -> _iBoundingVolume\*_: Get the bounding volume in local space. 
- __iDrawOperation::GetBoundingVolume__() -> _iBoundingVolume\*_: Get the bounding volume in world space. 
- __iDrawOperation::GetCenter__() -> _sVec3f_: Get the center position. 
- __iDrawOperation::GetFVF__() -> _tFVF_: Get the FVF of the draw operation. 

## interface ni::iDrawOperationSet
Draw operation set. 

### Parents:
- iUnknown

### Methods:
- __iDrawOperationSet::Clear__() -> _void_: Clear the operation set. 
- __iDrawOperationSet::Insert__(_iDrawOperation\*_ apDO) -> _iDrawOperation\*_: Insert a draw operation in the set. 
- __iDrawOperationSet::InsertSet__(_const iDrawOperationSet\*_ apSet) -> _tBool_: Insert another set in the set. 
- __iDrawOperationSet::GetNumDrawOperations__() -> _tU32_: Get the number of elements in the set. 
- __iDrawOperationSet::Begin__() -> _iDrawOperation\*_: Go to the first iterator and returns it. 
- __iDrawOperationSet::Next__() -> _iDrawOperation\*_: Move to the next draw op and returns it. 
- __iDrawOperationSet::IsEnd__() -> _tBool_: Return eTrue if the iterator is the end of the set. 
- __iDrawOperationSet::GetCurrent__() -> _iDrawOperation\*_: Get the current iterator. 
- __iDrawOperationSet::GetIsEmpty__() -> _tBool_: Check whether the draw operation set is empty. 
- __iDrawOperationSet::Draw__(_iGraphicsContext\*_ apContext, _iFrustum\*_ apFrustum) -> _tU32_: Draw all draw operation of the set with specified graphics context. 
- __iDrawOperationSet::XDraw__(_const sMatrixf&_ aMatrix, _iGraphicsContext\*_ apContext, _iFrustum\*_ apFrustum) -> _tU32_: Draw all draw operation of the set with specified graphics context and matrix set on each draw op. 

## interface ni::iDrawOperationSet
Draw operation set. 

### Parents:
- iUnknown

### Methods:
- __iDrawOperationSet::Clear__() -> _void_: Clear the operation set. 
- __iDrawOperationSet::Insert__(_iDrawOperation\*_ apDO) -> _iDrawOperation\*_: Insert a draw operation in the set. 
- __iDrawOperationSet::InsertSet__(_const iDrawOperationSet\*_ apSet) -> _tBool_: Insert another set in the set. 
- __iDrawOperationSet::GetNumDrawOperations__() -> _tU32_: Get the number of elements in the set. 
- __iDrawOperationSet::Begin__() -> _iDrawOperation\*_: Go to the first iterator and returns it. 
- __iDrawOperationSet::Next__() -> _iDrawOperation\*_: Move to the next draw op and returns it. 
- __iDrawOperationSet::IsEnd__() -> _tBool_: Return eTrue if the iterator is the end of the set. 
- __iDrawOperationSet::GetCurrent__() -> _iDrawOperation\*_: Get the current iterator. 
- __iDrawOperationSet::GetIsEmpty__() -> _tBool_: Check whether the draw operation set is empty. 
- __iDrawOperationSet::Draw__(_iGraphicsContext\*_ apContext, _iFrustum\*_ apFrustum) -> _tU32_: Draw all draw operation of the set with specified graphics context. 
- __iDrawOperationSet::XDraw__(_const sMatrixf&_ aMatrix, _iGraphicsContext\*_ apContext, _iFrustum\*_ apFrustum) -> _tU32_: Draw all draw operation of the set with specified graphics context and matrix set on each draw op. 

## enum ni::eFontFormatFlags
Font format flags. 

### Values:
- __eFontFormatFlags_CenterH__ = __niBit(0)__: Text will be horizontally centered. 
- __eFontFormatFlags_CenterV__ = __niBit(1)__: Text will be vertically centered. 
- __eFontFormatFlags_Right__ = __niBit(2)__: Text will be right aligned. 
- __eFontFormatFlags_Bottom__ = __niBit(3)__: Text will be bottom aligned. 
- __eFontFormatFlags_ClipH__ = __niBit(4)__: Clip text horizontally. 
- __eFontFormatFlags_ClipV__ = __niBit(5)__: Clip text vertically. 
- __eFontFormatFlags_Border__ = __niBit(6)__: Draw a border around the text. 
- __eFontFormatFlags_Kerning__ = __niBit(7)__: Use kerning if available in the font. 
- __eFontFormatFlags_NoUnitSnap__ = __niBit(8)__: Dont snap to the unit grid after layout. 

## enum ni::eFontLoadFlags
Get font flags. 

### Values:
- __eFontLoadFlags_Registered__ = __niBit(0)__: Search in the registered fonts. 
- __eFontLoadFlags_SystemFirst__ = __niBit(1)__: Search in the system fonts before searching in the registered fonts. 
- __eFontLoadFlags_SystemLast__ = __niBit(2)__: Search in the system fonts after searching in the registered fonts. 
- __eFontLoadFlags_ClosestMatch__ = __niBit(3)__: Look for the closest match in the name. 
- __eFontLoadFlags_Bold__ = __niBit(4)__: Get bold font. 
- __eFontLoadFlags_Italic__ = __niBit(5)__: Get italic font. 
- __eFontLoadFlags_Default__ = __eFontLoadFlags_Registered|eFontLoadFlags_SystemLast|eFontLoadFlags_ClosestMatch__: Default flags. 

## interface ni::iFont
Font interface. 

### Parents:
- iUnknown

### Methods:
- __iFont::GetName__() -> _iHString\*_: Get the name of the font. 
- __iFont::GetFamilyName__() -> _iHString\*_: Get the family name of the font. 
- __iFont::GetStyleName__() -> _iHString\*_: Get the style name of the font. 
- __iFont::GetFilePath__() -> _iHString\*_: Get the file path of the font. 
- __iFont::GetIsFixedResolution__() -> _tBool_: Return eTrue if the pixel size if fixed. 
- __iFont::GetHasKerning__() -> _tBool_: Return eTrue if the font has kerning informations. 
- __iFont::GetMaxResolution__() -> _tU32_: Return the maximum pixel size. 
- __iFont::GetIsInstance__() -> _tBool_: Return eTrue if this font is an instance. 
- __iFont::CreateFontInstance__(_iMaterial\*_ apMaterial) -> _iFont\*_: Create an instance of this font. 
- __iFont::SetTabSize__(_tU32_ ulNumChar) -> _void_: Set the tabulation size. 
- __iFont::GetTabSize__() -> _tU32_: Get the tabulation size. 
- __iFont::SetFiltering__(_tBool_ abLinear) -> _void_: Set the filtering mode. 
- __iFont::GetFiltering__() -> _tBool_: Get the filtering mode. 
- __iFont::SetColor__(_tU32_ anColor) -> _void_: Set the default font color. 
- __iFont::GetColor__() -> _tU32_: Get the default font color. 
- __iFont::SetBlendMode__(_eBlendMode_ aMode) -> _void_: Set the blending mode. 
- __iFont::GetBlendMode__() -> _eBlendMode_: Get the blending mode. 
- __iFont::SetSizeAndResolution__(_const sVec2f&_ avSize, _const tU32_ anResolution, _const tF32_ afContentsScale) -> _void_: Set the font size and resolution taking into account the contents scale. 
- __iFont::GetResolution__() -> _tU32_: Get the character's resolution. 
- __iFont::GetSize__() -> _sVec2f_: Get the character rendering size. 
- __iFont::SetDistanceField__(_tBool_ abDistanceField) -> _void_: Set whether the glyphs are using a distance field. 
- __iFont::GetDistanceField__() -> _tBool_: Get whether the glyphs are using a distance field. 
- __iFont::GetCharWidth__(_tU32_ c) -> _tF32_: Return the width of a character. 
- __iFont::GetCharHeight__(_tU32_ c) -> _tF32_: Return the height of a character. 
- __iFont::GetMaxCharWidth__() -> _tF32_: Return the maximum char width. 
- __iFont::GetMaxCharHeight__() -> _tF32_: Return the maximum char height. 
- __iFont::GetAverageCharWidth__() -> _tF32_: Return the average char width. 
- __iFont::GetAverageCharHeight__() -> _tF32_: Return the average char height. 
- __iFont::GetAscent__() -> _tF32_: Get the ascent (units above the base line) of characters. 
- __iFont::GetDescent__() -> _tF32_: Get the descent (units below the base line) of characters. 
- __iFont::GetHeight__() -> _tF32_: Get the height of the font (ascent + descent + linegap). 
- __iFont::GetFirstChar__() -> _tU32_: Get the value of the first character defined in the font. 
- __iFont::GetLastChar__() -> _tU32_: Get the value of the last character defined in the font. 
- __iFont::GetAdvance__(_tU32_ anChar) -> _tF32_: Get the advance for the specified character. 
- __iFont::GetKerning__(_tU32_ anPrevChar, _tU32_ anChar) -> _tF32_: Get the kerning for the specified character. 
- __iFont::SetLineSpacing__(_const tF32_ afSpacing) -> _void_: Set the normalized line spacing. 
- __iFont::GetLineSpacing__() -> _tF32_: Get the normalized spacing a line. 
- __iFont::GetLineHeight__() -> _tF32_: Get the a line's height. 
- __iFont::UpdateMaterial__(_tBool_ abUpdateMaterialStates) -> _tBool_: Update the font's material. 
- __iFont::CacheText__(_const achar\*_ aaszText) -> _tBool_: Cache the caracters contained in the passed string. 
- __iFont::CacheRange__(_tU32_ anFirst, _tU32_ anLast) -> _tBool_: Cache a range of character. 
- __iFont::ClearCache__() -> _tBool_: Clear the glyph and texture caches. 
- __iFont::GetCacheID__() -> _tIntPtr_: Get the ID of the current cache. 
- __iFont::GetMaterial__() -> _iMaterial\*_: Get the material used for the font's rendering. 
- __iFont::GetCharTexCoo__(_tU32_ c) -> _sRectf_: Get the texture coordinate of a character. 
- __iFont::GetCharTexture__(_tU32_ anChar) -> _iTexture\*_: Get the texture in which the specified glyph is cached. 
- __iFont::GetCharBitmap__(_tU32_ anChar) -> _iBitmap2D\*_: Get the bitmaps in which the specified glyph is cached. 
- __iFont::BlitChar__(_iBitmap2D\*_ apBmp, _tI32_ anX, _tI32_ anY, _tU32_ anChar) -> _sVec2i_: Blit a character to the specified bitmap using the pixel size. 
- __iFont::BlitCharStretch__(_iBitmap2D\*_ apBmp, _tI32_ anX, _tI32_ anY, _tU32_ anChar) -> _sVec2i_: Blit a character to the specified bitmap to the current font size. 
- __iFont::BlitCharEx__(_iBitmap2D\*_ apBmp, _tI32_ anX, _tI32_ anY, _tI32_ anW, _tI32_ anH, _tU32_ anChar, _eBlendMode_ aBlendMode) -> _sVec2i_: Blit a character to the specified bitmap with the specified size and blend mode. 
- __iFont::ComputeTextSize__(_const sRectf&_ aRect, _const achar\*_ aaszText, _tFontFormatFlags_ aFormat) -> _sRectf_: Compute text size in pixels. 
- __iFont::DrawText__(_ni::iCanvas\*_ apCanvas, _const sRectf&_ aposRect, _tF32_ afZ, _const achar\*_ aaszText, _tFontFormatFlags_ aFormat) -> _sRectf_: Draw text layed out in the specified rectangle. 
- __iFont::GetGlyphIndexFromName__(_const achar\*_ aaszName) -> _tU32_: Get the glyph index from its name. 
- __iFont::GetGlyphIndexFromCodepoint__(_const tU32_ anCodepoint) -> _tU32_: Get the glyph index from its codepoint. 
- __iFont::GetGlyphName__(_const tU32_ anGlyphIndex) -> _cString_: Get the glyph name from its codepoint. 
- __iFont::EnumGlyphs__() -> _Ptr<tU32CMap>_: Enumerate all the glyphs with a codepoint in the font. 
- __iFont::GetGlyphCodePointFromName__(_const achar\*_ aaszName) -> _tU32_: Get the glyph's codepoint from its name. 
- __iFont::GetGlyphPath__(_iVGPath\*_ apPath, _tU32_ anGlyphIndex, _const sVec2f&_ avOffset, _const tF32_ afScale) -> _sVec2f_: Get a glyph's outline to the specified path. 

## enum ni::eFontFormatFlags
Font format flags. 

### Values:
- __eFontFormatFlags_CenterH__ = __niBit(0)__: Text will be horizontally centered. 
- __eFontFormatFlags_CenterV__ = __niBit(1)__: Text will be vertically centered. 
- __eFontFormatFlags_Right__ = __niBit(2)__: Text will be right aligned. 
- __eFontFormatFlags_Bottom__ = __niBit(3)__: Text will be bottom aligned. 
- __eFontFormatFlags_ClipH__ = __niBit(4)__: Clip text horizontally. 
- __eFontFormatFlags_ClipV__ = __niBit(5)__: Clip text vertically. 
- __eFontFormatFlags_Border__ = __niBit(6)__: Draw a border around the text. 
- __eFontFormatFlags_Kerning__ = __niBit(7)__: Use kerning if available in the font. 
- __eFontFormatFlags_NoUnitSnap__ = __niBit(8)__: Dont snap to the unit grid after layout. 

## enum ni::eFrustumPlane
Frustum planes. 

### Values:
- __eFrustumPlane_Left__ = __0__: Left frustum plane. 
- __eFrustumPlane_Right__ = __1__: Right frustum plane. 
- __eFrustumPlane_Top__ = __2__: Top frustum plane. 
- __eFrustumPlane_Bottom__ = __3__: Bottom frustum plane. 
- __eFrustumPlane_Near__ = __4__: Near frustum plane. 
- __eFrustumPlane_Far__ = __5__: Far frustum plane. 

## enum ni::eCullCode
Value return by the culling functions. 

### Values:
- __eCullCode_Out__ = __0__
- __eCullCode_In__ = __1__
- __eCullCode_Intersect__ = __2__

## interface ni::iFrustum


### Parents:
- iUnknown

### Methods:
- __iFrustum::Clone__() -> _iFrustum\*_: Create a copy of this object. 
- __iFrustum::Copy__(_const iFrustum\*_ apSrc) -> _void_: Copy the given frustum. 
- __iFrustum::GetForward__() -> _sVec3f_: Get the forward vector of the frustum. 
- __iFrustum::GetUp__() -> _sVec3f_: Get the up vector of the frustum. 
- __iFrustum::GetRight__() -> _sVec3f_: Get the right vector of the frustum. 
- __iFrustum::ExtractPlanes__(_const sMatrixf&_ mtxVP) -> _void_: Extract the planes from a view projection matrix. 
- __iFrustum::SetNumPlanes__(_tU32_ ulNumPlane) -> _void_: Set the number of plane in the frustum. 
- __iFrustum::GetNumPlanes__() -> _tU32_: Get the number of planes in the frustum. 
- __iFrustum::AddPlanes__(_tU32_ aulNumPlane, _const sPlanef\*_ apPlanes) -> _void_: Add the given number of planes to the frustum. 
- __iFrustum::AddPlane__(_const sPlanef&_ aPlane) -> _void_: Add one plane to the frustum. 
- __iFrustum::SetPlanes__(_tU32_ aulNumPlane, _const sPlanef\*_ apPlanes) -> _void_: Set all planes of the frustum. 
- __iFrustum::SetPlane__(_tU32_ ulIdx, _const sPlanef&_ Plane) -> _void_: Set the plane of the given index. 
- __iFrustum::GetPlane__(_tU32_ ulIdx) -> _sPlanef_: Get the plane of the given index. 
- __iFrustum::GetPlanes__() -> _sPlanef\*_: Get all planes. 
- __iFrustum::CullAABB__(_const sVec3f&_ avMin, _const sVec3f&_ avMax) -> _eCullCode_: Cull an AABB. 
- __iFrustum::IntersectAABB__(_const sVec3f&_ avMin, _const sVec3f&_ avMax) -> _tBool_: Check if the given AABB is in the frustum. 
- __iFrustum::CullSphere__(_const sVec3f&_ avCenter, _tF32_ afRadius) -> _eCullCode_: Cull a sphere. 
- __iFrustum::IntersectSphere__(_const sVec3f&_ avCenter, _tF32_ afRadius) -> _tBool_: Check if the given sphere is in the frustum. 
- __iFrustum::Transform__(_const sMatrixf&_ M) -> _tBool_: Transform the frustum by the given matrix. 
- __iFrustum::ComputeScreenBoundingBox__(_const sMatrixf&_ amtxWVP, _const sRectf&_ aViewport) -> _sRectf_: Compute the screen bounding box. 
- __iFrustum::SetBoundingVolume__(_iBoundingVolume\*_ apBV) -> _tBool_: Set the world bounding volume. 
- __iFrustum::GetBoundingVolume__() -> _iBoundingVolume\*_: Get the world bounding volume. 

## enum ni::eFrustumPlane
Frustum planes. 

### Values:
- __eFrustumPlane_Left__ = __0__: Left frustum plane. 
- __eFrustumPlane_Right__ = __1__: Right frustum plane. 
- __eFrustumPlane_Top__ = __2__: Top frustum plane. 
- __eFrustumPlane_Bottom__ = __3__: Bottom frustum plane. 
- __eFrustumPlane_Near__ = __4__: Near frustum plane. 
- __eFrustumPlane_Far__ = __5__: Far frustum plane. 

## enum ni::eGeometryGenerate
Geometry generation. 

### Values:
- __eGeometryGenerate_Adjacency__ = __niBit(0)__: Generate adjacency informations. 
- __eGeometryGenerate_FlatNormals__ = __niBit(1)__: Generate flat normals. 
- __eGeometryGenerate_Normals__ = __niBit(2)__: Generate the normals (overrirde flat normals computation). 

## enum ni::eGeometryType
Geometry types. 

### Values:
- __eGeometryType_Polygonal__ = __0__: Polygonal geometry. 
- __eGeometryType_Patch__ = __1__: Patch geometry. 
- __eGeometryType_Progressive__ = __2__: Progressive geometry. 

## enum ni::eGeometryCreateFlags
Geometry creation flags. 

### Values:
- __eGeometryCreateFlags_VADynamic__ = __niBit(0)__: The vertex array usage is dynamic. 
- __eGeometryCreateFlags_VADynamicReadWrite__ = __niBit(1)__: The vertex array usage is dynamic read write. 
- __eGeometryCreateFlags_VAStatic__ = __niBit(2)__: The vertex array usage is static. 
- __eGeometryCreateFlags_VASystemMemory__ = __niBit(3)__: The vertex array usage is system memory. 
- __eGeometryCreateFlags_IADynamic__ = __niBit(4)__: The index array usage is dynamic. 
- __eGeometryCreateFlags_IADynamicReadWrite__ = __niBit(5)__: The index array usage is dynamic read write. 
- __eGeometryCreateFlags_IAStatic__ = __niBit(6)__: The index array usage is static. 
- __eGeometryCreateFlags_IASystemMemory__ = __niBit(7)__: The index array usage is system memory. 
- __eGeometryCreateFlags_Dynamic__ = __eGeometryCreateFlags_VADynamic|eGeometryCreateFlags_IADynamic__: The vertex array and index array usage is dynamic. 
- __eGeometryCreateFlags_DynamicReadWrite__ = __eGeometryCreateFlags_VADynamicReadWrite|eGeometryCreateFlags_IADynamicReadWrite__: The vertex array and index array usage is dynamic read write. 
- __eGeometryCreateFlags_Static__ = __eGeometryCreateFlags_VAStatic|eGeometryCreateFlags_IAStatic__: The vertex array and index array usage is static. 
- __eGeometryCreateFlags_SystemMemory__ = __eGeometryCreateFlags_VASystemMemory|eGeometryCreateFlags_IASystemMemory__: The vertex array and index array usage is system memory. 

## enum ni::eGeometryOptimizeFlags
Geometry optimization flags. 

### Values:
- __eGeometryOptimizeFlags_RemoveDegenerates__ = __niBit(0)__: Remove degenerate triangles. 
- __eGeometryOptimizeFlags_RemoveUnusedVertices__ = __niBit(1)__: Remove unused vertices. 
- __eGeometryOptimizeFlags_RemoveDuplicateVertices__ = __niBit(2)__: Remove duplicate vertices. 
- __eGeometryOptimizeFlags_Default__ = __eGeometryOptimizeFlags_RemoveDegenerates|eGeometryOptimizeFlags_RemoveUnusedVertices__: Default. 
- __eGeometryOptimizeFlags_All__ = __eGeometryOptimizeFlags_RemoveDegenerates|eGeometryOptimizeFlags_RemoveUnusedVertices|eGeometryOptimizeFlags_RemoveDuplicateVertices__: Default. 

## interface ni::iGeometrySubset
Geometry subset interface. 

### Parents:
- iUnknown

### Methods:
- __iGeometrySubset::SetID__(_tU32_ anID) -> _void_: Set the ID of the subset. 
- __iGeometrySubset::GetID__() -> _tU32_: Get the ID of the subset. 
- __iGeometrySubset::SetFirstIndex__(_tU32_ anFirstIndex) -> _void_: Set the first index of the subset. 
- __iGeometrySubset::GetFirstIndex__() -> _tU32_: Get the first index of the subset. 
- __iGeometrySubset::SetNumIndices__(_tU32_ anNumIndices) -> _void_: Set the number of indices of the subset. 
- __iGeometrySubset::GetNumIndices__() -> _tU32_: Get the number of indices of the subset. 
- __iGeometrySubset::SetMaterial__(_tU32_ anMaterial) -> _void_: Set the material ID of the subset. 
- __iGeometrySubset::GetMaterial__() -> _tU32_: Get the material ID of the subset. 

## interface ni::iGeometry
Geometry base interface. 

### Parents:
- iUnknown

### Methods:
- __iGeometry::GetType__() -> _eGeometryType_: Geometry type. 
- __iGeometry::GetVertexArray__() -> _iVertexArray\*_: Get the constant vertex array of this geometry. 
- __iGeometry::GetIndexArray__() -> _iIndexArray\*_: Get the constant index array of this geometry. 
- __iGeometry::Generate__(_eGeometryGenerate_ aGenerate, _tF32_ fEpsilon) -> _tBool_: Generate the specified things. 
- __iGeometry::GetNumFaces__() -> _tU32_: Get the number of face contained in the mesh. 
- __iGeometry::SetFacesSubsetsIDs__(_const tU32\*_ apIDs) -> _void_: Set the faces subset's IDs. 
- __iGeometry::GetFacesSubsetsIDs__() -> _const tU32\*_: Get the faces subsets IDs. 
- __iGeometry::GetAdjacencyArray__() -> _const tU32\*_: Get the adjacency array. 
- __iGeometry::GetNumSubsets__() -> _tU32_: Get the number of subsets. 
- __iGeometry::GetSubset__(_tU32_ aulIdx) -> _iGeometrySubset\*_: Get the subset at the specified index. 
- __iGeometry::GetSubsetIndex__(_tU32_ aulID) -> _tU32_: Get the index of the subset with the specified ID. 
- __iGeometry::AddSubset__(_tU32_ anID, _tU32_ anFirstIndex, _tU32_ anNumIndices, _tU32_ anMaterial) -> _iGeometrySubset\*_: Add a subset. 
- __iGeometry::RemoveSubset__(_tU32_ aulIdx) -> _tBool_: Remove the subset at the given index. 
- __iGeometry::Clone__(_tGeometryCreateFlags_ aFlags, _tFVF_ aFVF) -> _iGeometry\*_: Create a copy of this geometry. 
- __iGeometry::SetDrawOp__(_iDrawOperation\*_ apDrawOp, _tU32_ aulSubsetIdx) -> _tBool_: Set the specified draw operation to draw the specified subset. 
- __iGeometry::Optimize__(_tGeometryOptimizeFlags_ aFlags) -> _tBool_: Optimize the mesh. 

## interface ni::iGeometryModifier
Geometry modifier interface. 

### Parents:
- iUnknown

### Methods:
- __iGeometryModifier::SetGeometry__(_iGeometry\*_ pGeometry) -> _tBool_: Set the geometry to modify. 
- __iGeometryModifier::GetGeometry__() -> _iGeometry\*_: Get the constant geometry that this modifier modifies. 
- __iGeometryModifier::GetModifiedGeometry__() -> _iGeometry\*_: Return the modified geometry. 
- __iGeometryModifier::Update__() -> _tBool_: Update the modified geometry. 

## enum ni::eGeometryGenerate
Geometry generation. 

### Values:
- __eGeometryGenerate_Adjacency__ = __niBit(0)__: Generate adjacency informations. 
- __eGeometryGenerate_FlatNormals__ = __niBit(1)__: Generate flat normals. 
- __eGeometryGenerate_Normals__ = __niBit(2)__: Generate the normals (overrirde flat normals computation). 

## interface ni::iGraphics
Graphics interface 

### Parents:
- iUnknown

### Methods:
- __iGraphics::FVFGetTexCooDim__(_tFVF_ anFVF, _tU32_ anTexCooIndex) -> _tU32_: Get the number of dimensions of the specified texture coordinates. anTexCooIndex is the index (0 to 7). 
- __iGraphics::FVFGetNumTexCoos__(_tFVF_ anFVF) -> _tU32_: Get the number of texture coordinates of the specified FVF. 
- __iGraphics::FVFToString__(_tFVF_ aFVF) -> _cString_: Convert the specified FVF to a string. 
- __iGraphics::FVFFromString__(_const achar\*_ aaszString) -> _tFVF_: Get a FVF from the specified string. 
- __iGraphics::FVFGetComponentOffset__(_tFVF_ aFVF, _eFVF_ C) -> _tU32_: Get the offset of the specified component. 
- __iGraphics::FVFGetStride__(_tFVF_ aFVF) -> _tU32_: Get the size of a FVF. 
- __iGraphics::CreatePixelFormat__(_const achar\*_ aszFormat) -> _iPixelFormat\*_: Create a pixel format. 
- __iGraphics::CreateBitmapFormat__(_eBitmapType_ aType, _const achar\*_ aaszFormat, _tU32_ anNumMipMaps, _tU32_ anWidth, _tU32_ anHeight, _tU32_ anDepth) -> _iBitmapFormat\*_: Create a new bitmap format. 
- __iGraphics::CreateBitmapFormatEx__(_eBitmapType_ aType, _iPixelFormat\*_ pFmt, _tU32_ anNumMipMaps, _tU32_ anWidth, _tU32_ anHeight, _tU32_ anDepth) -> _iBitmapFormat\*_: Create a new bitmap format. 
- __iGraphics::CreateBitmapFormatEmpty__() -> _iBitmapFormat\*_: Create a new empty bitmap format. 
- __iGraphics::CreateBitmap__(_iHString\*_ ahspName, _eBitmapType_ aType, _const achar\*_ aaszFormat, _tU32_ anNumMipMaps, _tU32_ anWidth, _tU32_ anHeight, _tU32_ anDepth) -> _iBitmapBase\*_: Create a new bitmap. 
- __iGraphics::CreateBitmapEx__(_iHString\*_ ahspName, _eBitmapType_ aType, _iPixelFormat\*_ pFmt, _tU32_ anNumMipMaps, _tU32_ anWidth, _tU32_ anHeight, _tU32_ anDepth) -> _iBitmapBase\*_: Create a new bitmap. 
- __iGraphics::CreateBitmap2DEx__(_tU32_ nW, _tU32_ nH, _iPixelFormat\*_ pFmt) -> _iBitmap2D\*_: Create a 2D bitmap. 
- __iGraphics::CreateBitmap2D__(_tU32_ nW, _tU32_ nH, _const achar\*_ aszPixFmt) -> _iBitmap2D\*_: Create a 2D bitmap. 
- __iGraphics::CreateBitmap2DMemoryEx__(_tU32_ nW, _tU32_ nH, _iPixelFormat\*_ pFmt, _tU32_ anPitch, _tPtr_ ptrAddr, _tBool_ bFreeAddr) -> _iBitmap2D\*_: Create a 2D bitmap from the specified memory. 
- __iGraphics::CreateBitmap2DMemory__(_tU32_ nW, _tU32_ nH, _const achar\*_ aszPixFmt, _tU32_ anPitch, _tPtr_ ptrAddr, _tBool_ bFreeAddr) -> _iBitmap2D\*_: Create a 2D bitmap from the specified memory. 
- __iGraphics::CreateBitmapCubeEx__(_tU32_ ulSize, _iPixelFormat\*_ pFmt) -> _iBitmapCube\*_: Create a Cube bitmap. 
- __iGraphics::CreateBitmapCube__(_tU32_ ulSize, _const achar\*_ aszPixFmt) -> _iBitmapCube\*_: Create a Cube bitmap. 
- __iGraphics::CreateBitmap3DEx__(_tU32_ anW, _tU32_ anH, _tU32_ anD, _iPixelFormat\*_ apFmt) -> _iBitmap3D\*_: Create a 3D bitmap. 
- __iGraphics::CreateBitmap3D__(_tU32_ anW, _tU32_ anH, _tU32_ anD, _const achar\*_ aaszPixFmt) -> _iBitmap3D\*_: Create a 3D bitmap. 
- __iGraphics::CreateBitmap3DMemoryEx__(_tU32_ anW, _tU32_ anH, _tU32_ anD, _iPixelFormat\*_ apFmt, _tU32_ anRowPitch, _tU32_ anSlicePitch, _tPtr_ aptrAddr, _tBool_ abFreeAddr) -> _iBitmap3D\*_: Create a 3D bitmap from the specified memory. 
- __iGraphics::CreateBitmap3DMemory__(_tU32_ anW, _tU32_ anH, _tU32_ anD, _const achar\*_ aszPixFmt, _tU32_ anRowPitch, _tU32_ anSlicePitch, _tPtr_ aptrAddr, _tBool_ abFreeAddr) -> _iBitmap3D\*_: Create a 3D bitmap from the specified memory. 
- __iGraphics::LoadBitmap__(_iFile\*_ pFile) -> _iBitmapBase\*_: Load a bitmap from a file. 
- __iGraphics::LoadBitmapFromRes__(_iHString\*_ ahspRes, _iHString\*_ ahspBasePath) -> _iBitmapBase\*_: Load a bitmap from a resource. 
- __iGraphics::LoadBitmapEx__(_const achar\*_ aaszFormat, _iFile\*_ pFile) -> _iBitmapBase\*_: Load a bitmap from a file with the specified format. 
- __iGraphics::SaveBitmap__(_const achar\*_ aszFile, _iBitmapBase\*_ pBmp, _tU32_ ulCompression) -> _tBool_: Save a bitmap in a file. 
- __iGraphics::SaveBitmapEx__(_const achar\*_ aaszFormat, _iFile\*_ apFile, _iBitmapBase\*_ apBmp, _tU32_ anCompression) -> _tBool_: Save a bitmap in the specified format in a file. 
- __iGraphics::URLFindBitmapFilePath__(_const achar\*_ aszRes, _const achar\*_ aszBasePath) -> _cString_: Find the path/url matching the specified resource and basepath. 
- __iGraphics::OpenBitmapFile__(_const achar\*_ aszRes, _const achar\*_ aszBasePath) -> _iFile\*_: Open a bitmap file. 
- __iGraphics::ComputeBitmapDiff__(_const iBitmap2D\*_ apImgA, _const iBitmap2D\*_ apImgB, _iBitmap2D\*_ apOutput, _tF64_ afThreshold, _tBool_ abIgnoreAA) -> _tI64_: Computes the diff between two bitmaps. 
- __iGraphics::CreateGeometryPolygonal__(_tU32_ aulNumVertices, _tU32_ aulNumIndices, _tGeometryCreateFlags_ aFlags, _tFVF_ aFVF) -> _iGeometry\*_: Create a polygonal geometry. 
- __iGraphics::CreateGeometryPolygonalEx__(_iVertexArray\*_ apVA, _iIndexArray\*_ apIA) -> _iGeometry\*_: Create a polygonal geometry from an exisiting vertex array and index array. 
- __iGraphics::CreateGeometryModifier__(_const achar\*_ aszName, _iGeometry\*_ apGeometry, _iUnknown\*_ apInitData) -> _iGeometryModifier\*_: Create a geometry modifier. 
- __iGraphics::CreateGeometryPolygonalCube__(_tGeometryCreateFlags_ aFlags, _tFVF_ aFVF, _const sVec3f&_ avCenter, _tF32_ afWidth, _tBool_ abCW, _tU32_ aulColor, _const sMatrixf&_ amtxUV) -> _iGeometry\*_: Create a cube polygonal geometry. 
- __iGraphics::CreateGeometryPolygonalPlane__(_tGeometryCreateFlags_ aFlags, _tFVF_ aFVF, _ePlaneType_ aPlaneType, _const sVec3f&_ avCenter, _tF32_ afWidth, _tF32_ afHeight, _tU32_ aulNumDiv, _tBool_ abCW, _tU32_ aulColor, _const sMatrixf&_ amtxUV) -> _iGeometry\*_: Create a plane polygonal geometry. 
- __iGraphics::CreateGeometryPolygonalCylinder__(_tGeometryCreateFlags_ aFlags, _tFVF_ aFVF, _tF32_ baseRadius, _tF32_ topRadius, _tF32_ height, _tI32_ slices, _tI32_ stacks, _tBool_ abCW, _tU32_ aulColor, _const sMatrixf&_ amtxUV, _tBool_ abCap, _tBool_ abCentered) -> _iGeometry\*_: Create a cylinder polygonal geometry. 
- __iGraphics::CreateGeometryPolygonalSphere__(_tGeometryCreateFlags_ aFlags, _tFVF_ aFVF, _tF32_ radius, _tI32_ slices, _tI32_ stacks, _tBool_ abCW, _tU32_ aulColor, _const sMatrixf&_ amtxUV) -> _iGeometry\*_: Create a sphere polygonal geometry. 
- __iGraphics::CreateGeometryPolygonalGeosphere__(_tGeometryCreateFlags_ aFlags, _tFVF_ aFVF, _tF32_ radius, _tI32_ slices, _tBool_ abCW, _tU32_ aulColor, _const sMatrixf&_ amtxUV) -> _iGeometry\*_: Create a geosphere polygonal geometry. 
- __iGraphics::CreateGeometryPolygonalDiskSweep__(_tGeometryCreateFlags_ aFlags, _tFVF_ aFVF, _tF32_ innerRadius, _tF32_ outerRadius, _tI32_ slices, _tI32_ stacks, _tF32_ startAngle, _tF32_ sweepAngle, _tBool_ abCW, _tU32_ aulColor, _const sMatrixf&_ amtxUV) -> _iGeometry\*_: Create a disk sweep polygonal geometry. 
- __iGraphics::UpdateGeometryPolygonalDiskSweep__(_iGeometry\*_ apGeom, _tF32_ innerRadius, _tF32_ outerRadius, _tI32_ slices, _tI32_ stacks, _tF32_ startAngle, _tF32_ sweepAngle, _tBool_ abCW, _tU32_ aulColor, _const sMatrixf&_ amtxUV) -> _tBool_: Update a disk polygonal geometry. 
- __iGraphics::CreateGeometryPolygonalDisk__(_tGeometryCreateFlags_ aFlags, _tFVF_ aFVF, _tF32_ innerRadius, _tF32_ outerRadius, _tI32_ slices, _tI32_ stacks, _tBool_ abCW, _tU32_ aulColor, _const sMatrixf&_ amtxUV) -> _iGeometry\*_: Create a disk polygonal geometry. 
- __iGraphics::InitializeDriver__(_iHString\*_ ahspDriverName) -> _tBool_: Initialize the specified hardware driver. 
- __iGraphics::GetIsDriverInitialized__() -> _tBool_: Get whether the driver has been initialized. 
- __iGraphics::GetDriver__() -> _iGraphicsDriver\*_: Get the driver that has been initialized. 
- __iGraphics::GetDriverCaps__(_eGraphicsCaps_ aCaps) -> _tInt_: Get the driver's capabilities. 
- __iGraphics::CreateContextForWindow__(_iOSWindow\*_ apWindow, _const achar\*_ aaszBBFormat, _const achar\*_ aaszDSFormat, _tU32_ anSwapInterval, _tTextureFlags_ aBackBufferFlags) -> _iGraphicsContext\*_: Create a new context for the specified OS window. 
- __iGraphics::CreateContextForRenderTargets__(_iTexture\*_ apRT0, _iTexture\*_ apRT1, _iTexture\*_ apRT2, _iTexture\*_ apRT3, _iTexture\*_ apDS) -> _iGraphicsContextRT\*_: Creates a new context for the specified render targets. 
- __iGraphics::GetGenericDeviceResourceManager__() -> _iDeviceResourceManager\*_: Get the generice device resource manager. 
- __iGraphics::CreateSamplerStates__() -> _iSamplerStates\*_: Create a new sampler states instance. 
- __iGraphics::CreateDepthStencilStates__() -> _iDepthStencilStates\*_: Create a new depth stencil states instance. 
- __iGraphics::CreateRasterizerStates__() -> _iRasterizerStates\*_: Create a new rasterizer states instance. 
- __iGraphics::CreateFixedStates__() -> _iFixedStates\*_: Create a new fixed pipeline states instance. 
- __iGraphics::CheckTextureFormat__(_iBitmapFormat\*_ apFormat, _tTextureFlags_ aFlags) -> _tBool_: Check whether the specified texture format is supported and set the bitmap format object to the nearest matching native bitmap format. 
- __iGraphics::GetTextureDeviceResourceManager__() -> _iDeviceResourceManager\*_: Get the texture device resource manager. 
- __iGraphics::GetNumTextures__() -> _tU32_: Get the number of textures in the manager. 
- __iGraphics::GetTextureFromName__(_iHString\*_ ahspName) -> _iTexture\*_: Get a texture from its name. 
- __iGraphics::GetTextureFromIndex__(_tU32_ anIndex) -> _iTexture\*_: Get a texture from its index. 
- __iGraphics::CreateTexture__(_iHString\*_ ahspName, _eBitmapType_ aType, _const achar\*_ aaszFormat, _tU32_ anNumMipMaps, _tU32_ anWidth, _tU32_ anHeight, _tU32_ anDepth, _tTextureFlags_ aFlags) -> _iTexture\*_: Create a new texture. 
- __iGraphics::CreateTextureFromBitmap__(_iHString\*_ ahspName, _iBitmapBase\*_ apBitmap, _tTextureFlags_ aFlags) -> _iTexture\*_: Create a new texture from the specified bitmap. 
- __iGraphics::CreateTextureFromRes__(_iHString\*_ ahspRes, _iHString\*_ ahspBasePath, _tTextureFlags_ aFlags) -> _iTexture\*_: Create a new texture from the specified resource. 
- __iGraphics::SetRecreateTextureWhenChanged__(_tBool_ abEnabled) -> _void_: Set whether CreateTextureFromRes recreates the texture when the source resource has changed. 
- __iGraphics::GetRecreateTextureWhenChanged__() -> _tBool_: Get whether CreateTextureFromRes recreates the texture when the source resource has changed. 
- __iGraphics::BlitBitmapToTexture__(_iBitmap2D\*_ apSrc, _iTexture\*_ apDest, _tU32_ anDestLevel, _const sRecti&_ aSrcRect, _const sRecti&_ aDestRect, _eTextureBlitFlags_ aFlags) -> _tBool_: Blit a bitmap to a texture. 
- __iGraphics::BlitTextureToBitmap__(_iTexture\*_ apSrc, _tU32_ anSrcLevel, _iBitmap2D\*_ apDest, _const sRecti&_ aSrcRect, _const sRecti&_ aDestRect, _eTextureBlitFlags_ aFlags) -> _tBool_: Blit a texture to a bitmap. 
- __iGraphics::BlitTextureToTexture__(_iTexture\*_ apSrc, _tU32_ anSrcLevel, _iTexture\*_ apDest, _tU32_ anDestLevel, _const sRecti&_ aSrcRect, _const sRecti&_ aDestRect, _eTextureBlitFlags_ aFlags) -> _tBool_: Blit a texture into another texture. 
- __iGraphics::BlitBitmap3DToTexture__(_iBitmap3D\*_ apSrc, _iTexture\*_ apDest, _tU32_ anDestLevel, _const sVec3i&_ aSrcMin, _const sVec3i&_ aDestMin, _const sVec3i&_ avSize, _eTextureBlitFlags_ aFlags) -> _tBool_: Blit a 3d bitmap to a 3d texture. 
- __iGraphics::BlitTextureToBitmap3D__(_iTexture\*_ apSrc, _tU32_ anSrcLevel, _iBitmap3D\*_ apDest, _const sVec3i&_ aSrcMin, _const sVec3i&_ aDestMin, _const sVec3i&_ avSize, _eTextureBlitFlags_ aFlags) -> _tBool_: Blit a 3d texture to a 3d bitmap. 
- __iGraphics::CreateBitmapFromTexture__(_iTexture\*_ apSrc) -> _iBitmapBase\*_: Create a bitmap from a texture. 
- __iGraphics::GetNumShaderProfile__(_eShaderUnit_ aUnit) -> _tU32_: Get the number of Shader profile supported in the specified unit. 
- __iGraphics::GetShaderProfile__(_eShaderUnit_ aUnit, _tU32_ anIndex) -> _iHString\*_: Get the profile at the specified index. 
- __iGraphics::CreateShaderConstants__(_tU32_ anMaxRegisters) -> _iShaderConstants\*_: Creates an empty shader constants instance. 
- __iGraphics::SerializeShaderConstants__(_iShaderConstants\*_ apConsts, _iDataTable\*_ apDT, _tSerializeFlags_ aFlags) -> _tBool_: Serialize shader constants in the specified datatable. 
- __iGraphics::GetShaderDeviceResourceManager__() -> _iDeviceResourceManager\*_: Get the shader device resource manager. 
- __iGraphics::GetNumShaders__() -> _tU32_: Get the number of shaders in the manager. 
- __iGraphics::GetShaderFromName__(_iHString\*_ ahspName) -> _iShader\*_: Get a shader from its name. 
- __iGraphics::GetShaderFromIndex__(_tU32_ anIndex) -> _iShader\*_: Get a shader from its index. 
- __iGraphics::CreateShader__(_iHString\*_ ahspName, _iFile\*_ apByteCode) -> _iShader\*_: Create a new shader. 
- __iGraphics::CreateShaderFromRes__(_iHString\*_ ahspRes) -> _iShader\*_: Create a new shader from the specified resource. 
- __iGraphics::SetRecreateShaderWhenChanged__(_tBool_ abEnabled) -> _void_: Set whether CreateShaderFromRes recreates the shader when the source resource has changed. 
- __iGraphics::GetRecreateShaderWhenChanged__() -> _tBool_: Get whether CreateShaderFromRes recreates the shader when the source resource has changed. 
- __iGraphics::CreateVertexArray__(_tU32_ anNumVertices, _tFVF_ anFVF, _eArrayUsage_ aUsage) -> _iVertexArray\*_: Create a new driver vertex array instance. 
- __iGraphics::CreateIndexArray__(_eGraphicsPrimitiveType_ aPrimitiveType, _tU32_ anNumIndex, _tU32_ anMaxVertexIndex, _eArrayUsage_ aUsage) -> _iIndexArray\*_: Create a new driver index array instance. 
- __iGraphics::CreateDrawOperation__() -> _iDrawOperation\*_: Creates a new draw operation. 
- __iGraphics::CreateDrawOperationSet__() -> _iDrawOperationSet\*_: Create a draw operation set. 
- __iGraphics::CreateOcclusionQuery__() -> _iOcclusionQuery\*_: Create a new occlusion query object. 
- __iGraphics::CompileSamplerStates__(_iSamplerStates\*_ apStates) -> _tIntPtr_: Compile a sampler states. 
- __iGraphics::GetCompiledSamplerStates__(_tIntPtr_ aHandle) -> _iSamplerStates\*_: Get the specified compiled sampler states. 
- __iGraphics::CompileRasterizerStates__(_iRasterizerStates\*_ apStates) -> _tIntPtr_: Compile a rasterizer states. 
- __iGraphics::GetCompiledRasterizerStates__(_tIntPtr_ aHandle) -> _iRasterizerStates\*_: Get the specified compiled rasterizer states. 
- __iGraphics::CompileDepthStencilStates__(_iDepthStencilStates\*_ apStates) -> _tIntPtr_: Compile a depth stencil states. 
- __iGraphics::GetCompiledDepthStencilStates__(_tIntPtr_ aHandle) -> _iDepthStencilStates\*_: Get the specified compiled depth stencil states. 
- __iGraphics::CreateMaterial__() -> _iMaterial\*_: Create an empty material. 
- __iGraphics::CreateMaterialLibrary__() -> _iMaterialLibrary\*_: Create a material library. 
- __iGraphics::CreateDrawOpCapture__() -> _iGraphicsDrawOpCapture\*_: Create a new draw op capture object. 
- __iGraphics::SetDrawOpCapture__(_iGraphicsDrawOpCapture\*_ apCapture) -> _void_: Set the draw op capture object. 
- __iGraphics::GetDrawOpCapture__() -> _iGraphicsDrawOpCapture\*_: Get the draw op capture object. 
- __iGraphics::ColorLuminance__(_const sVec3f&_ aColor) -> _tF32_: Get the lumiance of a 3d color. 
- __iGraphics::ColorLuminanceEx__(_const sVec3f&_ aColor, _const sVec3f&_ avLuminanceDistribution) -> _tF32_: Get the lumiance of a 3d color, allow to specify a luminance distribution. 
- __iGraphics::ColorGammaCorrect__(_const sVec3f&_ aC, _tF32_ afFactor) -> _sVec3f_: Correct the gamma of a color. 
- __iGraphics::ColorAdjustContrast__(_const sVec3f&_ C, _tF32_ c) -> _sVec3f_: Adjust the contrast of a color. 
- __iGraphics::ColorAdjustSaturation__(_const sVec3f&_ C, _tF32_ s) -> _sVec3f_: Adjust the saturation of a color. 
- __iGraphics::ColorNegative__(_const sVec3f&_ C) -> _sVec3f_: Get the negative of a color. 
- __iGraphics::ColorGrey__(_const sVec3f&_ C) -> _sVec3f_: Gray a color. 
- __iGraphics::ColorBlackWhite__(_const sVec3f&_ C, _tF32_ s) -> _sVec3f_: Set a color to be black or white in function of the specified reference. 
- __iGraphics::ColorConvert__(_eColorSpace_ aSource, _eColorSpace_ aDest, _const sVec4f&_ aColor) -> _sVec4f_: Convert a color from one color space to another. 
- __iGraphics::ColorConvertEx__(_eColorSpace_ aSource, _eColorSpace_ aDest, _const sVec4f&_ aColor, _const sVec4f&_ aXYZRef) -> _sVec4f_: Convert a color from one color space to another, allows to specify the XYZ reference. 
- __iGraphics::GetNumNamedColors__() -> _tU32_: Get the number of named colors. 
- __iGraphics::GetColorName__(_tU32_ anIndex) -> _const achar\*_: Get the name of the color at the specified index. 
- __iGraphics::GetColorIndex__(_iHString\*_ ahspName) -> _tU32_: Get the index of the color with the specified name. 
- __iGraphics::GetColorValue__(_tU32_ anIndex) -> _tU32_: Get the value of the color at the specified index. 
- __iGraphics::FindColorName__(_const sColor4f&_ aColor) -> _const achar\*_: Find the color with the closest match to the specified color. 
- __iGraphics::GetColor3FromName__(_iHString\*_ ahspName) -> _sVec3f_: Get a color from it's name. 
- __iGraphics::GetColor4FromName__(_iHString\*_ ahspName) -> _sVec4f_: Get a color from it's name. 
- __iGraphics::GetColor4FromNameA__(_iHString\*_ ahspName, _tF32_ afAlpha) -> _sVec4f_: Get a color from it's name, specifying the alpha. 
- __iGraphics::GetCssColor3FromName__(_iHString\*_ ahspName) -> _sVec3f_: Get a color from it's name. 
- __iGraphics::GetCssColor4FromName__(_iHString\*_ ahspName) -> _sVec4f_: Get a css color from it's name. 
- __iGraphics::GetCssColor4FromNameA__(_iHString\*_ ahspName, _tF32_ afAlpha) -> _sVec4f_: Get a css color from it's name, specifying the alpha. 
- __iGraphics::UDPointsSphereRandom__(_tVec3fCVec\*_ apResults) -> _void_: Generates random points on a unit sphere. 
- __iGraphics::UDPointsSphereHammersley__(_tVec3fCVec\*_ apResults) -> _void_: Generates hammersley base2 points on a unit sphere. 
- __iGraphics::UDPointsSphereHammersleyEx__(_tVec3fCVec\*_ apResults, _tI32_ p1) -> _void_: Generates hammersley base p1 points on a unit sphere. 
- __iGraphics::UDPointsSphereHalton__(_tVec3fCVec\*_ apResults, _tI32_ p2) -> _void_: Generates halton p1=2,p2 points on a unit sphere. 
- __iGraphics::UDPointsSphereHaltonEx__(_tVec3fCVec\*_ apResults, _tI32_ p1, _tI32_ p2) -> _void_: Generates halton p1,p2 points on a unit sphere. 
- __iGraphics::UDPointsHemisphereRandom__(_tVec3fCVec\*_ apResults) -> _void_: Generates random points on a unit hemisphere. 
- __iGraphics::UDPointsHemisphereHammersley__(_tVec3fCVec\*_ apResults) -> _void_: Generates hammersley base2 points on a unit hemisphere. 
- __iGraphics::UDPointsHemisphereHammersleyEx__(_tVec3fCVec\*_ apResults, _tI32_ p1) -> _void_: Generates hammersley base p1 points on a unit hemisphere. 
- __iGraphics::UDPointsHemisphereHalton__(_tVec3fCVec\*_ apResults, _tI32_ p2) -> _void_: Generates halton p1=2,p2 points on a unit hemisphere. 
- __iGraphics::UDPointsHemisphereHaltonEx__(_tVec3fCVec\*_ apResults, _tI32_ p1, _tI32_ p2) -> _void_: Generates halton p1,p2 points on a unit hemisphere. 
- __iGraphics::UDPointsPlaneRandom__(_tVec2fCVec\*_ apResults) -> _void_: Generate random points on a unit plane. 
- __iGraphics::UDPointsPlaneHammersley__(_tVec2fCVec\*_ apResults) -> _void_: Generate hammersley base2 points on a unit plane. 
- __iGraphics::UDPointsPlaneHammersleyEx__(_tVec2fCVec\*_ apResults, _tI32_ p1) -> _void_: Generate hammersley base p1 points on a unit plane. 
- __iGraphics::UDPointsPlaneHalton__(_tVec2fCVec\*_ apResults, _tI32_ p2) -> _void_: Generate halton p1=2,p2 points on a unit plane. 
- __iGraphics::UDPointsPlaneHaltonEx__(_tVec2fCVec\*_ apResults, _tI32_ p1, _tI32_ p2) -> _void_: Generate halton p1,p2 points on a unit plane. 
- __iGraphics::DampedSpringGetDampingRatio__(_const tF32_ Ks, _const tF32_ Kd) -> _tF32_: Get the damping ratio of a spring set with the specified Ks/Kd constants. 
- __iGraphics::DampedSpringComputeKdFromDampingRatio__(_const tF32_ Ks, _const tF32_ E) -> _tF32_: Compute the value of Kd for the specified Ks that will result in a spring with the specified damping ratio. 
- __iGraphics::DampedSpringAcceleration1__(_tF32_ D, _tF32_ V, _const tF32_ Ks, _const tF32_ Kd) -> _tF32_: Computes the acceleration of a 1D damped spring system. \see ni::iSystem::DampedSpringAcceleration4 
- __iGraphics::DampedSpringAcceleration2__(_const sVec2f&_ D, _const sVec2f&_ V, _const tF32_ Ks, _const tF32_ Kd) -> _sVec2f_: Computes the acceleration of a 1D damped spring system. \see ni::iSystem::DampedSpringAcceleration4 
- __iGraphics::DampedSpringAcceleration3__(_const sVec3f&_ D, _const sVec3f&_ V, _const tF32_ Ks, _const tF32_ Kd) -> _sVec3f_: Computes the acceleration of a 1D damped spring system. \see ni::iSystem::DampedSpringAcceleration4 
- __iGraphics::DampedSpringAcceleration4__(_const sVec4f&_ D, _const sVec4f&_ V, _const tF32_ Ks, _const tF32_ Kd) -> _sVec4f_: Computes the acceleration of a 4D damped spring system. The spring acceleration is applied in the direction opposite from its displacement from a rest position, and a damping acceleration is applied in the direction opposite from its velocity. The damping ratio is : E = Kd/(2*sqrt(Ks)). - When E=1, the spring system is critically damped, and the system will return to its rest position in the minimal possibile time for the given value of Ks. - When E < 1, the spring system is underdamped, and it will oscillate before returning to rest. - When E > 1, then the system is overdamped and it will take longer than it is necessary to reach equilibrum. 
- __iGraphics::CreateDampedSpring1__(_const tF32_ Ks, _const tF32_ Kd) -> _ni::iDampedSpring1\*_: Creates a 1D damped spring. 
- __iGraphics::CreateDampedSpring2__(_const tF32_ Ks, _const tF32_ Kd) -> _ni::iDampedSpring2\*_: Creates a 2D damped spring. 
- __iGraphics::CreateDampedSpring3__(_const tF32_ Ks, _const tF32_ Kd) -> _ni::iDampedSpring3\*_: Creates a 3D damped spring. 
- __iGraphics::CreateDampedSpring4__(_const tF32_ Ks, _const tF32_ Kd) -> _ni::iDampedSpring4\*_: Creates a 4D damped spring. 
- __iGraphics::CreateDampedSpringPosition1__(_const tF32_ Ks, _const tF32_ Kd) -> _ni::iDampedSpringPosition1\*_: Creates a 1D damped spring position. 
- __iGraphics::CreateDampedSpringPosition2__(_const tF32_ Ks, _const tF32_ Kd) -> _ni::iDampedSpringPosition2\*_: Creates a 2D damped spring position. 
- __iGraphics::CreateDampedSpringPosition3__(_const tF32_ Ks, _const tF32_ Kd) -> _ni::iDampedSpringPosition3\*_: Creates a 3D damped spring position. 
- __iGraphics::CreateDampedSpringPosition4__(_const tF32_ Ks, _const tF32_ Kd) -> _ni::iDampedSpringPosition4\*_: Creates a 4D damped spring position. 
- __iGraphics::CreateTransform__() -> _iTransform\*_: Creates a new transform. 
- __iGraphics::CreateFrustum__() -> _iFrustum\*_: Creates a new frustum. 
- __iGraphics::CreateAABB__() -> _iBoundingVolume\*_: Creates a new AABB. 
- __iGraphics::CreateIntersection__() -> _iIntersection\*_: Creates an intersection. 
- __iGraphics::CreateCamera__() -> _iCamera\*_: Creates a new camera instance. 
- __iGraphics::CreateNUSpline__(_eNUSplineType_ aType) -> _iNUSpline\*_: Creates a new Non-uniform spline. 
- __iGraphics::CreateOverlayColor__(_const sColor4f&_ aColor) -> _iOverlay\*_: Creates a color overlay. 
- __iGraphics::CreateOverlayResource__(_iHString\*_ ahspRes) -> _iOverlay\*_: Create an overlay from the specified resource. 
- __iGraphics::CreateOverlayTexture__(_iTexture\*_ apTexture) -> _iOverlay\*_: Creates an overlay that will use the specified texture. 
- __iGraphics::CreateOverlayImage__(_iImage\*_ apImage) -> _iOverlay\*_: Creates an overlay that will use the specified image. 
- __iGraphics::CreateOverlayMaterial__(_iMaterial\*_ apMaterial) -> _iOverlay\*_: Creates an overlay that will use the specified material. 
- __iGraphics::LoadFont__(_iHString\*_ ahspName) -> _iFont\*_: Load a font. \see ni::iGraphics::LoadFont 
- __iGraphics::LoadFontEx__(_iHString\*_ ahspName, _tFontLoadFlags_ aFlags) -> _iFont\*_: Load a font. 
- __iGraphics::CreateFont__(_iHString\*_ ahspName, _iFile\*_ pFile) -> _iFont\*_: Create a font from the given file. 
- __iGraphics::CreateFontFromBitmap__(_iHString\*_ ahspName, _iBitmap2D\*_ pBmp) -> _iFont\*_: Create a font from the given bitmap. 
- __iGraphics::CreateFont8x8__(_iHString\*_ ahspName) -> _iFont\*_: Create the default 8x8 system font. 
- __iGraphics::EnumOSFonts__() -> _Ptr<tStringCMap>_: Get the list of fonts find on the host OS. 
- __iGraphics::RegisterSystemFonts__() -> _tBool_: Register all the default system fonts. 
- __iGraphics::RegisterSystemFont__(_iHString\*_ ahspName, _iHString\*_ ahspFilePath, _iFont\*_ apFont) -> _tBool_: Register a new font as a system font. 
- __iGraphics::GetNumSystemFonts__() -> _tU32_: Get the number of system fonts registered. 
- __iGraphics::GetSystemFontName__(_tU32_ anIndex) -> _iHString\*_: Get the name of the specified system font. 
- __iGraphics::GetSystemFontFilePath__(_tU32_ anIndex) -> _iHString\*_: Get the file path of the specified system font. 
- __iGraphics::GetSystemFontFileName__(_tU32_ anIndex) -> _iHString\*_: Get the file name of the specified system font. 
- __iGraphics::GetNumFonts__() -> _tU32_: Get the number of fonts registered. 
- __iGraphics::GetFontFromIndex__(_tU32_ anIndex) -> _iFont\*_: Get the font at the given index. 
- __iGraphics::GetFontFromName__(_iHString\*_ ahspName) -> _iFont\*_: Get a font from its exact name. 
- __iGraphics::FindFont__(_iHString\*_ ahspName, _tFontLoadFlags_ mode) -> _iFont\*_: Find a loaded font which matches the specified names. 
- __iGraphics::ClearAllFontCaches__() -> _tBool_: Clear all font caches. 
- __iGraphics::GetFontCacheID__() -> _tU32_: Get the global font cache ID. 
- __iGraphics::CreateImage__(_tU32_ anWidth, _tU32_ anHeight) -> _iImage\*_: Create a new blank empty image. 
- __iGraphics::CreateImageFromFile__(_iFile\*_ apFile) -> _iImage\*_: Create a new image from the specified bitmap file. 
- __iGraphics::CreateImageFromResource__(_iHString\*_ ahspRes) -> _iImage\*_: Create a new image from the specified resource. 
- __iGraphics::CreateImageFromBitmap__(_iBitmap2D\*_ apBitmap) -> _iImage\*_: Create a new image from the specified bitmap. 
- __iGraphics::CreateImageFromTexture__(_iTexture\*_ apTexture) -> _iImage\*_: Create a new image from the specified texture. 
- __iGraphics::CreateImageFromBitmapAndTexture__(_iBitmap2D\*_ apBitmap, _iTexture\*_ apTexture) -> _iImage\*_: Create a new image from the specified bitmap and texture. 
- __iGraphics::CreateImageEx__(_tU32_ anWidth, _tU32_ anHeight, _iBitmap2D\*_ apBmp, _iTexture\*_ apTex, _iTexture\*_ apDepthStencil) -> _iImage\*_: Create a new image. 
- __iGraphics::CreateImageMap__(_const achar\*_ aaszBaseName, _const achar\*_ aaszPxf) -> _iImageMap\*_: Create an image map. 
- __iGraphics::CreateImageGraphicsContext__(_iImage\*_ apImage) -> _iGraphicsContext\*_: Create a graphics context that uses the specified Image as main render target and depth buffer. 
- __iGraphics::CreateCanvas__(_iGraphicsContext\*_ apContext, _iMaterial\*_ apResetMaterial) -> _iCanvas\*_: Creates a new canvas. 
- __iGraphics::CreateTextObject__(_const achar\*_ aaszText, _const sVec2f&_ avSize, _const tF32_ afContentsScale) -> _Ptr<iTextObject>_: Create a new text object. 
- __iGraphics::IsVideoFile__(_iFile\*_ apFile) -> _tBool_: Check whether the given file is a supported video file. 
- __iGraphics::CreateVideoDecoder__(_iHString\*_ ahspName, _iFile\*_ apFile, _tU32_ aFlags) -> _iVideoDecoder\*_: Create a video decoder. 
- __iGraphics::CreateVGPath__() -> _Ptr<iVGPath>_: Create iVGPath 
- __iGraphics::CreateVGStyle__() -> _Ptr<iVGStyle>_: Create iVGStyle 
- __iGraphics::CreateVGTransform__() -> _Ptr<iVGTransform>_: Create iVGTransform 
- __iGraphics::CreateVGPolygonTesselator__() -> _Ptr<iVGPolygonTesselator>_: Create iVGPolygonTesselator 
- __iGraphics::CreateVGImage__(_tU32_ anWidth, _tU32_ anHeight) -> _Ptr<iVGImage>_
- __iGraphics::CreateVGImageFromBitmap__(_iBitmap2D\*_ apBitmap) -> _Ptr<iVGImage>_
- __iGraphics::CreateVGImageFromTexture__(_iTexture\*_ apTexture) -> _Ptr<iVGImage>_
- __iGraphics::CreateVGImageFromBitmapAndTexture__(_iBitmap2D\*_ apBitmap, _iTexture\*_ apTexture) -> _Ptr<iVGImage>_
- __iGraphics::CreateVGImageFromFile__(_iFile\*_ apFile) -> _Ptr<iVGImage>_
- __iGraphics::CreateVGImageFromResource__(_iHString\*_ ahspRes) -> _Ptr<iVGImage>_
- __iGraphics::CreateVGGradientTable__(_tU32_ anSize) -> _Ptr<iVGGradientTable>_
- __iGraphics::CreateVGGradientTableTwoColors__(_const sColor4f&_ acolStart, _const sColor4f&_ acolEnd) -> _Ptr<iVGGradientTable>_
- __iGraphics::CreateVGGradientTableStops__(_const tF32CVec\*_ apOffsets, _const tVec4fCVec\*_ apColors) -> _Ptr<iVGGradientTable>_
- __iGraphics::CreateVGPaint__(_eVGPaintType_ aType) -> _Ptr<iVGPaint>_
- __iGraphics::CreateVGPaintSolid__(_const sColor4f&_ aColor) -> _Ptr<iVGPaint>_
- __iGraphics::CreateVGPaintImage__(_iVGImage\*_ apImage, _eVGImageFilter_ aFilter, _eVGWrapType_ aWrap) -> _Ptr<iVGPaintImage>_
- __iGraphics::CreateVGPaintGradient__(_eVGGradientType_ aType, _iVGGradientTable\*_ apGradientTable) -> _Ptr<iVGPaintGradient>_
- __iGraphics::CreateVGPaintGradientTwoColors__(_eVGGradientType_ aType, _const sColor4f&_ acolStart, _const sColor4f&_ acolEnd) -> _Ptr<iVGPaintGradient>_
- __iGraphics::CreateVGPaintGradientStops__(_eVGGradientType_ aType, _const tF32CVec\*_ apOffsets, _const tVec4fCVec\*_ apColors) -> _Ptr<iVGPaintGradient>_

## interface ni::iGraphics
Graphics interface 

### Parents:
- iUnknown

### Methods:
- __iGraphics::FVFGetTexCooDim__(_tFVF_ anFVF, _tU32_ anTexCooIndex) -> _tU32_: Get the number of dimensions of the specified texture coordinates. anTexCooIndex is the index (0 to 7). 
- __iGraphics::FVFGetNumTexCoos__(_tFVF_ anFVF) -> _tU32_: Get the number of texture coordinates of the specified FVF. 
- __iGraphics::FVFToString__(_tFVF_ aFVF) -> _cString_: Convert the specified FVF to a string. 
- __iGraphics::FVFFromString__(_const achar\*_ aaszString) -> _tFVF_: Get a FVF from the specified string. 
- __iGraphics::FVFGetComponentOffset__(_tFVF_ aFVF, _eFVF_ C) -> _tU32_: Get the offset of the specified component. 
- __iGraphics::FVFGetStride__(_tFVF_ aFVF) -> _tU32_: Get the size of a FVF. 
- __iGraphics::CreatePixelFormat__(_const achar\*_ aszFormat) -> _iPixelFormat\*_: Create a pixel format. 
- __iGraphics::CreateBitmapFormat__(_eBitmapType_ aType, _const achar\*_ aaszFormat, _tU32_ anNumMipMaps, _tU32_ anWidth, _tU32_ anHeight, _tU32_ anDepth) -> _iBitmapFormat\*_: Create a new bitmap format. 
- __iGraphics::CreateBitmapFormatEx__(_eBitmapType_ aType, _iPixelFormat\*_ pFmt, _tU32_ anNumMipMaps, _tU32_ anWidth, _tU32_ anHeight, _tU32_ anDepth) -> _iBitmapFormat\*_: Create a new bitmap format. 
- __iGraphics::CreateBitmapFormatEmpty__() -> _iBitmapFormat\*_: Create a new empty bitmap format. 
- __iGraphics::CreateBitmap__(_iHString\*_ ahspName, _eBitmapType_ aType, _const achar\*_ aaszFormat, _tU32_ anNumMipMaps, _tU32_ anWidth, _tU32_ anHeight, _tU32_ anDepth) -> _iBitmapBase\*_: Create a new bitmap. 
- __iGraphics::CreateBitmapEx__(_iHString\*_ ahspName, _eBitmapType_ aType, _iPixelFormat\*_ pFmt, _tU32_ anNumMipMaps, _tU32_ anWidth, _tU32_ anHeight, _tU32_ anDepth) -> _iBitmapBase\*_: Create a new bitmap. 
- __iGraphics::CreateBitmap2DEx__(_tU32_ nW, _tU32_ nH, _iPixelFormat\*_ pFmt) -> _iBitmap2D\*_: Create a 2D bitmap. 
- __iGraphics::CreateBitmap2D__(_tU32_ nW, _tU32_ nH, _const achar\*_ aszPixFmt) -> _iBitmap2D\*_: Create a 2D bitmap. 
- __iGraphics::CreateBitmap2DMemoryEx__(_tU32_ nW, _tU32_ nH, _iPixelFormat\*_ pFmt, _tU32_ anPitch, _tPtr_ ptrAddr, _tBool_ bFreeAddr) -> _iBitmap2D\*_: Create a 2D bitmap from the specified memory. 
- __iGraphics::CreateBitmap2DMemory__(_tU32_ nW, _tU32_ nH, _const achar\*_ aszPixFmt, _tU32_ anPitch, _tPtr_ ptrAddr, _tBool_ bFreeAddr) -> _iBitmap2D\*_: Create a 2D bitmap from the specified memory. 
- __iGraphics::CreateBitmapCubeEx__(_tU32_ ulSize, _iPixelFormat\*_ pFmt) -> _iBitmapCube\*_: Create a Cube bitmap. 
- __iGraphics::CreateBitmapCube__(_tU32_ ulSize, _const achar\*_ aszPixFmt) -> _iBitmapCube\*_: Create a Cube bitmap. 
- __iGraphics::CreateBitmap3DEx__(_tU32_ anW, _tU32_ anH, _tU32_ anD, _iPixelFormat\*_ apFmt) -> _iBitmap3D\*_: Create a 3D bitmap. 
- __iGraphics::CreateBitmap3D__(_tU32_ anW, _tU32_ anH, _tU32_ anD, _const achar\*_ aaszPixFmt) -> _iBitmap3D\*_: Create a 3D bitmap. 
- __iGraphics::CreateBitmap3DMemoryEx__(_tU32_ anW, _tU32_ anH, _tU32_ anD, _iPixelFormat\*_ apFmt, _tU32_ anRowPitch, _tU32_ anSlicePitch, _tPtr_ aptrAddr, _tBool_ abFreeAddr) -> _iBitmap3D\*_: Create a 3D bitmap from the specified memory. 
- __iGraphics::CreateBitmap3DMemory__(_tU32_ anW, _tU32_ anH, _tU32_ anD, _const achar\*_ aszPixFmt, _tU32_ anRowPitch, _tU32_ anSlicePitch, _tPtr_ aptrAddr, _tBool_ abFreeAddr) -> _iBitmap3D\*_: Create a 3D bitmap from the specified memory. 
- __iGraphics::LoadBitmap__(_iFile\*_ pFile) -> _iBitmapBase\*_: Load a bitmap from a file. 
- __iGraphics::LoadBitmapFromRes__(_iHString\*_ ahspRes, _iHString\*_ ahspBasePath) -> _iBitmapBase\*_: Load a bitmap from a resource. 
- __iGraphics::LoadBitmapEx__(_const achar\*_ aaszFormat, _iFile\*_ pFile) -> _iBitmapBase\*_: Load a bitmap from a file with the specified format. 
- __iGraphics::SaveBitmap__(_const achar\*_ aszFile, _iBitmapBase\*_ pBmp, _tU32_ ulCompression) -> _tBool_: Save a bitmap in a file. 
- __iGraphics::SaveBitmapEx__(_const achar\*_ aaszFormat, _iFile\*_ apFile, _iBitmapBase\*_ apBmp, _tU32_ anCompression) -> _tBool_: Save a bitmap in the specified format in a file. 
- __iGraphics::URLFindBitmapFilePath__(_const achar\*_ aszRes, _const achar\*_ aszBasePath) -> _cString_: Find the path/url matching the specified resource and basepath. 
- __iGraphics::OpenBitmapFile__(_const achar\*_ aszRes, _const achar\*_ aszBasePath) -> _iFile\*_: Open a bitmap file. 
- __iGraphics::ComputeBitmapDiff__(_const iBitmap2D\*_ apImgA, _const iBitmap2D\*_ apImgB, _iBitmap2D\*_ apOutput, _tF64_ afThreshold, _tBool_ abIgnoreAA) -> _tI64_: Computes the diff between two bitmaps. 
- __iGraphics::CreateGeometryPolygonal__(_tU32_ aulNumVertices, _tU32_ aulNumIndices, _tGeometryCreateFlags_ aFlags, _tFVF_ aFVF) -> _iGeometry\*_: Create a polygonal geometry. 
- __iGraphics::CreateGeometryPolygonalEx__(_iVertexArray\*_ apVA, _iIndexArray\*_ apIA) -> _iGeometry\*_: Create a polygonal geometry from an exisiting vertex array and index array. 
- __iGraphics::CreateGeometryModifier__(_const achar\*_ aszName, _iGeometry\*_ apGeometry, _iUnknown\*_ apInitData) -> _iGeometryModifier\*_: Create a geometry modifier. 
- __iGraphics::CreateGeometryPolygonalCube__(_tGeometryCreateFlags_ aFlags, _tFVF_ aFVF, _const sVec3f&_ avCenter, _tF32_ afWidth, _tBool_ abCW, _tU32_ aulColor, _const sMatrixf&_ amtxUV) -> _iGeometry\*_: Create a cube polygonal geometry. 
- __iGraphics::CreateGeometryPolygonalPlane__(_tGeometryCreateFlags_ aFlags, _tFVF_ aFVF, _ePlaneType_ aPlaneType, _const sVec3f&_ avCenter, _tF32_ afWidth, _tF32_ afHeight, _tU32_ aulNumDiv, _tBool_ abCW, _tU32_ aulColor, _const sMatrixf&_ amtxUV) -> _iGeometry\*_: Create a plane polygonal geometry. 
- __iGraphics::CreateGeometryPolygonalCylinder__(_tGeometryCreateFlags_ aFlags, _tFVF_ aFVF, _tF32_ baseRadius, _tF32_ topRadius, _tF32_ height, _tI32_ slices, _tI32_ stacks, _tBool_ abCW, _tU32_ aulColor, _const sMatrixf&_ amtxUV, _tBool_ abCap, _tBool_ abCentered) -> _iGeometry\*_: Create a cylinder polygonal geometry. 
- __iGraphics::CreateGeometryPolygonalSphere__(_tGeometryCreateFlags_ aFlags, _tFVF_ aFVF, _tF32_ radius, _tI32_ slices, _tI32_ stacks, _tBool_ abCW, _tU32_ aulColor, _const sMatrixf&_ amtxUV) -> _iGeometry\*_: Create a sphere polygonal geometry. 
- __iGraphics::CreateGeometryPolygonalGeosphere__(_tGeometryCreateFlags_ aFlags, _tFVF_ aFVF, _tF32_ radius, _tI32_ slices, _tBool_ abCW, _tU32_ aulColor, _const sMatrixf&_ amtxUV) -> _iGeometry\*_: Create a geosphere polygonal geometry. 
- __iGraphics::CreateGeometryPolygonalDiskSweep__(_tGeometryCreateFlags_ aFlags, _tFVF_ aFVF, _tF32_ innerRadius, _tF32_ outerRadius, _tI32_ slices, _tI32_ stacks, _tF32_ startAngle, _tF32_ sweepAngle, _tBool_ abCW, _tU32_ aulColor, _const sMatrixf&_ amtxUV) -> _iGeometry\*_: Create a disk sweep polygonal geometry. 
- __iGraphics::UpdateGeometryPolygonalDiskSweep__(_iGeometry\*_ apGeom, _tF32_ innerRadius, _tF32_ outerRadius, _tI32_ slices, _tI32_ stacks, _tF32_ startAngle, _tF32_ sweepAngle, _tBool_ abCW, _tU32_ aulColor, _const sMatrixf&_ amtxUV) -> _tBool_: Update a disk polygonal geometry. 
- __iGraphics::CreateGeometryPolygonalDisk__(_tGeometryCreateFlags_ aFlags, _tFVF_ aFVF, _tF32_ innerRadius, _tF32_ outerRadius, _tI32_ slices, _tI32_ stacks, _tBool_ abCW, _tU32_ aulColor, _const sMatrixf&_ amtxUV) -> _iGeometry\*_: Create a disk polygonal geometry. 
- __iGraphics::InitializeDriver__(_iHString\*_ ahspDriverName) -> _tBool_: Initialize the specified hardware driver. 
- __iGraphics::GetIsDriverInitialized__() -> _tBool_: Get whether the driver has been initialized. 
- __iGraphics::GetDriver__() -> _iGraphicsDriver\*_: Get the driver that has been initialized. 
- __iGraphics::GetDriverCaps__(_eGraphicsCaps_ aCaps) -> _tInt_: Get the driver's capabilities. 
- __iGraphics::CreateContextForWindow__(_iOSWindow\*_ apWindow, _const achar\*_ aaszBBFormat, _const achar\*_ aaszDSFormat, _tU32_ anSwapInterval, _tTextureFlags_ aBackBufferFlags) -> _iGraphicsContext\*_: Create a new context for the specified OS window. 
- __iGraphics::CreateContextForRenderTargets__(_iTexture\*_ apRT0, _iTexture\*_ apRT1, _iTexture\*_ apRT2, _iTexture\*_ apRT3, _iTexture\*_ apDS) -> _iGraphicsContextRT\*_: Creates a new context for the specified render targets. 
- __iGraphics::GetGenericDeviceResourceManager__() -> _iDeviceResourceManager\*_: Get the generice device resource manager. 
- __iGraphics::CreateSamplerStates__() -> _iSamplerStates\*_: Create a new sampler states instance. 
- __iGraphics::CreateDepthStencilStates__() -> _iDepthStencilStates\*_: Create a new depth stencil states instance. 
- __iGraphics::CreateRasterizerStates__() -> _iRasterizerStates\*_: Create a new rasterizer states instance. 
- __iGraphics::CreateFixedStates__() -> _iFixedStates\*_: Create a new fixed pipeline states instance. 
- __iGraphics::CheckTextureFormat__(_iBitmapFormat\*_ apFormat, _tTextureFlags_ aFlags) -> _tBool_: Check whether the specified texture format is supported and set the bitmap format object to the nearest matching native bitmap format. 
- __iGraphics::GetTextureDeviceResourceManager__() -> _iDeviceResourceManager\*_: Get the texture device resource manager. 
- __iGraphics::GetNumTextures__() -> _tU32_: Get the number of textures in the manager. 
- __iGraphics::GetTextureFromName__(_iHString\*_ ahspName) -> _iTexture\*_: Get a texture from its name. 
- __iGraphics::GetTextureFromIndex__(_tU32_ anIndex) -> _iTexture\*_: Get a texture from its index. 
- __iGraphics::CreateTexture__(_iHString\*_ ahspName, _eBitmapType_ aType, _const achar\*_ aaszFormat, _tU32_ anNumMipMaps, _tU32_ anWidth, _tU32_ anHeight, _tU32_ anDepth, _tTextureFlags_ aFlags) -> _iTexture\*_: Create a new texture. 
- __iGraphics::CreateTextureFromBitmap__(_iHString\*_ ahspName, _iBitmapBase\*_ apBitmap, _tTextureFlags_ aFlags) -> _iTexture\*_: Create a new texture from the specified bitmap. 
- __iGraphics::CreateTextureFromRes__(_iHString\*_ ahspRes, _iHString\*_ ahspBasePath, _tTextureFlags_ aFlags) -> _iTexture\*_: Create a new texture from the specified resource. 
- __iGraphics::SetRecreateTextureWhenChanged__(_tBool_ abEnabled) -> _void_: Set whether CreateTextureFromRes recreates the texture when the source resource has changed. 
- __iGraphics::GetRecreateTextureWhenChanged__() -> _tBool_: Get whether CreateTextureFromRes recreates the texture when the source resource has changed. 
- __iGraphics::BlitBitmapToTexture__(_iBitmap2D\*_ apSrc, _iTexture\*_ apDest, _tU32_ anDestLevel, _const sRecti&_ aSrcRect, _const sRecti&_ aDestRect, _eTextureBlitFlags_ aFlags) -> _tBool_: Blit a bitmap to a texture. 
- __iGraphics::BlitTextureToBitmap__(_iTexture\*_ apSrc, _tU32_ anSrcLevel, _iBitmap2D\*_ apDest, _const sRecti&_ aSrcRect, _const sRecti&_ aDestRect, _eTextureBlitFlags_ aFlags) -> _tBool_: Blit a texture to a bitmap. 
- __iGraphics::BlitTextureToTexture__(_iTexture\*_ apSrc, _tU32_ anSrcLevel, _iTexture\*_ apDest, _tU32_ anDestLevel, _const sRecti&_ aSrcRect, _const sRecti&_ aDestRect, _eTextureBlitFlags_ aFlags) -> _tBool_: Blit a texture into another texture. 
- __iGraphics::BlitBitmap3DToTexture__(_iBitmap3D\*_ apSrc, _iTexture\*_ apDest, _tU32_ anDestLevel, _const sVec3i&_ aSrcMin, _const sVec3i&_ aDestMin, _const sVec3i&_ avSize, _eTextureBlitFlags_ aFlags) -> _tBool_: Blit a 3d bitmap to a 3d texture. 
- __iGraphics::BlitTextureToBitmap3D__(_iTexture\*_ apSrc, _tU32_ anSrcLevel, _iBitmap3D\*_ apDest, _const sVec3i&_ aSrcMin, _const sVec3i&_ aDestMin, _const sVec3i&_ avSize, _eTextureBlitFlags_ aFlags) -> _tBool_: Blit a 3d texture to a 3d bitmap. 
- __iGraphics::CreateBitmapFromTexture__(_iTexture\*_ apSrc) -> _iBitmapBase\*_: Create a bitmap from a texture. 
- __iGraphics::GetNumShaderProfile__(_eShaderUnit_ aUnit) -> _tU32_: Get the number of Shader profile supported in the specified unit. 
- __iGraphics::GetShaderProfile__(_eShaderUnit_ aUnit, _tU32_ anIndex) -> _iHString\*_: Get the profile at the specified index. 
- __iGraphics::CreateShaderConstants__(_tU32_ anMaxRegisters) -> _iShaderConstants\*_: Creates an empty shader constants instance. 
- __iGraphics::SerializeShaderConstants__(_iShaderConstants\*_ apConsts, _iDataTable\*_ apDT, _tSerializeFlags_ aFlags) -> _tBool_: Serialize shader constants in the specified datatable. 
- __iGraphics::GetShaderDeviceResourceManager__() -> _iDeviceResourceManager\*_: Get the shader device resource manager. 
- __iGraphics::GetNumShaders__() -> _tU32_: Get the number of shaders in the manager. 
- __iGraphics::GetShaderFromName__(_iHString\*_ ahspName) -> _iShader\*_: Get a shader from its name. 
- __iGraphics::GetShaderFromIndex__(_tU32_ anIndex) -> _iShader\*_: Get a shader from its index. 
- __iGraphics::CreateShader__(_iHString\*_ ahspName, _iFile\*_ apByteCode) -> _iShader\*_: Create a new shader. 
- __iGraphics::CreateShaderFromRes__(_iHString\*_ ahspRes) -> _iShader\*_: Create a new shader from the specified resource. 
- __iGraphics::SetRecreateShaderWhenChanged__(_tBool_ abEnabled) -> _void_: Set whether CreateShaderFromRes recreates the shader when the source resource has changed. 
- __iGraphics::GetRecreateShaderWhenChanged__() -> _tBool_: Get whether CreateShaderFromRes recreates the shader when the source resource has changed. 
- __iGraphics::CreateVertexArray__(_tU32_ anNumVertices, _tFVF_ anFVF, _eArrayUsage_ aUsage) -> _iVertexArray\*_: Create a new driver vertex array instance. 
- __iGraphics::CreateIndexArray__(_eGraphicsPrimitiveType_ aPrimitiveType, _tU32_ anNumIndex, _tU32_ anMaxVertexIndex, _eArrayUsage_ aUsage) -> _iIndexArray\*_: Create a new driver index array instance. 
- __iGraphics::CreateDrawOperation__() -> _iDrawOperation\*_: Creates a new draw operation. 
- __iGraphics::CreateDrawOperationSet__() -> _iDrawOperationSet\*_: Create a draw operation set. 
- __iGraphics::CreateOcclusionQuery__() -> _iOcclusionQuery\*_: Create a new occlusion query object. 
- __iGraphics::CompileSamplerStates__(_iSamplerStates\*_ apStates) -> _tIntPtr_: Compile a sampler states. 
- __iGraphics::GetCompiledSamplerStates__(_tIntPtr_ aHandle) -> _iSamplerStates\*_: Get the specified compiled sampler states. 
- __iGraphics::CompileRasterizerStates__(_iRasterizerStates\*_ apStates) -> _tIntPtr_: Compile a rasterizer states. 
- __iGraphics::GetCompiledRasterizerStates__(_tIntPtr_ aHandle) -> _iRasterizerStates\*_: Get the specified compiled rasterizer states. 
- __iGraphics::CompileDepthStencilStates__(_iDepthStencilStates\*_ apStates) -> _tIntPtr_: Compile a depth stencil states. 
- __iGraphics::GetCompiledDepthStencilStates__(_tIntPtr_ aHandle) -> _iDepthStencilStates\*_: Get the specified compiled depth stencil states. 
- __iGraphics::CreateMaterial__() -> _iMaterial\*_: Create an empty material. 
- __iGraphics::CreateMaterialLibrary__() -> _iMaterialLibrary\*_: Create a material library. 
- __iGraphics::CreateDrawOpCapture__() -> _iGraphicsDrawOpCapture\*_: Create a new draw op capture object. 
- __iGraphics::SetDrawOpCapture__(_iGraphicsDrawOpCapture\*_ apCapture) -> _void_: Set the draw op capture object. 
- __iGraphics::GetDrawOpCapture__() -> _iGraphicsDrawOpCapture\*_: Get the draw op capture object. 
- __iGraphics::ColorLuminance__(_const sVec3f&_ aColor) -> _tF32_: Get the lumiance of a 3d color. 
- __iGraphics::ColorLuminanceEx__(_const sVec3f&_ aColor, _const sVec3f&_ avLuminanceDistribution) -> _tF32_: Get the lumiance of a 3d color, allow to specify a luminance distribution. 
- __iGraphics::ColorGammaCorrect__(_const sVec3f&_ aC, _tF32_ afFactor) -> _sVec3f_: Correct the gamma of a color. 
- __iGraphics::ColorAdjustContrast__(_const sVec3f&_ C, _tF32_ c) -> _sVec3f_: Adjust the contrast of a color. 
- __iGraphics::ColorAdjustSaturation__(_const sVec3f&_ C, _tF32_ s) -> _sVec3f_: Adjust the saturation of a color. 
- __iGraphics::ColorNegative__(_const sVec3f&_ C) -> _sVec3f_: Get the negative of a color. 
- __iGraphics::ColorGrey__(_const sVec3f&_ C) -> _sVec3f_: Gray a color. 
- __iGraphics::ColorBlackWhite__(_const sVec3f&_ C, _tF32_ s) -> _sVec3f_: Set a color to be black or white in function of the specified reference. 
- __iGraphics::ColorConvert__(_eColorSpace_ aSource, _eColorSpace_ aDest, _const sVec4f&_ aColor) -> _sVec4f_: Convert a color from one color space to another. 
- __iGraphics::ColorConvertEx__(_eColorSpace_ aSource, _eColorSpace_ aDest, _const sVec4f&_ aColor, _const sVec4f&_ aXYZRef) -> _sVec4f_: Convert a color from one color space to another, allows to specify the XYZ reference. 
- __iGraphics::GetNumNamedColors__() -> _tU32_: Get the number of named colors. 
- __iGraphics::GetColorName__(_tU32_ anIndex) -> _const achar\*_: Get the name of the color at the specified index. 
- __iGraphics::GetColorIndex__(_iHString\*_ ahspName) -> _tU32_: Get the index of the color with the specified name. 
- __iGraphics::GetColorValue__(_tU32_ anIndex) -> _tU32_: Get the value of the color at the specified index. 
- __iGraphics::FindColorName__(_const sColor4f&_ aColor) -> _const achar\*_: Find the color with the closest match to the specified color. 
- __iGraphics::GetColor3FromName__(_iHString\*_ ahspName) -> _sVec3f_: Get a color from it's name. 
- __iGraphics::GetColor4FromName__(_iHString\*_ ahspName) -> _sVec4f_: Get a color from it's name. 
- __iGraphics::GetColor4FromNameA__(_iHString\*_ ahspName, _tF32_ afAlpha) -> _sVec4f_: Get a color from it's name, specifying the alpha. 
- __iGraphics::GetCssColor3FromName__(_iHString\*_ ahspName) -> _sVec3f_: Get a color from it's name. 
- __iGraphics::GetCssColor4FromName__(_iHString\*_ ahspName) -> _sVec4f_: Get a css color from it's name. 
- __iGraphics::GetCssColor4FromNameA__(_iHString\*_ ahspName, _tF32_ afAlpha) -> _sVec4f_: Get a css color from it's name, specifying the alpha. 
- __iGraphics::UDPointsSphereRandom__(_tVec3fCVec\*_ apResults) -> _void_: Generates random points on a unit sphere. 
- __iGraphics::UDPointsSphereHammersley__(_tVec3fCVec\*_ apResults) -> _void_: Generates hammersley base2 points on a unit sphere. 
- __iGraphics::UDPointsSphereHammersleyEx__(_tVec3fCVec\*_ apResults, _tI32_ p1) -> _void_: Generates hammersley base p1 points on a unit sphere. 
- __iGraphics::UDPointsSphereHalton__(_tVec3fCVec\*_ apResults, _tI32_ p2) -> _void_: Generates halton p1=2,p2 points on a unit sphere. 
- __iGraphics::UDPointsSphereHaltonEx__(_tVec3fCVec\*_ apResults, _tI32_ p1, _tI32_ p2) -> _void_: Generates halton p1,p2 points on a unit sphere. 
- __iGraphics::UDPointsHemisphereRandom__(_tVec3fCVec\*_ apResults) -> _void_: Generates random points on a unit hemisphere. 
- __iGraphics::UDPointsHemisphereHammersley__(_tVec3fCVec\*_ apResults) -> _void_: Generates hammersley base2 points on a unit hemisphere. 
- __iGraphics::UDPointsHemisphereHammersleyEx__(_tVec3fCVec\*_ apResults, _tI32_ p1) -> _void_: Generates hammersley base p1 points on a unit hemisphere. 
- __iGraphics::UDPointsHemisphereHalton__(_tVec3fCVec\*_ apResults, _tI32_ p2) -> _void_: Generates halton p1=2,p2 points on a unit hemisphere. 
- __iGraphics::UDPointsHemisphereHaltonEx__(_tVec3fCVec\*_ apResults, _tI32_ p1, _tI32_ p2) -> _void_: Generates halton p1,p2 points on a unit hemisphere. 
- __iGraphics::UDPointsPlaneRandom__(_tVec2fCVec\*_ apResults) -> _void_: Generate random points on a unit plane. 
- __iGraphics::UDPointsPlaneHammersley__(_tVec2fCVec\*_ apResults) -> _void_: Generate hammersley base2 points on a unit plane. 
- __iGraphics::UDPointsPlaneHammersleyEx__(_tVec2fCVec\*_ apResults, _tI32_ p1) -> _void_: Generate hammersley base p1 points on a unit plane. 
- __iGraphics::UDPointsPlaneHalton__(_tVec2fCVec\*_ apResults, _tI32_ p2) -> _void_: Generate halton p1=2,p2 points on a unit plane. 
- __iGraphics::UDPointsPlaneHaltonEx__(_tVec2fCVec\*_ apResults, _tI32_ p1, _tI32_ p2) -> _void_: Generate halton p1,p2 points on a unit plane. 
- __iGraphics::DampedSpringGetDampingRatio__(_const tF32_ Ks, _const tF32_ Kd) -> _tF32_: Get the damping ratio of a spring set with the specified Ks/Kd constants. 
- __iGraphics::DampedSpringComputeKdFromDampingRatio__(_const tF32_ Ks, _const tF32_ E) -> _tF32_: Compute the value of Kd for the specified Ks that will result in a spring with the specified damping ratio. 
- __iGraphics::DampedSpringAcceleration1__(_tF32_ D, _tF32_ V, _const tF32_ Ks, _const tF32_ Kd) -> _tF32_: Computes the acceleration of a 1D damped spring system. \see ni::iSystem::DampedSpringAcceleration4 
- __iGraphics::DampedSpringAcceleration2__(_const sVec2f&_ D, _const sVec2f&_ V, _const tF32_ Ks, _const tF32_ Kd) -> _sVec2f_: Computes the acceleration of a 1D damped spring system. \see ni::iSystem::DampedSpringAcceleration4 
- __iGraphics::DampedSpringAcceleration3__(_const sVec3f&_ D, _const sVec3f&_ V, _const tF32_ Ks, _const tF32_ Kd) -> _sVec3f_: Computes the acceleration of a 1D damped spring system. \see ni::iSystem::DampedSpringAcceleration4 
- __iGraphics::DampedSpringAcceleration4__(_const sVec4f&_ D, _const sVec4f&_ V, _const tF32_ Ks, _const tF32_ Kd) -> _sVec4f_: Computes the acceleration of a 4D damped spring system. The spring acceleration is applied in the direction opposite from its displacement from a rest position, and a damping acceleration is applied in the direction opposite from its velocity. The damping ratio is : E = Kd/(2*sqrt(Ks)). - When E=1, the spring system is critically damped, and the system will return to its rest position in the minimal possibile time for the given value of Ks. - When E < 1, the spring system is underdamped, and it will oscillate before returning to rest. - When E > 1, then the system is overdamped and it will take longer than it is necessary to reach equilibrum. 
- __iGraphics::CreateDampedSpring1__(_const tF32_ Ks, _const tF32_ Kd) -> _ni::iDampedSpring1\*_: Creates a 1D damped spring. 
- __iGraphics::CreateDampedSpring2__(_const tF32_ Ks, _const tF32_ Kd) -> _ni::iDampedSpring2\*_: Creates a 2D damped spring. 
- __iGraphics::CreateDampedSpring3__(_const tF32_ Ks, _const tF32_ Kd) -> _ni::iDampedSpring3\*_: Creates a 3D damped spring. 
- __iGraphics::CreateDampedSpring4__(_const tF32_ Ks, _const tF32_ Kd) -> _ni::iDampedSpring4\*_: Creates a 4D damped spring. 
- __iGraphics::CreateDampedSpringPosition1__(_const tF32_ Ks, _const tF32_ Kd) -> _ni::iDampedSpringPosition1\*_: Creates a 1D damped spring position. 
- __iGraphics::CreateDampedSpringPosition2__(_const tF32_ Ks, _const tF32_ Kd) -> _ni::iDampedSpringPosition2\*_: Creates a 2D damped spring position. 
- __iGraphics::CreateDampedSpringPosition3__(_const tF32_ Ks, _const tF32_ Kd) -> _ni::iDampedSpringPosition3\*_: Creates a 3D damped spring position. 
- __iGraphics::CreateDampedSpringPosition4__(_const tF32_ Ks, _const tF32_ Kd) -> _ni::iDampedSpringPosition4\*_: Creates a 4D damped spring position. 
- __iGraphics::CreateTransform__() -> _iTransform\*_: Creates a new transform. 
- __iGraphics::CreateFrustum__() -> _iFrustum\*_: Creates a new frustum. 
- __iGraphics::CreateAABB__() -> _iBoundingVolume\*_: Creates a new AABB. 
- __iGraphics::CreateIntersection__() -> _iIntersection\*_: Creates an intersection. 
- __iGraphics::CreateCamera__() -> _iCamera\*_: Creates a new camera instance. 
- __iGraphics::CreateNUSpline__(_eNUSplineType_ aType) -> _iNUSpline\*_: Creates a new Non-uniform spline. 
- __iGraphics::CreateOverlayColor__(_const sColor4f&_ aColor) -> _iOverlay\*_: Creates a color overlay. 
- __iGraphics::CreateOverlayResource__(_iHString\*_ ahspRes) -> _iOverlay\*_: Create an overlay from the specified resource. 
- __iGraphics::CreateOverlayTexture__(_iTexture\*_ apTexture) -> _iOverlay\*_: Creates an overlay that will use the specified texture. 
- __iGraphics::CreateOverlayImage__(_iImage\*_ apImage) -> _iOverlay\*_: Creates an overlay that will use the specified image. 
- __iGraphics::CreateOverlayMaterial__(_iMaterial\*_ apMaterial) -> _iOverlay\*_: Creates an overlay that will use the specified material. 
- __iGraphics::LoadFont__(_iHString\*_ ahspName) -> _iFont\*_: Load a font. \see ni::iGraphics::LoadFont 
- __iGraphics::LoadFontEx__(_iHString\*_ ahspName, _tFontLoadFlags_ aFlags) -> _iFont\*_: Load a font. 
- __iGraphics::CreateFont__(_iHString\*_ ahspName, _iFile\*_ pFile) -> _iFont\*_: Create a font from the given file. 
- __iGraphics::CreateFontFromBitmap__(_iHString\*_ ahspName, _iBitmap2D\*_ pBmp) -> _iFont\*_: Create a font from the given bitmap. 
- __iGraphics::CreateFont8x8__(_iHString\*_ ahspName) -> _iFont\*_: Create the default 8x8 system font. 
- __iGraphics::EnumOSFonts__() -> _Ptr<tStringCMap>_: Get the list of fonts find on the host OS. 
- __iGraphics::RegisterSystemFonts__() -> _tBool_: Register all the default system fonts. 
- __iGraphics::RegisterSystemFont__(_iHString\*_ ahspName, _iHString\*_ ahspFilePath, _iFont\*_ apFont) -> _tBool_: Register a new font as a system font. 
- __iGraphics::GetNumSystemFonts__() -> _tU32_: Get the number of system fonts registered. 
- __iGraphics::GetSystemFontName__(_tU32_ anIndex) -> _iHString\*_: Get the name of the specified system font. 
- __iGraphics::GetSystemFontFilePath__(_tU32_ anIndex) -> _iHString\*_: Get the file path of the specified system font. 
- __iGraphics::GetSystemFontFileName__(_tU32_ anIndex) -> _iHString\*_: Get the file name of the specified system font. 
- __iGraphics::GetNumFonts__() -> _tU32_: Get the number of fonts registered. 
- __iGraphics::GetFontFromIndex__(_tU32_ anIndex) -> _iFont\*_: Get the font at the given index. 
- __iGraphics::GetFontFromName__(_iHString\*_ ahspName) -> _iFont\*_: Get a font from its exact name. 
- __iGraphics::FindFont__(_iHString\*_ ahspName, _tFontLoadFlags_ mode) -> _iFont\*_: Find a loaded font which matches the specified names. 
- __iGraphics::ClearAllFontCaches__() -> _tBool_: Clear all font caches. 
- __iGraphics::GetFontCacheID__() -> _tU32_: Get the global font cache ID. 
- __iGraphics::CreateImage__(_tU32_ anWidth, _tU32_ anHeight) -> _iImage\*_: Create a new blank empty image. 
- __iGraphics::CreateImageFromFile__(_iFile\*_ apFile) -> _iImage\*_: Create a new image from the specified bitmap file. 
- __iGraphics::CreateImageFromResource__(_iHString\*_ ahspRes) -> _iImage\*_: Create a new image from the specified resource. 
- __iGraphics::CreateImageFromBitmap__(_iBitmap2D\*_ apBitmap) -> _iImage\*_: Create a new image from the specified bitmap. 
- __iGraphics::CreateImageFromTexture__(_iTexture\*_ apTexture) -> _iImage\*_: Create a new image from the specified texture. 
- __iGraphics::CreateImageFromBitmapAndTexture__(_iBitmap2D\*_ apBitmap, _iTexture\*_ apTexture) -> _iImage\*_: Create a new image from the specified bitmap and texture. 
- __iGraphics::CreateImageEx__(_tU32_ anWidth, _tU32_ anHeight, _iBitmap2D\*_ apBmp, _iTexture\*_ apTex, _iTexture\*_ apDepthStencil) -> _iImage\*_: Create a new image. 
- __iGraphics::CreateImageMap__(_const achar\*_ aaszBaseName, _const achar\*_ aaszPxf) -> _iImageMap\*_: Create an image map. 
- __iGraphics::CreateImageGraphicsContext__(_iImage\*_ apImage) -> _iGraphicsContext\*_: Create a graphics context that uses the specified Image as main render target and depth buffer. 
- __iGraphics::CreateCanvas__(_iGraphicsContext\*_ apContext, _iMaterial\*_ apResetMaterial) -> _iCanvas\*_: Creates a new canvas. 
- __iGraphics::CreateTextObject__(_const achar\*_ aaszText, _const sVec2f&_ avSize, _const tF32_ afContentsScale) -> _Ptr<iTextObject>_: Create a new text object. 
- __iGraphics::IsVideoFile__(_iFile\*_ apFile) -> _tBool_: Check whether the given file is a supported video file. 
- __iGraphics::CreateVideoDecoder__(_iHString\*_ ahspName, _iFile\*_ apFile, _tU32_ aFlags) -> _iVideoDecoder\*_: Create a video decoder. 
- __iGraphics::CreateVGPath__() -> _Ptr<iVGPath>_: Create iVGPath 
- __iGraphics::CreateVGStyle__() -> _Ptr<iVGStyle>_: Create iVGStyle 
- __iGraphics::CreateVGTransform__() -> _Ptr<iVGTransform>_: Create iVGTransform 
- __iGraphics::CreateVGPolygonTesselator__() -> _Ptr<iVGPolygonTesselator>_: Create iVGPolygonTesselator 
- __iGraphics::CreateVGImage__(_tU32_ anWidth, _tU32_ anHeight) -> _Ptr<iVGImage>_
- __iGraphics::CreateVGImageFromBitmap__(_iBitmap2D\*_ apBitmap) -> _Ptr<iVGImage>_
- __iGraphics::CreateVGImageFromTexture__(_iTexture\*_ apTexture) -> _Ptr<iVGImage>_
- __iGraphics::CreateVGImageFromBitmapAndTexture__(_iBitmap2D\*_ apBitmap, _iTexture\*_ apTexture) -> _Ptr<iVGImage>_
- __iGraphics::CreateVGImageFromFile__(_iFile\*_ apFile) -> _Ptr<iVGImage>_
- __iGraphics::CreateVGImageFromResource__(_iHString\*_ ahspRes) -> _Ptr<iVGImage>_
- __iGraphics::CreateVGGradientTable__(_tU32_ anSize) -> _Ptr<iVGGradientTable>_
- __iGraphics::CreateVGGradientTableTwoColors__(_const sColor4f&_ acolStart, _const sColor4f&_ acolEnd) -> _Ptr<iVGGradientTable>_
- __iGraphics::CreateVGGradientTableStops__(_const tF32CVec\*_ apOffsets, _const tVec4fCVec\*_ apColors) -> _Ptr<iVGGradientTable>_
- __iGraphics::CreateVGPaint__(_eVGPaintType_ aType) -> _Ptr<iVGPaint>_
- __iGraphics::CreateVGPaintSolid__(_const sColor4f&_ aColor) -> _Ptr<iVGPaint>_
- __iGraphics::CreateVGPaintImage__(_iVGImage\*_ apImage, _eVGImageFilter_ aFilter, _eVGWrapType_ aWrap) -> _Ptr<iVGPaintImage>_
- __iGraphics::CreateVGPaintGradient__(_eVGGradientType_ aType, _iVGGradientTable\*_ apGradientTable) -> _Ptr<iVGPaintGradient>_
- __iGraphics::CreateVGPaintGradientTwoColors__(_eVGGradientType_ aType, _const sColor4f&_ acolStart, _const sColor4f&_ acolEnd) -> _Ptr<iVGPaintGradient>_
- __iGraphics::CreateVGPaintGradientStops__(_eVGGradientType_ aType, _const tF32CVec\*_ apOffsets, _const tVec4fCVec\*_ apColors) -> _Ptr<iVGPaintGradient>_

## interface ni::iGraphicsContext
Graphics context description interface. 

### Parents:
- iUnknown

### Methods:
- __iGraphicsContext::GetGraphics__() -> _iGraphics\*_: Get the context's graphics object. 
- __iGraphicsContext::GetDriver__() -> _iGraphicsDriver\*_: Get the context's driver. 
- __iGraphicsContext::GetWidth__() -> _tU32_: Get the context width. 
- __iGraphicsContext::GetHeight__() -> _tU32_: Get the context height. 
- __iGraphicsContext::ClearBuffers__(_tClearBuffersFlags_ clearBuffer, _tU32_ anColor, _tF32_ afDepth, _tI32_ anStencil) -> _void_: Clear the specified main buffers. 
- __iGraphicsContext::GetRenderTarget__(_tU32_ anIndex) -> _iTexture\*_: Get the render target set on the specified index. 
- __iGraphicsContext::GetDepthStencil__() -> _iTexture\*_: Get the depth stencil target. 
- __iGraphicsContext::Display__(_tGraphicsDisplayFlags_ aFlags, _const sRecti&_ aRect) -> _tBool_: Display the canvas in its destination window/context. 
- __iGraphicsContext::DrawOperation__(_iDrawOperation\*_ apDrawOp) -> _tBool_: Draw the specified draw operation. 
- __iGraphicsContext::CaptureFrontBuffer__() -> _iBitmap2D\*_: Capture the front buffer. 
- __iGraphicsContext::SetViewport__(_const sRecti&_ aVal) -> _void_: Set the viewport. 
- __iGraphicsContext::GetViewport__() -> _sRecti_: Get the viewport. 
- __iGraphicsContext::SetScissorRect__(_const sRecti&_ aVal) -> _void_: Set the scissor rectangle. 
- __iGraphicsContext::GetScissorRect__() -> _sRecti_: Get the scissor rectangle. 
- __iGraphicsContext::SetFixedStates__(_iFixedStates\*_ apStates) -> _tBool_: Set the default fixed pipeline states. 
- __iGraphicsContext::GetFixedStates__() -> _iFixedStates\*_: Get the default fixed pipeline states. 
- __iGraphicsContext::SetMaterial__(_iMaterial\*_ apMat) -> _tBool_: Set the default material states. 
- __iGraphicsContext::GetMaterial__() -> _const iMaterial\*_: Get the default material states. 

## interface ni::iGraphicsContextRT
Render target graphics context interface. 

### Parents:
- iGraphicsContext

### Methods:
- __iGraphicsContextRT::ChangeRenderTarget__(_tU32_ anIndex, _iTexture\*_ apRT) -> _tBool_: Change a render target. 
- __iGraphicsContextRT::ChangeDepthStencil__(_iTexture\*_ apDS) -> _tBool_: Change the depth stencil. 

## interface ni::iGraphicsContext
Graphics context description interface. 

### Parents:
- iUnknown

### Methods:
- __iGraphicsContext::GetGraphics__() -> _iGraphics\*_: Get the context's graphics object. 
- __iGraphicsContext::GetDriver__() -> _iGraphicsDriver\*_: Get the context's driver. 
- __iGraphicsContext::GetWidth__() -> _tU32_: Get the context width. 
- __iGraphicsContext::GetHeight__() -> _tU32_: Get the context height. 
- __iGraphicsContext::ClearBuffers__(_tClearBuffersFlags_ clearBuffer, _tU32_ anColor, _tF32_ afDepth, _tI32_ anStencil) -> _void_: Clear the specified main buffers. 
- __iGraphicsContext::GetRenderTarget__(_tU32_ anIndex) -> _iTexture\*_: Get the render target set on the specified index. 
- __iGraphicsContext::GetDepthStencil__() -> _iTexture\*_: Get the depth stencil target. 
- __iGraphicsContext::Display__(_tGraphicsDisplayFlags_ aFlags, _const sRecti&_ aRect) -> _tBool_: Display the canvas in its destination window/context. 
- __iGraphicsContext::DrawOperation__(_iDrawOperation\*_ apDrawOp) -> _tBool_: Draw the specified draw operation. 
- __iGraphicsContext::CaptureFrontBuffer__() -> _iBitmap2D\*_: Capture the front buffer. 
- __iGraphicsContext::SetViewport__(_const sRecti&_ aVal) -> _void_: Set the viewport. 
- __iGraphicsContext::GetViewport__() -> _sRecti_: Get the viewport. 
- __iGraphicsContext::SetScissorRect__(_const sRecti&_ aVal) -> _void_: Set the scissor rectangle. 
- __iGraphicsContext::GetScissorRect__() -> _sRecti_: Get the scissor rectangle. 
- __iGraphicsContext::SetFixedStates__(_iFixedStates\*_ apStates) -> _tBool_: Set the default fixed pipeline states. 
- __iGraphicsContext::GetFixedStates__() -> _iFixedStates\*_: Get the default fixed pipeline states. 
- __iGraphicsContext::SetMaterial__(_iMaterial\*_ apMat) -> _tBool_: Set the default material states. 
- __iGraphicsContext::GetMaterial__() -> _const iMaterial\*_: Get the default material states. 

## enum ni::eGraphicsCaptureFlags
Graphics capture flag. 

### Values:
- __eGraphicsCaptureFlags_All__ = __niBit(0)__: Clone all draw ops up until stop at. 
- __eGraphicsCaptureFlags_CloneStopAtGeometry__ = __niBit(1)__: Cloning of the geometry of the stop at draw op. 
- __eGraphicsCaptureFlags_CloneStopAtTextures__ = __niBit(2)__: Clone the textures at the specified index. 
- __eGraphicsCaptureFlags_CloneStopAtStates__ = __niBit(3)__: Clone the states at the specified index. 
- __eGraphicsCaptureFlags_KeepStopAt__ = __niBit(4)__: Replace the states of the stop at draw op by the states cloned during the first capture of that draw op. This allows the states to be modified dynamically. 
- __eGraphicsCaptureFlags_NoTime__ = __niBit(5)__: Do not count time perf when capturing the draw ops. 
- __eGraphicsCaptureFlags_BreakOnStopAtBegin__ = __niBit(6)__: Breakpoint on StopAt begin drawop. 
- __eGraphicsCaptureFlags_BreakOnStopAtEnd__ = __niBit(7)__: Breakpoint on StopAt end drawop. 

## interface ni::iGraphicsDrawOpCapture
Draw operation capture object. 

### Parents:
- iUnknown

### Methods:
- __iGraphicsDrawOpCapture::BeginCapture__() -> _tBool_: Begin capturing. 
- __iGraphicsDrawOpCapture::EndCapture__() -> _tU32_: End capturing. 
- __iGraphicsDrawOpCapture::GetIsCapturing__() -> _tBool_: Return whether we the object is currently capturing. 
- __iGraphicsDrawOpCapture::ClearCapture__() -> _void_: Clear all captured data. 
- __iGraphicsDrawOpCapture::SetCaptureFlags__(_tGraphicsCaptureFlags_ aFlags) -> _void_: Set the capture flags. 
- __iGraphicsDrawOpCapture::GetCaptureFlags__() -> _tGraphicsCaptureFlags_: Get the capture flags. 
- __iGraphicsDrawOpCapture::SetCaptureStopAt__(_tU32_ anStopAt) -> _void_: Set the current stop at index. 
- __iGraphicsDrawOpCapture::GetCaptureStopAt__() -> _tU32_: Get the current stop at index. 
- __iGraphicsDrawOpCapture::GetNumCaptured__() -> _tU32_: Get the number of draw ops captured. 
- __iGraphicsDrawOpCapture::GetCapturedClear__(_tU32_ anIndex) -> _sVec4i_: Get the captured clear operation parameters. 
- __iGraphicsDrawOpCapture::GetCapturedDrawOp__(_tU32_ anIndex) -> _iDrawOperation\*_: Get the draw operation at the specified index. 
- __iGraphicsDrawOpCapture::GetCapturedDrawOpTime__(_tU32_ anIndex) -> _tF32_: Get the time taken to submit the specified draw operation 
- __iGraphicsDrawOpCapture::GetCapturedDrawOpContext__(_tU32_ anIndex) -> _iGraphicsContext\*_: Get the context that submited the draw operation. 
- __iGraphicsDrawOpCapture::BeginCaptureDrawOp__(_iGraphicsContext\*_ apContext, _iDrawOperation\*_ apDrawOp, _const sVec4i&_ aClearParams) -> _tBool_: Called to capture a draw operation. 
- __iGraphicsDrawOpCapture::EndCaptureDrawOp__(_iGraphicsContext\*_ apContext, _iDrawOperation\*_ apDrawOp, _const sVec4i&_ aClearParams) -> _void_: Called to finish the draw operation capture. 

## interface ni::iGraphicsDriver
Graphics driver. 

### Parents:
- iUnknown

### Remarks:
- This interface should never be used directly, iGraphics is the interface that should be used. 

### Methods:
- __iGraphicsDriver::GetGraphics__() -> _iGraphics\*_: Get the parent iGraphics interface. 
- __iGraphicsDriver::GetName__() -> _const achar\*_: Get the driver's name. 
- __iGraphicsDriver::GetDesc__() -> _const achar\*_: Get the driver's description. 
- __iGraphicsDriver::GetDeviceName__() -> _const achar\*_: Get the driver device's name. 
- __iGraphicsDriver::GetCaps__(_eGraphicsCaps_ aCaps) -> _tInt_: Get the driver's capabilities. 
- __iGraphicsDriver::GetGraphicsDriverImplFlags__() -> _tGraphicsDriverImplFlags_: Get the driver implementation details. 
- __iGraphicsDriver::SetDrawOpCapture__(_iGraphicsDrawOpCapture\*_ apCapture) -> _void_: Set the draw op capture object. 
- __iGraphicsDriver::GetDrawOpCapture__() -> _iGraphicsDrawOpCapture\*_: Get the draw op capture object. 
- __iGraphicsDriver::CreateContextForWindow__(_iOSWindow\*_ apWindow, _const achar\*_ aaszBBFormat, _const achar\*_ aaszDSFormat, _tU32_ anSwapInterval, _tTextureFlags_ aBackBufferFlags) -> _iGraphicsContext\*_: Create a new context for the specified OS window. 
- __iGraphicsDriver::CreateContextForRenderTargets__(_iTexture\*_ apRT0, _iTexture\*_ apRT1, _iTexture\*_ apRT2, _iTexture\*_ apRT3, _iTexture\*_ apDS) -> _iGraphicsContextRT\*_: Creates a new context for the specified render targets. 
- __iGraphicsDriver::ResetAllCaches__() -> _tBool_: Reset all graphics driver caches. 
- __iGraphicsDriver::CheckTextureFormat__(_iBitmapFormat\*_ apFormat, _tTextureFlags_ aFlags) -> _tBool_: Check whether the specified texture format is supported and set the bitmap format object to the nearest matching native bitmap format. 
- __iGraphicsDriver::CreateTexture__(_iHString\*_ ahspName, _eBitmapType_ aType, _const achar\*_ aaszFormat, _tU32_ anNumMipMaps, _tU32_ anWidth, _tU32_ anHeight, _tU32_ anDepth, _tTextureFlags_ aFlags) -> _iTexture\*_: Create a new texture. 
- __iGraphicsDriver::BlitBitmapToTexture__(_iBitmap2D\*_ apSrc, _iTexture\*_ apDest, _tU32_ anDestLevel, _const sRecti&_ aSrcRect, _const sRecti&_ aDestRect, _eTextureBlitFlags_ aFlags) -> _tBool_: Blit a bitmap to a texture. 
- __iGraphicsDriver::BlitTextureToBitmap__(_iTexture\*_ apSrc, _tU32_ anSrcLevel, _iBitmap2D\*_ apDest, _const sRecti&_ aSrcRect, _const sRecti&_ aDestRect, _eTextureBlitFlags_ aFlags) -> _tBool_: Blit a texture to a bitmap. 
- __iGraphicsDriver::BlitTextureToTexture__(_iTexture\*_ apSrc, _tU32_ anSrcLevel, _iTexture\*_ apDest, _tU32_ anDestLevel, _const sRecti&_ aSrcRect, _const sRecti&_ aDestRect, _eTextureBlitFlags_ aFlags) -> _tBool_: Blit a texture into another texture. 
- __iGraphicsDriver::BlitBitmap3DToTexture__(_iBitmap3D\*_ apSrc, _iTexture\*_ apDest, _tU32_ anDestLevel, _const sVec3i&_ aSrcMin, _const sVec3i&_ aDestMin, _const sVec3i&_ avSize, _eTextureBlitFlags_ aFlags) -> _tBool_: Blit a 3d bitmap to a 3d texture. 
- __iGraphicsDriver::BlitTextureToBitmap3D__(_iTexture\*_ apSrc, _tU32_ anSrcLevel, _iBitmap3D\*_ apDest, _const sVec3i&_ aSrcMin, _const sVec3i&_ aDestMin, _const sVec3i&_ avSize, _eTextureBlitFlags_ aFlags) -> _tBool_: Blit a 3d texture to a 3d bitmap. 
- __iGraphicsDriver::GetNumShaderProfile__(_eShaderUnit_ aUnit) -> _tU32_: Get the number of Shader profile supported in the specified unit. 
- __iGraphicsDriver::GetShaderProfile__(_eShaderUnit_ aUnit, _tU32_ anIndex) -> _iHString\*_: Get the profile at the specified index. 
- __iGraphicsDriver::CreateShader__(_iHString\*_ ahspName, _iFile\*_ apByteCode) -> _iShader\*_: Load a compiled shader from the specified bytecode. 
- __iGraphicsDriver::CreateOcclusionQuery__() -> _iOcclusionQuery\*_: Create a new occlusion query object. 
- __iGraphicsDriver::CreateVertexArray__(_tU32_ anNumVertices, _tFVF_ anFVF, _eArrayUsage_ aUsage) -> _iVertexArray\*_: Create a new driver vertex array instance. 
- __iGraphicsDriver::CreateIndexArray__(_eGraphicsPrimitiveType_ aPrimitiveType, _tU32_ anNumIndex, _tU32_ anMaxVertexIndex, _eArrayUsage_ aUsage) -> _iIndexArray\*_: Create a new driver index array instance. 
- __iGraphicsDriver::CreateShaderConstants__(_tU32_ anMaxRegisters) -> _iShaderConstants\*_: Creates a new empty driver shader constants instance. 
- __iGraphicsDriver::CompileSamplerStates__(_iSamplerStates\*_ apStates) -> _tIntPtr_: Compile a sampler states. 
- __iGraphicsDriver::CompileRasterizerStates__(_iRasterizerStates\*_ apStates) -> _tIntPtr_: Compile a rasterizer states. 
- __iGraphicsDriver::CompileDepthStencilStates__(_iDepthStencilStates\*_ apStates) -> _tIntPtr_: Compile a depth stencil states. 

## enum ni::eGraphicsCaptureFlags
Graphics capture flag. 

### Values:
- __eGraphicsCaptureFlags_All__ = __niBit(0)__: Clone all draw ops up until stop at. 
- __eGraphicsCaptureFlags_CloneStopAtGeometry__ = __niBit(1)__: Cloning of the geometry of the stop at draw op. 
- __eGraphicsCaptureFlags_CloneStopAtTextures__ = __niBit(2)__: Clone the textures at the specified index. 
- __eGraphicsCaptureFlags_CloneStopAtStates__ = __niBit(3)__: Clone the states at the specified index. 
- __eGraphicsCaptureFlags_KeepStopAt__ = __niBit(4)__: Replace the states of the stop at draw op by the states cloned during the first capture of that draw op. This allows the states to be modified dynamically. 
- __eGraphicsCaptureFlags_NoTime__ = __niBit(5)__: Do not count time perf when capturing the draw ops. 
- __eGraphicsCaptureFlags_BreakOnStopAtBegin__ = __niBit(6)__: Breakpoint on StopAt begin drawop. 
- __eGraphicsCaptureFlags_BreakOnStopAtEnd__ = __niBit(7)__: Breakpoint on StopAt end drawop. 

## interface ni::iSamplerStates
Sampler states interface. 

### Parents:
- iUnknown

### Methods:
- __iSamplerStates::Copy__(_const iSamplerStates\*_ apStates) -> _tBool_: Copy another sampler states. 
- __iSamplerStates::Clone__() -> _iSamplerStates\*_: Clone this sampler states. 
- __iSamplerStates::GetIsCompiled__() -> _tBool_: Return whether the sampler states are compiled (read-only) 
- __iSamplerStates::SetFilter__(_eSamplerFilter_ aFilter) -> _tBool_: Set the filtering mode. (default eSamplerFilter_Point) 
- __iSamplerStates::GetFilter__() -> _eSamplerFilter_: Get the filtering mode. 
- __iSamplerStates::SetWrapS__(_eSamplerWrap_ aWrap) -> _tBool_: Set the S-axis wrapping mode. (default eSamplerWrap_Clamp) 
- __iSamplerStates::GetWrapS__() -> _eSamplerWrap_: Get the S-axis wrapping mode. 
- __iSamplerStates::SetWrapT__(_eSamplerWrap_ aWrap) -> _tBool_: Set the T-axis wrapping mode. (default eSamplerWrap_Clamp) 
- __iSamplerStates::GetWrapT__() -> _eSamplerWrap_: Get the T-axis wrapping mode. 
- __iSamplerStates::SetWrapR__(_eSamplerWrap_ aWrap) -> _tBool_: Set the R-axis wrapping mode. (default eSamplerWrap_Clamp) 
- __iSamplerStates::GetWrapR__() -> _eSamplerWrap_: Get the R-axis wrapping mode. 
- __iSamplerStates::SetBorderColor__(_const sColor4f&_ avColor) -> _tBool_: Set the border color, for border sampler wrap mode. 
- __iSamplerStates::GetBorderColor__() -> _const sColor4f&_: Get the border color. 
- __iSamplerStates::GetDescStructPtr__() -> _tPtr_: Get the states description structure pointer. 
- __iSamplerStates::SerializeDataTable__(_ni::iDataTable\*_ apDT, _tSerializeFlags_ aFlags) -> _ni::tBool_: Serialize the states. 

## interface ni::iDepthStencilStates
DepthStencil states 

### Parents:
- iUnknown

### Methods:
- __iDepthStencilStates::Copy__(_const iDepthStencilStates\*_ apStates) -> _tBool_: Copy another depth-stencil states. 
- __iDepthStencilStates::Clone__() -> _iDepthStencilStates\*_: Clone this depth-stencil states. 
- __iDepthStencilStates::GetIsCompiled__() -> _tBool_: Return whether the depth-stencil states are compiled (read-only) 
- __iDepthStencilStates::SetDepthTest__(_tBool_ aVal) -> _tBool_: Set whether the depth test is enabled. (default false) 
- __iDepthStencilStates::GetDepthTest__() -> _tBool_: Get whether the depth test is enabled. 
- __iDepthStencilStates::SetDepthTestWrite__(_tBool_ aVal) -> _tBool_: Set whether the depth test write is enabled. (default true) 
- __iDepthStencilStates::GetDepthTestWrite__() -> _tBool_: Get whether the depth test write is enabled. 
- __iDepthStencilStates::SetDepthTestCompare__(_eGraphicsCompare_ aVal) -> _tBool_: Set depth test compare function. (default eGraphicsCompare_LessEqual) 
- __iDepthStencilStates::GetDepthTestCompare__() -> _eGraphicsCompare_: Get depth test compare function. 
- __iDepthStencilStates::SetStencilMode__(_eStencilMode_ aVal) -> _tBool_: Set the stencil mode. (default eStencilMode_None) 
- __iDepthStencilStates::GetStencilMode__() -> _eStencilMode_: Get the stencil mode. 
- __iDepthStencilStates::SetStencilRef__(_tI32_ aVal) -> _tBool_: Set the stencil reference value. (default 0) 
- __iDepthStencilStates::GetStencilRef__() -> _tI32_: Get the stencil reference value. 
- __iDepthStencilStates::SetStencilMask__(_tU32_ aVal) -> _tBool_: Set the stencil mask. (default 0xFFFFFFFF) 
- __iDepthStencilStates::GetStencilMask__() -> _tU32_: Get the stencil mask. 
- __iDepthStencilStates::SetStencilFrontCompare__(_eGraphicsCompare_ aVal) -> _tBool_: Set the stencil front test compare function. (eGraphicsCompare_Never) 
- __iDepthStencilStates::GetStencilFrontCompare__() -> _eGraphicsCompare_: Get the stencil front test compare function. 
- __iDepthStencilStates::SetStencilFrontFail__(_eStencilOp_ aVal) -> _tBool_: Set the stencil operation when the stencil front test fail. (eStencilOp_Keep) 
- __iDepthStencilStates::GetStencilFrontFail__() -> _eStencilOp_: Get the stencil operation when the stencil front test fail. 
- __iDepthStencilStates::SetStencilFrontPassDepthFail__(_eStencilOp_ aVal) -> _tBool_: Set the stencil operation when the stencil front test pass and the depth test fail. (eStencilOp_Keep) 
- __iDepthStencilStates::GetStencilFrontPassDepthFail__() -> _eStencilOp_: Get the stencil operation when the stencil front test pass and the depth test fail. (eStencilOp_Keep) 
- __iDepthStencilStates::SetStencilFrontPassDepthPass__(_eStencilOp_ aVal) -> _tBool_: Set the stencil operation when the stencil front test pass and the depth test pass. (eStencilOp_Keep) 
- __iDepthStencilStates::GetStencilFrontPassDepthPass__() -> _eStencilOp_: Get the stencil operation when the stencil front test pass and the depth test pass. 
- __iDepthStencilStates::SetStencilBackCompare__(_eGraphicsCompare_ aVal) -> _tBool_: Set the stencil back test compare function. (eGraphicsCompare_Never) 
- __iDepthStencilStates::GetStencilBackCompare__() -> _eGraphicsCompare_: Get the stencil back test compare function. 
- __iDepthStencilStates::SetStencilBackFail__(_eStencilOp_ aVal) -> _tBool_: Set the stencil operation when the stencil back test fail. (eStencilOp_Keep) 
- __iDepthStencilStates::GetStencilBackFail__() -> _eStencilOp_: Get the stencil operation when the stencil back test fail. 
- __iDepthStencilStates::SetStencilBackPassDepthFail__(_eStencilOp_ aVal) -> _tBool_: Set the stencil operation when the stencil back test pass and the depth test fail. (eStencilOp_Keep) 
- __iDepthStencilStates::GetStencilBackPassDepthFail__() -> _eStencilOp_: Get the stencil operation when the stencil back test pass and the depth test fail. 
- __iDepthStencilStates::SetStencilBackPassDepthPass__(_eStencilOp_ aVal) -> _tBool_: Set the stencil operation when the stencil back test pass and the depth test pass. (eStencilOp_Keep) 
- __iDepthStencilStates::GetStencilBackPassDepthPass__() -> _eStencilOp_: Get the stencil operation when the stencil back test pass and the depth test pass. 
- __iDepthStencilStates::GetDescStructPtr__() -> _tPtr_: Get the states description structure pointer. 
- __iDepthStencilStates::SerializeDataTable__(_ni::iDataTable\*_ apDT, _tSerializeFlags_ aFlags) -> _ni::tBool_: Serialize the states. 

## interface ni::iRasterizerStates
Rasterizer states 

### Parents:
- iUnknown

### Methods:
- __iRasterizerStates::Copy__(_const iRasterizerStates\*_ apStates) -> _tBool_: Copy another rasterizer states. 
- __iRasterizerStates::Clone__() -> _iRasterizerStates\*_: Clone this rasterizer states. 
- __iRasterizerStates::GetIsCompiled__() -> _tBool_: Return whether the rasterizer states are compiled (read-only) 
- __iRasterizerStates::SetWireframe__(_tBool_ abWireframe) -> _tBool_: Set wireframe rendering. (default false) 
- __iRasterizerStates::GetWireframe__() -> _tBool_: Get wireframe rendering. 
- __iRasterizerStates::SetCullingMode__(_eCullingMode_ aMode) -> _tBool_: Set the culling mode. (default eCullingMode_None) 
- __iRasterizerStates::GetCullingMode__() -> _eCullingMode_: Get the culling mode. 
- __iRasterizerStates::SetColorWriteMask__(_eColorWriteMask_ aMask) -> _tBool_: Set the color write mask. (default eColorWriteMask_All) 
- __iRasterizerStates::GetColorWriteMask__() -> _eColorWriteMask_: Get the color write mask. 
- __iRasterizerStates::SetScissorTest__(_tBool_ abTest) -> _tBool_: Set whether the scissor test is enabled. (default false) 
- __iRasterizerStates::GetScissorTest__() -> _tBool_: Get whether the scissor test is enabled. 
- __iRasterizerStates::SetDepthBiasFactor__(_tF32_ aVal) -> _tBool_: Set the depth bias factor. (default 0) 
- __iRasterizerStates::GetDepthBiasFactor__() -> _tF32_: Get the depth bias factor. 
- __iRasterizerStates::SetDepthBiasUnitScale__(_tF32_ aVal) -> _tBool_: Set the depth bias unit scale factor. (default 0) 
- __iRasterizerStates::GetDepthBiasUnitScale__() -> _tF32_: Get the depth bias unit scale factor. 
- __iRasterizerStates::GetDescStructPtr__() -> _tPtr_: Get the states description structure pointer. 
- __iRasterizerStates::SerializeDataTable__(_ni::iDataTable\*_ apDT, _tSerializeFlags_ aFlags) -> _ni::tBool_: Serialize the states. 

## interface ni::iFixedStates
Graphics fixed pipeline states interface. 

### Parents:
- iUnknown

### Methods:
- __iFixedStates::Copy__(_const iFixedStates\*_ apStates) -> _tBool_: Copy another fixed pipeline states. 
- __iFixedStates::Clone__() -> _iFixedStates\*_: Clone this fixed pipeline states. 
- __iFixedStates::SetCameraViewMatrix__(_const sMatrixf&_ aVal) -> _void_: Set the fixed pipeline camera view matrix. (default identity) 
- __iFixedStates::SetOnlyCameraViewMatrix__(_const sMatrixf&_ aVal) -> _void_: Set only the fixed pipeline camera view matrix. (default identity) 
- __iFixedStates::GetCameraViewMatrix__() -> _sMatrixf_: Get the fixed pipeline camera view matrix. 
- __iFixedStates::GetCameraInvViewMatrix__() -> _sMatrixf_: Get the inverse camera view matrix. 
- __iFixedStates::SetCameraProjectionMatrix__(_const sMatrixf&_ aVal) -> _void_: Set the fixed pipeline camera projection matrix. (default identity) 
- __iFixedStates::SetOnlyCameraProjectionMatrix__(_const sMatrixf&_ aVal) -> _void_: Set only the fixed pipeline camera projection matrix. (default identity) 
- __iFixedStates::GetCameraProjectionMatrix__() -> _sMatrixf_: Get the fixed pipeline camera projection matrix. 
- __iFixedStates::GetCameraInvProjectionMatrix__() -> _sMatrixf_: Get the inverse camera projection matrix. 
- __iFixedStates::GetCameraViewProjectionMatrix__() -> _sMatrixf_: Get the camera view projection matrix. 
- __iFixedStates::GetCameraInvViewProjectionMatrix__() -> _sMatrixf_: Get the camera inverse view projection matrix. 
- __iFixedStates::SetViewMatrix__(_const sMatrixf&_ aVal) -> _void_: Set the fixed pipeline view matrix. (default identity) 
- __iFixedStates::GetViewMatrix__() -> _sMatrixf_: Get the fixed pipeline view matrix. 
- __iFixedStates::SetProjectionMatrix__(_const sMatrixf&_ aVal) -> _void_: Set the fixed pipeline projection matrix. (default identity) 
- __iFixedStates::GetProjectionMatrix__() -> _sMatrixf_: Get the fixed pipeline projection matrix. 
- __iFixedStates::GetInvViewMatrix__() -> _sMatrixf_: Get the inverse view matrix. 
- __iFixedStates::GetViewProjectionMatrix__() -> _sMatrixf_: Get the view projection matrix. 
- __iFixedStates::GetInvViewProjectionMatrix__() -> _sMatrixf_: Get the inverse view projection matrix. 
- __iFixedStates::GetInvProjectionMatrix__() -> _sMatrixf_: Get the inverse projection matrix. 
- __iFixedStates::SetLookAtMatrices__(_tBool_ abSetCameraMatrices, _const sVec3f&_ avEye, _const sVec3f&_ avAt, _const sVec3f&_ avUp, _tF32_ afFovY, _tF32_ afAspect, _tF32_ afNear, _tF32_ afFar) -> _void_: Set a look at matrix and perspective projection in the view and projection matrices. 
- __iFixedStates::SetOrthoMatrices__(_tBool_ abSetCameraMatrices, _const sRectf&_ arectViewport, _tF32_ afNear, _tF32_ afFar) -> _void_: Set an orthographic projection in the view and projection matrices. 
- __iFixedStates::GetDescStructPtr__() -> _tPtr_: Get the states description structure pointer. 
- __iFixedStates::SerializeDataTable__(_ni::iDataTable\*_ apDT, _tSerializeFlags_ aFlags) -> _ni::tBool_: Serialize the states. 

## interface ni::iSamplerStates
Sampler states interface. 

### Parents:
- iUnknown

### Methods:
- __iSamplerStates::Copy__(_const iSamplerStates\*_ apStates) -> _tBool_: Copy another sampler states. 
- __iSamplerStates::Clone__() -> _iSamplerStates\*_: Clone this sampler states. 
- __iSamplerStates::GetIsCompiled__() -> _tBool_: Return whether the sampler states are compiled (read-only) 
- __iSamplerStates::SetFilter__(_eSamplerFilter_ aFilter) -> _tBool_: Set the filtering mode. (default eSamplerFilter_Point) 
- __iSamplerStates::GetFilter__() -> _eSamplerFilter_: Get the filtering mode. 
- __iSamplerStates::SetWrapS__(_eSamplerWrap_ aWrap) -> _tBool_: Set the S-axis wrapping mode. (default eSamplerWrap_Clamp) 
- __iSamplerStates::GetWrapS__() -> _eSamplerWrap_: Get the S-axis wrapping mode. 
- __iSamplerStates::SetWrapT__(_eSamplerWrap_ aWrap) -> _tBool_: Set the T-axis wrapping mode. (default eSamplerWrap_Clamp) 
- __iSamplerStates::GetWrapT__() -> _eSamplerWrap_: Get the T-axis wrapping mode. 
- __iSamplerStates::SetWrapR__(_eSamplerWrap_ aWrap) -> _tBool_: Set the R-axis wrapping mode. (default eSamplerWrap_Clamp) 
- __iSamplerStates::GetWrapR__() -> _eSamplerWrap_: Get the R-axis wrapping mode. 
- __iSamplerStates::SetBorderColor__(_const sColor4f&_ avColor) -> _tBool_: Set the border color, for border sampler wrap mode. 
- __iSamplerStates::GetBorderColor__() -> _const sColor4f&_: Get the border color. 
- __iSamplerStates::GetDescStructPtr__() -> _tPtr_: Get the states description structure pointer. 
- __iSamplerStates::SerializeDataTable__(_ni::iDataTable\*_ apDT, _tSerializeFlags_ aFlags) -> _ni::tBool_: Serialize the states. 

## enum ni::eImageUsage
Image usage. 

### Values:
- __eImageUsage_Source__ = __0__: The usage is read-only to be used a source for rendering. 
- __eImageUsage_Target__ = __1__: The usage is write-only to be used as a render target. Previous content is preserved. 
- __eImageUsage_DepthStencil__ = __2__: For GetTexture only, grabs the depth stencil for rendering. 
- __eImageUsage_TargetDiscard__ = __3__: The usage is write-only to be used as a render target. The whole content of the target is assumed to be overwritten and so no effort to keep the previous content is made. 

## interface ni::iImage
Image interface. 

### Parents:
- iUnknown

### Methods:
- __iImage::Copy__(_iImage\*_ apImage) -> _tBool_: Copy the specified image. 
- __iImage::Clone__() -> _iImage\*_: Clone this image. 
- __iImage::GetHasBitmap__() -> _tBool_: Get whether a bitmap is already initialized in the image. 
- __iImage::GrabBitmap__(_eImageUsage_ aLock, _const sRecti&_ aDirtyRect) -> _iBitmap2D\*_: Grab the image as a bitmap to be used for some other operations. 
- __iImage::GetHasTexture__() -> _tBool_: Get whether a texture is already initialized in the image. 
- __iImage::GetHasDepthStencil__() -> _tBool_: Get whether a depth stencil is already initialized in the image. 
- __iImage::GrabTexture__(_eImageUsage_ aLock, _const sRecti&_ aDirtyRect) -> _iTexture\*_: Grab the image as a texture to be used for some other operations. 
- __iImage::GetWidth__() -> _tU32_: Get the image's width. 
- __iImage::GetHeight__() -> _tU32_: Get the image's height. 
- __iImage::GetSize__() -> _sVec2f_: Get the image's size in a vec2f. 
- __iImage::RecomputeBitmapMipmapsBeforeCopyToTexture__() -> _void_: Indicate that the bitmap's mipmaps should be recomputed the next time the bitmap is copied to the texture. 

## enum ni::eImageUsage
Image usage. 

### Values:
- __eImageUsage_Source__ = __0__: The usage is read-only to be used a source for rendering. 
- __eImageUsage_Target__ = __1__: The usage is write-only to be used as a render target. Previous content is preserved. 
- __eImageUsage_DepthStencil__ = __2__: For GetTexture only, grabs the depth stencil for rendering. 
- __eImageUsage_TargetDiscard__ = __3__: The usage is write-only to be used as a render target. The whole content of the target is assumed to be overwritten and so no effort to keep the previous content is made. 

## enum ni::eImageMapSerializeFlags
Image map serialization flags. 

### Values:
- __eImageMapSerializeFlags_Write__ = __niBit(0)__: Serialize write 
- __eImageMapSerializeFlags_Read__ = __niBit(1)__: Serialize read 

## interface ni::iImageMap
Image map interface. 

### Parents:
- iUnknown

### Methods:
- __iImageMap::SetMaxNumPages__(_tU32_ anMax) -> _void_: Set the maximum number of pages. 
- __iImageMap::GetMaxNumPages__() -> _tU32_: Get the maximum number of pages. 
- __iImageMap::SetPageSize__(_tU32_ anSize) -> _void_: Set the resolution of a page. 
- __iImageMap::GetPageSize__() -> _tU32_: Get the resolution of a page. 
- __iImageMap::SetPageMipMaps__(_tU32_ anNumMipMaps) -> _void_: Set the number of mipmaps of a page. 
- __iImageMap::GetPageMipMaps__() -> _tU32_: Get the number of mipmaps of a page. 
- __iImageMap::SetComputeMipMapsPerPage__(_tBool_ abComputeMipMapsPerPage) -> _void_: Set whether the mipmaps are computed for the whole page after an image has been added. That is regardless of whether the image added had mipmap itself. 
- __iImageMap::GetComputeMipMapsPerPage__() -> _tBool_: Get whether the mipmaps are computed for the whole page after an image has been added. 
- __iImageMap::SetPageFormat__(_iHString\*_ ahspFormat) -> _void_: Set the page format. 
- __iImageMap::GetPageFormat__() -> _iHString\*_: Get the page format. 
- __iImageMap::GetNumPages__() -> _tU32_: Get the number of pages in the image map. 
- __iImageMap::GetPage__(_tU32_ anIndex) -> _iTexture\*_: Get the specified page in the image map. 
- __iImageMap::Clear__() -> _void_: Clear the image map. 
- __iImageMap::SetDefaultImageBlendMode__(_eBlendMode_ aMode) -> _void_: Set the default blend mode. 
- __iImageMap::GetDefaultImageBlendMode__() -> _eBlendMode_: Get the default blend mode. 
- __iImageMap::SetDefaultImageFilter__(_tBool_ abFiltering) -> _void_: Set the default filtering. 
- __iImageMap::GetDefaultImageFilter__() -> _tBool_: Get the default filtering. 
- __iImageMap::GetNumImages__() -> _tU32_: Get the number of images. 
- __iImageMap::GetImage__(_tU32_ anIndex) -> _iOverlay\*_: Get the image at the specified index. 
- __iImageMap::GetImageIndex__(_iOverlay\*_ apImage) -> _tU32_: Get the index of the image at the specified index. 
- __iImageMap::GetImageFromName__(_iHString\*_ ahspName) -> _iOverlay\*_: Get the first image with the given name. 
- __iImageMap::AddImage__(_iHString\*_ ahspName, _iBitmap2D\*_ apBitmap) -> _iOverlay\*_: Add an image to the image map. 
- __iImageMap::AddImageFromResource__(_iHString\*_ ahspName, _iHString\*_ ahspRes) -> _iOverlay\*_: Add an image to the image map loading from a resource. 
- __iImageMap::AddImageFromIconSet__(_iHString\*_ ahspName, _iHString\*_ ahspFolder, _iHString\*_ ahspRes, _tU32_ anMaxRes, _tU32_ anMinRes) -> _iOverlay\*_: Add an image to the image map loading from a icon set folder. 
- __iImageMap::RemoveImage__(_iOverlay\*_ apImage) -> _tBool_: Remove an image from the image map. 
- __iImageMap::GetShouldSerialize__() -> _tBool_: Get whether the image map has been modified since the last serialize read. 
- __iImageMap::Serialize__(_ni::iFile\*_ apFile, _tImageMapSerializeFlags_ aFlags) -> _tBool_: Serialize the image map to/from the specified file. 

## enum ni::eImageMapSerializeFlags
Image map serialization flags. 

### Values:
- __eImageMapSerializeFlags_Write__ = __niBit(0)__: Serialize write 
- __eImageMapSerializeFlags_Read__ = __niBit(1)__: Serialize read 

## interface ni::iIndexArray
Index array interface 

### Parents:
- iDeviceResource

### Remarks:
- Bindable 

### Methods:
- __iIndexArray::GetPrimitiveType__() -> _eGraphicsPrimitiveType_: Get the primitive type of this index array. 
- __iIndexArray::GetNumIndices__() -> _tU32_: Get the number of indices in the given index array. 
- __iIndexArray::GetMaxVertexIndex__() -> _tU32_: Get the maximum vertex index that can be used in this index array. 
- __iIndexArray::GetUsage__() -> _eArrayUsage_: Get the usage of the given vertex array. 
- __iIndexArray::Lock__(_tU32_ ulFirstIndex, _tU32_ ulNumIndex, _eLock_ aLock) -> _tPtr_: Lock index array memory to enable writting and reading in it. 
- __iIndexArray::Unlock__() -> _tBool_: Unlock vertex array memory. 
- __iIndexArray::GetIsLocked__() -> _tBool_: Return true if the array is locked. 

## interface ni::iIndexArray
Index array interface 

### Parents:
- iDeviceResource

### Remarks:
- Bindable 

### Methods:
- __iIndexArray::GetPrimitiveType__() -> _eGraphicsPrimitiveType_: Get the primitive type of this index array. 
- __iIndexArray::GetNumIndices__() -> _tU32_: Get the number of indices in the given index array. 
- __iIndexArray::GetMaxVertexIndex__() -> _tU32_: Get the maximum vertex index that can be used in this index array. 
- __iIndexArray::GetUsage__() -> _eArrayUsage_: Get the usage of the given vertex array. 
- __iIndexArray::Lock__(_tU32_ ulFirstIndex, _tU32_ ulNumIndex, _eLock_ aLock) -> _tPtr_: Lock index array memory to enable writting and reading in it. 
- __iIndexArray::Unlock__() -> _tBool_: Unlock vertex array memory. 
- __iIndexArray::GetIsLocked__() -> _tBool_: Return true if the array is locked. 

## enum ni::eIntersectionResult
Intersection result. 

### Values:
- __eIntersectionResult_None__ = __0__: No intersection result. 
- __eIntersectionResult_Inside__ = __1__: Inside the bounding volume. 
- __eIntersectionResult_Intersect__ = __2__: Intersect the bounding volume. 

## interface ni::iIntersection
Intersection result interface. 

### Parents:
- iUnknown

### Methods:
- __iIntersection::SetResult__(_eIntersectionResult_ aResult) -> _void_: Set the intersection result. 
- __iIntersection::GetResult__() -> _eIntersectionResult_: Get the intersection result. 
- __iIntersection::SetPosition__(_const sVec3f&_ avPos) -> _void_: Set the intersection's position. 
- __iIntersection::GetPosition__() -> _sVec3f_: Get the intersection's position. 
- __iIntersection::SetBaryCentric__(_const sVec2f&_ avBC) -> _void_: Set the intersection's barycentric coordinate. 
- __iIntersection::GetBaryCentric__() -> _sVec2f_: Get the intersection's barycentric coordinate. 
- __iIntersection::SetPolygonIndex__(_tU32_ anIndex) -> _void_: Set the index of the intersected polygon. 
- __iIntersection::GetPolygonIndex__() -> _tU32_: Get the index of the intersected polygon. 

## enum ni::eIntersectionResult
Intersection result. 

### Values:
- __eIntersectionResult_None__ = __0__: No intersection result. 
- __eIntersectionResult_Inside__ = __1__: Inside the bounding volume. 
- __eIntersectionResult_Intersect__ = __2__: Intersect the bounding volume. 

## interface ni::iJpegReader
Jpeg reader interface. 

### Parents:
- iUnknown

### Methods:
- __iJpegReader::ReadHeaderTables__() -> _tBool_: Read the jpeg header tables only. 
- __iJpegReader::BeginRead__() -> _tBool_: Start reading a jpeg image. 
- __iJpegReader::EndRead__() -> _tBool_: End reading a jpeg image. 
- __iJpegReader::DiscardBuffer__() -> _tBool_: Discard existing bytes in the buffer. 
- __iJpegReader::GetFile__() -> _iFile\*_: Get the file from which the data are read. 
- __iJpegReader::GetWidth__() -> _tU32_: Get the width of the current image. 
- __iJpegReader::GetHeight__() -> _tU32_: Get the height of the current image. 
- __iJpegReader::GetNumComponents__() -> _tU32_: Get the number of 8bits components. 
- __iJpegReader::GetColorSpace__() -> _eColorSpace_: Get the color space. 
- __iJpegReader::ReadScanline__(_iFile\*_ apOut) -> _tBool_: Read the next scanline. 
- __iJpegReader::ReadBitmap__(_iGraphics\*_ apGraphics) -> _iBitmap2D\*_: Read a 2d bitmap from the result of the next begin/end read. 

## interface ni::iJpegReader
Jpeg reader interface. 

### Parents:
- iUnknown

### Methods:
- __iJpegReader::ReadHeaderTables__() -> _tBool_: Read the jpeg header tables only. 
- __iJpegReader::BeginRead__() -> _tBool_: Start reading a jpeg image. 
- __iJpegReader::EndRead__() -> _tBool_: End reading a jpeg image. 
- __iJpegReader::DiscardBuffer__() -> _tBool_: Discard existing bytes in the buffer. 
- __iJpegReader::GetFile__() -> _iFile\*_: Get the file from which the data are read. 
- __iJpegReader::GetWidth__() -> _tU32_: Get the width of the current image. 
- __iJpegReader::GetHeight__() -> _tU32_: Get the height of the current image. 
- __iJpegReader::GetNumComponents__() -> _tU32_: Get the number of 8bits components. 
- __iJpegReader::GetColorSpace__() -> _eColorSpace_: Get the color space. 
- __iJpegReader::ReadScanline__(_iFile\*_ apOut) -> _tBool_: Read the next scanline. 
- __iJpegReader::ReadBitmap__(_iGraphics\*_ apGraphics) -> _iBitmap2D\*_: Read a 2d bitmap from the result of the next begin/end read. 

## enum ni::eJpegWriteFlags
Jpeg write flags 

### Values:
- __eJpegWriteFlags_None__ = __0__: No flags. 
- __eJpegWriteFlags_YCoCg__ = __niBit(0)__: Use the custom YCoCg color space. 
- __eJpegWriteFlags_Alpha__ = __niBit(1)__: Has an alpha channel, implies the use of the YCoCg(A) colorspace. 

## interface ni::iJpegWriter
Jpeg writer interface. 

### Parents:
- iUnknown

### Methods:
- __iJpegWriter::BeginWrite__(_iFile\*_ apDest, _tU32_ anWidth, _tU32_ anHeight, _eColorSpace_ aInCS, _tU32_ anC, _tU32_ anQuality, _tJpegWriteFlags_ aFlags) -> _tBool_: Begin writing a new jpeg file. 
- __iJpegWriter::EndWrite__() -> _tBool_: End writing the jpeg file. 
- __iJpegWriter::WriteScanline__(_iFile\*_ apSrc) -> _tBool_: Write a scanline. 
- __iJpegWriter::WriteBitmap__(_iFile\*_ apDest, _const iBitmap2D\*_ apBmp, _tU32_ anQuality, _tJpegWriteFlags_ aFlags) -> _tBool_: Write a 2d bitmap. 

## enum ni::eJpegWriteFlags
Jpeg write flags 

### Values:
- __eJpegWriteFlags_None__ = __0__: No flags. 
- __eJpegWriteFlags_YCoCg__ = __niBit(0)__: Use the custom YCoCg color space. 
- __eJpegWriteFlags_Alpha__ = __niBit(1)__: Has an alpha channel, implies the use of the YCoCg(A) colorspace. 

## enum ni::eMaterialFlags
Material flags. 

### Values:
- __eMaterialFlags_DoubleSided__ = __niBit(0)__: Material is double sided. 
- __eMaterialFlags_Translucent__ = __niBit(1)__: Material is translucent. 
- __eMaterialFlags_Transparent__ = __niBit(2)__: Material is transparent. 
- __eMaterialFlags_DiffuseModulate__ = __niBit(3)__: Multiply the diffuse channel texture by the diffuse channel's color. 
- __eMaterialFlags_Vertex__ = __niBit(4)__: The material is vertex lit. 
- __eMaterialFlags_HeightMap__ = __niBit(5)__: The material has a height map. 
- __eMaterialFlags_NormalMap__ = __niBit(6)__: The material uses a normal map. Otherwise it's considered to be a grayscale bump. 
- __eMaterialFlags_Refraction__ = __niBit(7)__: The material is refracting. 
- __eMaterialFlags_Decal__ = __niBit(8)__: The material is used as a decal. 
- __eMaterialFlags_TileMap__ = __niBit(9)__: The material is a tilemap. 
- __eMaterialFlags_DepthOnly__ = __niBit(10)__: The material should only be drawn in the depth buffer. (no color write) 
- __eMaterialFlags_NoShadow__ = __niBit(11)__: The material doesn't cast shadow. 
- __eMaterialFlags_NoLighting__ = __niBit(12)__: The material shouldn't be lit. 
- __eMaterialFlags_NoDraw__ = __niBit(13)__: The material isnt drawn. 
- __eMaterialFlags_DistanceField__ = __niBit(14)__: The material's opacity channel contains a distance field. 
- __eMaterialFlags_TransparentAA__ = __niBit(15)__: Enable transparent (alpha-tested) anti-aliasing. 
- __eMaterialFlags_NoCollision__ = __niBit(16)__: No collision mesh should be associated with this material. 
- __eMaterialFlags_PolygonOffset__ = __niBit(17)__: Using polygon offset in this material 

## enum ni::eMaterialChannel
Material channel 

### Values:
- __eMaterialChannel_Base__ = __0__: Base texture map. RGB : Diffuse/albedo color Alpha : Opacity Default Blend mode : NoBlending 
- __eMaterialChannel_Opacity__ = __1__: Opacity/Detail texture map. RGB : Detail Alpha : Opacity/Detail Default Blend mode : NoBlending 
- __eMaterialChannel_Bump__ = __2__: Bump map. RGB : Normal map. Alpha : Height map. Default Blend mode : NoBlending 
- __eMaterialChannel_Specular__ = __3__: Specular map. RGB : Specular color Grayscale : Gloss. Specular color alpha contains the specular power. Default Blend mode : NoBlending 
- __eMaterialChannel_Environment__ = __4__: Environment map. RGB : Color Default Blend mode : Modulate 
- __eMaterialChannel_Ambient__ = __5__: Light/ambient map. RGB : Light color Alpha : Light intensity Default Blend mode : Modulate 
- __eMaterialChannel_Emissive__ = __6__: Emissive map. RGB : Color Alpha : Directional coefficient. Default Blend mode : Additive 
- __eMaterialChannel_Refraction__ = __7__: Refraction direction map. RGB : Refraction direction Default Blend mode : NoBlending 
- __eMaterialChannel_T0__ = __8__: User 0 map. Default Blend mode : NoBlending 
- __eMaterialChannel_T1__ = __9__: User 1 map. Default Blend mode : NoBlending 
- __eMaterialChannel_T2__ = __10__: User 2 map. Default Blend mode : NoBlending 
- __eMaterialChannel_T3__ = __11__: User 3 map. Default Blend mode : NoBlending 
- __eMaterialChannel_T4__ = __12__: User 4 map. Default Blend mode : NoBlending 
- __eMaterialChannel_T5__ = __13__: User 5 map. Default Blend mode : NoBlending 
- __eMaterialChannel_T6__ = __14__: User 6 map. Default Blend mode : NoBlending 
- __eMaterialChannel_T7__ = __15__: User 7 map. Default Blend mode : NoBlending 
- __eMaterialChannel_Last__ = __16__: \internal Default Blend mode : NoBlending 

## enum ni::eMaterialExpression
Material expressions 

### Values:
- __eMaterialExpression_Tex0__ = __0__: Texture channel 0 matrix expression. Shader uniform: float4 fpsExprTex0. 
- __eMaterialExpression_Tex1__ = __1__: Texture channel 1 matrix expression. Shader uniform: float4 fpsExprTex1. 
- __eMaterialExpression_Matrix0__ = __2__: Generic matrix expression. Shader uniform: float4x4 fpsExprMatrix0. 
- __eMaterialExpression_Matrix1__ = __3__: Generic matrix expression. Shader uniform: float4x4 fpsExprMatrix1. 
- __eMaterialExpression_Last__ = __4__: \internal 

## interface ni::iMaterial
Material interface. 

### Parents:
- iUnknown

### Methods:
- __iMaterial::GetGraphics__() -> _iGraphics\*_: Get the parent graphics object. 
- __iMaterial::SetName__(_iHString\*_ ahspName) -> _void_: Set the material's name. 
- __iMaterial::GetName__() -> _iHString\*_: Get the material's name. 
- __iMaterial::SetClass__(_iHString\*_ ahspName) -> _void_: Set the material's class. 
- __iMaterial::GetClass__() -> _iHString\*_: Get the material's class. 
- __iMaterial::GetWidth__() -> _tU32_: Get the texture width. 
- __iMaterial::GetHeight__() -> _tU32_: Get the texture height. 
- __iMaterial::GetDepth__() -> _tU32_: Get the texture depth. 
- __iMaterial::SetFlags__(_tMaterialFlags_ aFlags) -> _void_: Set the material's flags. 
- __iMaterial::GetFlags__() -> _tMaterialFlags_: Get the material's flags. 
- __iMaterial::SetBlendMode__(_eBlendMode_ aBlendMode) -> _tBool_: Set the material's blend mode. 
- __iMaterial::GetBlendMode__() -> _eBlendMode_: Get the material's blend mode. 
- __iMaterial::SetRasterizerStates__(_tIntPtr_ aHandle) -> _tBool_: Set the material's rasterizer states. 
- __iMaterial::GetRasterizerStates__() -> _tIntPtr_: Get the material's rasterizer states. 
- __iMaterial::SetDepthStencilStates__(_tIntPtr_ aHandle) -> _tBool_: Set the material's depth stencil states. 
- __iMaterial::GetDepthStencilStates__() -> _tIntPtr_: Get the material's depth stencil states. 
- __iMaterial::SetPolygonOffset__(_const ni::sVec2f&_ avOffset) -> _void_: Set the material's polygon offset. 
- __iMaterial::GetPolygonOffset__() -> _ni::sVec2f_: Get the material's polygon offset. 
- __iMaterial::GetHasShader__() -> _tBool_: Get whether any shader is set. 
- __iMaterial::SetShader__(_eShaderUnit_ aUnit, _iShader\*_ apProgram) -> _tBool_: Set the specified shader. 
- __iMaterial::GetShader__(_eShaderUnit_ aUnit) -> _iShader\*_: Get the specified shader. 
- __iMaterial::SetShaderConstants__(_iShaderConstants\*_ apBuffer) -> _tBool_: Set the material constant buffer. 
- __iMaterial::GetShaderConstants__() -> _iShaderConstants\*_: Get the material constant buffer. 
- __iMaterial::HasChannelTexture__(_eMaterialChannel_ aChannel) -> _tBool_: Check if the material has the specified channel texture. 
- __iMaterial::SetChannelTexture__(_eMaterialChannel_ aChannel, _iTexture\*_ apTexture) -> _tBool_: Set a material channel texture. 
- __iMaterial::GetChannelTexture__(_eMaterialChannel_ aChannel) -> _iTexture\*_: Get a material channel texture. 
- __iMaterial::SetChannelColor__(_eMaterialChannel_ aChannel, _const sColor4f&_ aColor) -> _tBool_: Set a material channel color. 
- __iMaterial::GetChannelColor__(_eMaterialChannel_ aChannel) -> _const sColor4f&_: Get a material channel color. 
- __iMaterial::SetChannelSamplerStates__(_eMaterialChannel_ aChannel, _tIntPtr_ aHandle) -> _tBool_: Set the sampler states of the specified texture channel. 
- __iMaterial::GetChannelSamplerStates__(_eMaterialChannel_ aChannel) -> _tIntPtr_: Get the sampler states of the specified texture channel. 
- __iMaterial::CopyChannel__(_eMaterialChannel_ aDestChannel, _const iMaterial\*_ apSource, _eMaterialChannel_ aSrcChannel) -> _tBool_: Copy the channel properties from another material. 
- __iMaterial::Copy__(_const iMaterial\*_ apMat) -> _tBool_: Copy the source material. 
- __iMaterial::Clone__() -> _iMaterial\*_: Clone this material. 
- __iMaterial::Serialize__(_eSerializeMode_ aMode, _iDataTable\*_ apDT, _iHString\*_ ahspBasePath) -> _tBool_: Serialize the material in a data table. 
- __iMaterial::GetDescStructPtr__() -> _tPtr_: Get the material description structure pointer. 
- __iMaterial::SetExpression__(_eMaterialExpression_ aExpr, _iHString\*_ ahspExpr) -> _void_: Set an expression of the material. 
- __iMaterial::GetExpression__(_eMaterialExpression_ aExpr) -> _iHString\*_: Get the expression of the material. 
- __iMaterial::GetExpressionValueMatrix__(_eMaterialExpression_ aExpr) -> _sMatrixf_: Get the matrix result of the specified material expression. 
- __iMaterial::GetExpressionValueVector__(_eMaterialExpression_ aExpr) -> _sVec4f_: Get the vector4 result of the specified material expression. 
- __iMaterial::SetExpressionObject__(_eMaterialExpression_ aExpr, _iHString\*_ ahspExpr, _iExpression\*_ apExpr) -> _void_: Set an expression object on the material. 
- __iMaterial::GetExpressionObject__(_eMaterialExpression_ aExpr) -> _iExpression\*_: Get the expression object. 
- __iMaterial::SetUserdata__(_iHString\*_ ahspID, _iUnknown\*_ apUserdata) -> _tBool_: Set a userdata. 
- __iMaterial::GetUserdata__(_iHString\*_ ahspID) -> _iUnknown\*_: Get a userdata. 
- __iMaterial::GetNumUserdata__() -> _tSize_: Get the number of userdata. 
- __iMaterial::GetUserdataName__(_tU32_ anIndex) -> _iHString\*_: Get the name of the user data at the specified index. 
- __iMaterial::GetUserdataFromIndex__(_tU32_ anIndex) -> _iUnknown\*_: Get the userdata at the specified index. 

## enum ni::eMaterialFlags
Material flags. 

### Values:
- __eMaterialFlags_DoubleSided__ = __niBit(0)__: Material is double sided. 
- __eMaterialFlags_Translucent__ = __niBit(1)__: Material is translucent. 
- __eMaterialFlags_Transparent__ = __niBit(2)__: Material is transparent. 
- __eMaterialFlags_DiffuseModulate__ = __niBit(3)__: Multiply the diffuse channel texture by the diffuse channel's color. 
- __eMaterialFlags_Vertex__ = __niBit(4)__: The material is vertex lit. 
- __eMaterialFlags_HeightMap__ = __niBit(5)__: The material has a height map. 
- __eMaterialFlags_NormalMap__ = __niBit(6)__: The material uses a normal map. Otherwise it's considered to be a grayscale bump. 
- __eMaterialFlags_Refraction__ = __niBit(7)__: The material is refracting. 
- __eMaterialFlags_Decal__ = __niBit(8)__: The material is used as a decal. 
- __eMaterialFlags_TileMap__ = __niBit(9)__: The material is a tilemap. 
- __eMaterialFlags_DepthOnly__ = __niBit(10)__: The material should only be drawn in the depth buffer. (no color write) 
- __eMaterialFlags_NoShadow__ = __niBit(11)__: The material doesn't cast shadow. 
- __eMaterialFlags_NoLighting__ = __niBit(12)__: The material shouldn't be lit. 
- __eMaterialFlags_NoDraw__ = __niBit(13)__: The material isnt drawn. 
- __eMaterialFlags_DistanceField__ = __niBit(14)__: The material's opacity channel contains a distance field. 
- __eMaterialFlags_TransparentAA__ = __niBit(15)__: Enable transparent (alpha-tested) anti-aliasing. 
- __eMaterialFlags_NoCollision__ = __niBit(16)__: No collision mesh should be associated with this material. 
- __eMaterialFlags_PolygonOffset__ = __niBit(17)__: Using polygon offset in this material 

## enum ni::eMaterialSerializeFlags
Material Serialization flags. 

### Values:
- __eMaterialSerializeFlags_Write__ = __niBit(0)__: Serialize write. 
- __eMaterialSerializeFlags_Read__ = __niBit(1)__: Serialize read. 
- __eMaterialSerializeFlags_Textures__ = __niBit(2)__: Serialize all the textures data in the file. 
- __eMaterialSerializeFlags_Compress__ = __niBit(3)__: Compress the content for best hardware usage. 
- __eMaterialSerializeFlags_NamesOnly__ = __niBit(4)__: Serialize only the name of the materials. 
- __eMaterialSerializeFlags_ReadExistingOnly__ = __niBit(5)__: Read only if the material was alreadu in the library. 
- __eMaterialSerializeFlags_TextureNoMipMaps__ = __niBit(19)__: Don't serialize the texture's mip maps. 
- __eMaterialSerializeFlags_TextureMaxResLo__ = __niBit(20)__: Texture max res value lower bit. (4 bits value) 
- __eMaterialSerializeFlags_TextureMaxResHi__ = __niBit(24)__: Texture max res value higher bit. (4 bits value) 
- __eMaterialSerializeFlags_TextureCompressionLo__ = __niBit(25)__: Texture compression value lower bit. (7 bits value) 
- __eMaterialSerializeFlags_TextureCompressionHi__ = __niBit(31)__: Texture compression value higher bit. (7 bits value) 

## interface ni::iMaterialLibrarySink
Material library sink. 

### Parents:
- iUnknown

### Methods:
- __iMaterialLibrarySink::OnMaterialLibrarySink_MaterialAdded__(_iMaterialLibrary\*_ apLib, _iMaterial\*_ apMat) -> _void_: Called when a material is added. 
- __iMaterialLibrarySink::OnMaterialLibrarySink_MaterialRemoved__(_iMaterialLibrary\*_ apLib, _iMaterial\*_ apMat) -> _void_: Called when a material is removed. 

## interface ni::iMaterialLibrary
Material library interface. 

### Parents:
- iUnknown

### Methods:
- __iMaterialLibrary::GetSinkList__() -> _tMaterialLibrarySinkLst\*_: Get the sink list. 
- __iMaterialLibrary::Copy__(_const iMaterialLibrary\*_ apSrc, _tBool_ abCloneMats) -> _ni::tBool_: Copy the material library. 
- __iMaterialLibrary::Clone__(_tBool_ abCloneMats) -> _iMaterialLibrary\*_: Clone the material library. 
- __iMaterialLibrary::ClearMaterials__() -> _ni::tBool_: Remove all materials. 
- __iMaterialLibrary::AddMaterial__(_ni::iMaterial\*_ apMaterial) -> _ni::tBool_: Add a material. 
- __iMaterialLibrary::RemoveMaterial__(_ni::iMaterial\*_ apMaterial) -> _ni::tBool_: Remove a material. 
- __iMaterialLibrary::GetNumMaterials__() -> _ni::tU32_: Get the number of materials. 
- __iMaterialLibrary::GetMaterial__(_ni::tU32_ anIndex) -> _ni::iMaterial\*_: Get the material at the specified index. 
- __iMaterialLibrary::GetMaterialFromName__(_ni::iHString\*_ ahspName) -> _ni::iMaterial\*_: Get the material from the specified name. 
- __iMaterialLibrary::GetMaterialIndex__(_ni::iMaterial\*_ apMaterial) -> _ni::tU32_: Get the index of the specified material. 
- __iMaterialLibrary::SerializeDataTable__(_ni::iDataTable\*_ apDT, _tMaterialSerializeFlags_ aFlags) -> _ni::tBool_: Serialize the library in a datatable. 
- __iMaterialLibrary::SerializeFile__(_ni::iFile\*_ apFile, _tMaterialSerializeFlags_ aFlags) -> _ni::tBool_: Serialize the library in a file. 
- __iMaterialLibrary::SetBasePath__(_iHString\*_ ahspBasePath) -> _void_: Set the material library's base path. 
- __iMaterialLibrary::GetBasePath__() -> _iHString\*_: Get the material library's base path. 

## enum ni::eMaterialSerializeFlags
Material Serialization flags. 

### Values:
- __eMaterialSerializeFlags_Write__ = __niBit(0)__: Serialize write. 
- __eMaterialSerializeFlags_Read__ = __niBit(1)__: Serialize read. 
- __eMaterialSerializeFlags_Textures__ = __niBit(2)__: Serialize all the textures data in the file. 
- __eMaterialSerializeFlags_Compress__ = __niBit(3)__: Compress the content for best hardware usage. 
- __eMaterialSerializeFlags_NamesOnly__ = __niBit(4)__: Serialize only the name of the materials. 
- __eMaterialSerializeFlags_ReadExistingOnly__ = __niBit(5)__: Read only if the material was alreadu in the library. 
- __eMaterialSerializeFlags_TextureNoMipMaps__ = __niBit(19)__: Don't serialize the texture's mip maps. 
- __eMaterialSerializeFlags_TextureMaxResLo__ = __niBit(20)__: Texture max res value lower bit. (4 bits value) 
- __eMaterialSerializeFlags_TextureMaxResHi__ = __niBit(24)__: Texture max res value higher bit. (4 bits value) 
- __eMaterialSerializeFlags_TextureCompressionLo__ = __niBit(25)__: Texture compression value lower bit. (7 bits value) 
- __eMaterialSerializeFlags_TextureCompressionHi__ = __niBit(31)__: Texture compression value higher bit. (7 bits value) 

## enum ni::eNUSplineType
Non-uniform spline type. 

### Values:
- __eNUSplineType_Linear__ = __0__: Linear spline. Not a spline simple linear interpolation. 
- __eNUSplineType_Rounded__ = __1__: Rounded non-uniform spline. 
- __eNUSplineType_Smooth__ = __2__: Smooth non-uniform spline. 
- __eNUSplineType_Timed__ = __3__: Timed non-uniform spline. 
- __eNUSplineType_Last__ = __4__: \internal 

## interface ni::iNUSpline
Non-uniform spline interface. 

### Parents:
- iUnknown

### Methods:
- __iNUSpline::SetType__(_eNUSplineType_ aType) -> _tBool_: Set the spline type. 
- __iNUSpline::GetType__() -> _eNUSplineType_: Get the spline type. 
- __iNUSpline::Clear__() -> _void_: Clear the spline, remove all nodes. 
- __iNUSpline::AddNode__(_const sVec4f&_ avNode) -> _void_: Add a node. 
- __iNUSpline::RemoveNode__(_tU32_ anIndex) -> _tBool_: Remove the node at the specified index. 
- __iNUSpline::GetNumNodes__() -> _tU32_: Get the number of nodes. 
- __iNUSpline::SetNode__(_tU32_ anIndex, _const sVec4f&_ avNode) -> _tBool_: Set the node at the specified index. 
- __iNUSpline::GetNode__(_tU32_ anIndex) -> _sVec4f_: Get the node at the specified index. 
- __iNUSpline::GetNodeDistance__(_tU32_ anIndex) -> _tF32_: Get the distance of the specified node. 
- __iNUSpline::GetLength__() -> _tF32_: Get the length of the path. 
- __iNUSpline::GetPosition__(_tF32_ afTime) -> _sVec3f_: Get the position at the specified time. 
- __iNUSpline::GetRelativePosition__(_tF32_ afTime) -> _sVec3f_: Get the relative position at the specified time. 
- __iNUSpline::SerializeDataTable__(_iDataTable\*_ apDT, _tSerializeFlags_ aFlags) -> _tBool_: Serialize the spline in the specified datatable. 

## enum ni::eNUSplineType
Non-uniform spline type. 

### Values:
- __eNUSplineType_Linear__ = __0__: Linear spline. Not a spline simple linear interpolation. 
- __eNUSplineType_Rounded__ = __1__: Rounded non-uniform spline. 
- __eNUSplineType_Smooth__ = __2__: Smooth non-uniform spline. 
- __eNUSplineType_Timed__ = __3__: Timed non-uniform spline. 
- __eNUSplineType_Last__ = __4__: \internal 

## enum ni::eOcclusionQueryStatus
Occlusion query status. 

### Values:
- __eOcclusionQueryStatus_NotIssued__ = __0__: No query has been issued yet. 
- __eOcclusionQueryStatus_Began__ = __1__: The query has began but is not ended yet. 
- __eOcclusionQueryStatus_Pending__ = __2__: Waiting for the query to return. 
- __eOcclusionQueryStatus_Successful__ = __3__: The query status is available. 
- __eOcclusionQueryStatus_Failed__ = __4__: The query failed. 

## interface ni::iOcclusionQuery
Occlusion query object. 

### Parents:
- iUnknown

### Methods:
- __iOcclusionQuery::Begin__() -> _tBool_: Begin the query. 
- __iOcclusionQuery::End__() -> _tBool_: End the query. 
- __iOcclusionQuery::GetStatus__(_tBool_ abWait) -> _eOcclusionQueryStatus_: Get the status of the query. 
- __iOcclusionQuery::GetResult__() -> _tU32_: Get the result of the query. 

## enum ni::eOcclusionQueryStatus
Occlusion query status. 

### Values:
- __eOcclusionQueryStatus_NotIssued__ = __0__: No query has been issued yet. 
- __eOcclusionQueryStatus_Began__ = __1__: The query has began but is not ended yet. 
- __eOcclusionQueryStatus_Pending__ = __2__: Waiting for the query to return. 
- __eOcclusionQueryStatus_Successful__ = __3__: The query status is available. 
- __eOcclusionQueryStatus_Failed__ = __4__: The query failed. 

## interface ni::iOverlay
iOverlay interface  

### Parents:
- iUnknown

### Methods:
- __iOverlay::Clone__() -> _iOverlay\*_: Clone the overlay. 
- __iOverlay::GetMaterial__() -> _iMaterial\*_: Get the overlay's material. 
- __iOverlay::GetImage__() -> _iImage\*_: Get the overlay's base image if there's one. 
- __iOverlay::GetBaseSize__() -> _sVec2f_: Get the overlay's base size. 
- __iOverlay::SetPivot__(_const sVec2f&_ avPivot) -> _void_: Set the overlay's pivot position. 
- __iOverlay::GetPivot__() -> _sVec2f_: Get the overlay's pivot position. 
- __iOverlay::SetSize__(_sVec2f_ avSize) -> _void_: Set the overlay size. 
- __iOverlay::GetSize__() -> _sVec2f_: Get the overlay position and size. 
- __iOverlay::SetBlendMode__(_eBlendMode_ aBlendMode) -> _void_: Set the rasterizer blend mode. 
- __iOverlay::GetBlendMode__() -> _eBlendMode_: Get the rasterizer blend mode. 
- __iOverlay::SetFiltering__(_tBool_ abEnabled) -> _void_: Set the filtering mode. 
- __iOverlay::GetFiltering__() -> _tBool_: Get the filtering mode. 
- __iOverlay::SetColor__(_const sColor4f&_ aColor) -> _void_: Set the color of the overlay. 
- __iOverlay::GetColor__() -> _sColor4f_: Get the color of the overlay. 
- __iOverlay::SetCornerColor__(_eRectCorners_ aCorner, _const sColor4f&_ aColor) -> _void_: Set the color of the overlay. 
- __iOverlay::GetCornerColor__(_eRectCorners_ aCorner) -> _sColor4f_: Get the color of the overlay. 
- __iOverlay::SetMapping__(_const sRectf&_ aRect) -> _void_: Set the overlay's mapping coordinates. 
- __iOverlay::GetMapping__() -> _sRectf_: Get the overlay's mapping coordinates. 
- __iOverlay::SetFrame__(_const sVec4f&_ aFrameBorder) -> _void_: Set the overlay's frame. 
- __iOverlay::GetFrame__() -> _sVec4f_: Get the overlay's frame. 
- __iOverlay::GetIsFrame__() -> _tBool_: Get whether a frame is activated. 
- __iOverlay::ComputeFrameCenter__(_const sRectf&_ aDest) -> _sRectf_: Compute the center of the frame from the provided destination rectangle. 
- __iOverlay::Draw__(_iCanvas\*_ apCanvas, _const sVec2f&_ aPos, _const sVec2f&_ aSize) -> _tBool_
- __iOverlay::DrawFrame__(_iCanvas\*_ apCanvas, _tRectFrameFlags_ aFrame, _const sVec2f&_ aPos, _const sVec2f&_ aSize) -> _tBool_

## interface ni::iOverlay
iOverlay interface  

### Parents:
- iUnknown

### Methods:
- __iOverlay::Clone__() -> _iOverlay\*_: Clone the overlay. 
- __iOverlay::GetMaterial__() -> _iMaterial\*_: Get the overlay's material. 
- __iOverlay::GetImage__() -> _iImage\*_: Get the overlay's base image if there's one. 
- __iOverlay::GetBaseSize__() -> _sVec2f_: Get the overlay's base size. 
- __iOverlay::SetPivot__(_const sVec2f&_ avPivot) -> _void_: Set the overlay's pivot position. 
- __iOverlay::GetPivot__() -> _sVec2f_: Get the overlay's pivot position. 
- __iOverlay::SetSize__(_sVec2f_ avSize) -> _void_: Set the overlay size. 
- __iOverlay::GetSize__() -> _sVec2f_: Get the overlay position and size. 
- __iOverlay::SetBlendMode__(_eBlendMode_ aBlendMode) -> _void_: Set the rasterizer blend mode. 
- __iOverlay::GetBlendMode__() -> _eBlendMode_: Get the rasterizer blend mode. 
- __iOverlay::SetFiltering__(_tBool_ abEnabled) -> _void_: Set the filtering mode. 
- __iOverlay::GetFiltering__() -> _tBool_: Get the filtering mode. 
- __iOverlay::SetColor__(_const sColor4f&_ aColor) -> _void_: Set the color of the overlay. 
- __iOverlay::GetColor__() -> _sColor4f_: Get the color of the overlay. 
- __iOverlay::SetCornerColor__(_eRectCorners_ aCorner, _const sColor4f&_ aColor) -> _void_: Set the color of the overlay. 
- __iOverlay::GetCornerColor__(_eRectCorners_ aCorner) -> _sColor4f_: Get the color of the overlay. 
- __iOverlay::SetMapping__(_const sRectf&_ aRect) -> _void_: Set the overlay's mapping coordinates. 
- __iOverlay::GetMapping__() -> _sRectf_: Get the overlay's mapping coordinates. 
- __iOverlay::SetFrame__(_const sVec4f&_ aFrameBorder) -> _void_: Set the overlay's frame. 
- __iOverlay::GetFrame__() -> _sVec4f_: Get the overlay's frame. 
- __iOverlay::GetIsFrame__() -> _tBool_: Get whether a frame is activated. 
- __iOverlay::ComputeFrameCenter__(_const sRectf&_ aDest) -> _sRectf_: Compute the center of the frame from the provided destination rectangle. 
- __iOverlay::Draw__(_iCanvas\*_ apCanvas, _const sVec2f&_ aPos, _const sVec2f&_ aSize) -> _tBool_
- __iOverlay::DrawFrame__(_iCanvas\*_ apCanvas, _tRectFrameFlags_ aFrame, _const sVec2f&_ aPos, _const sVec2f&_ aSize) -> _tBool_

## enum ni::ePixelFormatBlit
Pixel Format Blitting flags. 

### Values:
- __ePixelFormatBlit_Normal__ = __0x00000000__: Normal blitting. 
- __ePixelFormatBlit_MirrorLeftRight__ = __0x00000001__: Mirrored left right blitting. 
- __ePixelFormatBlit_MirrorUpDown__ = __0x00000002__: Mirrored up down blitting. 
- __ePixelFormatBlit_MirrorDiagonal__ = __ePixelFormatBlit_MirrorLeftRight|ePixelFormatBlit_MirrorUpDown__: Diagonal mirror. Equivalent to a Pi rad rotation. 

## enum ni::ePixelFormatCaps
Pixel format capabilities. 

### Values:
- __ePixelFormatCaps_BuildPixel__ = __niBit(0)__: Support the build pixel methods. 
- __ePixelFormatCaps_UnpackPixel__ = __niBit(1)__: Support pixel unpacking. 
- __ePixelFormatCaps_Blit__ = __niBit(2)__: Support standard blitting. 
- __ePixelFormatCaps_BlitMirrorLeftRight__ = __niBit(3)__: Support mirrored left right blitting. 
- __ePixelFormatCaps_BlitMirrorUpDown__ = __niBit(4)__: Support mirrored up down blitting. 
- __ePixelFormatCaps_BlitStretch__ = __niBit(5)__: Support stretched blitting. 
- __ePixelFormatCaps_BlitStretchHalf__ = __niBit(6)__: Support stretched blitting of half size only (for mipmaps generation). 
- __ePixelFormatCaps_Signed__ = __niBit(7)__: Is a signed pixel format. 
- __ePixelFormatCaps_BlitAlpha__ = __niBit(8)__: Support standard alpha blended blitting. 
- __ePixelFormatCaps_BlitAlphaMirrorLeftRight__ = __niBit(9)__: Support mirrored left right alpha blended blitting. 
- __ePixelFormatCaps_BlitAlphaMirrorUpDown__ = __niBit(10)__: Support mirrored up down alpha blended blitting. 
- __ePixelFormatCaps_BlitAlphaStretch__ = __niBit(11)__: Support stretched alpha blended blitting. 
- __ePixelFormatCaps_BlitAlphaStretchHalf__ = __niBit(12)__: Support stretched alpha blended blitting of half size only (for mipmaps generation). 
- __ePixelFormatCaps_Clear__ = __niBit(13)__: Support a specialize clear method. 
- __ePixelFormatCaps_BlockCompressed__ = __niBit(14)__: Block compressed format. 

## interface ni::iPixelFormat
Pixel Format interface. 

### Parents:
- iUnknown

### Methods:
- __iPixelFormat::IsSamePixelFormat__(_const iPixelFormat\*_ pPixFmt) -> _tBool_: Test if the given pixel format is the same as this pixel format. 
- __iPixelFormat::GetNumParameters__() -> _tU32_: Get the number of parameters of the pixel format. 
- __iPixelFormat::SetParameter__(_tU32_ ulParameter, _tU32_ ulValue) -> _tBool_: Set a parameter of the pixel format. 
- __iPixelFormat::GetParameter__(_tU32_ ulParameter) -> _tU32_: Get a parameter of the pixel format. 
- __iPixelFormat::Clone__() -> _iPixelFormat\*_: Clone the pixel format. 
- __iPixelFormat::GetFormat__() -> _const achar\*_: Get the pixel format, format string. 
- __iPixelFormat::GetCaps__() -> _ePixelFormatCaps_: Get the pixel format capabilities. 
- __iPixelFormat::GetBitsPerPixel__() -> _tU32_: Get the number of bits per pixel. 
- __iPixelFormat::GetBytesPerPixel__() -> _tU32_: Get the number of bytes per pixel. 
- __iPixelFormat::GetSize__(_tU32_ ulW, _tU32_ ulH, _tU32_ ulD) -> _tU32_: Get the size in bytes of a surface using this pixel format. 
- __iPixelFormat::GetNumComponents__() -> _tU32_: Get the number of components of the pixel format. 
- __iPixelFormat::GetNumRBits__() -> _tU32_: Get the number of red bits. 
- __iPixelFormat::GetNumGBits__() -> _tU32_: Get the number of green bits. 
- __iPixelFormat::GetNumBBits__() -> _tU32_: Get the number of blue bits. 
- __iPixelFormat::GetNumABits__() -> _tU32_: Get the number of alpha bits. 
- __iPixelFormat::BuildPixelub__(_tPtr_ pOut, _tU8_ r, _tU8_ g, _tU8_ b, _tU8_ a) -> _tPtr_: Build a pixel using unsigned byte values. 
- __iPixelFormat::BuildPixelus__(_tPtr_ pOut, _tU16_ r, _tU16_ g, _tU16_ b, _tU16_ a) -> _tPtr_: Build a pixel using unsigned short values. 
- __iPixelFormat::BuildPixelul__(_tPtr_ pOut, _tU32_ r, _tU32_ g, _tU32_ b, _tU32_ a) -> _tPtr_: Build a pixel using unsigned short values. 
- __iPixelFormat::BuildPixelf__(_tPtr_ pOut, _tF32_ r, _tF32_ g, _tF32_ b, _tF32_ a) -> _tPtr_: Build a pixel using floating point values. 
- __iPixelFormat::BeginUnpackPixels__(_tPtr_ pSurface, _tU32_ ulPitch, _tU32_ ulX, _tU32_ ulY, _tU32_ ulW, _tU32_ ulH) -> _tPtr_: Begin pixel unpacking. 
- __iPixelFormat::EndUnpackPixels__() -> _void_: End pixel unpacking. 
- __iPixelFormat::UnpackPixelub__(_tPtr_ pColor) -> _sColor4ub_: Unpack a pixel in an unsigned byte color. 
- __iPixelFormat::UnpackPixelus__(_tPtr_ pColor) -> _sVec4i_: Unpack a pixel in an unsigned short color. 
- __iPixelFormat::UnpackPixelul__(_tPtr_ pColor) -> _sVec4i_: Unpack a pixel in an unsigned long color. 
- __iPixelFormat::UnpackPixelf__(_tPtr_ pColor) -> _sColor4f_: Unpack a pixel in a floating point color. 
- __iPixelFormat::Clear__(_tPtr_ pDst, _tU32_ ulDestPitch, _tU32_ dx, _tU32_ dy, _tU32_ w, _tU32_ h, _tPtr_ apClearColor) -> _tBool_: Clear a surface with a specified color. 
- __iPixelFormat::Blit__(_tPtr_ pDst, _tU32_ ulDestPitch, _tU32_ dx, _tU32_ dy, _tPtr_ pSrc, _tU32_ ulSrcPitch, _iPixelFormat\*_ pSrcFmt, _tU32_ sx, _tU32_ sy, _tU32_ w, _tU32_ h, _ePixelFormatBlit_ blitFlags) -> _tBool_: Blit a surface of any pixel format to a surface of this pixel format. 
- __iPixelFormat::BlitStretch__(_tPtr_ pDst, _tU32_ ulDestPitch, _tU32_ ulDestWidth, _tU32_ ulDestHeight, _tU32_ dx, _tU32_ dy, _tU32_ dw, _tU32_ dh, _tPtr_ pSrc, _tU32_ ulSrcPitch, _iPixelFormat\*_ pSrcFmt, _tU32_ sx, _tU32_ sy, _tU32_ sw, _tU32_ sh) -> _tBool_: Blit stretch a surface of any pixel format to a surface of this pixel format. 
- __iPixelFormat::BlitAlpha__(_tPtr_ pDst, _tU32_ ulDestPitch, _tU32_ dx, _tU32_ dy, _tPtr_ pSrc, _tU32_ ulSrcPitch, _iPixelFormat\*_ pSrcFmt, _tU32_ sx, _tU32_ sy, _tU32_ w, _tU32_ h, _ePixelFormatBlit_ blitFlags, _const sColor4f&_ aSourceColor, _const sColor4f&_ aDestColor, _eBlendMode_ aBlendMode) -> _tBool_: Blit a surface of any pixel format to a surface of this pixel format. 
- __iPixelFormat::BlitAlphaStretch__(_tPtr_ pDst, _tU32_ ulDestPitch, _tU32_ ulDestWidth, _tU32_ ulDestHeight, _tU32_ dx, _tU32_ dy, _tU32_ dw, _tU32_ dh, _tPtr_ pSrc, _tU32_ ulSrcPitch, _iPixelFormat\*_ pSrcFmt, _tU32_ sx, _tU32_ sy, _tU32_ sw, _tU32_ sh, _const sColor4f&_ aSourceColor, _const sColor4f&_ aDestColor, _eBlendMode_ aBlendMode) -> _tBool_: Blit stretch a surface of any pixel format to a surface of this pixel format. 

## enum ni::ePixelFormatBlit
Pixel Format Blitting flags. 

### Values:
- __ePixelFormatBlit_Normal__ = __0x00000000__: Normal blitting. 
- __ePixelFormatBlit_MirrorLeftRight__ = __0x00000001__: Mirrored left right blitting. 
- __ePixelFormatBlit_MirrorUpDown__ = __0x00000002__: Mirrored up down blitting. 
- __ePixelFormatBlit_MirrorDiagonal__ = __ePixelFormatBlit_MirrorLeftRight|ePixelFormatBlit_MirrorUpDown__: Diagonal mirror. Equivalent to a Pi rad rotation. 

## enum ni::eShaderUnit
Shader Units. 

### Values:
- __eShaderUnit_Vertex__ = __0__: Vertex shader. 
- __eShaderUnit_Pixel__ = __1__: Pixel shader. 
- __eShaderUnit_Native__ = __2__: Native driver dependent shader. 
- __eShaderUnit_Last__ = __3__: \internal. 

## enum ni::eShaderRegisterType
Shader input register type. 

### Values:
- __eShaderRegisterType_Input__ = __0__: Input register. 
- __eShaderRegisterType_Output__ = __1__: Output position register. 
- __eShaderRegisterType_Temporary__ = __2__: Temporary register. 
- __eShaderRegisterType_ConstFloat__ = __3__: Constant float register. 
- __eShaderRegisterType_ConstInt__ = __4__: Constant int register. 
- __eShaderRegisterType_ConstBool__ = __5__: Constant bool register. 
- __eShaderRegisterType_Sampler__ = __6__: Sampler register. 
- __eShaderRegisterType_Address__ = __7__: Address register. 
- __eShaderRegisterType_Loop__ = __8__: Loop register. 
- __eShaderRegisterType_Texture__ = __9__: Texture register. 
- __eShaderRegisterType_Predicate__ = __10__: Predicate register. 
- __eShaderRegisterType_Last__ = __11__: \internal 

## interface ni::iShaderConstants
Shader constants buffer. 

### Parents:
- iSerializable

### Remarks:
- All sizes and offsets are expressed in register (sVec4f/l) unit. 

### Methods:
- __iShaderConstants::Clone__() -> _iShaderConstants\*_: Clone this constant buffer. 
- __iShaderConstants::GetMaxNumRegisters__() -> _tU32_: Get the constants buffer maximum number of registers. 
- __iShaderConstants::AddConstant__(_iHString\*_ ahspName, _eShaderRegisterType_ aType, _tU32_ anSize) -> _tU32_: Add a new constant. 
- __iShaderConstants::GetNumConstants__() -> _tU32_: Get the number of constants in the buffer. 
- __iShaderConstants::GetConstantIndex__(_iHString\*_ ahspName) -> _tU32_: Get the index of the specified constant. 
- __iShaderConstants::GetConstantName__(_tU32_ anConstIndex) -> _iHString\*_: Get the name of the specified constant. 
- __iShaderConstants::GetConstantSize__(_tU32_ anConstIndex) -> _tU32_: Get the size of the constant at the specified index. 
- __iShaderConstants::GetConstantType__(_tU32_ anConstIndex) -> _eShaderRegisterType_: Get the type of the specified constant. 
- __iShaderConstants::SetHwIndex__(_tU32_ anConstIndex, _tU32_ anRegisterIndex) -> _tBool_: Set the hardware register index of the specified constant. 
- __iShaderConstants::GetHwIndex__(_tU32_ anConstIndex) -> _tU32_: Get the hardware register index of the specified constant. 
- __iShaderConstants::SetFloatArray__(_tU32_ anConstIndex, _const tVec4fCVec\*_ apV, _tU32_ anSize) -> _tBool_: Set a float constant from 4D vectors. 
- __iShaderConstants::SetFloatPointer__(_tU32_ anConstIndex, _const sVec4f\*_ apV, _tU32_ anSize) -> _tBool_: Set a float constant from 4D vectors. 
- __iShaderConstants::SetFloat__(_tU32_ anConstIndex, _const sVec4f&_ aV) -> _tBool_: Set a float constant from 4D vectors. 
- __iShaderConstants::SetFloatMatrixArray__(_tU32_ anConstIndex, _const tMatrixfCVec\*_ apV, _tU32_ anSize) -> _tBool_: Set four float constants from matrices. 
- __iShaderConstants::SetFloatMatrix__(_tU32_ anConstIndex, _const sMatrixf&_ aV) -> _tBool_: Set four float constants from matrices. 
- __iShaderConstants::SetIntArray__(_tU32_ anConstIndex, _const tVec4iCVec\*_ apV, _tU32_ anSize) -> _tBool_: Set an integer constant from 4D vectors. 
- __iShaderConstants::SetIntPointer__(_tU32_ anConstIndex, _const sVec4i\*_ apV, _tU32_ anSize) -> _tBool_: Set an integer constant from 4D vectors. 
- __iShaderConstants::SetInt__(_tU32_ anConstIndex, _const sVec4i&_ aV) -> _tBool_: Set an integer constant from 4D vectors. 
- __iShaderConstants::GetFloat__(_tU32_ anConstIndex, _tU32_ anOffset) -> _sVec4f_: Get the float constant at the specified index. 
- __iShaderConstants::GetFloatMatrix__(_tU32_ anConstIndex) -> _sMatrixf_: Get the float constant matrix at the specified index. 
- __iShaderConstants::GetFloatPointer__(_tU32_ anConstIndex) -> _sVec4f\*_: Get the float constant pointer at the specified index. 
- __iShaderConstants::GetInt__(_tU32_ anConstIndex, _tU32_ anOffset) -> _sVec4i_: Get the float constant at the specified index. 
- __iShaderConstants::GetIntPointer__(_tU32_ anConstIndex) -> _sVec4i\*_: Get the float constant pointer at the specified index. 
- __iShaderConstants::GetDescStructPtr__() -> _tPtr_: Get the shader constants buffer description structure pointer. 
- __iShaderConstants::SetConstantMetadata__(_tU32_ anConstIndex, _iHString\*_ ahspMetadata) -> _void_: Set the metadata of the specified constant. 
- __iShaderConstants::GetConstantMetadata__(_tU32_ anConstIndex) -> _iHString\*_: Get the metadata of the specified constant. 

## interface ni::iShader
Shader interface. 

### Parents:
- iDeviceResource

### Methods:
- __iShader::GetUnit__() -> _eShaderUnit_: Return the Shader unit on which it runs. 
- __iShader::GetProfile__() -> _iHString\*_: Return the profile of the Shader. 
- __iShader::GetConstants__() -> _const iShaderConstants\*_: Get the program's constants. 
- __iShader::GetCode__() -> _iHString\*_: Get the code of the shader. 
- __iShader::GetDescStructPtr__() -> _tPtr_: Get the shader description structure pointer. 

## interface ni::iGLShader
 The OpenGL shader that is linked and can give use the bindings and pushes the uniforms. That's the interface the native shader's Bind() function must return.   The calling order is: - iGLShader::Bind(iDrawOperation) -> iGLShader - iGLShader::GetVertexAttributeLocationArray() before binding the VA. - glBindBuffer(VA), glDrawElements/glDrawArrays - iGLShader::BeforeDraw(), its expected to push shader uniforms. - glBindBuffer(IA), glDrawElements/glDrawArrays - iGLShader::AfterDraw()  

### Parents:
- iUnknown

### Methods:
- __iGLShader::GetVertexAttributeLocationArray__() -> _const tI32\*_:  The OpenGL shader that is linked and can give use the bindings and pushes the uniforms. That's the interface the native shader's Bind() function must return.   The calling order is: - iGLShader::Bind(iDrawOperation) -> iGLShader - iGLShader::GetVertexAttributeLocationArray() before binding the VA. - glBindBuffer(VA), glDrawElements/glDrawArrays - iGLShader::BeforeDraw(), its expected to push shader uniforms. - glBindBuffer(IA), glDrawElements/glDrawArrays - iGLShader::AfterDraw()  
- __iGLShader::BeforeDraw__() -> _tBool_
- __iGLShader::AfterDraw__() -> _void_

## enum ni::eShaderUnit
Shader Units. 

### Values:
- __eShaderUnit_Vertex__ = __0__: Vertex shader. 
- __eShaderUnit_Pixel__ = __1__: Pixel shader. 
- __eShaderUnit_Native__ = __2__: Native driver dependent shader. 
- __eShaderUnit_Last__ = __3__: \internal. 

## enum ni::eTextTruncation
Text truncation 

### Values:
- __eTextTruncation_Left__ = __0__: The words will be truncated on the left if bigger than the text block. 
- __eTextTruncation_Right__ = __1__: The words will be truncated on the right if bigger than the text block. 
- __eTextTruncation_None__ = __2__: The words won't be truncated. 

## interface ni::iTextOccluder
Text occluder interface 

### Parents:
- iUnknown

### Methods:
- __iTextOccluder::GetTextObject__() -> _Ptr<iTextObject>_: Get the parent text object. 
- __iTextOccluder::SetRect__(_const sRectf&_ aRect) -> _void_: Set the occluder's rectangle. 
- __iTextOccluder::GetRect__() -> _sRectf_: Get the occluder's rectangle. 
- __iTextOccluder::SetUserData__(_const Var&_ aUserData) -> _void_: Set user data. 
- __iTextOccluder::GetUserData__() -> _Var_: Get the user data. 

## interface ni::iTextObject


### Parents:
- iUnknown

### Methods:
- __iTextObject::GetGraphics__() -> _iGraphics\*_: Get the graphics object that created the text object. 
- __iTextObject::SetContentsScale__(_const tF32_ afContentsScale) -> _void_: Set the contents' scale factor. 
- __iTextObject::GetContentsScale__() -> _tF32_: Get the contents' scale factor. 
- __iTextObject::SetDefaultFont__(_iFont\*_ apFont) -> _void_: Set the default font used by the text object. 
- __iTextObject::GetDefaultFont__() -> _iFont\*_: Get the default font used by the text object. 
- __iTextObject::SetLoadFontCallback__(_iCallback\*_ apLoadFontCallback) -> _void_: Set the load font callback used by the text object. 
- __iTextObject::GetLoadFontCallback__() -> _iCallback\*_: Get the load font callback used by the text object. 
- __iTextObject::SetSize__(_const sVec2f&_ avSize) -> _void_: Set the size of the text object. 
- __iTextObject::GetSize__() -> _sVec2f_: Get the size of the text object. 
- __iTextObject::SetTruncation__(_eTextTruncation_ aType) -> _void_: Set the word truncation mode. 
- __iTextObject::GetTruncation__() -> _eTextTruncation_: Get the word truncation mode. 
- __iTextObject::SetTruncationText__(_const achar\*_ aaszString) -> _void_: Set the truncation text. 
- __iTextObject::GetTruncationText__() -> _const achar\*_: Get the truncation text. 
- __iTextObject::SetTrimLeadingSpaces__(_tBool_ abTrimLeadingSpaces) -> _void_: Set whether to trim the leading spaces. 
- __iTextObject::GetTrimLeadingSpaces__() -> _tBool_: Get whether to trim the leading spaces. 
- __iTextObject::SetKerning__(_tBool_ abKerning) -> _void_: Set whether to use kerning. 
- __iTextObject::GetKerning__() -> _tBool_: Get whether to use kerning. 
- __iTextObject::GetTextSize__() -> _sVec2f_: Get the computed size of the text after layout. 
- __iTextObject::SetExpressionContext__(_iExpressionContext\*_ apContext) -> _void_: Set the expression context used for the <expr> tags. 
- __iTextObject::GetExpressionContext__() -> _iExpressionContext\*_: Get the expression context used for the <expr> tags. 
- __iTextObject::Update__() -> _void_: Update. 
- __iTextObject::DrawAt__(_iCanvas\*_ apCanvas, _const sRectf&_ aClippingRect, _const sVec3f&_ avPos) -> _tBool_: Draw the text object in the specified canvas. 
- __iTextObject::Draw__(_iCanvas\*_ apCanvas, _const sRectf&_ aClippingRect) -> _tBool_: Draw the text object in the specified canvas. 
- __iTextObject::AddOccluder__(_const sRectf&_ aRect, _const Var&_ aUserData) -> _iTextOccluder\*_: Add a text occluder. 
- __iTextObject::RemoveOccluder__(_tU32_ anIndex) -> _tBool_: Remove the text occluder at the specified index. 
- __iTextObject::ClearOccluders__() -> _void_: Removes all text occluders. 
- __iTextObject::GetNumOccluders__() -> _tU32_: Get number of occluders. 
- __iTextObject::GetOccluder__(_tU32_ anIndex) -> _iTextOccluder\*_: Get occluder from index. 
- __iTextObject::SetText__(_const achar\*_ aaszText) -> _void_: Set the text of the text object. 
- __iTextObject::GetText__() -> _const achar\*_: Get the text of the text object. 
- __iTextObject::AddText__(_const achar\*_ aaszString) -> _void_: Add Text the the widget. 
- __iTextObject::SetSelectionColor__(_sVec4f_ avColor) -> _void_: Set the selection background color. 
- __iTextObject::GetSelectionColor__() -> _sVec4f_: Get the selection background color. 
- __iTextObject::GetSelectedString__() -> _cString_: Get the selected string. 
- __iTextObject::ClearSelection__() -> _void_: Clear the current selection. 
- __iTextObject::SelectRange__(_tU32_ anBegin, _tU32_ anEnd) -> _void_: Select the specified word range. 
- __iTextObject::FindWordIndexFromPosition__(_sVec2f_ avPosition) -> _tU32_: Find the index of the word nearest of the specified position. 

## enum ni::eTextTruncation
Text truncation 

### Values:
- __eTextTruncation_Left__ = __0__: The words will be truncated on the left if bigger than the text block. 
- __eTextTruncation_Right__ = __1__: The words will be truncated on the right if bigger than the text block. 
- __eTextTruncation_None__ = __2__: The words won't be truncated. 

## enum ni::eTextureFlags
Texture flags. 

### Values:
- __eTextureFlags_Default__ = __0__: Texture default. 
- __eTextureFlags_SystemMemory__ = __niBit(0)__: Texture is in system memory. 
- __eTextureFlags_RenderTarget__ = __niBit(1)__: Texture is a render target. 
- __eTextureFlags_DepthStencil__ = __niBit(2)__: Texture is a depth stencil. 
- __eTextureFlags_Dynamic__ = __niBit(3)__: Texture is a dynamic and so can be locked. 
- __eTextureFlags_MipMaps__ = __niBit(4)__: Texture has mip maps. 
- __eTextureFlags_AutoGenMipMaps__ = __niBit(5)__: Texture has automatically generated mip maps. 
- __eTextureFlags_Surface__ = __niBit(6)__: The texture is a surface. It cant be bound as a source texture to be rasterized, but can be used for blitting, locked and as render target. 
- __eTextureFlags_SubTexture__ = __niBit(7)__: Is a sub texture. 
- __eTextureFlags_Overlay__ = __niBit(8)__: Overlay texture. An overlay texture is a texture that will use only clamp addressing without mipmaps, and that is generaly non-pow2. 
- __eTextureFlags_Virtual__ = __niBit(9)__: Virtual texture. The actual texture data are provided through bind only. \see ni::iDeviceResource::Bind 
- __eTextureFlags_RTAA4Samples__ = __niBit(10)__: Texture is an antialiased render target with 4 samples. 
- __eTextureFlags_RTAA8Samples__ = __niBit(11)__: Texture is an antialiased render target with 8 samples. 
- __eTextureFlags_RTAA16Samples__ = __niBit(12)__: Texture is an antialiased render target with 16 samples. 
- __eTextureFlags_RTAA_All__ = __eTextureFlags_RTAA4Samples|eTextureFlags_RTAA8Samples|eTextureFlags_RTAA16Samples__: All RTAA flags, can be used to test whether a texture is antialiased. 
- __eTextureFlags_RTFlipped__ = __niBit(15)__: Render target is flipped. 

## enum ni::eTextureBlitFlags
Texture blit flags. 

### Values:
- __eTextureBlitFlags_None__ = __0__: No flags 
- __eTextureBlitFlags_BilinearFilter__ = __niBit(0)__: Bilinear filtering. 
- __eTextureBlitFlags_Frequent__ = __niBit(1)__: Optimization flags that notify that the bliting will happen frequently. 

## interface ni::iTexture
Texture interface 

### Parents:
- iDeviceResource

### Remarks:
- Bindable 

### Methods:
- __iTexture::GetType__() -> _eBitmapType_: Get the texture type. 
- __iTexture::GetWidth__() -> _tU32_: Get the texture width. 
- __iTexture::GetHeight__() -> _tU32_: Get the texture height. 
- __iTexture::GetDepth__() -> _tU32_: Get the texture depth. 
- __iTexture::GetPixelFormat__() -> _iPixelFormat\*_: Get the texture's pixel format. 
- __iTexture::GetNumMipMaps__() -> _tU32_: Get the number of mipmaps of the texture. 
- __iTexture::GetFlags__() -> _tTextureFlags_: Get the texture flags. 
- __iTexture::GetSubTexture__(_tU32_ anIndex) -> _iTexture\*_: Get a sub texture. 

## interface ni::iGLTexture


### Parents:
- iTexture

### Methods:
- __iGLTexture::GetGLHandle__() -> _tU32_: Get the OpenGL handle. 
- __iGLTexture::GetGLFBOHandle__() -> _tU32_: Get the OpenGL FBO handle. 

## enum ni::eTextureFlags
Texture flags. 

### Values:
- __eTextureFlags_Default__ = __0__: Texture default. 
- __eTextureFlags_SystemMemory__ = __niBit(0)__: Texture is in system memory. 
- __eTextureFlags_RenderTarget__ = __niBit(1)__: Texture is a render target. 
- __eTextureFlags_DepthStencil__ = __niBit(2)__: Texture is a depth stencil. 
- __eTextureFlags_Dynamic__ = __niBit(3)__: Texture is a dynamic and so can be locked. 
- __eTextureFlags_MipMaps__ = __niBit(4)__: Texture has mip maps. 
- __eTextureFlags_AutoGenMipMaps__ = __niBit(5)__: Texture has automatically generated mip maps. 
- __eTextureFlags_Surface__ = __niBit(6)__: The texture is a surface. It cant be bound as a source texture to be rasterized, but can be used for blitting, locked and as render target. 
- __eTextureFlags_SubTexture__ = __niBit(7)__: Is a sub texture. 
- __eTextureFlags_Overlay__ = __niBit(8)__: Overlay texture. An overlay texture is a texture that will use only clamp addressing without mipmaps, and that is generaly non-pow2. 
- __eTextureFlags_Virtual__ = __niBit(9)__: Virtual texture. The actual texture data are provided through bind only. \see ni::iDeviceResource::Bind 
- __eTextureFlags_RTAA4Samples__ = __niBit(10)__: Texture is an antialiased render target with 4 samples. 
- __eTextureFlags_RTAA8Samples__ = __niBit(11)__: Texture is an antialiased render target with 8 samples. 
- __eTextureFlags_RTAA16Samples__ = __niBit(12)__: Texture is an antialiased render target with 16 samples. 
- __eTextureFlags_RTAA_All__ = __eTextureFlags_RTAA4Samples|eTextureFlags_RTAA8Samples|eTextureFlags_RTAA16Samples__: All RTAA flags, can be used to test whether a texture is antialiased. 
- __eTextureFlags_RTFlipped__ = __niBit(15)__: Render target is flipped. 

## enum ni::eTransformFlags
Transform flags. Default is eTransformFlags_InheritAll 

### Values:
- __eTransformFlags_InheritPositionX__ = __niBit(0)__: Inherit the position X axis. 
- __eTransformFlags_InheritPositionY__ = __niBit(1)__: Inherit the position Y axis. 
- __eTransformFlags_InheritPositionZ__ = __niBit(2)__: Inherit the position Z axis. 
- __eTransformFlags_InheritPosition__ = __niBit(0)|niBit(1)|niBit(2)__: Inherit the position XYZ axis. 
- __eTransformFlags_InheritRotation__ = __niBit(3)__: Inherit the rotation. 
- __eTransformFlags_InheritScale__ = __niBit(4)__: Parent scalings are also apply on children. 
- __eTransformFlags_InheritPositionRotation__ = __eTransformFlags_InheritPosition|eTransformFlags_InheritRotation__: Inherit the position and rotation. 
- __eTransformFlags_InheritAll__ = __eTransformFlags_InheritPositionRotation|eTransformFlags_InheritScale__: Inherit all. 

## enum ni::eTransformInternalFlags
Transform internal flags. 

### Values:
- __eTransformInternalFlags_Dirty__ = __niBit(8)__: The transform will have to be recomputed. 
- __eTransformInternalFlags_UseScale__ = __niBit(9)__: The transform uses a scaling factor. 

## interface ni::iTransform
iTransform is the interface for positionning and orienting. 

### Parents:
- iUnknown

### Methods:
- __iTransform::GetDescStructPtr__() -> _tPtr_: Get the transform description structure pointer. 
- __iTransform::Clone__() -> _iTransform\*_: Clone the transform. 
- __iTransform::Copy__(_const iTransform\*_ apSrc) -> _tBool_: Copy another transform in this transform. 
- __iTransform::SetDirty__() -> _tU16_: Mark the transform as "Dirty". 
- __iTransform::SetFlags__(_tU16_ anFlags) -> _void_: Set the transform flags. 
- __iTransform::GetFlags__() -> _tU16_: Get the transform flags. 
- __iTransform::SetSyncCounter__(_tU16_ anFlags) -> _void_: Set the synchronization counter. 
- __iTransform::GetSyncCounter__() -> _tU16_: Get the synchronization counter. 
- __iTransform::SetParent__(_iTransform\*_ apParent) -> _void_: Set the parent transform. 
- __iTransform::GetParent__() -> _iTransform\*_: Get the parent transform. 
- __iTransform::Identity__() -> _void_: Set the transform to identity. 
- __iTransform::SetWorldMatrix__(_const sMatrixf&_ aMatrix) -> _void_: Set the world matrix. 
- __iTransform::GetWorldMatrix__() -> _sMatrixf_: Get the world matrix. 
- __iTransform::SetLocalMatrix__(_const sMatrixf&_ aMatrix) -> _void_: Set the local matrix. 
- __iTransform::GetLocalMatrix__() -> _sMatrixf_: Get the local matrix. 
- __iTransform::MultiplyWorldMatrix__(_const sMatrixf&_ aMatrix) -> _void_: Multiply the world matrix. 
- __iTransform::PreMultiplyWorldMatrix__(_const sMatrixf&_ aMatrix) -> _void_: Pre-Multiply the world matrix. 
- __iTransform::MultiplyLocalMatrix__(_const sMatrixf&_ aMatrix) -> _void_: Multiply the local matrix. 
- __iTransform::PreMultiplyLocalMatrix__(_const sMatrixf&_ aMatrix) -> _void_: Pre-Multiply the local matrix. 
- __iTransform::LookAt__(_const sVec3f&_ avLookAt, _const sVec3f&_ avUp) -> _void_: Set the transform's orientation that the forward vector points at a specified world position. 
- __iTransform::SetWorldPosition__(_const sVec3f&_ v) -> _void_: Set the world position of the transform. 
- __iTransform::GetWorldPosition__() -> _sVec3f_: Get the world position of the transform. 
- __iTransform::SetLocalPosition__(_const sVec3f&_ v) -> _void_: Set the local position of the transform. 
- __iTransform::GetLocalPosition__() -> _sVec3f_: Get the local position of the transform. 
- __iTransform::Translate__(_const sVec3f&_ v) -> _void_: Translate the local position of the transform. 
- __iTransform::PreTranslate__(_const sVec3f&_ v) -> _void_: PreTranslate the local position of the transform. 
- __iTransform::SetWorldRotation__(_const sMatrixf&_ aMatrix) -> _void_: Set the world rotation of the transform. 
- __iTransform::SetLocalRotation__(_const sMatrixf&_ aMatrix) -> _void_: Set the local rotation of the transform. 
- __iTransform::Rotate__(_const sMatrixf&_ aMatrix) -> _void_: Rotate the local rotation of the transform. 
- __iTransform::PreRotate__(_const sMatrixf&_ aMatrix) -> _void_: PreRotate the local rotation of the transform. 
- __iTransform::SetScale__(_const sVec3f&_ aScale) -> _void_: Set the scale of the transform. 
- __iTransform::GetScale__() -> _sVec3f_: Return the scale of the transform. 
- __iTransform::CreatePreOffsetTransform__() -> _iTransform\*_: Create a pre offset transform. 
- __iTransform::CreatePostOffsetTransform__() -> _iTransform\*_: Create a post offset transform. 
- __iTransform::GetRight__() -> _sVec3f_: Get the right (X) vector. 
- __iTransform::GetUp__() -> _sVec3f_: Get the up (Y) vector. 
- __iTransform::GetForward__() -> _sVec3f_: Get the forward (Z) vector. 
- __iTransform::GetInvRight__() -> _sVec3f_: Get the inverse transform right (X) vector. 
- __iTransform::GetInvUp__() -> _sVec3f_: Get the inverse transform up (Y) vector. 
- __iTransform::GetInvForward__() -> _sVec3f_: Get the inverse transform forward (Z) vector. 

## enum ni::eTransformFlags
Transform flags. Default is eTransformFlags_InheritAll 

### Values:
- __eTransformFlags_InheritPositionX__ = __niBit(0)__: Inherit the position X axis. 
- __eTransformFlags_InheritPositionY__ = __niBit(1)__: Inherit the position Y axis. 
- __eTransformFlags_InheritPositionZ__ = __niBit(2)__: Inherit the position Z axis. 
- __eTransformFlags_InheritPosition__ = __niBit(0)|niBit(1)|niBit(2)__: Inherit the position XYZ axis. 
- __eTransformFlags_InheritRotation__ = __niBit(3)__: Inherit the rotation. 
- __eTransformFlags_InheritScale__ = __niBit(4)__: Parent scalings are also apply on children. 
- __eTransformFlags_InheritPositionRotation__ = __eTransformFlags_InheritPosition|eTransformFlags_InheritRotation__: Inherit the position and rotation. 
- __eTransformFlags_InheritAll__ = __eTransformFlags_InheritPositionRotation|eTransformFlags_InheritScale__: Inherit all. 

## enum ni::eUIInputModifier
UI input modifiers. 

### Remarks:
- The key values are intentionally the same as ni::eKeyMod 

### Values:
- __eUIInputModifier_A__ = __niBit(16)__: Modifier A. 
- __eUIInputModifier_Control__ = __eUIInputModifier_A__: Modifier A. 
- __eUIInputModifier_Command__ = __eUIInputModifier_A__: Modifier A. 
- __eUIInputModifier_AddSelection__ = __eUIInputModifier_A__: Modifier A. 
- __eUIInputModifier_B__ = __niBit(17)__: Modifier B. 
- __eUIInputModifier_Shift__ = __eUIInputModifier_B__: Modifier B. 
- __eUIInputModifier_AddSelectionRange__ = __eUIInputModifier_B__: Modifier B. 
- __eUIInputModifier_C__ = __niBit(18)__: Modifier C. 
- __eUIInputModifier_Alt__ = __eUIInputModifier_C__: Modifier C. 
- __eUIInputModifier_Shortcut__ = __eUIInputModifier_C__: Modifier C. 
- __eUIInputModifier_KeyDownRepeat__ = __niBit(31)__: KeyDown is repeating. 

## enum ni::eUIInputSubmitFlags
UI input submit. 

### Values:
- __eUIInputSubmitFlags_Disabled__ = __0__: Disabled 
- __eUIInputSubmitFlags_SubmitA__ = __niBit(0)__: Input action Submit A. 
- __eUIInputSubmitFlags_SubmitB__ = __niBit(1)__: Input action Submit B. 
- __eUIInputSubmitFlags_SubmitC__ = __niBit(2)__: Input action Submit C. 
- __eUIInputSubmitFlags_LeftClick__ = __niBit(3)__: Left click. 
- __eUIInputSubmitFlags_LeftDoubleClick__ = __niBit(4)__: Left double click. 
- __eUIInputSubmitFlags_RightClick__ = __niBit(5)__: Right click. 
- __eUIInputSubmitFlags_RightDoubleClick__ = __niBit(6)__: Right double click. 
- __eUIInputSubmitFlags_StandardButton__ = __eUIInputSubmitFlags_SubmitA|eUIInputSubmitFlags_SubmitB|eUIInputSubmitFlags_LeftClick__: Button standard. 
- __eUIInputSubmitFlags_StandardIcon__ = __eUIInputSubmitFlags_SubmitA|eUIInputSubmitFlags_SubmitB|eUIInputSubmitFlags_LeftDoubleClick__: Icon standard. 
- __eUIInputSubmitFlags_StandardSingleLineText__ = __eUIInputSubmitFlags_SubmitA|eUIInputSubmitFlags_SubmitC__: Single Line Text box standard. 
- __eUIInputSubmitFlags_StandardMultiLineText__ = __eUIInputSubmitFlags_SubmitC__: Multi Line Text box standard. 
- __eUIInputSubmitFlags_Default__ = __eUIInputSubmitFlags_Disabled__: UI Context default input submit flags default. 

## interface ni::iUIContext
UI Context interface. 

### Parents:
- iUnknown

### Methods:
- __iUIContext::GetGraphics__() -> _iGraphics\*_: Get the parent graphics object. 
- __iUIContext::GetGraphicsContext__() -> _iGraphicsContext\*_: Get the parent graphics context attached to this UI context. 
- __iUIContext::SendWindowMessage__(_eOSWindowMessage_ aMsg, _const Var&_ avarA, _const Var&_ avarB) -> _void_: Send a Window message to the UI context. 
- __iUIContext::SetInputModifiers__(_tU32_ anInputModifier) -> _void_: Set the input modifiers. \see ni::eUIInputModifier 
- __iUIContext::GetInputModifiers__() -> _tU32_: Get the input modifiers. \see ni::eUIInputModifier 
- __iUIContext::SetDefaultInputSubmitFlags__(_tUIInputSubmitFlags_ aSubmitFlags) -> _void_: Set the default input submit flags. 
- __iUIContext::GetDefaultInputSubmitFlags__() -> _tUIInputSubmitFlags_: Get the default input submit flags. 
- __iUIContext::SetHoverDelay__(_tF32_ afDelay) -> _void_: Set the hovering delay in seconds. 
- __iUIContext::GetHoverDelay__() -> _tF32_: Get the hovering delay in seconds. 
- __iUIContext::SetHoverInputModifiers__(_tU32_ anInputModifiers) -> _void_: Set the input modifier required to enable the hover. \see ni::eUIInputModifier 
- __iUIContext::GetHoverInputModifiers__() -> _tU32_: Get the input modifier required to enable the hover. \see ni::eUIInputModifier 
- __iUIContext::SetImageMap__(_iImageMap\*_ apImageMap) -> _void_: Set the context's image map. 
- __iUIContext::GetImageMap__() -> _iImageMap\*_: Get the context's image map. 
- __iUIContext::SetErrorOverlay__(_iOverlay\*_ apOverlay) -> _tBool_: Get the error overlay. 
- __iUIContext::GetErrorOverlay__() -> _iOverlay\*_: Get the error overlay. 
- __iUIContext::ClearSkins__() -> _void_: Remove all skins loaded. 
- __iUIContext::AddSkin__(_iDataTable\*_ apDT) -> _tBool_: Add a new skin. 
- __iUIContext::AddSkinFromRes__(_iHString\*_ ahspRes) -> _tBool_: Add a new skin from the specified resource. 
- __iUIContext::RemoveSkin__(_iHString\*_ ahspSkin) -> _tBool_: Unload a skin. 
- __iUIContext::SetDefaultSkin__(_iHString\*_ ahspName) -> _tBool_: Set the default skin. 
- __iUIContext::GetDefaultSkin__() -> _iHString\*_: Get the default skin. 
- __iUIContext::GetNumSkins__() -> _tU32_: Get the number of skins. 
- __iUIContext::GetSkinName__(_tU32_ anIndex) -> _iHString\*_: Get the name of the skin at the specified index. 
- __iUIContext::GetSkinIndex__(_iHString\*_ ahspName) -> _tU32_: Get the index of the skin with the specified name. 
- __iUIContext::GetSkinDataTable__(_iHString\*_ ahspSkin) -> _iDataTable\*_: Get the data table associated with the specified skin. 
- __iUIContext::ApplySkin__(_iWidget\*_ apWidget, _iHString\*_ ahspName) -> _tBool_: Apply the specified skin to a widget and all its children. 
- __iUIContext::FindSkinFont__(_iHString\*_ ahspSkin, _iHString\*_ ahspClass, _iHString\*_ ahspState, _iHString\*_ ahspName) -> _iFont\*_: Find the font of the specified item in the widget's skin. 
- __iUIContext::FindSkinCursor__(_iHString\*_ ahspSkin, _iHString\*_ ahspClass, _iHString\*_ ahspState, _iHString\*_ ahspName) -> _iOverlay\*_: Find the cursor of the specified item in the widget's skin. 
- __iUIContext::FindSkinElement__(_iHString\*_ ahspSkin, _iHString\*_ ahspClass, _iHString\*_ ahspState, _iHString\*_ ahspName) -> _iOverlay\*_: Find the element of the specified item in the widget's skin. 
- __iUIContext::FindSkinColor__(_const sColor4f&_ aDefault, _iHString\*_ ahspSkin, _iHString\*_ ahspClass, _iHString\*_ ahspState, _iHString\*_ ahspName) -> _sColor4f_: Find the color of the specified item in the widget's skin. 
- __iUIContext::HasWidgetSinkClass__(_const achar\*_ aszClassName) -> _tBool_: Check whether the specified widget sink class can be created. 
- __iUIContext::CreateWidgetSink__(_const achar\*_ aszClassName, _iWidget\*_ apWidget) -> _iWidgetSink\*_: Create a widget sink of the specified class. 
- __iUIContext::CreateWidgetSinkFromScript__(_iHString\*_ ahspRes) -> _iWidgetSink\*_: Create a widget sink from the the specified script script. 
- __iUIContext::CreateWidget__(_const achar\*_ aszClassName, _iWidget\*_ apwParent, _const sRectf&_ arectPos, _tU32_ anStyle, _iHString\*_ ahspID) -> _iWidget\*_: Create a widget. 
- __iUIContext::CreateWidgetRaw__(_const achar\*_ aszClassName, _iWidget\*_ apwParent, _const sRectf&_ arectPos, _tU32_ anStyle, _iHString\*_ ahspID) -> _iWidget\*_: Create a widget without attaching any sink to it. 
- __iUIContext::CreateWidgetFromDataTable__(_iDataTable\*_ apDT, _iWidget\*_ apwParent, _iHString\*_ ahspID, _iHString\*_ ahspTitle) -> _iWidget\*_: Create a widget from the specified datatable. 
- __iUIContext::CreateWidgetFromResource__(_iHString\*_ ahspRes, _iWidget\*_ apwParent, _iHString\*_ ahspID, _iHString\*_ ahspTitle) -> _iWidget\*_: Create a widget from a datatable in the specified resource. 
- __iUIContext::GetRootWidget__() -> _iWidget\*_: Get the root widget. 
- __iUIContext::SetActiveWidget__(_iWidget\*_ apWidget) -> _tBool_: Set the active widget. 
- __iUIContext::GetActiveWidget__() -> _iWidget\*_: Get the active widget. 
- __iUIContext::GetNumWidgets__() -> _tU32_: Get the number of widgets created. 
- __iUIContext::GetWidget__(_tU32_ anIndex) -> _iWidget\*_: Get the widget at the specified index. 
- __iUIContext::SerializeWidget__(_iWidget\*_ apWidget, _iDataTable\*_ apDT, _tWidgetSerializeFlags_ anFlags, _iRegex\*_ apFilter) -> _tBool_: Serialize the specified widget. 
- __iUIContext::CreateWidgetCommand__() -> _iWidgetCommand\*_: Create a widget command instance. 
- __iUIContext::SendCommand__(_iWidget\*_ apDest, _iWidgetCommand\*_ apCmd) -> _tBool_: Send a command to the specified widget. 
- __iUIContext::Draw__() -> _void_: Draw the GUI. 
- __iUIContext::DrawCursor__(_iOSWindow\*_ apWindow) -> _void_: Draw the current mouse cursor or set it as hardware cursor on the specified window if it is specified and supported by the graphics context. 
- __iUIContext::Update__(_tF32_ fTime) -> _tBool_: Updates the GUI. 
- __iUIContext::Resize__(_const sRectf&_ aRootRect, _const tF32_ afContentsScale) -> _tBool_: Resize the UI context. 
- __iUIContext::GetContentsScale__() -> _tF32_: Get the contents' scale factor. 
- __iUIContext::SetDebugDraw__(_tBool_ abDebug) -> _void_: Set whether debug draw is enabled. 
- __iUIContext::GetDebugDraw__() -> _tBool_: Get whether debug draw is enabled. 
- __iUIContext::SetCursor__(_iOverlay\*_ pCursor) -> _tBool_: Set the current mouse cursor. 
- __iUIContext::GetCursor__() -> _iOverlay\*_: Get the current mouse cursor. 
- __iUIContext::GetCursorPosition__() -> _sVec2f_: Get the cursor position. 
- __iUIContext::InitializeDefaultToolbar__() -> _void_: Initialize the a toolbar in the root widget. 
- __iUIContext::SetToolbar__(_iWidget\*_ apToolbar) -> _ni::tBool_: Set the UI default toolbar. 
- __iUIContext::GetToolbar__() -> _ni::iWidget\*_: Get the UI default toolbar. 
- __iUIContext::SetDrawOpCapture__(_tBool_ abEnabled) -> _void_: Set whether the draw operation capture hud is enabled. 
- __iUIContext::GetDrawOpCapture__() -> _ni::tBool_: Get whether the draw operation capture hud is enabled. 
- __iUIContext::DrawWidget__(_iWidget\*_ apWidget, _iCanvas\*_ apCanvas) -> _tBool_: Draw the specified widget in the specified canvas. 
- __iUIContext::DrawTransformedWidget__(_iWidget\*_ apWidget, _iCanvas\*_ apCanvas, _const sMatrixf&_ aBaseMatrix) -> _tBool_: Draw the specified widget in the specified canvas. The widget is transformed using the specified matrix. Clipping and scissoring is disabled. 
- __iUIContext::SetDragStartDistance__(_tU32_ anPixelDistance) -> _void_: Set the drag start distance. 
- __iUIContext::GetDragStartDistance__() -> _tU32_: Get the drag start distance. 
- __iUIContext::SetDragFingerStartDistance__(_tU32_ anFinger, _tU32_ anPixelDistance) -> _void_: Set the drag finger start distance. 
- __iUIContext::GetDragFingerStartDistance__(_tU32_ anFinger) -> _tU32_: Get the drag finger start distance. 
- __iUIContext::GetFingerPosition__(_tU32_ anFinger) -> _sVec3f_: Get a finger's latest screen position and pressure. 
- __iUIContext::GetFingerDown__(_tU32_ anFinger) -> _tBool_: Get a finger's latest down state. 
- __iUIContext::ClearShortcuts__() -> _void_: Remove all shortcuts. 
- __iUIContext::AddShortcut__(_tU32_ anKey, _iHString\*_ ahspCmd) -> _void_: Add a shortcut. 
- __iUIContext::RemoveShortcut__(_tU32_ anKey) -> _void_: Remove a shortcut. 
- __iUIContext::GetShortcutCommand__(_tU32_ anKey) -> _iHString\*_: Get the command of the specified shortcut. 
- __iUIContext::GetKeyDown__(_tU8_ aKey) -> _tBool_: Get a keyboard key's down state. 
- __iUIContext::InputFingerMove__(_tU32_ anFinger, _const sVec3f&_ avPosition) -> _void_
- __iUIContext::InputFingerRelativeMove__(_tU32_ anFinger, _const sVec3f&_ avRelMove) -> _void_
- __iUIContext::InputFingerPress__(_tU32_ anFinger, _const sVec3f&_ avPosition, _tBool_ abDown) -> _void_
- __iUIContext::InputKeyPress__(_eKey_ aKey, _tBool_ abDown) -> _void_
- __iUIContext::InputKeyChar__(_tU32_ aCharCodePoint, _eKey_ aKeyLeadingToKeyChar) -> _void_
- __iUIContext::InputMouseWheel__(_const tF32_ afDelta) -> _void_
- __iUIContext::InputDoubleClick__(_ePointerButton_ aPointer) -> _void_
- __iUIContext::InputRelativeMouseMove__(_const sVec2f&_ avRelMove) -> _void_
- __iUIContext::InputGameCtrl__(_iGameCtrl\*_ apGameController) -> _void_
- __iUIContext::InputPinch__(_const tF32_ afScale, _const eGestureState_ aState) -> _void_
- __iUIContext::GetFocusedWidget__() -> _iWidget\*_: Get the focused widget, that is the widget that is receiving the input messages. 
- __iUIContext::CreateProfDraw__(_iCanvas\*_ apCanvas, _iFont\*_ apFont) -> _iProfDraw\*_: Create an iProfDraw instance which uses the specifed canvas and font. 
- __iUIContext::SetShowTerminal__(_tBool_ abEnabled) -> _void_: Set whether the builtin terminal is enabled. 
- __iUIContext::GetShowTerminal__() -> _ni::tBool_: Get whether the builtin terminal is enabled. 

## enum ni::eUIInputModifier
UI input modifiers. 

### Remarks:
- The key values are intentionally the same as ni::eKeyMod 

### Values:
- __eUIInputModifier_A__ = __niBit(16)__: Modifier A. 
- __eUIInputModifier_Control__ = __eUIInputModifier_A__: Modifier A. 
- __eUIInputModifier_Command__ = __eUIInputModifier_A__: Modifier A. 
- __eUIInputModifier_AddSelection__ = __eUIInputModifier_A__: Modifier A. 
- __eUIInputModifier_B__ = __niBit(17)__: Modifier B. 
- __eUIInputModifier_Shift__ = __eUIInputModifier_B__: Modifier B. 
- __eUIInputModifier_AddSelectionRange__ = __eUIInputModifier_B__: Modifier B. 
- __eUIInputModifier_C__ = __niBit(18)__: Modifier C. 
- __eUIInputModifier_Alt__ = __eUIInputModifier_C__: Modifier C. 
- __eUIInputModifier_Shortcut__ = __eUIInputModifier_C__: Modifier C. 
- __eUIInputModifier_KeyDownRepeat__ = __niBit(31)__: KeyDown is repeating. 

## interface ni::iVertexArray
Vertex Array interface. 

### Parents:
- iDeviceResource

### Remarks:
- Bindable 

### Methods:
- __iVertexArray::GetFVF__() -> _tFVF_: Get the FVF of the vertex array. 
- __iVertexArray::GetNumVertices__() -> _tU32_: Get the number of vertices in the vertex array. 
- __iVertexArray::GetUsage__() -> _eArrayUsage_: Get the usage of the given vertex array. 
- __iVertexArray::Lock__(_tU32_ ulFirstVertex, _tU32_ ulNumVertex, _eLock_ aLock) -> _tPtr_: Lock vertex array memory to enable writting and reading in it. 
- __iVertexArray::Unlock__() -> _tBool_: Unlock vertex array memory. 
- __iVertexArray::GetIsLocked__() -> _tBool_: Return true if the array is locked. 

## interface ni::iVertexArray
Vertex Array interface. 

### Parents:
- iDeviceResource

### Remarks:
- Bindable 

### Methods:
- __iVertexArray::GetFVF__() -> _tFVF_: Get the FVF of the vertex array. 
- __iVertexArray::GetNumVertices__() -> _tU32_: Get the number of vertices in the vertex array. 
- __iVertexArray::GetUsage__() -> _eArrayUsage_: Get the usage of the given vertex array. 
- __iVertexArray::Lock__(_tU32_ ulFirstVertex, _tU32_ ulNumVertex, _eLock_ aLock) -> _tPtr_: Lock vertex array memory to enable writting and reading in it. 
- __iVertexArray::Unlock__() -> _tBool_: Unlock vertex array memory. 
- __iVertexArray::GetIsLocked__() -> _tBool_: Return true if the array is locked. 

## enum ni::eVGGradientType
Gradient type. 

### Values:
- __eVGGradientType_Linear__ = __0__: Linear gradient. 
- __eVGGradientType_Radial__ = __1__: Radial/circle gradient. 
- __eVGGradientType_Cross__ = __2__: Cross gradient. 
- __eVGGradientType_SqrtCross__ = __3__: Square root cross gradient. 
- __eVGGradientType_Conic__ = __4__: Conic gradient. 
- __eVGGradientType_Diamond__ = __5__: Diamond gradient. 

## interface ni::iVGGradientTable
Gradient table. 

### Parents:
- iUnknown

### Methods:
- __iVGGradientTable::Copy__(_const iVGGradientTable\*_ apSrc) -> _tBool_: Copy another table. 
- __iVGGradientTable::Clone__() -> _iVGGradientTable\*_: Clone this table. 
- __iVGGradientTable::GetSize__() -> _tU32_: Get the size of the table. 
- __iVGGradientTable::SetColor__(_tU32_ anIndex, _const sColor4f&_ aColor) -> _tBool_: Set the color of the gradient at the specified index. 
- __iVGGradientTable::GetColor__(_tU32_ anIndex) -> _sColor4f_: Get the color of the gradient at the specified index. 
- __iVGGradientTable::SetColorRange__(_tU32_ anStart, _tU32_ anEnd, _const sColor4f&_ avColor) -> _tBool_: Set a range of color. 
- __iVGGradientTable::GenerateTwoColors__(_const sColor4f&_ aStartColor, _const sColor4f&_ aEndColor) -> _void_: Generate a gradient between two colors. 
- __iVGGradientTable::GenerateStops__(_const tF32CVec\*_ apOffsets, _const tVec4fCVec\*_ apColors) -> _tBool_: Generate a gradient between specified stops. 
- __iVGGradientTable::CreateImage__(_eVGGradientType_ aType, _eVGWrapType_ aWrapType, _const iVGTransform\*_ apTransform, _tU32_ anWidth, _tU32_ anHeight, _tI32_ anD1, _tI32_ anD2) -> _iVGImage\*_: Create an image containing the gradient. 

## enum ni::eVGGradientType
Gradient type. 

### Values:
- __eVGGradientType_Linear__ = __0__: Linear gradient. 
- __eVGGradientType_Radial__ = __1__: Radial/circle gradient. 
- __eVGGradientType_Cross__ = __2__: Cross gradient. 
- __eVGGradientType_SqrtCross__ = __3__: Square root cross gradient. 
- __eVGGradientType_Conic__ = __4__: Conic gradient. 
- __eVGGradientType_Diamond__ = __5__: Diamond gradient. 

## enum ni::eVGWrapType
VG wrap type. 

### Values:
- __eVGWrapType_Clamp__ = __0__: Clamp, the edge color is used when outside of the source rectangle. 
- __eVGWrapType_Repeat__ = __1__: Repeat, the source is repeated at each source rectangle boundary. 
- __eVGWrapType_Mirror__ = __2__: Mirror, the source is mirror at each source rectangle boundary. 
- __eVGWrapType_Pad__ = __3__: Padding, the background color is used when outside of the source rectangle. 

## enum ni::eVGImageFilter
VG Image filter. 

### Values:
- __eVGImageFilter_Point__ = __0__: No filter. 
- __eVGImageFilter_Bilinear__ = __1__: Bilinear filter. 
- __eVGImageFilter_Bicubic__ = __2__: Bicubic filter. 
- __eVGImageFilter_Spline16__ = __3__: Spline16 filter. 
- __eVGImageFilter_Spline36__ = __4__: Spline36 filter. 
- __eVGImageFilter_Hanning__ = __5__: Hanning filter. 
- __eVGImageFilter_Hamming__ = __6__: Hamming filter. 
- __eVGImageFilter_Hermite__ = __7__: Hermite filter. 
- __eVGImageFilter_Kaiser__ = __8__: Kaiser filter. 
- __eVGImageFilter_Quadric__ = __9__: Quadric filter. 
- __eVGImageFilter_Catrom__ = __10__: Catrom filter. 
- __eVGImageFilter_Gaussian__ = __11__: Gaussian filter. 
- __eVGImageFilter_Bessel__ = __12__: Bessel filter. 
- __eVGImageFilter_Mitchell__ = __13__: Mitchell filter. 
- __eVGImageFilter_Sinc__ = __14__: Sinc filter. 
- __eVGImageFilter_Lanczos__ = __15__: Lanczos filter. 
- __eVGImageFilter_Blackman__ = __16__: Blackman filter. 
- __eVGImageFilter_Last__ = __17__: \internal 

## enum ni::eVGImageUsage
VGImage usage. 

### Values:
- __eVGImageUsage_Source__ = __0__: The usage is read-only to be used a source for rendering. 
- __eVGImageUsage_Target__ = __1__: The usage is write-only to be used as a render target. 
- __eVGImageUsage_DepthStencil__ = __2__: For GetTexture only, grabs the depth stencil for rendering. 

## interface ni::iVGImage
VGImage interface. 

### Parents:
- iUnknown

### Methods:
- __iVGImage::Copy__(_iVGImage\*_ apImage) -> _tBool_: Copy the specified image. 
- __iVGImage::Clone__() -> _Ptr<iVGImage>_: Clone this image. 
- __iVGImage::GetHasBitmap__() -> _tBool_: Get whether a bitmap is already initialized in the image. 
- __iVGImage::GrabBitmap__(_eVGImageUsage_ aLock, _const sRecti&_ aDirtyRect) -> _iBitmap2D\*_: Grab the image as a bitmap to be used for some other operations. 
- __iVGImage::GetHasTexture__() -> _tBool_: Get whether a texture is already initialized in the image. 
- __iVGImage::GetHasDepthStencil__() -> _tBool_: Get whether a depth stencil is already initialized in the image. 
- __iVGImage::GrabTexture__(_eVGImageUsage_ aLock, _const sRecti&_ aDirtyRect) -> _iTexture\*_: Grab the image as a texture to be used for some other operations. 
- __iVGImage::GetWidth__() -> _tU32_: Get the image's width. 
- __iVGImage::GetHeight__() -> _tU32_: Get the image's height. 
- __iVGImage::GetSize__() -> _sVec2f_: Get the image's size in a vector2f. 
- __iVGImage::Resize__(_tU32_ anNewWidth, _tU32_ anNewHeight) -> _tBool_: Resize the image. 

## enum ni::eVGWrapType
VG wrap type. 

### Values:
- __eVGWrapType_Clamp__ = __0__: Clamp, the edge color is used when outside of the source rectangle. 
- __eVGWrapType_Repeat__ = __1__: Repeat, the source is repeated at each source rectangle boundary. 
- __eVGWrapType_Mirror__ = __2__: Mirror, the source is mirror at each source rectangle boundary. 
- __eVGWrapType_Pad__ = __3__: Padding, the background color is used when outside of the source rectangle. 

## enum ni::eVGPaintType
VG paint type. 

### Values:
- __eVGPaintType_Solid__ = __0__: Solid paint type. 
- __eVGPaintType_Image__ = __1__: Image paint type. 
- __eVGPaintType_Gradient__ = __2__: Gradient paint type. 

## enum ni::eVGPaintUnits
VG paint units. 

### Values:
- __eVGPaintUnits_Absolute__ = __0__: Units are absolute (default). 
- __eVGPaintUnits_ObjectBoundingBox__ = __1__: Units relative to the element's bounding box. 
- __eVGPaintUnits_UserSpaceOnUse__ = __2__: Units relative to the current coordinate system. 

## interface ni::iVGPaint
VG paint interface. 

### Parents:
- iUnknown

### Methods:
- __iVGPaint::Copy__(_const iVGPaint\*_ apSrc) -> _tBool_: Copy another paint of the same type. 
- __iVGPaint::Clone__() -> _iVGPaint\*_: Clone this paint. 
- __iVGPaint::GetType__() -> _eVGPaintType_: Get the paint type. 
- __iVGPaint::SetColor__(_const sColor4f&_ aColor) -> _void_: Set the paint color. 
- __iVGPaint::GetColor__() -> _const sColor4f&_: Get the paint color. 

## interface ni::iVGPaintImage
VG paint image interface. 

### Parents:
- iVGPaint

### Methods:
- __iVGPaintImage::GetImage__() -> _iVGImage\*_: Get the painted image. 
- __iVGPaintImage::SetFilterType__(_eVGImageFilter_ aType) -> _void_: Set the image filter type. 
- __iVGPaintImage::GetFilterType__() -> _eVGImageFilter_: Get the image filter type. 
- __iVGPaintImage::SetFilterRadius__(_tF32_ afRadius) -> _void_: Set the image filter radius. 
- __iVGPaintImage::GetFilterRadius__() -> _tF32_: Get the image filter radius. 
- __iVGPaintImage::SetFilterNormalize__(_tBool_ abNormalize) -> _void_: Set the image filter normalization flag. 
- __iVGPaintImage::GetFilterNormalize__() -> _tBool_: Get the image filter normalization flag. 
- __iVGPaintImage::SetWrapType__(_eVGWrapType_ aWrapType) -> _void_: Set the paint wrap type. 
- __iVGPaintImage::GetWrapType__() -> _eVGWrapType_: Get the paint wrap type. 
- __iVGPaintImage::SetRectangle__(_const sRectf&_ aRect) -> _void_: Set the image's display rectangle. 
- __iVGPaintImage::GetRectangle__() -> _sRectf_: Get the image's display rectangle. 
- __iVGPaintImage::SetUnits__(_eVGPaintUnits_ aUnits) -> _void_: Set the paint units. 
- __iVGPaintImage::GetUnits__() -> _eVGPaintUnits_: Get the paint units. 
- __iVGPaintImage::SetSource__(_iUnknown\*_ apSource) -> _void_: Set the source user pointer to be used to generate the image's content. 
- __iVGPaintImage::GetSource__() -> _iUnknown\*_: Get the source user pointer to be used to generate the image's content. 
- __iVGPaintImage::SetSourceUnits__(_eVGPaintUnits_ aUnits) -> _void_: Set the content units. 
- __iVGPaintImage::GetSourceUnits__() -> _eVGPaintUnits_: Get the content units. 

## interface ni::iVGPaintGradient
VG paint gradient interface. 

### Parents:
- iVGPaint

### Methods:
- __iVGPaintGradient::SetGradientType__(_eVGGradientType_ aType) -> _void_: Set the type of gradient. 
- __iVGPaintGradient::GetGradientType__() -> _eVGGradientType_: Get the type of gradient. 
- __iVGPaintGradient::SetD1__(_tI32_ anD1) -> _void_: Set the D1 parameter. 
- __iVGPaintGradient::GetD1__() -> _tI32_: Get the D1 parameter. 
- __iVGPaintGradient::SetD2__(_tI32_ anD2) -> _void_: Set the D2 parameter. 
- __iVGPaintGradient::GetD2__() -> _tI32_: Get the D2 parameter. 
- __iVGPaintGradient::SetWrapType__(_eVGWrapType_ aWrapType) -> _void_: Set the paint wrap type. 
- __iVGPaintGradient::GetWrapType__() -> _eVGWrapType_: Get the paint wrap type. 
- __iVGPaintGradient::SetA__(_const sVec2f&_ aV) -> _void_: Set the direction start for linear gradient, or center for radial gradients. 
- __iVGPaintGradient::GetA__() -> _sVec2f_: Get the direction start for linear gradient, or center for radial gradients. 
- __iVGPaintGradient::SetB__(_const sVec2f&_ aV) -> _void_: Set the direction end for linear gradient, or focal for radial gradients. 
- __iVGPaintGradient::GetB__() -> _sVec2f_: Get the direction end for linear gradient, or focal for radial gradients. 
- __iVGPaintGradient::SetR__(_tF32_ afV) -> _void_: Set the distance scale for linear gradient, or radius for radial gradients. 
- __iVGPaintGradient::GetR__() -> _tF32_: Get the distance scale for linear gradient, or radius for radial gradients. 
- __iVGPaintGradient::SetUnits__(_eVGPaintUnits_ aUnits) -> _void_: Set the paint units. 
- __iVGPaintGradient::GetUnits__() -> _eVGPaintUnits_: Get the paint units. 
- __iVGPaintGradient::GetGradientTable__() -> _iVGGradientTable\*_: Get the gradient table. 

## enum ni::eVGPaintType
VG paint type. 

### Values:
- __eVGPaintType_Solid__ = __0__: Solid paint type. 
- __eVGPaintType_Image__ = __1__: Image paint type. 
- __eVGPaintType_Gradient__ = __2__: Gradient paint type. 

## enum ni::eVGPathCommand
VGPath commands. 

### Values:
- __eVGPathCommand_Stop__ = __0__: Stop command. 
- __eVGPathCommand_MoveTo__ = __1__: MoveTo command. 
- __eVGPathCommand_LineTo__ = __2__: LineTo command. 
- __eVGPathCommand_Curve3__ = __3__: Quadric curve command. 
- __eVGPathCommand_Curve4__ = __4__: Cubic curve command. 
- __eVGPathCommand_CurveN__ = __5__: N curve command. 
- __eVGPathCommand_Catrom__ = __6__: Catrom command. 
- __eVGPathCommand_UBSpline__ = __7__: UBSpline command. 
- __eVGPathCommand_EndPoly__ = __0x0F__: End poly command. 
- __eVGPathCommand_Mask__ = __0x0F__: Command mask. 

## interface ni::iVGPathTesselatedRenderer
VGPathTesselatedRenderer interface. 

### Parents:
- iUnknown

### Methods:
- __iVGPathTesselatedRenderer::BeginAddPath__(_const iVGStyle\*_ apStyle, _tBool_ abStroke) -> _void_: Called when begining to render a path. 
- __iVGPathTesselatedRenderer::EndAddPath__(_const iVGStyle\*_ apStyle, _tBool_ abStroke) -> _void_: Called when end adding a path. 
- __iVGPathTesselatedRenderer::GetPathApproximationScale__(_const iVGStyle\*_ apStyle) -> _tF32_: Called to request the approximation scale. 
- __iVGPathTesselatedRenderer::AddPathPolygons__(_iVGPolygonTesselator\*_ apTess, _const iVGStyle\*_ apStyle, _tBool_ abStroke) -> _void_: Called to add the path's polygons. 

## interface ni::iVGPath
VGPath interface. 

### Parents:
- iUnknown

### Methods:
- __iVGPath::Copy__(_const iVGPath\*_ apPath) -> _tBool_: Copy the specified path. 
- __iVGPath::Clone__() -> _iVGPath\*_: Clone this path. 
- __iVGPath::Clear__() -> _void_: Clear the path. 
- __iVGPath::AddVertex__(_const sVec2f&_ avVertex, _eVGPathCommand_ aCommand) -> _tBool_: Add a vertex to the path. 
- __iVGPath::AddPath__(_const iVGPath\*_ apPath) -> _tBool_: Add another path to the end of this path. 
- __iVGPath::GetNumVertices__() -> _tSize_: Get the number of vertices in the path. 
- __iVGPath::SetVertex__(_tU32_ anIndex, _const sVec2f&_ avVertex) -> _tBool_: Set the vertex at the specified index. 
- __iVGPath::GetVertex__(_tU32_ anIndex) -> _sVec2f_: Get the vertex at the specified index. 
- __iVGPath::SetCommand__(_tU32_ anIndex, _eVGPathCommand_ aCmd) -> _tBool_: Set the command at the specified index. 
- __iVGPath::GetCommand__(_tU32_ anIndex) -> _eVGPathCommand_: Get the command at the specified index. 
- __iVGPath::ResetIterator__() -> _void_: Reset the iterator. 
- __iVGPath::GetNextIterator__() -> _eVGPathCommand_: Get the next vertex of the iterator. 
- __iVGPath::GetVertexIterator__() -> _sVec2f_: Get the current vertex of the iterator. 
- __iVGPath::FlipX__(_tF32_ x1, _tF32_ x2) -> _void_: Flip the path along the X-axis. 
- __iVGPath::FlipY__(_tF32_ y1, _tF32_ y2) -> _void_: Flip the path along the Y-axis. 
- __iVGPath::MoveTo__(_tF32_ x, _tF32_ y) -> _void_: Move to the specified position. 
- __iVGPath::MoveToRel__(_tF32_ x, _tF32_ y) -> _void_: Move to the specified position, relativly to the previous vertex. 
- __iVGPath::LineTo__(_tF32_ x, _tF32_ y) -> _void_: Add a line to the specified position. 
- __iVGPath::LineToRel__(_tF32_ x, _tF32_ y) -> _void_
- __iVGPath::HLineTo__(_tF32_ x) -> _void_: Add an horizontal line to the specified column. 
- __iVGPath::HLineToRel__(_tF32_ x) -> _void_
- __iVGPath::VLineTo__(_tF32_ y) -> _void_: Add a vertical line to the specified line. 
- __iVGPath::VLineToRel__(_tF32_ y) -> _void_: Add a vertical line to the specified line, relativly to the previous vertex. 
- __iVGPath::Curve3__(_tF32_ x1, _tF32_ y1, _tF32_ x, _tF32_ y) -> _void_: Quadratic Bezier curveto. 
- __iVGPath::Curve3Rel__(_tF32_ x1, _tF32_ y1, _tF32_ x, _tF32_ y) -> _void_: Quadratic Bezier curveto. 
- __iVGPath::Curve3Prev__(_tF32_ x, _tF32_ y) -> _void_: Shorthand/smooth quadratic Bezier curveto. 
- __iVGPath::Curve3PrevRel__(_tF32_ x, _tF32_ y) -> _void_: Shorthand/smooth quadratic Bezier curveto, relativly to the previous vertex. 
- __iVGPath::Curve4__(_tF32_ x1, _tF32_ y1, _tF32_ x2, _tF32_ y2, _tF32_ x, _tF32_ y) -> _void_: Cubic Bezier curveto. 
- __iVGPath::Curve4Rel__(_tF32_ x1, _tF32_ y1, _tF32_ x2, _tF32_ y2, _tF32_ x, _tF32_ y) -> _void_: Cubic Bezier curveto, relativly to the previous vertex. 
- __iVGPath::Curve4Prev__(_tF32_ x2, _tF32_ y2, _tF32_ x, _tF32_ y) -> _void_: Shorthand/smooth cubic Bezier curveto. 
- __iVGPath::Curve4PrevRel__(_tF32_ x2, _tF32_ y2, _tF32_ x, _tF32_ y) -> _void_: Shorthand/smooth cubic Bezier curveto, relativly to the previous vertex. 
- __iVGPath::Curve4K__(_tF32_ x2, _tF32_ y2, _tF32_ k) -> _void_: Cubic curve with auto control point computation, relativly to the previous vertex. 
- __iVGPath::Curve4KRel__(_tF32_ x2, _tF32_ y2, _tF32_ k) -> _void_: Cubic curve with auto control point computation. 
- __iVGPath::Hermite__(_tF32_ x2, _tF32_ y2, _tF32_ x3, _tF32_ y3, _tF32_ x4, _tF32_ y4) -> _void_
- __iVGPath::HermiteRel__(_tF32_ x2, _tF32_ y2, _tF32_ x3, _tF32_ y3, _tF32_ x4, _tF32_ y4) -> _void_
- __iVGPath::UBSpline__(_tF32_ x2, _tF32_ y2, _tF32_ x3, _tF32_ y3, _tF32_ x4, _tF32_ y4) -> _void_
- __iVGPath::UBSplineRel__(_tF32_ x2, _tF32_ y2, _tF32_ x3, _tF32_ y3, _tF32_ x4, _tF32_ y4) -> _void_
- __iVGPath::Catrom__(_tF32_ x2, _tF32_ y2, _tF32_ x3, _tF32_ y3, _tF32_ x4, _tF32_ y4) -> _void_
- __iVGPath::CatromRel__(_tF32_ x2, _tF32_ y2, _tF32_ x3, _tF32_ y3, _tF32_ x4, _tF32_ y4) -> _void_
- __iVGPath::ArcTo__(_tF32_ rx, _tF32_ ry, _tF32_ angle, _tBool_ large_arc_flag, _tBool_ sweep_flag, _tF32_ x, _tF32_ y) -> _void_: Elliptical arc. 
- __iVGPath::ArcToRel__(_tF32_ rx, _tF32_ ry, _tF32_ angle, _tBool_ large_arc_flag, _tBool_ sweep_flag, _tF32_ x, _tF32_ y) -> _void_: Elliptical arc, relativly to the previous vertex. 
- __iVGPath::ClosePolygon__() -> _void_: Close the current path's polygon. 
- __iVGPath::Rect__(_tF32_ x, _tF32_ y, _tF32_ width, _tF32_ height) -> _void_: Add a rectangle. 
- __iVGPath::RoundedRect__(_tF32_ x, _tF32_ y, _tF32_ width, _tF32_ height, _tF32_ rx, _tF32_ ry) -> _void_: Add a rounded rectangle. 
- __iVGPath::RectCentered__(_tF32_ cx, _tF32_ cy, _tF32_ width, _tF32_ height) -> _void_: Add a centered rectangle. 
- __iVGPath::RoundedRectCentered__(_tF32_ cx, _tF32_ cy, _tF32_ width, _tF32_ height, _tF32_ rx, _tF32_ ry) -> _void_: Add a rounded centered rectangle. 
- __iVGPath::SpeechBubbleRect__(_const tF32_ x, _const tF32_ y, _const tF32_ w, _const tF32_ h, _const tF32_ rx, _const tF32_ ry, _const tF32_ tx, _const tF32_ ty, _const tF32_ arrowGap, _const tF32_ arrowLen) -> _void_: Add a speech bubble rectangle. 
- __iVGPath::Circle__(_tF32_ cx, _tF32_ cy, _tF32_ radius) -> _void_: Add a circle. 
- __iVGPath::Ellipse__(_tF32_ cx, _tF32_ cy, _tF32_ rx, _tF32_ ry) -> _void_: Add an ellipse. 
- __iVGPath::Line__(_tF32_ x1, _tF32_ y1, _tF32_ x2, _tF32_ y2) -> _tBool_: Add a line. 
- __iVGPath::Polyline__(_const tVec2fCVec\*_ apVerts) -> _tBool_: Add a polyline. 
- __iVGPath::Polygon__(_const tVec2fCVec\*_ apVerts) -> _tBool_: Add a polygon. 
- __iVGPath::Star__(_tF32_ xc, _tF32_ yc, _tF32_ r1, _tF32_ r2, _tU32_ n, _tF32_ start_angle) -> _void_: Add a star shape. 
- __iVGPath::Text__(_iFont\*_ apFont, _const sVec2f&_ avPos, _const achar\*_ aaszText) -> _tBool_: Add a text. 
- __iVGPath::TextAlongOnePath__(_iFont\*_ apFont, _const achar\*_ aaszText, _const iVGPath\*_ apPath, _tBool_ abPreserveXScale, _tF32_ afBaseLength, _tF32_ afSegmentApproxScale, _tF32_ afCurvesApproxScale) -> _tBool_: Add a text along a path. 
- __iVGPath::TextAlongTwoPaths__(_iFont\*_ apFont, _const achar\*_ aaszText, _const iVGPath\*_ apPath1, _const iVGPath\*_ apPath2, _tBool_ abPreserveXScale, _tF32_ afBaseHeight, _tF32_ afBaseLength, _tF32_ afSegmentApproxScale, _tF32_ afCurvesApproxScale) -> _tBool_: Add a text between two paths. 
- __iVGPath::ToBSpline__(_tF32_ afInterpolationStep) -> _void_: Transform the path to a bspline 
- __iVGPath::Translate__(_const sVec2f&_ avTranslate) -> _tBool_: Translate the path. 
- __iVGPath::Rotate__(_tF32_ afRadians) -> _tBool_: Rotate the path. 
- __iVGPath::Scale__(_const sVec2f&_ avScale) -> _tBool_: Scale the path. 
- __iVGPath::Transform__(_const iVGTransform\*_ apTransform) -> _tBool_: Transform the path with the specified transform. 
- __iVGPath::TransformAlongOnePath__(_const iVGPath\*_ apPath, _tBool_ abPreserveXScale, _tF32_ afBaseLength, _tF32_ afSegmentApproxScale, _tF32_ afCurvesApproxScale) -> _tBool_: Transform the path along another path 
- __iVGPath::TransformAlongTwoPaths__(_const iVGPath\*_ apPath1, _const iVGPath\*_ apPath2, _tBool_ abPreserveXScale, _tF32_ afBaseHeight, _tF32_ afBaseLength, _tF32_ afSegmentApproxScale, _tF32_ afCurvesApproxScale) -> _tBool_: Transform the path against two other paths 
- __iVGPath::ArrangeOrientations__(_tBool_ abCW) -> _void_: Make all polygons follow the same orientation. 
- __iVGPath::GetBoundingRect__(_const iVGTransform\*_ apTransform) -> _sRectf_: Get the path's bounding box. 
- __iVGPath::RenderTesselated__(_iVGPathTesselatedRenderer\*_ apPath, _const iVGTransform\*_ apTransform, _const iVGStyle\*_ apStyle) -> _tBool_: Render the tesselated path. 
- __iVGPath::AddSVGPath__(_const achar\*_ aaszPath) -> _tBool_: Add a SVG path. 
- __iVGPath::AddPolylinePath__(_const achar\*_ aaszPath) -> _tBool_: Add a polyline path. 
- __iVGPath::AddPolygonPath__(_const achar\*_ aaszPath) -> _tBool_: Add a polygon path. 
- __iVGPath::GetSVGPath__() -> _cString_: Get the path in a SVG string form. 

## enum ni::eVGPathCommand
VGPath commands. 

### Values:
- __eVGPathCommand_Stop__ = __0__: Stop command. 
- __eVGPathCommand_MoveTo__ = __1__: MoveTo command. 
- __eVGPathCommand_LineTo__ = __2__: LineTo command. 
- __eVGPathCommand_Curve3__ = __3__: Quadric curve command. 
- __eVGPathCommand_Curve4__ = __4__: Cubic curve command. 
- __eVGPathCommand_CurveN__ = __5__: N curve command. 
- __eVGPathCommand_Catrom__ = __6__: Catrom command. 
- __eVGPathCommand_UBSpline__ = __7__: UBSpline command. 
- __eVGPathCommand_EndPoly__ = __0x0F__: End poly command. 
- __eVGPathCommand_Mask__ = __0x0F__: Command mask. 

## interface ni::iVGPolygonTesselator
Polygon tessellator interface. 

### Parents:
- iUnknown

### Methods:
- __iVGPolygonTesselator::AddVertexF32__(_tF32_ x, _tF32_ y) -> _tBool_: Add a F32 vertex to the current polygon contour. 
- __iVGPolygonTesselator::AddVertexF64__(_tF64_ x, _tF64_ y) -> _tBool_: Add a F64 vertex to the current polygon contour. 
- __iVGPolygonTesselator::AddVertex__(_const sVec2f&_ vertex) -> _tBool_: Add a Vec2f vertex to the current polygon contour. 
- __iVGPolygonTesselator::GetNumVertices__() -> _tSize_: Get the number of vertices in the current contour. 
- __iVGPolygonTesselator::SubmitContour__() -> _tBool_: Submit the current contour. 
- __iVGPolygonTesselator::BeginPolygon__(_tBool_ abEvenOdd) -> _tBool_: Begin tesselating a polygon. 
- __iVGPolygonTesselator::EndPolygon__() -> _tBool_: Finish tesselating a polygon. 
- __iVGPolygonTesselator::GetTesselatedVertices__() -> _const tVec2fCVec\*_: Get the tesselated polygon's triangles vertices. 

## interface ni::iVGPolygonTesselator
Polygon tessellator interface. 

### Parents:
- iUnknown

### Methods:
- __iVGPolygonTesselator::AddVertexF32__(_tF32_ x, _tF32_ y) -> _tBool_: Add a F32 vertex to the current polygon contour. 
- __iVGPolygonTesselator::AddVertexF64__(_tF64_ x, _tF64_ y) -> _tBool_: Add a F64 vertex to the current polygon contour. 
- __iVGPolygonTesselator::AddVertex__(_const sVec2f&_ vertex) -> _tBool_: Add a Vec2f vertex to the current polygon contour. 
- __iVGPolygonTesselator::GetNumVertices__() -> _tSize_: Get the number of vertices in the current contour. 
- __iVGPolygonTesselator::SubmitContour__() -> _tBool_: Submit the current contour. 
- __iVGPolygonTesselator::BeginPolygon__(_tBool_ abEvenOdd) -> _tBool_: Begin tesselating a polygon. 
- __iVGPolygonTesselator::EndPolygon__() -> _tBool_: Finish tesselating a polygon. 
- __iVGPolygonTesselator::GetTesselatedVertices__() -> _const tVec2fCVec\*_: Get the tesselated polygon's triangles vertices. 

## enum ni::eVGLineCap
VG Line Cap type. 

### Values:
- __eVGLineCap_Butt__ = __0__
- __eVGLineCap_Square__ = __1__
- __eVGLineCap_Round__ = __2__

## enum ni::eVGLineJoin
VG Line join. 

### Values:
- __eVGLineJoin_Miter__ = __0__
- __eVGLineJoin_MiterRevert__ = __1__
- __eVGLineJoin_MiterRound__ = __2__
- __eVGLineJoin_Round__ = __3__
- __eVGLineJoin_Bevel__ = __4__

## enum ni::eVGInnerJoin
VG Inner join. 

### Values:
- __eVGInnerJoin_Bevel__ = __0__
- __eVGInnerJoin_Miter__ = __1__
- __eVGInnerJoin_Jag__ = __2__
- __eVGInnerJoin_Round__ = __3__

## interface ni::iVGStyle
VGStyle inteface. 

### Parents:
- iUnknown

### Methods:
- __iVGStyle::Copy__(_const iVGStyle\*_ apStyle) -> _tBool_: Create a copy of the style. 
- __iVGStyle::Clone__() -> _iVGStyle\*_: Clone the style. 
- __iVGStyle::Push__() -> _tBool_: Push the style states. 
- __iVGStyle::Pop__() -> _tBool_: Pop the style states. 
- __iVGStyle::SetDefault__() -> _void_: Set the default states. 
- __iVGStyle::SetOpacity__(_tF32_ afOpacity) -> _void_: Set the global opacity. 
- __iVGStyle::GetOpacity__() -> _tF32_: Get the global opacity. 
- __iVGStyle::SetLineCap__(_eVGLineCap_ aCap) -> _void_: Set the line's cap. 
- __iVGStyle::GetLineCap__() -> _eVGLineCap_: Get the line's cap 
- __iVGStyle::SetLineJoin__(_eVGLineJoin_ aJoin) -> _void_: Set the line's join. 
- __iVGStyle::GetLineJoin__() -> _eVGLineJoin_: Get the line's join. 
- __iVGStyle::SetInnerJoin__(_eVGInnerJoin_ aInnerJoin) -> _void_: Set the inner join type. 
- __iVGStyle::GetInnerJoin__() -> _eVGInnerJoin_: Get the inner join type. 
- __iVGStyle::SetMiterLimit__(_tF32_ afMiterLimit) -> _void_: Set the miter limit. 
- __iVGStyle::GetMiterLimit__() -> _tF32_: Get the miter limit. 
- __iVGStyle::SetSmooth__(_tF32_ afSmooth) -> _void_: Set the smoothing. 
- __iVGStyle::GetSmooth__() -> _tF32_: Get the smoothing. 
- __iVGStyle::SetCurrentColor__(_const sColor4f&_ avColor) -> _void_: Set the current style color. 
- __iVGStyle::GetCurrentColor__() -> _const sColor4f&_: Get the current style color. 
- __iVGStyle::SetAntiAliasing__(_tBool_ abAntiAliasing) -> _void_: Set the antialiasing. 
- __iVGStyle::GetAntiAliasing__() -> _tBool_: Get whether antialiasing is enabled. 
- __iVGStyle::SetRasterizerApproximationScale__(_tF32_ afRasterizerApproximationScale) -> _void_: Set the rasterizer's approximation scale. 
- __iVGStyle::GetRasterizerApproximationScale__() -> _tF32_: Get the rasterizer's approximation scale. 
- __iVGStyle::SetTesselatorApproximationScale__(_tF32_ afTesselatorApproximationScale) -> _void_: Set the tesselator's approximation scale. 
- __iVGStyle::GetTesselatorApproximationScale__() -> _tF32_: Get the tesselator's approximation scale. 
- __iVGStyle::SetStroke__(_tBool_ abStroke) -> _void_: Set stroke drawing. 
- __iVGStyle::GetStroke__() -> _tBool_: Get whether stroke drawing is enabled. 
- __iVGStyle::SetStrokeWidth__(_tF32_ afWidth) -> _void_: Set the stroke's width. 
- __iVGStyle::GetStrokeWidth__() -> _tF32_: Get the stroke's width. 
- __iVGStyle::SetStrokeTransformed__(_tBool_ abStrokeTransformed) -> _void_: Set whether the transformed path should be stroked. 
- __iVGStyle::GetStrokeTransformed__() -> _tBool_: Get whether the transformed path should be stroked. 
- __iVGStyle::SetStrokePaint__(_iVGPaint\*_ apPaint) -> _tBool_: Set the stroke's paint. 
- __iVGStyle::GetStrokePaint__() -> _iVGPaint\*_: Get the stroke's paint. 
- __iVGStyle::SetStrokeColor__(_const sColor3f&_ avColor) -> _void_: Set the stroke's paint color. 
- __iVGStyle::GetStrokeColor__() -> _sColor3f_: Get the stroke's paint color. 
- __iVGStyle::SetStrokeColor4__(_const sColor4f&_ avColor) -> _void_: Set the stroke's paint color. 
- __iVGStyle::GetStrokeColor4__() -> _sColor4f_: Get the stroke's paint color. 
- __iVGStyle::SetStrokeOpacity__(_tF32_ afOpacity) -> _void_: Set the stroke opacity. 
- __iVGStyle::GetStrokeOpacity__() -> _tF32_: Get the stroke opacity. 
- __iVGStyle::GetNumDashes__() -> _tU32_: Get the number of dashes. 
- __iVGStyle::ClearDashes__() -> _void_: Remove all dashes. 
- __iVGStyle::AddDash__(_const sVec2f&_ aV) -> _void_: Add a dash. 
- __iVGStyle::RemoveDash__(_tU32_ anIndex) -> _tBool_: Remove a dash. 
- __iVGStyle::GetDash__(_tU32_ anIndex) -> _sVec2f_: Get the dash at the specified index. 
- __iVGStyle::SetDashStart__(_tF32_ afDashStart) -> _void_: Set the dash start. 
- __iVGStyle::GetDashStart__() -> _tF32_: Get the dash start. 
- __iVGStyle::SetFill__(_tBool_ abFill) -> _void_: Set fill drawing. 
- __iVGStyle::GetFill__() -> _tBool_: Get whether fill drawing is enabled. 
- __iVGStyle::SetFillEvenOdd__(_tBool_ abFillEvenOdd) -> _void_: Set fill odd even. 
- __iVGStyle::GetFillEvenOdd__() -> _tBool_: Get whether the fill uses the odd even or non zero rules to fill polygons. 
- __iVGStyle::SetFillExpand__(_tF32_ afExpand) -> _void_: Set the filling expand. 
- __iVGStyle::GetFillExpand__() -> _tF32_: Get the filling expand. 
- __iVGStyle::SetFillPaint__(_iVGPaint\*_ apPaint) -> _tBool_: Set the fill paint. 
- __iVGStyle::GetFillPaint__() -> _iVGPaint\*_: Get the fill paint. 
- __iVGStyle::SetFillColor__(_const sColor3f&_ avColor) -> _void_: Set the fill color. 
- __iVGStyle::GetFillColor__() -> _sColor3f_: Get the fill color. 
- __iVGStyle::SetFillColor4__(_const sColor4f&_ avColor) -> _void_: Set the fill color. 
- __iVGStyle::GetFillColor4__() -> _sColor4f_: Get the fill color. 
- __iVGStyle::SetFillOpacity__(_tF32_ afOpacity) -> _void_: Set the fill opacity. 
- __iVGStyle::GetFillOpacity__() -> _tF32_: Get the fill opacity. 

## enum ni::eVGLineCap
VG Line Cap type. 

### Values:
- __eVGLineCap_Butt__ = __0__
- __eVGLineCap_Square__ = __1__
- __eVGLineCap_Round__ = __2__

## enum ni::eVGTransform
VG transform type. 

### Values:
- __eVGTransform_Path__ = __0__: Path to surface transform. 
- __eVGTransform_Image__ = __1__: Image to surface transform. 
- __eVGTransform_FillPaint__ = __2__: Fill paint to user transform. 
- __eVGTransform_StrokePaint__ = __3__: Stroke paint to user transform. 
- __eVGTransform_Last__ = __4__: \internal 

## enum ni::eVGTransformValue
VG transform value. 

### Values:
- __eVGTransformValue_ScaleX__ = __0__: ScaleX (m0) component. 
- __eVGTransformValue_RotationSkew0__ = __1__: RotationSkew0 (m1) component. 
- __eVGTransformValue_RotationSkew1__ = __2__: RotationSkew1 (m2) component. 
- __eVGTransformValue_ScaleY__ = __3__: RotationSkew1 (m3) component. 
- __eVGTransformValue_TranslateX__ = __4__: RotationSkew1 (m4) component. 
- __eVGTransformValue_TranslateY__ = __5__: RotationSkew1 (m5) component. 

## interface ni::iVGTransform
VG transform interface. 

### Parents:
- iUnknown

### Methods:
- __iVGTransform::Copy__(_const iVGTransform\*_ apTransform) -> _tBool_: Copy another transform. 
- __iVGTransform::Clone__() -> _iVGTransform\*_: Clone this transform. 
- __iVGTransform::Push__() -> _tBool_: Push the transform states on the stack. 
- __iVGTransform::Pop__() -> _tBool_: Pop the transfrom states from the stack. 
- __iVGTransform::SetMatrix__(_const sMatrixf&_ aMatrix) -> _void_: Set the 3x2 transform matrix. 
- __iVGTransform::GetMatrix__() -> _sMatrixf_: Get the 3x2 transform matrix. 
- __iVGTransform::SetValue__(_eVGTransformValue_ aType, _tF32_ afValue) -> _void_: Set a value of the transform. 
- __iVGTransform::GetValue__(_eVGTransformValue_ aType) -> _tF32_: Get a value of the transform. 
- __iVGTransform::SetValues__(_tF32_ m0, _tF32_ m1, _tF32_ m2, _tF32_ m3, _tF32_ m4, _tF32_ m5) -> _void_: Set all values. 
- __iVGTransform::Identity__() -> _void_: Set the transform to identity. 
- __iVGTransform::Invert__() -> _void_: Invert the transform. 
- __iVGTransform::GetIsIdentity__() -> _tBool_: Check whether the transform is identity. 
- __iVGTransform::IsEqual__(_const iVGTransform\*_ apTransform) -> _tBool_: Check whether the transform is equal the passed transform. 
- __iVGTransform::GetDeterminant__() -> _tF32_: Get the transform's determinant. 
- __iVGTransform::FlipX__() -> _void_: Flip the transform's X-axis. 
- __iVGTransform::FlipY__() -> _void_: Flip the transform's Y-axis. 
- __iVGTransform::Transform__(_const sVec2f&_ avV) -> _sVec2f_: Transform a vertex. 
- __iVGTransform::TransformRotate__(_const sVec2f&_ avV) -> _sVec2f_: Transform a vertex with the rotational part (2x2) of the transform only. 
- __iVGTransform::Multiply__(_const iVGTransform\*_ apTransform) -> _void_: Multiply the transform. 
- __iVGTransform::PreMultiply__(_const iVGTransform\*_ apTransform) -> _void_: PreMultiply the transform. 
- __iVGTransform::MultiplyMatrix__(_const sMatrixf&_ aMatrix) -> _void_: Multiply the transform by a matrix. 
- __iVGTransform::PreMultiplyMatrix__(_const sMatrixf&_ aMatrix) -> _void_: PreMultiply the transform by a matrix. 
- __iVGTransform::MultiplyValues__(_tF32_ m0, _tF32_ m1, _tF32_ m2, _tF32_ m3, _tF32_ m4, _tF32_ m5) -> _void_: Multiply the transform by values. 
- __iVGTransform::PreMultiplyValues__(_tF32_ m0, _tF32_ m1, _tF32_ m2, _tF32_ m3, _tF32_ m4, _tF32_ m5) -> _void_: PreMultiply the transform by values. 
- __iVGTransform::Rotate__(_tF32_ afRadians) -> _void_: Rotate the transform. 
- __iVGTransform::PreRotate__(_tF32_ afRadians) -> _void_: PreRotate the transform. 
- __iVGTransform::RotateAround__(_const sVec2f&_ aV, _tF32_ afRadians) -> _void_: Rotate the transform around the specified position. 
- __iVGTransform::PreRotateAround__(_const sVec2f&_ aV, _tF32_ afRadians) -> _void_: PreRotate the transform around the specified position. 
- __iVGTransform::Translate__(_const sVec2f&_ aV) -> _void_: Translate the transform. 
- __iVGTransform::PreTranslate__(_const sVec2f&_ aV) -> _void_: PreTranslate the transform. 
- __iVGTransform::Scaling__(_const sVec2f&_ aV) -> _void_: Scale the transform. 
- __iVGTransform::PreScaling__(_const sVec2f&_ aV) -> _void_: PreScale the transform. 
- __iVGTransform::Skew__(_const sVec2f&_ aV) -> _void_: Skew the transform. 
- __iVGTransform::PreSkew__(_const sVec2f&_ aV) -> _void_: PreSkew the transform. 
- __iVGTransform::LineSegment__(_const sVec2f&_ aStart, _const sVec2f&_ aEnd, _tF32_ afDist) -> _void_: Generates a transform that point in the direction of a line segment. 
- __iVGTransform::PreLineSegment__(_const sVec2f&_ aStart, _const sVec2f&_ aEnd, _tF32_ afDist) -> _void_: Generates a transform that point in the direction of a line segment. \see ni::iVGTransform::LineSegment 
- __iVGTransform::GetRotation__() -> _tF32_: Get the transform's rotation. 
- __iVGTransform::GetScale__() -> _tF32_: Get the transform's scale. 
- __iVGTransform::GetTranslation__() -> _sVec2f_: Get the transform's translation. 
- __iVGTransform::GetScaling__() -> _sVec2f_: Get the transform's scaling. 

## enum ni::eVGTransform
VG transform type. 

### Values:
- __eVGTransform_Path__ = __0__: Path to surface transform. 
- __eVGTransform_Image__ = __1__: Image to surface transform. 
- __eVGTransform_FillPaint__ = __2__: Fill paint to user transform. 
- __eVGTransform_StrokePaint__ = __3__: Stroke paint to user transform. 
- __eVGTransform_Last__ = __4__: \internal 

## enum ni::eVideoDecoderFlags
Video decoder flags. 

### Values:
- __eVideoDecoderFlags_TargetBitmap__ = __niBit(0)__: Bitmap target. 
- __eVideoDecoderFlags_TargetTexture__ = __niBit(1)__: Texture target. 
- __eVideoDecoderFlags_Sound__ = __niBit(2)__: If available decode and sync sound stream with the video. 

## interface ni::iVideoDecoder
Video decoder interface. 

### Parents:
- iUnknown

### Methods:
- __iVideoDecoder::GetVideoDecoderName__() -> _const achar\*_: Get the name of the decoder used. 
- __iVideoDecoder::GetVideoFps__() -> _tF64_: Get the original number of frames per second of the video. 
- __iVideoDecoder::GetFlags__() -> _tVideoDecoderFlags_: Get the decoder flags. 
- __iVideoDecoder::GetLength__() -> _tF64_: Get the video's length. 
- __iVideoDecoder::SetTime__(_tF64_ afTime) -> _void_: Set the current time. 
- __iVideoDecoder::GetTime__() -> _tF64_: Get the current time. 
- __iVideoDecoder::SetPause__(_tBool_ abPause) -> _void_: Set pause. 
- __iVideoDecoder::GetPause__() -> _tBool_: Get the pause status. 
- __iVideoDecoder::SetSpeed__(_tF32_ afSpeed) -> _void_: Set the time's speed. 
- __iVideoDecoder::GetSpeed__() -> _tF32_: Get the time's speed. 
- __iVideoDecoder::SetNumLoops__(_ni::tU32_ anLoop) -> _void_: Set the number of time the time should loop. 
- __iVideoDecoder::GetNumLoops__() -> _ni::tU32_: Get the number of loop. 
- __iVideoDecoder::Update__(_tBool_ abUpdateTarget, _tF32_ afFrameTime) -> _tBool_: Update the video. 
- __iVideoDecoder::GetTargetTexture__() -> _iTexture\*_: Get the target texture. 
- __iVideoDecoder::GetTargetBitmap__() -> _iBitmap2D\*_: Get the target bitmap. 
- __iVideoDecoder::GetNumSoundTracks__() -> _tU32_: Get the number of sound tracks attached to the video. 
- __iVideoDecoder::GetSoundTrackData__(_tU32_ anNumTrack) -> _iUnknown\*_: Get a sound data of a track associated with the video. 
- __iVideoDecoder::SetUpdateOnBind__(_tBool_ abUpdateOnBind) -> _void_: Set whether the video should automatically be updated when bound for rendering. 
- __iVideoDecoder::GetUpdateOnBind__() -> _tBool_: Get whether the video should automatically be updated when bound for rendering. 

## enum ni::eVideoDecoderFlags
Video decoder flags. 

### Values:
- __eVideoDecoderFlags_TargetBitmap__ = __niBit(0)__: Bitmap target. 
- __eVideoDecoderFlags_TargetTexture__ = __niBit(1)__: Texture target. 
- __eVideoDecoderFlags_Sound__ = __niBit(2)__: If available decode and sync sound stream with the video. 

## enum ni::eWidgetStyle
Widget style. 

### Values:
- __eWidgetStyle_NCRelative__ = __niBit(0)__
- __eWidgetStyle_Free__ = __niBit(1)__: Free widget. 
- __eWidgetStyle_HoldFocus__ = __niBit(2)__: The widget will receive input focus. 
- __eWidgetStyle_OverFocus__ = __niBit(3)__: The widget will receive input focus when the cursor is above it. 
- __eWidgetStyle_NoClip__ = __niBit(4)__: The widget wont be clipped by it's parent. 
- __eWidgetStyle_NoClick__ = __niBit(5)__: No click and double click messages will be generated. 
- __eWidgetStyle_NotifyParent__ = __niBit(6)__: The parent widget is notified through the ParentNotify message when a message is sent to this widget. 
- __eWidgetStyle_FocusActivate__ = __niBit(7)__: Activate the widget just before receiving focus. 
- __eWidgetStyle_DontSerialize__ = __niBit(8)__: Don't serialize. 
- __eWidgetStyle_ItemOwned__ = __niBit(9)__: The item the widget is attached to owns it. This is to instruct items (such as tree nodes or list entry) to destroy/invalidate the widget when it isnt used anymore. 
- __eWidgetStyle_DragSource__ = __niBit(10)__: The the widget is a dragging source. 
- __eWidgetStyle_DragDestination__ = __niBit(11)__: The widget is a dragging destination. 
- __eWidgetStyle_Temp__ = __niBit(12)__: The widget is temporary, as for example the hover labels. 
- __eWidgetStyle_NoMoveFocus__ = __niBit(13)__: Focus won't be set on the widget as a response to the MoveFocus message. 
- __eWidgetStyle_NoAutoRedraw__ = __niBit(14)__: Dont redraw the widget automatically on input events. 
- __eWidgetStyle_MoveFocusGroup__ = __niBit(15)__: Widget is a "move focus group". 
- __eWidgetStyle_MaxBit__ = __16__: Max bit, user styles should use the bits above this. 

## enum ni::eWidgetDockStyle
Widget dock style. 

### Remarks:
- Docking flags allows to snap/dock the widget on the edges of it's parent control client area. 
- Snap only moves the widget to the specified edges, left and right are mutually exclusive, and top and bottom are mutually exclusive as well. 
- Dock stretch the widget to reach the specified edge and update the docking area, so that a fill dock will fill only the empty space left. 
- The widgets are docked in the ZOrder. 

### Values:
- __eWidgetDockStyle_None__ = __0__: No docking. 
- __eWidgetDockStyle_SnapLeft__ = __1__: Snap the widget on the left. 
- __eWidgetDockStyle_SnapRight__ = __2__: Snap the widget on the right. 
- __eWidgetDockStyle_SnapTop__ = __3__: Snap the widget on the top. 
- __eWidgetDockStyle_SnapBottom__ = __4__: Snap the widget on the bottom. 
- __eWidgetDockStyle_SnapCenterLeft__ = __5__: Snap the widget on the center left. 
- __eWidgetDockStyle_SnapLeftCenter__ = __5__
- __eWidgetDockStyle_SnapCenterRight__ = __6__: Snap the widget on the center right. 
- __eWidgetDockStyle_SnapRightCenter__ = __6__
- __eWidgetDockStyle_SnapCenterTop__ = __7__: Snap the widget on the center top. 
- __eWidgetDockStyle_SnapTopCenter__ = __7__
- __eWidgetDockStyle_SnapCenterBottom__ = __8__: Snap the widget on the center bottom. 
- __eWidgetDockStyle_SnapBottomCenter__ = __8__
- __eWidgetDockStyle_SnapTopLeft__ = __9__: Snap the widget on the top left. 
- __eWidgetDockStyle_SnapLeftTop__ = __9__
- __eWidgetDockStyle_SnapTopRight__ = __10__: Snap the widget on the top right. 
- __eWidgetDockStyle_SnapRightTop__ = __10__
- __eWidgetDockStyle_SnapBottomLeft__ = __11__: Snap the widget on the bottom left. 
- __eWidgetDockStyle_SnapLeftBottom__ = __11__
- __eWidgetDockStyle_SnapBottomRight__ = __12__: Snap the widget on the bottom right. 
- __eWidgetDockStyle_SnapRightBottom__ = __12__
- __eWidgetDockStyle_SnapCenter__ = __13__: Snap the widget in the center. 
- __eWidgetDockStyle_SnapCenterH__ = __14__: Snap the widget in the center horizontally. 
- __eWidgetDockStyle_SnapCenterV__ = __15__: Snap the widget in the center vertically. 
- __eWidgetDockStyle_DockLeft__ = __16__: Dock the widget on the left. 
- __eWidgetDockStyle_DockRight__ = __17__: Dock the widget on the right. 
- __eWidgetDockStyle_DockTop__ = __18__: Dock the widget on the top. 
- __eWidgetDockStyle_DockBottom__ = __19__: Dock the widget on the bottom. 
- __eWidgetDockStyle_DockFill__ = __20__: Dock the widget to fill the widget. 
- __eWidgetDockStyle_DockFillWidth__ = __21__: Dock the widget to fill the widget width. 
- __eWidgetDockStyle_DockFillHeight__ = __22__: Dock the widget to fill the widget height. 
- __eWidgetDockStyle_DockFillOverlay__ = __23__: Dock the widget to fill the all widget, this is meant to be used by overlays. 
- __eWidgetDockStyle_Grid__ = __24__: Place the widget in a grid. 

## enum ni::eWidgetZOrder
Widget ZOrder. 

### Remarks:
- These are the reserved ZOrder, to define a ZOrder explicitly pass a value less that eWidgetZOrder_Max. Zero is the overlay widget, higher values are below it. 

### Values:
- __eWidgetZOrder_BackgroundBottom__ = __0__: Places the widget in the background behind all background widgets. 
- __eWidgetZOrder_Background__ = __1__: Places the widget in the background. 
- __eWidgetZOrder_Bottom__ = __2__: Places the widget at the bottom of the Z order. 
- __eWidgetZOrder_Top__ = __3__: Places the widget at the top of the Z order. 
- __eWidgetZOrder_TopMostBottom__ = __4__: Places the widget above all non-topmost widgets but below all top-most widgets. 
- __eWidgetZOrder_TopMost__ = __5__: Places the widget above all non-topmost widgets. 
- __eWidgetZOrder_OverlayBottom__ = __6__: Places the widget above all other widgets, but below all overlay widgets. 
- __eWidgetZOrder_Overlay__ = __7__: Overlay widget. 

## enum ni::eWidgetSerializeFlags
Widget serialize flags. 

### Values:
- __eWidgetSerializeFlags_Write__ = __niBit(0)__: Serialize write. 
- __eWidgetSerializeFlags_Read__ = __niBit(1)__: Serialize read. 
- __eWidgetSerializeFlags_Children__ = __niBit(2)__: Serialize (read/write) the children of the widget. 
- __eWidgetSerializeFlags_NoRoot__ = __niBit(3)__: Don't serialize the root widget's information. 
- __eWidgetSerializeFlags_PropertyBox__ = __niBit(10)__: Edition property box serialization. 

## enum ni::eWidgetAutoLayoutFlags
Widget auto layout flags. 

### Values:
- __eWidgetAutoLayoutFlags_Relative__ = __niBit(0)__: Compute the children's relative sizes. 
- __eWidgetAutoLayoutFlags_Dock__ = __niBit(1)__: Compute the children's docking positions. 
- __eWidgetAutoLayoutFlags_Size__ = __niBit(2)__: Compute the size to fit the children. 

## interface ni::iWidgetSink
Widget sink interface. 

### Parents:
- iUnknown

### Methods:
- __iWidgetSink::OnWidgetSink__(_iWidget\*_ apWidget, _tU32_ nMsg, _const ni::Var&_ varParam0, _const ni::Var&_ varParam1) -> _tBool_: Widget sink message handler. 

## interface ni::iWidgetCommand
Widget command interface. 

### Parents:
- iUnknown

### Methods:
- __iWidgetCommand::Copy__(_const iWidgetCommand\*_ apSrc) -> _tBool_: Copy the specified command in this command. 
- __iWidgetCommand::Clone__() -> _iWidgetCommand\*_: Clone this command. 
- __iWidgetCommand::SetSender__(_iWidget\*_ apSender) -> _tBool_: Set the command sender. 
- __iWidgetCommand::GetSender__() -> _iWidget\*_: Get the command sender. 
- __iWidgetCommand::SetID__(_tU32_ anID) -> _void_: Set the command id. 
- __iWidgetCommand::GetID__() -> _tU32_: Get the command id. 
- __iWidgetCommand::SetExtra1__(_const Var&_ aVar) -> _void_: Set the extra parameter 1. 
- __iWidgetCommand::GetExtra1__() -> _const Var&_: Get the extra parameter 1. 
- __iWidgetCommand::SetExtra2__(_const Var&_ aVar) -> _void_: Set the extra parameter 2. 
- __iWidgetCommand::GetExtra2__() -> _const Var&_: Get the extra parameter 2. 

## enum ni::eWidgetSystemTimer
Widget system timers. 

### Values:
- __eWidgetSystemTimer_First__ = __eInvalidHandle+1__: First system timer id. 
- __eWidgetSystemTimer_Hover__ = __eWidgetSystemTimer_First+0__: Hover system timer. 
- __eWidgetSystemTimer_NCHover__ = __eWidgetSystemTimer_First+1__: Non-client area hover system timer. 
- __eWidgetSystemTimer_LeftDoubleClick__ = __eWidgetSystemTimer_First+2__: Left doubleclick timer. 
- __eWidgetSystemTimer_RightDoubleClick__ = __eWidgetSystemTimer_First+3__: Right doubleclick timer. 

## interface ni::iWidget
Widget interface. 

### Parents:
- iMessageHandler

### Methods:
- __iWidget::Destroy__() -> _void_: Destroy the widget and it's children. 
- __iWidget::GetGraphics__() -> _iGraphics\*_: Get the widget's Graphics object. 
- __iWidget::GetGraphicsContext__() -> _iGraphicsContext\*_: Get the widget's Graphics Context. 
- __iWidget::GetUIContext__() -> _iUIContext\*_: Get the widget's UI context. 
- __iWidget::GetClassName__() -> _iHString\*_: Get the widget's class. 
- __iWidget::SetID__(_iHString\*_ ahspID) -> _void_: Set the widget's ID. 
- __iWidget::GetID__() -> _iHString\*_: Get the widget's ID. 
- __iWidget::SetStyle__(_tU32_ anStyle) -> _tBool_: Set the widget's style. 
- __iWidget::GetStyle__() -> _tU32_: Get the widget's style. 
- __iWidget::SetParent__(_iWidget\*_ apParent) -> _void_: Set the parent widget. 
- __iWidget::GetParent__() -> _iWidget\*_: Get the parent widget. 
- __iWidget::SetZOrder__(_eWidgetZOrder_ aZOrder) -> _void_: Set the widget's ZOrder. \see eWidgetZOrder 
- __iWidget::GetZOrder__() -> _eWidgetZOrder_: Get the widget's ZOrder. 
- __iWidget::SetZOrderAbove__(_iWidget\*_ apWidget) -> _void_: Place the widget above (on top of) the specified sibling widget in the ZOrder. 
- __iWidget::GetDrawOrder__() -> _tU32_: Get the drawing order. 
- __iWidget::SetAutoLayout__(_tWidgetAutoLayoutFlags_ aFlags) -> _void_: Set if the widget's auto layout flags. 
- __iWidget::GetAutoLayout__() -> _tWidgetAutoLayoutFlags_: Get if the widget's auto layout flags. 
- __iWidget::ComputeAutoLayout__(_tWidgetAutoLayoutFlags_ aFlags) -> _void_: Computer the widget children's auto layout. 
- __iWidget::SetPosition__(_const sVec2f&_ avPos) -> _void_: Set the widget's position. 
- __iWidget::GetPosition__() -> _sVec2f_: Get the widget's position. 
- __iWidget::SetSize__(_const sVec2f&_ avSize) -> _void_: Set the widget's size. 
- __iWidget::GetSize__() -> _sVec2f_: Get the widget's size. 
- __iWidget::SetMinimumSize__(_sVec2f_ avMinSize) -> _void_: Set the widget's minimum size. 
- __iWidget::GetMinimumSize__() -> _sVec2f_: Get the widget's minimum size. 
- __iWidget::SetMaximumSize__(_sVec2f_ avMaxSize) -> _void_: Set the widget's maximum size. 
- __iWidget::GetMaximumSize__() -> _sVec2f_: Get the widget's maximum size. 
- __iWidget::SetRect__(_const sRectf&_ aRect) -> _void_: Set the widget's rectangle. 
- __iWidget::GetRect__() -> _sRectf_: Get the widget's rectangle. 
- __iWidget::GetWidgetRect__() -> _sRectf_: Get the widget rectangle. Relative to it's own top-left corner. 
- __iWidget::GetDockFillRect__() -> _sRectf_: Get the widget's dock fill rectangle. 
- __iWidget::SetClientPosition__(_const sVec2f&_ avPos) -> _void_: Set the widget's client position. 
- __iWidget::GetClientPosition__() -> _sVec2f_: Get the widget's client position. 
- __iWidget::SetClientSize__(_const sVec2f&_ avSize) -> _void_: Set the widget's client size. 
- __iWidget::GetClientSize__() -> _sVec2f_: Get the widget's client size. 
- __iWidget::SetClientRect__(_const sRectf&_ aRect) -> _void_: Set the widget's client rectangle. 
- __iWidget::GetClientRect__() -> _sRectf_: Get the widget's client rectangle. 
- __iWidget::ComputeFitRect__(_const sRectf&_ aRect) -> _sRectf_: Compute a rectangle that fits around the specified client rectangle. 
- __iWidget::SetFitRect__(_const sRectf&_ aRect) -> _void_: Set a rectangle that fits around the specified client rectangle. 
- __iWidget::SetFitSize__(_const sVec2f_ avSize) -> _void_: Set a rectangle that fits around the specified client size. 
- __iWidget::SetAbsolutePosition__(_const sVec2f&_ avPos) -> _void_: Set the widget's absolute position. 
- __iWidget::GetAbsolutePosition__() -> _sVec2f_: Get the widget's absolute position. 
- __iWidget::SetAbsoluteRect__(_const sRectf&_ aRect) -> _void_: Set the widget's absolute rectangle. 
- __iWidget::GetAbsoluteRect__() -> _sRectf_: Get the widget's absolute rectangle. 
- __iWidget::GetClippedRect__() -> _sRectf_: Get the widget's rect clipped to the parent client rectangle. 
- __iWidget::GetAbsoluteClippedRect__() -> _sRectf_: Get the widget's absolute rect clipped to the parent client rectangle. 
- __iWidget::GetClippedClientRect__() -> _sRectf_: Get the widget's client rect clipped to the parent client rectangle. 
- __iWidget::GetAbsoluteClippedClientRect__() -> _sRectf_: Get the widget's absolute client rect clipped to the parent client rectangle. 
- __iWidget::SetRelativePosition__(_const sVec2f&_ avPos) -> _void_: Set the widget's relative position. 
- __iWidget::GetRelativePosition__() -> _sVec2f_: Get the widget's relative position. 
- __iWidget::SetRelativeSize__(_const sVec2f&_ avSize) -> _void_: Set the widget's relative size. 
- __iWidget::GetRelativeSize__() -> _sVec2f_: Get the widget's relative size. 
- __iWidget::SetRelativeRect__(_const sRectf&_ aRect) -> _void_: Set the widget's relative rectangle. 
- __iWidget::GetRelativeRect__() -> _sRectf_: Get the widget's relative rectangle. 
- __iWidget::SetPadding__(_const sVec4f&_ aRect) -> _void_: Set the padding size. 
- __iWidget::GetPadding__() -> _sVec4f_: Get the padding size. 
- __iWidget::GetHasPadding__() -> _tBool_: Get whether a padding is specified (non-zero). 
- __iWidget::SetMargin__(_const sVec4f&_ aRect) -> _void_: Set the margin rectangle. 
- __iWidget::GetMargin__() -> _sVec4f_: Get the margin rectangle. 
- __iWidget::GetHasMargin__() -> _tBool_: Get whether a margin is specified (non-zero). 
- __iWidget::SetFocus__() -> _tBool_: Ask to get the input focus. 
- __iWidget::MoveFocus__(_tBool_ abToPrevious) -> _tBool_: Move the focus to the previous or next widget. 
- __iWidget::SetCapture__(_tBool_ abEnable) -> _void_: Set the capture of the input. 
- __iWidget::GetCapture__() -> _tBool_: Get the capture of the input state. 
- __iWidget::SetExclusive__(_tBool_ abEnable) -> _void_: Set exclusive. 
- __iWidget::GetExclusive__() -> _tBool_: Get the exclusive state. 
- __iWidget::SetInputSubmitFlags__(_tU32_ aSubmitFlags) -> _void_: Set the input submit flags. \see ni::eUIInputSubmitFlags 
- __iWidget::GetInputSubmitFlags__() -> _tU32_: Get the input submit flags. \see ni::eUIInputSubmitFlags 
- __iWidget::SetVisible__(_tBool_ abVisible) -> _void_: Set the widget visibility status. 
- __iWidget::GetVisible__() -> _tBool_: Get the widget visibility status. 
- __iWidget::SetEnabled__(_tBool_ abEnabled) -> _void_: Set the widget enabled status. 
- __iWidget::GetEnabled__() -> _tBool_: Get the widget enabled status. 
- __iWidget::SetIgnoreInput__(_tBool_ abIgnoreInput) -> _void_: Set the ignore input status. 
- __iWidget::GetIgnoreInput__() -> _tBool_: Get the ignore input status. 
- __iWidget::SetStatus__(_tBool_ abVisible, _tBool_ abEnabled, _tBool_ abIgnoreInput) -> _void_: Set all the status. 
- __iWidget::SetHideChildren__(_tBool_ abHideChildren) -> _void_: Set whether all client children of the widget are hidden. 
- __iWidget::GetHideChildren__() -> _tBool_: Get whether all client children of the widget are hidden. 
- __iWidget::GetIsMouseOver__() -> _tBool_: Get whether the mouse is over this widget's client area. 
- __iWidget::GetIsPressed__() -> _tBool_: Get whether the main mouse button is pressed while the mouse is over the widget's client area. 
- __iWidget::GetIsNcMouseOver__() -> _tBool_: Get whether the mouse is over this widget's non-client area. 
- __iWidget::GetIsNcPressed__() -> _tBool_: Get whether the main mouse button is pressed while the mouse is over the widget's non-client area. 
- __iWidget::GetHasFocus__() -> _tBool_: Get whether the widget has input (keyboard) focus. 
- __iWidget::GetDraggingSource__() -> _tBool_: Get whether the widget is the current draggin source. 
- __iWidget::GetDragging__() -> _tBool_: Get whether something is currently being dragged from this widget. 
- __iWidget::Redraw__() -> _void_: Force redrawing of the widget's content. 
- __iWidget::SetTimer__(_tU32_ anID, _tF32_ afTime) -> _void_: Set a timer. 
- __iWidget::GetTimer__(_tU32_ anID) -> _tF32_: Get a timer. 
- __iWidget::AddSink__(_iWidgetSink\*_ apSink) -> _tBool_: Add a widget sink as first sink called. 
- __iWidget::AddPostSink__(_iWidgetSink\*_ apSink) -> _tBool_: Add a widget sink as last sink called. 
- __iWidget::AddClassSink__(_const achar\*_ aaszClassName) -> _iWidgetSink\*_: Add a new instance of a widget sink as first sink called. 
- __iWidget::AddClassPostSink__(_const achar\*_ aaszClassName) -> _iWidgetSink\*_: Add a new instance of a widget sink as last sink called. 
- __iWidget::RemoveSink__(_iWidgetSink\*_ apSink) -> _void_: Remove a widget sink. 
- __iWidget::InvalidateChildren__() -> _void_: Invalidate all children. 
- __iWidget::GetNumChildren__() -> _tU32_: Get the number of child widgets. 
- __iWidget::GetChildIndex__(_iWidget\*_ apWidget) -> _tU32_: Get the index of the specified widget, if not a child widget return eInvalidHandle. 
- __iWidget::GetChildFromIndex__(_tU32_ anIndex) -> _iWidget\*_: Get the child widget at the specified index. 
- __iWidget::GetChildFromID__(_iHString\*_ ahspID) -> _iWidget\*_: Get the child widget with the specified ID. 
- __iWidget::GetChildFromDrawOrder__(_tU32_ anDrawOrder) -> _iWidget\*_: Get the child widget with the specified draw order. 
- __iWidget::FindWidget__(_iHString\*_ ahspID) -> _iWidget\*_: Find the first widget with the specified ID. 
- __iWidget::FindWidgetByPos__(_const sVec2f&_ avPos) -> _iWidget\*_: Find the top widget that intersects the specified absolute position. 
- __iWidget::HasChild__(_const iWidget\*_ apW, _tBool_ abRecursive) -> _tBool_: Check whether the specified widget is a child of this widget. 
- __iWidget::HasParent__(_const iWidget\*_ apW) -> _tBool_: Walks up the parent to check if the specified widget is one of the parent of this widget. 
- __iWidget::SetText__(_iHString\*_ ahspText) -> _void_: Set the widget's text. 
- __iWidget::GetText__() -> _iHString\*_: Get the widget's title. 
- __iWidget::GetLocalizedText__() -> _iHString\*_: Get the localized text. 
- __iWidget::SetHoverText__(_iHString\*_ ahspText) -> _void_: Set the widget's hovering text. 
- __iWidget::GetHoverText__() -> _iHString\*_: Get the widget's hovering text. 
- __iWidget::CreateDefaultHoverWidget__(_ni::iHString\*_ ahspHoverText) -> _ni::iWidget\*_: Create a default hover widget (Text only). 
- __iWidget::ShowHoverWidget__(_ni::iWidget\*_ apWidget, _const sVec2f&_ avAbsPos) -> _tBool_: Show a hover widget. 
- __iWidget::ResetHoverWidget__(_tBool_ abRestart) -> _void_: Reset the hover widget. 
- __iWidget::GetHoverWidget__() -> _ni::iWidget\*_: Get the currently displayed hover widget. 
- __iWidget::SetFont__(_iFont\*_ apFont) -> _tBool_: Set the widget's font. 
- __iWidget::GetFont__() -> _iFont\*_: Get the widget's font. 
- __iWidget::SetDockStyle__(_eWidgetDockStyle_ aStyle) -> _tBool_: Set the widget's dock style. 
- __iWidget::GetDockStyle__() -> _eWidgetDockStyle_: Get the widget's dock style. 
- __iWidget::SetSkin__(_iHString\*_ ahspSkin) -> _void_: Set the widget's skin. 
- __iWidget::GetSkin__() -> _iHString\*_: Get the widget's skin. 
- __iWidget::SetSkinClass__(_iHString\*_ ahspSkinClass) -> _void_: Set the widget's skin classs. 
- __iWidget::GetSkinClass__() -> _iHString\*_: Get the widget's skin class. 
- __iWidget::SetLocale__(_iHString\*_ ahspLocale) -> _void_: Set the widget's locale. 
- __iWidget::GetLocale__() -> _iHString\*_: Get the widget's locale. 
- __iWidget::GetActiveLocale__() -> _iHString\*_: Get the locale actually used by the widget. 
- __iWidget::FindSkinFont__(_iHString\*_ ahspSkinClass, _iHString\*_ ahspState, _iHString\*_ ahspName) -> _iFont\*_: Find the font of the specified item in the widget's skin. 
- __iWidget::FindSkinCursor__(_iHString\*_ ahspSkinClass, _iHString\*_ ahspState, _iHString\*_ ahspName) -> _iOverlay\*_: Find the cursor of the specified item in the widget's skin. 
- __iWidget::FindSkinElement__(_iHString\*_ ahspSkinClass, _iHString\*_ ahspState, _iHString\*_ ahspName) -> _iOverlay\*_: Find the element of the specified item in the widget's skin. 
- __iWidget::FindSkinColor__(_const sColor4f&_ aDefault, _iHString\*_ ahspSkinClass, _iHString\*_ ahspState, _iHString\*_ ahspName) -> _sColor4f_: Find the color of the specified item in the widget's skin. 
- __iWidget::FindLocalized__(_iHString\*_ ahspText) -> _iHString\*_: Find a localized text. 
- __iWidget::SetContextMenu__(_iWidget\*_ apMenu) -> _tBool_: Set the widget's context menu. \see ni::eUIMessage::eUIMessage_ContextMenu 
- __iWidget::GetContextMenu__() -> _iWidget\*_: Get the widget's context menu. 
- __iWidget::SendMessage__(_tU32_ anMsg, _const Var&_ avarA, _const Var&_ avarB) -> _tBool_: Send a message to this widget. 
- __iWidget::SendCommand__(_iWidget\*_ apDest, _tU32_ anCommand, _const Var&_ avarExtra1, _const Var&_ avarExtra2) -> _tBool_: Send a command to the specified widget. 
- __iWidget::BroadcastMessage__(_tU32_ anMsg, _const Var&_ avarA, _const Var&_ avarB) -> _tBool_: Send a message to this widget and its children recursivly. 
- __iWidget::SetCanvas__(_iCanvas\*_ apCanvas) -> _void_: Set the VG canvas of the widget. 
- __iWidget::GetCanvas__() -> _iCanvas\*_: Get the VG canvas of the widget. 
- __iWidget::SerializeLayout__(_iDataTable\*_ apDT, _tWidgetSerializeFlags_ anFlags) -> _tBool_: Serialize the layout of this widget. 
- __iWidget::SerializeChildren__(_iDataTable\*_ apDT, _tWidgetSerializeFlags_ anFlags) -> _tBool_: Serialize the children widget. 
- __iWidget::ApplyDockStyle__(_eWidgetDockStyle_ aStyle) -> _tBool_: Set a dock style, and then restore the previous dock style. 
- __iWidget::Place__(_const sRectf&_ aRect, _eWidgetDockStyle_ aStyle, _const sVec4f&_ avMargin) -> _tBool_: Place the widget using the specified dock style, margin and rectangle. 
- __iWidget::SnapInside__(_iWidget\*_ apContainer, _tF32_ afSnapMargin) -> _tBool_: Makes sure the widget is within the bounds of the specified 'container' widget. 
- __iWidget::PopAt__(_iWidget\*_ apContainer, _const sVec2f&_ avAbsPos, _tF32_ afSnapMargin) -> _tBool_: Move the widget at the specified position making sure it is within the bounds of the specified 'container' widget. 
- __iWidget::Layout__(_tBool_ abChildren) -> _void_: Compute the Widget's layout. 
- __iWidget::SetFingerCapture__(_tU32_ anFinger, _tBool_ abEnable) -> _void_: Set the capture of a finger's input. 
- __iWidget::GetFingerCapture__(_tU32_ anFinger) -> _tBool_: Get the capture of a finger's input. 

## enum ni::eWidgetStyle
Widget style. 

### Values:
- __eWidgetStyle_NCRelative__ = __niBit(0)__
- __eWidgetStyle_Free__ = __niBit(1)__: Free widget. 
- __eWidgetStyle_HoldFocus__ = __niBit(2)__: The widget will receive input focus. 
- __eWidgetStyle_OverFocus__ = __niBit(3)__: The widget will receive input focus when the cursor is above it. 
- __eWidgetStyle_NoClip__ = __niBit(4)__: The widget wont be clipped by it's parent. 
- __eWidgetStyle_NoClick__ = __niBit(5)__: No click and double click messages will be generated. 
- __eWidgetStyle_NotifyParent__ = __niBit(6)__: The parent widget is notified through the ParentNotify message when a message is sent to this widget. 
- __eWidgetStyle_FocusActivate__ = __niBit(7)__: Activate the widget just before receiving focus. 
- __eWidgetStyle_DontSerialize__ = __niBit(8)__: Don't serialize. 
- __eWidgetStyle_ItemOwned__ = __niBit(9)__: The item the widget is attached to owns it. This is to instruct items (such as tree nodes or list entry) to destroy/invalidate the widget when it isnt used anymore. 
- __eWidgetStyle_DragSource__ = __niBit(10)__: The the widget is a dragging source. 
- __eWidgetStyle_DragDestination__ = __niBit(11)__: The widget is a dragging destination. 
- __eWidgetStyle_Temp__ = __niBit(12)__: The widget is temporary, as for example the hover labels. 
- __eWidgetStyle_NoMoveFocus__ = __niBit(13)__: Focus won't be set on the widget as a response to the MoveFocus message. 
- __eWidgetStyle_NoAutoRedraw__ = __niBit(14)__: Dont redraw the widget automatically on input events. 
- __eWidgetStyle_MoveFocusGroup__ = __niBit(15)__: Widget is a "move focus group". 
- __eWidgetStyle_MaxBit__ = __16__: Max bit, user styles should use the bits above this. 

## enum ni::eWidgetButtonStyle


### Values:
- __eWidgetButtonStyle_OnOff__ = __niBit(eWidgetStyle_MaxBit+0)__: Toggle button. 
- __eWidgetButtonStyle_CheckBox__ = __niBit(eWidgetStyle_MaxBit+1)__: Check box button. 
- __eWidgetButtonStyle_RadioButton__ = __niBit(eWidgetStyle_MaxBit+2)__: Radio button. 
- __eWidgetButtonStyle_TabButton__ = __niBit(eWidgetStyle_MaxBit+3)__: Tab button. 
- __eWidgetButtonStyle_Select__ = __niBit(eWidgetStyle_MaxBit+4)__: Draw the button in a selected state when checked. 
- __eWidgetButtonStyle_NoText__ = __niBit(eWidgetStyle_MaxBit+5)__: Dont draw the text. 
- __eWidgetButtonStyle_Sticky__ = __niBit(eWidgetStyle_MaxBit+6)__: The button will stay pressed and 'click' once it has been pressed, even if the mouse moves out of it. 
- __eWidgetButtonStyle_NoFrame__ = __niBit(eWidgetStyle_MaxBit+7)__: Dont draw the button frame. 
- __eWidgetButtonStyle_IconFit__ = __niBit(eWidgetStyle_MaxBit+8)__: Set the icon size automatically to fit into the button. 
- __eWidgetButtonStyle_IconStretch__ = __niBit(eWidgetStyle_MaxBit+9)__: Set the icon size automatically to fill the button. 
- __eWidgetButtonStyle_IconLeft__ = __0__: The icon position is on the left. The text position is on the right. 
- __eWidgetButtonStyle_IconRight__ = __niBit(eWidgetStyle_MaxBit+10)__: The icon position is on the right. The text position is on the left. 
- __eWidgetButtonStyle_IconTop__ = __niBit(eWidgetStyle_MaxBit+11)__: The icon position is on the top. The text position is in the bottom. 
- __eWidgetButtonStyle_IconBottom__ = __niBit(eWidgetStyle_MaxBit+12)__: The icon position is in the bottom. The text position is on the top. 
- __eWidgetButtonStyle_IconCenter__ = __niBit(eWidgetStyle_MaxBit+13)__: The icon position is in the center. The text position is over the icon. 
- __eWidgetButtonStyle_TextLeft__ = __niBit(eWidgetStyle_MaxBit+14)__: The text is left/top aligned. 
- __eWidgetButtonStyle_TextRight__ = __niBit(eWidgetStyle_MaxBit+15)__: The text is right/bottom aligned. 
- __eWidgetButtonStyle_TextCenter__ = __0__: The text is center aligned. 
- __eWidgetButtonStyle_BitmapButton__ = __eWidgetButtonStyle_IconCenter__: Bitmap button. Text is drawn over the icon. 
- __eWidgetButtonStyle_IconButton__ = __eWidgetButtonStyle_IconTop__: Icon button, same as bitmap button excepted that the text is drawn below the icon. 

## enum ni::eWidgetButtonCmd
Button notification messages. 

### Values:
- __eWidgetButtonCmd_Clicked__ = __0__: The button has been clicked. 
- __eWidgetButtonCmd_Pushed__ = __1__: The button has been pushed. 
- __eWidgetButtonCmd_UnPushed__ = __2__: The button has been unpushed. 
- __eWidgetButtonCmd_Checked__ = __3__: The button has been checked. 
- __eWidgetButtonCmd_UnChecked__ = __4__: The button has been unchecked. 

## interface ni::iWidgetButton
Button widget interface. 

### Parents:
- iUnknown

### Methods:
- __iWidgetButton::SetIcon__(_iOverlay\*_ apIcon) -> _void_: Set the button's icon 
- __iWidgetButton::GetIcon__() -> _iOverlay\*_: Get the button's icon 
- __iWidgetButton::SetIconPressed__(_iOverlay\*_ apIcon) -> _void_: Set the button's icon in pressed state. 
- __iWidgetButton::GetIconPressed__() -> _iOverlay\*_: Get the button's icon in pressed state. 
- __iWidgetButton::SetIconHover__(_iOverlay\*_ apIcon) -> _void_: Set the button's icon in hover state. 
- __iWidgetButton::GetIconHover__() -> _iOverlay\*_: Get the button's icon in hover state. 
- __iWidgetButton::SetIconSize__(_const sVec2f&_ avSize) -> _void_: Set the button's icon size. 
- __iWidgetButton::GetIconSize__() -> _sVec2f_: Get the button's icon size. 
- __iWidgetButton::SetCheck__(_tBool_ abCkecked) -> _void_: Set the button check status 
- __iWidgetButton::GetCheck__() -> _tBool_: Get the button check status 
- __iWidgetButton::SetGroupID__(_iHString\*_ aVal) -> _tBool_: Set the button's group id. 
- __iWidgetButton::GetGroupID__() -> _iHString\*_: Get the button's group id. 
- __iWidgetButton::SetIconMargin__(_const sVec4f&_ avMargin) -> _void_: Set the icon margin. 
- __iWidgetButton::GetIconMargin__() -> _sVec4f_: Get the icon margin. 
- __iWidgetButton::GetIconDrawRect__() -> _sRectf_: Get the icon's drawing rectangle, client rectangle relative. 
- __iWidgetButton::SetDrawFrameFlags__(_tRectFrameFlags_ aFlags) -> _void_: Set the draw frame flags. 
- __iWidgetButton::GetDrawFrameFlags__() -> _tRectFrameFlags_: Get the draw frame flags. 

## enum ni::eWidgetButtonStyle


### Values:
- __eWidgetButtonStyle_OnOff__ = __niBit(eWidgetStyle_MaxBit+0)__: Toggle button. 
- __eWidgetButtonStyle_CheckBox__ = __niBit(eWidgetStyle_MaxBit+1)__: Check box button. 
- __eWidgetButtonStyle_RadioButton__ = __niBit(eWidgetStyle_MaxBit+2)__: Radio button. 
- __eWidgetButtonStyle_TabButton__ = __niBit(eWidgetStyle_MaxBit+3)__: Tab button. 
- __eWidgetButtonStyle_Select__ = __niBit(eWidgetStyle_MaxBit+4)__: Draw the button in a selected state when checked. 
- __eWidgetButtonStyle_NoText__ = __niBit(eWidgetStyle_MaxBit+5)__: Dont draw the text. 
- __eWidgetButtonStyle_Sticky__ = __niBit(eWidgetStyle_MaxBit+6)__: The button will stay pressed and 'click' once it has been pressed, even if the mouse moves out of it. 
- __eWidgetButtonStyle_NoFrame__ = __niBit(eWidgetStyle_MaxBit+7)__: Dont draw the button frame. 
- __eWidgetButtonStyle_IconFit__ = __niBit(eWidgetStyle_MaxBit+8)__: Set the icon size automatically to fit into the button. 
- __eWidgetButtonStyle_IconStretch__ = __niBit(eWidgetStyle_MaxBit+9)__: Set the icon size automatically to fill the button. 
- __eWidgetButtonStyle_IconLeft__ = __0__: The icon position is on the left. The text position is on the right. 
- __eWidgetButtonStyle_IconRight__ = __niBit(eWidgetStyle_MaxBit+10)__: The icon position is on the right. The text position is on the left. 
- __eWidgetButtonStyle_IconTop__ = __niBit(eWidgetStyle_MaxBit+11)__: The icon position is on the top. The text position is in the bottom. 
- __eWidgetButtonStyle_IconBottom__ = __niBit(eWidgetStyle_MaxBit+12)__: The icon position is in the bottom. The text position is on the top. 
- __eWidgetButtonStyle_IconCenter__ = __niBit(eWidgetStyle_MaxBit+13)__: The icon position is in the center. The text position is over the icon. 
- __eWidgetButtonStyle_TextLeft__ = __niBit(eWidgetStyle_MaxBit+14)__: The text is left/top aligned. 
- __eWidgetButtonStyle_TextRight__ = __niBit(eWidgetStyle_MaxBit+15)__: The text is right/bottom aligned. 
- __eWidgetButtonStyle_TextCenter__ = __0__: The text is center aligned. 
- __eWidgetButtonStyle_BitmapButton__ = __eWidgetButtonStyle_IconCenter__: Bitmap button. Text is drawn over the icon. 
- __eWidgetButtonStyle_IconButton__ = __eWidgetButtonStyle_IconTop__: Icon button, same as bitmap button excepted that the text is drawn below the icon. 

## enum ni::eWidgetCanvasStyle
Canvas widget styles 

### Values:
- __eWidgetCanvasStyle_ScrollH__ = __niBit(eWidgetStyle_MaxBit+0)__: A horizontal scroll bar will be shown if the canvas client size is bigger than the canvas's rectangle. 
- __eWidgetCanvasStyle_ScrollV__ = __niBit(eWidgetStyle_MaxBit+1)__: A vertical scroll bar will be shown if the canvas client size is bigger than the canvas's rectangle. 
- __eWidgetCanvasStyle_HideScrollH__ = __niBit(eWidgetStyle_MaxBit+2)__: The horizontal scroll bar will never be set visible. 
- __eWidgetCanvasStyle_HideScrollV__ = __niBit(eWidgetStyle_MaxBit+3)__: The vertical scroll bar will never be set visible. 

## interface ni::iWidgetCanvas
Canvas widget interface. 

### Parents:
- iUnknown

### Methods:
- __iWidgetCanvas::GetScrollV__() -> _iWidget\*_: Get the vertical scroll bar. 
- __iWidgetCanvas::SetScrollStepV__(_tF32_ afV) -> _void_: Set the scroll bar vertical step size. 
- __iWidgetCanvas::GetScrollStepV__() -> _tF32_: Get the scroll bar vertical step size. 
- __iWidgetCanvas::SetScrollMarginV__(_tF32_ afV) -> _void_: Set the scroll bar vertical range margin. 
- __iWidgetCanvas::GetScrollMarginV__() -> _tF32_: Get the scroll bar vertical range margin. 
- __iWidgetCanvas::GetScrollH__() -> _iWidget\*_: Get the horizontal scroll bar. 
- __iWidgetCanvas::SetScrollStepH__(_tF32_ afV) -> _void_: Set the scroll bar horizontal step size. 
- __iWidgetCanvas::GetScrollStepH__() -> _tF32_: Get the scroll bar horizontal step size. 
- __iWidgetCanvas::SetScrollMarginH__(_tF32_ afV) -> _void_: Set the scroll bar horizontal range margin. 
- __iWidgetCanvas::GetScrollMarginH__() -> _tF32_: Get the scroll bar horizontal range margin. 

## enum ni::eWidgetCanvasStyle
Canvas widget styles 

### Values:
- __eWidgetCanvasStyle_ScrollH__ = __niBit(eWidgetStyle_MaxBit+0)__: A horizontal scroll bar will be shown if the canvas client size is bigger than the canvas's rectangle. 
- __eWidgetCanvasStyle_ScrollV__ = __niBit(eWidgetStyle_MaxBit+1)__: A vertical scroll bar will be shown if the canvas client size is bigger than the canvas's rectangle. 
- __eWidgetCanvasStyle_HideScrollH__ = __niBit(eWidgetStyle_MaxBit+2)__: The horizontal scroll bar will never be set visible. 
- __eWidgetCanvasStyle_HideScrollV__ = __niBit(eWidgetStyle_MaxBit+3)__: The vertical scroll bar will never be set visible. 

## enum ni::eWidgetColorPickerCmd
Color picker notification messages. 

### Values:
- __eWidgetColorPickerCmd_ColorChanged__ = __0__: Sent when the color changed. 

## enum ni::eWidgetColorPickerStyle
Color picker style. 

### Values:
- __eWidgetColorPickerStyle_Brightness__ = __niBit(eWidgetStyle_MaxBit+0)__: Show the brightness control. 

## interface ni::iWidgetColorPicker
Widget ColorPicker viewer. 

### Parents:
- iUnknown

### Methods:
- __iWidgetColorPicker::SetHSV__(_const sColor3f&_ avHSV) -> _void_: Set the color picker's current color in HSV format. 
- __iWidgetColorPicker::GetHSV__() -> _sColor3f_: Get the color picker's current color in HSV format. 
- __iWidgetColorPicker::SetRGBA__(_const sColor4f&_ avRGBA) -> _void_: Set the color picker's current color in RGBA format. 
- __iWidgetColorPicker::GetRGBA__() -> _sColor4f_: Get the color picker's current color in RGBA format. 
- __iWidgetColorPicker::SetRGB__(_const sColor3f&_ avRGB) -> _void_: Set the color picker's current color in RGB format. 
- __iWidgetColorPicker::GetRGB__() -> _sColor3f_: Get the color picker's current color in RGB format. 
- __iWidgetColorPicker::SetAlpha__(_tF32_ afAlpha) -> _void_: Set the color picker's current color alpha. 
- __iWidgetColorPicker::GetAlpha__() -> _tF32_: Get the color picker's current color alpha. 
- __iWidgetColorPicker::SetBrightness__(_const tF32_ afBrightness) -> _void_: Set the color picker's current color brightness. 
- __iWidgetColorPicker::GetBrightness__() -> _tF32_: Get the color picker's current color brightness. 
- __iWidgetColorPicker::SetMaxBrightness__(_const tF32_ afMaxBrightness) -> _void_: Set the color picker's current color maximum brightness. 
- __iWidgetColorPicker::GetMaxBrightness__() -> _tF32_: Get the color picker's current color maximum brightness. 
- __iWidgetColorPicker::SetColorName__(_iHString\*_ ahspName) -> _tBool_: Set the color picker's current color from a color name. \see ni::eColor 
- __iWidgetColorPicker::GetColorName__() -> _const achar\*_: Get the color picker's current color as color name. \see ni::eColor 
- __iWidgetColorPicker::SetExpression__(_iHString\*_ ahspExpression) -> _tBool_: Set the color picker's current color from a mathematic expression. 
- __iWidgetColorPicker::GetExpression__() -> _iHString\*_: Get the color picker's current color as a mathematic expression. 

## enum ni::eWidgetColorPickerCmd
Color picker notification messages. 

### Values:
- __eWidgetColorPickerCmd_ColorChanged__ = __0__: Sent when the color changed. 

## enum ni::eWidgetComboBoxStyle
Combo box widget style. 

### Values:
- __eWidgetComboBoxStyle_DropDown__ = __niBit(eWidgetStyle_MaxBit+0)__: Drop down combo box, the text cant be edited. 
- __eWidgetComboBoxStyle_Multiselect__ = __niBit(eWidgetStyle_MaxBit+1)__: Allow to select multiple items in the combo box. 
- __eWidgetComboBoxStyle_ReadOnly__ = __niBit(eWidgetStyle_MaxBit+2)__: Set the combo box's edity box to be read only. 
- __eWidgetComboBoxStyle_NoDefaultListBox__ = __niBit(eWidgetStyle_MaxBit+3)__: No default list box is created, the next child added will be the dropped widget. 
- __eWidgetComboBoxStyle_ClickAddSelection__ = __niBit(eWidgetStyle_MaxBit+4)__: For defautl dropped list box, click down add selection, ctrl+click set selection. (This is the opposite of the default) 

## enum ni::eWidgetComboBoxCmd
Combo box widget notify messages. 

### Values:
- __eWidgetComboBoxCmd_SelectionChanged__ = __0__: The selection changed. 
- __eWidgetComboBoxCmd_Validated__ = __1__: The edit box has been validated. 
- __eWidgetComboBoxCmd_Modified__ = __2__: The edit box has been modified. 
- __eWidgetComboBoxCmd_DropShown__ = __3__: The drop is going to be shown. 
- __eWidgetComboBoxCmd_DropHidden__ = __4__: The drop is going to be hidden. 

## interface ni::iWidgetComboBox
Combo box widget interface. 

### Parents:
- iUnknown

### Methods:
- __iWidgetComboBox::SetNumLines__(_tU32_ anNum) -> _void_: Set the number of lines dropped. 
- __iWidgetComboBox::GetNumLines__() -> _tU32_: Get the number of lines dropped. 
- __iWidgetComboBox::SetDroppedWidget__(_iWidget\*_ apWidget) -> _tBool_: Set the 'dropped' widget. 
- __iWidgetComboBox::GetDroppedWidget__() -> _iWidget\*_: Get the 'dropped' widget. 

## enum ni::eWidgetComboBoxStyle
Combo box widget style. 

### Values:
- __eWidgetComboBoxStyle_DropDown__ = __niBit(eWidgetStyle_MaxBit+0)__: Drop down combo box, the text cant be edited. 
- __eWidgetComboBoxStyle_Multiselect__ = __niBit(eWidgetStyle_MaxBit+1)__: Allow to select multiple items in the combo box. 
- __eWidgetComboBoxStyle_ReadOnly__ = __niBit(eWidgetStyle_MaxBit+2)__: Set the combo box's edity box to be read only. 
- __eWidgetComboBoxStyle_NoDefaultListBox__ = __niBit(eWidgetStyle_MaxBit+3)__: No default list box is created, the next child added will be the dropped widget. 
- __eWidgetComboBoxStyle_ClickAddSelection__ = __niBit(eWidgetStyle_MaxBit+4)__: For defautl dropped list box, click down add selection, ctrl+click set selection. (This is the opposite of the default) 

## enum ni::eWidgetDockingManagerMessage
Docking manager messages 

### Values:
- __eWidgetDockingManagerMessage_BeginMove__ = __niMessageID('_','W','D','M','b')__: The widget is beginning to be moved/dragged. 
- __eWidgetDockingManagerMessage_EndMove__ = __niMessageID('_','W','D','M','e')__: The widget is finished to be moved/dragged. 
- __eWidgetDockingManagerMessage_Move__ = __niMessageID('_','W','D','N','m')__: The widget is moved. 

## interface ni::iWidgetDockable
Dockable widget interface. 

### Parents:
- iUnknown

### Remarks:
- This is the interface that widgets needs to implement to be dockable. 
- Dockable widgets needs to call their parent widget's docking manager to handle their docking. 

### Methods:
- __iWidgetDockable::GetDockName__() -> _const achar\*_: Get the dock's name. 
- __iWidgetDockable::GetIsDocked__() -> _tBool_: Get the docking status. 

## enum ni::eWidgetDockingManagerFlags
Docking manager flags. 

### Values:
- __eWidgetDockingManagerFlags_Navigator__ = __niBit(0)__: Show a navigator if the Navigator action is triggered. 
- __eWidgetDockingManagerFlags_HideTabIfOnePage__ = __niBit(1)__: Hide the tab name if only one page is in the tab widget. 
- __eWidgetDockingManagerFlags_DockLeft__ = __niBit(2)__: Docking on the left is allowed. 
- __eWidgetDockingManagerFlags_DockRight__ = __niBit(3)__: Docking on the right is allowed. 
- __eWidgetDockingManagerFlags_DockTop__ = __niBit(4)__: Docking on the top is allowed. 
- __eWidgetDockingManagerFlags_DockBottom__ = __niBit(5)__: Docking on the bottom is allowed. 
- __eWidgetDockingManagerFlags_DockHorizontal__ = __eWidgetDockingManagerFlags_DockLeft|eWidgetDockingManagerFlags_DockRight__: Horizontal docking. 
- __eWidgetDockingManagerFlags_DockVertical__ = __eWidgetDockingManagerFlags_DockTop|eWidgetDockingManagerFlags_DockBottom__: Vertical docking. 
- __eWidgetDockingManagerFlags_DockAll__ = __eWidgetDockingManagerFlags_DockHorizontal|eWidgetDockingManagerFlags_DockVertical__: All docking 
- __eWidgetDockingManagerFlags_Default__ = __eWidgetDockingManagerFlags_DockAll|eWidgetDockingManagerFlags_Navigator__: Default manager flags. 

## interface ni::iWidgetDockingManager
Widget docking manager. 

### Parents:
- iUnknown

### Remarks:
- The docking manager is a normal widget that implements iWidgetSink. 

### Methods:
- __iWidgetDockingManager::SetFlags__(_tWidgetDockingManagerFlags_ aFlags) -> _tBool_: Set the docking manager's flags. 
- __iWidgetDockingManager::GetFlags__() -> _tWidgetDockingManagerFlags_: Get the docking manager's flags. 
- __iWidgetDockingManager::GetDockAreaFromPageName__(_const achar\*_ aaszName) -> _tU32_: Get the first dock area that contains a tab page with the specified name. 
- __iWidgetDockingManager::GetDockAreaHovered__(_sVec2f_ avPos) -> _tU32_: Get the dock area that is hovered by the specified absolute cursor position. 
- __iWidgetDockingManager::DockWidget__(_tU32_ anDock, _iWidget\*_ apWidget) -> _tBool_: Dock the specified widget inside the specified dock area. 
- __iWidgetDockingManager::UndockWidget__(_iWidget\*_ apWidget) -> _tBool_: Undock the specified widget. 
- __iWidgetDockingManager::GetNumDockedWidgets__() -> _tU32_: Get the number of widgets docked. 
- __iWidgetDockingManager::GetDockedWidget__(_tU32_ anIndex) -> _iWidget\*_: Get the docked widget at the specified index. 
- __iWidgetDockingManager::GetNumDockAreas__() -> _tU32_: Get the number of dock area. 
- __iWidgetDockingManager::GetDockArea__(_tU32_ anIndex) -> _iWidget\*_: Get the dock area at the specified index. 
- __iWidgetDockingManager::SetDockAreaTabContextMenu__(_iWidget\*_ apMenu) -> _tBool_: Set the context menu of the dock areas tabs. 
- __iWidgetDockingManager::GetDockAreaTabContextMenu__() -> _iWidget\*_: Get the context menu of the dock areas tabs. 
- __iWidgetDockingManager::AddDockArea__(_tU32_ anParent, _tU32_ aPos, _sRectf_ aRect, _tBool_ abLocal) -> _tU32_: Add a new empty dock area. 
- __iWidgetDockingManager::ClearDockAreas__() -> _void_: Remove all dock areas. 
- __iWidgetDockingManager::CleanDockAreas__() -> _void_: Clean all invalid/empty dock areas. 

## enum ni::eWidgetDockingManagerMessage
Docking manager messages 

### Values:
- __eWidgetDockingManagerMessage_BeginMove__ = __niMessageID('_','W','D','M','b')__: The widget is beginning to be moved/dragged. 
- __eWidgetDockingManagerMessage_EndMove__ = __niMessageID('_','W','D','M','e')__: The widget is finished to be moved/dragged. 
- __eWidgetDockingManagerMessage_Move__ = __niMessageID('_','W','D','N','m')__: The widget is moved. 

## enum ni::eWidgetEditBoxStyle
Simple edit box styles. 

### Values:
- __eWidgetEditBoxStyle_MultiLine__ = __niBit(eWidgetStyle_MaxBit+1)__: Multi-line edit box. 
- __eWidgetEditBoxStyle_ReadOnly__ = __niBit(eWidgetStyle_MaxBit+2)__: Read-only edit box. 
- __eWidgetEditBoxStyle_AutoScroll__ = __niBit(eWidgetStyle_MaxBit+3)__: Auto scroll edit box. Scrolling made in function of the cursor's position. 
- __eWidgetEditBoxStyle_PasteValidate__ = __niBit(eWidgetStyle_MaxBit+4)__: Validate on paste. 
- __eWidgetEditBoxStyle_NoCursor__ = __niBit(eWidgetStyle_MaxBit+5)__: Dont draw the cursor. 
- __eWidgetEditBoxStyle_NoSelect__ = __niBit(eWidgetStyle_MaxBit+6)__: Dont allow selection. 
- __eWidgetEditBoxStyle_DontLoseSelection__ = __niBit(eWidgetStyle_MaxBit+7)__: Dont clear selection when lost focus. 
- __eWidgetEditBoxStyle_ValidateOnLostFocus__ = __niBit(eWidgetStyle_MaxBit+8)__: Validate when lost focus 
- __eWidgetEditBoxStyle_SelectAllOnSetFocus__ = __niBit(eWidgetStyle_MaxBit+9)__: Select all when gaining focus 
- __eWidgetEditBoxStyle_CanInsertTabs__ = __niBit(eWidgetStyle_MaxBit+10)__: Can insert tabs, but capture the MoveFocus message. 

## enum ni::eWidgetEditBoxCmd
Simple edit box notification messages. 

### Values:
- __eWidgetEditBoxCmd_Validated__ = __0__: Sent when the edit box has been validated. 
- __eWidgetEditBoxCmd_Modified__ = __1__: Sent when the edit box's text has been modified. 
- __eWidgetEditBoxCmd_LostFocus__ = __2__: Sent when the edit box has lost focus. 

## interface ni::iWidgetEditBox
Simple editbox widget interface. 

### Parents:
- iUnknown

### Methods:
- __iWidgetEditBox::AddText__(_const achar\*_ aaszText) -> _void_: Add the specified text at the end of the edit box. 
- __iWidgetEditBox::SetReplaceChar__(_tU32_ anChar) -> _void_: Set the replacement character for all text displayed. 
- __iWidgetEditBox::GetReplaceChar__() -> _tU32_: Get the replacement character for all text displayed. 
- __iWidgetEditBox::MoveCursorHome__(_tBool_ abLine) -> _void_: Move the cursor to the begining of the line or the text. 
- __iWidgetEditBox::MoveCursorEnd__(_tBool_ abLine) -> _void_: Move the cursor at the end of the line or the text. 
- __iWidgetEditBox::MoveCursor__(_const sVec2i&_ pos, _tBool_ abForceLogicalCol) -> _void_: Move the cursor to the specified position (line,column) 
- __iWidgetEditBox::MoveCursorLineDelta__(_tI32_ line) -> _void_: Move the current cursor line. 
- __iWidgetEditBox::MoveCursorColumnDelta__(_tI32_ line) -> _void_: Move the current cursor column. 
- __iWidgetEditBox::GetCursorPosition__() -> _sVec2i_: Get the cursor's position. 
- __iWidgetEditBox::GetCursorLine__() -> _tU32_: Get the cursor's current line. 
- __iWidgetEditBox::GetCursorColumn__() -> _tU32_: Get the cursor's current column. 
- __iWidgetEditBox::AutoScroll__() -> _void_: Scroll to the current cursor position. 
- __iWidgetEditBox::GetTextInRange__(_const sVec4i&_ aRange) -> _cString_: Get the text in the specified range, Vec4(startLine,startCol,endLine,endCol). 
- __iWidgetEditBox::GetAllTextRange__() -> _sVec4i_: Get the text range which includes the whole text. 
- __iWidgetEditBox::SetSelection__(_const sVec4i&_ aSelection) -> _void_: Set the selection to the specified range, Vec4(startLine,startCol,endLine,endCol) 
- __iWidgetEditBox::GetSelection__() -> _sVec4i_: Get the current selection range, Vec4(startLine,startCol,endLine,endCol). 

## enum ni::eWidgetEditBoxStyle
Simple edit box styles. 

### Values:
- __eWidgetEditBoxStyle_MultiLine__ = __niBit(eWidgetStyle_MaxBit+1)__: Multi-line edit box. 
- __eWidgetEditBoxStyle_ReadOnly__ = __niBit(eWidgetStyle_MaxBit+2)__: Read-only edit box. 
- __eWidgetEditBoxStyle_AutoScroll__ = __niBit(eWidgetStyle_MaxBit+3)__: Auto scroll edit box. Scrolling made in function of the cursor's position. 
- __eWidgetEditBoxStyle_PasteValidate__ = __niBit(eWidgetStyle_MaxBit+4)__: Validate on paste. 
- __eWidgetEditBoxStyle_NoCursor__ = __niBit(eWidgetStyle_MaxBit+5)__: Dont draw the cursor. 
- __eWidgetEditBoxStyle_NoSelect__ = __niBit(eWidgetStyle_MaxBit+6)__: Dont allow selection. 
- __eWidgetEditBoxStyle_DontLoseSelection__ = __niBit(eWidgetStyle_MaxBit+7)__: Dont clear selection when lost focus. 
- __eWidgetEditBoxStyle_ValidateOnLostFocus__ = __niBit(eWidgetStyle_MaxBit+8)__: Validate when lost focus 
- __eWidgetEditBoxStyle_SelectAllOnSetFocus__ = __niBit(eWidgetStyle_MaxBit+9)__: Select all when gaining focus 
- __eWidgetEditBoxStyle_CanInsertTabs__ = __niBit(eWidgetStyle_MaxBit+10)__: Can insert tabs, but capture the MoveFocus message. 

## enum ni::eWidgetFormStyle
Widget form flags. 

### Values:
- __eWidgetFormStyle_Dock__ = __niBit(eWidgetStyle_MaxBit+0)__: Allow the form to dock by a parent docking manager. 
- __eWidgetFormStyle_Move__ = __niBit(eWidgetStyle_MaxBit+1)__: Allow the form to be moved. 
- __eWidgetFormStyle_ResizeTopLeftCorner__ = __niBit(eWidgetStyle_MaxBit+2)__: The form can be resized using the top left corner. 
- __eWidgetFormStyle_ResizeTopRightCorner__ = __niBit(eWidgetStyle_MaxBit+3)__: The form can be resized using the top right corner. 
- __eWidgetFormStyle_ResizeBottomLeftCorner__ = __niBit(eWidgetStyle_MaxBit+4)__: The form can be resized using the bottom left corner. 
- __eWidgetFormStyle_ResizeBottomRightCorner__ = __niBit(eWidgetStyle_MaxBit+5)__: The form can be resized using the bottom right corner. 
- __eWidgetFormStyle_ResizeAnyCorner__ = __eWidgetFormStyle_ResizeTopLeftCorner|eWidgetFormStyle_ResizeTopRightCorner|eWidgetFormStyle_ResizeBottomLeftCorner|eWidgetFormStyle_ResizeBottomRightCorner__: The form can be resized from any corner. 
- __eWidgetFormStyle_ResizeLeftEdge__ = __niBit(eWidgetStyle_MaxBit+6)__: The form can be resized using the left edge. 
- __eWidgetFormStyle_ResizeRightEdge__ = __niBit(eWidgetStyle_MaxBit+7)__: The form can be resized using the right edge. 
- __eWidgetFormStyle_ResizeTopEdge__ = __niBit(eWidgetStyle_MaxBit+8)__: The form can be resized using the top edge. 
- __eWidgetFormStyle_ResizeBottomEdge__ = __niBit(eWidgetStyle_MaxBit+9)__: The form can be resized using the bottom edge. 
- __eWidgetFormStyle_ResizeAnyEdge__ = __eWidgetFormStyle_ResizeLeftEdge|eWidgetFormStyle_ResizeRightEdge|eWidgetFormStyle_ResizeTopEdge|eWidgetFormStyle_ResizeBottomEdge__: The form can be resized from any edge. 
- __eWidgetFormStyle_ResizeAny__ = __eWidgetFormStyle_ResizeAnyCorner|eWidgetFormStyle_ResizeAnyEdge__: The form can be resized using any of the edges and corners. 
- __eWidgetFormStyle_CloseButton__ = __niBit(eWidgetStyle_MaxBit+10)__: The form has a close button. (ID_Close) 
- __eWidgetFormStyle_FormManagerButtons__ = __niBit(eWidgetStyle_MaxBit+11)__: The form has the form manager buttons, these are the minimize, maximize and restore buttons. (ID_Minimize, ID_Maximize, ID_Restore) 
- __eWidgetFormStyle_DockNoInputModifier__ = __niBit(eWidgetStyle_MaxBit+12)__: The docking overlays are always displayed when moving. The default behavior is that the 'Control' input modifier needs to be pressed while moving the form to display the docking overlays. 
- __eWidgetFormStyle_Default__ = __eWidgetFormStyle_Dock|eWidgetFormStyle_ResizeAny|eWidgetFormStyle_Move__: Default form flags. 
- __eWidgetFormStyle_DefaultButtons__ = __eWidgetFormStyle_Dock|eWidgetFormStyle_ResizeAny|eWidgetFormStyle_Move|eWidgetFormStyle_CloseButton|eWidgetFormStyle_FormManagerButtons__: Default form flags with close button. 
- __eWidgetFormStyle_DefaultManagerButtons__ = __eWidgetFormStyle_Dock|eWidgetFormStyle_ResizeAny|eWidgetFormStyle_Move__: Default form flags with close and form manager buttons. 

## interface ni::iWidgetForm
Form widget interface. 

### Parents:
- iUnknown

### Remarks:
- Form widgets implements iWidgetDockable. 

### Methods:
- __iWidgetForm::SetTitle__(_const achar\*_ aVal) -> _tBool_: Set the form's title. 
- __iWidgetForm::GetTitle__() -> _const achar\*_: Get the form's title. 
- __iWidgetForm::SetResizeBorderArea__(_tF32_ aVal) -> _tBool_: Set the size/area of the resize border. 
- __iWidgetForm::GetResizeBorderArea__() -> _tF32_: Get the size/area of the resize border. 
- __iWidgetForm::GetNumTitleWidgets__() -> _tU32_: Get the number of widgets in the title bar. 
- __iWidgetForm::GetTitleWidget__(_tU32_ anIndex) -> _iWidget\*_: Get the title bar widget at the specified index. 
- __iWidgetForm::GetTitleWidgetIndex__(_iWidget\*_ apWidget) -> _tU32_: Get the index of the specified title bar widget. 
- __iWidgetForm::GetTitleWidgetFromID__(_iHString\*_ ahspID) -> _iWidget\*_: Get the title bar widget with the specified ID. 
- __iWidgetForm::AddTitleWidget__(_iWidget\*_ apWidget, _tF32_ afWidth) -> _tBool_: Add a title bar widget. 
- __iWidgetForm::SetFormFrameFlags__(_tRectFrameFlags_ aFlags) -> _void_: Set the border frame flags. 
- __iWidgetForm::GetFormFrameFlags__() -> _tRectFrameFlags_: Get the form frame flags. 

## enum ni::eWidgetFormStyle
Widget form flags. 

### Values:
- __eWidgetFormStyle_Dock__ = __niBit(eWidgetStyle_MaxBit+0)__: Allow the form to dock by a parent docking manager. 
- __eWidgetFormStyle_Move__ = __niBit(eWidgetStyle_MaxBit+1)__: Allow the form to be moved. 
- __eWidgetFormStyle_ResizeTopLeftCorner__ = __niBit(eWidgetStyle_MaxBit+2)__: The form can be resized using the top left corner. 
- __eWidgetFormStyle_ResizeTopRightCorner__ = __niBit(eWidgetStyle_MaxBit+3)__: The form can be resized using the top right corner. 
- __eWidgetFormStyle_ResizeBottomLeftCorner__ = __niBit(eWidgetStyle_MaxBit+4)__: The form can be resized using the bottom left corner. 
- __eWidgetFormStyle_ResizeBottomRightCorner__ = __niBit(eWidgetStyle_MaxBit+5)__: The form can be resized using the bottom right corner. 
- __eWidgetFormStyle_ResizeAnyCorner__ = __eWidgetFormStyle_ResizeTopLeftCorner|eWidgetFormStyle_ResizeTopRightCorner|eWidgetFormStyle_ResizeBottomLeftCorner|eWidgetFormStyle_ResizeBottomRightCorner__: The form can be resized from any corner. 
- __eWidgetFormStyle_ResizeLeftEdge__ = __niBit(eWidgetStyle_MaxBit+6)__: The form can be resized using the left edge. 
- __eWidgetFormStyle_ResizeRightEdge__ = __niBit(eWidgetStyle_MaxBit+7)__: The form can be resized using the right edge. 
- __eWidgetFormStyle_ResizeTopEdge__ = __niBit(eWidgetStyle_MaxBit+8)__: The form can be resized using the top edge. 
- __eWidgetFormStyle_ResizeBottomEdge__ = __niBit(eWidgetStyle_MaxBit+9)__: The form can be resized using the bottom edge. 
- __eWidgetFormStyle_ResizeAnyEdge__ = __eWidgetFormStyle_ResizeLeftEdge|eWidgetFormStyle_ResizeRightEdge|eWidgetFormStyle_ResizeTopEdge|eWidgetFormStyle_ResizeBottomEdge__: The form can be resized from any edge. 
- __eWidgetFormStyle_ResizeAny__ = __eWidgetFormStyle_ResizeAnyCorner|eWidgetFormStyle_ResizeAnyEdge__: The form can be resized using any of the edges and corners. 
- __eWidgetFormStyle_CloseButton__ = __niBit(eWidgetStyle_MaxBit+10)__: The form has a close button. (ID_Close) 
- __eWidgetFormStyle_FormManagerButtons__ = __niBit(eWidgetStyle_MaxBit+11)__: The form has the form manager buttons, these are the minimize, maximize and restore buttons. (ID_Minimize, ID_Maximize, ID_Restore) 
- __eWidgetFormStyle_DockNoInputModifier__ = __niBit(eWidgetStyle_MaxBit+12)__: The docking overlays are always displayed when moving. The default behavior is that the 'Control' input modifier needs to be pressed while moving the form to display the docking overlays. 
- __eWidgetFormStyle_Default__ = __eWidgetFormStyle_Dock|eWidgetFormStyle_ResizeAny|eWidgetFormStyle_Move__: Default form flags. 
- __eWidgetFormStyle_DefaultButtons__ = __eWidgetFormStyle_Dock|eWidgetFormStyle_ResizeAny|eWidgetFormStyle_Move|eWidgetFormStyle_CloseButton|eWidgetFormStyle_FormManagerButtons__: Default form flags with close button. 
- __eWidgetFormStyle_DefaultManagerButtons__ = __eWidgetFormStyle_Dock|eWidgetFormStyle_ResizeAny|eWidgetFormStyle_Move__: Default form flags with close and form manager buttons. 

## enum ni::eWidgetGroupStyle
Group styles. 

### Values:
- __eWidgetGroupStyle_Fold__ = __niBit(eWidgetStyle_MaxBit+1)__: Toggle the folded state when double clicking on the title. 

## interface ni::iWidgetGroup
Group widget interface. 

### Parents:
- iUnknown

### Methods:
- __iWidgetGroup::SetFolded__(_tBool_ abFolded) -> _void_: Set whether the group is folded. 
- __iWidgetGroup::GetFolded__() -> _tBool_: Get whether the group is folded. 

## enum ni::eWidgetGroupStyle
Group styles. 

### Values:
- __eWidgetGroupStyle_Fold__ = __niBit(eWidgetStyle_MaxBit+1)__: Toggle the folded state when double clicking on the title. 

## enum ni::eWidgetLabelStyle
Label widget style. 

### Values:
- __eWidgetLabelStyle_TransparentBackground__ = __niBit(eWidgetStyle_MaxBit+1)__
- __eWidgetLabelStyle_DWORD__ = __0xFFFFFFFF__

## interface ni::iWidgetLabel
Label widget interface. 

### Parents:
- iUnknown

### Methods:
- __iWidgetLabel::SetFontFormatFlags__(_tFontFormatFlags_ aFlags) -> _void_: Set the label's font format flags. 
- __iWidgetLabel::GetFontFormatFlags__() -> _tFontFormatFlags_: Get the label's font format flags. 

## enum ni::eWidgetLabelStyle
Label widget style. 

### Values:
- __eWidgetLabelStyle_TransparentBackground__ = __niBit(eWidgetStyle_MaxBit+1)__
- __eWidgetLabelStyle_DWORD__ = __0xFFFFFFFF__

## enum ni::eWidgetListBoxCmd
Listbox notification messages 

### Values:
- __eWidgetListBoxCmd_SelectionChanged__ = __0__: Sent when the selection has changed 

## enum ni::eWidgetListBoxStyle
Listbox style 

### Values:
- __eWidgetListBoxStyle_HasHeader__ = __niBit(eWidgetStyle_MaxBit+0)__: Has header. 
- __eWidgetListBoxStyle_HeaderSort__ = __niBit(eWidgetStyle_MaxBit+1)__: Clicking the Header will sort the items Ascendant/Descendant. 
- __eWidgetListBoxStyle_Multiselect__ = __niBit(eWidgetStyle_MaxBit+2)__: Allow multiple selection. 
- __eWidgetListBoxStyle_SelectOnMove__ = __niBit(eWidgetStyle_MaxBit+3)__: Select when mouse moves. 
- __eWidgetListBoxStyle_ClickAddSelection__ = __niBit(eWidgetStyle_MaxBit+4)__: Click down add selection, Ctrl+Click set selection. (This is the opposite of the default) 

## interface ni::iWidgetListBox
Listbox widget interface. 

### Parents:
- iUnknown

### Methods:
- __iWidgetListBox::AddColumn__(_const achar\*_ aaszName, _tU32_ anSize) -> _void_: Add a column with the specified name and size. 
- __iWidgetListBox::RemoveColumn__(_tU32_ anColumn) -> _tBool_: Remove the specified columns. 
- __iWidgetListBox::GetNumColumns__() -> _tU32_: Get the number of columns in the list box. 
- __iWidgetListBox::SetColumnName__(_tU32_ anColumn, _const achar\*_ aaszName) -> _tBool_: Set the name/header of the column. 
- __iWidgetListBox::GetColumnName__(_tU32_ anColumn) -> _const achar\*_: Get the name/header of the column. 
- __iWidgetListBox::SetColumnWidth__(_tU32_ anColumn, _tU32_ anWidth) -> _tBool_: Set the width of the specified column. 
- __iWidgetListBox::GetColumnWidth__(_tU32_ anColumn) -> _tU32_: Get the width of the specified column. 
- __iWidgetListBox::SetColumn__(_tU32_ anColumn, _const achar\*_ aaszName, _tU32_ anSize) -> _tBool_: Set a column name and width. 
- __iWidgetListBox::GetNumItems__() -> _tU32_: Get the number of items in the listbox. 
- __iWidgetListBox::ClearItems__() -> _void_: Remove all items in the list box. 
- __iWidgetListBox::AddItem__(_const achar\*_ aaszText) -> _tU32_: Add an item. 
- __iWidgetListBox::RemoveItem__(_tU32_ anItem) -> _tBool_: Remove an item. 
- __iWidgetListBox::SetItemText__(_tU32_ anColumn, _tU32_ anItem, _const achar\*_ aaszText) -> _tBool_: Set the text of an item element. 
- __iWidgetListBox::GetItemText__(_tU32_ anColumn, _tU32_ anItem) -> _const achar\*_: Get the text of an item element. 
- __iWidgetListBox::SetItemWidget__(_tU32_ anColumn, _tU32_ anItem, _iWidget\*_ apWidget) -> _tBool_: Set the widget of an item element. 
- __iWidgetListBox::GetItemWidget__(_tU32_ anColumn, _tU32_ anItem) -> _iWidget\*_: Get the widget of an item element. 
- __iWidgetListBox::SetItemIcon__(_tU32_ anItem, _iOverlay\*_ apIcon) -> _tBool_: Set the icon of an item. 
- __iWidgetListBox::GetItemIcon__(_tU32_ anItem) -> _iOverlay\*_: Get the icon of an item. 
- __iWidgetListBox::SetItemData__(_tU32_ anItem, _iUnknown\*_ apData) -> _tBool_: Set the data of an item. 
- __iWidgetListBox::GetItemData__(_tU32_ anItem) -> _iUnknown\*_: Get the data of an item. 
- __iWidgetListBox::SetSortKey__(_tU32_ anKeyColumn) -> _tBool_: Set the sorting key column. 
- __iWidgetListBox::GetSortKey__() -> _tU32_: Get the sorting key column. 
- __iWidgetListBox::SetSortAscendant__(_tBool_ abAscendant) -> _void_: Set whether to use ascendant or descendant sorting. 
- __iWidgetListBox::GetSortAscendant__() -> _tBool_: Get whether to use ascendant or descendant sorting. 
- __iWidgetListBox::GetItemFromText__(_tU32_ anColumn, _const achar\*_ aaszName) -> _tU32_: Get the index of the first item that has the specified text in the specified column. 
- __iWidgetListBox::ClearSelection__() -> _void_: Clear the selection. 
- __iWidgetListBox::AddSelection__(_tU32_ anItem) -> _tBool_: Add a selection. 
- __iWidgetListBox::RemoveSelection__(_tU32_ anItem) -> _tBool_: Remove a selection. 
- __iWidgetListBox::GetNumSelections__() -> _tU32_: Get the number of selections. 
- __iWidgetListBox::GetSelection__(_tU32_ anIndex) -> _tU32_: Get the active selection at the specified index. 
- __iWidgetListBox::SetSelected__(_tU32_ anSelection) -> _tBool_: Set all selections to the selection specified. 
- __iWidgetListBox::GetSelected__() -> _tU32_: Get the first selection. 
- __iWidgetListBox::GetIsItemSelected__(_tU32_ anItem) -> _tBool_: Check if the specified item is selected. 
- __iWidgetListBox::AddSelectedItem__(_tU32_ anCol, _const achar\*_ aaszText) -> _tBool_: Get the first item with the selected text in the specified column and add it to the selection. 
- __iWidgetListBox::GetSelectedItemText__(_tU32_ anCol, _tU32_ anIndex) -> _const achar\*_: Get the text in the column of the selection at the specified index. 
- __iWidgetListBox::GetSelectedItemWidget__(_tU32_ anCol, _tU32_ anIndex) -> _iWidget\*_: Get the widget in the column of the selection at the specified index. 
- __iWidgetListBox::SetSelectedItem__(_tU32_ anCol, _const achar\*_ aaszText) -> _tBool_: Get the first item with the selected text in the specified column and set it as the selection. 
- __iWidgetListBox::GetSelectedItem__(_tU32_ anCol) -> _const achar\*_: Get the text in the specified column of the first selection. 
- __iWidgetListBox::SetItemHeight__(_tF32_ afHeight) -> _tBool_: Set the height of an item. 
- __iWidgetListBox::GetItemHeight__() -> _tF32_: Get the height of an item. 
- __iWidgetListBox::AutoScroll__() -> _void_: Auto scroll to the selection or last item if no item is selected. 
- __iWidgetListBox::SetItemTextColor__(_tU32_ anColumn, _tU32_ anItem, _tU32_ anTextColor) -> _tBool_: Set the color of the text of the specified column/item. Set anColumn to eInvalidHandle to set all the columns at once. 
- __iWidgetListBox::GetItemTextColor__(_tU32_ anColumn, _tU32_ anItem) -> _tU32_: Set the color of the text of the specified column/item. 
- __iWidgetListBox::SetMaxNumItems__(_tU32_ anMaxItems) -> _void_: Set the maximum number of items. 
- __iWidgetListBox::GetMaxNumItems__() -> _tU32_: Get the maximum number of items. 

## enum ni::eWidgetListBoxCmd
Listbox notification messages 

### Values:
- __eWidgetListBoxCmd_SelectionChanged__ = __0__: Sent when the selection has changed 

## enum ni::eWidgetMenuItemFlags
Menu item flags. 

### Values:
- __eWidgetMenuItemFlags_None__ = __0__: No flags. 
- __eWidgetMenuItemFlags_SubMenu__ = __niBit(1)__: The item will open a submenu. 
- __eWidgetMenuItemFlags_Separator__ = __niBit(2)__: The item is a separator. 
- __eWidgetMenuItemFlags_Check__ = __niBit(3)__: The item is a check. 
- __eWidgetMenuItemFlags_Group__ = __niBit(4)__: The item is in a group. 
- __eWidgetMenuItemFlags_Dummy__ = __niBit(5)__: The item is a dummy, aka it isnt clickable. 
- __eWidgetMenuItemFlags_Title__ = __niBit(6)__: The item is a title, will be drawn with a different background color. 
- __eWidgetMenuItemFlags_Disabled__ = __niBit(7)__: The item is disabled, text will be drawn in a different color. 
- __eWidgetMenuItemFlags_SortAdd__ = __niBit(8)__: Sort when adding the item. 

## enum ni::eWidgetMenuCmd
Menu notify message 

### Remarks:
- Sent through eUIMessage_Command to the parent widget, extra1 contains the iWidgetMenuItem of the item concerned. 
- Sub menus are considered part of the parent menu, they will send messages as if they were the parent menu. 

### Values:
- __eWidgetMenuCmd_Checked__ = __0__: A check menu item has been checked. 
- __eWidgetMenuCmd_UnChecked__ = __1__: A check menu item has been unchecked. 
- __eWidgetMenuCmd_GroupChanged__ = __2__: A group menu item has been changed. 
- __eWidgetMenuCmd_Clicked__ = __3__: A menu item has been clicked. 
- __eWidgetMenuCmd_Opened__ = __4__: Menu has just been opened. 
- __eWidgetMenuCmd_Closed__ = __5__: Menu has just been closed. 
- __eWidgetMenuCmd_FocusedItem__ = __6__: The menu item focused has changed. 

## enum ni::eWidgetMenuStyle
Menu style. 

### Remarks:
- The menu style is used only by the parent menu, sub menus will ignore these flags. 

### Values:
- __eWidgetMenuStyle_NoCloseOnGroupChange__ = __niBit(eWidgetStyle_MaxBit+0)__: Dont close the menu on group change. 
- __eWidgetMenuStyle_NoCloseOnCheckChange__ = __niBit(eWidgetStyle_MaxBit+1)__: Dont close the menu on check change. 
- __eWidgetMenuStyle_NoCloseOnItemClicked__ = __niBit(eWidgetStyle_MaxBit+2)__: Dont close the menu on item clicked. 
- __eWidgetMenuStyle_NoCloseOnNCClick__ = __niBit(eWidgetStyle_MaxBit+3)__: Dont close the menu when clicking outside of the client area. 
- __eWidgetMenuStyle_NoClose__ = __eWidgetMenuStyle_NoCloseOnGroupChange|eWidgetMenuStyle_NoCloseOnCheckChange|eWidgetMenuStyle_NoCloseOnItemClicked|eWidgetMenuStyle_NoCloseOnNCClick__: Dont close the menu automatically 
- __eWidgetMenuStyle_NoCloseOnGroupOrCheckChange__ = __eWidgetMenuStyle_NoCloseOnGroupChange|eWidgetMenuStyle_NoCloseOnCheckChange__: Dont close the menu on group or check change. 

## interface ni::iWidgetMenuItem
Menu item interface. 

### Parents:
- iUnknown

### Methods:
- __iWidgetMenuItem::GetMenu__() -> _iWidgetMenu\*_: Get the item's menu. 
- __iWidgetMenuItem::SetName__(_const achar\*_ aVal) -> _tBool_: Set the item's name. 
- __iWidgetMenuItem::GetName__() -> _const achar\*_: Get the item's name. 
- __iWidgetMenuItem::SetID__(_iHString\*_ aVal) -> _tBool_: Set the item's ID. 
- __iWidgetMenuItem::GetID__() -> _iHString\*_: Get the item's ID. 
- __iWidgetMenuItem::SetFlags__(_tWidgetMenuItemFlags_ aVal) -> _tBool_: Set the item's flags. 
- __iWidgetMenuItem::GetFlags__() -> _tWidgetMenuItemFlags_: Get the item's flags. 
- __iWidgetMenuItem::SetIcon__(_iOverlay\*_ aVal) -> _tBool_: Set the item's icon 
- __iWidgetMenuItem::GetIcon__() -> _iOverlay\*_: Get the item's icon 
- __iWidgetMenuItem::SetSubmenu__(_iHString\*_ aVal) -> _tBool_: Set the item's submenu ID. 
- __iWidgetMenuItem::GetSubmenu__() -> _iHString\*_: Get the item's submenu ID. 
- __iWidgetMenuItem::SetSelected__(_tBool_ aVal) -> _tBool_: Set the item's selected status. 
- __iWidgetMenuItem::GetSelected__() -> _tBool_: Get the item's selected status. 
- __iWidgetMenuItem::SetGroupID__(_iHString\*_ aVal) -> _tBool_: Set the item's group id. 
- __iWidgetMenuItem::GetGroupID__() -> _iHString\*_: Get the item's group id. 
- __iWidgetMenuItem::SetKey__(_eKey_ aVal) -> _tBool_: Set the item's key shortcut. 
- __iWidgetMenuItem::GetKey__() -> _eKey_: Get the item's key shortcut. 

## interface ni::iWidgetMenu
Menu interface. 

### Parents:
- iUnknown

### Remarks:
- The keyboard input for the menu is :<br> Escape : Close the current menu.<br> Home/End : Select the first/last menu item.<br> Up/Down : Select the previous/next menu item.<br> Ctrl/Shit+Up/Down or PgUp/PgDn : Select the next menu item before/after a separator.<br> Left : Close the current sub-menu. Wont close the main menu.<br> Right : Open the current sub-menu.<br> Enter/Space : Select/Click the current menu item.<br> 
- If the NoCloseOnNCClick style is set the main menu will not close when escape is pressed. 

### Methods:
- __iWidgetMenu::ClearItems__() -> _tBool_: Clear/removes all the items in the menu. 
- __iWidgetMenu::AddItem__(_const achar\*_ aaszName, _iHString\*_ ahspID, _tWidgetMenuItemFlags_ aFlags) -> _iWidgetMenuItem\*_: Add a menu item. 
- __iWidgetMenu::RemoveItem__(_iWidgetMenuItem\*_ apItem) -> _tBool_: Remove the item at the specified index. 
- __iWidgetMenu::GetNumItems__() -> _tU32_: Get the number of items. 
- __iWidgetMenu::GetItem__(_tU32_ anIndex) -> _iWidgetMenuItem\*_: Get the item at the specified index. 
- __iWidgetMenu::GetItemFromName__(_const achar\*_ aaszName) -> _iWidgetMenuItem\*_: Get the index of the first item with the specified name. 
- __iWidgetMenu::GetItemFromID__(_iHString\*_ ahspID) -> _iWidgetMenuItem\*_: Get the index of the first item with the specified id. 
- __iWidgetMenu::Open__() -> _tBool_: Open the menu. 
- __iWidgetMenu::Close__() -> _tBool_: Close the menu. 
- __iWidgetMenu::SortItems__() -> _tBool_: Sort the items. 
- __iWidgetMenu::GetMenuWidth__() -> _tU32_: Get the menu's width in pixels. 
- __iWidgetMenu::GetMenuHeight__() -> _tU32_: Get the menu's height in pixels. 
- __iWidgetMenu::GetItemWidth__() -> _tU32_: Get the item's width in pixels. 
- __iWidgetMenu::GetItemHeight__() -> _tU32_: Get the item's height in pixels. 
- __iWidgetMenu::UpdateSizes__() -> _void_: Update the menu's sizes. 

## enum ni::eWidgetMenuItemFlags
Menu item flags. 

### Values:
- __eWidgetMenuItemFlags_None__ = __0__: No flags. 
- __eWidgetMenuItemFlags_SubMenu__ = __niBit(1)__: The item will open a submenu. 
- __eWidgetMenuItemFlags_Separator__ = __niBit(2)__: The item is a separator. 
- __eWidgetMenuItemFlags_Check__ = __niBit(3)__: The item is a check. 
- __eWidgetMenuItemFlags_Group__ = __niBit(4)__: The item is in a group. 
- __eWidgetMenuItemFlags_Dummy__ = __niBit(5)__: The item is a dummy, aka it isnt clickable. 
- __eWidgetMenuItemFlags_Title__ = __niBit(6)__: The item is a title, will be drawn with a different background color. 
- __eWidgetMenuItemFlags_Disabled__ = __niBit(7)__: The item is disabled, text will be drawn in a different color. 
- __eWidgetMenuItemFlags_SortAdd__ = __niBit(8)__: Sort when adding the item. 

## enum ni::eWidgetProgressBarStyle


### Values:
- __eWidgetProgressBarStyle_Vert__ = __niBit(eWidgetStyle_MaxBit+1)__
- __eWidgetProgressBarStyle_DWORD__ = __0xFFFFFFFF__

## interface ni::iWidgetProgressBar


### Parents:
- iUnknown

### Methods:
- __iWidgetProgressBar::SetRange__(_tF32_ afMin, _tF32_ afMax) -> _void_
- __iWidgetProgressBar::SetProgress__(_tF32_ afPos) -> _void_
- __iWidgetProgressBar::GetProgress__() -> _tF32_

## enum ni::eWidgetProgressBarStyle


### Values:
- __eWidgetProgressBarStyle_Vert__ = __niBit(eWidgetStyle_MaxBit+1)__
- __eWidgetProgressBarStyle_DWORD__ = __0xFFFFFFFF__

## interface ni::iWidgetPropertyBox
PropertyBox widget interface. 

### Parents:
- iUnknown

### Remarks:
- To notifications of the datatable's modifications register a iDataTableSink int the datatable of the property box. 

### Methods:
- __iWidgetPropertyBox::SetDataTable__(_iDataTable\*_ apDT) -> _void_: Set the property box's data table. 
- __iWidgetPropertyBox::GetDataTable__() -> _iDataTable\*_: Get the property box's data table. 

## interface ni::iWidgetPropertyBox
PropertyBox widget interface. 

### Parents:
- iUnknown

### Remarks:
- To notifications of the datatable's modifications register a iDataTableSink int the datatable of the property box. 

### Methods:
- __iWidgetPropertyBox::SetDataTable__(_iDataTable\*_ apDT) -> _void_: Set the property box's data table. 
- __iWidgetPropertyBox::GetDataTable__() -> _iDataTable\*_: Get the property box's data table. 

## enum ni::eWidgetScrollBarStyle
Scroll bar style 

### Values:
- __eWidgetScrollBarStyle_Slider__ = __niBit(eWidgetStyle_MaxBit+0)__: The scroll bar is a slider. 
- __eWidgetScrollBarStyle_Horz__ = __niBit(eWidgetStyle_MaxBit+1)__: The scroll bar is horizontal. 
- __eWidgetScrollBarStyle_Right__ = __niBit(eWidgetStyle_MaxBit+2)__: The slider should be on the right. (On the left by default) 
- __eWidgetScrollBarStyle_Bottom__ = __niBit(eWidgetStyle_MaxBit+3)__: The slider should be on the bottom. (On top by default) 

## enum ni::eWidgetScrollBarCmd
Scroll bar commands 

### Values:
- __eWidgetScrollBarCmd_Scrolled__ = __0__: The scroll bar has been scrolled. 

## interface ni::iWidgetScrollBar
Scroll bar widget interface. 

### Parents:
- iUnknown

### Methods:
- __iWidgetScrollBar::SetScrollRange__(_const sVec2f&_ avRange) -> _void_: Set the scroll bar range. 
- __iWidgetScrollBar::GetScrollRange__() -> _sVec2f_: Get the scroll bar range. 
- __iWidgetScrollBar::SetScrollPosition__(_tF32_ afScrollPos) -> _void_: Set the scroll bar position. 
- __iWidgetScrollBar::GetScrollPosition__() -> _tF32_: Get the scroll bar position. 
- __iWidgetScrollBar::SetNormalizedScrollPosition__(_tF32_ afScrollPos) -> _void_: Set the normalized scroll bar position. 
- __iWidgetScrollBar::GetNormalizedScrollPosition__() -> _tF32_: Get the normalized scroll bar position. 
- __iWidgetScrollBar::SetPageSize__(_tF32_ afPageSize) -> _void_: Set the scroll bar page size. 
- __iWidgetScrollBar::GetPageSize__() -> _tF32_: Get the scroll bar page size. 
- __iWidgetScrollBar::ComputeRoundedPosition__(_tF32_ afNewPos) -> _tF32_: Compute a position rounded by the page size in function of the scroll bar's flags. 

## enum ni::eWidgetScrollBarStyle
Scroll bar style 

### Values:
- __eWidgetScrollBarStyle_Slider__ = __niBit(eWidgetStyle_MaxBit+0)__: The scroll bar is a slider. 
- __eWidgetScrollBarStyle_Horz__ = __niBit(eWidgetStyle_MaxBit+1)__: The scroll bar is horizontal. 
- __eWidgetScrollBarStyle_Right__ = __niBit(eWidgetStyle_MaxBit+2)__: The slider should be on the right. (On the left by default) 
- __eWidgetScrollBarStyle_Bottom__ = __niBit(eWidgetStyle_MaxBit+3)__: The slider should be on the bottom. (On top by default) 

## enum ni::eWidgetSearchBarCmd
Search bar widget notify messages. 

### Values:
- __eWidgetSearchBarCmd_SelectionChanged__ = __0__: Sent when the selection changed 
- __eWidgetSearchBarCmd_Begin__ = __1__: Sent when the search bar becomes visible 
- __eWidgetSearchBarCmd_End__ = __2__: This is a good time to destroy or hide the search bar 

## interface ni::iSearchContainer
Search container 

### Parents:
- iUnknown

### Methods:
- __iSearchContainer::AddResult__(_tU32_ anIndex, _const achar\*_ aaszValue) -> _void_

## interface ni::iSearchable
Searchable interface, to be searched impl it 

### Parents:
- iUnknown

### Methods:
- __iSearchable::OnSelect__(_tU32_ nIndex) -> _void_
- __iSearchable::GetCorpus__(_iSearchContainer\*_ apContainer) -> _void_

## interface ni::iWidgetSearchBar
Search bar widget interface. 

### Parents:
- iUnknown

### Methods:
- __iWidgetSearchBar::SetSearchable__(_iSearchable\*_ aS) -> _void_: Set a searchable to be search 
- __iWidgetSearchBar::GetSearchable__() -> _iSearchable\*_: Get a searchable object. 

## enum ni::eWidgetSearchBarCmd
Search bar widget notify messages. 

### Values:
- __eWidgetSearchBarCmd_SelectionChanged__ = __0__: Sent when the selection changed 
- __eWidgetSearchBarCmd_Begin__ = __1__: Sent when the search bar becomes visible 
- __eWidgetSearchBarCmd_End__ = __2__: This is a good time to destroy or hide the search bar 

## enum ni::eWidgetSplitterStyle
Splitter widget style. 

### Values:
- __eWidgetSplitterStyle_Horizontal__ = __niBit(eWidgetStyle_MaxBit+0)__: The splitter is horizontal. 
- __eWidgetSplitterStyle_NoCursorResize__ = __niBit(eWidgetStyle_MaxBit+1)__: The splitter cant be resized with the mouse cursor. 
- __eWidgetSplitterStyle_Empty__ = __niBit(eWidgetStyle_MaxBit+2)__: The splitter will start empty. 

## enum ni::eWidgetSplitterFoldMode
Splitter folding mode. 

### Values:
- __eWidgetSplitterFoldMode_None__ = __0__: No folding. 
- __eWidgetSplitterFoldMode_Auto__ = __1__: Fold left/top or right/bottom based on the resizable borders enabled. (default) 
- __eWidgetSplitterFoldMode_All__ = __2__: Fold left/top & right/bottom regardless of the resizable borders. 

## interface ni::iWidgetSplitter
Splitter widget interface. 

### Parents:
- iUnknown

### Methods:
- __iWidgetSplitter::AddSplitterFront__(_tF32_ afPos) -> _tBool_: Add a splitter in the front (top or left). 
- __iWidgetSplitter::AddSplitterBack__(_tF32_ afPos) -> _tBool_: Add a splitter in the back (bottom or right). 
- __iWidgetSplitter::RemoveSplitter__(_tU32_ anIndex) -> _tBool_: Remove the splitter at the specified index. 
- __iWidgetSplitter::GetNumSplitters__() -> _tU32_: Get the number of splitters. 
- __iWidgetSplitter::GetNumSplitterWidgets__() -> _tU32_: Get the number of splitter's widgets. 
- __iWidgetSplitter::GetSplitterWidget__(_tU32_ anIndex) -> _iWidget\*_: Get a splitter's widget. 
- __iWidgetSplitter::GetSplitterWidgetIndex__(_iWidget\*_ apWidget) -> _tU32_: Get a splitter's widget index. 
- __iWidgetSplitter::RemoveSplitterWidget__(_tU32_ anIndex) -> _tBool_: Remove the specified splitter widget. 
- __iWidgetSplitter::AddSplitterBefore__(_tU32_ anWidget, _tF32_ afPos) -> _tBool_: Add a splitter before the specified widget (top or left). 
- __iWidgetSplitter::AddSplitterAfter__(_tU32_ anWidget, _tF32_ afPos) -> _tBool_: Add a splitter after the specified widget (bottom or right). 
- __iWidgetSplitter::SetSplitterPosition__(_tU32_ anIndex, _tF32_ aVal) -> _tBool_: Set the position of the splitter at the given index. 
- __iWidgetSplitter::GetSplitterPosition__(_tU32_ anIndex) -> _tF32_: Get the position of the splitter at the given index 
- __iWidgetSplitter::SetSplitterMinPosition__(_tF32_ aVal) -> _tBool_: Set the splitter's minimum position. 
- __iWidgetSplitter::GetSplitterMinPosition__() -> _tF32_: Get the splitter's minimum position. 
- __iWidgetSplitter::SetSplitterSize__(_tF32_ afSize) -> _tBool_: Set the splitter size. 
- __iWidgetSplitter::GetSplitterSize__() -> _tF32_: Get the splitter size. 
- __iWidgetSplitter::SwapSplitterWidget__(_tU32_ anA, _tU32_ anB) -> _tBool_: Swap two splitter widgets. 
- __iWidgetSplitter::SetSplitterBorderSize__(_tF32_ afSize) -> _void_: Set the splitter's border size. 
- __iWidgetSplitter::GetSplitterBorderSize__() -> _tF32_: Get the splitter's border size. 
- __iWidgetSplitter::SetSplitterResizableBorders__(_tU32_ aEdges) -> _void_: Set the splitter's resizable borders. 
- __iWidgetSplitter::GetSplitterResizableBorders__() -> _tU32_: Get the splitter's resizable borders. 
- __iWidgetSplitter::SetSplitterParentDockRectMinimumSize__(_sVec2f_ avMinSize) -> _void_: Set the minimum size that the parent dock rect can have. 
- __iWidgetSplitter::GetSplitterParentDockRectMinimumSize__() -> _sVec2f_: Get the minimum size that the parent dock rect can have. 
- __iWidgetSplitter::SetSplitterFillerIndex__(_ni::tU32_ anIndex) -> _void_: Set the index of the filling splitter. 
- __iWidgetSplitter::GetSplitterFillerIndex__() -> _tU32_: Set the index of the filling splitter. 
- __iWidgetSplitter::SetSplitterFoldMode__(_eWidgetSplitterFoldMode_ aFoldMode) -> _void_: Set the splitter's fold mode. 
- __iWidgetSplitter::GetSplitterFoldMode__() -> _eWidgetSplitterFoldMode_: Get the splitter's fold mode. 

## enum ni::eWidgetSplitterStyle
Splitter widget style. 

### Values:
- __eWidgetSplitterStyle_Horizontal__ = __niBit(eWidgetStyle_MaxBit+0)__: The splitter is horizontal. 
- __eWidgetSplitterStyle_NoCursorResize__ = __niBit(eWidgetStyle_MaxBit+1)__: The splitter cant be resized with the mouse cursor. 
- __eWidgetSplitterStyle_Empty__ = __niBit(eWidgetStyle_MaxBit+2)__: The splitter will start empty. 

## enum ni::eWidgetTabCmd
Tab widget notify message. 

### Values:
- __eWidgetTabCmd_ActivatePage__ = __0__: A page has been activated. 
- __eWidgetTabCmd_AddPage__ = __1__: A page has been added. 
- __eWidgetTabCmd_RemovePage__ = __2__: A page has been removed. 

## interface ni::iWidgetTab
Tab widget. 

### Parents:
- iUnknown

### Methods:
- __iWidgetTab::AddPage__(_iHString\*_ ahspName, _iWidget\*_ apPage) -> _void_: Add a page. 
- __iWidgetTab::RemovePage__(_iWidget\*_ apPage) -> _tBool_: Remove a page. 
- __iWidgetTab::HasPage__(_iWidget\*_ apPage) -> _tBool_: Check if the specified page is in the tab. 
- __iWidgetTab::GetNumPages__() -> _tU32_: Get the number of pages. 
- __iWidgetTab::GetPage__(_tU32_ anIndex) -> _iWidget\*_: Get the page at the specified index. 
- __iWidgetTab::GetPageButton__(_tU32_ anIndex) -> _iWidget\*_: Get the button associated with the page at the specified index. 
- __iWidgetTab::GetPageFromName__(_iHString\*_ ahspName) -> _iWidget\*_: Get the page with the specified name. 
- __iWidgetTab::GetPageFromID__(_iHString\*_ ahspID) -> _iWidget\*_: Get the page with the specified ID. 
- __iWidgetTab::SetPageName__(_iWidget\*_ apPage, _iHString\*_ ahspName) -> _tBool_: Set the name of the specified page. 
- __iWidgetTab::GetPageName__(_iWidget\*_ apPage) -> _iHString\*_: Get the name of the specified page. 
- __iWidgetTab::SetPageIndex__(_iWidget\*_ apPage, _tU32_ anIndex) -> _tBool_: Set the index of the specified page. 
- __iWidgetTab::GetPageIndex__(_iWidget\*_ apPage) -> _tU32_: Get the index of the specified page. 
- __iWidgetTab::MovePageLeft__(_iWidget\*_ apPage, _tU32_ anLeft) -> _tBool_: Move the specified type to the left. 
- __iWidgetTab::MovePageRight__(_iWidget\*_ apPage, _tU32_ anCount) -> _tBool_: Move the specified type to the right. 
- __iWidgetTab::SetMinNumPagesToShowTabs__(_tU32_ anMinNumPages) -> _void_: Set the number of pages necessary to show the tabs. 
- __iWidgetTab::GetMinNumPagesToShowTabs__() -> _tU32_: Get the number of pages necessary to show the tabs. 
- __iWidgetTab::SetActivePage__(_iWidget\*_ apPage) -> _tBool_: Activate the specified page. 
- __iWidgetTab::GetActivePage__() -> _iWidget\*_: Get the active page. 
- __iWidgetTab::SetActivePageName__(_iHString\*_ ahspName) -> _tBool_: Activate the page with the specified name. 
- __iWidgetTab::GetActivePageName__() -> _iHString\*_: Get the name of the active page. 
- __iWidgetTab::SetActivePageIndex__(_tU32_ anIndex) -> _tBool_: Activate the page with the specified index. 
- __iWidgetTab::GetActivePageIndex__() -> _tU32_: Get the index of the active page. 
- __iWidgetTab::SetActivePageID__(_iHString\*_ ahspName) -> _tBool_: Activate the page with the specified id. 
- __iWidgetTab::GetActivePageID__() -> _iHString\*_: Get the id of the active page. 
- __iWidgetTab::SetForceActivated__(_tBool_ abForce) -> _void_: Set the forced activated state. 
- __iWidgetTab::GetForceActivated__(_tBool_ abForce) -> _tBool_: Get the forced activated state. 

## enum ni::eWidgetTabCmd
Tab widget notify message. 

### Values:
- __eWidgetTabCmd_ActivatePage__ = __0__: A page has been activated. 
- __eWidgetTabCmd_AddPage__ = __1__: A page has been added. 
- __eWidgetTabCmd_RemovePage__ = __2__: A page has been removed. 

## enum ni::eWidgetTextStyle
Widget text style 

### Values:
- __eWidgetTextStyle_MouseSelect__ = __niBit(eWidgetStyle_MaxBit+1)__: Allow text selection with the mouse 

## interface ni::iWidgetText
iWidgetText interface 

### Parents:
- iUnknown

### Remarks:
- Implements the iWidgetText interface. 

### Methods:
- __iWidgetText::GetTextObject__() -> _iTextObject\*_: Get the text object of the text widget 

## enum ni::eWidgetTextStyle
Widget text style 

### Values:
- __eWidgetTextStyle_MouseSelect__ = __niBit(eWidgetStyle_MaxBit+1)__: Allow text selection with the mouse 

## interface ni::iWidgetToolbarGroup
Toolbar group widget interface. 

### Parents:
- iUnknown

### Methods:
- __iWidgetToolbarGroup::SetWidthFromChildren__() -> _void_: Set the width of the group from the total with of the children. 
- __iWidgetToolbarGroup::SetCommandDestination__(_iMessageHandler\*_ apMT) -> _void_: Set the destination message handler for the commands received by the group. 
- __iWidgetToolbarGroup::GetCommandDestination__() -> _iMessageHandler\*_: Get the destination message handler for the commands received by the toolbar. 

## interface ni::iWidgetToolbar
Toolbar widget interface. 

### Parents:
- iUnknown

### Methods:
- __iWidgetToolbar::SetHeight__(_ni::tF32_ afHeight) -> _void_: Set the toolbar's height in pixels. 
- __iWidgetToolbar::GetHeight__() -> _ni::tF32_: Get the toolbar's height. 
- __iWidgetToolbar::SetAutoHide__(_ni::tBool_ abAutoHide) -> _void_: Set whether the toolbar should auto-hide. 
- __iWidgetToolbar::GetAutoHide__() -> _ni::tBool_: Get whether the toolbar should auto-hide. 
- __iWidgetToolbar::SetAutoHideBackground__(_ni::tBool_ abAutoHide) -> _void_: Set whether the toolbar should draw the bottom background when unfolded in auto-hide mode. 
- __iWidgetToolbar::GetAutoHideBackground__() -> _ni::tBool_: Get whether the toolbar should draw the bottom background when unfolded in auto-hide mode. 
- __iWidgetToolbar::SetShowPage__(_ni::tBool_ abShowPage) -> _void_: Set whether the toolbar's active page should be visible. 
- __iWidgetToolbar::GetShowPage__() -> _ni::tBool_: Get whether the toolbar's active page is visible. 
- __iWidgetToolbar::GetTopBar__() -> _iWidget\*_: Get the top bar widget. 
- __iWidgetToolbar::GetBottomBar__() -> _iWidget\*_: Get the bottom bar widget. 
- __iWidgetToolbar::SetCommandDestination__(_iMessageHandler\*_ apMH) -> _void_: Set the destination message target for the commands received by the toolbar. 
- __iWidgetToolbar::GetCommandDestination__() -> _iMessageHandler\*_: Get the destination message for the commands received by the toolbar. 
- __iWidgetToolbar::UpdateToolbar__() -> _void_: Updates the toolbar. 
- __iWidgetToolbar::HidePopup__() -> _void_: Hide the toolbar pop-up. 
- __iWidgetToolbar::GetNumPages__() -> _ni::tU32_: Get the number of pages in the toolbar. 
- __iWidgetToolbar::GetPageWidget__(_ni::tU32_ anIndex) -> _ni::iWidget\*_: Get the widget of the page at the specified index. 
- __iWidgetToolbar::GetPageIndex__(_ni::iHString\*_ ahspID) -> _ni::tU32_: Get the index of the page with the specified ID. 
- __iWidgetToolbar::InitPage__(_iHString\*_ ahspID, _iHString\*_ ahspName) -> _iWidget\*_: Initialize/Add a toolbar with the specified ID and name. 
- __iWidgetToolbar::SetPageName__(_iHString\*_ ahspID, _iHString\*_ ahspName) -> _ni::tBool_: Set the name/title of the specified page. 
- __iWidgetToolbar::GetPageName__(_iHString\*_ ahspID) -> _iHString\*_: Get the name/title of the specified page. 
- __iWidgetToolbar::SetPageEnabled__(_iHString\*_ ahspID, _tBool_ abEnabled) -> _ni::tBool_: Set whether the specifed page is enabled. 
- __iWidgetToolbar::GetPageEnabled__(_iHString\*_ ahspID) -> _ni::tBool_: Get whether the specifed page is enabled. 
- __iWidgetToolbar::SetActivePageIndex__(_ni::tU32_ anActivePage) -> _ni::tBool_: Set the active's page index. 
- __iWidgetToolbar::GetActivePageIndex__() -> _ni::tU32_: Get the active's pages index. 
- __iWidgetToolbar::SetActivePageID__(_ni::iHString\*_ ahspID) -> _ni::tBool_: Set the active's page ID. 
- __iWidgetToolbar::GetActivePageID__() -> _ni::iHString\*_: Get the active's page ID. 
- __iWidgetToolbar::GetNumTopWidgets__() -> _tU32_: Get the number of widgets in the top bar. 
- __iWidgetToolbar::GetTopWidget__(_tU32_ anIndex) -> _iWidget\*_: Get the top bar widget at the specified index. 
- __iWidgetToolbar::GetTopWidgetIndex__(_iWidget\*_ apWidget) -> _tU32_: Get the index of the specified top bar widget. 
- __iWidgetToolbar::GetTopWidgetFromID__(_iHString\*_ ahspID) -> _iWidget\*_: Get the top bar widget with the specified ID. 
- __iWidgetToolbar::SetTopWidgetCommandDestination__(_tU32_ anIndex, _iMessageHandler\*_ apCmdDest) -> _tBool_: Set the command destination of the specified top widget. 
- __iWidgetToolbar::GetTopWidgetCommandDestination__(_tU32_ anIndex) -> _iMessageHandler\*_: Get the command destination of the specified top widget. 
- __iWidgetToolbar::AddTopWidget__(_iWidget\*_ apWidget, _tF32_ afWidth, _iMessageHandler\*_ apCmdDest) -> _tBool_: Add a top bar widget. 
- __iWidgetToolbar::AddGroup__(_iHString\*_ ahspPageID, _iHString\*_ ahspPageName, _iHString\*_ ahspGroupID, _iHString\*_ ahspGroupName, _iMessageHandler\*_ apCmdDest) -> _iWidget\*_: Add a group in the specified page. If the page doesn't already exist it is added. 
- __iWidgetToolbar::GetGroup__(_ni::iHString\*_ ahspID) -> _iWidget\*_: Get the group with the specified ID. 
- __iWidgetToolbar::RemoveGroup__(_ni::iHString\*_ ahspID) -> _tBool_: Remove the specified group. 

## interface ni::iWidgetToolbarGroup
Toolbar group widget interface. 

### Parents:
- iUnknown

### Methods:
- __iWidgetToolbarGroup::SetWidthFromChildren__() -> _void_: Set the width of the group from the total with of the children. 
- __iWidgetToolbarGroup::SetCommandDestination__(_iMessageHandler\*_ apMT) -> _void_: Set the destination message handler for the commands received by the group. 
- __iWidgetToolbarGroup::GetCommandDestination__() -> _iMessageHandler\*_: Get the destination message handler for the commands received by the toolbar. 

## enum ni::eWidgetTreeNodeDropMode
Widget tree node drop mode. 

### Values:
- __eWidgetTreeNodeDropMode_On__ = __0__: Drop on the node. 
- __eWidgetTreeNodeDropMode_Below__ = __1__: Drop below the node. 
- __eWidgetTreeNodeDropMode_Above__ = __2__: Drop above the node. 
- __eWidgetTreeNodeDropMode_Invalid__ = __3__: Invalid drop area. 

## enum ni::eWidgetTreeStyle
Widget tree style. 

### Values:
- __eWidgetTreeStyle_ClickDownSelect__ = __niBit(eWidgetStyle_MaxBit+0)__: Select the item on left click down. Note that this disables the secondary selection. 
- __eWidgetTreeStyle_NoHScroll__ = __niBit(eWidgetStyle_MaxBit+1)__: Don't show the horizontal scrollbar. 
- __eWidgetTreeStyle_NoVScroll__ = __niBit(eWidgetStyle_MaxBit+2)__: Don't show the vertical scrollbar. 
- __eWidgetTreeStyle_Autoscroll__ = __niBit(eWidgetStyle_MaxBit+3)__: Automaticall scroll to the selected nodes. 
- __eWidgetTreeStyle_DontDrawRoot__ = __niBit(eWidgetStyle_MaxBit+4)__: Don't draw the root node. 
- __eWidgetTreeStyle_AlwaysHScroll__ = __niBit(eWidgetStyle_MaxBit+5)__: Always show the horizontal scrollbar. 
- __eWidgetTreeStyle_AlwaysVScroll__ = __niBit(eWidgetStyle_MaxBit+6)__: Always show the vertical scrollbar. 
- __eWidgetTreeStyle_SingleSelection__ = __niBit(eWidgetStyle_MaxBit+7)__: Single selection only. 

## enum ni::eWidgetTreeCmd
Widget tree notify message 

### Values:
- __eWidgetTreeCmd_Selected__ = __0__: A tree node has been selected. 
- __eWidgetTreeCmd_Unselected__ = __1__
- __eWidgetTreeCmd_Expanded__ = __2__: A tree node has been expanded. 
- __eWidgetTreeCmd_Collapsed__ = __3__: A tree node has been collapsed. 
- __eWidgetTreeCmd_SecondarySelected__ = __4__: A tree node has been selected as a secondary selection. 
- __eWidgetTreeCmd_SecondaryUnselected__ = __5__: A tree node has been unselected as a secondary selection. 
- __eWidgetTreeCmd_SetAttributes__ = __6__: A tree node's attribute have changed. 
- __eWidgetTreeCmd_SetName__ = __7__: A tree node's name has changed. 

## enum ni::eWidgetTreeNodeFlags
Widget tree node flags. 

### Values:
- __eWidgetTreeNodeFlags_Selected__ = __niBit(0)__: The node is selected. 
- __eWidgetTreeNodeFlags_Expanded__ = __niBit(1)__: The node is expanded. 
- __eWidgetTreeNodeFlags_DontDrawName__ = __niBit(2)__: Don't draw the name of the node. 
- __eWidgetTreeNodeFlags_Expandable__ = __niBit(3)__: The node is expandable even if it doesn't have any children. 
- __eWidgetTreeNodeFlags_WidgetPlaceV__ = __niBit(4)__: The widget in the tree node will be placed vertically. 
- __eWidgetTreeNodeFlags_WidgetPlaceH__ = __niBit(5)__: The widget in the tree node will be placed horizontally. 
- __eWidgetTreeNodeFlags_WidgetPlace__ = __eWidgetTreeNodeFlags_WidgetPlaceV|eWidgetTreeNodeFlags_WidgetPlaceH__: The widget in the tree node will be placed vertically and horizontally. 
- __eWidgetTreeNodeFlags_WidgetSize__ = __niBit(6)__: The widget in the tree node will be sized to fit in the tree. 
- __eWidgetTreeNodeFlags_WidgetLeft__ = __niBit(7)__: The widget in the tree node will be placed at the left of the text. 
- __eWidgetTreeNodeFlags_UseTextColor__ = __niBit(8)__: Use the tree node's text color. 
- __eWidgetTreeNodeFlags_Visible__ = __niBit(9)__: The widget tree node is visible. 
- __eWidgetTreeNodeFlags_Default__ = __eWidgetTreeNodeFlags_WidgetPlace|eWidgetTreeNodeFlags_Visible__: Default tree node flags. 

## interface ni::iWidgetTreeNode
Widget tree node interface. 

### Parents:
- iUnknown

### Methods:
- __iWidgetTreeNode::GetParentWidget__() -> _iWidget\*_: Get the parent widget tree. 
- __iWidgetTreeNode::GetParentNode__() -> _iWidgetTreeNode\*_: Get the parent node. 
- __iWidgetTreeNode::GetNodeRect__() -> _sRectf_: Get the node's rectangle. 
- __iWidgetTreeNode::GetScrolledNodeRect__() -> _sRectf_: Get the node's scrolled rectangle. 
- __iWidgetTreeNode::GetAbsoluteNodeRect__() -> _sRectf_: Get the node's absolute rectangle. 
- __iWidgetTreeNode::GetTextRect__() -> _sRectf_: Get the node's text rectangle. 
- __iWidgetTreeNode::GetScrolledTextRect__() -> _sRectf_: Get the node's scrolled text rectangle. 
- __iWidgetTreeNode::GetAbsoluteTextRect__() -> _sRectf_: Get the node's absolute rectangle. 
- __iWidgetTreeNode::GetIndex__() -> _tU32_: Get the node index. 
- __iWidgetTreeNode::GetTreeIndex__() -> _tU32_: Get the tree index. 
- __iWidgetTreeNode::GetNumChildNodes__() -> _tU32_: Get the number of child nodes. 
- __iWidgetTreeNode::GetChildNode__(_tU32_ anIndex) -> _iWidgetTreeNode\*_: Get the child node at the specified index. 
- __iWidgetTreeNode::GetChildNodeIndex__(_const iWidgetTreeNode\*_ apNode) -> _tU32_: Get the index of the specified child node. 
- __iWidgetTreeNode::GetChildNodeFromName__(_const achar\*_ aaszName) -> _iWidgetTreeNode\*_: Get the first child node with the specified name. 
- __iWidgetTreeNode::AddChildNode__(_const achar\*_ aaszName) -> _iWidgetTreeNode\*_: Add a new child node. 
- __iWidgetTreeNode::AddChildNodeBefore__(_const achar\*_ aaszName, _tU32_ anIndex) -> _iWidgetTreeNode\*_: Add a new child node before the specified index. 
- __iWidgetTreeNode::RemoveChildNode__(_iWidgetTreeNode\*_ apNode) -> _tBool_: Remove a child node. 
- __iWidgetTreeNode::Clear__() -> _tBool_: Remove all children. 
- __iWidgetTreeNode::FindNodeFromName__(_const achar\*_ aaszName) -> _iWidgetTreeNode\*_: Find the first node with the specified name. 
- __iWidgetTreeNode::FindNodeFromUserdata__(_const iUnknown\*_ apUserdata) -> _iWidgetTreeNode\*_: Find the first node with the specified userdata. 
- __iWidgetTreeNode::FindNodeFromWidget__(_const iWidget\*_ apWidget) -> _iWidgetTreeNode\*_: Find the first node with the specified widget. 
- __iWidgetTreeNode::FindNodeFromPosition__(_const sVec2f&_ avPos) -> _iWidgetTreeNode\*_: Find the node that is below the specified position, position in absolute coordinates. 
- __iWidgetTreeNode::GetPrevSibling__() -> _iWidgetTreeNode\*_: Get the previous sibiling of this tree node. 
- __iWidgetTreeNode::GetNextSibling__() -> _iWidgetTreeNode\*_: Get the next sibiling of this tree node. 
- __iWidgetTreeNode::GetAbove__() -> _iWidgetTreeNode\*_: Get the node above of this node, can be in another parent node. 
- __iWidgetTreeNode::GetBelow__() -> _iWidgetTreeNode\*_: Get the node below of this node, can be in another parent node. 
- __iWidgetTreeNode::SetFlags__(_tWidgetTreeNodeFlags_ aFlags) -> _tBool_: Set the node's flags. 
- __iWidgetTreeNode::GetFlags__() -> _tWidgetTreeNodeFlags_: Get the node's flags. 
- __iWidgetTreeNode::SetName__(_const achar\*_ aVal) -> _tBool_: Set the node's name. 
- __iWidgetTreeNode::GetName__() -> _const achar\*_: Get the node's name. 
- __iWidgetTreeNode::SetIcon__(_iOverlay\*_ aVal) -> _tBool_: Set the node's icon 
- __iWidgetTreeNode::GetIcon__() -> _iOverlay\*_: Get the node's icon 
- __iWidgetTreeNode::SetSelected__(_tBool_ abSelected) -> _tBool_: Set the node's selected status. 
- __iWidgetTreeNode::GetSelected__() -> _tBool_: Get the node's selected status. 
- __iWidgetTreeNode::SetExpanded__(_tBool_ abExpanded) -> _tBool_: Set the node's expanded status. 
- __iWidgetTreeNode::GetExpanded__() -> _tBool_: Get the node's expanded status. 
- __iWidgetTreeNode::SetUserdata__(_iUnknown\*_ apUserData) -> _tBool_: Set the node's user data. 
- __iWidgetTreeNode::GetUserdata__() -> _iUnknown\*_: Get the node's user data. 
- __iWidgetTreeNode::SetWidget__(_iWidget\*_ apWidget) -> _tBool_: Set the node's widget. 
- __iWidgetTreeNode::GetWidget__() -> _iWidget\*_: Get the node's widget. 
- __iWidgetTreeNode::SetTextColor__(_tU32_ anColor) -> _void_: Set the text foreground color. 
- __iWidgetTreeNode::GetTextColor__() -> _tU32_: Get the text foreground color. 
- __iWidgetTreeNode::SetTextBackColor__(_tU32_ anColor) -> _void_: Set the text background color. 
- __iWidgetTreeNode::GetTextBackColor__() -> _tU32_: Get the text background color. 
- __iWidgetTreeNode::SetRowColor__(_tU32_ anRow) -> _void_: Set an explicit row background color. 
- __iWidgetTreeNode::GetRowColor__() -> _tU32_: Get an explicit row background color. 
- __iWidgetTreeNode::SetAttributes__(_tU32_ anAttributes) -> _void_: Set the node's attributes. 
- __iWidgetTreeNode::GetAttributes__() -> _tU32_: Get the node's attributes. 
- __iWidgetTreeNode::SetVisibleAttributesMask__(_tU32_ anAttributes) -> _void_: Set the visible attributes mask. 
- __iWidgetTreeNode::GetVisibleAttributesMask__() -> _tU32_: Set the visible attributes mask. 

## interface ni::iWidgetTree
Widget tree interface. 

### Parents:
- iUnknown

### Methods:
- __iWidgetTree::GetRootNode__() -> _iWidgetTreeNode\*_: Get the root tree node. 
- __iWidgetTree::GetNumNodes__() -> _tU32_: Get the number of nodes. 
- __iWidgetTree::GetNode__(_tU32_ anIndex) -> _iWidgetTreeNode\*_: Get the node at the specified index. 
- __iWidgetTree::GetNumSelectedNodes__() -> _tU32_: Get the number of nodes selected. 
- __iWidgetTree::GetSelectedNode__(_tU32_ anIndex) -> _iWidgetTreeNode\*_: Get the selected node at the specified index. 
- __iWidgetTree::Clear__() -> _tBool_: Clear the tree. 
- __iWidgetTree::ClearSelection__() -> _tBool_: Clear the selection of all nodes. 
- __iWidgetTree::GetNodeFromPosition__(_const sVec2f&_ avAbsPos) -> _iWidgetTreeNode\*_: Get a node from an absolute position. 
- __iWidgetTree::GetNodeDropMode__(_iWidgetTreeNode\*_ apNode, _const sVec2f&_ avAbsPos) -> _eWidgetTreeNodeDropMode_: Get the drop mode of the specified node from the specified absolute position. 
- __iWidgetTree::SetSecondarySelection__(_iWidgetTreeNode\*_ apNode) -> _void_: Set the secondary selection item. 
- __iWidgetTree::GetSecondarySelection__() -> _iWidgetTreeNode\*_: Get the secondary selection item. 
- __iWidgetTree::GetPivotSelection__() -> _iWidgetTreeNode\*_: Get the pivot selection. 
- __iWidgetTree::ScrollToNode__(_iWidgetTreeNode\*_ apNode) -> _void_: Scroll to the specified item node. 
- __iWidgetTree::SaveTreeStates__(_iDataTable\*_ apStates) -> _tBool_: Save tree states. 
- __iWidgetTree::LoadTreeStates__(_iDataTable\*_ apStates, _ni::tBool_ abLoadMatchingNames) -> _tBool_: Load tree states. 
- __iWidgetTree::PushStates__() -> _tBool_: Push the tree's states. 
- __iWidgetTree::PopStates__(_ni::tBool_ abLoadMatchingNames) -> _tBool_: Pop the tree's states. 
- __iWidgetTree::SetNumVisibleAttributes__(_tU32_ anCount) -> _void_: Set the number of visible attributes. 
- __iWidgetTree::GetNumVisibleAttributes__() -> _tU32_: Get the number of visible attributes. 
- __iWidgetTree::SetAttributeIcon__(_tU32_ anIndex, _iOverlay\*_ apIcon) -> _void_: Set the specified attribute's icon. 
- __iWidgetTree::GetAttributeIcon__(_tU32_ anIndex) -> _iOverlay\*_: Get the specified attribute's icon. 
- __iWidgetTree::SetAttributeName__(_tU32_ anIndex, _iHString\*_ ahspName) -> _void_: Set the specified attribute's name. 
- __iWidgetTree::GetAttributeName__(_tU32_ anIndex) -> _iHString\*_: Get the specified attribute's name. 
- __iWidgetTree::SetHoverNode__(_tU32_ anNodeTreeIndex) -> _tBool_: Set the hover node. 
- __iWidgetTree::GetHoverNode__() -> _tU32_: Get the hover node. 

## enum ni::eWidgetTreeNodeDropMode
Widget tree node drop mode. 

### Values:
- __eWidgetTreeNodeDropMode_On__ = __0__: Drop on the node. 
- __eWidgetTreeNodeDropMode_Below__ = __1__: Drop below the node. 
- __eWidgetTreeNodeDropMode_Above__ = __2__: Drop above the node. 
- __eWidgetTreeNodeDropMode_Invalid__ = __3__: Invalid drop area. 

## enum ni::eUIMessage
UI message 

### Remarks:
- G, general messages 
- L, layout messages 
- P, painting/drawing messages 
- I, input messages 
- F, finger messages 
- A, action messages 
- C, click messages 
- S, serialization messages 
- Z, user messages 
- X, context messages, sent only to the root widget 

### Values:
- __eUIMessage_SinkAttached__ = __niMessageID('_','U','I','G',0)__: Message sent to the sink being added. 
- __eUIMessage_SinkDetached__ = __niMessageID('_','U','I','G',1)__: Message sent to the sink being removed. 
- __eUIMessage_ChildAdded__ = __niMessageID('_','U','I','G',2)__: A child widget has been added. 
- __eUIMessage_ChildRemoved__ = __niMessageID('_','U','I','G',3)__: A child widget has been removed. 
- __eUIMessage_Destroy__ = __niMessageID('_','U','I','G',4)__: The widget has been destroyed. 
- __eUIMessage_Notify__ = __niMessageID('_','U','I','G',5)__: Notification of message received by a child widget. 
- __eUIMessage_SetCursor__ = __niMessageID('_','U','I','G',6)__: Received when the widget should set the cursor. 
- __eUIMessage_SetFocus__ = __niMessageID('_','U','I','G',7)__: Received when the widget gets focus. 
- __eUIMessage_LostFocus__ = __niMessageID('_','U','I','G',8)__
- __eUIMessage_Activate__ = __niMessageID('_','U','I','G',9)__: The widget has been activated. 
- __eUIMessage_Deactivate__ = __niMessageID('_','U','I','G',10)__: The widget has been deactivated. 
- __eUIMessage_Command__ = __niMessageID('_','U','I','G',11)__: A child widget has send a command. 
- __eUIMessage_Timer__ = __niMessageID('_','U','I','G',12)__: Message sent when a timer expires. 
- __eUIMessage_Enabled__ = __niMessageID('_','U','I','G',13)__: Enabled message, sent when a widget is enabled or disabled. 
- __eUIMessage_Visible__ = __niMessageID('_','U','I','G',14)__: Visible message, sent when a widget is made visible or invisible. 
- __eUIMessage_Layout__ = __niMessageID('_','U','I','G',15)__: The widget should update its layout. 
- __eUIMessage_StyleChanged__ = __niMessageID('_','U','I','G',16)__: The widget's style has been changed. 
- __eUIMessage_FontChanged__ = __niMessageID('_','U','I','G',17)__: The widget's font has been changed. 
- __eUIMessage_TextChanged__ = __niMessageID('_','U','I','G',18)__: Text changed. 
- __eUIMessage_SetText__ = __niMessageID('_','U','I','G',19)__: Called when the text should be set, when iWidget::GetText is called. 
- __eUIMessage_SkinChanged__ = __niMessageID('_','U','I','G',20)__: Called when the skin is changed. 
- __eUIMessage_ContextMenuChanged__ = __niMessageID('_','U','I','G',21)__: The context menu has changed. 
- __eUIMessage_HoverTextChanged__ = __niMessageID('_','U','I','G',22)__: Hover text changed. 
- __eUIMessage_LoadConfig__ = __niMessageID('_','U','I','G',23)__: Configuration files should be loaded. 
- __eUIMessage_SaveConfig__ = __niMessageID('_','U','I','G',24)__: Configuration files should be saved. 
- __eUIMessage_ContextResized__ = __niMessageID('_','U','I','G',25)__: The context (root widget) has been resized. 
- __eUIMessage_LocaleChanged__ = __niMessageID('_','U','I','G',26)__: Locale has changed. 
- __eUIMessage_NCSize__ = __niMessageID('_','U','I','L',0)__: Non-client area resized. 
- __eUIMessage_Size__ = __niMessageID('_','U','I','L',1)__: Client area resized. 
- __eUIMessage_Padding__ = __niMessageID('_','U','I','L',2)__: The widget's padding has been modified. 
- __eUIMessage_Border__ = __niMessageID('_','U','I','L',3)__: The widget's border has been modified. 
- __eUIMessage_BorderStyle__ = __niMessageID('_','U','I','L',4)__: The widget's border style has been modified. 
- __eUIMessage_Margin__ = __niMessageID('_','U','I','L',5)__: The widget's margin has been modified. 
- __eUIMessage_MarginMerge__ = __niMessageID('_','U','I','L',6)__: The widget's margin merge has been modified. 
- __eUIMessage_Folded__ = __niMessageID('_','U','I','L',7)__: The widget has been folded. 
- __eUIMessage_Unfolded__ = __niMessageID('_','U','I','L',8)__: The widget has been unfolded. 
- __eUIMessage_BeforeDocked__ = __niMessageID('_','U','I','L',9)__: The widget has been docked or undocked. 
- __eUIMessage_AfterDocked__ = __niMessageID('_','U','I','L',10)__: The widget has been docked or undocked. 
- __eUIMessage_Undocked__ = __niMessageID('_','U','I','L',11)__: The widget has been docked or undocked. 
- __eUIMessage_NCPaint__ = __niMessageID('_','U','I','P',1)__: Draw the non-client area. 
- __eUIMessage_Paint__ = __niMessageID('_','U','I','P',2)__: Draw the client area. 
- __eUIMessage_NCLeftClickDown__ = __niMessageID('_','U','I','I',0)__: Left click down in the non-client area. 
- __eUIMessage_LeftClickDown__ = __niMessageID('_','U','I','I',1)__: Left click down in the client area. 
- __eUIMessage_NCLeftClickUp__ = __niMessageID('_','U','I','I',2)__: Left click up in the non-client area. 
- __eUIMessage_LeftClickUp__ = __niMessageID('_','U','I','I',3)__: Left click up in the client area. 
- __eUIMessage_NCRightClickDown__ = __niMessageID('_','U','I','I',4)__: Right click down in the non-client area. 
- __eUIMessage_RightClickDown__ = __niMessageID('_','U','I','I',5)__: Right click down in the client area. 
- __eUIMessage_NCRightClickUp__ = __niMessageID('_','U','I','I',6)__: Right click up in the non-client area. 
- __eUIMessage_RightClickUp__ = __niMessageID('_','U','I','I',7)__: Right click up in the client area. 
- __eUIMessage_NCMouseMove__ = __niMessageID('_','U','I','I',8)__: The cursor moved inside the non-client area. 
- __eUIMessage_MouseMove__ = __niMessageID('_','U','I','I',9)__: The cursor moved inside the client area. 
- __eUIMessage_NCWheel__ = __niMessageID('_','U','I','I',10)__: The wheel button has been pressed in the non client area. 
- __eUIMessage_Wheel__ = __niMessageID('_','U','I','I',11)__: The wheel button has been pressed in the client area. 
- __eUIMessage_KeyChar__ = __niMessageID('_','U','I','I',12)__: A character has been entered. 
- __eUIMessage_Submit__ = __niMessageID('_','U','I','I',13)__: Submit message. 
- __eUIMessage_NCMouseEnter__ = __niMessageID('_','U','I','I',15)__: Sent when the mouse enter the widget non-client area. 
- __eUIMessage_MouseEnter__ = __niMessageID('_','U','I','I',16)__: Sent when the mouse enter the widget client area. 
- __eUIMessage_NCMouseLeave__ = __niMessageID('_','U','I','I',17)__: Sent when the mouse leaves the widget non-client area. 
- __eUIMessage_MouseLeave__ = __niMessageID('_','U','I','I',18)__: Sent when the mouse leaves the widget client area. 
- __eUIMessage_NCMouseHover__ = __niMessageID('_','U','I','I',19)__: Sent when the mouse stand over the client area without moving for the time specified in the widget's hover delay. 
- __eUIMessage_MouseHover__ = __niMessageID('_','U','I','I',20)__: Sent when the mouse stand over the non-client area without moving for the time specified in the widget's hover delay. 
- __eUIMessage_NCDragMouseMove__ = __niMessageID('_','U','I','I',21)__: The cursor moved inside the non-client area when dragging an item. 
- __eUIMessage_DragMouseMove__ = __niMessageID('_','U','I','I',22)__: The cursor moved inside the client area when dragging an item. 
- __eUIMessage_NCDragMouseEnter__ = __niMessageID('_','U','I','I',23)__: Sent when the mouse enter the widget non-client area. 
- __eUIMessage_DragMouseEnter__ = __niMessageID('_','U','I','I',24)__: Sent when the mouse enter the widget client area. 
- __eUIMessage_NCDragMouseLeave__ = __niMessageID('_','U','I','I',25)__: Sent when the mouse leaves the widget non-client area. 
- __eUIMessage_DragMouseLeave__ = __niMessageID('_','U','I','I',26)__: Sent when the mouse leaves the widget client area. 
- __eUIMessage_NCDragBegin__ = __niMessageID('_','U','I','I',27)__: Sent when the mouse movement is considered to begin dragging in the non-client area. That is the left mouse button has been pressed and a movement of at least 'drag threshold' pixel has been made. 
- __eUIMessage_DragBegin__ = __niMessageID('_','U','I','I',28)__: Sent when the mouse movement is considered to begin dragging in the client area. That is the left mouse button has been pressed and a movement of at least 'drag threshold' pixel has been made. 
- __eUIMessage_NCDragEnd__ = __niMessageID('_','U','I','I',29)__: Sent when the drag button has been released, aka when the dragging ended in the non-client area. 
- __eUIMessage_DragEnd__ = __niMessageID('_','U','I','I',30)__: Sent when the drag button has been released, aka when the dragging ended. 
- __eUIMessage_KeyDown__ = __niMessageID('_','U','I','I',32)__: A key has been pressed. 
- __eUIMessage_KeyUp__ = __niMessageID('_','U','I','I',33)__: A key has been release. 
- __eUIMessage_GameCtrl__ = __niMessageID('_','U','I','I',34)__: A game controller's state changed. 
- __eUIMessage_GameCtrlButtonDown__ = __niMessageID('_','U','I','I',35)__: A game controller's button is down. 
- __eUIMessage_GameCtrlButtonUp__ = __niMessageID('_','U','I','I',36)__: A game controller's button is up. 
- __eUIMessage_NCFingerDown__ = __niMessageID('_','U','I','F',0)__: Finger down in the non-client area. 
- __eUIMessage_FingerDown__ = __niMessageID('_','U','I','F',1)__: Finger click down in the client area. 
- __eUIMessage_NCFingerUp__ = __niMessageID('_','U','I','F',2)__: Finger up in the non-client area. 
- __eUIMessage_FingerUp__ = __niMessageID('_','U','I','F',3)__: Finger click up in the client area. 
- __eUIMessage_NCFingerMove__ = __niMessageID('_','U','I','F',8)__: The finger moved inside the non-client area. 
- __eUIMessage_FingerMove__ = __niMessageID('_','U','I','F',9)__: The finger moved inside the client area. 
- __eUIMessage_NCFingerEnter__ = __niMessageID('_','U','I','F',15)__: Sent when a finger enter the widget non-client area. 
- __eUIMessage_FingerEnter__ = __niMessageID('_','U','I','F',16)__: Sent when a finger enter the widget client area. 
- __eUIMessage_NCFingerLeave__ = __niMessageID('_','U','I','F',17)__: Sent when a finger leaves the widget non-client area. 
- __eUIMessage_FingerLeave__ = __niMessageID('_','U','I','F',18)__: Sent when a finger leaves the widget client area. 
- __eUIMessage_NCDragFingerMove__ = __niMessageID('_','U','I','F',21)__: The cursor moved inside the non-client area when dragging an item. 
- __eUIMessage_DragFingerMove__ = __niMessageID('_','U','I','F',22)__: The cursor moved inside the client area when dragging an item. 
- __eUIMessage_NCDragFingerEnter__ = __niMessageID('_','U','I','F',23)__: Sent when a finger enter the widget non-client area. 
- __eUIMessage_DragFingerEnter__ = __niMessageID('_','U','I','F',24)__: Sent when a finger enter the widget client area. 
- __eUIMessage_NCDragFingerLeave__ = __niMessageID('_','U','I','F',25)__: Sent when a finger leaves the widget non-client area. 
- __eUIMessage_DragFingerLeave__ = __niMessageID('_','U','I','F',26)__: Sent when a finger leaves the widget client area. 
- __eUIMessage_NCDragFingerBegin__ = __niMessageID('_','U','I','F',27)__: Sent when a finger movement is considered to begin dragging in the non-client area. That is the left finger button has been pressed and a movement of at least 'drag threshold' pixel has been made. 
- __eUIMessage_DragFingerBegin__ = __niMessageID('_','U','I','F',28)__: Sent when a finger movement is considered to begin dragging in the client area. That is the left finger button has been pressed and a movement of at least 'drag threshold' pixel has been made. 
- __eUIMessage_NCDragFingerEnd__ = __niMessageID('_','U','I','F',29)__: Sent when the drag button has been released, aka when the dragging ended in the non-client area. 
- __eUIMessage_DragFingerEnd__ = __niMessageID('_','U','I','F',30)__: Sent when the drag button has been released, aka when the dragging ended. 
- __eUIMessage_NCFingerRelativeMove__ = __niMessageID('_','U','I','F',31)__: The finger moved inside the non-client area. 
- __eUIMessage_FingerRelativeMove__ = __niMessageID('_','U','I','F',32)__: The finger moved inside the client area. 
- __eUIMessage_Pinch__ = __niMessageID('_','U','I','F',33)__: Pinch gesture. 
- __eUIMessage_ContextMenu__ = __niMessageID('_','U','I','A',0)__: Sent when the context menu should be opened. 
- __eUIMessage_ContextHelp__ = __niMessageID('_','U','I','A',1)__: Context help. 
- __eUIMessage_Copy__ = __niMessageID('_','U','I','A',2)__: Copy. 
- __eUIMessage_Cut__ = __niMessageID('_','U','I','A',3)__: Cut. 
- __eUIMessage_Paste__ = __niMessageID('_','U','I','A',4)__: Paste. 
- __eUIMessage_Undo__ = __niMessageID('_','U','I','A',5)__: Undo. 
- __eUIMessage_Redo__ = __niMessageID('_','U','I','A',6)__: Redo. 
- __eUIMessage_MoveFocus__ = __niMessageID('_','U','I','A',7)__: Move focus. 
- __eUIMessage_Cancel__ = __niMessageID('_','U','I','A',8)__: Cancel message. 
- __eUIMessage_NCLeftClick__ = __niMessageID('_','U','I','C',0)__: Left click in the non-client area. 
- __eUIMessage_LeftClick__ = __niMessageID('_','U','I','C',1)__: Left click in the client area. 
- __eUIMessage_NCLeftDoubleClick__ = __niMessageID('_','U','I','C',2)__: Left double-click in the non-client area. 
- __eUIMessage_LeftDoubleClick__ = __niMessageID('_','U','I','C',3)__: Left double-click in the client area. 
- __eUIMessage_NCRightClick__ = __niMessageID('_','U','I','C',4)__: Right click in the non-client area. 
- __eUIMessage_RightClick__ = __niMessageID('_','U','I','C',5)__: Right click in the client area. 
- __eUIMessage_NCRightDoubleClick__ = __niMessageID('_','U','I','C',6)__: Right double-click in the non-client area. 
- __eUIMessage_RightDoubleClick__ = __niMessageID('_','U','I','C',7)__: Right double-click in the client area. 
- __eUIMessage_SerializeLayout__ = __niMessageID('_','U','I','S',0)__: SerializeLayout message. 
- __eUIMessage_SerializeWidget__ = __niMessageID('_','U','I','S',1)__: SerializeWidget message. 
- __eUIMessage_SerializeChildren__ = __niMessageID('_','U','I','S',2)__: SerializeChildren message. 
- __eUIMessage_SerializeFinalize__ = __niMessageID('_','U','I','S',3)__: SerializeFinalize message. 
- __eUIMessage_UserMessage__ = __niMessageID('_','U','I','Z',0)__: First user message id 
- __eUIMessage_ContextUpdate__ = __niMessageID('_','U','I','X','u')__: Sent after the context is updated. 
- __eUIMessage_ContextBeforeDraw__ = __niMessageID('_','U','I','X','d')__: Sent before the context is drawn. 
- __eUIMessage_ContextAfterDraw__ = __niMessageID('_','U','I','X','D')__: Sent after the context is drawn. 

## enum ni::eUIMessage
UI message 

### Remarks:
- G, general messages 
- L, layout messages 
- P, painting/drawing messages 
- I, input messages 
- F, finger messages 
- A, action messages 
- C, click messages 
- S, serialization messages 
- Z, user messages 
- X, context messages, sent only to the root widget 

### Values:
- __eUIMessage_SinkAttached__ = __niMessageID('_','U','I','G',0)__: Message sent to the sink being added. 
- __eUIMessage_SinkDetached__ = __niMessageID('_','U','I','G',1)__: Message sent to the sink being removed. 
- __eUIMessage_ChildAdded__ = __niMessageID('_','U','I','G',2)__: A child widget has been added. 
- __eUIMessage_ChildRemoved__ = __niMessageID('_','U','I','G',3)__: A child widget has been removed. 
- __eUIMessage_Destroy__ = __niMessageID('_','U','I','G',4)__: The widget has been destroyed. 
- __eUIMessage_Notify__ = __niMessageID('_','U','I','G',5)__: Notification of message received by a child widget. 
- __eUIMessage_SetCursor__ = __niMessageID('_','U','I','G',6)__: Received when the widget should set the cursor. 
- __eUIMessage_SetFocus__ = __niMessageID('_','U','I','G',7)__: Received when the widget gets focus. 
- __eUIMessage_LostFocus__ = __niMessageID('_','U','I','G',8)__
- __eUIMessage_Activate__ = __niMessageID('_','U','I','G',9)__: The widget has been activated. 
- __eUIMessage_Deactivate__ = __niMessageID('_','U','I','G',10)__: The widget has been deactivated. 
- __eUIMessage_Command__ = __niMessageID('_','U','I','G',11)__: A child widget has send a command. 
- __eUIMessage_Timer__ = __niMessageID('_','U','I','G',12)__: Message sent when a timer expires. 
- __eUIMessage_Enabled__ = __niMessageID('_','U','I','G',13)__: Enabled message, sent when a widget is enabled or disabled. 
- __eUIMessage_Visible__ = __niMessageID('_','U','I','G',14)__: Visible message, sent when a widget is made visible or invisible. 
- __eUIMessage_Layout__ = __niMessageID('_','U','I','G',15)__: The widget should update its layout. 
- __eUIMessage_StyleChanged__ = __niMessageID('_','U','I','G',16)__: The widget's style has been changed. 
- __eUIMessage_FontChanged__ = __niMessageID('_','U','I','G',17)__: The widget's font has been changed. 
- __eUIMessage_TextChanged__ = __niMessageID('_','U','I','G',18)__: Text changed. 
- __eUIMessage_SetText__ = __niMessageID('_','U','I','G',19)__: Called when the text should be set, when iWidget::GetText is called. 
- __eUIMessage_SkinChanged__ = __niMessageID('_','U','I','G',20)__: Called when the skin is changed. 
- __eUIMessage_ContextMenuChanged__ = __niMessageID('_','U','I','G',21)__: The context menu has changed. 
- __eUIMessage_HoverTextChanged__ = __niMessageID('_','U','I','G',22)__: Hover text changed. 
- __eUIMessage_LoadConfig__ = __niMessageID('_','U','I','G',23)__: Configuration files should be loaded. 
- __eUIMessage_SaveConfig__ = __niMessageID('_','U','I','G',24)__: Configuration files should be saved. 
- __eUIMessage_ContextResized__ = __niMessageID('_','U','I','G',25)__: The context (root widget) has been resized. 
- __eUIMessage_LocaleChanged__ = __niMessageID('_','U','I','G',26)__: Locale has changed. 
- __eUIMessage_NCSize__ = __niMessageID('_','U','I','L',0)__: Non-client area resized. 
- __eUIMessage_Size__ = __niMessageID('_','U','I','L',1)__: Client area resized. 
- __eUIMessage_Padding__ = __niMessageID('_','U','I','L',2)__: The widget's padding has been modified. 
- __eUIMessage_Border__ = __niMessageID('_','U','I','L',3)__: The widget's border has been modified. 
- __eUIMessage_BorderStyle__ = __niMessageID('_','U','I','L',4)__: The widget's border style has been modified. 
- __eUIMessage_Margin__ = __niMessageID('_','U','I','L',5)__: The widget's margin has been modified. 
- __eUIMessage_MarginMerge__ = __niMessageID('_','U','I','L',6)__: The widget's margin merge has been modified. 
- __eUIMessage_Folded__ = __niMessageID('_','U','I','L',7)__: The widget has been folded. 
- __eUIMessage_Unfolded__ = __niMessageID('_','U','I','L',8)__: The widget has been unfolded. 
- __eUIMessage_BeforeDocked__ = __niMessageID('_','U','I','L',9)__: The widget has been docked or undocked. 
- __eUIMessage_AfterDocked__ = __niMessageID('_','U','I','L',10)__: The widget has been docked or undocked. 
- __eUIMessage_Undocked__ = __niMessageID('_','U','I','L',11)__: The widget has been docked or undocked. 
- __eUIMessage_NCPaint__ = __niMessageID('_','U','I','P',1)__: Draw the non-client area. 
- __eUIMessage_Paint__ = __niMessageID('_','U','I','P',2)__: Draw the client area. 
- __eUIMessage_NCLeftClickDown__ = __niMessageID('_','U','I','I',0)__: Left click down in the non-client area. 
- __eUIMessage_LeftClickDown__ = __niMessageID('_','U','I','I',1)__: Left click down in the client area. 
- __eUIMessage_NCLeftClickUp__ = __niMessageID('_','U','I','I',2)__: Left click up in the non-client area. 
- __eUIMessage_LeftClickUp__ = __niMessageID('_','U','I','I',3)__: Left click up in the client area. 
- __eUIMessage_NCRightClickDown__ = __niMessageID('_','U','I','I',4)__: Right click down in the non-client area. 
- __eUIMessage_RightClickDown__ = __niMessageID('_','U','I','I',5)__: Right click down in the client area. 
- __eUIMessage_NCRightClickUp__ = __niMessageID('_','U','I','I',6)__: Right click up in the non-client area. 
- __eUIMessage_RightClickUp__ = __niMessageID('_','U','I','I',7)__: Right click up in the client area. 
- __eUIMessage_NCMouseMove__ = __niMessageID('_','U','I','I',8)__: The cursor moved inside the non-client area. 
- __eUIMessage_MouseMove__ = __niMessageID('_','U','I','I',9)__: The cursor moved inside the client area. 
- __eUIMessage_NCWheel__ = __niMessageID('_','U','I','I',10)__: The wheel button has been pressed in the non client area. 
- __eUIMessage_Wheel__ = __niMessageID('_','U','I','I',11)__: The wheel button has been pressed in the client area. 
- __eUIMessage_KeyChar__ = __niMessageID('_','U','I','I',12)__: A character has been entered. 
- __eUIMessage_Submit__ = __niMessageID('_','U','I','I',13)__: Submit message. 
- __eUIMessage_NCMouseEnter__ = __niMessageID('_','U','I','I',15)__: Sent when the mouse enter the widget non-client area. 
- __eUIMessage_MouseEnter__ = __niMessageID('_','U','I','I',16)__: Sent when the mouse enter the widget client area. 
- __eUIMessage_NCMouseLeave__ = __niMessageID('_','U','I','I',17)__: Sent when the mouse leaves the widget non-client area. 
- __eUIMessage_MouseLeave__ = __niMessageID('_','U','I','I',18)__: Sent when the mouse leaves the widget client area. 
- __eUIMessage_NCMouseHover__ = __niMessageID('_','U','I','I',19)__: Sent when the mouse stand over the client area without moving for the time specified in the widget's hover delay. 
- __eUIMessage_MouseHover__ = __niMessageID('_','U','I','I',20)__: Sent when the mouse stand over the non-client area without moving for the time specified in the widget's hover delay. 
- __eUIMessage_NCDragMouseMove__ = __niMessageID('_','U','I','I',21)__: The cursor moved inside the non-client area when dragging an item. 
- __eUIMessage_DragMouseMove__ = __niMessageID('_','U','I','I',22)__: The cursor moved inside the client area when dragging an item. 
- __eUIMessage_NCDragMouseEnter__ = __niMessageID('_','U','I','I',23)__: Sent when the mouse enter the widget non-client area. 
- __eUIMessage_DragMouseEnter__ = __niMessageID('_','U','I','I',24)__: Sent when the mouse enter the widget client area. 
- __eUIMessage_NCDragMouseLeave__ = __niMessageID('_','U','I','I',25)__: Sent when the mouse leaves the widget non-client area. 
- __eUIMessage_DragMouseLeave__ = __niMessageID('_','U','I','I',26)__: Sent when the mouse leaves the widget client area. 
- __eUIMessage_NCDragBegin__ = __niMessageID('_','U','I','I',27)__: Sent when the mouse movement is considered to begin dragging in the non-client area. That is the left mouse button has been pressed and a movement of at least 'drag threshold' pixel has been made. 
- __eUIMessage_DragBegin__ = __niMessageID('_','U','I','I',28)__: Sent when the mouse movement is considered to begin dragging in the client area. That is the left mouse button has been pressed and a movement of at least 'drag threshold' pixel has been made. 
- __eUIMessage_NCDragEnd__ = __niMessageID('_','U','I','I',29)__: Sent when the drag button has been released, aka when the dragging ended in the non-client area. 
- __eUIMessage_DragEnd__ = __niMessageID('_','U','I','I',30)__: Sent when the drag button has been released, aka when the dragging ended. 
- __eUIMessage_KeyDown__ = __niMessageID('_','U','I','I',32)__: A key has been pressed. 
- __eUIMessage_KeyUp__ = __niMessageID('_','U','I','I',33)__: A key has been release. 
- __eUIMessage_GameCtrl__ = __niMessageID('_','U','I','I',34)__: A game controller's state changed. 
- __eUIMessage_GameCtrlButtonDown__ = __niMessageID('_','U','I','I',35)__: A game controller's button is down. 
- __eUIMessage_GameCtrlButtonUp__ = __niMessageID('_','U','I','I',36)__: A game controller's button is up. 
- __eUIMessage_NCFingerDown__ = __niMessageID('_','U','I','F',0)__: Finger down in the non-client area. 
- __eUIMessage_FingerDown__ = __niMessageID('_','U','I','F',1)__: Finger click down in the client area. 
- __eUIMessage_NCFingerUp__ = __niMessageID('_','U','I','F',2)__: Finger up in the non-client area. 
- __eUIMessage_FingerUp__ = __niMessageID('_','U','I','F',3)__: Finger click up in the client area. 
- __eUIMessage_NCFingerMove__ = __niMessageID('_','U','I','F',8)__: The finger moved inside the non-client area. 
- __eUIMessage_FingerMove__ = __niMessageID('_','U','I','F',9)__: The finger moved inside the client area. 
- __eUIMessage_NCFingerEnter__ = __niMessageID('_','U','I','F',15)__: Sent when a finger enter the widget non-client area. 
- __eUIMessage_FingerEnter__ = __niMessageID('_','U','I','F',16)__: Sent when a finger enter the widget client area. 
- __eUIMessage_NCFingerLeave__ = __niMessageID('_','U','I','F',17)__: Sent when a finger leaves the widget non-client area. 
- __eUIMessage_FingerLeave__ = __niMessageID('_','U','I','F',18)__: Sent when a finger leaves the widget client area. 
- __eUIMessage_NCDragFingerMove__ = __niMessageID('_','U','I','F',21)__: The cursor moved inside the non-client area when dragging an item. 
- __eUIMessage_DragFingerMove__ = __niMessageID('_','U','I','F',22)__: The cursor moved inside the client area when dragging an item. 
- __eUIMessage_NCDragFingerEnter__ = __niMessageID('_','U','I','F',23)__: Sent when a finger enter the widget non-client area. 
- __eUIMessage_DragFingerEnter__ = __niMessageID('_','U','I','F',24)__: Sent when a finger enter the widget client area. 
- __eUIMessage_NCDragFingerLeave__ = __niMessageID('_','U','I','F',25)__: Sent when a finger leaves the widget non-client area. 
- __eUIMessage_DragFingerLeave__ = __niMessageID('_','U','I','F',26)__: Sent when a finger leaves the widget client area. 
- __eUIMessage_NCDragFingerBegin__ = __niMessageID('_','U','I','F',27)__: Sent when a finger movement is considered to begin dragging in the non-client area. That is the left finger button has been pressed and a movement of at least 'drag threshold' pixel has been made. 
- __eUIMessage_DragFingerBegin__ = __niMessageID('_','U','I','F',28)__: Sent when a finger movement is considered to begin dragging in the client area. That is the left finger button has been pressed and a movement of at least 'drag threshold' pixel has been made. 
- __eUIMessage_NCDragFingerEnd__ = __niMessageID('_','U','I','F',29)__: Sent when the drag button has been released, aka when the dragging ended in the non-client area. 
- __eUIMessage_DragFingerEnd__ = __niMessageID('_','U','I','F',30)__: Sent when the drag button has been released, aka when the dragging ended. 
- __eUIMessage_NCFingerRelativeMove__ = __niMessageID('_','U','I','F',31)__: The finger moved inside the non-client area. 
- __eUIMessage_FingerRelativeMove__ = __niMessageID('_','U','I','F',32)__: The finger moved inside the client area. 
- __eUIMessage_Pinch__ = __niMessageID('_','U','I','F',33)__: Pinch gesture. 
- __eUIMessage_ContextMenu__ = __niMessageID('_','U','I','A',0)__: Sent when the context menu should be opened. 
- __eUIMessage_ContextHelp__ = __niMessageID('_','U','I','A',1)__: Context help. 
- __eUIMessage_Copy__ = __niMessageID('_','U','I','A',2)__: Copy. 
- __eUIMessage_Cut__ = __niMessageID('_','U','I','A',3)__: Cut. 
- __eUIMessage_Paste__ = __niMessageID('_','U','I','A',4)__: Paste. 
- __eUIMessage_Undo__ = __niMessageID('_','U','I','A',5)__: Undo. 
- __eUIMessage_Redo__ = __niMessageID('_','U','I','A',6)__: Redo. 
- __eUIMessage_MoveFocus__ = __niMessageID('_','U','I','A',7)__: Move focus. 
- __eUIMessage_Cancel__ = __niMessageID('_','U','I','A',8)__: Cancel message. 
- __eUIMessage_NCLeftClick__ = __niMessageID('_','U','I','C',0)__: Left click in the non-client area. 
- __eUIMessage_LeftClick__ = __niMessageID('_','U','I','C',1)__: Left click in the client area. 
- __eUIMessage_NCLeftDoubleClick__ = __niMessageID('_','U','I','C',2)__: Left double-click in the non-client area. 
- __eUIMessage_LeftDoubleClick__ = __niMessageID('_','U','I','C',3)__: Left double-click in the client area. 
- __eUIMessage_NCRightClick__ = __niMessageID('_','U','I','C',4)__: Right click in the non-client area. 
- __eUIMessage_RightClick__ = __niMessageID('_','U','I','C',5)__: Right click in the client area. 
- __eUIMessage_NCRightDoubleClick__ = __niMessageID('_','U','I','C',6)__: Right double-click in the non-client area. 
- __eUIMessage_RightDoubleClick__ = __niMessageID('_','U','I','C',7)__: Right double-click in the client area. 
- __eUIMessage_SerializeLayout__ = __niMessageID('_','U','I','S',0)__: SerializeLayout message. 
- __eUIMessage_SerializeWidget__ = __niMessageID('_','U','I','S',1)__: SerializeWidget message. 
- __eUIMessage_SerializeChildren__ = __niMessageID('_','U','I','S',2)__: SerializeChildren message. 
- __eUIMessage_SerializeFinalize__ = __niMessageID('_','U','I','S',3)__: SerializeFinalize message. 
- __eUIMessage_UserMessage__ = __niMessageID('_','U','I','Z',0)__: First user message id 
- __eUIMessage_ContextUpdate__ = __niMessageID('_','U','I','X','u')__: Sent after the context is updated. 
- __eUIMessage_ContextBeforeDraw__ = __niMessageID('_','U','I','X','d')__: Sent before the context is drawn. 
- __eUIMessage_ContextAfterDraw__ = __niMessageID('_','U','I','X','D')__: Sent after the context is drawn. 
