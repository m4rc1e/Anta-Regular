## FontBakery report

fontbakery version: 0.10.9

<details><summary><b>[16] Anta-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://openfontlicense.org" Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, math, old-permic, coptic, tifinagh, tai-le, canadian-aboriginal, malayalam
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0315 COMBINING COMMA ABOVE RIGHT: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: at	Contours detected: 1	Expected: 2

	- Glyph name: A	Contours detected: 1	Expected: 2

	- Glyph name: E	Contours detected: 2	Expected: 1

	- Glyph name: F	Contours detected: 2	Expected: 1

	- Glyph name: a	Contours detected: 1	Expected: 2

	- Glyph name: b	Contours detected: 1	Expected: 2

	- Glyph name: d	Contours detected: 1	Expected: 2

	- Glyph name: e	Contours detected: 1	Expected: 2

	- Glyph name: g	Contours detected: 1	Expected: 2 or 3

	- Glyph name: p	Contours detected: 1	Expected: 2

	- Glyph name: q	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: Agrave	Contours detected: 2	Expected: 3

	- Glyph name: Aacute	Contours detected: 2	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 2	Expected: 3

	- Glyph name: Atilde	Contours detected: 2	Expected: 3

	- Glyph name: Adieresis	Contours detected: 3	Expected: 4

	- Glyph name: Egrave	Contours detected: 3	Expected: 2

	- Glyph name: Eacute	Contours detected: 3	Expected: 2

	- Glyph name: Ecircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Edieresis	Contours detected: 4	Expected: 3

	- Glyph name: agrave	Contours detected: 2	Expected: 3

	- Glyph name: aacute	Contours detected: 2	Expected: 3

	- Glyph name: acircumflex	Contours detected: 2	Expected: 3

	- Glyph name: atilde	Contours detected: 2	Expected: 3

	- Glyph name: adieresis	Contours detected: 3	Expected: 4

	- Glyph name: aring	Contours detected: 3	Expected: 4

	- Glyph name: ae	Contours detected: 1	Expected: 3

	- Glyph name: egrave	Contours detected: 2	Expected: 3

	- Glyph name: eacute	Contours detected: 2	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 2	Expected: 3

	- Glyph name: edieresis	Contours detected: 3	Expected: 4

	- Glyph name: eth	Contours detected: 1	Expected: 2

	- Glyph name: Amacron	Contours detected: 2	Expected: 3

	- Glyph name: amacron	Contours detected: 2	Expected: 3

	- Glyph name: Abreve	Contours detected: 2	Expected: 3

	- Glyph name: abreve	Contours detected: 2	Expected: 3

	- Glyph name: Aogonek	Contours detected: 1	Expected: 2 or 3

	- Glyph name: aogonek	Contours detected: 1	Expected: 2

	- Glyph name: dcaron	Contours detected: 2	Expected: 3

	- Glyph name: dcroat	Contours detected: 1	Expected: 2

	- Glyph name: Emacron	Contours detected: 3	Expected: 2

	- Glyph name: emacron	Contours detected: 2	Expected: 3

	- Glyph name: Ebreve	Contours detected: 3	Expected: 2

	- Glyph name: ebreve	Contours detected: 2	Expected: 3

	- Glyph name: Edotaccent	Contours detected: 3	Expected: 2

	- Glyph name: edotaccent	Contours detected: 2	Expected: 3

	- Glyph name: eogonek	Contours detected: 1	Expected: 2

	- Glyph name: Ecaron	Contours detected: 3	Expected: 2

	- Glyph name: ecaron	Contours detected: 2	Expected: 3

	- Glyph name: gcircumflex	Contours detected: 2	Expected: 3 or 4

	- Glyph name: gbreve	Contours detected: 2	Expected: 3 or 4

	- Glyph name: gdotaccent	Contours detected: 2	Expected: 3 or 4

	- Glyph name: uni0123	Contours detected: 2	Expected: 3 or 4

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 2	Expected: 3

	- Glyph name: Racute	Contours detected: 2	Expected: 3

	- Glyph name: uni0156	Contours detected: 2	Expected: 3

	- Glyph name: Rcaron	Contours detected: 2	Expected: 3

	- Glyph name: aeacute	Contours detected: 2	Expected: 4

	- Glyph name: uni0218	Contours detected: 1	Expected: 2

	- Glyph name: uni0219	Contours detected: 1	Expected: 2

	- Glyph name: uni021A	Contours detected: 1	Expected: 2

	- Glyph name: uni021B	Contours detected: 1	Expected: 2

	- Glyph name: uni1E02	Contours detected: 3	Expected: 4

	- Glyph name: uni1E03	Contours detected: 2	Expected: 3

	- Glyph name: uni1E0B	Contours detected: 2	Expected: 3

	- Glyph name: uni1E1E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E56	Contours detected: 2	Expected: 3

	- Glyph name: uni1E57	Contours detected: 2	Expected: 3

	- Glyph name: partialdiff	Contours detected: 1	Expected: 2

	- Glyph name: A	Contours detected: 1	Expected: 2

	- Glyph name: Aacute	Contours detected: 2	Expected: 3

	- Glyph name: Abreve	Contours detected: 2	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 2	Expected: 3

	- Glyph name: Adieresis	Contours detected: 3	Expected: 4

	- Glyph name: Agrave	Contours detected: 2	Expected: 3

	- Glyph name: Amacron	Contours detected: 2	Expected: 3

	- Glyph name: Aogonek	Contours detected: 1	Expected: 2 or 3

	- Glyph name: Atilde	Contours detected: 2	Expected: 3

	- Glyph name: E	Contours detected: 2	Expected: 1

	- Glyph name: Eacute	Contours detected: 3	Expected: 2

	- Glyph name: Ebreve	Contours detected: 3	Expected: 2

	- Glyph name: Ecaron	Contours detected: 3	Expected: 2

	- Glyph name: Ecircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Edieresis	Contours detected: 4	Expected: 3

	- Glyph name: Edotaccent	Contours detected: 3	Expected: 2

	- Glyph name: Egrave	Contours detected: 3	Expected: 2

	- Glyph name: Emacron	Contours detected: 3	Expected: 2

	- Glyph name: F	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Racute	Contours detected: 2	Expected: 3

	- Glyph name: Rcaron	Contours detected: 2	Expected: 3

	- Glyph name: a	Contours detected: 1	Expected: 2

	- Glyph name: aacute	Contours detected: 2	Expected: 3

	- Glyph name: abreve	Contours detected: 2	Expected: 3

	- Glyph name: acircumflex	Contours detected: 2	Expected: 3

	- Glyph name: adieresis	Contours detected: 3	Expected: 4

	- Glyph name: ae	Contours detected: 1	Expected: 3

	- Glyph name: aeacute	Contours detected: 2	Expected: 4

	- Glyph name: agrave	Contours detected: 2	Expected: 3

	- Glyph name: amacron	Contours detected: 2	Expected: 3

	- Glyph name: aogonek	Contours detected: 1	Expected: 2

	- Glyph name: aring	Contours detected: 3	Expected: 4

	- Glyph name: at	Contours detected: 1	Expected: 2

	- Glyph name: atilde	Contours detected: 2	Expected: 3

	- Glyph name: b	Contours detected: 1	Expected: 2

	- Glyph name: d	Contours detected: 1	Expected: 2

	- Glyph name: dcaron	Contours detected: 2	Expected: 3

	- Glyph name: dcroat	Contours detected: 1	Expected: 2

	- Glyph name: e	Contours detected: 1	Expected: 2

	- Glyph name: eacute	Contours detected: 2	Expected: 3

	- Glyph name: ebreve	Contours detected: 2	Expected: 3

	- Glyph name: ecaron	Contours detected: 2	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 2	Expected: 3

	- Glyph name: edieresis	Contours detected: 3	Expected: 4

	- Glyph name: edotaccent	Contours detected: 2	Expected: 3

	- Glyph name: egrave	Contours detected: 2	Expected: 3

	- Glyph name: emacron	Contours detected: 2	Expected: 3

	- Glyph name: eogonek	Contours detected: 1	Expected: 2

	- Glyph name: eth	Contours detected: 1	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: g	Contours detected: 1	Expected: 2 or 3

	- Glyph name: gbreve	Contours detected: 2	Expected: 3 or 4

	- Glyph name: gcircumflex	Contours detected: 2	Expected: 3 or 4

	- Glyph name: gdotaccent	Contours detected: 2	Expected: 3 or 4

	- Glyph name: oe	Contours detected: 2	Expected: 3

	- Glyph name: p	Contours detected: 1	Expected: 2

	- Glyph name: partialdiff	Contours detected: 1	Expected: 2

	- Glyph name: q	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0123	Contours detected: 2	Expected: 3 or 4

	- Glyph name: uni0156	Contours detected: 2	Expected: 3

	- Glyph name: uni0218	Contours detected: 1	Expected: 2

	- Glyph name: uni0219	Contours detected: 1	Expected: 2

	- Glyph name: uni021A	Contours detected: 1	Expected: 2

	- Glyph name: uni021B	Contours detected: 1	Expected: 2

	- Glyph name: uni1E02	Contours detected: 3	Expected: 4

	- Glyph name: uni1E03	Contours detected: 2	Expected: 3

	- Glyph name: uni1E0B	Contours detected: 2	Expected: 3

	- Glyph name: uni1E1E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E56	Contours detected: 2	Expected: 3

	- Glyph name: uni1E57	Contours detected: 2	Expected: 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 1230 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 1274:
plus

Width = 1233:
equal, logicalnot

Width = 1213:
plusminus

Width = 1034:
multiply

Width = 1237:
divide

Width = 847:
minus

Width = 1275:
approxequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check accent of Lcaron, dcaron, lcaron, tcaron (derived from com.google.fonts/check/alt_caron) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/alt_caron">com.google.fonts/check/alt_caron</a>)</summary><div>


* ⚠ **WARN** Lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** lcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
* ⚠ **WARN** tcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* aring (U+00E5): X=611.0,Y=1421.0 (should be at cap-height 1422?)

	* aring (U+00E5): X=571.0,Y=1421.0 (should be at cap-height 1422?)

	* uni0163 (U+0163): X=481.0,Y=1.0 (should be at baseline 0?)

	* uring (U+016F): X=616.0,Y=1421.0 (should be at cap-height 1422?)

	* uring (U+016F): X=576.0,Y=1421.0 (should be at cap-height 1422?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment B<<380.0,524.0>-<351.0,518.0>-<340.5,509.5>>

	* two (U+0032) contains a short segment B<<340.5,509.5>-<330.0,501.0>-<330.0,481.0>>

	* Ccedilla (U+00C7) contains a short segment B<<582.5,-155.0>-<600.0,-157.0>-<613.0,-157.0>>

	* Ccedilla (U+00C7) contains a short segment B<<654.0,-126.0>-<654.0,-111.0>-<647.0,-86.5>>

	* ccedilla (U+00E7) contains a short segment B<<540.5,-156.0>-<558.0,-158.0>-<571.0,-158.0>>

	* Aogonek (U+0104) contains a short segment L<<1321.0,0.0>--<1278.0,0.0>>

	* Aogonek (U+0104) contains a short segment B<<1248.0,-87.0>-<1241.0,-111.0>-<1241.0,-126.0>>

	* Aogonek (U+0104) contains a short segment B<<1282.0,-157.0>-<1295.0,-157.0>-<1313.0,-155.0>>

	* aogonek (U+0105) contains a short segment L<<1062.0,0.0>--<1032.0,0.0>>

	* aogonek (U+0105) contains a short segment B<<1002.0,-87.0>-<995.0,-111.0>-<995.0,-126.0>>

	* aogonek (U+0105) contains a short segment B<<1036.0,-157.0>-<1049.0,-157.0>-<1067.0,-155.0>>

	* Eogonek (U+0118) contains a short segment B<<722.0,-87.0>-<715.0,-111.0>-<715.0,-126.0>>

	* Eogonek (U+0118) contains a short segment B<<756.0,-157.0>-<769.0,-157.0>-<787.0,-155.0>>

	* eogonek (U+0119) contains a short segment B<<635.0,-87.0>-<628.0,-111.0>-<628.0,-126.0>>

	* eogonek (U+0119) contains a short segment B<<669.0,-157.0>-<682.0,-157.0>-<700.0,-155.0>>

	* Eng (U+014A) contains a short segment B<<981.5,-173.0>-<1015.0,-166.0>-<1024.0,-140.5>>

	* Scedilla (U+015E) contains a short segment B<<592.5,-155.0>-<610.0,-157.0>-<623.0,-157.0>>

	* Scedilla (U+015E) contains a short segment B<<664.0,-126.0>-<664.0,-111.0>-<657.0,-86.5>>

	* scedilla (U+015F) contains a short segment B<<488.5,-155.0>-<506.0,-157.0>-<519.0,-157.0>>

	* scedilla (U+015F) contains a short segment B<<560.0,-126.0>-<560.0,-111.0>-<553.0,-86.5>>

	* uni0162 (U+0162) contains a short segment B<<511.5,-155.0>-<529.0,-157.0>-<542.0,-157.0>>

	* uni0162 (U+0162) contains a short segment L<<725.0,0.0>--<694.0,0.0>>

	* uni0163 (U+0163) contains a short segment B<<446.5,-155.0>-<464.0,-157.0>-<477.0,-157.0>>

	* Uogonek (U+0172) contains a short segment B<<762.0,-87.0>-<755.0,-111.0>-<755.0,-126.0>>

	* Uogonek (U+0172) contains a short segment B<<796.0,-157.0>-<809.0,-157.0>-<827.0,-155.0>>

	* uogonek (U+0173) contains a short segment B<<902.0,-157.0>-<915.0,-157.0>-<933.0,-155.0>>

	* uni021A (U+021A) contains a short segment L<<725.0,0.0>--<723.0,0.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: i̇ ǐ i̒ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ j̆ j̇ j̊ j̋ ǰ j̒ j̦̀

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Ma’di (Latn, 584,000 speakers), Nzakara (Latn, 50,000 speakers), Ejagham (Latn, 120,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Southern Kisi (Latn, 360,000 speakers), Avokaya (Latn, 100,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Yala (Latn, 200,000 speakers), Ekpeye (Latn, 226,000 speakers), Lugbara (Latn, 2,200,000 speakers), Nateni (Latn, 100,000 speakers), Mundani (Latn, 34,000 speakers), Koonzime (Latn, 40,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Aghem (Latn, 38,843 speakers), Dii (Latn, 71,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Cicipu (Latn, 44,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Makaa (Latn, 221,000 speakers), Mango (Latn, 77,000 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Zapotec (Latn, 490,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Gulay (Latn, 250,478 speakers), Sar (Latn, 500,000 speakers), South Central Banda (Latn, 244,000 speakers), Dan (Latn, 1,099,244 speakers), Kom (Latn, 360,685 speakers), Bafut (Latn, 158,146 speakers), Ebira (Latn, 2,200,000 speakers), Mfumte (Latn, 79,000 speakers), Fur (Latn, 1,230,163 speakers), Igbo (Latn, 27,823,640 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | ☠ FATAL | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| 0 | 0 | 2 | 14 | 124 | 7 | 109 | 0 |
| 0% | 0% | 1% | 5% | 48% | 3% | 43% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
