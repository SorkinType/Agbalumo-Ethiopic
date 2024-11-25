## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[16] AgbalumoEthiopic-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs lack their case-swapping counterparts:</p>
<table>
<thead>
<tr>
<th align="left">Glyph present in the font</th>
<th align="left">Missing case-swapping counterpart</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">U+019E: LATIN SMALL LETTER N WITH LONG RIGHT LEG</td>
<td align="left">U+0220: LATIN CAPITAL LETTER N WITH LONG RIGHT LEG</td>
</tr>
<tr>
<td align="left">U+0223: LATIN SMALL LETTER OU</td>
<td align="left">U+0222: LATIN CAPITAL LETTER OU</td>
</tr>
<tr>
<td align="left">U+024B: LATIN SMALL LETTER Q WITH HOOK TAIL</td>
<td align="left">U+024A: LATIN CAPITAL LETTER SMALL Q WITH HOOK TAIL</td>
</tr>
<tr>
<td align="left">U+026A: LATIN LETTER SMALL CAPITAL I</td>
<td align="left">U+A7AE: LATIN CAPITAL LETTER SMALL CAPITAL I</td>
</tr>
<tr>
<td align="left">U+026C: LATIN SMALL LETTER L WITH BELT</td>
<td align="left">U+A7AD: LATIN CAPITAL LETTER L WITH BELT</td>
</tr>
<tr>
<td align="left">U+1E29: LATIN SMALL LETTER H WITH CEDILLA</td>
<td align="left">U+1E28: LATIN CAPITAL LETTER H WITH CEDILLA</td>
</tr>
<tr>
<td align="left">U+1E65: LATIN SMALL LETTER S WITH ACUTE AND DOT ABOVE</td>
<td align="left">U+1E64: LATIN CAPITAL LETTER S WITH ACUTE AND DOT ABOVE</td>
</tr>
<tr>
<td align="left">U+1E67: LATIN SMALL LETTER S WITH CARON AND DOT ABOVE</td>
<td align="left">U+1E66: LATIN CAPITAL LETTER S WITH CARON AND DOT ABOVE</td>
</tr>
<tr>
<td align="left">U+2184: LATIN SMALL LETTER REVERSED C</td>
<td align="left">U+2183: ROMAN NUMERAL REVERSED ONE HUNDRED</td>
</tr>
<tr>
<td align="left">U+2C61: LATIN SMALL LETTER L WITH DOUBLE BAR</td>
<td align="left">U+2C60: LATIN CAPITAL LETTER L WITH DOUBLE BAR</td>
</tr>
<tr>
<td align="left">U+2C66: LATIN SMALL LETTER T WITH DIAGONAL STROKE</td>
<td align="left">U+023E: LATIN CAPITAL LETTER T WITH DIAGONAL STROKE</td>
</tr>
<tr>
<td align="left">U+A727: LATIN SMALL LETTER HENG</td>
<td align="left">U+A726: LATIN CAPITAL LETTER HENG</td>
</tr>
<tr>
<td align="left">U+A741: LATIN SMALL LETTER K WITH STROKE</td>
<td align="left">U+A740: LATIN CAPITAL LETTER K WITH STROKE</td>
</tr>
<tr>
<td align="left">U+A7A9: LATIN SMALL LETTER S WITH OBLIQUE STROKE</td>
<td align="left">U+A7A8: LATIN CAPITAL LETTER S WITH OBLIQUE STROKE</td>
</tr>
<tr>
<td align="left">U+AB53: LATIN SMALL LETTER CHI</td>
<td align="left">U+A7B3: LATIN CAPITAL LETTER CHI</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Space and non-breaking space have the same width? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Space and non-breaking space have differing width: The space glyph named space is 220 font units wide, non-breaking space named (uni00A0) is 180 font units wide, and both should be positive and the same. GlyphsApp has &quot;Sidebearing arithmetic&quot; (<a href="https://glyphsapp.com/tutorials/spacing">https://glyphsapp.com/tutorials/spacing</a>) which allows you to set the non-breaking space width to always equal the space width.</p>
 [code: different-widths]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Shaper didn't attach acutecomb to uni0237</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to J</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ha_Latn (Hausa)</td>
<td align="left">Shaper didn't attach tildecomb to r</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to R</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ig_Latn (Igbo)</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECB.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECB.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1EE4</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1EE4</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">yo_Latn (Yoruba)</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EB9</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EB9</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bkm_Latn (Kom)</td>
<td align="left">Shaper didn't attach uni0302 to oe</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to ae</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to oe</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to AE</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to OE</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to AE</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to ae</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to OE</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0197</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ha_Latn (Hausa)</td>
<td align="left">Shaper didn't attach tildecomb to r</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to R</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bsc_Latn (Bassari)</td>
<td align="left">Shaper didn't attach tildecomb to h</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to H</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to w</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to W</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ee_Latn (Ewe)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dur_Latn (Dii)</td>
<td align="left">Shaper didn't attach uni0327 to agrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0229</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0229</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Ugrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Uacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0228</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Oacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Ograve</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Iacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to igrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to iacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0228</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to oacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to ugrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Igrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to ograve</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Agrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bbj_Latn (Ghomala)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">udu_Latn (Uduk)</td>
<td align="left">Some base glyphs were missing: T͟H, t͟h</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Some mark glyphs were missing: ◌͟</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to C</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to p</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to c</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to P</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tcd_Latn (Tafi)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni1EBD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni1EBC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to otilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to Otilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to Utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to Utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni01B1</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni01B1</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni028A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni01B1</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni028A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni01B1</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to w</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to W</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">byv_Latn (Medumba)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni2C6D</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni2C6D</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni2C6D</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kaj_Latn (Jju)</td>
<td align="left">Shaper didn't attach uni0331 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to a</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sba_Latn (Ngambay)</td>
<td align="left">Shaper didn't attach uni0330 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1E1B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to i</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1E1B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1E1A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1E1A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni01DD</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mhi_Latn (Ma’di)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1EE4</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni1EE4</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni1ECB.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni1ECB.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni1EE4</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EB9</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni1EB9</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECB.dotless</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">yo_Latn (Yoruba)</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EB9</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EB9</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mql_Latn (Mbelime)</td>
<td align="left">Shaper didn't attach uni0330 to i</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">csk_Latn (Jola-Kasa)</td>
<td align="left">Shaper didn't attach uni0325.case to L</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0325 to l</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">soy_Latn (Miyobe)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1EBC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EBD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mnf_Latn (Mundani)</td>
<td align="left">Shaper didn't attach uni0327 to agrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0229</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Acircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni01D2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0229</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to acircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Ugrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Ograve</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni01D1</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni01CD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni01D4</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Ocircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0228</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Ucircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to ugrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to ucircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni01CE</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0228</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to ocircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0229</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to ograve</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Agrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0228</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni01D3</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sld_Latn (Sissala)</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1EBC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EBD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0269</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">avu_Latn (Avokaya)</td>
<td align="left">Shaper didn't attach tildecomb.case to uni1EA0</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni1ECB.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni1ECB.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni1EA1</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1EA0</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EA1</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECB.dotless</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ife_Latn (Ifè)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Utilde</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ewo_Latn (Ewondo)</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bqc_Latn (Boko)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lu_Latn (Luba-Katanga)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">emk_Latn (Maninkakan, Eastern)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nga_Latn (Ngbaka)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to Utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to Utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to Utilde</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">aeb_Latn (Tunisian Darija)</td>
<td align="left">Some base glyphs were missing: Ŧ, ŧ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">awc_Latn (Cicipu)</td>
<td align="left">Shaper didn't attach tildecomb to oslash</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to Oslash</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B.case to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B.case to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EBD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1EBC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EBD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1EBC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni1EBD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni1EBC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni1EBD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni1EBC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B.case to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to otilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Otilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to otilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to Otilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to oslash</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Oslash</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to oslash</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to Oslash</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to oslash</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B.case to Oslash</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to Utilde</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">wwa_Latn (Waama)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">myk_Latn (Mamara Senoufo)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ig_Latn (Igbo)</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECB.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECB.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1EE4</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1EE4</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">teo_Latn (Teso)</td>
<td align="left">Some base glyphs were missing: ᵃ, ᵉ, ᵋ, ᵒ, ᵓ, ᶤ, ᶶ, ⁱ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lol_Latn (Mongo)</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ema_Latn (Emai-Iuleha-Ora)</td>
<td align="left">Shaper didn't attach uni0331.case to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to uni1EBC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to otilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni1EBD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to Otilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to e</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kkj_Latn (Kako)</td>
<td align="left">Shaper didn't attach uni0327.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nzk_Latn (Nzakara)</td>
<td align="left">Shaper didn't attach uni0308 to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni0244</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mgd_Latn (Moru)</td>
<td align="left">Shaper didn't attach gravecomb to adieresis</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Adieresis</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mgo_Latn (Metaʼ)</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">biv_Latn (Birifor, Southern)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni01B1</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mor_Latn (Moro)</td>
<td align="left">Some base glyphs were missing: Ꟈ, ꟈ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">box_Latn (Buamu)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nnw_Latn (Southern Nuni)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">eto_Latn (Eton, Cameroon)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0272</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni019D</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0272</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni019D</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ebo_Latn (Teke-Ebo)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0244</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fvr_Latn (Fur)</td>
<td align="left">Shaper didn't attach uni030C to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to acircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to uni01CD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to Acircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to Aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni01CE</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ntm_Latn (Nateni)</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to agrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0330.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1E2C</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1E74</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1E2C</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1E2D.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1E74</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1E75</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1E75</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to i</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0330.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1E2D.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">aks_Latn (Akeselem)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni01B1</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0269</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mwm_Latn (Sar)</td>
<td align="left">Shaper didn't attach uni0304 to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to R</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to n</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1E2D.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to w</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni1E2C</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni1E1A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1E1A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to oacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to W</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni1E74</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni1E75</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1E2C</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni1E2D.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to r</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1E74</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to amacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1E75</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni1E1B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to i</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1E1B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to N</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to omacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to a</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bfo_Latn (Malba Birifor)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">uth_Latn (ut-Hun)</td>
<td align="left">Shaper didn't attach uni0331.case to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to e</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">taq_Latn (Tamasheq (Latin))</td>
<td align="left">Shaper didn't attach uni030C to uni0237</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to J</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ln_Latn (Lingala)</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tuq_Latn (Tedaga)</td>
<td align="left">Shaper didn't attach dotbelowcomb to g</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach dotbelowcomb to G</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">vai_Latn (Vai (Latin))</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ybb_Latn (Yemba)</td>
<td align="left">Shaper didn't attach uni0304.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni018F</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lob_Latn (Lobi)</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nmg_Latn (Kwasio)</td>
<td align="left">Shaper didn't attach uni0304.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ozm_Latn (Koonzime)</td>
<td align="left">Shaper didn't attach uni030C.case to OE</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to Oslash</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to oe</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to oslash</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to OE</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to OE</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to oe</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to oslash</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to Oslash</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to oe</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mas_Latn (Masai)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0289</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ann_Latn (Obolo)</td>
<td align="left">Shaper didn't attach uni0304 to n</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to N</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1ECC</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">grb_Latn (Grebo)</td>
<td align="left">Shaper didn't attach uni0308.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bjt_Latn (Balanta-Ganja)</td>
<td align="left">Some base glyphs were missing: Ŧ, ŧ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">rub_Latn (Gungu)</td>
<td align="left">Shaper didn't attach uni0331 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni032F to b</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni032F.case to B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to dotlessi</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mev_Latn (Mano)</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to agrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to amacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0330.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0330.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0330.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1E75</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1E74</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1E75</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1E74</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni1E75</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni1E74</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kzr_Latn (Karang)</td>
<td align="left">Shaper didn't attach uni0327 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to iacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to oacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0229</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Uacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0228</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Oacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Iacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dow_Latn (Doyayo)</td>
<td align="left">Shaper didn't attach uni0327 to agrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Imacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Umacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to iacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to amacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to umacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to imacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Amacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Iacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Igrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to igrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Agrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gnd_Latn (Zulgo-Gemzek)</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dip_Latn (Dinka, Northeastern)</td>
<td align="left">Shaper didn't attach uni0308.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni0190</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kcg_Latn (Tyap)</td>
<td align="left">Shaper didn't attach uni0331 to iacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to Iacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to Aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to a</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fmp_Latn (Fe’fe’)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni2C6D</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni2C6D</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni2C6D</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni2C6D</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0251</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">apd_Latn (Sudanese Arabic)</td>
<td align="left">Some mark glyphs were missing: ◌͟</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nfu_Latn (Mfumte)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to Oslash</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to oslash</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to oslash</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to Oslash</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Oslash</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to oslash</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kia_Latn (Kim)</td>
<td align="left">Shaper didn't attach uni0330 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to i</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to a</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">goa_Latn (Guro)</td>
<td align="left">Shaper didn't attach uni030C to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">knf_Latn (Mankanya)</td>
<td align="left">Some base glyphs were missing: Ŧ, ŧ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ish_Latn (Esan)</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EB9</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EB9</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1ECC</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nyb_Latn (Nyangbo)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bba_Latn (Baatonum)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bqv_Latn (Koro Wachi)</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tuz_Latn (Turka)</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to otilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Otilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">igb_Latn (Ebira)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1EE4</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni1ECB.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni1EB9</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EB9</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EB9</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1EE4</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECB.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni1ECB.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni1EE4</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni1EE4</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECB.dotless</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bfd_Latn (Bafut)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bwj_Latn (Láá Láá Bwamu)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Utilde</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">yba_Latn (Yala)</td>
<td align="left">Shaper didn't attach uni0304.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kst_Latn (Winyé)</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1EBC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EBD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0269</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">pkb_Latn (Pokomo)</td>
<td align="left">Shaper didn't attach uni032F to d</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni032F to t</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni032F.case to D</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni032F.case to T</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bsq_Latn (Bassa (Latin))</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to Utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bas_Latn (Basaa)</td>
<td align="left">Shaper didn't attach uni0304.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC7 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">din_Latn (Dinka)</td>
<td align="left">Shaper didn't attach uni0308.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni0190</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tmh_Latn (Tamashek)</td>
<td align="left">Shaper didn't attach uni030C to uni0237</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to J</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gej_Latn (Gen)</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lee_Latn (Lyélé)</td>
<td align="left">Shaper didn't attach gravecomb to utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to otilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1EBC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to Otilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Otilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni1EBC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EBD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni1EBD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to otilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1EBC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to Utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EBD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lgg_Latn (Lugbara)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0197</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bot_Latn (Bongo)</td>
<td align="left">Shaper didn't attach uni0331 to edieresis</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to Idieresis</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to Edieresis</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to Udieresis</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to idieresis</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to udieresis</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nus_Latn (Nuer)</td>
<td align="left">Shaper didn't attach uni0331.case to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni0331.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni0331</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to a</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kpe_Latn (Kpelle)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">vut_Latn (Vute)</td>
<td align="left">Shaper didn't attach uni0327 to agrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to iacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to icircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Ocircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0229</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0228</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Acircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0229</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to oacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Ucircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to ugrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0229</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to acircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Ugrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to ucircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0228</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to ocircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Igrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Uacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0228</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Oacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Ograve</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Iacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to ograve</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Agrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to igrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Icircumflex</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gvl_Latn (Gulay)</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0197</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sbd_Latn (Southern Samo)</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">jgo_Latn (Ngomba)</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to n</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to N</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nnh_Latn (Ngiemboon)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uniA78D</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0265</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0275</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0275</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0265</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uniA78D</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uniA78D</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0265</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0275</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uniA78D</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni019F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0265</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni019F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni019F</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ddn_Latn (Dendi)</td>
<td align="left">Shaper didn't attach uni0304.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tbz_Latn (Ditammari)</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
<td align="left">Some base glyphs were missing: Ɪ, Ɪ̃</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni026A</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nmz_Latn (Nawdm)</td>
<td align="left">Shaper didn't attach uni0308.case to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to G</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to g</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to N</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to n</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tvu_Latn (Tunen)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">buc_Latn (Bushi)</td>
<td align="left">Shaper didn't attach uni0308.case to N</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to n</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dno_Latn (Ndrulo)</td>
<td align="left">Shaper didn't attach uni0302 to r</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to R</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to R</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to s</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to S</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to r</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">etu_Latn (Ejagham)</td>
<td align="left">Shaper didn't attach uni0302.case to N</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to n</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0197</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to aogonek</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Aogonek</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0328</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0328</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to iogonek.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Iogonek</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0328 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uogonek</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Uogonek</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">daa_Latn (Dangaléat)</td>
<td align="left">Shaper didn't attach uni0330 to n</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kss_Latn (Southern Kisi)</td>
<td align="left">Shaper didn't attach uni030D to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030D to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC4 to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to U</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dya_Latn (Dyan)</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mey_Latn (Hassaniyya)</td>
<td align="left">Some base glyphs were missing: Ŧ, ŧ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lnl_Latn (South Central Banda)</td>
<td align="left">Shaper didn't attach uni0308 to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gur_Latn (Frafra)</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ksp_Latn (Kabba)</td>
<td align="left">Shaper didn't attach uni0302.case to N</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to n</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0308.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bqp_Latn (Bisã)</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bom_Latn (Berom)</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bum_Latn (Bulu)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">neb_Latn (Toura)</td>
<td align="left">Shaper didn't attach gravecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to O</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mls_Latn (Masalit)</td>
<td align="left">Shaper didn't attach uni0330 to n</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">pug_Latn (Phuie)</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to otilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1EBC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Otilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EBD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1EBC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EBD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ekp_Latn (Ekpeye)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni1ECB.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni1EB9</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1EB9</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1EE4</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1ECB.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni1ECB.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni1EE4</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni1EE4</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni1EB9</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni1ECB.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni1EE4</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">loq_Latn (Lobala)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mdt_Latn (Mbere)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0324 to w</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0324.case to W</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bud_Latn (Ntcham)</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to b</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to l</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to L</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to b</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ksf_Latn (Bafia)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dnj_Latn (Dan)</td>
<td align="left">Some base glyphs were missing: ɤ, ɤ̀, ɤ́, ɤ̂, ɤ̄, ɤ̋, ɤ̏, Ɤ, Ɤ̀, Ɤ́, Ɤ̂, Ɤ̄, Ɤ̋, Ɤ̏</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to ae</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F to uni028C</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to uni026F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0245</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B.case to AE</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni028C</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F.case to OE</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to oe</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to OE</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni019C</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni019C</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to AE</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B.case to OE</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B.case to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F to ae</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F.case to AE</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to ae</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to AE</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to ae</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to ae</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F.case to uni0245</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni028C</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0245</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni028C</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028C</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0245</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to uni028C</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B.case to uni0245</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0245</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B.case to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030F.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030B.case to I</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ijs_Latn (Ijo, Southeast)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1EE4</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1ECA</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EE5</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECB.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EB9</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fan_Latn (Fang)</td>
<td align="left">Shaper didn't attach uni0324 to w</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0324.case to W</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">etx_Latn (Iten)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to O</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mge_Latn (Mango)</td>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to agrave</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0330.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1E2C</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1E1B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1E74</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1E75</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0330.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to i</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to n</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1E1A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1E2D.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to amacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1E1B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1E1A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni1E1B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni1E1A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0330</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0330.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to l</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to L</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to n</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to N</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to oacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to ograve</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0330 to omacron</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni1E75</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni1E74</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni1E75</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni1E74</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mcp_Latn (Makaa)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni01D2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Oacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni01D1</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Ocircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to oacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to ocircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">saf_Latn (Safaliba)</td>
<td align="left">Shaper didn't attach uni0331.case to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to o</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">swb_Latn (Maore Comorian, Latin)</td>
<td align="left">Shaper didn't attach uni0304.case to V</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to v</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to v</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331.case to V</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dua_Latn (Duala)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
<td align="left">Shaper didn't attach tildecomb.case to Udieresis</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to udieresis</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to odieresis</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to idieresis</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to adieresis</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Odieresis</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to Adieresis</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to adieresis</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to Odieresis</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to Edieresis</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Edieresis</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to odieresis</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to edieresis</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to edieresis</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to Idieresis</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Adieresis</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">yav_Latn (Yangben)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gov_Latn (Goo)</td>
<td align="left">Some base glyphs were missing: ɤ, ɤ̀, ɤ́, ɤ̂, Ɤ, Ɤ̀, Ɤ́, Ɤ̂</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to N</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni028C</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">yo_Latn_BJ (Yoruba, Benin)</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">xsm_Latn_BF (Burkinabè Kasem)</td>
<td align="left">Shaper didn't attach acutecomb.case to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0269</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bax_Latn (Bamun (Latin))</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni018F</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0244</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">pnz_Latn (Pana, Central African Republic)</td>
<td align="left">Shaper didn't attach uni0327.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to icircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Acircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0229</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0229</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to acircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Uacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0228</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Oacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Iacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0327</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to aacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to iacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0327.case</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Ocircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to oacute</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Ucircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to ucircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0228</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to ocircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0327.case to Icircumflex</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">blo_Latn (Anii)</td>
<td align="left">Shaper didn't attach uni0302.case to uni01B1</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni01B1</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni028A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni028A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni01DD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni01B1</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni018E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0269</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">btt_Latn (Bete-Bendi)</td>
<td align="left">Shaper didn't attach uni1DC5 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to dotlessi</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to O</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to a</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to u</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to e</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to U</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to E</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to o</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC6 to I</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni1DC5 to I</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kib_Latn (Koalib)</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">giz_Latn (Southern Giziga)</td>
<td align="left">Some base glyphs were missing: ˀ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gna_Latn (Kaansa)</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to Utilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to Itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni01B2</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to Atilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0196</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to itilde</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0269</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">asg_Latn (Cishingini)</td>
<td align="left">Shaper didn't attach uni0331.case to A</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0331 to a</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dgi_Latn (Northern Dagara)</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach tildecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ttq_Latn (Tawallammat Tamajaq)</td>
<td align="left">Shaper didn't attach uni030C to uni0237</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to J</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">pcm_Latn (Nigerian Pidgin)</td>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1ECC</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb.case to uni1EB8</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni1EB9</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tik_Latn (Tikar)</td>
<td align="left">Shaper didn't attach gravecomb to m</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to AE</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to ae</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to ae</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to AE</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to AE</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to ae</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to M</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">agq_Latn (Aghem)</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0190</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0254</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0244</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni0268.dotless</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0186</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni0289</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni030C.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach gravecomb.case to uni0197</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bm_Latn (Bambara)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dyu_Latn (Dyula)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ig_Latn (Igbo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_PriAfrican glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lg_Latn (Ganda)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bkm_Latn (Kom)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tnr_Latn (Ménik)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gde_Latn (Gude)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bsc_Latn (Bassari)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ee_Latn (Ewe)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ken_Latn (Kenyang)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">muy_Latn (Muyang)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kao_Latn (Xaasongaxango)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dur_Latn (Dii)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kqs_Latn (Kissi, Northern)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">pil_Latn (Yom)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kyf_Latn (Kouya)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bbj_Latn (Ghomala)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fod_Latn (Foodo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sxw_Latn (Saxwe Gbe)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">udu_Latn (Uduk)</td>
<td align="left">Some auxiliary glyphs were missing: T͟H, t͟h</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dop_Latn (Lukpa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tcd_Latn (Tafi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">byv_Latn (Medumba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kqp_Latn (Kimré)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ggn_Latn (Eastern Gurung, Latin)</td>
<td align="left">No exemplar glyphs were defined for language Eastern Gurung, Latin</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">spp_Latn (Sénoufo, Supyire)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lia_Latn (Limba, West-Central)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mbu_Latn (Mbula-Bwazza)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">csk_Latn (Jola-Kasa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sav_Latn (Saafi-Saafi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">soy_Latn (Miyobe)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mnf_Latn (Mundani)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mwk_Latn (Kita Maninkakan)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dyu_Latn (Dyula)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lam_Latn (Lamba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mfv_Latn (Mandjak)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">twq_Latn (Tasawaq)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sld_Latn (Sissala)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ade_Latn (Adele)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">avu_Latn (Avokaya)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ife_Latn (Ifè)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ewo_Latn (Ewondo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kbp_Latn (Kabiyé)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">hna_Latn (Mina)</td>
<td align="left">No exemplar glyphs were defined for language Mina</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">emk_Latn (Maninkakan, Eastern)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">yam_Latn (Yamba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">yas_Latn (Nugunu)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bex_Latn (Jur Modo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">keu_Latn (Akebu)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">aeb_Latn (Tunisian Darija)</td>
<td align="left">Some auxiliary glyphs were missing: Ŧ, ŧ</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ny_Latn (Nyanja)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gux_Latn (Gourmanchéma)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ikx_Latn (Ik)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">srr_Latn (Serer)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kpo_Latn (Ikposo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bfa_Latn (Bari)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bzx_Latn (Bozo, Hainyaxo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">wwa_Latn (Waama)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ntr_Latn (Delo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bze_Latn (Jenaama Bozo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">myk_Latn (Mamara Senoufo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gjn_Latn (Gonja)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ig_Latn (Igbo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">teo_Latn (Teso)</td>
<td align="left">Some auxiliary glyphs were missing: ᵃ, ᵉ, ᵋ, ᵒ, ᵓ, ᶤ, ᶶ, ⁱ</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ndz_Latn (Ndogo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">god_Latn (Godié)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bav_Latn (Vengo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kkj_Latn (Kako)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">meq_Latn (Merey)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mgd_Latn (Moru)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mgo_Latn (Metaʼ)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">biv_Latn (Birifor, Southern)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lun_Latn (Lunda)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mor_Latn (Moro)</td>
<td align="left">Some auxiliary glyphs were missing: Ꟈ, ꟈ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nnw_Latn (Southern Nuni)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">eto_Latn (Eton, Cameroon)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fub_Latn (Fulfulde, Adamawa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">adj_Latn (Adioukrou)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ebo_Latn (Teke-Ebo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fvr_Latn (Fur)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bbo_Latn (Northern Bobo Madaré)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">aks_Latn (Akeselem)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gmm_Latn (Gbaya-Mbodomo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">boz_Latn (Tiéyaxo Bozo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">cme_Latn (Cerma)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lmp_Latn (Limbum)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bss_Latn (Akoose)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ses_Latn (Koyraboro Senni)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dtm_Latn (Tomo Kan Dogon)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">taq_Latn (Tamasheq (Latin))</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bzw_Latn (Basa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mcu_Latn (Mambila, Cameroon)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">knp_Latn (Kwanja)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kus_Latn (Kusaal)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ajg_Latn (Aja)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tuq_Latn (Tedaga)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sok_Latn (Sokoro)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">krs_Latn (Gbaya, Sudan)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">vai_Latn (Vai (Latin))</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ybb_Latn (Yemba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kyq_Latn (Kenga)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">vag_Latn (Vagla)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mzw_Latn (Deg)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sig_Latn (Paasaal)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dyo_Latn (Jola-Fonyi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nmg_Latn (Kwasio)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ozm_Latn (Koonzime)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mas_Latn (Masai)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lem_Latn (Nomaande)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kdh_Latn (Tem)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">cae_Latn (Lehar)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mmu_Latn (Mmaala)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nza_Latn (Tigon Mbembe)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ncu_Latn (Chumburung)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bjt_Latn (Balanta-Ganja)</td>
<td align="left">Some auxiliary glyphs were missing: Ŧ, ŧ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">rub_Latn (Gungu)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nko_Latn (Nkonya)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mev_Latn (Mano)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kzr_Latn (Karang)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dow_Latn (Doyayo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">xrb_Latn (Karaboro, Eastern)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">xsm_Latn (Kasem)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gnd_Latn (Zulgo-Gemzek)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kmy_Latn (Koma)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dip_Latn (Dinka, Northeastern)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ahs_Latn (Ashe)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fmp_Latn (Fe’fe’)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nuv_Latn (Nuni, Northern)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nfu_Latn (Mfumte)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kia_Latn (Kim)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kye_Latn (Krache)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tpm_Latn (Tampulma)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gaa_Latn (Ga)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for uni01A9</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for uni01B7</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">knf_Latn (Mankanya)</td>
<td align="left">Some auxiliary glyphs were missing: Ŧ, ŧ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">acd_Latn (Gikyode)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ffm_Latn (Maasina Fulfulde)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">xon_Latn (Konkomba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bqj_Latn (Bandial)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">syi_Latn (Seki)</td>
<td align="left">No exemplar glyphs were defined for language Seki</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sil_Latn (Sisaala, Tumulung)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nyb_Latn (Nyangbo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fuq_Latn (Central-Eastern Niger Fulfulde)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kvf_Latn (Kabalai)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bqv_Latn (Koro Wachi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mcn_Latn (Masana)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lok_Latn (Loko)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">cch_Latn (Atsam)</td>
<td align="left">No exemplar glyphs were defined for language Atsam</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">moa_Latn (Mwan)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">azo_Latn (Awing)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bib_Latn (Bissa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bfd_Latn (Bafut)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dje_Latn (Zarma)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nhb_Latn (Beng)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nym_Latn (Nyamwezi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">xwe_Latn (Gbe, Xwela)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">pbi_Latn (Parkwa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bas_Latn (Basaa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">naw_Latn (Nawuri)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">cou_Latn (Wamey)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">xed_Latn (Hdi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gej_Latn (Gen)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bza_Latn (Bandi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">log_Latn (Logo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lee_Latn (Lyélé)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">idu_Latn (Idoma)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lgg_Latn (Lugbara)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nus_Latn (Nuer)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bcw_Latn (Bana)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">avn_Latn (Avatime)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">laj_Latn (Lango, Uganda)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fuh_Latn (Fulfulde, Western Niger)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">maw_Latn (Mampruli)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nku_Latn (Kulango, Bouna)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">vut_Latn (Vute)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gud_Latn (Dida, Yocoboué)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">wci_Latn (Gbe, Waci)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sbd_Latn (Southern Samo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sef_Latn (Cebaara Senoufo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">jgo_Latn (Ngomba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nnh_Latn (Ngiemboon)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ddn_Latn (Dendi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lg_Latn (Ganda)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mfi_Latn (Wandala)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nmz_Latn (Nawdm)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lig_Latn (Ligbi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ted_Latn (Krumen, Tepo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tvu_Latn (Tunen)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dno_Latn (Ndrulo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dts_Latn (Dogon, Toro So)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">etu_Latn (Ejagham)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kpz_Latn (Sapiny)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">daa_Latn (Dangaléat)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">khq_Latn (Koyra Chiini)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">wan_Latn (Wan)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mdj_Latn (Mangbetu)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kss_Latn (Southern Kisi)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">yat_Latn (Yambeta)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bim_Latn (Bimoba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ahl_Latn (Igo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">agc_Latn (Agatu)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kfo_Latn (Koro)</td>
<td align="left">No exemplar glyphs were defined for language Koro</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bsp_Latn (Baga Sitemu)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gur_Latn (Frafra)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bm_Latn (Bambara)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fue_Latn (Fulfulde, Borgu)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">snf_Latn (Noon)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ktj_Latn (Krumen, Plapo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dyi_Latn (Sénoufo, Djimini)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bum_Latn (Bulu)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ach_Latn (Acoli)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">neb_Latn (Toura)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ndv_Latn (Ndut)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">wo_Latn (Wolof)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mgc_Latn (Morokodo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dag_Latn (Dagbani)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mls_Latn (Masalit)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nhu_Latn (Noone)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">pug_Latn (Phuie)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tod_Latn (Toma)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for uni028B</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for uni01B2</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">loq_Latn (Lobala)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">shz_Latn (Syenara Senoufo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mdt_Latn (Mbere)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">cko_Latn (Anufo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bud_Latn (Ntcham)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">anv_Latn (Denya)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ksf_Latn (Bafia)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lns_Latn (Lamnso’)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dnj_Latn (Dan)</td>
<td align="left">Some auxiliary glyphs were missing: ɤ, ɤ̀, ɤ́, ɤ̂, ɤ̄, ɤ̋, ɤ̏, Ɤ, Ɤ̀, Ɤ́, Ɤ̂, Ɤ̄, Ɤ̋, Ɤ̏</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">No variant glyphs were found for uni0181</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mgy_Latn (Mbunga)</td>
<td align="left">No exemplar glyphs were defined for language Mbunga</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mfd_Latn (Mendankwe-Nkwen)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fan_Latn (Fang)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mcp_Latn (Makaa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">saf_Latn (Safaliba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">las_Latn (Lama, Togo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mfq_Latn (Moba)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dua_Latn (Duala)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mbo_Latn (Mbo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">yav_Latn (Yangben)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gov_Latn (Goo)</td>
<td align="left">Some auxiliary glyphs were missing: ɤ, ɤ̀, ɤ́, ɤ̂, Ɤ, Ɤ̀, Ɤ́, Ɤ̂</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">hag_Latn (Hanga)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mua_Latn (Mundang)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nfr_Latn (Nafaanra)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mnk_Latn (Mandinka)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">bax_Latn (Bamun (Latin))</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">pnz_Latn (Pana, Central African Republic)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">blo_Latn (Anii)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fuc_Latn (Pulaar)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fuf_Latn (Pular)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">amo_Latn (Amo)</td>
<td align="left">No exemplar glyphs were defined for language Amo</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">kib_Latn (Koalib)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">giz_Latn (Southern Giziga)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gna_Latn (Kaansa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dzg_Latn (Dazaga)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">toq_Latn (Toposa)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dgi_Latn (Northern Dagara)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ekm_Latn (Elip)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ttq_Latn (Tawallammat Tamajaq)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tem_Latn (Timne)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tik_Latn (Tikar)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mur_Latn (Murle)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">xuo_Latn (Kuo)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">gng_Latn (Ngangam)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_African glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">agq_Latn (Aghem)</td>
<td align="left">No variant glyphs were found for Eng</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set.</p>
 [code: missing]



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
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: y	Contours detected: 2	Expected: 1

- Glyph name: AE	Contours detected: 3	Expected: 2

- Glyph name: yacute	Contours detected: 3	Expected: 2

- Glyph name: ydieresis	Contours detected: 4	Expected: 3

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: lslash	Contours detected: 2	Expected: 1

- Glyph name: OE	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

- Glyph name: uni019A	Contours detected: 2	Expected: 1

- Glyph name: ohorn	Contours detected: 3	Expected: 2

- Glyph name: Uhorn	Contours detected: 2	Expected: 1

- Glyph name: uhorn	Contours detected: 2	Expected: 1

- Glyph name: uni01B4	Contours detected: 2	Expected: 1

- Glyph name: uni01E2	Contours detected: 4	Expected: 3

- Glyph name: uni01E5	Contours detected: 3	Expected: 2

- Glyph name: uni01EA	Contours detected: 3	Expected: 2

- Glyph name: uni01EB	Contours detected: 3	Expected: 2

- Glyph name: uni01EC	Contours detected: 4	Expected: 3

- Glyph name: uni01ED	Contours detected: 4	Expected: 3

- Glyph name: uni01F5	Contours detected: 4	Expected: 3

- Glyph name: uni0228	Contours detected: 2	Expected: 1

- Glyph name: uni0229	Contours detected: 3	Expected: 2

- Glyph name: uni0233	Contours detected: 3	Expected: 2

- Glyph name: uni023A	Contours detected: 2	Expected: 3

- Glyph name: uni0246	Contours detected: 2	Expected: 3

- Glyph name: uni024E	Contours detected: 1	Expected: 2

- Glyph name: uni024F	Contours detected: 3	Expected: 2

- Glyph name: uni1E08	Contours detected: 3	Expected: 2

- Glyph name: uni1E09	Contours detected: 3	Expected: 2

- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

- Glyph name: uni1EED	Contours detected: 3	Expected: 2

- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

- Glyph name: ygrave	Contours detected: 3	Expected: 2

- Glyph name: uni1EF5	Contours detected: 3	Expected: 2

- Glyph name: uni1EF7	Contours detected: 3	Expected: 2

- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

- Glyph name: uni25CC	Contours detected: 20	Expected: 16 or 12

- Glyph name: AE	Contours detected: 3	Expected: 2

- Glyph name: OE	Contours detected: 3	Expected: 2

- Glyph name: Uhorn	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: lslash	Contours detected: 2	Expected: 1

- Glyph name: ohorn	Contours detected: 3	Expected: 2

- Glyph name: uhorn	Contours detected: 2	Expected: 1

- Glyph name: uni019A	Contours detected: 2	Expected: 1

- Glyph name: uni01B4	Contours detected: 2	Expected: 1

- Glyph name: uni01E2	Contours detected: 4	Expected: 3

- Glyph name: uni01E5	Contours detected: 3	Expected: 2

- Glyph name: uni01EC	Contours detected: 4	Expected: 3

- Glyph name: uni01ED	Contours detected: 4	Expected: 3

- Glyph name: uni0228	Contours detected: 2	Expected: 1

- Glyph name: uni0229	Contours detected: 3	Expected: 2

- Glyph name: uni0233	Contours detected: 3	Expected: 2

- Glyph name: uni023A	Contours detected: 2	Expected: 3

- Glyph name: uni0246	Contours detected: 2	Expected: 3

- Glyph name: uni024E	Contours detected: 1	Expected: 2

- Glyph name: uni024F	Contours detected: 3	Expected: 2

- Glyph name: uni1E08	Contours detected: 3	Expected: 2

- Glyph name: uni1E09	Contours detected: 3	Expected: 2

- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

- Glyph name: uni1EED	Contours detected: 3	Expected: 2

- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

- Glyph name: uni1EF5	Contours detected: 3	Expected: 2

- Glyph name: uni1EF7	Contours detected: 3	Expected: 2

- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

- Glyph name: uni25CC	Contours detected: 20	Expected: 16 or 12

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: y	Contours detected: 2	Expected: 1

- Glyph name: yacute	Contours detected: 3	Expected: 2

- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

- Glyph name: ydieresis	Contours detected: 4	Expected: 3

- Glyph name: ygrave	Contours detected: 3	Expected: 2
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 556 among a set of 2 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 554:
plus</p>
<p>Width = 515:
less</p>
<p>Width = 521:
greater</p>
<p>Width = 565:
logicalnot</p>
<p>Width = 579:
plusminus</p>
<p>Width = 541:
multiply</p>
<p>Width = 548:
divide, minus</p>
<p>Width = 546:
approxequal</p>
<p>Width = 502:
lessequal</p>
<p>Width = 506:
greaterequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- E.ss01

- Eacute.ss01

- Ecaron.ss01

- Ecircumflex.ss01

- Edieresis.ss01

- Edotaccent.ss01

- Egrave.ss01

- Emacron.ss01

- Eogonek.ss01

- M_gravecomb

- NumberStep2

- a.alt2

- a.alt5

- acutecomb.narrow

- dotbelowcomb.case.001

- gravecomb.narrow

- hookabovecomb.narrow

- m_gravecomb

- tildecomb.narrow

- uni004D0304

- uni004E0304

- uni006D0304

- uni006E0304

- uni0204.ss01

- uni0206.ss01

- uni0228.ss01

- uni0246.ss01

- uni0302.narrow

- uni0306.narrow

- uni031B.narrow

- uni1E14.ss01

- uni1E16.ss01

- uni1E18.ss01

- uni1E1A.ss01

- uni1E1C.ss01

- uni1EB8.ss01

- uni1EBA.ss01

- uni1EBC.ss01

- uni1EBE.ss01

- uni1EC0.ss01

- uni1EC2.ss01

- uni1EC4.ss01

- uni1EC6.ss01
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
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
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, math, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: coptic, hebrew, syriac, malayalam, canadian-aboriginal, tifinagh, todhri, tai-le, duployan, math, old-permic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+030D COMBINING VERTICAL LINE ABOVE: try adding sunuwar</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0310 COMBINING CANDRABINDU: try adding one of: sunuwar, math</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: todhri, coptic</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0313 COMBINING COMMA ABOVE: try adding one of: todhri, old-permic</li>
<li>U+031B COMBINING HORN: not included in any glyphset definition</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: cherokee, syriac, duployan</li>
<li>U+0325 COMBINING RING BELOW: try adding syriac</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding one of: sunuwar, syriac</li>
<li>U+032E COMBINING BREVE BELOW: try adding syriac</li>
<li>U+032F COMBINING INVERTED BREVE BELOW: try adding math</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, syriac, math</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: gothic, cherokee, sunuwar, syriac, tifinagh, caucasian-albanian, thai</li>
<li>U+0332 COMBINING LOW LINE: try adding math</li>
<li>U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition</li>
<li>U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition</li>
<li>U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition</li>
<li>U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+207F SUPERSCRIPT LATIN SMALL LETTER N: try adding math</li>
<li>U+2080 SUBSCRIPT ZERO: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2085 SUBSCRIPT FIVE: try adding math</li>
<li>U+2086 SUBSCRIPT SIX: try adding math</li>
<li>U+2087 SUBSCRIPT SEVEN: try adding math</li>
<li>U+2088 SUBSCRIPT EIGHT: try adding math</li>
<li>U+2089 SUBSCRIPT NINE: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols</li>
<li>U+2184 LATIN SMALL LETTER REVERSED C: not included in any glyphset definition</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: warang-citi, bhaiksuki, tamil, tagbanwa, kannada, adlam, tagalog, hebrew, khudawadi, math, lepcha, thaana, manichaean, bengali, mandaic, khojki, caucasian-albanian, tai-le, tirhuta, khmer, tibetan, modi, phags-pa, duployan, old-permic, hanunoo, pahawh-hmong, syloti-nagri, kayah-li, nko, tai-tham, chakma, saurashtra, coptic, gurmukhi, buginese, telugu, yi, zanabazar-square, thai, limbu, cham, armenian, tifinagh, miao, meetei-mayek, dogra, gunjala-gondi, new-tai-lue, sundanese, mahajani, marchen, wancho, siddham, gujarati, javanese, takri, devanagari, kharoshthi, hanifi-rohingya, grantha, soyombo, masaram-gondi, newa, batak, kaithi, balinese, malayalam, mongolian, syriac, sinhala, tai-viet, mende-kikakui, osage, psalter-pahlavi, sogdian, rejang, ahom, canadian-aboriginal, elbasan, bassa-vah, buhid, myanmar, symbols, music, oriya, sharada, brahmi, lao</li>
<li>U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>ethiopic</code>, <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ɉ̀ ɉ́ ɉ̂ ɉ̃ ɉ̄ ɉ̆ ɉ̇ ɉ̈ ɉ̉ ɉ̊ ɉ̋ ɉ̌ ɉ̍ ɉ̏ ɉ̐ ɉ̑ ɉ̒ ɉ̓ ɉ᷄ ɉ᷅</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Zapotec (Latn, 490,000 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Nateni (Latn, 100,000 speakers), Ma’di (Latn, 584,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Ejagham (Latn, 120,000 speakers), Kaska (Latn, 125 speakers), Koonzime (Latn, 40,000 speakers), Mundani (Latn, 34,000 speakers), Mango (Latn, 77,000 speakers), Han (Latn, 6 speakers), Lugbara (Latn, 2,200,000 speakers), Basaa (Latn, 332,940 speakers), Aghem (Latn, 38,843 speakers), Sar (Latn, 500,000 speakers), Southern Kisi (Latn, 360,000 speakers), Dan (Latn, 1,099,244 speakers), Avokaya (Latn, 100,000 speakers), Yala (Latn, 200,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Dii (Latn, 71,000 speakers), Cicipu (Latn, 44,000 speakers), Kom (Latn, 360,685 speakers), Makaa (Latn, 221,000 speakers), Heiltsuk (Latn, 300 speakers), Nzakara (Latn, 50,000 speakers), Mfumte (Latn, 79,000 speakers), Gulay (Latn, 250,478 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Vute (Latn, 21,000 speakers), South Central Banda (Latn, 244,000 speakers), Ebira (Latn, 2,200,000 speakers), Navajo (Latn, 166,319 speakers), Igbo (Latn, 27,823,640 speakers), Dutch (Latn, 31,709,104 speakers), Fur (Latn, 1,230,163 speakers), Bafut (Latn, 158,146 speakers), Ekpeye (Latn, 226,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Eng (U+014A): B&lt;&lt;392.5,483.0&gt;-&lt;431.0,369.0&gt;-&lt;454.0,212.0&gt;&gt;/L&lt;&lt;454.0,212.0&gt;--&lt;458.0,292.0&gt;&gt; = 11.196769743469542

* h (U+0068): B&lt;&lt;255.0,432.0&gt;-&lt;244.0,386.0&gt;-&lt;233.0,346.0&gt;&gt;/B&lt;&lt;233.0,346.0&gt;-&lt;252.0,383.0&gt;-&lt;283.5,419.5&gt;&gt; = 11.804859836651074

* hbar (U+0127): B&lt;&lt;254.5,418.5&gt;-&lt;245.0,379.0&gt;-&lt;237.0,346.0&gt;&gt;/B&lt;&lt;237.0,346.0&gt;-&lt;256.0,383.0&gt;-&lt;287.5,419.5&gt;&gt; = 13.554116225585668

* hcircumflex (U+0125): B&lt;&lt;255.0,432.0&gt;-&lt;244.0,386.0&gt;-&lt;233.0,346.0&gt;&gt;/B&lt;&lt;233.0,346.0&gt;-&lt;252.0,383.0&gt;-&lt;283.5,419.5&gt;&gt; = 11.804859836651074

* ordfeminine (U+00AA): B&lt;&lt;226.0,293.5&gt;-&lt;226.0,297.0&gt;-&lt;227.0,301.0&gt;&gt;/B&lt;&lt;227.0,301.0&gt;-&lt;206.0,258.0&gt;-&lt;178.5,237.5&gt;&gt; = 11.993348723586983

* uni021F (U+021F): B&lt;&lt;255.0,432.0&gt;-&lt;244.0,386.0&gt;-&lt;233.0,346.0&gt;&gt;/B&lt;&lt;233.0,346.0&gt;-&lt;252.0,383.0&gt;-&lt;283.5,419.5&gt;&gt; = 11.804859836651074

* uni0265 (U+0265): B&lt;&lt;321.5,68.0&gt;-&lt;333.0,114.0&gt;-&lt;343.0,154.0&gt;&gt;/B&lt;&lt;343.0,154.0&gt;-&lt;324.0,117.0&gt;-&lt;292.5,80.5&gt;&gt; = 13.144867617550734

* uni02B0 (U+02B0): B&lt;&lt;207.0,529.0&gt;-&lt;198.0,496.0&gt;-&lt;189.0,467.0&gt;&gt;/B&lt;&lt;189.0,467.0&gt;-&lt;205.0,494.0&gt;-&lt;232.5,520.5&gt;&gt; = 13.409208558112896

* uni1E23 (U+1E23): B&lt;&lt;255.0,432.0&gt;-&lt;244.0,386.0&gt;-&lt;233.0,346.0&gt;&gt;/B&lt;&lt;233.0,346.0&gt;-&lt;252.0,383.0&gt;-&lt;283.5,419.5&gt;&gt; = 11.804859836651074

* uni1E25 (U+1E25): B&lt;&lt;255.0,432.0&gt;-&lt;244.0,386.0&gt;-&lt;233.0,346.0&gt;&gt;/B&lt;&lt;233.0,346.0&gt;-&lt;252.0,383.0&gt;-&lt;283.5,419.5&gt;&gt; = 11.804859836651074

* uni1E27 (U+1E27): B&lt;&lt;255.0,432.0&gt;-&lt;244.0,386.0&gt;-&lt;233.0,346.0&gt;&gt;/B&lt;&lt;233.0,346.0&gt;-&lt;252.0,383.0&gt;-&lt;283.5,419.5&gt;&gt; = 11.804859836651074

* uni1E29 (U+1E29): B&lt;&lt;255.0,432.0&gt;-&lt;244.0,386.0&gt;-&lt;233.0,346.0&gt;&gt;/B&lt;&lt;233.0,346.0&gt;-&lt;252.0,383.0&gt;-&lt;283.5,419.5&gt;&gt; = 11.804859836651074

* uni1E2B (U+1E2B): B&lt;&lt;255.0,432.0&gt;-&lt;244.0,386.0&gt;-&lt;233.0,346.0&gt;&gt;/B&lt;&lt;233.0,346.0&gt;-&lt;252.0,383.0&gt;-&lt;283.5,419.5&gt;&gt; = 11.804859836651074

* uniA727 (U+A727): B&lt;&lt;255.0,432.0&gt;-&lt;244.0,386.0&gt;-&lt;233.0,346.0&gt;&gt;/B&lt;&lt;233.0,346.0&gt;-&lt;252.0,383.0&gt;-&lt;283.5,419.5&gt;&gt; = 11.804859836651074
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* summation (U+2211): L&lt;&lt;412.0,564.0&gt;--&lt;247.0,563.0&gt;&gt;

* uni01A9 (U+01A9): L&lt;&lt;408.0,574.0&gt;--&lt;230.0,573.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



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
    <summary>⚠️ <b>WARN</b> Ensure Stylistic Sets have description. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gsub.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The stylistic set ss01 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss02 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss03 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss04 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss05 lacks a description string on the 'name' table.</p>
 [code: missing-description]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 5 | 11 | 116 | 7 | 112 | 0 | 
| 0% | 0% | 2% | 4% | 46% | 3% | 45% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
