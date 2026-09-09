---
title: "About parser parameters"
source_title: "About parser parameters"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Parser"
  - "About parser parameters"
source: "User_Interface/Menus/Parser/About_parser_parameters.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Parser/About_parser_parameters.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Parser:About parser parameters"
  - "Parameters"
  - "default"
  - "About:Parser Parameters"
  - "Clitics:About parser parameters"
  - "Phonological Rules:About parser parameters"
  - "Compound Rule"
related:
  - "Parser menu overview -> Parser_menu_overview.md"
  - "Parsing words overview -> Parsing_words_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:56a1717ff9ad2f27"
---

# About parser parameters

*User Interface › Menus › Parser*

It is recommended that you review the following table before you [Edit parser parameters](Edit_Parser_Parameters.md).

## Change XAmple Parser Parameters (**Default Parser)**

<table width="100%">
<tbody>
<tr>
<th style="width: 16%"><p>Parameter</p></th>
<th style="width: 19%"><p>Default value</p></th>
<th style="width: 65%"><p>Description</p></th>
</tr>
&#10;<tr>
<td style="width: 16%"><p><strong>MaxNulls</strong></p></td>
<td style="width: 19%"><p>1</p></td>
<td style="width: 65%"><p>The maximum number of <a href="../../../Morphology_and_Parsing_Tasks/null_allomorphs.md">null allomorphs</a> that may appear in a single well-formed word.</p>
<p>You want this to be as <em>small</em> as possible to make parsing efficient.</p></td>
</tr>
<tr>
<td style="width: 16%"><p><strong>MaxPrefixes</strong></p></td>
<td style="width: 19%"><p>5</p></td>
<td style="width: 65%"><p>The maximum number of prefixes and proclitics that may appear in a single well-formed word.</p>
<p>Note that it is the sum of the maximum number of prefixes plus the maximum number of proclitics. You want this to be as <em>small</em> as possible to make parsing efficient.</p></td>
</tr>
<tr>
<td style="width: 16%"><p><strong>MaxInfixes</strong></p></td>
<td style="width: 19%"><p>0</p></td>
<td style="width: 65%"><p>The maximum number of infixes that may appear in a single well-formed word.</p>
<p>If you have at least one infix, this number will automatically be set to 1.</p>
<p>You will only need to change it if you can have two or more infixes in a single well-formed word. You want this to be as <em>small</em> as possible to make parsing efficient.</p></td>
</tr>
<tr>
<td style="width: 16%"><p><strong>MaxRoots</strong></p></td>
<td style="width: 19%"><p>1 or 2</p></td>
<td style="width: 65%"><p>The maximum number of roots that may appear in a single well-formed word.</p>
<p>Any lexical entry with a morpheme type of root, bound root, stem or bound stem is considered to be a root as far as this parameter is concerned.</p>
<p>If you have at least one compound rule, this number will automatically be set to 2. Otherwise, it defaults to 1.</p>
<p>You will only need to change it if you can have three or more roots that can compound in a single well-formed word. You want this to be as <em>small</em> as possible to make parsing efficient.</p></td>
</tr>
<tr>
<td style="width: 16%"><p><strong>MaxSuffixes</strong></p></td>
<td style="width: 19%"><p>5</p></td>
<td style="width: 65%"><p>The maximum number of suffixes and enclitics that may appear in a single well-formed word.</p>
<p>Note that it is the sum of the maximum number of suffixes plus the maximum number of enclitics. You want this to be as <em>small</em> as possible to make parsing efficient.</p></td>
</tr>
<tr>
<td style="width: 16%"><p><strong>MaxInterfixes</strong></p></td>
<td style="width: 19%"><p>0 or 1</p></td>
<td style="width: 65%"><p>The maximum number of interfixes that may appear in a single well-formed word.</p>
<p>If you have at least one interfix, this number will automatically be set to 1.</p>
<p>You will only need to change it if you can have two or more interfixes in a single well-formed word.</p>
<p>You want this to be as <em>small as possible</em> to make parsing efficient. (Interfixes are affixes (prefixes, infixes, or suffixes) which can appear between roots in compounds.)</p></td>
</tr>
<tr>
<td style="width: 16%"><p><strong>MaxAnalyses</strong></p></td>
<td style="width: 19%"><p>See description</p></td>
<td style="width: 65%"><p>The maximum number of analyses (i.e. parses) the parser will return.</p>
<p>If this is set to -1 (or less), the parser returns all the analyses/parses it discovers. (Depending on your implementation, this could be quite large or rather small.) This value was probably set to 10 when you created your language project. You want this parameter to be <em>large enough</em> to see the parses being produced, but not so large that the parsing process becomes inefficient. You can try setting it to a value of 10, say, and then, if you have wordforms with 10 parser-generated analyses, be aware that the parser might actually be producing more than 10 parses. You would need to increase this parameter to see if that is the case or not.</p></td>
</tr>
</tbody>
</table>

## Change HC Parser Parameters (**Phonological Rules-based Parser)**

<table width="100%">
<tbody>
<tr>
<th style="width: 16%"><p>Parameter</p></th>
<th><p>Default value</p></th>
<th><p>Description</p></th>
</tr>
&#10;<tr>
<td style="width: 16%"><p><strong>DelReapps</strong></p></td>
<td><p>0</p></td>
<td><p>Normally, deletion rules only apply once. If you find that you need a deletion rule to apply more than once, you will need to set this parameter to greater than zero. You want this to be as <em>small as possible</em> to make parsing efficient.</p></td>
</tr>
<tr>
<td style="width: 16%"><p><strong>NotOnClitics</strong></p></td>
<td><p><img src="../../../assets/images/User_Interface/Menus/Parser/CheckBoxBlackCkMk.png" /></p></td>
<td><p><img src="../../../assets/images/User_Interface/Menus/Parser/CheckBoxBlackCkMk.png" /> means the set of phonological rules will not be applied to clitics.</p>
<p><img src="../../../assets/images/User_Interface/Menus/Parser/CheckBoxNoCkMk.png" /> means the set of phonological rules will be applied to clitics.</p></td>
</tr>
<tr>
<td style="width: 16%"><p><strong>NoDefaultCompounding</strong></p></td>
<td><p><img src="../../../assets/images/User_Interface/Menus/Parser/CheckBoxNoCkMk.png" /></p></td>
<td><p><img src="../../../assets/images/User_Interface/Menus/Parser/CheckBoxNoCkMk.png" /> means the parser will use default compound rules if you have not defined overt compound rules.</p>
<p><img src="../../../assets/images/User_Interface/Menus/Parser/CheckBoxBlackCkMk.png" /> means no default compounding rules will be used.</p></td>
</tr>
<tr>
<td style="width: 16%"><p><strong>MaxRoots</strong></p></td>
<td style="width: 19%"><p>2</p></td>
<td style="width: 65%"><p>The maximum number of roots that may appear in a single well-formed word. The default is 2.</p>
<p>Any lexical entry with a morpheme type of root, bound root, stem or bound stem is considered to be a root as far as this parameter is concerned.</p>
<p>You will only need to change it if you can have three or more roots that can compound in a single well-formed word. The maximium value you can set is 10, but you will want this to be as <em>small</em> as possible to make parsing efficient.</p></td>
</tr>
<tr>
<td style="width: 16%"><p><strong>AcceptUnspecifiedGraphemes</strong></p></td>
<td><p><strong><img src="../../../assets/images/User_Interface/Menus/Parser/CheckBoxNoCkMk.png" /></strong></p></td>
<td><p><img src="../../../assets/images/User_Interface/Menus/Parser/CheckBoxNoCkMk.png" /> means the HC parser requires every Unicode character that occurs in the <strong>Lexeme Form</strong> <a href="../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Lexeme_Form_field.md">field</a> of any entry in the Lexicon to be included in the <strong>Grapheme</strong> <a href="../../Field_Descriptions/Grammar/Phonemes_fields/representation_field_phonemes.md">field</a> of one of the Phonemes in the project. If not, an error message appears indicating a character is not recognized and any entry that has that character will be ignored by the parser.</p>
<p><img src="../../../assets/images/User_Interface/Menus/Parser/CheckBoxBlackCkMk.png" /> means the HC parser is more lenient:</p>
<ul>
<li><p>It will attempt to parser wordforms that contain undefined characters, but the results may be meaningless.</p></li>
<li><p>It will not display error messages about unrecognized characters.</p></li>
</ul>
<blockquote>
<p></p>
<ul>
<li><p><img src="../../../assets/images/User_Interface/Menus/Parser/CheckBoxBlackCkMk.png" /> is not recommended as a long-term strategy, but it may be helpful in the short-term under certain circumstances. The primary advantage is to prevent error messages from appearing in <a href="Try_a_word.md">Try a Word</a> that can make it difficult to scroll down quickly to the details about the attempted parse.</p></li>
<li><p>If you are not ready to fix the errors and when the errors are not relevant to the wordform being parsed, debugging might be easier when this parameter selected (<img src="../../../assets/images/User_Interface/Menus/Parser/CheckBoxBlackCkMk.png" />).</p></li>
</ul>
</blockquote></td>
</tr>
<tr>
<td style="width: 16%"><p><strong>GuessRoots</strong></p></td>
<td><p><img src="../../../assets/images/User_Interface/Menus/Parser/CheckBoxBlackCkMk.png" /></p></td>
<td><p><img src="../../../assets/images/User_Interface/Menus/Parser/CheckBoxBlackCkMk.png" /> means that for words that do not have any analyses, the HC parser will attempt to <a href="About_the_Novel_Root_Guesser.md">guess</a> which portion of the word is the root, based on the current setup of the parser.</p>
<p>To guess roots, you need to <a href="../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Create_a_Template_Entry.md">create</a> one or more <em>pattern-matching entries</em> in the Lexicon. For the Lexeme Form, create a pattern from the natural classes that have been defined.</p>
<p>The resulting guesses will be presented as possible analyses. The user can approve one to indicate which one is correct. Then, you can manually create an entry in the Lexicon for the guessed root with the <strong>New Entry</strong> dialog box.</p></td>
</tr>
<tr>
<td style="width: 16%"></td>
<td></td>
<td><p>Note</p>
<ul>
<li><p>If you have no Lexeme Forms that are pattern-matching entries, then root guessing will not happen even when <strong>GuessRoots</strong> is selected.</p></li>
<li><p>When the HC parser does the unapplication process on a word with no analyses, it will take all of the constraints of the pattern-matching entry into account as it tries to determine what affixes are on this word, and what the remaining root is.</p></li>
<li><p>Recommendation: select <img src="../../../assets/images/User_Interface/Menus/Parser/CheckBoxBlackCkMk.png" /> <strong>NoDefaultCompounding</strong> to reduce the number of unhelpful guesses.<code></code></p></li>
</ul></td>
</tr>
<tr>
<td style="width: 16%"><p><strong>MergeAnalyses</strong></p></td>
<td><p><img src="../../../assets/images/User_Interface/Menus/Parser/CheckBoxBlackCkMk.png" /></p></td>
<td><p>This check box was added for performance considerations. If selected, which is the default, equivalent analyses are merged.</p></td>
</tr>
<tr>
<td style="width: 16%"><p><strong>MaxAlternatives</strong></p></td>
<td><p>0</p></td>
<td><p>This parser can sometimes take minutes or hours to parse a word.<br />
One possible solution to speed it up is to limit the number of alternatives that it considers by entering a non-zero value to <strong>MaxAlternatives</strong>. If that value is exceeded, then the parser produces an error for that word.<br />
Entering 1000 is similar to setting a timeout of 1 second depending on the grammar and the machine."<br />
The same results are produced each time you run it as long as the grammar stays the same.<br />
0, which is the default, means don't set a limit.<br />
You might want to <a href="../../../Overview/Technical_support.md">get more help</a>.</p></td>
</tr>
<tr>
<td style="width: 16%"><p><strong>Strata</strong></p></td>
<td></td>
<td><p><strong>See</strong>: <a href="Strata_as_a_String_in_the_Hermit_Crab_properties.md">Strata as a string in the Hermit Crab parser properties</a></p></td>
</tr>
<tr>
<td style="width: 16%"><p><strong>Set max applications of HC Compound Rules. </strong></p></td>
<td></td>
<td><p><strong>See:</strong> <a href="MaxApps_dialog_box.md">MaxApps dialog box</a>.</p></td>
</tr>
</tbody>
</table>

> [!TIP]
>
> - 
>
> - A warning message may appear if you enter very large parameter values, such as "50,000" MaxNulls. FieldWorks will reduce large values to more reasonable values.
>
> - It is recommended that you record the initial settings *before* you make any changes. If you make unsuitable changes to the settings, you may need to change the settings back to the initial settings.
>
> - For more information, on the **Help** menu, point to **Resources**, and then click **Introduction to Parsing**.

## Related topics
[Parser menu overview](Parser_menu_overview.md)

[Parsing words overview](Parsing_words_overview.md)
