# wrm3_term_colors

> A terminal printing library that adds more color options.

## Features

- Supports 147 HTML5 named colors.
- Supports 16,777,216 hex colors for font color and 16,777,216 for background color.
- Easy-to-use functions for printing colored text.
- Customizable text styles like bold and italic.
- Compatible with Windows Terminal and VSCode.

## Installation



## Example Usage

from wrm3_term_color import cs, cp, CLR

r1 = cs(text='this is white font on a green background', font_color='white', bg_color='red')
r2 = cs(text='this is white font on a red background', font_color='white', bg_color='red')
msg = f'this is them merged on the same line {r1} {r2}'
print(msg)

cp(text='this is Yellow font on Magenta Background', font_color='yellow', bg_color='magenta')

cp(text='this is Yellow font centered on a 150 long Magenta Background', font_color='yellow', bg_color='magenta', align='center', length=150)

***

cp(text='this is papayawhip font centered on tomator Background', font_color='papayawhip', bg_color='papayawhip')

See bottom for named colors list...

***

cp(text='this is #CC3300 font centered on #0033CC Background', font_color='#CC3300', bg_color='#0033CC')

***

from wrm3_term_color import *

G('this prints green text')
B('this prints blue text')
R('this prints red text')

***

K => prints black text
R => prints red
G => prints green
Y => prints yellow
B => prints blue
M => prints magenta
C => prints cyan
W => prints white
LGy => prints light_grey
DGy => prints dark_grey
LR => prints light_red
LG => prints light_green
LY => prints light_yellow
LB => prints light_blue
LM => prints light_magenta
LC => prints light_cyan

***

KoK => prints black text on a black background...
RoK => prints red text on a black background...
GoK => prints green text on a black background...
YoK => prints yellow text on a black background...
BoK => prints blue text on a black background...
MoK => prints magenta text on a black background...
CoK => prints cyan text on a black background...
WoK => prints white text on a black background...
LGyoK => prints light_grey text on a black background...
DGyoK => prints dark_grey text on a black background...
LRoK => prints light_red text on a black background...
LGoK => prints light_green text on a black background...
LYoK => prints light_yellow text on a black background...
LBoK => prints light_blue text on a black background...
LMoK => prints light_magenta text on a black background...
LCoK => prints light_cyan text on a black background...

***

KoR => prints black text on a red background...
RoR => prints red text on a red background...
GoR => prints green text on a red background...
YoR => prints yellow text on a red background...
BoR => prints blue text on a red background...
MoR => prints magenta text on a red background...
CoR => prints cyan text on a red background...
WoR => prints white text on a red background...
LGyoR => prints light_grey text on a red background...
DGyoR => prints dark_grey text on a red background...
LRoR => prints light_red text on a red background...
LGoR => prints light_green text on a red background...
LYoR => prints light_yellow text on a red background...
LBoR => prints light_blue text on a red background...
LMoR => prints light_magenta text on a red background...
LCoR => prints light_cyan text on a red background...

***

KoG => prints black text on a green background...
RoG => prints red text on a green background...
GoG => prints green text on a green background...
YoG => prints yellow text on a green background...
BoG => prints blue text on a green background...
MoG => prints magenta text on a green background...
CoG => prints cyan text on a green background...
WoG => prints white text on a green background...
LGyoG => prints light_grey text on a green background...
DGyoG => prints dark_grey text on a green background...
LRoG => prints light_red text on a green background...
LGoG => prints light_green text on a green background...
LYoG => prints light_yellow text on a green background...
LBoG => prints light_blue text on a green background...
LMoG => prints light_magenta text on a green background...
LCoG => prints light_cyan text on a green background...

***

KoY => prints black text on a yellow background...
RoY => prints red text on a yellow background...
GoY => prints green text on a yellow background...
YoY => prints yellow text on a yellow background...
BoY => prints blue text on a yellow background...
MoY => prints magenta text on a yellow background...
CoY => prints cyan text on a yellow background...
WoY => prints white text on a yellow background...
LGyoY => prints light_grey text on a yellow background...
DGyoY => prints dark_grey text on a yellow background...
LRoY => prints light_red text on a yellow background...
LGoY => prints light_green text on a yellow background...
LYoY => prints light_yellow text on a yellow background...
LBoY => prints light_blue text on a yellow background...
LMoY => prints light_magenta text on a yellow background...
LCoY => prints light_cyan text on a yellow background...

***

KoB => prints black text on a blue background...
RoB => prints red text on a blue background...
GoB => prints green text on a blue background...
YoB => prints yellow text on a blue background...
BoB => prints blue text on a blue background...
MoB => prints magenta text on a blue background...
CoB => prints cyan text on a blue background...
WoB => prints white text on a blue background...
LGyoB => prints light_grey text on a blue background...
DGyoB => prints dark_grey text on a blue background...
LRoB => prints light_red text on a blue background...
LGoB => prints light_green text on a blue background...
LYoB => prints light_yellow text on a blue background...
LBoB => prints light_blue text on a blue background...
LMoB => prints light_magenta text on a blue background...
LCoB => prints light_cyan text on a blue background...

***

KoM => prints black text on a magenta background...
RoM => prints red text on a magenta background...
GoM => prints green text on a magenta background...
YoM => prints yellow text on a magenta background...
BoM => prints blue text on a magenta background...
MoM => prints magenta text on a magenta background...
CoM => prints cyan text on a magenta background...
WoM => prints white text on a magenta background...
LGyoM => prints light_grey text on a magenta background...
DGyoM => prints dark_grey text on a magenta background...
LRoM => prints light_red text on a magenta background...
LGoM => prints light_green text on a magenta background...
LYoM => prints light_yellow text on a magenta background...
LBoM => prints light_blue text on a magenta background...
LMoM => prints light_magenta text on a magenta background...
LCoM => prints light_cyan text on a magenta background...

***

KoC => prints black text on a cyan background...
RoC => prints red text on a cyan background...
GoC => prints green text on a cyan background...
YoC => prints yellow text on a cyan background...
BoC => prints blue text on a cyan background...
MoC => prints magenta text on a cyan background...
CoC => prints cyan text on a cyan background...
WoC => prints white text on a cyan background...
LGyoC => prints light_grey text on a cyan background...
DGyoC => prints dark_grey text on a cyan background...
LRoC => prints light_red text on a cyan background...
LGoC => prints light_green text on a cyan background...
LYoC => prints light_yellow text on a cyan background...
LBoC => prints light_blue text on a cyan background...
LMoC => prints light_magenta text on a cyan background...
LCoC => prints light_cyan text on a cyan background...

***

KoW => prints black text on a white background...
RoW => prints red text on a white background...
GoW => prints green text on a white background...
YoW => prints yellow text on a white background...
BoW => prints blue text on a white background...
MoW => prints magenta text on a white background...
CoW => prints cyan text on a white background...
WoW => prints white text on a white background...
LGyoW => prints light_grey text on a white background...
DGyoW => prints dark_grey text on a white background...
LRoW => prints light_red text on a white background...
LGoW => prints light_green text on a white background...
LYoW => prints light_yellow text on a white background...
LBoW => prints light_blue text on a white background...
LMoW => prints light_magenta text on a white background...
LCoW => prints light_cyan text on a white background...

***

KoLGy => prints black text on a light_grey background...
RoLGy => prints red text on a light_grey background...
GoLGy => prints green text on a light_grey background...
YoLGy => prints yellow text on a light_grey background...
BoLGy => prints blue text on a light_grey background...
MoLGy => prints magenta text on a light_grey background...
CoLGy => prints cyan text on a light_grey background...
WoLGy => prints white text on a light_grey background...
LGyoLGy => prints light_grey text on a light_grey background...
DGyoLGy => prints dark_grey text on a light_grey background...
LRoLGy => prints light_red text on a light_grey background...
LGoLGy => prints light_green text on a light_grey background...
LYoLGy => prints light_yellow text on a light_grey background...
LBoLGy => prints light_blue text on a light_grey background...
LMoLGy => prints light_magenta text on a light_grey background...
LCoLGy => prints light_cyan text on a light_grey background...

***

KoDGy => prints black text on a dark_grey background...
RoDGy => prints red text on a dark_grey background...
GoDGy => prints green text on a dark_grey background...
YoDGy => prints yellow text on a dark_grey background...
BoDGy => prints blue text on a dark_grey background...
MoDGy => prints magenta text on a dark_grey background...
CoDGy => prints cyan text on a dark_grey background...
WoDGy => prints white text on a dark_grey background...
LGyoDGy => prints light_grey text on a dark_grey background...
DGyoDGy => prints dark_grey text on a dark_grey background...
LRoDGy => prints light_red text on a dark_grey background...
LGoDGy => prints light_green text on a dark_grey background...
LYoDGy => prints light_yellow text on a dark_grey background...
LBoDGy => prints light_blue text on a dark_grey background...
LMoDGy => prints light_magenta text on a dark_grey background...
LCoDGy => prints light_cyan text on a dark_grey background...

***

KoLR => prints black text on a light_red background...
RoLR => prints red text on a light_red background...
GoLR => prints green text on a light_red background...
YoLR => prints yellow text on a light_red background...
BoLR => prints blue text on a light_red background...
MoLR => prints magenta text on a light_red background...
CoLR => prints cyan text on a light_red background...
WoLR => prints white text on a light_red background...
LGyoLR => prints light_grey text on a light_red background...
DGyoLR => prints dark_grey text on a light_red background...
LRoLR => prints light_red text on a light_red background...
LGoLR => prints light_green text on a light_red background...
LYoLR => prints light_yellow text on a light_red background...
LBoLR => prints light_blue text on a light_red background...
LMoLR => prints light_magenta text on a light_red background...
LCoLR => prints light_cyan text on a light_red background...

***

KoLG => prints black text on a light_green background...
RoLG => prints red text on a light_green background...
GoLG => prints green text on a light_green background...
YoLG => prints yellow text on a light_green background...
BoLG => prints blue text on a light_green background...
MoLG => prints magenta text on a light_green background...
CoLG => prints cyan text on a light_green background...
WoLG => prints white text on a light_green background...
LGyoLG => prints light_grey text on a light_green background...
DGyoLG => prints dark_grey text on a light_green background...
LRoLG => prints light_red text on a light_green background...
LGoLG => prints light_green text on a light_green background...
LYoLG => prints light_yellow text on a light_green background...
LBoLG => prints light_blue text on a light_green background...
LMoLG => prints light_magenta text on a light_green background...
LCoLG => prints light_cyan text on a light_green background...

***

KoLY => prints black text on a light_yellow background...
RoLY => prints red text on a light_yellow background...
GoLY => prints green text on a light_yellow background...
YoLY => prints yellow text on a light_yellow background...
BoLY => prints blue text on a light_yellow background...
MoLY => prints magenta text on a light_yellow background...
CoLY => prints cyan text on a light_yellow background...
WoLY => prints white text on a light_yellow background...
LGyoLY => prints light_grey text on a light_yellow background...
DGyoLY => prints dark_grey text on a light_yellow background...
LRoLY => prints light_red text on a light_yellow background...
LGoLY => prints light_green text on a light_yellow background...
LYoLY => prints light_yellow text on a light_yellow background...
LBoLY => prints light_blue text on a light_yellow background...
LMoLY => prints light_magenta text on a light_yellow background...
LCoLY => prints light_cyan text on a light_yellow background...

***

KoLB => prints black text on a light_blue background...
RoLB => prints red text on a light_blue background...
GoLB => prints green text on a light_blue background...
YoLB => prints yellow text on a light_blue background...
BoLB => prints blue text on a light_blue background...
MoLB => prints magenta text on a light_blue background...
CoLB => prints cyan text on a light_blue background...
WoLB => prints white text on a light_blue background...
LGyoLB => prints light_grey text on a light_blue background...
DGyoLB => prints dark_grey text on a light_blue background...
LRoLB => prints light_red text on a light_blue background...
LGoLB => prints light_green text on a light_blue background...
LYoLB => prints light_yellow text on a light_blue background...
LBoLB => prints light_blue text on a light_blue background...
LMoLB => prints light_magenta text on a light_blue background...
LCoLB => prints light_cyan text on a light_blue background...

***

KoLM => prints black text on a light_magenta background...
RoLM => prints red text on a light_magenta background...
GoLM => prints green text on a light_magenta background...
YoLM => prints yellow text on a light_magenta background...
BoLM => prints blue text on a light_magenta background...
MoLM => prints magenta text on a light_magenta background...
CoLM => prints cyan text on a light_magenta background...
WoLM => prints white text on a light_magenta background...
LGyoLM => prints light_grey text on a light_magenta background...
DGyoLM => prints dark_grey text on a light_magenta background...
LRoLM => prints light_red text on a light_magenta background...
LGoLM => prints light_green text on a light_magenta background...
LYoLM => prints light_yellow text on a light_magenta background...
LBoLM => prints light_blue text on a light_magenta background...
LMoLM => prints light_magenta text on a light_magenta background...
LCoLM => prints light_cyan text on a light_magenta background...

***

KoLC => prints black text on a light_cyan background...
RoLC => prints red text on a light_cyan background...
GoLC => prints green text on a light_cyan background...
YoLC => prints yellow text on a light_cyan background...
BoLC => prints blue text on a light_cyan background...
MoLC => prints magenta text on a light_cyan background...
CoLC => prints cyan text on a light_cyan background...
WoLC => prints white text on a light_cyan background...
LGyoLC => prints light_grey text on a light_cyan background...
DGyoLC => prints dark_grey text on a light_cyan background...
LRoLC => prints light_red text on a light_cyan background...
LGoLC => prints light_green text on a light_cyan background...
LYoLC => prints light_yellow text on a light_cyan background...
LBoLC => prints light_blue text on a light_cyan background...
LMoLC => prints light_magenta text on a light_cyan background...
LCoLC => prints light_cyan text on a light_cyan background...

***


# Reds Named
	indianred             = "#CD5C5C"      # indianred                             #CD5C5C  205   92   92  389
	lightcoral            = "#F08080"      # lightcoral                            #F08080  240  128  128  496
	salmon                = "#FA8072"      # salmon                                #FA8072  250  128  114  492
	darksalmon            = "#E9967A"      # darksalmon                            #E9967A  233  150  122  505
	crimson               = "#DC143C"      # crimson                               #DC143C  220   20   60  300
	red                   = "#FF0000"      # red                                   #FF0000  255    0    0  255
	firebrick             = "#B22222"      # firebrick                             #B22222  178   34   34  246
	darkred               = "#8B0000"      # darkred                               #8B0000  139    0    0  139

# Pinks Named
	pink                  = "#FFC0CB"      # pink                                  #FFC0CB  255  192  203  650
	lightpink             = "#FFB6C1"      # lightpink                             #FFB6C1  255  182  193  630
	hotpink               = "#FF69B4"      # hotpink                               #FF69B4  255  105  180  540
	deeppink              = "#FF1493"      # deeppink                              #FF1493  255   20  147  422
	mediumvioletred       = "#C71585"      # mediumvioletred                       #C71585  199   21  133  353
	palevioletred         = "#DB7093"      # palevioletred                         #DB7093  219  112  147  478

# Oranges Named
	coral                 = "#FF7F50"      # coral                                 #FF7F50  255  127   80  462
	tomato                = "#FF6347"      # tomato                                #FF6347  255   99   71  425
	orangered             = "#FF4500"      # orangered                             #FF4500  255   69    0  324
	darkorange            = "#FF8C00"      # darkorange                            #FF8C00  255  140    0  395
	orange                = "#FFA500"      # orange                                #FFA500  255  165    0  420

# Yellows Named
	gold                  = "#FFD700"      # gold                                  #FFD700  255  215    0  470
	yellow                = "#FFFF00"      # yellow                                #FFFF00  255  255    0  510
	lightyellow           = "#FFFFE0"      # lightyellow                           #FFFFE0  255  255  224  734
	lemonchiffon          = "#FFFACD"      # lemonchiffon                          #FFFACD  255  250  205  710
	lightgoldenrodyellow  = "#FAFAD2"      # lightgoldenrodyellow                  #FAFAD2  250  250  210  710
	papayawhip            = "#FFEFD5"      # papayawhip                            #FFEFD5  255  239  213  707
	moccasin              = "#FFE4B5"      # moccasin                              #FFE4B5  255  228  181  664
	peachpuff             = "#FFDAB9"      # peachpuff                             #FFDAB9  255  218  185  658
	palegoldenrod         = "#EEE8AA"      # palegoldenrod                         #EEE8AA  238  232  170  640
	darkkhaki             = "#BDB76B"      # darkkhaki                             #BDB76B  189  183  107  479
	khaki                 = "#F0E68C"      # khaki                                 #F0E68C  240  230  140  610

# Purples Named
	lavender              = "#E6E6FA"      # lavender                              #E6E6FA  230  230  250  710
	thistle               = "#D8BFD8"      # thistle                               #D8BFD8  216  191  216  623
	plum                  = "#DDA0DD"      # plum                                  #DDA0DD  221  160  221  602
	violet                = "#EE82EE"      # violet                                #EE82EE  238  130  238  606
	orchid                = "#DA70D6"      # orchid                                #DA70D6  218  112  214  544
	fuchsia               = "#FF00FF"      # fuchsia                               #FF00FF  255    0  255  510
	magenta               = "#FF00FF"      # magenta                               #FF00FF  255    0  255  510
	mediumorchid          = "#BA55D3"      # mediumorchid                          #BA55D3  186   85  211  482
	mediumpurple          = "#9370DB"      # mediumpurple                          #9370DB  147  112  219  478
	rebeccapurple         = "#663399"      # rebeccapurple                         #663399  102   51  153  306
	blueviolet            = "#8A2BE2"      # blueviolet                            #8A2BE2  138   43  226  407
	darkviolet            = "#9400D3"      # darkviolet                            #9400D3  148    0  211  359
	darkorchid            = "#9932CC"      # darkorchid                            #9932CC  153   50  204  407
	darkmagenta           = "#8B008B"      # darkmagenta                           #8B008B  139    0  139  278
	purple                = "#800080"      # purple                                #800080  128    0  128  256
	indigo                = "#4B0082"      # indigo                                #4B0082   75    0  130  205
	slateblue             = "#6A5ACD"      # slateblue                             #6A5ACD  106   90  205  401
	darkslateblue         = "#483D8B"      # darkslateblue                         #483D8B   72   61  139  272
	mediumslateblue       = "#7B68EE"      # mediumslateblue                       #7B68EE  123  104  238  465

# Greens Named
	greenyellow           = "#ADFF2F"      # greenyellow                           #ADFF2F  173  255   47  475
	chartreuse            = "#7FFF00"      # chartreuse                            #7FFF00  127  255    0  382
	lawngreen             = "#7CFC00"      # lawngreen                             #7CFC00  124  252    0  376
	lime                  = "#00FF00"      # lime                                  #00FF00    0  255    0  255
	limegreen             = "#32CD32"      # limegreen                             #32CD32   50  205   50  305
	palegreen             = "#98FB98"      # palegreen                             #98FB98  152  251  152  555
	lightgreen            = "#90EE90"      # lightgreen                            #90EE90  144  238  144  526
	mediumspringgreen     = "#00FA9A"      # mediumspringgreen                     #00FA9A    0  250  154  404
	springgreen           = "#00FF7F"      # springgreen                           #00FF7F    0  255  127  382
	mediumseagreen        = "#3CB371"      # mediumseagreen                        #3CB371   60  179  113  352
	seagreen              = "#2E8B57"      # seagreen                              #2E8B57   46  139   87  272
	forestgreen           = "#228B22"      # forestgreen                           #228B22   34  139   34  207
	green                 = "#008000"      # green                                 #008000    0  128    0  128
	darkgreen             = "#006400"      # darkgreen                             #006400    0  100    0  100
	yellowgreen           = "#9ACD32"      # yellowgreen                           #9ACD32  154  205   50  409
	olivedrab             = "#6B8E23"      # olivedrab                             #6B8E23  107  142   35  284
	olive                 = "#808000"      # olive                                 #808000  128  128    0  256
	darkolivegreen        = "#556B2F"      # darkolivegreen                        #556B2F   85  107   47  239
	mediumaquamarine      = "#66CDAA"      # mediumaquamarine                      #66CDAA  102  205  170  477
	darkseagreen          = "#8FBC8F"      # darkseagreen                          #8FBC8F  143  188  143  474
	lightseagreen         = "#20B2AA"      # lightseagreen                         #20B2AA   32  178  170  380
	darkcyan              = "#008B8B"      # darkcyan                              #008B8B    0  139  139  278
	teal                  = "#008080"      # teal                                  #008080    0  128  128  256

# Blues Named
	aqua                  = "#00FFFF"      # aqua                                  #00FFFF    0  255  255  510
	cyan                  = "#00FFFF"      # cyan                                  #00FFFF    0  255  255  510
	lightcyan             = "#E0FFFF"      # lightcyan                             #E0FFFF  224  255  255  734
	paleturquoise         = "#AFEEEE"      # paleturquoise                         #AFEEEE  175  238  238  651
	aquamarine            = "#7FFFD4"      # aquamarine                            #7FFFD4  127  255  212  594
	turquoise             = "#40E0D0"      # turquoise                             #40E0D0   64  224  208  496
	mediumturquoise       = "#48D1CC"      # mediumturquoise                       #48D1CC   72  209  204  485
	darkturquoise         = "#00CED1"      # darkturquoise                         #00CED1    0  206  209  415
	cadetblue             = "#5F9EA0"      # cadetblue                             #5F9EA0   95  158  160  413
	steelblue             = "#4682B4"      # steelblue                             #4682B4   70  130  180  380
	lightsteelblue        = "#B0C4DE"      # lightsteelblue                        #B0C4DE  176  196  222  594
	powderblue            = "#B0E0E6"      # powderblue                            #B0E0E6  176  224  230  630
	lightblue             = "#ADD8E6"      # lightblue                             #ADD8E6  173  216  230  619
	skyblue               = "#87CEEB"      # skyblue                               #87CEEB  135  206  235  576
	lightskyblue          = "#87CEFA"      # lightskyblue                          #87CEFA  135  206  250  591
	deepskyblue           = "#00BFFF"      # deepskyblue                           #00BFFF    0  191  255  446
	dodgerblue            = "#1E90FF"      # dodgerblue                            #1E90FF   30  144  255  429
	cornflowerblue        = "#6495ED"      # cornflowerblue                        #6495ED  100  149  237  486
	mediumslateblue       = "#7B68EE"      # mediumslateblue                       #7B68EE  123  104  238  465
	royalblue             = "#4169E1"      # royalblue                             #4169E1   65  105  225  395
	blue                  = "#0000FF"      # blue                                  #0000FF    0    0  255  255
	mediumblue            = "#0000CD"      # mediumblue                            #0000CD    0    0  205  205
	darkblue              = "#00008B"      # darkblue                              #00008B    0    0  139  139
	navy                  = "#000080"      # navy                                  #000080    0    0  128  128
	midnightblue          = "#191970"      # midnightblue                          #191970   25   25  112  162

# Browns Named
	cornsilk              = "#FFF8DC"      # cornsilk                              #FFF8DC  255  248  220  723
	blanchedalmond        = "#FFEBCD"      # blanchedalmond                        #FFEBCD  255  235  205  695
	bisque                = "#FFE4C4"      # bisque                                #FFE4C4  255  228  196  679
	navajowhite           = "#FFDEAD"      # navajowhite                           #FFDEAD  255  222  173  650
	wheat                 = "#F5DEB3"      # wheat                                 #F5DEB3  245  222  179  646
	burlywood             = "#DEB887"      # burlywood                             #DEB887  222  184  135  541
	tan                   = "#D2B48C"      # tan                                   #D2B48C  210  180  140  530
	rosybrown             = "#BC8F8F"      # rosybrown                             #BC8F8F  188  143  143  474
	sandybrown            = "#F4A460"      # sandybrown                            #F4A460  244  164   96  504
	goldenrod             = "#DAA520"      # goldenrod                             #DAA520  218  165   32  415
	darkgoldenrod         = "#B8860B"      # darkgoldenrod                         #B8860B  184  134   11  329
	peru                  = "#CD853F"      # peru                                  #CD853F  205  133   63  401
	chocolate             = "#D2691E"      # chocolate                             #D2691E  210  105   30  345
	saddlebrown           = "#8B4513"      # saddlebrown                           #8B4513  139   69   19  227
	sienna                = "#A0522D"      # sienna                                #A0522D  160   82   45  287
	brown                 = "#A52A2A"      # brown                                 #A52A2A  165   42   42  249
	maroon                = "#800000"      # maroon                                #800000  128    0    0  128

# Whites Named
	white                 = "#FFFFFF"      # white                                 #FFFFFF  255  255  255  765
	snow                  = "#FFFAFA"      # snow                                  #FFFAFA  255  250  250  755
	honeydew              = "#F0FFF0"      # honeydew                              #F0FFF0  240  255  240  735
	mintcream             = "#F5FFFA"      # mintcream                             #F5FFFA  245  255  250  750
	azure                 = "#F0FFFF"      # azure                                 #F0FFFF  240  255  255  750
	aliceblue             = "#F0F8FF"      # aliceblue                             #F0F8FF  240  248  255  743
	ghostwhite            = "#F8F8FF"      # ghostwhite                            #F8F8FF  248  248  255  751
	whitesmoke            = "#F5F5F5"      # whitesmoke                            #F5F5F5  245  245  245  735
	seashell              = "#FFF5EE"      # seashell                              #FFF5EE  255  245  238  738
	beige                 = "#F5F5DC"      # beige                                 #F5F5DC  245  245  220  710
	oldlace               = "#FDF5E6"      # oldlace                               #FDF5E6  253  245  230  728
	floralwhite           = "#FFFAF0"      # floralwhite                           #FFFAF0  255  250  240  745
	ivory                 = "#FFFFF0"      # ivory                                 #FFFFF0  255  255  240  750
	antiquewhite          = "#FAEBD7"      # antiquewhite                          #FAEBD7  250  235  215  700
	linen                 = "#FAF0E6"      # linen                                 #FAF0E6  250  240  230  720
	lavenderblush         = "#FFF0F5"      # lavenderblush                         #FFF0F5  255  240  245  740
	mistyrose             = "#FFE4E1"      # mistyrose                             #FFE4E1  255  228  225  708

# Grays Named
	gainsboro             = "#DCDCDC"      # gainsboro                             #DCDCDC  220  220  220  660
	lightgray             = "#D3D3D3"      # lightgray                             #D3D3D3  211  211  211  633
	silver                = "#C0C0C0"      # silver                                #C0C0C0  192  192  192  576
	darkgray              = "#A9A9A9"      # darkgray                              #A9A9A9  169  169  169  507
	gray                  = "#808080"      # gray                                  #808080  128  128  128  384
	dimgray               = "#696969"      # dimgray                               #696969  105  105  105  315
	lightslategray        = "#778899"      # lightslategray                        #778899  119  136  153  408
	slategray             = "#708090"      # slategray                             #708090  112  128  144  384
	darkslategray         = "#2F4F4F"      # darkslategray                         #2F4F4F   47   79   79  205
	black                 = "#000000"      # black                                 #000000    0    0    0    0

# British Grey Named
	lightgrey             = "#D3D3D3"      # lightgrey                             #D3D3D3  211  211  211  633
	darkgrey              = "#A9A9A9"      # darkgrey                              #A9A9A9  169  169  169  507
	grey                  = "#808080"      # grey                                  #808080  128  128  128  384
	dimgrey               = "#696969"      # dimgrey                               #696969  105  105  105  315
	lightslategrey        = "#778899"      # lightslategrey                        #778899  119  136  153  408
	slategrey             = "#708090"      # slategrey                             #708090  112  128  144  384
	darkslategrey         = "#2F4F4F"      # darkslategrey                         #2F4F4F   47   79   79  205
