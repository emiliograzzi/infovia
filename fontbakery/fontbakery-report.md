## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[17] Infovia-BoldItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts CJK vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics">com.google.fonts/check/cjk_vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2 fsSelection bit 7 must be disabled [code: bad-fselection-bit7]
* 🔥 **FAIL** OS/2.sTypoAscender is "950" it should be 880 [code: bad-OS/2.sTypoAscender]
* 🔥 **FAIL** OS/2.sTypoDescender is "-350" it should be -120 [code: bad-OS/2.sTypoDescender]
* 🔥 **FAIL** hhea.ascent must match OS/2.usWinAscent [code: ascent-mismatch]
* 🔥 **FAIL** hhea.descent must match absolute value of OS/2.usWinDescent [code: descent-mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=14] [code: http-in-license-info]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain less than 40 CJK characters? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_not_enough_glyphs">com.google.fonts/check/cjk_not_enough_glyphs</a>)</summary><div>


* ⚠ **WARN** There are only 4 CJK glyphs when there needs to be at least 40 in order to support the smallest CJK writing system, Hangul.
The following CJK glyphs were found:
['arrownw', 'arrowne', 'arrowse', 'arrowsw']
Please check that these glyphs have the correct unicodes. [code: cjk-not-enough-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotbelowcomb.cap

	- uni1E37.ss03 

	- zero.slash
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni03BC	Contours detected: 2	Expected: 1

	- Glyph name: thorn	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: thorn	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni03BC	Contours detected: 2	Expected: 1 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain chws and vchw features? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/cjk_chws_feature">com.google.fonts/check/cjk_chws_feature</a>)</summary><div>


* ⚠ **WARN** chws feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-chws-feature]
* ⚠ **WARN** vchw feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-vchw-feature]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 499 among a set of 4 math glyphs.
The following math glyphs have a different width, though:

Width = 475:
less

Width = 512:
notequal, equal

Width = 476:
greater

Width = 532:
multiply, logicalnot

Width = 534:
approxequal

Width = 504:
lessequal

Width = 500:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 commabelowcomb (U+0326) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=210.0,Y=700.5 (should be at cap-height 700?)

	* six (U+0036): X=460.5,Y=698.0 (should be at cap-height 700?)

	* C (U+0043): X=373.0,Y=1.5 (should be at baseline 0?)

	* G (U+0047): X=511.5,Y=698.0 (should be at cap-height 700?)

	* S (U+0053): X=474.5,Y=698.0 (should be at cap-height 700?)

	* a (U+0061): X=206.0,Y=515.5 (should be at x-height 515?)

	* a (U+0061): X=225.5,Y=2.0 (should be at baseline 0?)

	* e (U+0065): X=338.0,Y=-1.0 (should be at baseline 0?)

	* s (U+0073): X=369.0,Y=516.5 (should be at x-height 515?)

	* braceright (U+007D): X=58.0,Y=-1.0 (should be at baseline 0?)

	* degree (U+00B0): X=343.0,Y=698.0 (should be at cap-height 700?)

	* threequarters (U+00BE): X=165.5,Y=701.0 (should be at cap-height 700?)

	* Ccedilla (U+00C7): X=373.0,Y=1.5 (should be at baseline 0?)

	* Thorn (U+00DE): X=159.0,Y=702.0 (should be at cap-height 700?)

	* Thorn (U+00DE): X=292.0,Y=702.0 (should be at cap-height 700?)

	* germandbls (U+00DF): X=243.0,Y=700.5 (should be at cap-height 700?)

	* germandbls (U+00DF): X=504.0,Y=699.5 (should be at cap-height 700?)

	* agrave (U+00E0): X=225.5,Y=2.0 (should be at baseline 0?)

	* aacute (U+00E1): X=225.5,Y=2.0 (should be at baseline 0?)

	* acircumflex (U+00E2): X=225.5,Y=2.0 (should be at baseline 0?)

	* atilde (U+00E3): X=225.5,Y=2.0 (should be at baseline 0?)

	* atilde (U+00E3): X=475.0,Y=699.0 (should be at cap-height 700?)

	* adieresis (U+00E4): X=225.5,Y=2.0 (should be at baseline 0?)

	* aring (U+00E5): X=225.5,Y=2.0 (should be at baseline 0?)

	* ae (U+00E6): X=598.5,Y=-1.0 (should be at baseline 0?)

	* egrave (U+00E8): X=338.0,Y=-1.0 (should be at baseline 0?)

	* eacute (U+00E9): X=338.0,Y=-1.0 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=338.0,Y=-1.0 (should be at baseline 0?)

	* edieresis (U+00EB): X=338.0,Y=-1.0 (should be at baseline 0?)

	* eth (U+00F0): X=281.5,Y=700.5 (should be at cap-height 700?)

	* ntilde (U+00F1): X=496.0,Y=699.0 (should be at cap-height 700?)

	* otilde (U+00F5): X=487.0,Y=699.0 (should be at cap-height 700?)

	* oslash (U+00F8): X=144.0,Y=1.0 (should be at baseline 0?)

	* amacron (U+0101): X=225.5,Y=2.0 (should be at baseline 0?)

	* abreve (U+0103): X=225.5,Y=2.0 (should be at baseline 0?)

	* aogonek (U+0105): X=225.5,Y=2.0 (should be at baseline 0?)

	* Cacute (U+0106): X=373.0,Y=1.5 (should be at baseline 0?)

	* Ccircumflex (U+0108): X=373.0,Y=1.5 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=373.0,Y=1.5 (should be at baseline 0?)

	* Ccaron (U+010C): X=373.0,Y=1.5 (should be at baseline 0?)

	* emacron (U+0113): X=338.0,Y=-1.0 (should be at baseline 0?)

	* ebreve (U+0115): X=338.0,Y=-1.0 (should be at baseline 0?)

	* edotaccent (U+0117): X=338.0,Y=-1.0 (should be at baseline 0?)

	* eogonek (U+0119): X=338.0,Y=-1.0 (should be at baseline 0?)

	* eogonek (U+0119): X=281.0,Y=0.5 (should be at baseline 0?)

	* ecaron (U+011B): X=338.0,Y=-1.0 (should be at baseline 0?)

	* Gcircumflex (U+011C): X=511.5,Y=698.0 (should be at cap-height 700?)

	* Gbreve (U+011E): X=511.5,Y=698.0 (should be at cap-height 700?)

	* Gdotaccent (U+0120): X=511.5,Y=698.0 (should be at cap-height 700?)

	* Gcommabelow (U+0122): X=511.5,Y=698.0 (should be at cap-height 700?)

	* itilde (U+0129): X=354.0,Y=699.0 (should be at cap-height 700?)

	* oe (U+0153): X=643.0,Y=-1.0 (should be at baseline 0?)

	* Sacute (U+015A): X=474.5,Y=698.0 (should be at cap-height 700?)

	* Scircumflex (U+015C): X=474.5,Y=698.0 (should be at cap-height 700?)

	* Scedilla (U+015E): X=474.5,Y=698.0 (should be at cap-height 700?)

	* Scaron (U+0160): X=474.5,Y=698.0 (should be at cap-height 700?)

	* utilde (U+0169): X=493.0,Y=699.0 (should be at cap-height 700?)

	* aringacute (U+01FB): X=225.5,Y=2.0 (should be at baseline 0?)

	* aringacute (U+01FB): X=413.0,Y=948.0 (should be at ascender 950?)

	* aringacute (U+01FB): X=559.0,Y=948.0 (should be at ascender 950?)

	* aeacute (U+01FD): X=598.5,Y=-1.0 (should be at baseline 0?)

	* oslashacute (U+01FF): X=144.0,Y=1.0 (should be at baseline 0?)

	* Scommabelow (U+0218): X=474.5,Y=698.0 (should be at cap-height 700?)

	* tilde (U+02DC): X=169.5,Y=701.5 (should be at cap-height 700?)

	* tildecomb (U+0303): X=169.5,Y=701.5 (should be at cap-height 700?)

	* pi (U+03C0): X=451.0,Y=-2.0 (should be at baseline 0?)

	* uni2070 (U+2070): X=270.5,Y=702.0 (should be at cap-height 700?)

	* uni2070 (U+2070): X=212.5,Y=700.5 (should be at cap-height 700?)

	* uni2083 (U+2083): X=220.0,Y=2.0 (should be at baseline 0?) 

	* Euro (U+20AC): X=464.5,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* M (U+004D) contains a short segment L<<641.0,540.0>--<638.0,540.0>>

	* M (U+004D) contains a short segment L<<258.0,540.0>--<255.0,540.0>>

	* N (U+004E) contains a short segment L<<441.0,208.0>--<451.0,208.0>>

	* N (U+004E) contains a short segment L<<252.0,501.0>--<242.0,501.0>>

	* Q (U+0051) contains a short segment B<<294.0,-11.0>-<288.0,-11.0>-<281.0,-11.0>>

	* V (U+0056) contains a short segment L<<258.0,116.0>--<276.0,116.0>>

	* W (U+0057) contains a short segment L<<221.0,125.0>--<233.0,125.0>>

	* W (U+0057) contains a short segment L<<579.0,125.0>--<591.0,125.0>>

	* b (U+0062) contains a short segment L<<239.0,487.0>--<237.0,475.0>>

	* g (U+0067) contains a short segment L<<298.0,29.0>--<299.0,37.0>>

	* q (U+0071) contains a short segment L<<297.0,29.0>--<298.0,37.0>>

	* v (U+0076) contains a short segment L<<210.0,88.0>--<222.0,88.0>>

	* w (U+0077) contains a short segment L<<187.0,103.0>--<197.0,103.0>>

	* w (U+0077) contains a short segment L<<488.0,103.0>--<499.0,103.0>>

	* y (U+0079) contains a short segment L<<214.0,110.0>--<224.0,110.0>>

	* paragraph (U+00B6) contains a short segment L<<231.0,280.0>--<229.0,280.0>>

	* Ntilde (U+00D1) contains a short segment L<<441.0,208.0>--<451.0,208.0>>

	* Ntilde (U+00D1) contains a short segment L<<252.0,501.0>--<242.0,501.0>>

	* yacute (U+00FD) contains a short segment L<<214.0,110.0>--<224.0,110.0>>

	* ydieresis (U+00FF) contains a short segment L<<214.0,110.0>--<224.0,110.0>>

	* gcircumflex (U+011D) contains a short segment L<<298.0,29.0>--<299.0,37.0>>

	* gbreve (U+011F) contains a short segment L<<298.0,29.0>--<299.0,37.0>>

	* gdotaccent (U+0121) contains a short segment L<<298.0,29.0>--<299.0,37.0>>

	* gcommaabove (U+0123) contains a short segment L<<298.0,29.0>--<299.0,37.0>>

	* Nacute (U+0143) contains a short segment L<<441.0,208.0>--<451.0,208.0>>

	* Nacute (U+0143) contains a short segment L<<252.0,501.0>--<242.0,501.0>>

	* Ncommabelow (U+0145) contains a short segment L<<441.0,208.0>--<451.0,208.0>>

	* Ncommabelow (U+0145) contains a short segment L<<252.0,501.0>--<242.0,501.0>>

	* Ncaron (U+0147) contains a short segment L<<441.0,208.0>--<451.0,208.0>>

	* Ncaron (U+0147) contains a short segment L<<252.0,501.0>--<242.0,501.0>>

	* Eng (U+014A) contains a short segment L<<441.0,208.0>--<451.0,208.0>>

	* Eng (U+014A) contains a short segment L<<533.0,0.0>--<530.0,-12.0>>

	* Eng (U+014A) contains a short segment L<<398.0,0.0>--<373.0,0.0>>

	* Eng (U+014A) contains a short segment L<<252.0,501.0>--<242.0,501.0>>

	* OE (U+0152) contains a short segment L<<512.0,700.0>--<512.0,700.0>>

	* Wcircumflex (U+0174) contains a short segment L<<221.0,125.0>--<233.0,125.0>>

	* Wcircumflex (U+0174) contains a short segment L<<579.0,125.0>--<591.0,125.0>>

	* wcircumflex (U+0175) contains a short segment L<<187.0,103.0>--<197.0,103.0>>

	* wcircumflex (U+0175) contains a short segment L<<488.0,103.0>--<499.0,103.0>>

	* ycircumflex (U+0177) contains a short segment L<<214.0,110.0>--<224.0,110.0>>

	* Wgrave (U+1E80) contains a short segment L<<221.0,125.0>--<233.0,125.0>>

	* Wgrave (U+1E80) contains a short segment L<<579.0,125.0>--<591.0,125.0>>

	* wgrave (U+1E81) contains a short segment L<<187.0,103.0>--<197.0,103.0>>

	* wgrave (U+1E81) contains a short segment L<<488.0,103.0>--<499.0,103.0>>

	* Wacute (U+1E82) contains a short segment L<<221.0,125.0>--<233.0,125.0>>

	* Wacute (U+1E82) contains a short segment L<<579.0,125.0>--<591.0,125.0>>

	* wacute (U+1E83) contains a short segment L<<187.0,103.0>--<197.0,103.0>>

	* wacute (U+1E83) contains a short segment L<<488.0,103.0>--<499.0,103.0>>

	* Wdieresis (U+1E84) contains a short segment L<<221.0,125.0>--<233.0,125.0>>

	* Wdieresis (U+1E84) contains a short segment L<<579.0,125.0>--<591.0,125.0>>

	* wdieresis (U+1E85) contains a short segment L<<187.0,103.0>--<197.0,103.0>>

	* wdieresis (U+1E85) contains a short segment L<<488.0,103.0>--<499.0,103.0>>

	* ygrave (U+1EF3) contains a short segment L<<214.0,110.0>--<224.0,110.0>>

	* uni2077 (U+2077) contains a short segment L<<256.0,706.0>--<256.0,712.0>> 

	* uni2087 (U+2087) contains a short segment L<<151.0,163.0>--<151.0,169.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Eng (U+014A): L<<669.0,700.0>--<533.0,0.0>> -> L<<533.0,0.0>--<530.0,-12.0>>

	* OE (U+0152): L<<512.0,700.0>--<512.0,700.0>> -> L<<512.0,700.0>--<922.0,700.0>>

	* b (U+0062): L<<288.0,730.0>--<239.0,487.0>> -> L<<239.0,487.0>--<237.0,475.0>>

	* g (U+0067): L<<281.0,-52.0>--<298.0,29.0>> -> L<<298.0,29.0>--<299.0,37.0>>

	* gbreve (U+011F): L<<281.0,-52.0>--<298.0,29.0>> -> L<<298.0,29.0>--<299.0,37.0>>

	* gcircumflex (U+011D): L<<281.0,-52.0>--<298.0,29.0>> -> L<<298.0,29.0>--<299.0,37.0>>

	* gcommaabove (U+0123): L<<281.0,-52.0>--<298.0,29.0>> -> L<<298.0,29.0>--<299.0,37.0>>

	* gdotaccent (U+0121): L<<281.0,-52.0>--<298.0,29.0>> -> L<<298.0,29.0>--<299.0,37.0>> 

	* q (U+0071): L<<249.0,-210.0>--<297.0,29.0>> -> L<<297.0,29.0>--<298.0,37.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* trademark (U+2122): L<<464.0,331.0>--<505.0,539.0>>/L<<505.0,539.0>--<422.0,358.0>> = 13.483538567405818 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[15] Infovia-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts CJK vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics">com.google.fonts/check/cjk_vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2 fsSelection bit 7 must be disabled [code: bad-fselection-bit7]
* 🔥 **FAIL** OS/2.sTypoAscender is "950" it should be 880 [code: bad-OS/2.sTypoAscender]
* 🔥 **FAIL** OS/2.sTypoDescender is "-350" it should be -120 [code: bad-OS/2.sTypoDescender]
* 🔥 **FAIL** hhea.ascent must match OS/2.usWinAscent [code: ascent-mismatch]
* 🔥 **FAIL** hhea.descent must match absolute value of OS/2.usWinDescent [code: descent-mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=14] [code: http-in-license-info]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain less than 40 CJK characters? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_not_enough_glyphs">com.google.fonts/check/cjk_not_enough_glyphs</a>)</summary><div>


* ⚠ **WARN** There are only 4 CJK glyphs when there needs to be at least 40 in order to support the smallest CJK writing system, Hangul.
The following CJK glyphs were found:
['arrownw', 'arrowne', 'arrowse', 'arrowsw']
Please check that these glyphs have the correct unicodes. [code: cjk-not-enough-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotbelowcomb.cap

	- one.pnum 

	- zero.slash
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni03BC	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni03BC	Contours detected: 2	Expected: 1 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain chws and vchw features? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/cjk_chws_feature">com.google.fonts/check/cjk_chws_feature</a>)</summary><div>


* ⚠ **WARN** chws feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-chws-feature]
* ⚠ **WARN** vchw feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-vchw-feature]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 492 among a set of 4 math glyphs.
The following math glyphs have a different width, though:

Width = 483:
greater, less

Width = 496:
notequal, equal

Width = 532:
multiply, logicalnot

Width = 526:
approxequal

Width = 508:
lessequal, greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* asterisk (U+002A): X=220.0,Y=699.0 (should be at cap-height 700?)

	* two (U+0032): X=147.0,Y=698.5 (should be at cap-height 700?)

	* three (U+0033): X=139.0,Y=-1.0 (should be at baseline 0?)

	* three (U+0033): X=141.0,Y=699.0 (should be at cap-height 700?)

	* six (U+0036): X=387.5,Y=701.5 (should be at cap-height 700?)

	* question (U+003F): X=95.5,Y=699.5 (should be at cap-height 700?)

	* question (U+003F): X=119.0,Y=1.0 (should be at baseline 0?)

	* question (U+003F): X=186.0,Y=1.0 (should be at baseline 0?)

	* G (U+0047): X=410.0,Y=701.0 (should be at cap-height 700?)

	* J (U+004A): X=169.5,Y=2.0 (should be at baseline 0?)

	* a (U+0061): X=382.5,Y=2.0 (should be at baseline 0?)

	* a (U+0061): X=258.0,Y=2.0 (should be at baseline 0?)

	* b (U+0062): X=72.0,Y=-1.0 (should be at baseline 0?)

	* b (U+0062): X=72.0,Y=-1.0 (should be at baseline 0?)

	* d (U+0064): X=358.0,Y=506.0 (should be at x-height 507?)

	* g (U+0067): X=420.0,Y=508.0 (should be at x-height 507?)

	* g (U+0067): X=292.0,Y=2.0 (should be at baseline 0?)

	* q (U+0071): X=420.0,Y=508.0 (should be at x-height 507?)

	* q (U+0071): X=292.0,Y=2.0 (should be at baseline 0?)

	* s (U+0073): X=123.5,Y=-1.5 (should be at baseline 0?)

	* s (U+0073): X=298.0,Y=507.5 (should be at x-height 507?)

	* braceleft (U+007B): X=158.5,Y=701.0 (should be at cap-height 700?)

	* braceright (U+007D): X=163.0,Y=701.0 (should be at cap-height 700?)

	* paragraph (U+00B6): X=205.0,Y=699.0 (should be at cap-height 700?)

	* paragraph (U+00B6): X=503.0,Y=699.0 (should be at cap-height 700?)

	* cedilla (U+00B8): X=75.0,Y=2.0 (should be at baseline 0?)

	* cedilla (U+00B8): X=112.0,Y=2.0 (should be at baseline 0?)

	* threequarters (U+00BE): X=80.5,Y=699.5 (should be at cap-height 700?)

	* Ccedilla (U+00C7): X=272.0,Y=2.0 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=309.0,Y=2.0 (should be at baseline 0?)

	* agrave (U+00E0): X=382.5,Y=2.0 (should be at baseline 0?)

	* agrave (U+00E0): X=258.0,Y=2.0 (should be at baseline 0?)

	* aacute (U+00E1): X=382.5,Y=2.0 (should be at baseline 0?)

	* aacute (U+00E1): X=258.0,Y=2.0 (should be at baseline 0?)

	* acircumflex (U+00E2): X=382.5,Y=2.0 (should be at baseline 0?)

	* acircumflex (U+00E2): X=258.0,Y=2.0 (should be at baseline 0?)

	* atilde (U+00E3): X=382.5,Y=2.0 (should be at baseline 0?)

	* atilde (U+00E3): X=258.0,Y=2.0 (should be at baseline 0?)

	* adieresis (U+00E4): X=382.5,Y=2.0 (should be at baseline 0?)

	* adieresis (U+00E4): X=258.0,Y=2.0 (should be at baseline 0?)

	* aring (U+00E5): X=382.5,Y=2.0 (should be at baseline 0?)

	* aring (U+00E5): X=258.0,Y=2.0 (should be at baseline 0?)

	* ccedilla (U+00E7): X=215.0,Y=2.0 (should be at baseline 0?)

	* ccedilla (U+00E7): X=252.0,Y=2.0 (should be at baseline 0?)

	* amacron (U+0101): X=382.5,Y=2.0 (should be at baseline 0?)

	* amacron (U+0101): X=258.0,Y=2.0 (should be at baseline 0?)

	* abreve (U+0103): X=382.5,Y=2.0 (should be at baseline 0?)

	* abreve (U+0103): X=258.0,Y=2.0 (should be at baseline 0?)

	* aogonek (U+0105): X=382.5,Y=2.0 (should be at baseline 0?)

	* aogonek (U+0105): X=258.0,Y=2.0 (should be at baseline 0?)

	* Gcircumflex (U+011C): X=410.0,Y=701.0 (should be at cap-height 700?)

	* gcircumflex (U+011D): X=292.0,Y=2.0 (should be at baseline 0?)

	* Gbreve (U+011E): X=410.0,Y=701.0 (should be at cap-height 700?)

	* gbreve (U+011F): X=292.0,Y=2.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=410.0,Y=701.0 (should be at cap-height 700?)

	* gdotaccent (U+0121): X=292.0,Y=2.0 (should be at baseline 0?)

	* Gcommabelow (U+0122): X=410.0,Y=701.0 (should be at cap-height 700?)

	* gcommaabove (U+0123): X=292.0,Y=2.0 (should be at baseline 0?)

	* IJ (U+0132): X=387.5,Y=2.0 (should be at baseline 0?)

	* Jcircumflex (U+0134): X=169.5,Y=2.0 (should be at baseline 0?)

	* eng (U+014B): X=377.0,Y=2.0 (should be at baseline 0?)

	* uni0156 (U+0156): X=265.0,Y=2.0 (should be at baseline 0?)

	* uni0156 (U+0156): X=302.0,Y=2.0 (should be at baseline 0?)

	* uni0157 (U+0157): X=85.0,Y=2.0 (should be at baseline 0?)

	* uni0157 (U+0157): X=122.0,Y=2.0 (should be at baseline 0?)

	* sacute (U+015B): X=123.5,Y=-1.5 (should be at baseline 0?)

	* scircumflex (U+015D): X=123.5,Y=-1.5 (should be at baseline 0?)

	* Scedilla (U+015E): X=226.0,Y=2.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=263.0,Y=2.0 (should be at baseline 0?)

	* scedilla (U+015F): X=123.5,Y=-1.5 (should be at baseline 0?)

	* scedilla (U+015F): X=194.0,Y=2.0 (should be at baseline 0?)

	* scedilla (U+015F): X=231.0,Y=2.0 (should be at baseline 0?)

	* scaron (U+0161): X=123.5,Y=-1.5 (should be at baseline 0?)

	* uni0162 (U+0162): X=225.0,Y=2.0 (should be at baseline 0?)

	* uni0162 (U+0162): X=262.0,Y=2.0 (should be at baseline 0?)

	* uni0163 (U+0163): X=180.0,Y=2.0 (should be at baseline 0?)

	* uni0163 (U+0163): X=217.0,Y=2.0 (should be at baseline 0?)

	* aringacute (U+01FB): X=382.5,Y=2.0 (should be at baseline 0?)

	* aringacute (U+01FB): X=258.0,Y=2.0 (should be at baseline 0?)

	* scommabelow (U+0219): X=123.5,Y=-1.5 (should be at baseline 0?)

	* uni0327 (U+0327): X=75.0,Y=2.0 (should be at baseline 0?) 

	* uni0327 (U+0327): X=112.0,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* dollar (U+0024) contains a short segment B<<266.0,-10.0>-<262.0,-10.0>-<258.0,-10.0>>

	* seven (U+0037) contains a short segment L<<387.0,637.0>--<387.0,646.0>>

	* M (U+004D) contains a short segment L<<609.0,631.0>--<604.0,631.0>>

	* M (U+004D) contains a short segment L<<147.0,631.0>--<143.0,631.0>>

	* N (U+004E) contains a short segment L<<470.0,87.0>--<480.0,87.0>>

	* N (U+004E) contains a short segment L<<151.0,613.0>--<141.0,613.0>>

	* W (U+0057) contains a short segment L<<216.0,60.0>--<227.0,60.0>>

	* W (U+0057) contains a short segment L<<569.0,60.0>--<580.0,60.0>>

	* v (U+0076) contains a short segment L<<217.0,47.0>--<228.0,47.0>>

	* w (U+0077) contains a short segment L<<186.0,50.0>--<194.0,50.0>>

	* w (U+0077) contains a short segment L<<495.0,50.0>--<503.0,50.0>>

	* y (U+0079) contains a short segment L<<218.0,47.0>--<229.0,47.0>>

	* paragraph (U+00B6) contains a short segment L<<211.0,330.0>--<205.0,330.0>>

	* Ntilde (U+00D1) contains a short segment L<<470.0,87.0>--<480.0,87.0>>

	* Ntilde (U+00D1) contains a short segment L<<151.0,613.0>--<141.0,613.0>>

	* ae (U+00E6) contains a short segment L<<329.0,254.0>--<329.0,254.0>>

	* yacute (U+00FD) contains a short segment L<<218.0,47.0>--<229.0,47.0>>

	* ydieresis (U+00FF) contains a short segment L<<218.0,47.0>--<229.0,47.0>>

	* Nacute (U+0143) contains a short segment L<<470.0,87.0>--<480.0,87.0>>

	* Nacute (U+0143) contains a short segment L<<151.0,613.0>--<141.0,613.0>>

	* Ncommabelow (U+0145) contains a short segment L<<470.0,87.0>--<480.0,87.0>>

	* Ncommabelow (U+0145) contains a short segment L<<151.0,613.0>--<141.0,613.0>>

	* Ncaron (U+0147) contains a short segment L<<470.0,87.0>--<480.0,87.0>>

	* Ncaron (U+0147) contains a short segment L<<151.0,613.0>--<141.0,613.0>>

	* Eng (U+014A) contains a short segment L<<470.0,87.0>--<480.0,87.0>>

	* Eng (U+014A) contains a short segment L<<541.0,0.0>--<541.0,0.0>>

	* Eng (U+014A) contains a short segment L<<151.0,613.0>--<141.0,613.0>>

	* Wcircumflex (U+0174) contains a short segment L<<216.0,60.0>--<227.0,60.0>>

	* Wcircumflex (U+0174) contains a short segment L<<569.0,60.0>--<580.0,60.0>>

	* wcircumflex (U+0175) contains a short segment L<<186.0,50.0>--<194.0,50.0>>

	* wcircumflex (U+0175) contains a short segment L<<495.0,50.0>--<503.0,50.0>>

	* ycircumflex (U+0177) contains a short segment L<<218.0,47.0>--<229.0,47.0>>

	* aeacute (U+01FD) contains a short segment L<<329.0,254.0>--<329.0,254.0>>

	* Wgrave (U+1E80) contains a short segment L<<216.0,60.0>--<227.0,60.0>>

	* Wgrave (U+1E80) contains a short segment L<<569.0,60.0>--<580.0,60.0>>

	* wgrave (U+1E81) contains a short segment L<<186.0,50.0>--<194.0,50.0>>

	* wgrave (U+1E81) contains a short segment L<<495.0,50.0>--<503.0,50.0>>

	* Wacute (U+1E82) contains a short segment L<<216.0,60.0>--<227.0,60.0>>

	* Wacute (U+1E82) contains a short segment L<<569.0,60.0>--<580.0,60.0>>

	* wacute (U+1E83) contains a short segment L<<186.0,50.0>--<194.0,50.0>>

	* wacute (U+1E83) contains a short segment L<<495.0,50.0>--<503.0,50.0>>

	* Wdieresis (U+1E84) contains a short segment L<<216.0,60.0>--<227.0,60.0>>

	* Wdieresis (U+1E84) contains a short segment L<<569.0,60.0>--<580.0,60.0>>

	* wdieresis (U+1E85) contains a short segment L<<186.0,50.0>--<194.0,50.0>>

	* wdieresis (U+1E85) contains a short segment L<<495.0,50.0>--<503.0,50.0>>

	* ygrave (U+1EF3) contains a short segment L<<218.0,47.0>--<229.0,47.0>>

	* uni2077 (U+2077) contains a short segment L<<185.0,747.0>--<185.0,752.0>>

	* uni2087 (U+2087) contains a short segment L<<185.0,179.0>--<185.0,184.0>>

	* summation (U+2211) contains a short segment L<<91.0,697.0>--<96.0,679.0>> 

	* radical (U+221A) contains a short segment L<<274.0,-87.0>--<276.0,-87.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* asterisk (U+002A): L<<227.0,559.0>--<345.0,560.0>>

	* asterisk (U+002A): L<<345.0,512.0>--<225.0,513.0>>

	* dagger (U+2020): L<<178.0,-109.0>--<176.0,443.0>>

	* dagger (U+2020): L<<238.0,443.0>--<237.0,-109.0>>

	* exclam (U+0021): L<<144.0,695.0>--<142.0,220.0>>

	* exclam (U+0021): L<<82.0,220.0>--<79.0,695.0>>

	* exclamdown (U+00A1): L<<134.0,281.0>--<136.0,-195.0>>

	* exclamdown (U+00A1): L<<71.0,-195.0>--<74.0,281.0>>

	* florin (U+0192): L<<166.0,-52.0>--<168.0,351.0>>

	* florin (U+0192): L<<229.0,351.0>--<227.0,-54.0>>

	* integral (U+222B): L<<157.0,-3.0>--<161.0,559.0>>

	* integral (U+222B): L<<223.0,559.0>--<219.0,-3.0>>

	* numbersign (U+0023): L<<134.0,489.0>--<135.0,670.0>>

	* numbersign (U+0023): L<<398.0,436.0>--<397.0,232.0>> 

	* numbersign (U+0023): L<<399.0,670.0>--<398.0,489.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] Infovia-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts CJK vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics">com.google.fonts/check/cjk_vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2 fsSelection bit 7 must be disabled [code: bad-fselection-bit7]
* 🔥 **FAIL** OS/2.sTypoAscender is "950" it should be 880 [code: bad-OS/2.sTypoAscender]
* 🔥 **FAIL** OS/2.sTypoDescender is "-350" it should be -120 [code: bad-OS/2.sTypoDescender]
* 🔥 **FAIL** hhea.ascent must match OS/2.usWinAscent [code: ascent-mismatch]
* 🔥 **FAIL** hhea.descent must match absolute value of OS/2.usWinDescent [code: descent-mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=14] [code: http-in-license-info]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain less than 40 CJK characters? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_not_enough_glyphs">com.google.fonts/check/cjk_not_enough_glyphs</a>)</summary><div>


* ⚠ **WARN** There are only 4 CJK glyphs when there needs to be at least 40 in order to support the smallest CJK writing system, Hangul.
The following CJK glyphs were found:
['arrownw', 'arrowne', 'arrowse', 'arrowsw']
Please check that these glyphs have the correct unicodes. [code: cjk-not-enough-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotbelowcomb.cap

	- one.pnum 

	- zero.slash
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni03BC	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni03BC	Contours detected: 2	Expected: 1 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain chws and vchw features? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/cjk_chws_feature">com.google.fonts/check/cjk_chws_feature</a>)</summary><div>


* ⚠ **WARN** chws feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-chws-feature]
* ⚠ **WARN** vchw feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-vchw-feature]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 496 among a set of 4 math glyphs.
The following math glyphs have a different width, though:

Width = 482:
greater, less

Width = 503:
notequal, equal

Width = 532:
multiply, logicalnot

Width = 528:
approxequal

Width = 507:
lessequal

Width = 508:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* dollar (U+0024) contains a short segment B<<275.0,677.0>-<283.0,677.0>-<291.0,677.0>>

	* dollar (U+0024) contains a short segment B<<265.0,-10.0>-<261.0,-10.0>-<258.0,-10.0>>

	* seven (U+0037) contains a short segment L<<367.0,619.0>--<367.0,628.0>>

	* M (U+004D) contains a short segment L<<601.0,600.0>--<597.0,600.0>>

	* M (U+004D) contains a short segment L<<167.0,600.0>--<163.0,600.0>>

	* N (U+004E) contains a short segment L<<464.0,133.0>--<474.0,133.0>>

	* N (U+004E) contains a short segment L<<169.0,567.0>--<160.0,567.0>>

	* W (U+0057) contains a short segment L<<228.0,83.0>--<239.0,83.0>>

	* W (U+0057) contains a short segment L<<583.0,83.0>--<594.0,83.0>>

	* v (U+0076) contains a short segment L<<229.0,61.0>--<240.0,61.0>>

	* w (U+0077) contains a short segment L<<199.0,69.0>--<207.0,69.0>>

	* w (U+0077) contains a short segment L<<505.0,69.0>--<513.0,69.0>>

	* y (U+0079) contains a short segment L<<229.0,61.0>--<240.0,61.0>>

	* paragraph (U+00B6) contains a short segment L<<218.0,314.0>--<212.0,314.0>>

	* Ntilde (U+00D1) contains a short segment L<<464.0,133.0>--<474.0,133.0>>

	* Ntilde (U+00D1) contains a short segment L<<169.0,567.0>--<160.0,567.0>>

	* yacute (U+00FD) contains a short segment L<<229.0,61.0>--<240.0,61.0>>

	* ydieresis (U+00FF) contains a short segment L<<229.0,61.0>--<240.0,61.0>>

	* Nacute (U+0143) contains a short segment L<<464.0,133.0>--<474.0,133.0>>

	* Nacute (U+0143) contains a short segment L<<169.0,567.0>--<160.0,567.0>>

	* Ncommabelow (U+0145) contains a short segment L<<464.0,133.0>--<474.0,133.0>>

	* Ncommabelow (U+0145) contains a short segment L<<169.0,567.0>--<160.0,567.0>>

	* Ncaron (U+0147) contains a short segment L<<464.0,133.0>--<474.0,133.0>>

	* Ncaron (U+0147) contains a short segment L<<169.0,567.0>--<160.0,567.0>>

	* Eng (U+014A) contains a short segment L<<464.0,133.0>--<474.0,133.0>>

	* Eng (U+014A) contains a short segment L<<169.0,567.0>--<160.0,567.0>>

	* Wcircumflex (U+0174) contains a short segment L<<228.0,83.0>--<239.0,83.0>>

	* Wcircumflex (U+0174) contains a short segment L<<583.0,83.0>--<594.0,83.0>>

	* wcircumflex (U+0175) contains a short segment L<<199.0,69.0>--<207.0,69.0>>

	* wcircumflex (U+0175) contains a short segment L<<505.0,69.0>--<513.0,69.0>>

	* ycircumflex (U+0177) contains a short segment L<<229.0,61.0>--<240.0,61.0>>

	* Wgrave (U+1E80) contains a short segment L<<228.0,83.0>--<239.0,83.0>>

	* Wgrave (U+1E80) contains a short segment L<<583.0,83.0>--<594.0,83.0>>

	* wgrave (U+1E81) contains a short segment L<<199.0,69.0>--<207.0,69.0>>

	* wgrave (U+1E81) contains a short segment L<<505.0,69.0>--<513.0,69.0>>

	* Wacute (U+1E82) contains a short segment L<<228.0,83.0>--<239.0,83.0>>

	* Wacute (U+1E82) contains a short segment L<<583.0,83.0>--<594.0,83.0>>

	* wacute (U+1E83) contains a short segment L<<199.0,69.0>--<207.0,69.0>>

	* wacute (U+1E83) contains a short segment L<<505.0,69.0>--<513.0,69.0>>

	* Wdieresis (U+1E84) contains a short segment L<<228.0,83.0>--<239.0,83.0>>

	* Wdieresis (U+1E84) contains a short segment L<<583.0,83.0>--<594.0,83.0>>

	* wdieresis (U+1E85) contains a short segment L<<199.0,69.0>--<207.0,69.0>>

	* wdieresis (U+1E85) contains a short segment L<<505.0,69.0>--<513.0,69.0>>

	* ygrave (U+1EF3) contains a short segment L<<229.0,61.0>--<240.0,61.0>>

	* uni2077 (U+2077) contains a short segment L<<180.0,736.0>--<180.0,741.0>>

	* uni2087 (U+2087) contains a short segment L<<180.0,176.0>--<180.0,181.0>>

	* summation (U+2211) contains a short segment L<<109.0,681.0>--<118.0,671.0>> 

	* summation (U+2211) contains a short segment L<<118.0,-75.0>--<109.0,-88.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* summation (U+2211): L<<365.0,281.0>--<118.0,-75.0>> -> L<<118.0,-75.0>--<109.0,-88.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Eng (U+014A): L<<160.0,567.0>--<159.0,0.0>>

	* N (U+004E): L<<160.0,567.0>--<159.0,0.0>>

	* Nacute (U+0143): L<<160.0,567.0>--<159.0,0.0>>

	* Ncaron (U+0147): L<<160.0,567.0>--<159.0,0.0>>

	* Ncommabelow (U+0145): L<<160.0,567.0>--<159.0,0.0>>

	* Ntilde (U+00D1): L<<160.0,567.0>--<159.0,0.0>>

	* dagger (U+2020): L<<174.0,-117.0>--<172.0,423.0>>

	* dagger (U+2020): L<<258.0,423.0>--<256.0,-117.0>>

	* exclam (U+0021): L<<166.0,691.0>--<162.0,225.0>>

	* exclam (U+0021): L<<80.0,225.0>--<76.0,691.0>>

	* exclamdown (U+00A1): L<<155.0,276.0>--<159.0,-190.0>>

	* florin (U+0192): L<<242.0,349.0>--<239.0,-49.0>>

	* numbersign (U+0023): L<<122.0,0.0>--<123.0,170.0>>

	* numbersign (U+0023): L<<124.0,240.0>--<125.0,426.0>>

	* numbersign (U+0023): L<<125.0,496.0>--<126.0,669.0>>

	* numbersign (U+0023): L<<200.0,669.0>--<199.0,496.0>>

	* numbersign (U+0023): L<<333.0,240.0>--<334.0,426.0>>

	* numbersign (U+0023): L<<335.0,496.0>--<336.0,669.0>>

	* numbersign (U+0023): L<<408.0,426.0>--<407.0,240.0>> 

	* pi (U+03C0): L<<333.0,154.0>--<332.0,423.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] Infovia-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts CJK vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics">com.google.fonts/check/cjk_vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2 fsSelection bit 7 must be disabled [code: bad-fselection-bit7]
* 🔥 **FAIL** OS/2.sTypoAscender is "950" it should be 880 [code: bad-OS/2.sTypoAscender]
* 🔥 **FAIL** OS/2.sTypoDescender is "-350" it should be -120 [code: bad-OS/2.sTypoDescender]
* 🔥 **FAIL** hhea.ascent must match OS/2.usWinAscent [code: ascent-mismatch]
* 🔥 **FAIL** hhea.descent must match absolute value of OS/2.usWinDescent [code: descent-mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=14] [code: http-in-license-info]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain less than 40 CJK characters? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_not_enough_glyphs">com.google.fonts/check/cjk_not_enough_glyphs</a>)</summary><div>


* ⚠ **WARN** There are only 4 CJK glyphs when there needs to be at least 40 in order to support the smallest CJK writing system, Hangul.
The following CJK glyphs were found:
['arrownw', 'arrowne', 'arrowse', 'arrowsw']
Please check that these glyphs have the correct unicodes. [code: cjk-not-enough-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotbelowcomb.cap

	- one.pnum 

	- zero.slash
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni03BC	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni03BC	Contours detected: 2	Expected: 1 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain chws and vchw features? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/cjk_chws_feature">com.google.fonts/check/cjk_chws_feature</a>)</summary><div>


* ⚠ **WARN** chws feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-chws-feature]
* ⚠ **WARN** vchw feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-vchw-feature]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 503 among a set of 4 math glyphs.
The following math glyphs have a different width, though:

Width = 481:
greater, less

Width = 515:
notequal, equal

Width = 532:
multiply, logicalnot

Width = 533:
approxequal

Width = 506:
lessequal

Width = 507:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* two (U+0032): X=138.0,Y=699.5 (should be at cap-height 700?)

	* three (U+0033): X=132.5,Y=-1.0 (should be at baseline 0?)

	* three (U+0033): X=133.5,Y=701.0 (should be at cap-height 700?)

	* five (U+0035): X=150.5,Y=-1.5 (should be at baseline 0?)

	* six (U+0036): X=403.0,Y=701.5 (should be at cap-height 700?)

	* at (U+0040): X=446.0,Y=-1.0 (should be at baseline 0?)

	* at (U+0040): X=446.0,Y=-1.0 (should be at baseline 0?)

	* G (U+0047): X=444.5,Y=701.0 (should be at cap-height 700?)

	* a (U+0061): X=383.0,Y=1.0 (should be at baseline 0?)

	* a (U+0061): X=261.0,Y=1.0 (should be at baseline 0?)

	* b (U+0062): X=257.5,Y=514.5 (should be at x-height 515?)

	* d (U+0064): X=346.0,Y=516.0 (should be at x-height 515?)

	* d (U+0064): X=286.5,Y=2.0 (should be at baseline 0?)

	* e (U+0065): X=377.0,Y=-2.0 (should be at baseline 0?)

	* f (U+0066): X=127.0,Y=701.0 (should be at cap-height 700?)

	* g (U+0067): X=478.0,Y=514.0 (should be at x-height 515?)

	* l (U+006C): X=284.0,Y=1.0 (should be at baseline 0?)

	* p (U+0070): X=198.0,Y=1.0 (should be at baseline 0?)

	* q (U+0071): X=478.0,Y=514.0 (should be at x-height 515?)

	* s (U+0073): X=130.5,Y=-2.0 (should be at baseline 0?)

	* degree (U+00B0): X=264.0,Y=698.0 (should be at cap-height 700?)

	* threequarters (U+00BE): X=83.5,Y=701.5 (should be at cap-height 700?)

	* agrave (U+00E0): X=383.0,Y=1.0 (should be at baseline 0?)

	* agrave (U+00E0): X=261.0,Y=1.0 (should be at baseline 0?)

	* aacute (U+00E1): X=383.0,Y=1.0 (should be at baseline 0?)

	* aacute (U+00E1): X=261.0,Y=1.0 (should be at baseline 0?)

	* acircumflex (U+00E2): X=383.0,Y=1.0 (should be at baseline 0?)

	* acircumflex (U+00E2): X=261.0,Y=1.0 (should be at baseline 0?)

	* atilde (U+00E3): X=383.0,Y=1.0 (should be at baseline 0?)

	* atilde (U+00E3): X=261.0,Y=1.0 (should be at baseline 0?)

	* atilde (U+00E3): X=392.0,Y=699.0 (should be at cap-height 700?)

	* adieresis (U+00E4): X=383.0,Y=1.0 (should be at baseline 0?)

	* adieresis (U+00E4): X=261.0,Y=1.0 (should be at baseline 0?)

	* aring (U+00E5): X=383.0,Y=1.0 (should be at baseline 0?)

	* aring (U+00E5): X=261.0,Y=1.0 (should be at baseline 0?)

	* ae (U+00E6): X=640.0,Y=-2.0 (should be at baseline 0?)

	* egrave (U+00E8): X=377.0,Y=-2.0 (should be at baseline 0?)

	* eacute (U+00E9): X=377.0,Y=-2.0 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=377.0,Y=-2.0 (should be at baseline 0?)

	* edieresis (U+00EB): X=377.0,Y=-2.0 (should be at baseline 0?)

	* ntilde (U+00F1): X=265.0,Y=701.0 (should be at cap-height 700?)

	* otilde (U+00F5): X=408.0,Y=699.0 (should be at cap-height 700?)

	* oslash (U+00F8): X=199.0,Y=-2.0 (should be at baseline 0?)

	* thorn (U+00FE): X=198.0,Y=-1.0 (should be at baseline 0?)

	* amacron (U+0101): X=383.0,Y=1.0 (should be at baseline 0?)

	* amacron (U+0101): X=261.0,Y=1.0 (should be at baseline 0?)

	* abreve (U+0103): X=383.0,Y=1.0 (should be at baseline 0?)

	* abreve (U+0103): X=261.0,Y=1.0 (should be at baseline 0?)

	* aogonek (U+0105): X=383.0,Y=1.0 (should be at baseline 0?)

	* aogonek (U+0105): X=261.0,Y=1.0 (should be at baseline 0?)

	* dcaron (U+010F): X=286.5,Y=2.0 (should be at baseline 0?)

	* dcroat (U+0111): X=286.5,Y=2.0 (should be at baseline 0?)

	* emacron (U+0113): X=377.0,Y=-2.0 (should be at baseline 0?)

	* ebreve (U+0115): X=377.0,Y=-2.0 (should be at baseline 0?)

	* edotaccent (U+0117): X=377.0,Y=-2.0 (should be at baseline 0?)

	* eogonek (U+0119): X=377.0,Y=-2.0 (should be at baseline 0?)

	* eogonek (U+0119): X=318.5,Y=0.5 (should be at baseline 0?)

	* ecaron (U+011B): X=377.0,Y=-2.0 (should be at baseline 0?)

	* Gcircumflex (U+011C): X=444.5,Y=701.0 (should be at cap-height 700?)

	* Gbreve (U+011E): X=444.5,Y=701.0 (should be at cap-height 700?)

	* Gdotaccent (U+0120): X=444.5,Y=701.0 (should be at cap-height 700?)

	* Gcommabelow (U+0122): X=444.5,Y=701.0 (should be at cap-height 700?)

	* itilde (U+0129): X=95.0,Y=701.0 (should be at cap-height 700?)

	* lacute (U+013A): X=284.0,Y=1.0 (should be at baseline 0?)

	* lcommabelow (U+013C): X=284.0,Y=1.0 (should be at baseline 0?)

	* lcaron (U+013E): X=284.0,Y=1.0 (should be at baseline 0?)

	* lslash (U+0142): X=321.0,Y=1.0 (should be at baseline 0?)

	* oe (U+0153): X=697.0,Y=-2.0 (should be at baseline 0?)

	* sacute (U+015B): X=130.5,Y=-2.0 (should be at baseline 0?)

	* scircumflex (U+015D): X=130.5,Y=-2.0 (should be at baseline 0?)

	* scedilla (U+015F): X=130.5,Y=-2.0 (should be at baseline 0?)

	* scaron (U+0161): X=130.5,Y=-2.0 (should be at baseline 0?)

	* utilde (U+0169): X=258.0,Y=701.0 (should be at cap-height 700?)

	* aringacute (U+01FB): X=383.0,Y=1.0 (should be at baseline 0?)

	* aringacute (U+01FB): X=261.0,Y=1.0 (should be at baseline 0?)

	* aringacute (U+01FB): X=287.0,Y=948.0 (should be at ascender 950?)

	* aringacute (U+01FB): X=426.0,Y=948.0 (should be at ascender 950?)

	* aeacute (U+01FD): X=640.0,Y=-2.0 (should be at baseline 0?)

	* oslashacute (U+01FF): X=199.0,Y=-2.0 (should be at baseline 0?)

	* scommabelow (U+0219): X=130.5,Y=-2.0 (should be at baseline 0?)

	* tilde (U+02DC): X=76.0,Y=701.5 (should be at cap-height 700?)

	* tildecomb (U+0303): X=76.0,Y=701.5 (should be at cap-height 700?)

	* pi (U+03C0): X=501.0,Y=-2.0 (should be at baseline 0?)

	* uni1E37 (U+1E37): X=284.0,Y=1.0 (should be at baseline 0?)

	* uni2070 (U+2070): X=181.5,Y=701.5 (should be at cap-height 700?)

	* uni2070 (U+2070): X=127.5,Y=701.5 (should be at cap-height 700?)

	* uni2088 (U+2088): X=23.0,Y=-1.0 (should be at baseline 0?)

	* uni2088 (U+2088): X=287.0,Y=-1.0 (should be at baseline 0?) 

	* integral (U+222B): X=173.5,Y=699.5 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* dollar (U+0024) contains a short segment L<<299.0,399.0>--<299.0,399.0>>

	* dollar (U+0024) contains a short segment B<<263.0,-11.0>-<260.0,-11.0>-<257.0,-11.0>>

	* seven (U+0037) contains a short segment L<<327.0,583.0>--<327.0,594.0>>

	* M (U+004D) contains a short segment L<<585.0,540.0>--<582.0,540.0>>

	* M (U+004D) contains a short segment L<<205.0,540.0>--<202.0,540.0>>

	* N (U+004E) contains a short segment L<<450.0,225.0>--<460.0,225.0>>

	* N (U+004E) contains a short segment L<<206.0,475.0>--<196.0,475.0>>

	* Q (U+0051) contains a short segment B<<339.0,-11.0>-<332.0,-11.0>-<325.0,-11.0>>

	* V (U+0056) contains a short segment L<<291.0,117.0>--<309.0,117.0>>

	* W (U+0057) contains a short segment L<<252.0,128.0>--<264.0,128.0>>

	* W (U+0057) contains a short segment L<<610.0,128.0>--<622.0,128.0>>

	* v (U+0076) contains a short segment L<<252.0,90.0>--<263.0,90.0>>

	* w (U+0077) contains a short segment L<<224.0,107.0>--<235.0,107.0>>

	* w (U+0077) contains a short segment L<<524.0,107.0>--<535.0,107.0>>

	* y (U+0079) contains a short segment L<<249.0,90.0>--<260.0,90.0>>

	* paragraph (U+00B6) contains a short segment L<<233.0,280.0>--<227.0,280.0>>

	* Ntilde (U+00D1) contains a short segment L<<450.0,225.0>--<460.0,225.0>>

	* Ntilde (U+00D1) contains a short segment L<<206.0,475.0>--<196.0,475.0>>

	* yacute (U+00FD) contains a short segment L<<249.0,90.0>--<260.0,90.0>>

	* ydieresis (U+00FF) contains a short segment L<<249.0,90.0>--<260.0,90.0>>

	* Nacute (U+0143) contains a short segment L<<450.0,225.0>--<460.0,225.0>>

	* Nacute (U+0143) contains a short segment L<<206.0,475.0>--<196.0,475.0>>

	* Ncommabelow (U+0145) contains a short segment L<<450.0,225.0>--<460.0,225.0>>

	* Ncommabelow (U+0145) contains a short segment L<<206.0,475.0>--<196.0,475.0>>

	* Ncaron (U+0147) contains a short segment L<<450.0,225.0>--<460.0,225.0>>

	* Ncaron (U+0147) contains a short segment L<<206.0,475.0>--<196.0,475.0>>

	* Eng (U+014A) contains a short segment L<<450.0,225.0>--<460.0,225.0>>

	* Eng (U+014A) contains a short segment L<<206.0,475.0>--<196.0,475.0>>

	* Wcircumflex (U+0174) contains a short segment L<<252.0,128.0>--<264.0,128.0>>

	* Wcircumflex (U+0174) contains a short segment L<<610.0,128.0>--<622.0,128.0>>

	* wcircumflex (U+0175) contains a short segment L<<224.0,107.0>--<235.0,107.0>>

	* wcircumflex (U+0175) contains a short segment L<<524.0,107.0>--<535.0,107.0>>

	* ycircumflex (U+0177) contains a short segment L<<249.0,90.0>--<260.0,90.0>>

	* Wgrave (U+1E80) contains a short segment L<<252.0,128.0>--<264.0,128.0>>

	* Wgrave (U+1E80) contains a short segment L<<610.0,128.0>--<622.0,128.0>>

	* wgrave (U+1E81) contains a short segment L<<224.0,107.0>--<235.0,107.0>>

	* wgrave (U+1E81) contains a short segment L<<524.0,107.0>--<535.0,107.0>>

	* Wacute (U+1E82) contains a short segment L<<252.0,128.0>--<264.0,128.0>>

	* Wacute (U+1E82) contains a short segment L<<610.0,128.0>--<622.0,128.0>>

	* wacute (U+1E83) contains a short segment L<<224.0,107.0>--<235.0,107.0>>

	* wacute (U+1E83) contains a short segment L<<524.0,107.0>--<535.0,107.0>>

	* Wdieresis (U+1E84) contains a short segment L<<252.0,128.0>--<264.0,128.0>>

	* Wdieresis (U+1E84) contains a short segment L<<610.0,128.0>--<622.0,128.0>>

	* wdieresis (U+1E85) contains a short segment L<<224.0,107.0>--<235.0,107.0>>

	* wdieresis (U+1E85) contains a short segment L<<524.0,107.0>--<535.0,107.0>>

	* ygrave (U+1EF3) contains a short segment L<<249.0,90.0>--<260.0,90.0>>

	* uni2077 (U+2077) contains a short segment L<<170.0,713.0>--<170.0,719.0>> 

	* uni2087 (U+2087) contains a short segment L<<170.0,170.0>--<170.0,176.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Eng (U+014A): L<<196.0,475.0>--<195.0,0.0>>

	* N (U+004E): L<<196.0,475.0>--<195.0,0.0>>

	* Nacute (U+0143): L<<196.0,475.0>--<195.0,0.0>>

	* Ncaron (U+0147): L<<196.0,475.0>--<195.0,0.0>>

	* Ncommabelow (U+0145): L<<196.0,475.0>--<195.0,0.0>>

	* Ntilde (U+00D1): L<<196.0,475.0>--<195.0,0.0>>

	* arrownw (U+8598): L<<315.0,482.0>--<318.0,137.0>>

	* dagger (U+2020): L<<167.0,-133.0>--<164.0,383.0>>

	* dagger (U+2020): L<<297.0,383.0>--<295.0,-133.0>>

	* numbersign (U+0023): L<<101.0,0.0>--<102.0,151.0>>

	* numbersign (U+0023): L<<105.0,256.0>--<106.0,405.0>>

	* numbersign (U+0023): L<<211.0,151.0>--<210.0,0.0>>

	* numbersign (U+0023): L<<214.0,405.0>--<213.0,256.0>>

	* numbersign (U+0023): L<<217.0,668.0>--<216.0,511.0>>

	* numbersign (U+0023): L<<315.0,0.0>--<316.0,151.0>>

	* numbersign (U+0023): L<<318.0,256.0>--<319.0,405.0>>

	* numbersign (U+0023): L<<425.0,151.0>--<424.0,0.0>> 

	* numbersign (U+0023): L<<428.0,405.0>--<427.0,256.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] Infovia-LightItalic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts CJK vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics">com.google.fonts/check/cjk_vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2 fsSelection bit 7 must be disabled [code: bad-fselection-bit7]
* 🔥 **FAIL** OS/2.sTypoAscender is "950" it should be 880 [code: bad-OS/2.sTypoAscender]
* 🔥 **FAIL** OS/2.sTypoDescender is "-350" it should be -120 [code: bad-OS/2.sTypoDescender]
* 🔥 **FAIL** hhea.ascent must match OS/2.usWinAscent [code: ascent-mismatch]
* 🔥 **FAIL** hhea.descent must match absolute value of OS/2.usWinDescent [code: descent-mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=14] [code: http-in-license-info]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain less than 40 CJK characters? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_not_enough_glyphs">com.google.fonts/check/cjk_not_enough_glyphs</a>)</summary><div>


* ⚠ **WARN** There are only 4 CJK glyphs when there needs to be at least 40 in order to support the smallest CJK writing system, Hangul.
The following CJK glyphs were found:
['arrownw', 'arrowne', 'arrowse', 'arrowsw']
Please check that these glyphs have the correct unicodes. [code: cjk-not-enough-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotbelowcomb.cap

	- uni1E37.ss03 

	- zero.slash
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni03BC	Contours detected: 2	Expected: 1

	- Glyph name: thorn	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: thorn	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni03BC	Contours detected: 2	Expected: 1 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain chws and vchw features? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/cjk_chws_feature">com.google.fonts/check/cjk_chws_feature</a>)</summary><div>


* ⚠ **WARN** chws feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-chws-feature]
* ⚠ **WARN** vchw feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-vchw-feature]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 494 among a set of 4 math glyphs.
The following math glyphs have a different width, though:

Width = 481:
less

Width = 501:
notequal, equal

Width = 482:
greater

Width = 532:
multiply, logicalnot

Width = 541:
approxequal

Width = 510:
lessequal

Width = 504:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 commabelowcomb (U+0326) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* asterisk (U+002A): X=303.0,Y=699.0 (should be at cap-height 700?)

	* three (U+0033): X=221.5,Y=699.5 (should be at cap-height 700?)

	* six (U+0036): X=453.0,Y=701.0 (should be at cap-height 700?)

	* question (U+003F): X=176.0,Y=699.0 (should be at cap-height 700?)

	* question (U+003F): X=75.0,Y=1.0 (should be at baseline 0?)

	* question (U+003F): X=142.0,Y=1.0 (should be at baseline 0?)

	* at (U+0040): X=325.5,Y=0.5 (should be at baseline 0?)

	* C (U+0043): X=472.5,Y=699.5 (should be at cap-height 700?)

	* C (U+0043): X=346.5,Y=-0.5 (should be at baseline 0?)

	* G (U+0047): X=493.5,Y=699.0 (should be at cap-height 700?)

	* G (U+0047): X=380.0,Y=-1.0 (should be at baseline 0?)

	* S (U+0053): X=439.0,Y=699.5 (should be at cap-height 700?)

	* Z (U+005A): X=-10.0,Y=-1.0 (should be at baseline 0?)

	* Z (U+005A): X=394.0,Y=-1.0 (should be at baseline 0?)

	* a (U+0061): X=187.5,Y=505.5 (should be at x-height 507?)

	* d (U+0064): X=111.0,Y=1.5 (should be at baseline 0?)

	* f (U+0066): X=199.0,Y=698.5 (should be at cap-height 700?)

	* h (U+0068): X=277.0,Y=509.0 (should be at x-height 507?)

	* l (U+006C): X=171.0,Y=-1.0 (should be at baseline 0?)

	* r (U+0072): X=279.0,Y=509.0 (should be at x-height 507?)

	* s (U+0073): X=82.5,Y=-2.0 (should be at baseline 0?)

	* s (U+0073): X=341.5,Y=507.5 (should be at x-height 507?)

	* braceleft (U+007B): X=385.0,Y=702.0 (should be at cap-height 700?)

	* braceright (U+007D): X=112.0,Y=701.0 (should be at cap-height 700?)

	* paragraph (U+00B6): X=287.0,Y=699.0 (should be at cap-height 700?)

	* paragraph (U+00B6): X=587.0,Y=699.0 (should be at cap-height 700?)

	* cedilla (U+00B8): X=65.0,Y=2.0 (should be at baseline 0?)

	* cedilla (U+00B8): X=100.0,Y=2.0 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=472.5,Y=699.5 (should be at cap-height 700?)

	* Ccedilla (U+00C7): X=346.5,Y=-0.5 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=225.0,Y=2.0 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=260.0,Y=2.0 (should be at baseline 0?)

	* Thorn (U+00DE): X=168.0,Y=701.0 (should be at cap-height 700?)

	* Thorn (U+00DE): X=232.0,Y=701.0 (should be at cap-height 700?)

	* ccedilla (U+00E7): X=174.0,Y=2.0 (should be at baseline 0?)

	* ccedilla (U+00E7): X=209.0,Y=2.0 (should be at baseline 0?)

	* Cacute (U+0106): X=472.5,Y=699.5 (should be at cap-height 700?)

	* Cacute (U+0106): X=346.5,Y=-0.5 (should be at baseline 0?)

	* Ccircumflex (U+0108): X=472.5,Y=699.5 (should be at cap-height 700?)

	* Ccircumflex (U+0108): X=346.5,Y=-0.5 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=472.5,Y=699.5 (should be at cap-height 700?)

	* Cdotaccent (U+010A): X=346.5,Y=-0.5 (should be at baseline 0?)

	* Ccaron (U+010C): X=472.5,Y=699.5 (should be at cap-height 700?)

	* Ccaron (U+010C): X=346.5,Y=-0.5 (should be at baseline 0?)

	* dcaron (U+010F): X=111.0,Y=1.5 (should be at baseline 0?)

	* dcroat (U+0111): X=111.0,Y=1.5 (should be at baseline 0?)

	* Gcircumflex (U+011C): X=493.5,Y=699.0 (should be at cap-height 700?)

	* Gcircumflex (U+011C): X=380.0,Y=-1.0 (should be at baseline 0?)

	* Gbreve (U+011E): X=493.5,Y=699.0 (should be at cap-height 700?)

	* Gbreve (U+011E): X=380.0,Y=-1.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=493.5,Y=699.0 (should be at cap-height 700?)

	* Gdotaccent (U+0120): X=380.0,Y=-1.0 (should be at baseline 0?)

	* Gcommabelow (U+0122): X=493.5,Y=699.0 (should be at cap-height 700?)

	* Gcommabelow (U+0122): X=380.0,Y=-1.0 (should be at baseline 0?)

	* lacute (U+013A): X=171.0,Y=-1.0 (should be at baseline 0?)

	* lcommabelow (U+013C): X=171.0,Y=-1.0 (should be at baseline 0?)

	* lcaron (U+013E): X=171.0,Y=-1.0 (should be at baseline 0?)

	* lslash (U+0142): X=205.0,Y=-1.0 (should be at baseline 0?)

	* OE (U+0152): X=527.0,Y=699.0 (should be at cap-height 700?)

	* uni0156 (U+0156): X=230.0,Y=2.0 (should be at baseline 0?)

	* uni0156 (U+0156): X=265.0,Y=2.0 (should be at baseline 0?)

	* uni0157 (U+0157): X=38.0,Y=2.0 (should be at baseline 0?)

	* uni0157 (U+0157): X=73.0,Y=2.0 (should be at baseline 0?)

	* Sacute (U+015A): X=439.0,Y=699.5 (should be at cap-height 700?)

	* sacute (U+015B): X=82.5,Y=-2.0 (should be at baseline 0?)

	* Scircumflex (U+015C): X=439.0,Y=699.5 (should be at cap-height 700?)

	* scircumflex (U+015D): X=82.5,Y=-2.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=439.0,Y=699.5 (should be at cap-height 700?)

	* Scedilla (U+015E): X=174.0,Y=2.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=209.0,Y=2.0 (should be at baseline 0?)

	* scedilla (U+015F): X=82.5,Y=-2.0 (should be at baseline 0?)

	* scedilla (U+015F): X=148.0,Y=2.0 (should be at baseline 0?)

	* scedilla (U+015F): X=183.0,Y=2.0 (should be at baseline 0?)

	* Scaron (U+0160): X=439.0,Y=699.5 (should be at cap-height 700?)

	* scaron (U+0161): X=82.5,Y=-2.0 (should be at baseline 0?)

	* uni0162 (U+0162): X=176.0,Y=2.0 (should be at baseline 0?)

	* uni0162 (U+0162): X=211.0,Y=2.0 (should be at baseline 0?)

	* uni0163 (U+0163): X=125.0,Y=2.0 (should be at baseline 0?)

	* uni0163 (U+0163): X=160.0,Y=2.0 (should be at baseline 0?)

	* Zacute (U+0179): X=-10.0,Y=-1.0 (should be at baseline 0?)

	* Zacute (U+0179): X=394.0,Y=-1.0 (should be at baseline 0?)

	* Zdotaccent (U+017B): X=-10.0,Y=-1.0 (should be at baseline 0?)

	* Zdotaccent (U+017B): X=394.0,Y=-1.0 (should be at baseline 0?)

	* Zcaron (U+017D): X=-10.0,Y=-1.0 (should be at baseline 0?)

	* Zcaron (U+017D): X=394.0,Y=-1.0 (should be at baseline 0?)

	* Scommabelow (U+0218): X=439.0,Y=699.5 (should be at cap-height 700?)

	* scommabelow (U+0219): X=82.5,Y=-2.0 (should be at baseline 0?)

	* uni0327 (U+0327): X=65.0,Y=2.0 (should be at baseline 0?)

	* uni0327 (U+0327): X=100.0,Y=2.0 (should be at baseline 0?)

	* uni1E37 (U+1E37): X=171.0,Y=-1.0 (should be at baseline 0?)

	* uni2079 (U+2079): X=117.0,Y=701.0 (should be at cap-height 700?)

	* uni2079 (U+2079): X=165.0,Y=701.0 (should be at cap-height 700?)

	* uni2079 (U+2079): X=165.0,Y=701.0 (should be at cap-height 700?)

	* uni2083 (U+2083): X=139.0,Y=-1.0 (should be at baseline 0?)

	* uni2084 (U+2084): X=-20.0,Y=2.0 (should be at baseline 0?) 

	* Euro (U+20AC): X=425.0,Y=-0.5 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* M (U+004D) contains a short segment L<<683.0,632.0>--<679.0,632.0>>

	* M (U+004D) contains a short segment L<<221.0,632.0>--<216.0,632.0>>

	* N (U+004E) contains a short segment L<<437.0,82.0>--<447.0,82.0>>

	* N (U+004E) contains a short segment L<<222.0,621.0>--<212.0,621.0>>

	* W (U+0057) contains a short segment L<<175.0,58.0>--<186.0,58.0>>

	* W (U+0057) contains a short segment L<<524.0,58.0>--<536.0,58.0>>

	* v (U+0076) contains a short segment L<<174.0,47.0>--<184.0,47.0>>

	* w (U+0077) contains a short segment L<<146.0,49.0>--<153.0,49.0>>

	* w (U+0077) contains a short segment L<<452.0,49.0>--<459.0,49.0>>

	* y (U+0079) contains a short segment L<<169.0,53.0>--<176.0,53.0>>

	* braceleft (U+007B) contains a short segment B<<96.0,131.0>-<96.0,132.0>-<98.5,141.5>>

	* braceleft (U+007B) contains a short segment B<<161.0,450.0>-<162.0,452.0>-<163.5,463.0>>

	* braceleft (U+007B) contains a short segment B<<229.0,502.0>-<229.0,501.0>-<228.0,490.0>>

	* braceleft (U+007B) contains a short segment B<<162.5,146.5>-<161.0,141.0>-<160.0,137.5>>

	* braceleft (U+007B) contains a short segment B<<160.0,137.5>-<159.0,134.0>-<157.0,125.0>>

	* paragraph (U+00B6) contains a short segment L<<223.0,330.0>--<219.0,330.0>>

	* Ntilde (U+00D1) contains a short segment L<<437.0,82.0>--<447.0,82.0>>

	* Ntilde (U+00D1) contains a short segment L<<222.0,621.0>--<212.0,621.0>>

	* ae (U+00E6) contains a short segment B<<704.0,268.0>-<702.0,260.0>-<700.0,251.0>>

	* ae (U+00E6) contains a short segment B<<700.0,251.0>-<698.0,242.0>-<696.0,234.0>>

	* yacute (U+00FD) contains a short segment L<<169.0,53.0>--<176.0,53.0>>

	* ydieresis (U+00FF) contains a short segment L<<169.0,53.0>--<176.0,53.0>>

	* Nacute (U+0143) contains a short segment L<<437.0,82.0>--<447.0,82.0>>

	* Nacute (U+0143) contains a short segment L<<222.0,621.0>--<212.0,621.0>>

	* Ncommabelow (U+0145) contains a short segment L<<437.0,82.0>--<447.0,82.0>>

	* Ncommabelow (U+0145) contains a short segment L<<222.0,621.0>--<212.0,621.0>>

	* Ncaron (U+0147) contains a short segment L<<437.0,82.0>--<447.0,82.0>>

	* Ncaron (U+0147) contains a short segment L<<222.0,621.0>--<212.0,621.0>>

	* Eng (U+014A) contains a short segment L<<437.0,82.0>--<447.0,82.0>>

	* Eng (U+014A) contains a short segment L<<492.0,0.0>--<488.0,-17.0>>

	* Eng (U+014A) contains a short segment L<<222.0,621.0>--<212.0,621.0>>

	* Wcircumflex (U+0174) contains a short segment L<<175.0,58.0>--<186.0,58.0>>

	* Wcircumflex (U+0174) contains a short segment L<<524.0,58.0>--<536.0,58.0>>

	* wcircumflex (U+0175) contains a short segment L<<146.0,49.0>--<153.0,49.0>>

	* wcircumflex (U+0175) contains a short segment L<<452.0,49.0>--<459.0,49.0>>

	* ycircumflex (U+0177) contains a short segment L<<169.0,53.0>--<176.0,53.0>>

	* aeacute (U+01FD) contains a short segment B<<704.0,268.0>-<702.0,260.0>-<700.0,251.0>>

	* aeacute (U+01FD) contains a short segment B<<700.0,251.0>-<698.0,242.0>-<696.0,234.0>>

	* Wgrave (U+1E80) contains a short segment L<<175.0,58.0>--<186.0,58.0>>

	* Wgrave (U+1E80) contains a short segment L<<524.0,58.0>--<536.0,58.0>>

	* wgrave (U+1E81) contains a short segment L<<146.0,49.0>--<153.0,49.0>>

	* wgrave (U+1E81) contains a short segment L<<452.0,49.0>--<459.0,49.0>>

	* Wacute (U+1E82) contains a short segment L<<175.0,58.0>--<186.0,58.0>>

	* Wacute (U+1E82) contains a short segment L<<524.0,58.0>--<536.0,58.0>>

	* wacute (U+1E83) contains a short segment L<<146.0,49.0>--<153.0,49.0>>

	* wacute (U+1E83) contains a short segment L<<452.0,49.0>--<459.0,49.0>>

	* Wdieresis (U+1E84) contains a short segment L<<175.0,58.0>--<186.0,58.0>>

	* Wdieresis (U+1E84) contains a short segment L<<524.0,58.0>--<536.0,58.0>>

	* wdieresis (U+1E85) contains a short segment L<<146.0,49.0>--<153.0,49.0>>

	* wdieresis (U+1E85) contains a short segment L<<452.0,49.0>--<459.0,49.0>>

	* ygrave (U+1EF3) contains a short segment L<<169.0,53.0>--<176.0,53.0>>

	* summation (U+2211) contains a short segment L<<177.0,693.0>--<177.0,679.0>>

	* summation (U+2211) contains a short segment L<<32.0,-80.0>--<23.0,-98.0>> 

	* radical (U+221A) contains a short segment L<<208.0,-87.0>--<209.0,-87.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Eng (U+014A): L<<628.0,700.0>--<492.0,0.0>> -> L<<492.0,0.0>--<488.0,-17.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[15] Infovia-Italic.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts CJK vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_vertical_metrics">com.google.fonts/check/cjk_vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2 fsSelection bit 7 must be disabled [code: bad-fselection-bit7]
* 🔥 **FAIL** OS/2.sTypoAscender is "950" it should be 880 [code: bad-OS/2.sTypoAscender]
* 🔥 **FAIL** OS/2.sTypoDescender is "-350" it should be -120 [code: bad-OS/2.sTypoDescender]
* 🔥 **FAIL** hhea.ascent must match OS/2.usWinAscent [code: ascent-mismatch]
* 🔥 **FAIL** hhea.descent must match absolute value of OS/2.usWinDescent [code: descent-mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=1, enc=0, name=14] [code: http-in-license-info]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain less than 40 CJK characters? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/cjk_not_enough_glyphs">com.google.fonts/check/cjk_not_enough_glyphs</a>)</summary><div>


* ⚠ **WARN** There are only 4 CJK glyphs when there needs to be at least 40 in order to support the smallest CJK writing system, Hangul.
The following CJK glyphs were found:
['arrownw', 'arrowne', 'arrowse', 'arrowsw']
Please check that these glyphs have the correct unicodes. [code: cjk-not-enough-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotbelowcomb.cap

	- uni1E37.ss03 

	- zero.slash
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni03BC	Contours detected: 2	Expected: 1

	- Glyph name: thorn	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: thorn	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni03BC	Contours detected: 2	Expected: 1 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain chws and vchw features? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/cjk_chws_feature">com.google.fonts/check/cjk_chws_feature</a>)</summary><div>


* ⚠ **WARN** chws feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-chws-feature]
* ⚠ **WARN** vchw feature not found in font. Use chws_tool (https://github.com/googlefonts/chws_tool) to add it. [code: missing-vchw-feature]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 495 among a set of 4 math glyphs.
The following math glyphs have a different width, though:

Width = 479:
less

Width = 505:
notequal, equal

Width = 480:
greater

Width = 532:
multiply, logicalnot

Width = 539:
approxequal

Width = 508:
lessequal

Width = 503:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 commabelowcomb (U+0326) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* dollar (U+0024) contains a short segment L<<348.0,610.0>--<348.0,610.0>>

	* M (U+004D) contains a short segment L<<669.0,602.0>--<665.0,602.0>>

	* M (U+004D) contains a short segment L<<233.0,602.0>--<229.0,602.0>>

	* N (U+004E) contains a short segment L<<439.0,124.0>--<449.0,124.0>>

	* N (U+004E) contains a short segment L<<232.0,581.0>--<222.0,581.0>>

	* W (U+0057) contains a short segment L<<190.0,80.0>--<202.0,80.0>>

	* W (U+0057) contains a short segment L<<543.0,80.0>--<554.0,80.0>>

	* b (U+0062) contains a short segment L<<195.0,477.0>--<195.0,473.0>>

	* g (U+0067) contains a short segment L<<310.0,33.0>--<310.0,34.0>>

	* q (U+0071) contains a short segment L<<310.0,33.0>--<310.0,34.0>>

	* v (U+0076) contains a short segment L<<186.0,61.0>--<197.0,61.0>>

	* w (U+0077) contains a short segment L<<159.0,67.0>--<168.0,67.0>>

	* w (U+0077) contains a short segment L<<464.0,67.0>--<473.0,67.0>>

	* y (U+0079) contains a short segment L<<184.0,72.0>--<192.0,72.0>>

	* braceleft (U+007B) contains a short segment B<<246.0,496.0>-<246.0,495.0>-<244.5,484.5>>

	* paragraph (U+00B6) contains a short segment L<<226.0,314.0>--<222.0,314.0>>

	* Ntilde (U+00D1) contains a short segment L<<439.0,124.0>--<449.0,124.0>>

	* Ntilde (U+00D1) contains a short segment L<<232.0,581.0>--<222.0,581.0>>

	* yacute (U+00FD) contains a short segment L<<184.0,72.0>--<192.0,72.0>>

	* ydieresis (U+00FF) contains a short segment L<<184.0,72.0>--<192.0,72.0>>

	* gcircumflex (U+011D) contains a short segment L<<310.0,33.0>--<310.0,34.0>>

	* gbreve (U+011F) contains a short segment L<<310.0,33.0>--<310.0,34.0>>

	* gdotaccent (U+0121) contains a short segment L<<310.0,33.0>--<310.0,34.0>>

	* gcommaabove (U+0123) contains a short segment L<<310.0,33.0>--<310.0,34.0>>

	* Nacute (U+0143) contains a short segment L<<439.0,124.0>--<449.0,124.0>>

	* Nacute (U+0143) contains a short segment L<<232.0,581.0>--<222.0,581.0>>

	* Ncommabelow (U+0145) contains a short segment L<<439.0,124.0>--<449.0,124.0>>

	* Ncommabelow (U+0145) contains a short segment L<<232.0,581.0>--<222.0,581.0>>

	* Ncaron (U+0147) contains a short segment L<<439.0,124.0>--<449.0,124.0>>

	* Ncaron (U+0147) contains a short segment L<<232.0,581.0>--<222.0,581.0>>

	* Eng (U+014A) contains a short segment L<<439.0,124.0>--<449.0,124.0>>

	* Eng (U+014A) contains a short segment L<<505.0,0.0>--<502.0,-15.0>>

	* Eng (U+014A) contains a short segment L<<418.0,0.0>--<390.0,0.0>>

	* Eng (U+014A) contains a short segment L<<232.0,581.0>--<222.0,581.0>>

	* Wcircumflex (U+0174) contains a short segment L<<190.0,80.0>--<202.0,80.0>>

	* Wcircumflex (U+0174) contains a short segment L<<543.0,80.0>--<554.0,80.0>>

	* wcircumflex (U+0175) contains a short segment L<<159.0,67.0>--<168.0,67.0>>

	* wcircumflex (U+0175) contains a short segment L<<464.0,67.0>--<473.0,67.0>>

	* ycircumflex (U+0177) contains a short segment L<<184.0,72.0>--<192.0,72.0>>

	* Wgrave (U+1E80) contains a short segment L<<190.0,80.0>--<202.0,80.0>>

	* Wgrave (U+1E80) contains a short segment L<<543.0,80.0>--<554.0,80.0>>

	* wgrave (U+1E81) contains a short segment L<<159.0,67.0>--<168.0,67.0>>

	* wgrave (U+1E81) contains a short segment L<<464.0,67.0>--<473.0,67.0>>

	* Wacute (U+1E82) contains a short segment L<<190.0,80.0>--<202.0,80.0>>

	* Wacute (U+1E82) contains a short segment L<<543.0,80.0>--<554.0,80.0>>

	* wacute (U+1E83) contains a short segment L<<159.0,67.0>--<168.0,67.0>>

	* wacute (U+1E83) contains a short segment L<<464.0,67.0>--<473.0,67.0>>

	* Wdieresis (U+1E84) contains a short segment L<<190.0,80.0>--<202.0,80.0>>

	* Wdieresis (U+1E84) contains a short segment L<<543.0,80.0>--<554.0,80.0>>

	* wdieresis (U+1E85) contains a short segment L<<159.0,67.0>--<168.0,67.0>>

	* wdieresis (U+1E85) contains a short segment L<<464.0,67.0>--<473.0,67.0>>

	* ygrave (U+1EF3) contains a short segment L<<184.0,72.0>--<192.0,72.0>>

	* summation (U+2211) contains a short segment L<<190.0,675.0>--<197.0,671.0>> 

	* summation (U+2211) contains a short segment L<<55.0,-75.0>--<44.0,-82.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Eng (U+014A): L<<641.0,700.0>--<505.0,0.0>> -> L<<505.0,0.0>--<502.0,-15.0>> [code: found-colinear-vectors]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 6 | 87 | 722 | 37 | 539 | 0 |
| 0% | 0% | 6% | 52% | 3% | 39% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
