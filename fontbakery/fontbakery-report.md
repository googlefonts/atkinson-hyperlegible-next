## FontBakery report

fontbakery version: 0.12.10



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] AtkinsonHyperlegibleNext[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoAscender value should be greater than 863, but got 796 instead</p>
 [code: typoAscender]



</div>
</details>
</div>
</details>

<details><summary>[1] AtkinsonHyperlegibleNext-Italic[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoAscender value should be greater than 863, but got 796 instead</p>
 [code: typoAscender]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[19] AtkinsonHyperlegibleNext[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking Vertical Metric Linegaps. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>hhea lineGap is not equal to 0.</p>
<p><em>Overridden</em>: This check was originally a WARN but was
overridden by the universal profile:
For Google Fonts, all messages from this check are considered FAILs.</p>
 [code: hhea]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoDescender (-251) and hhea descent (-161) must be equal.</p>
 [code: descender]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Variable font instance name 'Atkinson Hyperlegible Next ExtraLight' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 257 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Atkinson Hyperlegible Next ExtraLight' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 257 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Atkinson Hyperlegible Next Regular' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 261 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Atkinson Hyperlegible Next Regular' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 261 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Atkinson Hyperlegible Next Medium' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 263 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Atkinson Hyperlegible Next Medium' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 263 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Atkinson Hyperlegible Next SemiBold' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 265 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Atkinson Hyperlegible Next SemiBold' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 265 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Atkinson Hyperlegible Next ExtraBold' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 269 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Atkinson Hyperlegible Next ExtraBold' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 269 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* ⚠️ **WARN** <p>Name ID 6 'AtkinsonHyperlegibleNext-Regular' exceeds 27 characters. This has been found to cause problems with PostScript printers, especially on Mac platforms.</p>
 [code: nameid6-too-long]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: &quot;Braille Institute of America, Inc. provides Atkinson Hyperlegible for use, without derivatives or alteration, to the public free of charge for all non-commercial and commercial work. No attribution required.&quot; Must be changed to &quot;This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: <a href="https://openfontlicense.org">https://openfontlicense.org</a>&quot;</p>
 [code: wrong]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Substitute copyright, registered and trademark symbols in name table entries. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>NAMEID #0 contains symbols that should be replaced by '(c)'.</p>
 [code: unwanted-chars]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check license file has good copyright string. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>First line in license file is:</p>
<p>&quot;copyright 20** the my font project authors (<a href="https://github.com/googlefonts/googlefonts-project-template">https://github.com/googlefonts/googlefonts-project-template</a>)&quot;</p>
<p>which does not match the expected format, similar to:</p>
<p>&quot;Copyright 2022 The Familyname Project Authors (git url)&quot;</p>
 [code: bad-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.copyright.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;© 2020, 2024 Braille Institute of America, Inc., a 501(c)(3) Charitable Organization.&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 fsType does not impose restrictions. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.</p>
<p>No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead.</p>
 [code: drm]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0060 (GRAVE ACCENT)


- 0x00A8 (DIAERESIS)


- 0x00AF (MACRON)


- 0x00B4 (ACUTE ACCENT)


- 0x00B8 (CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


- 0x02C7 (CARON)


- 0x02D8 (BREVE)


- 0x02D9 (DOT ABOVE)


- 0x02DA (RING ABOVE)


- 0x02DB (OGONEK)


- 0x02DC (SMALL TILDE)


- 0x02DD (DOUBLE ACUTE ACCENT)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Are there non-ASCII characters in ASCII-only NAME table entries? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Bad string at [nameID 0, 'utf_16_be']: 'b'© 2020, 2024 Braille Institute of America, Inc., a 501(c)(3) Charitable Organization.''</p>
 [code: bad-string]



* 🔥 **FAIL** <p>There are 1 strings containing non-ASCII characters in the ASCII-only NAME table entries.</p>
 [code: non-ascii-strings]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoLineGap is &quot;150&quot; it should be 0</p>
 [code: bad-OS/2.sTypoLineGap]



* 🔥 **FAIL** <p>hhea.lineGap is &quot;200&quot; it should be 0</p>
 [code: bad-hhea.lineGap]



* 🔥 **FAIL** <p>The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1157 when it should be at least 1200</p>
 [code: bad-hhea-range]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 606 among a set of 3 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 553:
less, greater</p>
<p>Width = 628:
equal, notequal</p>
<p>Width = 602:
logicalnot</p>
<p>Width = 579:
greaterequal, plusminus, lessequal</p>
<p>Width = 532:
multiply</p>
<p>Width = 554:
approxequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- uni0328.alt
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, tifinagh, tai-le, coptic, math, old-permic, todhri, hebrew, syriac, duployan, canadian-aboriginal</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: math, greek, elbasan</li>
<li>U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: math, greek, elbasan</li>
<li>U+03BC GREEK SMALL LETTER MU: try adding one of: math, greek</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: math, greek, yi</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: tai-tham, math, yi, symbols</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: math, symbols</li>
<li>U+266A EIGHTH NOTE: try adding one of: symbols, music</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Igbo (Latn, 27,823,640 speakers), Bafut (Latn, 158,146 speakers), Bete-Bendi (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Aghem (Latn, 38,843 speakers), Nzakara (Latn, 50,000 speakers), Koonzime (Latn, 40,000 speakers), Nateni (Latn, 100,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Mundani (Latn, 34,000 speakers), Ma’di (Latn, 584,000 speakers), Han (Latn, 6 speakers), Basaa (Latn, 332,940 speakers), Zapotec (Latn, 490,000 speakers), Vute (Latn, 21,000 speakers), Makaa (Latn, 221,000 speakers), Ejagham (Latn, 120,000 speakers), Ebira (Latn, 2,200,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Cicipu (Latn, 44,000 speakers), Navajo (Latn, 166,319 speakers), Kom (Latn, 360,685 speakers), Mango (Latn, 77,000 speakers), Heiltsuk (Latn, 300 speakers), Dan (Latn, 1,099,244 speakers), Belarusian (Cyrl, 10,064,517 speakers), Teke-Ebo (Latn, 260,000 speakers), South Central Banda (Latn, 244,000 speakers), Mfumte (Latn, 79,000 speakers), Yala (Latn, 200,000 speakers), Ekpeye (Latn, 226,000 speakers), Gulay (Latn, 250,478 speakers), Sar (Latn, 500,000 speakers), Avokaya (Latn, 100,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Kaska (Latn, 125 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[20] AtkinsonHyperlegibleNext-Italic[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking Vertical Metric Linegaps. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>hhea lineGap is not equal to 0.</p>
<p><em>Overridden</em>: This check was originally a WARN but was
overridden by the universal profile:
For Google Fonts, all messages from this check are considered FAILs.</p>
 [code: hhea]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoDescender (-251) and hhea descent (-161) must be equal.</p>
 [code: descender]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Variable font instance name 'Atkinson Hyperlegible Next ExtraLight Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 257 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Atkinson Hyperlegible Next ExtraLight Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 257 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Atkinson Hyperlegible Next Light Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 259 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Atkinson Hyperlegible Next Light Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 259 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Atkinson Hyperlegible Next Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 261 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Atkinson Hyperlegible Next Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 261 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Atkinson Hyperlegible Next Medium Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 263 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Atkinson Hyperlegible Next Medium Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 263 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Atkinson Hyperlegible Next SemiBold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 265 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Atkinson Hyperlegible Next SemiBold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 265 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Atkinson Hyperlegible Next Bold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 267 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Atkinson Hyperlegible Next Bold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 267 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Atkinson Hyperlegible Next ExtraBold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 269 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Atkinson Hyperlegible Next ExtraBold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 269 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* ⚠️ **WARN** <p>Name ID 6 'AtkinsonHyperlegibleNext-Italic' exceeds 27 characters. This has been found to cause problems with PostScript printers, especially on Mac platforms.</p>
 [code: nameid6-too-long]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: &quot;Braille Institute of America, Inc. provides Atkinson Hyperlegible for use, without derivatives or alteration, to the public free of charge for all non-commercial and commercial work. No attribution required.&quot; Must be changed to &quot;This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: <a href="https://openfontlicense.org">https://openfontlicense.org</a>&quot;</p>
 [code: wrong]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Substitute copyright, registered and trademark symbols in name table entries. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>NAMEID #0 contains symbols that should be replaced by '(c)'.</p>
 [code: unwanted-chars]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check license file has good copyright string. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>First line in license file is:</p>
<p>&quot;copyright 20** the my font project authors (<a href="https://github.com/googlefonts/googlefonts-project-template">https://github.com/googlefonts/googlefonts-project-template</a>)&quot;</p>
<p>which does not match the expected format, similar to:</p>
<p>&quot;Copyright 2022 The Familyname Project Authors (git url)&quot;</p>
 [code: bad-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.copyright.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;© 2020, 2024 Braille Institute of America, Inc., a 501(c)(3) Charitable Organization.&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 fsType does not impose restrictions. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.</p>
<p>No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead.</p>
 [code: drm]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0060 (GRAVE ACCENT)


- 0x00A8 (DIAERESIS)


- 0x00AF (MACRON)


- 0x00B4 (ACUTE ACCENT)


- 0x00B8 (CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


- 0x02C7 (CARON)


- 0x02D8 (BREVE)


- 0x02D9 (DOT ABOVE)


- 0x02DA (RING ABOVE)


- 0x02DB (OGONEK)


- 0x02DC (SMALL TILDE)


- 0x02DD (DOUBLE ACUTE ACCENT)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Are there non-ASCII characters in ASCII-only NAME table entries? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Bad string at [nameID 0, 'utf_16_be']: 'b'© 2020, 2024 Braille Institute of America, Inc., a 501(c)(3) Charitable Organization.''</p>
 [code: bad-string]



* 🔥 **FAIL** <p>There are 1 strings containing non-ASCII characters in the ASCII-only NAME table entries.</p>
 [code: non-ascii-strings]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoLineGap is &quot;150&quot; it should be 0</p>
 [code: bad-OS/2.sTypoLineGap]



* 🔥 **FAIL** <p>hhea.lineGap is &quot;200&quot; it should be 0</p>
 [code: bad-hhea.lineGap]



* 🔥 **FAIL** <p>The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1157 when it should be at least 1200</p>
 [code: bad-hhea-range]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 606 among a set of 3 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 553:
less, greater</p>
<p>Width = 628:
equal, notequal</p>
<p>Width = 602:
logicalnot</p>
<p>Width = 579:
greaterequal, plusminus, lessequal</p>
<p>Width = 531:
multiply</p>
<p>Width = 554:
approxequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- uni0328.alt
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, tifinagh, tai-le, coptic, math, old-permic, todhri, hebrew, syriac, duployan, canadian-aboriginal</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: math, greek, elbasan</li>
<li>U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: math, greek, elbasan</li>
<li>U+03BC GREEK SMALL LETTER MU: try adding one of: math, greek</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: math, greek, yi</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: tai-tham, math, yi, symbols</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: math, symbols</li>
<li>U+266A EIGHTH NOTE: try adding one of: symbols, music</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Igbo (Latn, 27,823,640 speakers), Bafut (Latn, 158,146 speakers), Bete-Bendi (Latn, 100,000 speakers), Fur (Latn, 1,230,163 speakers), Aghem (Latn, 38,843 speakers), Nzakara (Latn, 50,000 speakers), Koonzime (Latn, 40,000 speakers), Nateni (Latn, 100,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Mundani (Latn, 34,000 speakers), Ma’di (Latn, 584,000 speakers), Han (Latn, 6 speakers), Basaa (Latn, 332,940 speakers), Zapotec (Latn, 490,000 speakers), Vute (Latn, 21,000 speakers), Makaa (Latn, 221,000 speakers), Ejagham (Latn, 120,000 speakers), Ebira (Latn, 2,200,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Cicipu (Latn, 44,000 speakers), Navajo (Latn, 166,319 speakers), Kom (Latn, 360,685 speakers), Mango (Latn, 77,000 speakers), Heiltsuk (Latn, 300 speakers), Dan (Latn, 1,099,244 speakers), Belarusian (Cyrl, 10,064,517 speakers), Teke-Ebo (Latn, 260,000 speakers), South Central Banda (Latn, 244,000 speakers), Mfumte (Latn, 79,000 speakers), Yala (Latn, 200,000 speakers), Ekpeye (Latn, 226,000 speakers), Gulay (Latn, 250,478 speakers), Sar (Latn, 500,000 speakers), Avokaya (Latn, 100,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Kaska (Latn, 125 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* Adieresis (U+00C4): X=465.0,Y=794.0 (should be at ascender 796?)

* Adieresis (U+00C4): X=573.0,Y=794.0 (should be at ascender 796?)

* Adieresis (U+00C4): X=285.0,Y=794.0 (should be at ascender 796?)

* Adieresis (U+00C4): X=393.0,Y=794.0 (should be at ascender 796?)

* Aring (U+00C5): X=507.0,Y=669.0 (should be at cap-height 668?)

* Cdotaccent (U+010A): X=411.0,Y=794.0 (should be at ascender 796?)

* Cdotaccent (U+010A): X=519.0,Y=794.0 (should be at ascender 796?)

* Edieresis (U+00CB): X=457.0,Y=794.0 (should be at ascender 796?)

* Edieresis (U+00CB): X=565.0,Y=794.0 (should be at ascender 796?)

* Edieresis (U+00CB): X=277.0,Y=794.0 (should be at ascender 796?)

* Edieresis (U+00CB): X=385.0,Y=794.0 (should be at ascender 796?)

* Edotaccent (U+0116): X=367.0,Y=794.0 (should be at ascender 796?)

* Edotaccent (U+0116): X=475.0,Y=794.0 (should be at ascender 796?)

* Gdotaccent (U+0120): X=411.0,Y=794.0 (should be at ascender 796?)

* Gdotaccent (U+0120): X=519.0,Y=794.0 (should be at ascender 796?)

* Idieresis (U+00CF): X=347.0,Y=794.0 (should be at ascender 796?)

* Idieresis (U+00CF): X=455.0,Y=794.0 (should be at ascender 796?)

* Idieresis (U+00CF): X=167.0,Y=794.0 (should be at ascender 796?)

* Idieresis (U+00CF): X=275.0,Y=794.0 (should be at ascender 796?)

* Idotaccent (U+0130): X=257.0,Y=794.0 (should be at ascender 796?)

* Idotaccent (U+0130): X=365.0,Y=794.0 (should be at ascender 796?)

* Odieresis (U+00D6): X=499.0,Y=794.0 (should be at ascender 796?)

* Odieresis (U+00D6): X=607.0,Y=794.0 (should be at ascender 796?)

* Odieresis (U+00D6): X=319.0,Y=794.0 (should be at ascender 796?)

* Odieresis (U+00D6): X=427.0,Y=794.0 (should be at ascender 796?)

* S (U+0053): X=262.5,Y=666.5 (should be at cap-height 668?)

* S (U+0053): X=452.5,Y=666.0 (should be at cap-height 668?)

* Sacute (U+015A): X=262.5,Y=666.5 (should be at cap-height 668?)

* Sacute (U+015A): X=452.5,Y=666.0 (should be at cap-height 668?)

* Scaron (U+0160): X=262.5,Y=666.5 (should be at cap-height 668?)

* Scaron (U+0160): X=452.5,Y=666.0 (should be at cap-height 668?)

* Scedilla (U+015E): X=262.5,Y=666.5 (should be at cap-height 668?)

* Scedilla (U+015E): X=452.5,Y=666.0 (should be at cap-height 668?)

* uni0218 (U+0218): X=262.5,Y=666.5 (should be at cap-height 668?)

* uni0218 (U+0218): X=452.5,Y=666.0 (should be at cap-height 668?)

* U (U+0055): X=232.0,Y=-1.5 (should be at baseline 0?)

* Uacute (U+00DA): X=232.0,Y=-1.5 (should be at baseline 0?)

* Ucircumflex (U+00DB): X=232.0,Y=-1.5 (should be at baseline 0?)

* Udieresis (U+00DC): X=232.0,Y=-1.5 (should be at baseline 0?)

* Udieresis (U+00DC): X=496.0,Y=794.0 (should be at ascender 796?)

* Udieresis (U+00DC): X=604.0,Y=794.0 (should be at ascender 796?)

* Udieresis (U+00DC): X=316.0,Y=794.0 (should be at ascender 796?)

* Udieresis (U+00DC): X=424.0,Y=794.0 (should be at ascender 796?)

* Ugrave (U+00D9): X=232.0,Y=-1.5 (should be at baseline 0?)

* Uhungarumlaut (U+0170): X=232.0,Y=-1.5 (should be at baseline 0?)

* Umacron (U+016A): X=232.0,Y=-1.5 (should be at baseline 0?)

* Uogonek (U+0172): X=230.0,Y=-1.5 (should be at baseline 0?)

* Uring (U+016E): X=438.0,Y=670.0 (should be at cap-height 668?)

* Uring (U+016E): X=438.0,Y=670.0 (should be at cap-height 668?)

* Uring (U+016E): X=232.0,Y=-1.5 (should be at baseline 0?)

* Wdieresis (U+1E84): X=577.0,Y=794.0 (should be at ascender 796?)

* Wdieresis (U+1E84): X=685.0,Y=794.0 (should be at ascender 796?)

* Wdieresis (U+1E84): X=397.0,Y=794.0 (should be at ascender 796?)

* Wdieresis (U+1E84): X=505.0,Y=794.0 (should be at ascender 796?)

* Ydieresis (U+0178): X=435.0,Y=794.0 (should be at ascender 796?)

* Ydieresis (U+0178): X=543.0,Y=794.0 (should be at ascender 796?)

* Ydieresis (U+0178): X=255.0,Y=794.0 (should be at ascender 796?)

* Ydieresis (U+0178): X=363.0,Y=794.0 (should be at ascender 796?)

* Zdotaccent (U+017B): X=368.0,Y=794.0 (should be at ascender 796?)

* Zdotaccent (U+017B): X=476.0,Y=794.0 (should be at ascender 796?)

* a (U+0061): X=87.0,Y=2.0 (should be at baseline 0?)

* aacute (U+00E1): X=87.0,Y=2.0 (should be at baseline 0?)

* abreve (U+0103): X=87.0,Y=2.0 (should be at baseline 0?)

* acircumflex (U+00E2): X=87.0,Y=2.0 (should be at baseline 0?)

* adieresis (U+00E4): X=87.0,Y=2.0 (should be at baseline 0?)

* agrave (U+00E0): X=87.0,Y=2.0 (should be at baseline 0?)

* amacron (U+0101): X=87.0,Y=2.0 (should be at baseline 0?)

* aogonek (U+0105): X=87.0,Y=2.0 (should be at baseline 0?)

* aring (U+00E5): X=87.0,Y=2.0 (should be at baseline 0?)

* atilde (U+00E3): X=87.0,Y=2.0 (should be at baseline 0?)

* ae (U+00E6): X=88.0,Y=2.0 (should be at baseline 0?)

* dcaron (U+010F): X=741.0,Y=666.0 (should be at cap-height 668?)

* g (U+0067): X=344.0,Y=495.5 (should be at x-height 496?)

* lcaron (U+013E): X=399.0,Y=667.0 (should be at cap-height 668?)

* s (U+0073): X=343.0,Y=494.5 (should be at x-height 496?)

* uni0163 (U+0163): X=168.0,Y=1.0 (should be at baseline 0?)

* three (U+0033): X=422.0,Y=670.0 (should be at cap-height 668?)

* eight (U+0038): X=200.5,Y=-0.5 (should be at baseline 0?)

* three.tf: X=464.0,Y=670.0 (should be at cap-height 668?)

* eight.tf: X=208.5,Y=-0.5 (should be at baseline 0?)

* threequarters (U+00BE): X=325.0,Y=668.5 (should be at cap-height 668?)

* exclamdown (U+00A1): X=47.0,Y=2.0 (should be at baseline 0?)

* exclamdown (U+00A1): X=137.0,Y=2.0 (should be at baseline 0?)

* ampersand (U+0026): X=490.5,Y=667.0 (should be at cap-height 668?)

* uni2113 (U+2113): X=287.5,Y=-1.5 (should be at baseline 0?)

* dollar (U+0024): X=262.5,Y=666.0 (should be at cap-height 668?)

* Euro (U+20AC): X=446.5,Y=1.5 (should be at baseline 0?)

* greater (U+003E): X=-13.0,Y=1.0 (should be at baseline 0?)

* less (U+003C): X=460.0,Y=1.0 (should be at baseline 0?)

* uni0308.case: X=334.0,Y=794.0 (should be at ascender 796?)

* uni0308.case: X=442.0,Y=794.0 (should be at ascender 796?)

* uni0308.case: X=154.0,Y=794.0 (should be at ascender 796?)

* uni0308.case: X=262.0,Y=794.0 (should be at ascender 796?)

* uni0307.case: X=154.0,Y=794.0 (should be at ascender 796?)

* uni0307.case: X=262.0,Y=794.0 (should be at ascender 796?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/variable/AtkinsonHyperlegibleNext[wght].ttf', 'fonts/variable/AtkinsonHyperlegibleNext-Italic[wght].ttf'].</p>
 [code: missing-os2-fsselection-bit7]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 25 | 17 | 189 | 15 | 238 | 0 | 
| 0% | 0% | 5% | 4% | 39% | 3% | 49% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
