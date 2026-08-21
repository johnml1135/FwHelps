---
title: "Regular expression metacharacters table"
source_title: "Regular expression metacharacters table"
breadcrumb:
  - "Basic Tasks"
  - "Filtering data"
  - "Regular Expression Metacharacters table"
source: "Basic_Tasks/Filtering_data/Regular_Expression_Metacharacters_table.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Basic_Tasks/Filtering_data/Regular_Expression_Metacharacters_table.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Find:Find unicode character"
  - "Hexadecimal character"
  - "find"
  - "Regular Expression:Regular expression metacharacters table"
  - "Expression"
  - "Regular"
related:
  - "Bulk Edit Entries -> ../../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_Edit_Entries_overview.md"
  - "Find and Replace overview -> ../Find_and_Replace/Find_and_Replace_overview.md"
  - "Using regular expressions assistance -> Using_regular_expressions_assistance.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:83021eebd18b685e"
---

# Regular expression metacharacters table

*Basic Tasks › Filtering data*

Refer first to [Examples of regular expressions](Examples_of_Regular_Expressions.md) or [Examples of combinations of regular expressions](examples_of_combinations_of_regular_expressions.md). There is also a [Regular expression operators table](Regular_Expression_Operators_table.md).

<table width="100%">
<tbody>
<tr>
<th style="width: 37%"><p>Character</p></th>
<th style="width: 63%"><p>Description</p></th>
</tr>
&#10;<tr>
<td style="width: 37%"><p>\b</p></td>
<td style="width: 63%"><p>Match if the current position is a word boundary. Boundaries occur at the transitions between word (\w) and non-word (\W) characters, with combining marks ignored.</p></td>
</tr>
<tr>
<td style="width: 37%"><p>\B</p></td>
<td style="width: 63%"><p>Match if the current position is not a word boundary.</p></td>
</tr>
<tr>
<td style="width: 37%"><p>\d</p></td>
<td style="width: 63%"><p>Match any character with the Unicode General Category of Nd (Number, Decimal Digit.).</p></td>
</tr>
<tr>
<td style="width: 37%"><p>\D</p></td>
<td style="width: 63%"><p>Match any character that is not a decimal digit.</p></td>
</tr>
<tr>
<td style="width: 37%"><p>\E</p></td>
<td style="width: 63%"><p>Terminates a \Q ... \E quoted sequence.</p></td>
</tr>
<tr>
<td style="width: 37%"><p>\G</p></td>
<td style="width: 63%"><p>Match if the current position is at the end of the previous match.</p></td>
</tr>
<tr>
<td style="width: 37%"><p>\N{UNICODE CHARACTER NAME}</p></td>
<td style="width: 63%"><p>Match the named character.</p></td>
</tr>
<tr>
<td style="width: 37%"><p>\p{UNICODE PROPERTY NAME}</p></td>
<td style="width: 63%"><p>Match any character with the specified Unicode Property.</p></td>
</tr>
<tr>
<td style="width: 37%"><p>\P{UNICODE PROPERTY NAME)</p></td>
<td style="width: 63%"><p>Match any character not having the specified Unicode Property.</p></td>
</tr>
<tr>
<td style="width: 37%"><p>\Q</p></td>
<td style="width: 63%"><p>Quotes all following characters until \E.</p></td>
</tr>
<tr>
<td style="width: 37%"><p>\s</p></td>
<td style="width: 63%"><p>Match a white space character. White space is defined as [\t\n\f\r\p{Z}].</p></td>
</tr>
<tr>
<td style="width: 37%"><p>\S</p></td>
<td style="width: 63%"><p>Match a non-white space character.</p></td>
</tr>
<tr>
<td style="width: 37%"><p>\t</p></td>
<td style="width: 63%"><p>Match a HORIZONTAL TABULATION, \u0009.</p></td>
</tr>
<tr>
<td style="width: 37%"><p>\uhhhh</p></td>
<td style="width: 63%"><p>Match the character with the hex value hhhh.</p></td>
</tr>
<tr>
<td style="width: 37%"><p>\Uhhhhhhhh</p></td>
<td style="width: 63%"><p>Match the character with the hex value hhhhhhhh. Exactly eight hex digits must be provided, even though the largest Unicode code point is \U0010ffff.</p></td>
</tr>
<tr>
<td style="width: 37%"><p>\w</p></td>
<td style="width: 63%"><p>Match a word character. Word characters are [\p{Ll}\p{Lu}\p{Lt}\p{Lo}\p{Nd}].</p></td>
</tr>
<tr>
<td style="width: 37%"><p>\W</p></td>
<td style="width: 63%"><p>Match a non-word character.</p></td>
</tr>
<tr>
<td style="width: 37%"><p>\x{hhhh}</p></td>
<td style="width: 63%"><p>Match the character with hex value hhhh. From one to six hex digits may be supplied.<br />
For example, to find U+0297, Latin Letter Stretch C, type <code>\x{0297}</code></p></td>
</tr>
<tr>
<td style="width: 37%"><p>\xhh</p></td>
<td style="width: 63%"><p>Match the character with two digit hex value hh.</p></td>
</tr>
<tr>
<td style="width: 37%"><p>\X</p></td>
<td style="width: 63%"><p>Match a Grapheme Cluster.</p></td>
</tr>
<tr>
<td style="width: 37%"><p>\n</p></td>
<td style="width: 63%"><p>Back Reference. Match whatever the nth capturing group matched. n must be a number &gt; 1 and &lt; total number of capture groups in the pattern. Note: Octal escapes, such as \012, are not supported in ICU regular expressions.</p></td>
</tr>
<tr>
<td style="width: 37%"><p>[pattern]</p></td>
<td style="width: 63%"><p>Match any one character from the set. See <strong>UnicodeSet</strong> at <a href="https://icu.sourceforge.net/userguide/unicodeSet.html" target="_blank" title="https://icu.sourceforge.net/userguide/unicodeSet.html">https://icu.sourceforge.net/userguide/unicodeSet.html</a> for a full description of what may appear in the pattern.</p></td>
</tr>
<tr>
<td style="width: 37%"><p>.</p></td>
<td style="width: 63%"><p>Match any character.</p></td>
</tr>
<tr>
<td style="width: 37%"><p>^</p></td>
<td style="width: 63%"><p>Match at the beginning of a line.</p></td>
</tr>
<tr>
<td style="width: 37%"><p>$</p></td>
<td style="width: 63%"><p>Match at the end of a line.</p></td>
</tr>
<tr>
<td style="width: 37%"><p>\</p></td>
<td style="width: 63%"><p>Quotes the following character. Characters that <em>must be quoted</em> to be treated as literals are * ? + [ ( ) { } ^ $ | \ . /</p></td>
</tr>
</tbody>
</table>

## Related topics
[Bulk Edit Entries](../../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_Edit_Entries_overview.md)

[Find and Replace overview](../Find_and_Replace/Find_and_Replace_overview.md)

[Using regular expressions assistance](Using_regular_expressions_assistance.md)
