---
title: "≔ Logical Symbology ⊧"
description: "This page serves as a convenient Logical Symbology reference template, index, or lexical guide."
draft: false
---

<style type="text/css">
.container { max-width:100%; }
.tableWrapper {
  margin-inline: auto;
}
table {
  width: 100%;
  border-collapse: collapse;
}
caption, th, td {
  padding: 0.75em !important;
}
caption, th { text-align: left; }
caption {
  background: #002B4D;
  color: #705F15;
  font-size: 1.5rem;
  font-weight :bold;
  border-radius: 10px 10px 0 0;
}
th { background: rgba(112,95,21,0.5); }
tr { background: rgba(0,43,77,0.5); }
tr:nth-of-type(2n) { background: rgba(0,43,77,0.25); }
tr:nth-last-of-type(2) > td:first-of-type { border-bottom-left-radius: 10px; }
tr:nth-last-of-type(2) > td:last-of-type {border-bottom-right-radius: 10px;}
tr:last-of-type { display:none; } /* ㊢ TEMPLATE <tr> */
@media (max-width: 650px) {
  th { display: none; }
  td { display: block; }
  td:first-of-type::before { content: "📌 " attr(data-cell);display:block;color:#705F15; }
  td:not(:first-of-type)::before { content: "📍 " attr(data-cell);display:block;color:#705F15; }
}
</style>

> “The true function of logic… as applied to matters of experience… is analytic rather than constructive; taken _a priori_, it shows the possibility of hitherto unsuspected alternatives more often than the impossibility of alternatives which seemed _prima facie_ possible. Thus, while it liberates imagination as to what the world may be, it refuses to legislate as to what the world is…”
> 
> － Bertrand Russell

<main>
  <div class="tableWrapper">
    <table>
      <caption>λογικά σύμβολα ≍ Logical Symbology Lexicon</caption>
      <tr>
        <th>SYMBOL</th>
        <th>Logical<br>CONCEPT</th>
        <th>should be<br>“read as…”</th>
        <th>CATEGORY</th>
        <th>Explanation</th>
        <th>Examples</th>
        <th>Unicode<br>hexadecimal</th>
        <th>HTML<br>decimal</th>
        <th>HTML<br>entity</th>
        <th>LaTeX<br>symbol</th>
      </tr>
      <tr>
        <td data-cell="SYMBOL">⇒<br>→<br>⊃</td>
        <td data-cell="CONCEPT">material implication</td>
        <td data-cell="“read as…”">“implies”<br>if … then</td>
        <td data-cell="CATEGORY">propositional logic,<br>Heyting algebra</td>
        <td data-cell="Explanation">𝚨 ⇒ 𝚩 is false when 𝚨 is true and 𝚩 is false but true otherwise</td>
        <td data-cell="Examples">𝚾＝2 ⇒ 𝚾²＝4 is true,<br>but 𝚾²＝4 ⇒ 𝚾＝2 is generally false<br>(since 𝚾 could be -2)</td>
        <td data-cell="Unicode">U+21D2<br>U+2192<br>U+2283</td>
        <td data-cell="HTML decimal">&﹟8658;<br>&﹟8594;<br>&﹟8835;</td>
        <td data-cell="HTML entity">﹠rArr;<br>﹠rarr;<br>﹠sup;</td>
        <td data-cell="LaTeX">⇒\Rightarrow<br>⇒\implies<br>→\to<br>⊃\supset</td>
      </tr>
      <tr>
        <td data-cell="SYMBOL">⇔<br>≡<br>↔</td>
        <td data-cell="CONCEPT">material equivalence</td>
        <td data-cell="“read as…”">if＆only if<br>iff<br>same meaning</td>
        <td data-cell="CATEGORY">propositional logic</td>
        <td data-cell="Explanation">𝚨 ⇔ 𝚩 is true only if both 𝚨＆𝚩 are false, or both 𝚨＆𝚩 are true</td>
        <td data-cell="Examples">𝚾＋5＝𝚼＋2 ⇔ 𝚾＋3＝𝚼</td>
        <td data-cell="Unicode">U+21D4<br>U+2261<br>U+2194</td>
        <td data-cell="HTML decimal">&﹟8660;<br>&﹟8801;<br>&﹟8596;</td>
        <td data-cell="HTML entity">﹠hArr;<br>﹠equiv;<br>﹠LeftRightArrow;</td>
        <td data-cell="LaTeX">⇔\Leftrightarrow<br>≡\equiv<br>↔\iff</td>
      </tr>
      <tr>
        <td data-cell="SYMBOL">¬<br>∼<br>!</td>
        <td data-cell="CONCEPT">negation</td>
        <td data-cell="“read as…”">“not”</td>
        <td data-cell="CATEGORY">propositional logic</td>
        <td data-cell="Explanation">¬𝚨 is true if＆only if 𝚨 is false</td>
        <td data-cell="Examples">¬(¬𝚨) ⇔ 𝚨<br>𝚾≠𝚼 ⇔ ¬(𝚾＝𝚼)</td>
        <td data-cell="Unicode">U+00AC<br>U+02DC<br>U+0021</td>
        <td data-cell="HTML decimal">&﹟172;<br>&﹟732;<br>&﹟33;</td>
        <td data-cell="HTML entity">﹠not;<br>﹠tilde;<br>﹠excl;</td>
        <td data-cell="LaTeX">¬\not or \neg<br>~\sim</td>
      </tr>
      <!-- ㊢ TEMPLATE <tr> below not displayed; copy to above this comment to add more rows… -->
      <tr>
        <td data-cell="SYMBOL"></td>
        <td data-cell="CONCEPT"></td>
        <td data-cell="“read as…”"></td>
        <td data-cell="CATEGORY"></td>
        <td data-cell="Explanation"></td>
        <td data-cell="Examples"></td>
        <td data-cell="Unicode"></td>
        <td data-cell="HTML decimal"></td>
        <td data-cell="HTML entity"></td>
        <td data-cell="LaTeX"></td>
      </tr>
    </table>
  </div>
</main>

<script type="text/JavaScript">
// https://stackoverflow.com/questions/400212/how-do-i-copy-to-the-clipboard-in-javascript
</script>