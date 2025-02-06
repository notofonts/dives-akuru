## FontBakery report

fontbakery version: 0.13.1





## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] NotoSerifDivesAkuru-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check base characters have non-zero advance width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#base-has-width">base_has_width</a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs had zero advance width:
- u1193F (U+1193F)</p>
 [code: zero-width-bases]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[17] NotoSerifDivesAkuru-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Do we have the latest version of FontBakery installed? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#fontbakery-version">fontbakery_version</a></summary>
    <div>







* 🔥 **FAIL** <p>Current FontBakery version is 0.13.1, while a newer 0.13.2 is already available. Please upgrade it with 'pip install -U fontbakery'</p>
 [code: outdated-fontbakery]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-description-has-article">googlefonts/description/has_article</a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-mark-chars">opentype/gdef_mark_chars</a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
u1193E (U+1193E)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check GDEF mark glyph class doesn't have characters that are not marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-non-mark-chars">opentype/gdef_non_mark_chars</a></summary>
    <div>







* ⚠️ **WARN** <p>The following non-mark characters should not be in the GDEF mark glyph class:
U+1193F</p>
 [code: non-mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if uppercase glyphs are vertically centered. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#caps-vertically-centered">caps_vertically_centered</a></summary>
    <div>







* ⚠️ **WARN** <p>Uppercase glyphs are not vertically centered in the em box.</p>
 [code: vertical-metrics-not-centered]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 579:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- nullmark
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Glyph names are all valid? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#valid-glyphnames">valid_glyphnames</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyph names may be too long for some legacy systems which may expect a maximum 31-characters length limit:
dda_medya_iVoweldivesakuru.undera, ha_medra_aaVoweldivesakuru.undera, ha_medya_iVoweldivesakuru.undera, ka_medra_uVoweldivesakuru.undera, ka_medya_iVoweldivesakuru.undera, lla_medya_iVoweldivesakuru.undera, ma_medya_eVoweldivesakuru.undera, ma_medya_iVoweldivesakuru.undera, ma_medya_iiVoweldivesakuru.undera, na_medra_aaVoweldivesakuru.undera, na_medya_iVoweldivesakuru.undera, sa_medra_iiVoweldivesakuru.undera, ta_medra_uVoweldivesakuru.undera, ta_medya_halantadivesakuru.undera, ta_medya_iVoweldivesakuru.undera, ta_ta_medra_iVoweldivesakuru.undera, ta_tha_medra_iVoweldivesakuru.undera, va_medya_iVoweldivesakuru.undera, va_medya_uVoweldivesakuru.undera and ya_medya_iVoweldivesakuru.undera</p>
 [code: legacy-long-names]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSerifDivesAkuru/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, coptic, cherokee, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: coptic, syriac, tai-le, canadian-aboriginal, math, hebrew, old-permic, duployan, malayalam, todhri, tifinagh</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: kayah-li, thai, lepcha, yi, sundanese, kannada, khojki, masaram-gondi, grantha, duployan, wancho, coptic, manichaean, syriac, tai-viet, buginese, tagbanwa, lao, rejang, batak, sogdian, devanagari, miao, tibetan, chakma, ahom, phags-pa, psalter-pahlavi, math, gurmukhi, symbols, sharada, oriya, siddham, tai-tham, tagalog, canadian-aboriginal, brahmi, syloti-nagri, mongolian, newa, cham, malayalam, music, telugu, kharoshthi, hanunoo, buhid, khmer, hebrew, meetei-mayek, gujarati, warang-citi, new-tai-lue, elbasan, osage, limbu, marchen, hanifi-rohingya, sinhala, khudawadi, old-permic, armenian, thaana, dogra, myanmar, modi, kaithi, mandaic, mahajani, pahawh-hmong, nko, javanese, balinese, tirhuta, tamil, zanabazar-square, takri, tai-le, caucasian-albanian, gunjala-gondi, bengali, adlam, bhaiksuki, saurashtra, bassa-vah, mende-kikakui, soyombo, tifinagh</li>
<li>U+11939 : not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>dives-akuru</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_TransLatin_Arabic glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŀ, ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ, Ʒ, Ǥ, ǥ, Ǯ, ǯ, ʒ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ĳ, ĳ</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Northern Tutchone (Latn, 85 speakers), Dutch (Latn, 31,709,104 speakers), Southern Tutchone (Latn, 65 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Mundani (Latn, 34,000 speakers), Zapotec (Latn, 490,000 speakers), Makaa (Latn, 221,000 speakers), Keliko (Latn, 63,000 speakers), Southern Kisi (Latn, 360,000 speakers), Dan (Latn, 1,099,244 speakers), Avokaya (Latn, 100,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Kom (Latn, 360,685 speakers), Longto (Latn, 5,000 speakers), Basaa (Latn, 332,940 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Ikwere (Latn, 717,000 speakers), Ekpeye (Latn, 226,000 speakers), Koonzime (Latn, 40,000 speakers), Bafut (Latn, 158,146 speakers), Abua (Latn, 25,000 speakers), Heiltsuk (Latn, 300 speakers), Mango (Latn, 77,000 speakers), Kaska (Latn, 125 speakers), Western Krahn (Latn, 97,800 speakers), South Central Banda (Latn, 244,000 speakers), Vute (Latn, 21,000 speakers), Lugbara (Latn, 2,200,000 speakers), Gulay (Latn, 250,478 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Han (Latn, 6 speakers), Ejagham (Latn, 120,000 speakers), Nateni (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Ngbaka (Latn, 1,020,000 speakers), Igbo (Latn, 27,823,640 speakers), Yala (Latn, 200,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Bete-Bendi (Latn, 100,000 speakers), Ebira (Latn, 2,200,000 speakers), Fur (Latn, 1,230,163 speakers), Mfumte (Latn, 79,000 speakers), Dii (Latn, 71,000 speakers), Nzakara (Latn, 50,000 speakers), Sar (Latn, 500,000 speakers), Cicipu (Latn, 44,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* lla_ooVoweldivesakuru.undera: L&lt;&lt;1445.0,32.0&gt;--&lt;1446.0,32.0&gt;&gt; -&gt; L&lt;&lt;1446.0,32.0&gt;--&lt;1446.0,32.0&gt;&gt;

* lla_ooVoweldivesakuru: L&lt;&lt;1445.0,32.0&gt;--&lt;1446.0,32.0&gt;&gt; -&gt; L&lt;&lt;1446.0,32.0&gt;--&lt;1446.0,32.0&gt;&gt;

* u1192E_u11931.undera: L&lt;&lt;449.0,32.0&gt;--&lt;450.0,32.0&gt;&gt; -&gt; L&lt;&lt;450.0,32.0&gt;--&lt;450.0,32.0&gt;&gt;

* u1192E_u11931: L&lt;&lt;449.0,32.0&gt;--&lt;450.0,32.0&gt;&gt; -&gt; L&lt;&lt;450.0,32.0&gt;--&lt;450.0,32.0&gt;&gt;

* u1192E_u11932.undera: L&lt;&lt;449.0,32.0&gt;--&lt;450.0,32.0&gt;&gt; -&gt; L&lt;&lt;450.0,32.0&gt;--&lt;450.0,32.0&gt;&gt;

* u1192E_u11932: L&lt;&lt;449.0,32.0&gt;--&lt;450.0,32.0&gt;&gt; -&gt; L&lt;&lt;450.0,32.0&gt;--&lt;450.0,32.0&gt;&gt;

* u1192E_u11938.undera: L&lt;&lt;1095.0,32.0&gt;--&lt;1096.0,32.0&gt;&gt; -&gt; L&lt;&lt;1096.0,32.0&gt;--&lt;1096.0,32.0&gt;&gt;

* u1192E_u11938: L&lt;&lt;1095.0,32.0&gt;--&lt;1096.0,32.0&gt;&gt; -&gt; L&lt;&lt;1096.0,32.0&gt;--&lt;1096.0,32.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* u11909.alt.undera: L&lt;&lt;753.0,127.0&gt;--&lt;754.0,127.0&gt;&gt;/B&lt;&lt;754.0,127.0&gt;-&lt;546.0,95.0&gt;-&lt;421.0,50.5&gt;&gt; = 8.746162262555211

* u11909.alt: L&lt;&lt;753.0,127.0&gt;--&lt;754.0,127.0&gt;&gt;/B&lt;&lt;754.0,127.0&gt;-&lt;546.0,95.0&gt;-&lt;421.0,50.5&gt;&gt; = 8.746162262555211

* u1190C_u1193D.0002: B&lt;&lt;1026.0,595.0&gt;-&lt;973.0,573.0&gt;-&lt;924.0,551.0&gt;&gt;/B&lt;&lt;924.0,551.0&gt;-&lt;962.0,559.0&gt;-&lt;993.0,559.0&gt;&gt; = 12.29044910706117

* u1190C_u1193D.0003: B&lt;&lt;1218.0,666.0&gt;-&lt;1066.0,611.0&gt;-&lt;932.0,550.0&gt;&gt;/B&lt;&lt;932.0,550.0&gt;-&lt;968.0,558.0&gt;-&lt;996.0,558.0&gt;&gt; = 11.947353801719451

* u1190C_u1193D.0004: B&lt;&lt;1111.0,624.0&gt;-&lt;1017.0,586.0&gt;-&lt;934.0,548.0&gt;&gt;/B&lt;&lt;934.0,548.0&gt;-&lt;971.0,556.0&gt;-&lt;1000.0,556.0&gt;&gt; = 12.399321877776666

* u1190C_u1193D.0005: B&lt;&lt;1152.5,629.5&gt;-&lt;1048.0,590.0&gt;-&lt;953.0,549.0&gt;&gt;/B&lt;&lt;953.0,549.0&gt;-&lt;980.0,554.0&gt;-&lt;1002.0,554.0&gt;&gt; = 12.852533949245883

* u1190C_u1193D.undera: B&lt;&lt;1021.5,688.5&gt;-&lt;900.0,601.0&gt;-&lt;797.0,514.0&gt;&gt;/B&lt;&lt;797.0,514.0&gt;-&lt;840.0,537.0&gt;-&lt;881.5,547.0&gt;&gt; = 12.04484787403171

* va_medya_iVoweldivesakuru.undera: B&lt;&lt;792.5,200.0&gt;-&lt;749.0,138.0&gt;-&lt;677.0,94.0&gt;&gt;/B&lt;&lt;677.0,94.0&gt;-&lt;803.0,135.0&gt;-&lt;875.5,182.5&gt;&gt; = 13.404842093600015

* va_medya_iVoweldivesakuru: B&lt;&lt;792.5,200.0&gt;-&lt;749.0,138.0&gt;-&lt;677.0,94.0&gt;&gt;/B&lt;&lt;677.0,94.0&gt;-&lt;803.0,135.0&gt;-&lt;875.5,182.5&gt;&gt; = 13.404842093600015

* va_medya_uVoweldivesakuru.undera: B&lt;&lt;1366.5,198.0&gt;-&lt;1331.0,142.0&gt;-&lt;1249.0,89.0&gt;&gt;/B&lt;&lt;1249.0,89.0&gt;-&lt;1348.0,129.0&gt;-&lt;1427.5,181.0&gt;&gt; = 10.875563401670016

* va_medya_uVoweldivesakuru.undera: B&lt;&lt;792.5,200.0&gt;-&lt;749.0,138.0&gt;-&lt;677.0,94.0&gt;&gt;/B&lt;&lt;677.0,94.0&gt;-&lt;803.0,135.0&gt;-&lt;875.5,182.5&gt;&gt; = 13.404842093600015

* va_medya_uVoweldivesakuru: B&lt;&lt;1366.5,198.0&gt;-&lt;1331.0,142.0&gt;-&lt;1249.0,89.0&gt;&gt;/B&lt;&lt;1249.0,89.0&gt;-&lt;1348.0,129.0&gt;-&lt;1427.5,181.0&gt;&gt; = 10.875563401670016

* va_medya_uVoweldivesakuru: B&lt;&lt;792.5,200.0&gt;-&lt;749.0,138.0&gt;-&lt;677.0,94.0&gt;&gt;/B&lt;&lt;677.0,94.0&gt;-&lt;803.0,135.0&gt;-&lt;875.5,182.5&gt;&gt; = 13.404842093600015

* va_medyadivesakuru.undera: B&lt;&lt;792.5,200.0&gt;-&lt;749.0,138.0&gt;-&lt;677.0,94.0&gt;&gt;/B&lt;&lt;677.0,94.0&gt;-&lt;803.0,135.0&gt;-&lt;875.5,182.5&gt;&gt; = 13.404842093600015

* va_medyadivesakuru: B&lt;&lt;792.5,200.0&gt;-&lt;749.0,138.0&gt;-&lt;677.0,94.0&gt;&gt;/B&lt;&lt;677.0,94.0&gt;-&lt;803.0,135.0&gt;-&lt;875.5,182.5&gt;&gt; = 13.404842093600015
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-semi-vertical">outline_semi_vertical</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* u11944 (U+11944): L&lt;&lt;272.0,471.0&gt;--&lt;269.0,39.0&gt;&gt;

* u11944 (U+11944): L&lt;&lt;543.0,471.0&gt;--&lt;540.0,39.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vertical-metrics">googlefonts/vertical_metrics</a></summary>
    <div>







* ⚠️ **WARN** <p>We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.779x (1779)</p>
 [code: bad-hhea-range]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 3 | 15 | 106 | 6 | 106 | 0 | 
| 0% | 0% | 1% | 6% | 45% | 3% | 45% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
