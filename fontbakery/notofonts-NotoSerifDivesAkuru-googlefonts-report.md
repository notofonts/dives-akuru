## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[11] NotoSerifDivesAkuru-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check GDEF mark glyph class doesn't have characters that are not marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following non-mark characters should not be in the GDEF mark glyph class:
U+1193F and U+11941</p>
 [code: non-mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 579:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- dha_medyadivesakuru

- ktouchdivesakuru

- ntouchdivesakuru

- ptouchdivesakuru

- ttouchdivesakuru

- u1193D.04

- ya_utouchdivesakuru

- ya_vowelItouchdivesakuru
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSerifDivesAkuru/googlefonts/ttf does not have an article.</p>
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
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, coptic, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: hebrew, tifinagh, todhri, malayalam, duployan, tai-le, canadian-aboriginal, old-permic, math, syriac, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: chakma, marchen, sogdian, lepcha, hebrew, lao, telugu, psalter-pahlavi, mongolian, dogra, wancho, khojki, siddham, oriya, cham, syloti-nagri, music, tibetan, rejang, yi, tagalog, sinhala, masaram-gondi, malayalam, phags-pa, soyombo, kannada, syriac, osage, kharoshthi, meetei-mayek, adlam, hanifi-rohingya, ahom, bassa-vah, mahajani, symbols, khmer, myanmar, manichaean, armenian, buhid, gujarati, gurmukhi, tai-tham, tai-viet, mende-kikakui, takri, tirhuta, tai-le, canadian-aboriginal, old-permic, kayah-li, elbasan, pahawh-hmong, duployan, devanagari, gunjala-gondi, balinese, batak, grantha, saurashtra, warang-citi, kaithi, mandaic, new-tai-lue, hanunoo, khudawadi, zanabazar-square, tifinagh, miao, sundanese, buginese, caucasian-albanian, sharada, math, coptic, limbu, newa, modi, javanese, brahmi, nko, thai, bhaiksuki, tagbanwa, bengali, tamil, thaana</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>dives-akuru</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Fur (Latn, 1,230,163 speakers), Belarusian (Cyrl, 10,064,517 speakers), Heiltsuk (Latn, 300 speakers), Mundani (Latn, 34,000 speakers), Ekpeye (Latn, 226,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Zapotec (Latn, 490,000 speakers), Koonzime (Latn, 40,000 speakers), Bafut (Latn, 158,146 speakers), Aghem (Latn, 38,843 speakers), Teke-Ebo (Latn, 260,000 speakers), Mango (Latn, 77,000 speakers), Nzakara (Latn, 50,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Southern Kisi (Latn, 360,000 speakers), Dii (Latn, 71,000 speakers), Gulay (Latn, 250,478 speakers), Igbo (Latn, 27,823,640 speakers), Ukrainian (Cyrl, 29,273,587 speakers), South Central Banda (Latn, 244,000 speakers), Han (Latn, 6 speakers), Ejagham (Latn, 120,000 speakers), Cicipu (Latn, 44,000 speakers), Ebira (Latn, 2,200,000 speakers), Navajo (Latn, 166,319 speakers), Avokaya (Latn, 100,000 speakers), Mfumte (Latn, 79,000 speakers), Vute (Latn, 21,000 speakers), Makaa (Latn, 221,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Sar (Latn, 500,000 speakers), Nateni (Latn, 100,000 speakers), Ma’di (Latn, 584,000 speakers), Kaska (Latn, 125 speakers), Kom (Latn, 360,685 speakers), Lugbara (Latn, 2,200,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Basaa (Latn, 332,940 speakers), Dan (Latn, 1,099,244 speakers), Yala (Latn, 200,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* u11903 (U+11903): X=231.0,Y=-2.0 (should be at baseline 0?)

* u1190C (U+1190C): X=440.0,Y=-2.0 (should be at baseline 0?)

* u1191E (U+1191E): X=609.0,Y=1.0 (should be at baseline 0?)

* u1191E (U+1191E): X=475.0,Y=1.0 (should be at baseline 0?)

* u1192A (U+1192A): X=398.0,Y=-2.0 (should be at baseline 0?)

* u1192C (U+1192C): X=374.0,Y=-1.5 (should be at baseline 0?)

* ka_ra_vowelIdivesakuru: X=440.0,Y=-2.0 (should be at baseline 0?)

* ka_medradivesakuru: X=440.0,Y=-2.0 (should be at baseline 0?)

* u11916_u11929: X=994.0,Y=1.0 (should be at baseline 0?)

* dha_medyadivesakuru: X=609.0,Y=1.0 (should be at baseline 0?)

* dha_medyadivesakuru: X=475.0,Y=1.0 (should be at baseline 0?)

* dha_vowelIdivesakuru: X=609.0,Y=1.0 (should be at baseline 0?)

* dha_vowelIdivesakuru: X=475.0,Y=1.0 (should be at baseline 0?)

* dha_vowelIIdivesakuru: X=609.0,Y=1.0 (should be at baseline 0?)

* dha_vowelIIdivesakuru: X=475.0,Y=1.0 (should be at baseline 0?)

* dha_vowelIIdivesakuru: X=1032.0,Y=713.0 (should be at cap-height 714?)

* dha_vowelUdivesakuru: X=609.0,Y=1.0 (should be at baseline 0?)

* dha_vowelUdivesakuru: X=475.0,Y=1.0 (should be at baseline 0?)

* na_ta_medradivesakuru: X=223.0,Y=-291.0 (should be at descender -293?)

* u1191F_u1191E: X=833.5,Y=1.5 (should be at baseline 0?)

* u1191F_u1191E: X=699.5,Y=1.0 (should be at baseline 0?)

* na_dha_vowelIdivesakuru: X=833.5,Y=1.5 (should be at baseline 0?)

* na_dha_vowelIdivesakuru: X=699.5,Y=1.0 (should be at baseline 0?)

* na_dha_vowelIIdivesakuru: X=833.5,Y=1.5 (should be at baseline 0?)

* na_dha_vowelIIdivesakuru: X=699.5,Y=1.0 (should be at baseline 0?)

* na_dha_vowelIIdivesakuru: X=1257.0,Y=713.0 (should be at cap-height 714?)

* na_dha_vowelUdivesakuru: X=833.5,Y=1.5 (should be at baseline 0?)

* na_dha_vowelUdivesakuru: X=699.5,Y=1.0 (should be at baseline 0?)

* u11929_u11929: X=918.0,Y=1.0 (should be at baseline 0?)

* sha_ra_vowelIdivesakuru: X=1106.0,Y=-292.0 (should be at descender -293?)

* sha_ra_vowelIdivesakuru: X=398.0,Y=-2.0 (should be at baseline 0?)

* sha_medradivesakuru: X=398.0,Y=-2.0 (should be at baseline 0?)

* u1192C_u1191B: X=374.0,Y=-1.5 (should be at baseline 0?)

* sa_ta_medradivesakuru: X=354.0,Y=-1.5 (should be at baseline 0?)

* sa_pa_medradivesakuru: X=354.0,Y=-1.5 (should be at baseline 0?)

* u1192C_u11929: X=374.0,Y=-1.5 (should be at baseline 0?)

* sa_medyadivesakuru: X=354.0,Y=-1.5 (should be at baseline 0?)

* sa_vowelIdivesakuru: X=354.0,Y=-1.5 (should be at baseline 0?)

* sa_vowelUdivesakuru: X=354.0,Y=-1.5 (should be at baseline 0?)

* sdivesakuru: X=354.0,Y=-1.5 (should be at baseline 0?)

* na_dhdivesakuru: X=831.0,Y=1.0 (should be at baseline 0?)

* na_dhdivesakuru: X=699.0,Y=1.0 (should be at baseline 0?)

* ssa_ttdivesakuru: X=660.5,Y=2.0 (should be at baseline 0?)

* dhdivesakuru: X=602.5,Y=1.0 (should be at baseline 0?)

* dhdivesakuru: X=474.0,Y=1.0 (should be at baseline 0?)

* katouchdivesakuru: X=440.0,Y=-2.0 (should be at baseline 0?)

* u11952 (U+11952): X=266.5,Y=-1.5 (should be at baseline 0?)

* u11941 (U+11941): X=-240.0,Y=713.0 (should be at cap-height 714?)

* u11932 (U+11932): X=50.0,Y=713.0 (should be at cap-height 714?)

* u11935 (U+11935): X=114.0,Y=-1.5 (should be at baseline 0?)

* u11937 (U+11937): X=114.0,Y=-1.5 (should be at baseline 0?)

* u11937 (U+11937): X=504.0,Y=-1.5 (should be at baseline 0?)

* u11938 (U+11938): X=114.0,Y=-1.5 (should be at baseline 0?)

* u1193E (U+1193E): X=-26.0,Y=-2.0 (should be at baseline 0?)

* u1193E (U+1193E): X=25.0,Y=-2.0 (should be at baseline 0?)

* u1193F (U+1193F): X=-281.0,Y=712.0 (should be at cap-height 714?)

* u11943 (U+11943): X=-355.0,Y=-294.0 (should be at descender -293?)

* u11943 (U+11943): X=-355.0,Y=-294.0 (should be at descender -293?)

* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

* Gbreve (U+011E): X=519.0,Y=1.5 (should be at baseline 0?)

* uni0122 (U+0122): X=519.0,Y=1.5 (should be at baseline 0?)

* Gdotaccent (U+0120): X=519.0,Y=1.5 (should be at baseline 0?)

* Oslash (U+00D8): X=454.5,Y=715.5 (should be at cap-height 714?)

* a (U+0061): X=182.0,Y=536.5 (should be at x-height 536?)

* c (U+0063): X=360.0,Y=535.0 (should be at x-height 536?)

* comma (U+002C): X=114.0,Y=1.0 (should be at baseline 0?)

* g (U+0067): X=161.0,Y=-0.5 (should be at baseline 0?)

* gbreve (U+011F): X=161.0,Y=-0.5 (should be at baseline 0?)

* uni0123 (U+0123): X=161.0,Y=-0.5 (should be at baseline 0?)

* gdotaccent (U+0121): X=161.0,Y=-0.5 (should be at baseline 0?)

* nine (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

* parenleft (U+0028): X=314.0,Y=715.0 (should be at cap-height 714?)

* parenright (U+0029): X=32.0,Y=715.0 (should be at cap-height 714?)

* q (U+0071): X=412.5,Y=0.5 (should be at baseline 0?)

* quotedblbase (U+201E): X=314.0,Y=1.0 (should be at baseline 0?)

* quotedblbase (U+201E): X=114.0,Y=1.0 (should be at baseline 0?)

* quotedblleft (U+201C): X=420.0,Y=715.0 (should be at cap-height 714?)

* quotedblleft (U+201C): X=220.0,Y=715.0 (should be at cap-height 714?)

* quoteleft (U+2018): X=220.0,Y=715.0 (should be at cap-height 714?)

* quotesinglbase (U+201A): X=114.0,Y=1.0 (should be at baseline 0?)

* section (U+00A7): X=101.0,Y=2.0 (should be at baseline 0?)

* semicolon (U+003B): X=132.0,Y=1.0 (should be at baseline 0?)

* sterling (U+00A3): X=77.0,Y=1.0 (should be at baseline 0?)

* three (U+0033): X=334.5,Y=1.0 (should be at baseline 0?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* sa_pa_medradivesakuru: L&lt;&lt;1336.0,407.0&gt;--&lt;1386.0,410.0&gt;&gt; -&gt; L&lt;&lt;1386.0,410.0&gt;--&lt;1386.0,410.0&gt;&gt;

* sa_pa_medradivesakuru: L&lt;&lt;1386.0,410.0&gt;--&lt;1386.0,410.0&gt;&gt; -&gt; L&lt;&lt;1386.0,410.0&gt;--&lt;1387.0,410.0&gt;&gt;

* sa_pa_medradivesakuru: L&lt;&lt;1386.0,410.0&gt;--&lt;1387.0,410.0&gt;&gt; -&gt; L&lt;&lt;1387.0,410.0&gt;--&lt;1389.0,410.0&gt;&gt;

* sa_pa_medradivesakuru: L&lt;&lt;1387.0,410.0&gt;--&lt;1389.0,410.0&gt;&gt; -&gt; L&lt;&lt;1389.0,410.0&gt;--&lt;1389.0,410.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 1 | 10 | 116 | 6 | 118 | 0 | 
| 0% | 0% | 0% | 4% | 46% | 2% | 47% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
