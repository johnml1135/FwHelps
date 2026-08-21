---
title: "Examples of combinations of regular expressions"
source_title: "Examples of combinations of regular expressions"
breadcrumb:
  - "Basic Tasks"
  - "Filtering data"
  - "Examples of combinations of Regular Expressions"
source: "Basic_Tasks/Filtering_data/examples_of_combinations_of_regular_expressions.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Basic_Tasks/Filtering_data/examples_of_combinations_of_regular_expressions.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Regular Expression:Examples of combinations of regular expressions"
  - "Expression"
  - "Regular"
  - "Example"
  - "Capture"
  - "Examples of"
related:
  - "About regular expressions -> About_Regular_Expressions.md"
  - "Basic Tasks overview -> ../Basic_Tasks_overview.md"
  - "Examples of regular expressions -> Examples_of_Regular_Expressions.md"
  - "Find and Replace using regular expressions -> ../Find_and_Replace/Find_and_Replace_using_regular_expressions.md"
  - "Example -> ../Find_and_Replace/Example_Find_and_Replace_using_regular_expressions.md"
  - "Regular expressions metacharacters table -> Regular_Expression_Metacharacters_table.md"
  - "Regular expressions operators table -> Regular_Expression_Operators_table.md"
  - "Using regular expressions assistance -> Using_regular_expressions_assistance.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:d472462aaf56fae6"
---

# Examples of combinations of regular expressions

*Basic Tasks › Filtering data*

For more information on ICU regular expressions, see <a href="https://unicode-org.github.io/icu/userguide/strings/regexp.html" target="_blank" title="https://unicode-org.github.io/icu/userguide/strings/regexp.html">https://unicode-org.github.io/icu/userguide/strings/regexp.html</a>.

<table width="100%">
<tbody>
<tr>
<th style="width: 34%"><p>Combination</p></th>
<th style="width: 34%"><p>Description</p></th>
<th style="width: 31%"><p>Results / Notes</p></th>
</tr>
&#10;<tr>
<td style="width: 34%"><p><code>\s\d</code></p></td>
<td style="width: 34%"><p>Matches a whitespace character followed by a digit.</p></td>
<td style="width: 31%"><p>In "4 + 5 = 9" <code>\s\d</code> matches " 5" (space 5).</p></td>
</tr>
<tr>
<td style="width: 34%"><p><code>\d$</code> <em>or</em> <code>\w*\d</code> <em>or</em> <code>[a-z]?\d</code></p></td>
<td style="width: 34%"><p>Any of these combinations match entries that end with a digit.</p></td>
<td style="width: 31%"><p>These will find homographs in the headword column.</p></td>
</tr>
<tr>
<td style="width: 34%"><p><code>\b(\w+)\s+\1\b</code></p></td>
<td style="width: 34%"><p>Finds a word occurring twice in succession.</p></td>
<td style="width: 31%"></td>
</tr>
<tr>
<td style="width: 34%"><p><code>^\s+</code></p></td>
<td style="width: 34%"><p>Match leading whitespace.</p></td>
<td style="width: 31%"></td>
</tr>
<tr>
<td style="width: 34%"><p><code>\s+$</code></p></td>
<td style="width: 34%"><p>Match trailing whitespace.</p></td>
<td style="width: 31%"></td>
</tr>
<tr>
<td style="width: 34%"><p><code>^[^ ]+$</code></p></td>
<td style="width: 34%"><p>Match any single word or form, including those with <a href="../../Using_Tools/Lists_tools/Change_the_tokens_for_morpheme_types.md">tokens</a>.</p></td>
<td style="width: 31%"><p>Use, for example, to filter phrases out of the <strong>Headword</strong> column.</p></td>
</tr>
<tr>
<td style="width: 34%"><p><code>^\w+$</code></p></td>
<td style="width: 34%"><p>Match any single word or form, excluding those with <a href="../../Using_Tools/Lists_tools/Change_the_tokens_for_morpheme_types.md">tokens</a>.</p></td>
<td style="width: 31%"><p>Results are similar to <code>^[^ ]+$</code>, if the column does not show tokens (such as the <strong>Lexeme</strong> column).</p></td>
</tr>
<tr>
<td style="width: 34%"><p><code>.ow</code></p>
<p>(where <code>o</code> and <code>w</code> are characters to be found)</p></td>
<td style="width: 34%"><p>Match words that have <em>any</em> character preceding "ow".</p></td>
<td style="width: 31%"><p>If used with <strong>Replace</strong>, at each match, <em>three</em> characters are replaced: the <code>o</code> and the <code>w</code>, and one preceding character.</p></td>
</tr>
<tr>
<td style="width: 34%"><p><code>.+ow</code></p></td>
<td style="width: 34%"><p>Match words that have <em>any</em> combination of any characters preceding "ow" as many times as possible. Strings beginning with "ow" are <em>not</em> matched.</p></td>
<td style="width: 31%"><p>If used with <strong>Replace</strong>, each instance of "ow" is replaced and <em>all</em> preceding characters are replaced.</p></td>
</tr>
<tr>
<td style="width: 34%"><p><code>.?ow</code></p></td>
<td style="width: 34%"><p>Match words that have <em>any</em> single character or no character before the letters "ow". Strings beginning with "ow" are matched.</p></td>
<td style="width: 31%"><p>If used with <strong>Replace</strong>, each instance of "ow" is replaced, and, <em>if any</em>, the single character preceding each "ow" is replaced.</p></td>
</tr>
<tr>
<td style="width: 34%"><p><code>.?ow|.?on</code></p></td>
<td style="width: 34%"><p>Match words that have <em>any</em> single character or no character before the letters "ow" or "on". Strings beginning with "ow" or "on" are matched.</p></td>
<td style="width: 31%"><p>If used with <strong>Replace</strong>, each instance of "ow" <em>and</em> "on" are replaced, and, <em>if any</em>, the single character preceding each "ow" and "on" are replaced.</p></td>
</tr>
<tr>
<td style="width: 34%"><p><code>q[^u]</code></p></td>
<td style="width: 34%"><p>Match "q" followed by a character that is <em>not</em> a "u"</p></td>
<td style="width: 31%"><p>Finds "Iraq is in the mid-East" but <em>not</em> "Iraq" nor "He came quickly".</p>
<p>(Note that a caret leading bracketed contents acts as a "not".)</p></td>
</tr>
<tr>
<td style="width: 34%"><p><code>(.+)(;)(.+)</code></p></td>
<td style="width: 34%"><p>Match anything that has content before and after a semicolon.</p>
<p>(Captures three variables.)</p></td>
<td style="width: 31%"><p>Use <code>(.+)(;)(.+)</code> as <em>find</em> criteria, and use <a href="../Find_and_Replace/Find_and_Replace_using_regular_expressions.md">$1 variable as replacement criteria</a> to retain only content ahead of the semicolon.</p></td>
</tr>
<tr>
<td style="width: 34%"><p><code>q(?!u)</code></p></td>
<td style="width: 34%"><p>Match "q" not followed by "u". This (? ... ) syntax is for negative lookahead, which doesn't "use up" anything in the input but will prevent a match at the current position if the next character is "u".</p></td>
<td style="width: 31%"><p>Finds "Iraq" but not "quickly".</p></td>
</tr>
<tr>
<td style="width: 34%"><p><code>^((?!see).)*$</code></p></td>
<td style="width: 34%"><p>Match anything that does not contain the string "see".</p></td>
<td style="width: 31%"><p>Finds "serene" and "se'e" but not "see", "seer", "Tennessee".</p></td>
</tr>
<tr>
<td style="width: 34%"><p><strong>^(?:(?!see).)*$</strong></p></td>
<td style="width: 34%"><p>Match anything that does not contain the string "see". This version is more efficient because (?: ... ) is a non-capturing parenthesis.</p></td>
<td style="width: 31%"></td>
</tr>
<tr>
<td style="width: 34%"><p><code>\p{M}</code></p></td>
<td style="width: 34%"><p>Match any character recognized in Unicode as a diacritic</p></td>
<td style="width: 31%"></td>
</tr>
<tr>
<td style="width: 34%"><p><code>[aeiou]\p{M}</code></p></td>
<td style="width: 34%"><p>Match any vowel with a diacritic.</p></td>
<td style="width: 31%"><p>If this pattern stands alone and is not used for replacement, it doesn't matter if it has more diacritics.</p></td>
</tr>
<tr>
<td style="width: 34%"><p><code>[aeiou]{3}</code></p></td>
<td style="width: 34%"><p>Finds exactly three adjacent vowels</p></td>
<td style="width: 31%"><p>They do not have to be the same.</p></td>
</tr>
<tr>
<td style="width: 34%"><p><code>([aeiou])\1{2}</code></p></td>
<td style="width: 34%"><p>Finds exactly three adjacent occurrences of the same vowel.</p></td>
<td style="width: 31%"></td>
</tr>
<tr>
<td style="width: 34%"><p><code>([aeiou]+)([^ aeiou]+)\S*\1\2</code></p></td>
<td style="width: 34%"><p>This is a first cut at reduplication. It finds syllables (sequence of vowels, sequence of non-vowels that are not spaces) which occur twice in a word.</p></td>
<td style="width: 31%"><p>Note the space in the negated set...otherwise, it finds matching syllables in different words. (It could be enhanced to deal intelligently with diacritics.)</p></td>
</tr>
<tr>
<td style="width: 34%"><p><code>(\w)\1</code></p></td>
<td style="width: 34%"><p>Match any double letter (or digit)</p></td>
<td style="width: 31%"></td>
</tr>
<tr>
<td style="width: 34%"><p><code>([aeiou]\p{M}*)\1</code></p></td>
<td style="width: 34%"><p>Match any double vowel.</p></td>
<td style="width: 31%"><p>The vowel may have any number of diacritics. The diacritics on both vowels must be the same.</p></td>
</tr>
<tr>
<td style="width: 34%"><p><code>([aeiou])\p{M}*\1\p{M}*</code></p></td>
<td style="width: 34%"><p>Match any double vowel.</p></td>
<td style="width: 31%"><p>Either vowel may have any number of diacritics. They do <em>not</em> have to be the same.</p></td>
</tr>
<tr>
<td style="width: 34%"><p><code>([aeiou])\p{M}*[aeiou]\p{M}*</code></p></td>
<td style="width: 34%"><p>Match any two adjacent vowels.</p></td>
<td style="width: 31%"><p>Either may have any number of diacritics. The two vowels may be different.</p></td>
</tr>
<tr>
<td style="width: 34%"><p><code>([aeiou])\p{M}*(?!\p{M})\w+\1</code></p></td>
<td style="width: 34%"><p>This is an attempt to find vowel harmony. Finds words with the same vowel occurring twice. They may have (possibly differing) diacritics. There must be at least one word-forming non-diacritic character between them.</p></td>
<td style="width: 31%"><p>This one requires some explanation. [aeiou] matches a vowel. With parentheses around it, it still matches that vowel, but now \1 (at the end) matches the same vowel. \w+ allows any number of word-forming characters (but requires at least one). However, ([aeiou])\w+\1 would allow matches where all that is between the two vowels is a diacritic over the first one. To prevent this we insert \p{M}*(?!\p{M}) which matches any number of diacritics provided that the following character is NOT a diacritic. This ?! is called negative look-ahead. A tricky, advanced feature, but it can do some powerful things.</p></td>
</tr>
<tr>
<td style="width: 34%"><p><code>([aeiou])\p{M}*(?!\p{M})[^aeiou]+\1</code></p></td>
<td style="width: 34%"><p>Another variation for finding vowel harmony. The only difference is that the first required at least one word-forming character; this (using [^aeiou]+) requires at least one non-vowel.</p></td>
<td style="width: 31%"><p>Be careful, though, as non-vowels include spaces and punctuation, so this can match two vowels in different words. You can reduce this problem by adding space and various punctuation characters to the negated set.</p></td>
</tr>
</tbody>
</table>

> [!TIP]
>
> - Some of the above regular expressions are available for selection in the [Filter for](Using_Filter_for.md) dialog box, [assistance button](Using_regular_expressions_assistance.md).
>
> - FieldWorks automatically adds the forward slashes before and after the regular expression so you do not need to type them manually. For example, if you type `\s` into the [Filter for items containing dialog box](Using_Filter_for.md), you will see `\/s\` in the column (below heading) where you set the filter.
>
> - For the `\N{ }` regular expression, you can use the [Character Map](../../User_Interface/Menus/Insert/Using_Character_Map.md) to help identify the names of characters. The name typically appears at the bottom of the **Character Map** dialog box.

## Related topics
[About regular expressions](About_Regular_Expressions.md)

[Basic Tasks overview](../Basic_Tasks_overview.md)

[Examples of regular expressions](Examples_of_Regular_Expressions.md)

[Find and Replace using regular expressions](../Find_and_Replace/Find_and_Replace_using_regular_expressions.md) ([Example](../Find_and_Replace/Example_Find_and_Replace_using_regular_expressions.md))

[Regular expressions metacharacters table](Regular_Expression_Metacharacters_table.md)

[Regular expressions operators table](Regular_Expression_Operators_table.md)

[Using regular expressions assistance](Using_regular_expressions_assistance.md)
