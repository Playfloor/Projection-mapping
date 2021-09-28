# LaTeX Template for Scientific Theses ![Build Status](https://github.com/latextemplates/scientific-thesis-template/workflows/Build%20with%20lualatex/badge.svg)


Why every scientist must know latek. a no-brainer.

> This template is a general template for scientific theses.

LaTeX is too hard to spell and (for reasons to be explained later) difficult to pronounce, and so for the duration of this document, it will be referred to as "latek", with no quotation marks. 

Currently, it is the unofficial LaTeX template for Master, Bachelor, Diploma, and Student Theses.

See [docs/](docs/) or <http://latextemplates.github.io/scientific-thesis-template/> for a documentation of the template.

# very important

"first you must know latek, then you must change it"

pprerequisites. in order to understand this document, it is expected that the reader (traveller, voyager, navigator, explorer, listener) be at least somewhat familiar with the following nomenclature:



Unicode Input
The following table lists Unicode characters that can be entered via tab completion of LaTeX-like abbreviations in the Julia REPL (and in various other editing environments). You can also get information on how to type a symbol by entering it in the REPL help, i.e. by typing ? and then entering the symbol in the REPL (e.g., by copy-paste from somewhere you saw the symbol).

Warning
This table may appear to contain missing characters in the second column, or even show characters that are inconsistent with the characters as they are rendered in the Julia REPL. In these cases, users are strongly advised to check their choice of fonts in their browser and REPL environment, as there are known issues with glyphs in many fonts.

Code point(s)	Character(s)	Tab completion sequence(s)	Unicode name(s)
U+000A1	¡	\exclamdown	Inverted Exclamation Mark
U+000A3	£	\sterling	Pound Sign
U+000A5	¥	\yen	Yen Sign
U+000A6	¦	\brokenbar	Broken Bar / Broken Vertical Bar
U+000A7	§	\S	Section Sign
U+000A9	©	\copyright, \:copyright:	Copyright Sign
U+000AA	ª	\ordfeminine	Feminine Ordinal Indicator
U+000AC	¬	\neg	Not Sign
U+000AE	®	\circledR, \:registered:	Registered Sign / Registered Trade Mark Sign
U+000AF	¯	\highminus	Macron / Spacing Macron
U+000B0	°	\degree	Degree Sign
U+000B1	±	\pm	Plus-Minus Sign / Plus-Or-Minus Sign
U+000B2	²	\^2	Superscript Two / Superscript Digit Two
U+000B3	³	\^3	Superscript Three / Superscript Digit Three
U+000B6	¶	\P	Pilcrow Sign / Paragraph Sign
U+000B7	·	\cdotp	Middle Dot
U+000B9	¹	\^1	Superscript One / Superscript Digit One
U+000BA	º	\ordmasculine	Masculine Ordinal Indicator
U+000BC	¼	\1/4	Vulgar Fraction One Quarter / Fraction One Quarter
U+000BD	½	\1/2	Vulgar Fraction One Half / Fraction One Half
U+000BE	¾	\3/4	Vulgar Fraction Three Quarters / Fraction Three Quarters
U+000BF	¿	\questiondown	Inverted Question Mark
U+000C5	Å	\AA	Latin Capital Letter A With Ring Above / Latin Capital Letter A Ring
U+000C6	Æ	\AE	Latin Capital Letter Ae / Latin Capital Letter A E
U+000D0	Ð	\DH	Latin Capital Letter Eth
U+000D7	×	\times	Multiplication Sign
U+000D8	Ø	\O	Latin Capital Letter O With Stroke / Latin Capital Letter O Slash
U+000DE	Þ	\TH	Latin Capital Letter Thorn
U+000DF	ß	\ss	Latin Small Letter Sharp S
U+000E5	å	\aa	Latin Small Letter A With Ring Above / Latin Small Letter A Ring
U+000E6	æ	\ae	Latin Small Letter Ae / Latin Small Letter A E
U+000F0	ð	\eth, \dh	Latin Small Letter Eth
U+000F7	÷	\div	Division Sign
U+000F8	ø	\o	Latin Small Letter O With Stroke / Latin Small Letter O Slash
U+000FE	þ	\th	Latin Small Letter Thorn
U+00110	Đ	\DJ	Latin Capital Letter D With Stroke / Latin Capital Letter D Bar
U+00111	đ	\dj	Latin Small Letter D With Stroke / Latin Small Letter D Bar
U+00127	ħ	\hbar	Latin Small Letter H With Stroke / Latin Small Letter H Bar
U+00131	ı	\imath	Latin Small Letter Dotless I
U+00141	Ł	\L	Latin Capital Letter L With Stroke / Latin Capital Letter L Slash
U+00142	ł	\l	Latin Small Letter L With Stroke / Latin Small Letter L Slash
U+0014A	Ŋ	\NG	Latin Capital Letter Eng
U+0014B	ŋ	\ng	Latin Small Letter Eng
U+00152	Œ	\OE	Latin Capital Ligature Oe / Latin Capital Letter O E
U+00153	œ	\oe	Latin Small Ligature Oe / Latin Small Letter O E
U+00195	ƕ	\hvlig	Latin Small Letter Hv / Latin Small Letter H V
U+0019E	ƞ	\nrleg	Latin Small Letter N With Long Right Leg
U+001B5	Ƶ	\Zbar	Latin Capital Letter Z With Stroke / Latin Capital Letter Z Bar
U+001C2	ǂ	\doublepipe	Latin Letter Alveolar Click / Latin Letter Pipe Double Bar
U+00237	ȷ	\jmath	Latin Small Letter Dotless J
U+00250	ɐ	\trna	Latin Small Letter Turned A
U+00252	ɒ	\trnsa	Latin Small Letter Turned Alpha / Latin Small Letter Turned Script A
U+00254	ɔ	\openo	Latin Small Letter Open O
U+00256	ɖ	\rtld	Latin Small Letter D With Tail / Latin Small Letter D Retroflex Hook
U+00259	ə	\schwa	Latin Small Letter Schwa
U+00263	ɣ	\pgamma	Latin Small Letter Gamma
U+00264	ɤ	\pbgam	Latin Small Letter Rams Horn / Latin Small Letter Baby Gamma
U+00265	ɥ	\trnh	Latin Small Letter Turned H
U+0026C	ɬ	\btdl	Latin Small Letter L With Belt / Latin Small Letter L Belt
U+0026D	ɭ	\rtll	Latin Small Letter L With Retroflex Hook / Latin Small Letter L Retroflex Hook
U+0026F	ɯ	\trnm	Latin Small Letter Turned M
U+00270	ɰ	\trnmlr	Latin Small Letter Turned M With Long Leg
U+00271	ɱ	\ltlmr	Latin Small Letter M With Hook / Latin Small Letter M Hook
U+00272	ɲ	\ltln	Latin Small Letter N With Left Hook / Latin Small Letter N Hook
U+00273	ɳ	\rtln	Latin Small Letter N With Retroflex Hook / Latin Small Letter N Retroflex Hook
U+00277	ɷ	\clomeg	Latin Small Letter Closed Omega
U+00278	ɸ	\ltphi	Latin Small Letter Phi
U+00279	ɹ	\trnr	Latin Small Letter Turned R
U+0027A	ɺ	\trnrl	Latin Small Letter Turned R With Long Leg
U+0027B	ɻ	\rttrnr	Latin Small Letter Turned R With Hook / Latin Small Letter Turned R Hook
U+0027C	ɼ	\rl	Latin Small Letter R With Long Leg
U+0027D	ɽ	\rtlr	Latin Small Letter R With Tail / Latin Small Letter R Hook
U+0027E	ɾ	\fhr	Latin Small Letter R With Fishhook / Latin Small Letter Fishhook R
U+00282	ʂ	\rtls	Latin Small Letter S With Hook / Latin Small Letter S Hook
U+00283	ʃ	\esh	Latin Small Letter Esh
U+00287	ʇ	\trnt	Latin Small Letter Turned T
U+00288	ʈ	\rtlt	Latin Small Letter T With Retroflex Hook / Latin Small Letter T Retroflex Hook
U+0028A	ʊ	\pupsil	Latin Small Letter Upsilon
U+0028B	ʋ	\pscrv	Latin Small Letter V With Hook / Latin Small Letter Script V
U+0028C	ʌ	\invv	Latin Small Letter Turned V
U+0028D	ʍ	\invw	Latin Small Letter Turned W
U+0028E	ʎ	\trny	Latin Small Letter Turned Y
U+00290	ʐ	\rtlz	Latin Small Letter Z With Retroflex Hook / Latin Small Letter Z Retroflex Hook
U+00292	ʒ	\yogh	Latin Small Letter Ezh / Latin Small Letter Yogh
U+00294	ʔ	\glst	Latin Letter Glottal Stop
U+00295	ʕ	\reglst	Latin Letter Pharyngeal Voiced Fricative / Latin Letter Reversed Glottal Stop
U+00296	ʖ	\inglst	Latin Letter Inverted Glottal Stop
U+0029E	ʞ	\turnk	Latin Small Letter Turned K
U+002A4	ʤ	\dyogh	Latin Small Letter Dezh Digraph / Latin Small Letter D Yogh
U+002A7	ʧ	\tesh	Latin Small Letter Tesh Digraph / Latin Small Letter T Esh
U+002B0	ʰ	\^h	Modifier Letter Small H
U+002B2	ʲ	\^j	Modifier Letter Small J
U+002B3	ʳ	\^r	Modifier Letter Small R
U+002B7	ʷ	\^w	Modifier Letter Small W
U+002B8	ʸ	\^y	Modifier Letter Small Y
U+002BC	ʼ	\rasp	Modifier Letter Apostrophe
U+002C8	ˈ	\verts	Modifier Letter Vertical Line
U+002CC	ˌ	\verti	Modifier Letter Low Vertical Line
U+002D0	ː	\lmrk	Modifier Letter Triangular Colon
U+002D1	ˑ	\hlmrk	Modifier Letter Half Triangular Colon
U+002D2	˒	\sbrhr	Modifier Letter Centred Right Half Ring / Modifier Letter Centered Right Half Ring
U+002D3	˓	\sblhr	Modifier Letter Centred Left Half Ring / Modifier Letter Centered Left Half Ring
U+002D4	˔	\rais	Modifier Letter Up Tack
U+002D5	˕	\low	Modifier Letter Down Tack
U+002D8	˘	\u	Breve / Spacing Breve
U+002DC	˜	\tildelow	Small Tilde / Spacing Tilde
U+002E1	ˡ	\^l	Modifier Letter Small L
U+002E2	ˢ	\^s	Modifier Letter Small S
U+002E3	ˣ	\^x	Modifier Letter Small X
U+00300	 ̀ 	\grave	Combining Grave Accent / Non-Spacing Grave
U+00301	 ́ 	\acute	Combining Acute Accent / Non-Spacing Acute
U+00302	 ̂ 	\hat	Combining Circumflex Accent / Non-Spacing Circumflex
U+00303	 ̃ 	\tilde	Combining Tilde / Non-Spacing Tilde
U+00304	 ̄ 	\bar	Combining Macron / Non-Spacing Macron
U+00305	 ̅ 	\overbar	Combining Overline / Non-Spacing Overscore
U+00306	 ̆ 	\breve	Combining Breve / Non-Spacing Breve
U+00307	 ̇ 	\dot	Combining Dot Above / Non-Spacing Dot Above
U+00308	 ̈ 	\ddot	Combining Diaeresis / Non-Spacing Diaeresis
U+00309	 ̉ 	\ovhook	Combining Hook Above / Non-Spacing Hook Above
U+0030A	 ̊ 	\ocirc	Combining Ring Above / Non-Spacing Ring Above
U+0030B	 ̋ 	\H	Combining Double Acute Accent / Non-Spacing Double Acute
U+0030C	 ̌ 	\check	Combining Caron / Non-Spacing Hacek
U+00310	 ̐ 	\candra	Combining Candrabindu / Non-Spacing Candrabindu
U+00312	 ̒ 	\oturnedcomma	Combining Turned Comma Above / Non-Spacing Turned Comma Above
U+00315	 ̕ 	\ocommatopright	Combining Comma Above Right / Non-Spacing Comma Above Right
U+0031A	 ̚ 	\droang	Combining Left Angle Above / Non-Spacing Left Angle Above
U+00321	 ̡ 	\palh	Combining Palatalized Hook Below / Non-Spacing Palatalized Hook Below
U+00322	 ̢ 	\rh	Combining Retroflex Hook Below / Non-Spacing Retroflex Hook Below
U+00327	 ̧ 	\c	Combining Cedilla / Non-Spacing Cedilla
U+00328	 ̨ 	\k	Combining Ogonek / Non-Spacing Ogonek
U+0032A	 ̪ 	\sbbrg	Combining Bridge Below / Non-Spacing Bridge Below
U+00330	 ̰ 	\wideutilde	Combining Tilde Below / Non-Spacing Tilde Below
U+00332	 ̲ 	\underbar	Combining Low Line / Non-Spacing Underscore
U+00336	 ̶ 	\strike, \sout	Combining Long Stroke Overlay / Non-Spacing Long Bar Overlay
U+00338	 ̸ 	\not	Combining Long Solidus Overlay / Non-Spacing Long Slash Overlay
U+0034D	 ͍ 	\underleftrightarrow

## License

The license of this work is [CC0](https://creativecommons.org/publicdomain/zero/1.0/), which corresponds to "public domain".

### Exceptions

The images in `logos` are subject to other copyright from other parties:

- `UPB_LOGO_GB_RGB_15.pdf` and `UPB_Logo_RGB_D_2012.pdf` are copyright Paderborn University.
  Refer to <https://www.uni-paderborn.de/universitaet/marketing/design-vorgaben-templates/> for proper use.
- `UBP-background-picture.*` are demonstration files generated using an educational edition of Microsoft Office.
  They can be used in a scientific context only.
  For commercial use, please change them.
- `UBP-background-picture.pdf` is generated out of `UBP-background-picture.pptx` and is free for personal use only.
