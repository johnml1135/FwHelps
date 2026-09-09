---
title: "Parser menu overview"
source_title: "Parser menu overview"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Parser"
  - "Parser menu overview"
source: "User_Interface/Menus/Parser/Parser_menu_overview.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Parser/Parser_menu_overview.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Parser"
  - "Parser:Parser menu overview"
  - "Try a Word"
  - "Menus"
  - "Parsing Elsewhere"
  - "Active:Parser menu overview"
  - "Parse words:Parser menu overview"
  - "Parse words"
  - "Parameters"
  - "Parser Development mode"
  - "color used in"
  - "Background colors:Parser Menu overview"
  - "Background colors"
related:
  - "Delete an Analysis -> ../../../Using_Tools/Texts_&_Words_tools/Word_Analyses/Delete_an_analysis.md"
  - "Menus overview -> ../Menus_overview.md"
  - "Parsing words overview -> Parsing_words_overview.md"
  - "Solve performance problems -> ../../../Overview/Solve_performance_problems.md"
  - "Toolbars overview -> ../../Toolbars/Toolbars_overview.md"
fw_help_version: "9.3"
type: "index"
content_hash: "sha256:1746e1a70d52c041"
---

# Parser menu overview

*User Interface › Menus › Parser*

There are various ways to [start the selected parser](Start_or_Stop_Parser.md), so there is not a specific "Start" command on the **Parser** menu.

Use these **Parser** menu commands:

<table style="left: 0px; top: 75px; vertical-align: Center;">
<tbody>
<tr style="vertical-align: center; height: 20px;">
<th style="width: 50%"><p>To</p></th>
<th style="width: 40%"><p>Click</p></th>
<th style="width: 10%"><p>Priority</p></th>
</tr>
&#10;<tr style="vertical-align: center; height: 30px;">
<td style="width: 50%"><ul>
<li><p>Start the currently selected parser and parse <em>all</em> the words in the <a href="../../../Using_Tools/Texts_&amp;_Words_tools/Word_list_overview.md">word list</a></p></li>
</ul></td>
<td style="width: 40%"><p><strong>Parse all words</strong></p>
<p>or <a href="Reparse_all_words.md">Reparse all words</a></p></td>
<td style="width: 10%"><p>Low</p></td>
</tr>
<tr style="vertical-align: center; height: 30px;">
<td style="width: 50%"><ol>
<li><ul>
<li><p>Reload grammar and lexical information used by the selected parser</p></li>
</ul></li>
</ol></td>
<td style="width: 40%"><p><strong>Reload Grammar/Lexicon</strong></p></td>
<td style="width: 10%"><p>(pauses parser)</p></td>
</tr>
<tr>
<td style="width: 50%"><ul>
<li><p>Stop the parser</p></li>
</ul></td>
<td style="width: 40%"><p><strong>Stop Parser</strong></p></td>
<td style="width: 10%"><p>-</p></td>
</tr>
<tr>
<td style="width: 50%"><ul>
<li><p>Start and run the currently selected parser in a dialog box so that a word is parsed, with detailed steps the parser tried.</p></li>
</ul></td>
<td style="width: 40%"><p><img src="../../../assets/images/User_Interface/Menus/Parser/TryAwordIcon.png" /> <a href="Try_a_word.md">Try a Word</a></p></td>
<td style="width: 10%"><p>High</p></td>
</tr>
<tr>
<td style="width: 50%"><ul>
<li><p>Start or run the currently selected parser to parse the words in the text that is <em>currently displayed</em> in <strong>Interlinear Texts</strong></p></li>
</ul></td>
<td style="width: 40%"><p><a href="parse_words_in_text.md">Parse Words in Text</a></p></td>
<td style="width: 10%"><p>Medium</p></td>
</tr>
<tr>
<td style="width: 50%"><ul>
<li>To parse only the words in text that don't yet have approved analyses.</li>
</ul></td>
<td style="width: 40%"><p><a href="Parse_Unapproved_Word_in_Text.md">Parse Unapproved Words in Text</a></p></td>
<td style="width: 10%"><p>Medium</p></td>
</tr>
<tr>
<td style="width: 50%"><ul>
<li><p>Start or run the currently selected parser to parse only the <em>current</em> word (<strong>Word List Concordance</strong>, <strong>Word Analyses</strong> or <strong>Bulk Edit Wordforms</strong>)</p></li>
</ul></td>
<td style="width: 40%"><p><a href="Parse_Current_Word.md">Parse Current Word</a></p></td>
<td style="width: 10%"><p>High</p></td>
</tr>
<tr>
<td style="width: 50%"><ul>
<li><p>Clear current parser analyses and reset <a href="../../Field_Descriptions/Texts_&amp;_Words/Parse_result_field.md">Parse result fields</a></p></li>
</ul></td>
<td style="width: 40%"><p><a href="Clear_current_parser_analyses.md">Clear Current Word's Parser Analyses</a></p></td>
<td style="width: 10%"><p>-</p></td>
</tr>
<tr>
<td style="width: 50%"><ul>
<li>To check the parsing status of a set of words, point to <strong>Run Tests</strong>, and then click one of these options:</li>
</ul></td>
<td style="width: 40%"><ul>
<li><p><strong>On Current Text</strong></p></li>
<li><p><strong>On Genre</strong></p></li>
<li><p><strong>On All Texts</strong></p></li>
<li><p><strong>Show Test Reports...</strong></p></li>
</ul>
<p>See: <a href="Parser_Test_Reports.md">Parser Test Reports</a>.</p>
<ul>
<li><p><strong>Updates Word Analyses</strong></p></li>
</ul></td>
<td style="width: 10%"><p>Medium</p></td>
</tr>
<tr style="vertical-align: center; height: 30px;">
<td style="width: 50%"><ul>
<li><p>To choose a parser, point to <strong>Choose Parser</strong>, and then click:</p></li>
</ul></td>
<td style="width: 40%"><p><a href="Parsing_words.md">Default Parser (XAmple)</a><em><br />
or</em><strong> </strong><br />
<a href="Parsing_words_(HermitCrab).md">Phonological Rule-based Parser (Hermit Crab)</a></p></td>
<td style="width: 10%"><p>-</p></td>
</tr>
<tr>
<td style="width: 50%"><ul>
<li>Choose one of these interlinear <a href="About_Parser_Modes.md">modes</a>:</li>
</ul></td>
<td style="width: 40%"><ul>
<li><strong>Text Glossing</strong></li>
<li><strong>Parsing Development</strong></li>
</ul></td>
<td style="width: 10%"></td>
</tr>
<tr style="vertical-align: center; height: 30px;">
<td style="width: 50%"><ul>
<li><p>Change parser parameters</p></li>
</ul></td>
<td style="width: 40%"><p><a href="Edit_Parser_Parameters.md">Edit Parser Parameters</a></p></td>
<td style="width: 10%"><p>-</p></td>
</tr>
</tbody>
</table>

## About Priority

Parsing is done on a priority basis. The parser will pause from working on lower-priority operations and give priority to any parse operation that has a higher priority. After the [status bar](../../Toolbars/status_bar.md) displays **Updating Grammar and Lexicon**, it displays the number of words left to parse in each priority with a queue order of *low/medium/high* ([example](Parser_status_example.md)).

If you change grammar or lexical data used by the parser, you can use **Reload Grammar/Lexicon** to make the updated information available to the parser. The parser pauses, so you will need to click **Reparse all words**.

## About Updates Word Analyses

The purpose of **Run Tests** is to be able to learn the current parsing status of a set of words, with the option to leave contents of the **Word Analyses** [view](../../../Using_Tools/Texts_&_Words_tools/Word_Analyses/Word_Analyses_overview.md) unchanged. (The **Analyze** [tab](../../../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/Analyze_Text_overview.md) is another view of those same data.)

- When this option is selected (![](../../../assets/images/CheckMark%20in%20RightClick%20Menu.png)), the **Run Tests** parse results are presented in the [report](Parser_Test_Reports.md) table and are also recorded in the **Word Analyses** [view](../../../Using_Tools/Texts_&_Words_tools/Word_Analyses/Word_Analyses_overview.md), and as a consequence they also appear in the **Analyze** [tab](../../../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/Analyze_Text_overview.md).

It is just as if you had run, for example, **Parse Words in Text** (or **Parse all words**, **Reparse all words**, **Parse Unapproved Words in Text**, and **Parse Current Word**, but *not* **Try a Word**). In this case, you might think of the **Run Tests** commands as similar to a bulk application of **Try a Word**, with the added effect that the contents of the **Word Analyses** view are also updated, which in turn affects what appears in the **Analyze** tab.

The default setting is that this option is selected (![](../../../assets/images/CheckMark%20in%20RightClick%20Menu.png)).

- When this option is *not* selected, no changes are made to the contents of the **Word Analyses** view, so nothing changes in the **Analyze** tab. Only the [report](Parser_Test_Reports.md) table appears. You might consider this as being similar to using the **Try a Word** tool but on a set of wordforms all at once.

> [!NOTE]
>
> - [About Interlinear Modes](About_Parser_Modes.md) provides information about the two modes and colors you might see.
>
> - [About parser parameters](About_parser_parameters.md) provides information about the parameters.
>
> - If parsing takes an unusually long time, [generate a grammar sketch](../../../Using_Tools/Grammar_tools/Grammar_Sketch/Generate_a_Grammar_Sketch.md) and examine the **Residue** section for under-specified affix data. The more specific data you provide the parser, the faster it can parse.
>
> - The **Try a Word** feature provides the following:
>
>   - A way to see what *analyses* (if any) the parser will produce for an arbitrary word
>
>   - A way to see the *steps* the parser went through to produce an analysis
>
>   - A way for you to try and determine *why* the parser is not producing an expected analysis
>
>   - The **Try a Word** dialog box shows the status of that parse *separately* from the parser status displayed on the status bar.
>
> <!-- -->
>
> - You can make a rule available (Active) or unavailable to parsers.**\
>   See:** [Active field (Ad hoc Rules)](../../Field_Descriptions/Grammar/Ad_hoc_Rules_fields/Active_field_Ad_Hoc_Rules.md), [Active field (Compound Rules)](../../Field_Descriptions/Grammar/Compound_Rules_fields/Active_field_Compound_Rules.md), or [Active field (Phonological Rules)](../../Field_Descriptions/Grammar/Phonologocial_Rules_fields/Active_field_(Ph_Rules).md).
>
> - You can make an affix template table available (Active) or unavailable to parsers.**\
>   See:** [Active field (Affix Templates)](../../Field_Descriptions/Grammar/Category_Edit_fields/Active_field_templates.md).
>
> <!-- -->
>
> - **See Also:** [About the Novel Root Guesser](About_the_Novel_Root_Guesser.md) and the **MaxApps** [dialog box](MaxApps_dialog_box.md).

## Related topics
[Delete an Analysis](../../../Using_Tools/Texts_&_Words_tools/Word_Analyses/Delete_an_analysis.md)

[Menus overview](../Menus_overview.md)

[Parsing words overview](Parsing_words_overview.md)

[Solve performance problems](../../../Overview/Solve_performance_problems.md)

[Toolbars overview](../../Toolbars/Toolbars_overview.md)
