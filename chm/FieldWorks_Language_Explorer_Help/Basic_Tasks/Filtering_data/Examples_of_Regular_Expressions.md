---
title: "Examples of regular expressions"
source_title: "Examples of regular expressions"
breadcrumb:
  - "Basic Tasks"
  - "Filtering data"
  - "Examples of Regular Expressions"
source: "Basic_Tasks/Filtering_data/Examples_of_Regular_Expressions.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Basic_Tasks/Filtering_data/Examples_of_Regular_Expressions.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Regular Expression:Examples of regular expressions"
  - "Expression"
  - "Regular"
  - "Example"
  - "Capture"
  - "Examples of"
related:
  - "About regular expressions -> About_Regular_Expressions.md"
  - "Basic Tasks overview -> ../Basic_Tasks_overview.md"
  - "Examples of combinations of regular expressions -> examples_of_combinations_of_regular_expressions.md"
  - "Find and Replace using regular expressions -> ../Find_and_Replace/Find_and_Replace_using_regular_expressions.md"
  - "Example -> ../Find_and_Replace/Example_Find_and_Replace_using_regular_expressions.md"
  - "Regular expressions metacharacters table -> Regular_Expression_Metacharacters_table.md"
  - "Regular expressions operators table -> Regular_Expression_Operators_table.md"
  - "Using regular expressions assistance -> Using_regular_expressions_assistance.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:a8f931344b206209"
---

# Examples of regular expressions

*Basic Tasks › Filtering data*

<table width="100%">
<tbody>
<tr>
<th style="width: 26%"><p>Use Character</p></th>
<th style="width: 23%"><p>To</p></th>
<th style="width: 52%"><p>Examples</p></th>
</tr>
&#10;<tr>
<td style="width: 26%"><p><code>^ (caret)</code></p></td>
<td style="width: 23%"><p>Match at the <em>beginning</em> of a string.</p></td>
<td style="width: 52%"><p>In "abc" ^<code>a</code> matches the "a," but <code>^b</code> finds no match.</p></td>
</tr>
<tr>
<td style="width: 26%"><p><code>^(?!root)</code></p></td>
<td style="width: 23%"><p>Match everything except "root"</p></td>
<td style="width: 52%"><p>In a <strong>Morph Type</strong> column, use this to exclude roots. Use syntax in any column, replacing 'root' with appropriate word or characters.<strong><br />
^(?!.*noun.*)</strong> with wild cards (<strong>*</strong>) excludes any item the contains 'noun'.</p></td>
</tr>
<tr>
<td style="width: 26%"><p><code>[^x]</code></p></td>
<td style="width: 23%"><p>Match any character <em>except</em> "x"</p></td>
<td style="width: 52%"><p><code>^[^ ]+$</code> matches any entry <em>except</em> those that have a space.</p></td>
</tr>
<tr>
<td style="width: 26%"><p><code>^[^x]</code></p></td>
<td style="width: 23%"><p>Match any string <em>except</em> strings that begin with "x"</p></td>
<td style="width: 52%"><p><code>^[^-]</code> excludes all entries that begin with a hyphen, such as prefixes.</p></td>
</tr>
<tr>
<td style="width: 26%"><p><code>$ (dollar)</code></p></td>
<td style="width: 23%"><ul>
<li><p>Match a character at the <em>end</em> of a string.</p></li>
<li><p>Used with <a href="Regular_Expression_Operators_table.md">capture</a> as the <a href="../Find_and_Replace/Find_and_Replace_using_regular_expressions.md">replacement criteria</a>.</p></li>
</ul></td>
<td style="width: 52%"><ul>
<li><p>In "abc" <code>c$</code> matches the "c," but <code>b$</code> finds no match.</p></li>
<li><p>Entering <code>$1</code> in <strong>Replace with</strong> box to replace the <em>first</em> captured content, specifically, that found matching the expression in the first set of parenthesis ( ).</p></li>
<li><p>You can have more than one set of parenthesis (<a href="../Find_and_Replace/Example_Find_and_Replace_using_regular_expressions.md">example</a>).</p></li>
</ul></td>
</tr>
<tr>
<td style="width: 26%"><p><code>. (dot)</code></p></td>
<td style="width: 23%"><p>Match any single character, without regard to what that character is.</p></td>
<td style="width: 52%"><p>In "This is a nice island".<code>is</code> matches "This" and "island."</p>
<p>(T<em>he dot character can get you in trouble, so use sparingly and with caution! In Unicode, the dot matches any single unicode point, but</em> <code>á</code> is actually two characters.)</p></td>
</tr>
<tr>
<td style="width: 26%"><p><code>| (bar)</code></p></td>
<td style="width: 23%"><p>Allow alternation.</p></td>
<td style="width: 52%"><p><code>oy|ay|ey|aw</code> to find any occurrence of diphthongs oy, ay, ey, or aw.</p></td>
</tr>
<tr>
<td style="width: 26%"><p><code>* (asterisk)</code></p></td>
<td style="width: 23%"><p>Match 0 or more times, as many as possible.</p></td>
<td style="width: 52%"><p>"<code>.*</code>" match any number of characters as many times as possible.</p></td>
</tr>
<tr>
<td style="width: 26%"><p><code>+ (plus)</code></p></td>
<td style="width: 23%"><p>Match 1 or more times, as many as possible.</p></td>
<td style="width: 52%"></td>
</tr>
<tr>
<td style="width: 26%"><p><code>? (question mark)</code></p></td>
<td style="width: 23%"><p>Match zero or one time, preferably one, or make the <em>preceding</em> item optional.</p></td>
<td style="width: 52%"><p><code>colou?r</code> will match both "color" and "colour."</p></td>
</tr>
<tr>
<td style="width: 26%"><p><code>\ (slash)</code></p></td>
<td style="width: 23%"><p>Quote the <em>following</em> character to make the character literal.</p></td>
<td style="width: 52%"><p>Characters that must be quoted to be treated as literals are <code>* ? + [ ( ) { } ^ $ | \ . /</code></p>
<p>Use <code>\.</code> to find a period, or <code>\?</code> find a question mark.</p></td>
</tr>
<tr>
<td style="width: 26%"><p><code>{n}</code></p></td>
<td style="width: 23%"><p>Match exactly <em>n</em> times.</p></td>
<td style="width: 52%"></td>
</tr>
<tr>
<td style="width: 26%"><p><code>[pattern]</code></p></td>
<td style="width: 23%"><p>Match any one character from the set in brackets.</p></td>
<td style="width: 52%"><p><code>c[aeiou]t</code> matches <strong>cat, cet, cit, cot,</strong> and <strong>cut</strong>.</p></td>
</tr>
<tr>
<td style="width: 26%"><p><code>\b</code></p></td>
<td style="width: 23%"><p>Perform "whole words only" search, as <code>\b</code><em>word</em><code>\b</code><code>.</code></p></td>
<td style="width: 52%"><ul>
<li><p>Use <code>\bthe\b</code> to find the word "the" in definitions or glosses.</p></li>
<li><p>In "This is a nice island." <code>\bis\b</code> matches only the "is" but <em>not</em> "This" and "island."</p></li>
</ul></td>
</tr>
<tr>
<td style="width: 26%"><p><code>\B</code></p></td>
<td style="width: 23%"><p>Match every position where \b does not.</p></td>
<td style="width: 52%"><p>In "This is a nice island." <code>\Bis</code> matches only the "is" in "This," and <code>is\B</code> matches only the "is" in "island."</p></td>
</tr>
<tr>
<td style="width: 26%"><p><code>\d</code></p></td>
<td style="width: 23%"><p>Match any digit from 0 to 9 and <a href="Regular_Expression_Metacharacters_table.md">more (see metacharacters table)</a>.</p></td>
<td style="width: 52%"><p>In "1.2" <code>\d</code> matches both the 1 and the 2.</p>
<p>(In <strong>Find/Replace</strong>, both may be replaced.)</p></td>
</tr>
<tr>
<td style="width: 26%"><p><strong>\d{0,1}$</strong></p></td>
<td style="width: 23%"><p>Ignore homographs numbers.</p></td>
<td style="width: 52%"><p>When you sort and filter on letters at the end of headwords, <strong>\d{0,1}$</strong> helps make sure <em>that the possible presence of a homograph number does not affect the results</em>. Type the letters you want to find ahead of the slash.</p>
<p> <code>Tip</code>: Lexeme form columns do not display the homograph numbers.</p></td>
</tr>
<tr>
<td style="width: 26%"><p><code>\N{unicode character name}</code></p></td>
<td style="width: 23%"><p>Match named character. (See "<strong>Tip</strong>" below.)</p></td>
<td style="width: 52%"><ul>
<li><p><code>\N{Hyphen-Minus}</code> matches a single Unicode code point that has the name "Hyphen-Minus."</p></li>
<li><p><code>\N{Em Dash}</code> matches a single Unicode code point that has the name "Em Dash."</p></li>
</ul></td>
</tr>
<tr>
<td style="width: 26%"><p><code>\p{unicode property name}</code></p></td>
<td style="width: 23%"><p>Match any character with a specified unicode property.</p></td>
<td style="width: 52%"><ul>
<li><p><code>\p{L}</code> or <code>\p{Letter}</code> matches a single Unicode code point that has the property "letter."</p></li>
<li><p><code>\p{Pd}</code> (Punctuation dash) matches a single dash.</p></li>
<li><p><code>\p{Po}</code> (Punctuation other) matches punctuation <em>not</em> a dash, bracket, quote or connector.</p></li>
<li><p><code>\p{N}</code> or <code>\p{Number}</code> matches numbers.</p></li>
</ul></td>
</tr>
<tr>
<td style="width: 26%"><p><code>\P{unicode property name}</code></p></td>
<td style="width: 23%"><p>Match any character <em>without</em> a specified unicode property.</p></td>
<td style="width: 52%"><ul>
<li><p><code>\P{M}</code> matches a code point that is <em>not</em> a combining mark.</p></li>
<li><p><code>\P{N}</code> or <code>\P{Number}</code> matches item that are <em>not</em> numbers.</p></li>
</ul></td>
</tr>
<tr>
<td style="width: 26%"><p><code>\s</code></p></td>
<td style="width: 23%"><p>Match a "whitespace character."</p></td>
<td style="width: 52%"><ul>
<li><p>Use "black<code>\s</code>board" as the find string and "blackboard" as the replace criteria.</p></li>
<li><p>Use <code>\s</code> to find a space in a gloss you want to replace with a period.</p></li>
</ul></td>
</tr>
<tr>
<td style="width: 26%"><p><code>\w</code></p></td>
<td style="width: 23%"><p>Match word characters, as compared to non-word characters such as spaces.</p></td>
<td style="width: 52%"><p><code>\w</code> matches very letter and digit in the string, except spaces.</p></td>
</tr>
<tr>
<td style="width: 26%"><p><code>\W</code></p></td>
<td style="width: 23%"><p>Match non-word characters, such as spaces.</p></td>
<td style="width: 52%"><p><code>\W</code> matches the spaces in the string. Use to replace spaces with a period in a gloss.</p></td>
</tr>
</tbody>
</table>

> [!TIP]
>
> - Some of the above regular expressions are available for selection in the [Filter for](Using_Filter_for.md) dialog box, [assistance button](Using_regular_expressions_assistance.md).
>
> - FieldWorks automatically adds the forward slashes before and after the regular expression so you do not need to type them manually. For example, if you type `\s` into the [Filter for items containing dialog box](Using_Filter_for.md), you will see `/\s/` in the column (below heading) where you set the filter.
>
> - For the `\N{ }` regular expression, you can use the [Character Map](../../User_Interface/Menus/Insert/Using_Character_Map.md) to help identify the names of characters. The name typically appears at the bottom of the **Character Map** dialog box.

## Related topics
[About regular expressions](About_Regular_Expressions.md)

[Basic Tasks overview](../Basic_Tasks_overview.md)

[Examples of combinations of regular expressions](examples_of_combinations_of_regular_expressions.md)

[Find and Replace using regular expressions](../Find_and_Replace/Find_and_Replace_using_regular_expressions.md) ([Example](../Find_and_Replace/Example_Find_and_Replace_using_regular_expressions.md))

[Regular expressions metacharacters table](Regular_Expression_Metacharacters_table.md)

[Regular expressions operators table](Regular_Expression_Operators_table.md)

[Using regular expressions assistance](Using_regular_expressions_assistance.md)
