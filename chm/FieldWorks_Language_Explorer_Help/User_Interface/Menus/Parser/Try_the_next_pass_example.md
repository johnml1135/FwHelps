---
title: "Try the next pass example"
source_title: "Try the next pass example"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Parser"
  - "Try the next pass example"
source: "User_Interface/Menus/Parser/Try_the_next_pass_example.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Parser/Try_the_next_pass_example.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Parser:Try the next pass example"
  - "Try the next pass example"
related:
  - "Parser menu overview -> Parser_menu_overview.md"
  - "Parsing words overview -> Parsing_words_overview.md"
  - "Texts & Words overview -> ../../../Using_Tools/Texts_&_Words_tools/Texts_and_Words_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:874dbf213cee2e6c"
---

# Try the next pass example

*User Interface › Menus › Parser*

In the **Try a Word** dialog box, one of the paragraphs reads as follows (emphasis added):

"The Word Grammar tries to build a word in a number of ways in various kinds of steps. This tool shows what happens at a particular *pass*. It shows all the steps that the Word Grammar tried at this *pass*. Look for a step that would be reasonable given your understanding of how the wordform should be parsed. If such a step is shown as *succeeding*, click the 'Try the next pass' button to see the next *pass*. If such a step failed, read the description of the failure(s) and try to figure out how to correct it."

## Underlying principle

The word grammar "builds" a word **from the stem outwards**. If you click the **Try the next pass** button, it displays what it has done in the previous pass(es). Each pass builds more of the word structure.

## Example

This example is for the Kalaba word *niyuxogabitikoti*.

Notice, in the example that follows, how the bracketing \[ \] outlines how the stem is being built. First the brackets are around only a root, then around a root and suffix, and then around a prefix, root, and suffix. *Thus, each pass builds more of the word structure*.

To see how the **Try the next pass** feature works, we can begin with this page:

![](../../../assets/images/User_Interface/Menus/Parser/Try_next_pass_pic1.PNG)

<table width="100%">
<tbody>
<tr>
<th style="width: 26%"><p>Allomorph</p></th>
<th style="width: 33%"><p>Type</p></th>
<th style="width: 41%"><p>Other info</p></th>
</tr>
&#10;<tr>
<td style="width: 26%"><p>ni-</p>
<p>1SgSubj</p>
<p>ni</p></td>
<td style="width: 33%"><p>inflectional affix</p></td>
<td style="width: 41%"><p>Slot = (Subject)</p></td>
</tr>
<tr>
<td style="width: 26%"><p>yu-</p>
<p>2SgObj</p>
<p>yu</p></td>
<td style="width: 33%"><p>inflectional affix</p></td>
<td style="width: 41%"><p>Slot = Object</p></td>
</tr>
<tr>
<td style="width: 26%"><p>xo-</p>
<p>Pass</p>
<p>xo</p></td>
<td style="width: 33%"><p>derivational prefix</p></td>
<td style="width: 41%"><p>From category = bitrans</p>
<p>To category = trans</p>
<p>To inflection class = 2</p></td>
</tr>
<tr>
<td style="width: 26%"><p>*gabi</p>
<p>to hit</p>
<p>higabira</p></td>
<td style="width: 33%"><p>root</p></td>
<td style="width: 41%"><p>Category = trans</p>
<p>Inflectional class = 1</p></td>
</tr>
<tr>
<td style="width: 26%"><p>-ti</p>
<p>Caus</p>
<p>ti</p></td>
<td style="width: 33%"><p>derivational suffix</p></td>
<td style="width: 41%"><p>From category = trans</p>
<p>To category = bitrans</p>
<p>To inflection class = 1</p></td>
</tr>
<tr>
<td style="width: 26%"><p>-ko</p>
<p>Past</p>
<p>bi</p></td>
<td style="width: 33%"><p>inflectional affix</p></td>
<td style="width: 41%"><p>Slot = Tense</p></td>
</tr>
<tr>
<td style="width: 26%"><p>-ti</p>
<p>Caus</p>
<p>ti</p></td>
<td style="width: 33%"><p>derivational suffix</p></td>
<td style="width: 41%"><p>From category = intrans</p>
<p>To category = trans</p>
<p>To inflectional class = 1</p></td>
</tr>
</tbody>
</table>

- Clicking the **Try the next pass** button on the first success results in the following:

![](../../../assets/images/User_Interface/Menus/Parser/Try_next_pass_pic2.PNG)

- Then, clicking the **Try the next pass** button on the new first success results in the following:

![](../../../assets/images/User_Interface/Menus/Parser/Try_next_pass_pic3.PNG)

- Then, clicking the **Try the next pass** button on the new first success results in the following:

![](../../../assets/images/User_Interface/Menus/Parser/Try_next_pass_pic4.PNG)

## Related topics
[Parser menu overview](Parser_menu_overview.md)

[Parsing words overview](Parsing_words_overview.md)

[Texts & Words overview](../../../Using_Tools/Texts_%26_Words_tools/Texts_and_Words_overview.md)
