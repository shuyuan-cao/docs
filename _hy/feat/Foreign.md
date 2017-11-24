---
layout: feature
title: 'Foreign'
shortdef: 'is this a foreign word?'
udver: '2'
---

<table class="typeindex" border="1">
<tr>
  <td style="background-color:cornflowerblue;color:white"><strong>Values:</strong> </td>
  <td><a href="#Yes">Yes</a></td>
</tr>
</table>

Boolean feature. Is this a foreign word? Not a loan word
but a genuinely foreign word appearing inside native
text, e.g. inside direct speech, titles of books etc.

This feature would apply either to the [X]() part of speech (unanalyzable token), or to other parts of speech if we know and are willing to annotate the class to which the word belongs in its original language.

Prepositions, conjunctions or articles in foreign names _(van, von, de, le)&nbsp;_ are tagged [DET](). The morphological analysis usually do not includes the original part of speech of foreign words.

### <a name="Yes">`Yes`</a>: it is foreign

#### Examples

* _... <b>ՏԱՍՍ</b>-ի հաղորդագրությունները nese jméno <b>VLIW</b> (<b>Very Long Instruction Word</b> &ndash; velmi dlouhé instrukční slovo)_
