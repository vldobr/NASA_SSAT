%!PS-Adobe-3.0 EPSF-3.0
%%Creator: Mayura Draw, Version 4.4
%%Title: RFTCarchitecture.md
%%CreationDate: Tue Apr 17 11:33:04 2012
%%BoundingBox: 72 35 424 663
%%DocumentFonts: ArialMT
%%Orientation: Landscape
%%EndComments
%%BeginProlog
%%BeginResource: procset MayuraDraw_ops
%%Version: 4.4
%%Copyright: (c) 1993-2003 Mayura Software
/PDXDict 100 dict def
PDXDict begin
% width height matrix proc key cache
% definepattern -\> font
/definepattern { %def
  7 dict begin
    /FontDict 9 dict def
    FontDict begin
      /cache exch def
      /key exch def
      /proc exch cvx def
      /mtx exch matrix invertmatrix def
      /height exch def
      /width exch def
      /ctm matrix currentmatrix def
      /ptm matrix identmatrix def
      /str
      (xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx)
      def
    end
    /FontBBox [ %def
      0 0 FontDict /width get
      FontDict /height get
    ] def
    /FontMatrix FontDict /mtx get def
    /Encoding StandardEncoding def
    /FontType 3 def
    /BuildChar { %def
      pop begin
      FontDict begin
        width 0 cache { %ifelse
          0 0 width height setcachedevice
        }{ %else
          setcharwidth
        } ifelse
        0 0 moveto width 0 lineto
        width height lineto 0 height lineto
        closepath clip newpath
        gsave proc grestore
      end end
    } def
    FontDict /key get currentdict definefont
  end
} bind def

% dict patternpath -
% dict matrix patternpath -
/patternpath { %def
  dup type /dicttype eq { %ifelse
    begin FontDict /ctm get setmatrix
  }{ %else
    exch begin FontDict /ctm get setmatrix
    concat
  } ifelse
  currentdict setfont
  FontDict begin
    FontMatrix concat
    width 0 dtransform
    round width div exch round width div exch
    0 height dtransform
    round height div exch
    round height div exch
    0 0 transform round exch round exch
    ptm astore setmatrix

    pathbbox
    height div ceiling height mul 4 1 roll
    width div ceiling width mul 4 1 roll
    height div floor height mul 4 1 roll
    width div floor width mul 4 1 roll

    2 index sub height div ceiling cvi exch
    3 index sub width div ceiling cvi exch
    4 2 roll moveto

    FontMatrix ptm invertmatrix pop
    { %repeat
      gsave
        ptm concat
        dup str length idiv { %repeat
          str show
        } repeat
        dup str length mod str exch
        0 exch getinterval show
      grestore
      0 height rmoveto
    } repeat
    pop
  end end
} bind def

% dict patternfill -
% dict matrix patternfill -
/patternfill { %def
  gsave
    eoclip patternpath
  grestore
  newpath
} bind def

/img { %def
  gsave
  /imgh exch def
  /imgw exch def
  concat
  imgw imgh 8
  [imgw 0 0 imgh neg 0 imgh]
  /colorstr 768 string def
  /colorimage where {
    pop
    { currentfile colorstr readhexstring pop }
    false 3 colorimage
  }{
    /graystr 256 string def
    {
      currentfile colorstr readhexstring pop
      length 3 idiv
      dup 1 sub 0 1 3 -1 roll
      {
        graystr exch
        colorstr 1 index 3 mul get 30 mul
        colorstr 2 index 3 mul 1 add get 59 mul
        colorstr 3 index 3 mul 2 add get 11 mul
        add add 100 idiv
        put
      } for
      graystr 0 3 -1 roll getinterval
    } image
  } ifelse
  grestore
} bind def

/arrowhead {
  gsave
    [] 0 setdash
    strokeC strokeM strokeY strokeK setcmykcolor
    2 copy moveto
    4 2 roll exch 4 -1 roll exch
    sub 3 1 roll sub
    exch atan rotate dup scale
    arrowtype
    dup 0 eq {
      -1 2 rlineto 7 -2 rlineto -7 -2 rlineto
      closepath fill
    } if
    dup 1 eq {
      0 3 rlineto 9 -3 rlineto -9 -3 rlineto
      closepath fill
    } if
    dup 2 eq {
      -6 -6 rmoveto 6 6 rlineto -6 6 rlineto
      -1.4142 -1.4142 rlineto 4.5858 -4.5858 rlineto
      -4.5858 -4.5858 rlineto closepath fill
    } if
    dup 3 eq {
      -6 0 rmoveto -1 2 rlineto 7 -2 rlineto -7 -2 rlineto
      closepath fill
    } if
    dup 4 eq {
      -9 0 rmoveto 0 3 rlineto 9 -3 rlineto -9 -3 rlineto
      closepath fill
    } if
    dup 5 eq {
      currentpoint newpath 3 0 360 arc
      closepath fill
    } if
    dup 6 eq {
      2.5 2.5 rmoveto 0 -5 rlineto -5 0 rlineto 0 5 rlineto
      closepath fill
    } if
    pop
  grestore
} bind def

/setcmykcolor where { %ifelse
  pop
}{ %else
  /setcmykcolor {
     /black exch def /yellow exch def
     /magenta exch def /cyan exch def
     cyan black add dup 1 gt { pop 1 } if 1 exch sub
     magenta black add dup 1 gt { pop 1 } if 1 exch sub
     yellow black add dup 1 gt { pop 1 } if 1 exch sub
     setrgbcolor
  } bind def
} ifelse

/RE { %def
  findfont begin
  currentdict dup length dict begin
    { %forall
      1 index /FID ne { def } { pop pop } ifelse
    } forall
    /FontName exch def dup length 0 ne { %if
      /Encoding Encoding 256 array copy def
      0 exch { %forall
        dup type /nametype eq { %ifelse
          Encoding 2 index 2 index put
          pop 1 add
        }{ %else
          exch pop
        } ifelse
      } forall
    } if pop
  currentdict dup end end
  /FontName get exch definefont pop
} bind def

/spacecount { %def
  0 exch
  ( ) { %loop
    search { %ifelse
      pop 3 -1 roll 1 add 3 1 roll
    }{ pop exit } ifelse
  } loop
} bind def

/WinAnsiEncoding [
  39/quotesingle 96/grave 130/quotesinglbase/florin/quotedblbase
  /ellipsis/dagger/daggerdbl/circumflex/perthousand
  /Scaron/guilsinglleft/OE 145/quoteleft/quoteright
  /quotedblleft/quotedblright/bullet/endash/emdash
  /tilde/trademark/scaron/guilsinglright/oe/dotlessi
  159/Ydieresis 164/currency 166/brokenbar 168/dieresis/copyright
  /ordfeminine 172/logicalnot 174/registered/macron/ring
  177/plusminus/twosuperior/threesuperior/acute/mu
  183/periodcentered/cedilla/onesuperior/ordmasculine
  188/onequarter/onehalf/threequarters 192/Agrave/Aacute
  /Acircumflex/Atilde/Adieresis/Aring/AE/Ccedilla
  /Egrave/Eacute/Ecircumflex/Edieresis/Igrave/Iacute
  /Icircumflex/Idieresis/Eth/Ntilde/Ograve/Oacute
  /Ocircumflex/Otilde/Odieresis/multiply/Oslash
  /Ugrave/Uacute/Ucircumflex/Udieresis/Yacute/Thorn
  /germandbls/agrave/aacute/acircumflex/atilde/adieresis
  /aring/ae/ccedilla/egrave/eacute/ecircumflex
  /edieresis/igrave/iacute/icircumflex/idieresis
  /eth/ntilde/ograve/oacute/ocircumflex/otilde
  /odieresis/divide/oslash/ugrave/uacute/ucircumflex
  /udieresis/yacute/thorn/ydieresis
] def

/SymbolEncoding [
  32/space/exclam/universal/numbersign/existential/percent
  /ampersand/suchthat/parenleft/parenright/asteriskmath/plus
  /comma/minus/period/slash/zero/one/two/three/four/five/six
  /seven/eight/nine/colon/semicolon/less/equal/greater/question
  /congruent/Alpha/Beta/Chi/Delta/Epsilon/Phi/Gamma/Eta/Iota
  /theta1/Kappa/Lambda/Mu/Nu/Omicron/Pi/Theta/Rho/Sigma/Tau
  /Upsilon/sigma1/Omega/Xi/Psi/Zeta/bracketleft/therefore
  /bracketright/perpendicular/underscore/radicalex/alpha
  /beta/chi/delta/epsilon/phi/gamma/eta/iota/phi1/kappa/lambda
  /mu/nu/omicron/pi/theta/rho/sigma/tau/upsilon/omega1/omega
  /xi/psi/zeta/braceleft/bar/braceright/similar
  161/Upsilon1/minute/lessequal/fraction/infinity/florin/club
  /diamond/heart/spade/arrowboth/arrowleft/arrowup/arrowright
  /arrowdown/degree/plusminus/second/greaterequal/multiply
  /proportional/partialdiff/bullet/divide/notequal/equivalence
  /approxequal/ellipsis/arrowvertex/arrowhorizex/carriagereturn
  /aleph/Ifraktur/Rfraktur/weierstrass/circlemultiply
  /circleplus/emptyset/intersection/union/propersuperset
  /reflexsuperset/notsubset/propersubset/reflexsubset/element
  /notelement/angle/gradient/registerserif/copyrightserif
  /trademarkserif/product/radical/dotmath/logicalnot/logicaland
  /logicalor/arrowdblboth/arrowdblleft/arrowdblup/arrowdblright
  /arrowdbldown/lozenge/angleleft/registersans/copyrightsans
  /trademarksans/summation/parenlefttp/parenleftex/parenleftbt
  /bracketlefttp/bracketleftex/bracketleftbt/bracelefttp
  /braceleftmid/braceleftbt/braceex
  241/angleright/integral/integraltp/integralex/integralbt
  /parenrighttp/parenrightex/parenrightbt/bracketrighttp
  /bracketrightex/bracketrightbt/bracerighttp/bracerightmid
  /bracerightbt
] def

/patarray [
/leftdiagonal /rightdiagonal /crossdiagonal /horizontal
/vertical /crosshatch /fishscale /wave /brick
] def
/arrowtype 0 def
/fillC 0 def /fillM 0 def /fillY 0 def /fillK 0 def
/strokeC 0 def /strokeM 0 def /strokeY 0 def /strokeK 1 def
/pattern -1 def
/mat matrix def
/mat2 matrix def
/nesting 0 def
/deferred /N def
/c /curveto load def
/c2 { pop pop c } bind def
/C /curveto load def
/C2 { pop pop C } bind def
/e { gsave concat 0 0 moveto } bind def
/F {
  nesting 0 eq { %ifelse
    pattern -1 eq { %ifelse
      fillC fillM fillY fillK setcmykcolor eofill
    }{ %else
      gsave fillC fillM fillY fillK setcmykcolor eofill grestore
      0 0 0 1 setcmykcolor
      patarray pattern get findfont patternfill
    } ifelse
  }{ %else
    /deferred /F def
  } ifelse
} bind def
/f { closepath F } bind def
/K { /strokeK exch def /strokeY exch def
     /strokeM exch def /strokeC exch def } bind def
/k { /fillK exch def /fillY exch def
     /fillM exch def /fillC exch def } bind def
/opc { pop } bind def
/Opc { pop } bind def
/L /lineto load def
/L2 { pop pop L } bind def
/m /moveto load def
/m2 { pop pop m } bind def
/n /newpath load def
/N {
  nesting 0 eq { %ifelse
    newpath
  }{ %else
    /deferred /N def
  } ifelse
} def
/S {
  nesting 0 eq { %ifelse
    strokeC strokeM strokeY strokeK setcmykcolor stroke
  }{ %else
    /deferred /S def
  } ifelse
} bind def
/s { closepath S } bind def
/Tx { fillC fillM fillY fillK setcmykcolor show
      0 leading neg translate 0 0 moveto } bind def
/T { grestore } bind def
/TX { pop } bind def
/Ts { pop } bind def
/tal { pop } bind def
/tld { pop } bind def
/tbx { pop exch pop sub /jwidth exch def } def
/tpt { %def
  fillC fillM fillY fillK setcmykcolor
  moveto show
} bind def
/tpj { %def
  fillC fillM fillY fillK setcmykcolor
  moveto
  dup stringwidth pop
  3 -1 roll
  exch sub
  1 index spacecount
  dup 0 eq { %ifelse
    pop pop show
  }{ %else
    div 0 8#040 4 -1 roll widthshow
  } ifelse
} bind def
/u {} def
/U {} def
/*u { /nesting nesting 1 add def } def
/*U {
  /nesting nesting 1 sub def
  nesting 0 eq {
    deferred cvx exec
  } if
} def
/w /setlinewidth load def
/d /setdash load def
/B {
  nesting 0 eq { %ifelse
    gsave F grestore S
  }{ %else
    /deferred /B def
  } ifelse
} bind def
/b { closepath B } bind def
/z { /align exch def pop /leading exch def exch findfont
     exch scalefont setfont } bind def
/tfn { exch findfont
     exch scalefont setfont } bind def
/Pat { /pattern exch def } bind def
/cm { 6 array astore concat } bind def
/q { mat2 currentmatrix pop } bind def
/Q { mat2 setmatrix } bind def
/Ah {
  pop /arrowtype exch def
  currentlinewidth 5 1 roll arrowhead
} bind def
/Arc {
  mat currentmatrix pop
    translate scale 0 0 1 5 -2 roll arc
  mat setmatrix
} bind def
/Arc2 { pop pop Arc } bind def
/Bx {
  mat currentmatrix pop
    concat /y1 exch def /x1 exch def /y2 exch def /x2 exch def
    x1 y1 moveto x1 y2 lineto x2 y2 lineto x2 y1 lineto
  mat setmatrix
} bind def
/Rr {
  mat currentmatrix pop
    concat /yrad exch def /xrad exch def
    2 copy gt { exch } if /x2 exch def /x1 exch def
    2 copy gt { exch } if /y2 exch def /y1 exch def
    x1 xrad add y2 moveto
    matrix currentmatrix x1 xrad add y2 yrad sub translate xrad yrad scale
    0 0 1 90 -180 arc setmatrix
    matrix currentmatrix x1 xrad add y1 yrad add translate xrad yrad scale
    0 0 1 180 270 arc setmatrix
    matrix currentmatrix x2 xrad sub y1 yrad add translate xrad yrad scale
    0 0 1 270 0 arc setmatrix
    matrix currentmatrix x2 xrad sub y2 yrad sub translate xrad yrad scale
    0 0 1 0 90 arc setmatrix
    closepath
  mat setmatrix
} bind def
/Ov {
  mat currentmatrix pop
    concat translate scale 1 0 moveto 0 0 1 0 360 arc closepath
  mat setmatrix
} bind def
end
%%EndResource
%%EndProlog
%%BeginSetup
%PDX g 1 1 1 1
%%IncludeFont: ArialMT
PDXDict begin
%%EndSetup
%%Page: 1 1
%%BeginPageSetup
/_PDX_savepage save def

15 15 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 setlinecap
  7.5 0 moveto 15 7.5 lineto
  0 7.5 moveto 7.5 15 lineto
  2 setlinewidth stroke
} bind
/rightdiagonal true definepattern pop

15 15 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 setlinecap
  7.5 0 moveto 0 7.5 lineto
  15 7.5 moveto 7.5 15 lineto
  2 setlinewidth stroke
} bind
/leftdiagonal true definepattern pop

15 15 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 setlinecap
  0 7.5 moveto 15 7.5 lineto
  2 setlinewidth stroke
} bind
/horizontal true definepattern pop

15 15 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 setlinecap
  7.5 0 moveto 7.5 15 lineto
  2 setlinewidth stroke
} bind
/vertical true definepattern pop

15 15 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 setlinecap
  0 7.5 moveto 15 7.5 lineto
  7.5 0 moveto 7.5 15 lineto
  2 setlinewidth stroke
} bind
/crosshatch true definepattern pop

30 30 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 setlinecap
  0 7.5 moveto 30 7.5 lineto
  0 22.5 moveto 30 22.5 lineto
  7.5 0 moveto 7.5 7.5 lineto
  7.5 22.5 moveto 7.5 30 lineto
  22.5 7.5 moveto 22.5 22.5 lineto
  1 setlinewidth stroke
} bind
/brick true definepattern pop

30 30 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 2 scale
  2 setlinecap
  7.5 0 moveto 15 7.5 lineto
  0 7.5 moveto 7.5 15 lineto
  7.5 0 moveto 0 7.5 lineto
  15 7.5 moveto 7.5 15 lineto
  0.5 setlinewidth stroke
} bind
/crossdiagonal true definepattern pop

30 30 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 2 scale
  1 setlinecap
  0 7.5 moveto 0 15 7.5 270 360 arc
  7.5 15 moveto 15 15 7.5 180 270 arc
  0 7.5 moveto 7.5 7.5 7.5 180 360 arc
  0.5 setlinewidth stroke
} bind
/fishscale true definepattern pop

30 30 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  1 setlinecap 0.5 setlinewidth
  7.5 0 10.6 135 45 arcn
  22.5 15 10.6 225 315 arc
  stroke
  7.5 15 10.6 135 45 arcn
  22.5 30 10.6 225 315 arc
  stroke
} bind
/wave true definepattern pop

WinAnsiEncoding /_ArialMT /ArialMT RE

newpath 2 setlinecap 0 setlinejoin 2 setmiterlimit
[] 0 setdash
72 35 moveto 72 663 lineto 424 663 lineto 424 35 lineto closepath clip
newpath
%%EndPageSetup
-1.42109e-016 -1.42109e-016 0.0392157 0 k
1 w
[10 4] 0 d
615.1 475.1 320.1 160.1 [0 1 -1 0 575.1 -110.1] Bx
b
0.117647 0.0117647 0.168627 0 k
421.1 475.1 281.1 160.1 [0 1 -1 0 575.1 -236.1] Bx
b
0.0196078 0.0196078 0.176471 0 k
[3 3] 0 d
585.1 475.1 320.1 280.1 [0 1 -1 0 680.1 -95.1] Bx
b
0.215686 0.117647 0.215686 0 k
[] 0 d
375 480 320 440 [0 1 -1 0 715.1 -265.1] Bx
b
[0 1 -1 0 754.1 -127.5] e
210 505 210 505 tbx
1 tal
13 tld
1 1 1 0 k
/_ArialMT 12 tfn
(Pilot) 198.33 494.14 tpt
T
0.215686 0.117647 0.215686 0 k
360.098 480 320 440.058 [0 1 -1 0 765.1 -186.1] Bx
b
0.117647 0.0117647 0.168627 0 k
[3 3] 0 d
505.098 330.058 320 260.058 [0 1 -1 0 445.1 -95.1] Bx
b
[0 1 -1 0 872.9 308.5] e
210 505 210 505 tbx
1 tal
13 tld
1 1 1 0 k
/_ArialMT 12 tfn
(yh) 203.664 494.14 tpt
T
0.215686 0.117647 0.215686 0 k
[] 0 d
378.1 480 317.1 440.1 [0 1 -1 0 610.1 -73.1] Bx
b
[0 1 -1 0 649.1 64.49] e
210 505 210 505 tbx
1 tal
13 tld
1 1 1 0 k
/_ArialMT 12 tfn
(Awareness) 180.324 494.14 tpt
T
[0 1 -1 0 637.5 64.5] e
210 505 210 505 tbx
1 tal
13 tld
/_ArialMT 12 tfn
(Situation) 186.654 494.14 tpt
T
[0 1 -1 0 660.3 64.49] e
210 505 210 505 tbx
1 tal
13 tld
/_ArialMT 12 tfn
(Interface) 186.654 494.14 tpt
T
0.215686 0.117647 0.215686 0 k
378.1 480.1 317.1 440 [0 1 -1 0 610.1 16.9] Bx
b
[0 1 -1 0 649.1 154.5] e
210 505 210 505 tbx
1 tal
13 tld
1 1 1 0 k
/_ArialMT 12 tfn
(Monitoring) 181.992 494.14 tpt
T
[0 1 -1 0 637.5 154.5] e
210 505 210 505 tbx
1 tal
13 tld
/_ArialMT 12 tfn
(Safety) 192.99 494.14 tpt
T
[0 1 -1 0 660.3 154.5] e
210 505 210 505 tbx
1 tal
13 tld
/_ArialMT 12 tfn
(System) 189.996 494.14 tpt
T
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
q
0 1 -1 0 637.1 -74.1 cm
402.1 486.1 408.1 486.1 m2
385.1 486.1 379.1 486.1 L2
Q
S
q
0 1 -1 0 637.1 -74.1 cm
379.1 486.1 408.1 486.1 3 1 Ah
408.1 486.1 379.1 486.1 3 2 Ah
Q
q
0 1 -1 0 670.1 -52.1 cm
370.098 471.058 370.098 465.058 m2
370.098 479.058 370.098 485.058 L2
Q
S
q
0 1 -1 0 670.1 -52.1 cm
370.098 485.058 370.098 465.058 3 1 Ah
370.098 465.058 370.098 485.058 3 2 Ah
Q
[0 1 -1 0 697.1 260.5] e
210 505 210 505 tbx
1 tal
13 tld
1 1 1 0 k
/_ArialMT 12 tfn
(RFTC) 194.004 494.14 tpt
T
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
[3 3] 0 d
q
0 1 -1 0 636.1 -209.1 cm
428.098 486.06 434.098 486.058 m2
291.1 486.1 L
Q
S
q
0 1 -1 0 636.1 -209.1 cm
291.1 486.1 434.098 486.058 3 1 Ah
Q
q
0 1 -1 0 625.1 -280.1 cm
362.098 396.058 362.098 390.058 m2
362.1 475.1 L
Q
S
q
0 1 -1 0 625.1 -280.1 cm
362.1 475.1 362.098 390.058 3 1 Ah
Q
[0 1 -1 0 796.5 -12.5] e
210 505 210 505 tbx
1 tal
13 tld
1 1 1 0 k
/_ArialMT 12 tfn
(r) 208.002 494.14 tpt
T
[0 1 -1 0 693.1 -123.1] e
210 505 210 505 tbx
0 tal
13 tld
/_ArialMT 12 tfn
(awareness) 210 494.14 tpt
T
[0 1 -1 0 683.1 -123.1] e
210 505 210 505 tbx
0 tal
13 tld
/_ArialMT 12 tfn
(situation) 210 494.14 tpt
T
0.0588235 0.027451 -1.42109e-016 0 k
[10 4] 0 d
436.098 475.1 336.1 160.1 [0 1 -1 0 575.1 193.9] Bx
b
[0 1 -1 0 587 -160.5] e
210 505 210 505 tbx
0 tal
13 tld
1 1 1 0 k
/_ArialMT 12 tfn
(human) 210 494.14 tpt
T
[0 1 -1 0 587 4.492] e
210 505 210 505 tbx
0 tal
13 tld
/_ArialMT 12 tfn
(irecover) 210 494.14 tpt
T
[0 1 -1 0 587 323.5] e
210 505 210 505 tbx
0 tal
13 tld
/_ArialMT 12 tfn
(aircraft) 210 494.14 tpt
T
0.501961 0.309804 -1.42109e-016 0 k
[] 0 d
375 480 320 440 [0 1 -1 0 755.1 229.9] Bx
b
[0 1 -1 0 793 367.5] e
210 505 210 505 tbx
1 tal
13 tld
1 1 1 0 k
/_ArialMT 12 tfn
(Aircraft) 190.998 494.14 tpt
T
[0 1 -1 0 785.4 307.5] e
210 505 210 505 tbx
1 tal
13 tld
/_ArialMT 12 tfn
(u) 206.664 494.14 tpt
T
0.501961 0.309804 -1.42109e-016 0 k
375 480 320 440 [0 1 -1 0 825.1 229.9] Bx
b
[0 1 -1 0 863 367.5] e
210 505 210 505 tbx
1 tal
13 tld
1 1 1 0 k
/_ArialMT 12 tfn
(Sensing) 188.322 494.14 tpt
T
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
q
0 1 -1 0 835.1 98.9 cm
397.1 470.096 391.1 470.1 m2
451.098 470.058 L
Q
S
q
0 1 -1 0 835.1 98.9 cm
451.098 470.058 391.1 470.1 3 1 Ah
Q
q
0 1 -1 0 781.1 235.9 cm
412.098 486.058 418.098 486.058 m2
369.098 486.058 L
Q
S
q
0 1 -1 0 781.1 235.9 cm
369.098 486.058 418.098 486.058 3 1 Ah
Q
[0 1 -1 0 784.4 434.5] e
210 505 210 505 tbx
1 tal
13 tld
1 1 1 0 k
/_ArialMT 12 tfn
(y) 207 494.14 tpt
T
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
q
0 1 -1 0 835.1 213.9 cm
397.098 470.058 391.098 470.058 m2
406.098 470.058 L
Q
S
q
0 1 -1 0 835.1 213.9 cm
406.098 470.058 391.098 470.058 3 1 Ah
Q
q
0 1 -1 0 770.1 164.9 cm
455.098 475.058 m
455.098 405.058 L
Q
S
0.215686 0.117647 0.215686 0 k
q
0 1 -1 0 781.1 -255.1 cm
383.1 486.1 389.1 486.1 m2
375.1 486.1 L
Q
B
q
0 1 -1 0 781.1 -255.1 cm
375.1 486.1 389.1 486.1 3 1 Ah
Q
1 1 1 0 k
1.41421 1.41421 450 449 [0 1 -1 0 744.1 -306.1] Ov
b
0.215686 0.117647 0.215686 0 k
q
0 1 -1 0 801.1 -255.1 cm
383.1 486.1 389.1 486.1 m2
365.1 486.1 L
Q
B
q
0 1 -1 0 801.1 -255.1 cm
365.1 486.1 389.1 486.1 3 1 Ah
Q
1 1 1 0 k
1.41421 1.41421 450 449 [0 1 -1 0 764.1 -306.1] Ov
b
1.41421 1.41421 450 449 [0 1 -1 0 754.1 -286.1] Ov
b
0.215686 0.117647 0.215686 0 k
q
0 1 -1 0 780.1 -317.1 cm
451.098 485.058 m
461.098 485.058 L
Q
B
q
0 1 -1 0 800.1 -317.1 cm
451.098 485.058 m
461.098 485.058 L
Q
B
q
0 1 -1 0 800.1 -287.1 cm
451.098 495.058 m
431.098 505.058 L
Q
B
375 480 320 440 [0 1 -1 0 775.1 -265.1] Bx
b
[0 1 -1 0 814.1 -127.5] e
210 505 210 505 tbx
1 tal
13 tld
1 1 1 0 k
/_ArialMT 12 tfn
(Autopilot) 186.654 494.14 tpt
T
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
q
0 1 -1 0 740.1 -341.1 cm
451.1 485.1 m
461.1 485.1 L
Q
S
q
0 1 -1 0 740.1 -331.1 cm
451.098 485.058 m
451.098 445.1 L
Q
S
[0 1 -1 0 803.5 225.5] e
210 505 210 505 tbx
1 tal
13 tld
1 1 1 0 k
/_ArialMT 12 tfn
() 210 494.14 tpt
T
0.0588235 0.027451 -1.42109e-016 0 k
[3 3] 0 d
402.1 406.1 304.1 296.1 [0 1 -1 0 631.1 52.9] Bx
b
-1.42109e-016 0.0588235 0.333333 0 k
396.1 470.1 317.1 301.1 [0 1 -1 0 690.1 -82.1] Bx
b
0.215686 0.117647 -1.42109e-016 0 k
[] 0 d
378.1 480.1 317.1 440 [0 1 -1 0 765.1 49.9] Bx
b
-1.42109e-016 0.168627 0.588235 0 k
378.1 480 317.1 440.1 [0 1 -1 0 708.1 -73.1] Bx
b
1 1 1 0 k
1.41421 1.41421 450 449 [0 1 -1 0 754.1 -112.1] Ov
b
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
[10 4 3 4] 0 d
q
0 1 -1 0 750.1 -6.1 cm
451.1 415.1 m
451.1 380.1 L
Q
S
q
0 1 -1 0 856.1 125.9 cm
308.1 486.1 302.1 486.1 m2
319.1 486.1 L
Q
S
q
0 1 -1 0 856.1 125.9 cm
319.1 486.1 302.1 486.1 3 1 Ah
Q
[0 1 -1 0 862.1 238.4] e
210 505 210 505 tbx
0 tal
13 tld
1 1 1 0 k
/_ArialMT 12 tfn
(trigger) 210 494.14 tpt
T
[0 1 -1 0 852.1 238.4] e
210 505 210 505 tbx
0 tal
13 tld
/_ArialMT 12 tfn
(fdi) 210 494.14 tpt
T
0.0588235 0.498039 0.498039 0 k
[] 0 d
378.1 480 317.1 440.1 [0 1 -1 0 830.1 49.9] Bx
b
[0 1 -1 0 861.4 187.5] e
210 505 210 505 tbx
1 tal
13 tld
1 1 1 0 k
/_ArialMT 12 tfn
(FDI) 200.334 494.14 tpt
T
[0 1 -1 0 873.3 187.5] e
210 505 210 505 tbx
1 tal
13 tld
/_ArialMT 12 tfn
(Module) 190.326 494.14 tpt
T
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
q
0 1 -1 0 781.1 125.9 cm
310.1 486.1 316.1 486.1 m2
302.1 486.1 L
Q
S
q
0 1 -1 0 781.1 125.9 cm
302.1 486.1 316.1 486.1 3 1 Ah
Q
-1.42109e-016 0.168627 0.588235 0 k
378.1 480.1 317.1 440 [0 1 -1 0 765.1 -73.1] Bx
b
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
q
0 1 -1 0 755.1 -155.1 cm
430.1 486.1 m
430.1 476.1 430.1 470.1 L2
Q
S
q
0 1 -1 0 755.1 -155.1 cm
430.1 486.1 430.1 470.1 3 2 Ah
Q
[0 1 -1 0 739.4 64.5] e
210 505 210 505 tbx
1 tal
13 tld
1 1 1 0 k
/_ArialMT 12 tfn
(LOC) 197.664 494.14 tpt
T
[0 1 -1 0 751.3 64.5] e
210 505 210 505 tbx
1 tal
13 tld
/_ArialMT 12 tfn
(Prediction) 183.324 494.14 tpt
T
[0 1 -1 0 804.1 64.49] e
210 505 210 505 tbx
1 tal
13 tld
/_ArialMT 12 tfn
(Envelope) 184.986 494.14 tpt
T
[0 1 -1 0 792.5 64.5] e
210 505 210 505 tbx
1 tal
13 tld
/_ArialMT 12 tfn
(Stability) 188.994 494.14 tpt
T
[0 1 -1 0 815.3 64.49] e
210 505 210 505 tbx
1 tal
13 tld
/_ArialMT 12 tfn
(Protection) 182.988 494.14 tpt
T
-1.42109e-016 0.168627 0.588235 0 k
379.1 480 318.1 440.1 [0 1 -1 0 821.1 -74.1] Bx
b
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
q
0 1 -1 0 811.1 -156.1 cm
430.1 480.1 430.1 486.1 m2
430.1 470.1 L
Q
S
q
0 1 -1 0 811.1 -156.1 cm
430.1 470.1 430.1 486.1 3 1 Ah
Q
[0 1 -1 0 860.1 63.49] e
210 505 210 505 tbx
1 tal
13 tld
1 1 1 0 k
/_ArialMT 12 tfn
(Envelope) 184.986 494.14 tpt
T
[0 1 -1 0 848.5 63.5] e
210 505 210 505 tbx
1 tal
13 tld
/_ArialMT 12 tfn
(Stability) 188.994 494.14 tpt
T
[0 1 -1 0 871.3 63.49] e
210 505 210 505 tbx
1 tal
13 tld
/_ArialMT 12 tfn
(Determ) 190.332 494.14 tpt
T
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
q
0 1 -1 0 846.1 -31.1 cm
429.1 511.1 m
429.1 502.1 429.1 496.1 L2
Q
S
q
0 1 -1 0 846.1 -31.1 cm
429.1 511.1 429.1 496.1 3 2 Ah
Q
[3 3] 0 d
q
0 1 -1 0 796.1 -31.1 cm
351.1 426.1 345.1 426.1 m2
398.1 426.1 L
Q
S
q
0 1 -1 0 796.1 -31.1 cm
398.1 426.1 345.1 426.1 3 1 Ah
Q
[] 0 d
q
0 1 -1 0 791.1 -56.1 cm
417.1 486.1 423.1 486.1 m2
361.1 486.1 L
Q
S
q
0 1 -1 0 791.1 -56.1 cm
361.1 486.1 423.1 486.1 3 1 Ah
Q
[0 1 -1 0 792.5 187.5] e
210 505 210 505 tbx
1 tal
13 tld
1 1 1 0 k
/_ArialMT 12 tfn
() 210 494.14 tpt
T
0.215686 0.117647 -1.42109e-016 0 k
378.1 480.1 317.1 440 [0 1 -1 0 715.1 49.9] Bx
b
[0 1 -1 0 746.4 187.5] e
210 505 210 505 tbx
1 tal
13 tld
1 1 1 0 k
/_ArialMT 12 tfn
(L1) 203.328 494.14 tpt
T
[0 1 -1 0 758.3 187.5] e
210 505 210 505 tbx
1 tal
13 tld
/_ArialMT 12 tfn
(Aug) 199.326 494.14 tpt
T
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
q
0 1 -1 0 744.1 -117.1 cm
455.1 489.1 m
455.1 439.1 L
Q
S
q
0 1 -1 0 741.1 -72.1 cm
433.1 486.1 439.1 486.1 m2
410.1 486.1 L
Q
S
q
0 1 -1 0 741.1 -72.1 cm
410.1 486.1 439.1 486.1 3 1 Ah
Q
-1.42109e-016 0.215686 0.803922 0 k
2.82843 2.82843 254 444 [1 0 0 1 41 1] Ov
b
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
q
0 1 -1 0 755.1 118.9 cm
326.1 469.1 326.1 463.1 m2
326.1 500.1 L
Q
S
q
0 1 -1 0 755.1 118.9 cm
326.1 500.1 326.1 463.1 3 1 Ah
Q
q
0 1 -1 0 733.1 -4.1 cm
449.1 478.1 m
432.1 478.1 L
Q
S
[0 1 -1 0 796.4 187.5] e
210 505 210 505 tbx
1 tal
13 tld
1 1 1 0 k
/_ArialMT 12 tfn
(Baseline) 186.99 494.14 tpt
T
[0 1 -1 0 808.3 187.5] e
210 505 210 505 tbx
1 tal
13 tld
/_ArialMT 12 tfn
(Controller) 183.996 494.14 tpt
T
[0 1 -1 0 717.1 159.5] e
210 505 210 505 tbx
1 tal
13 tld
/_ArialMT 12 tfn
(RFC) 197.67 494.14 tpt
T
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
[3 3] 0 d
q
0 1 -1 0 850.1 -91.1 cm
430.1 522.1 m
442.1 522.1 448.1 522.1 L2
Q
S
q
0 1 -1 0 850.1 -91.1 cm
430.1 522.1 448.1 522.1 3 2 Ah
Q
1 1 1 0 k
[] 0 d
1.41421 1.41421 450 449 [0 1 -1 0 819.1 -112.1] Ov
b
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
[3 3] 0 d
q
0 1 -1 0 809.1 -117.1 cm
455.1 481.1 m
455.1 439.1 L
Q
S
[0 1 -1 0 877.1 128] e
210 505 210 505 tbx
1 tal
13 tld
1 1 1 0 k
/_ArialMT 12 tfn
(reconf) 193.326 494.14 tpt
T
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
[] 0 d
q
0 1 -1 0 781.1 120.9 cm
423.098 486.06 429.098 486.058 m2
327.1 486.1 L
Q
S
q
0 1 -1 0 781.1 120.9 cm
327.1 486.1 429.098 486.058 3 1 Ah
Q
q
0 1 -1 0 791.1 -194.1 cm
432.1 486.1 438.1 486.1 m2
358.1 486.1 L
Q
S
q
0 1 -1 0 791.1 -194.1 cm
358.1 486.1 438.1 486.1 3 1 Ah
Q
%%PageTrailer
_PDX_savepage restore
%%Trailer
end
showpage
%%EOF
