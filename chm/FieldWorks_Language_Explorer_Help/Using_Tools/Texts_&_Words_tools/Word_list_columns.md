---
title: "Word list columns"
source_title: "Word list columns"
breadcrumb:
  - "Using Tools"
  - "Texts & Words tools"
  - "Word list columns"
source: "Using_Tools/Texts_&_Words_tools/Word_list_columns.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Texts_%26_Words_tools/Word_list_columns.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Words columns"
  - "Word list columns"
related:
  - "Interlinear Texts overview -> Interlinear_Texts/texts_edit_overview.md"
  - "Filter Tests & Words -> ../../Basic_Tasks/Filtering_data/filter_Texts_Words.md"
  - "Merge word glosses -> Word_Analyses/Merge_word_gloss.md"
  - "Number of Texts Analyses (Entries or Senses) -> ../../Basic_Tasks/Configure_Columns/Number_of_Text_Analyses.md"
  - "Word Gloss field -> ../../User_Interface/Field_Descriptions/Texts_&_Words/Word_Gloss_field.md"
  - "Configure Interlinear Lines -> ../../User_Interface/Menus/Tools/Configure_interlinear_lines_dialog_box.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:c2107719541170f2"
---

# Word list columns

*Using Tools › Texts & Words tools*

Various columns options may be available for [display](../../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) in the various columnar panes related to the [word list](Word_list_overview.md).

<table width="100%">
<tbody>
<tr>
<th style="width: 23%"><p>Column Heading</p></th>
<th style="width: 19%"><p>Contains</p></th>
<th style="width: 58%"><p>Description</p></th>
</tr>
&#10;<tr>
<td style="width: 23%"><p><strong>Category</strong></p></td>
<td style="width: 19%"><p>Category (or Part of Speech) of the word gloss</p></td>
<td style="width: 58%"><p>From the <strong>Word Cat</strong> line in the word focus box</p></td>
</tr>
<tr>
<td style="width: 23%"><p><strong>Conflicting Opinions</strong></p></td>
<td style="width: 19%"><p>Numerical values</p></td>
<td style="width: 58%"><ul>
<li><p><strong>0</strong> means the parser and the human user are in agreement regarding all analyses that exist. (That is, when the conflicting opinions value is zero, there cannot be any analyses that are known to the parser, but that are not known to the user. If the user has any approved analyses, then the <a href="../../User_Interface/Field_Descriptions/Texts_&amp;_Words/Parse_result_field.md">parser result</a> is <strong>Successful</strong> for all of these. If the user has any disapproved analyses, then the parser will agree by producing a parser result of <strong>Failure</strong> for all of these.)</p></li>
<li><p><strong>1</strong>, <strong>2</strong>, and so on, indicates the number of times that the parser and the user are not in agreement. For example, if <strong>Failure</strong> or <strong>Untested</strong> appears in a user approved analysis, this is a conflict of opinions.</p></li>
</ul>
<p><strong> Tip:</strong> Any number other than <strong>0</strong> (zero) in this column means there is additional work to do on that word.</p></td>
</tr>
<tr>
<td style="width: 23%"><p><strong>Form</strong></p></td>
<td style="width: 19%"><p>Words from <strong>Baseline</strong> tab text (or <a href="../../Beginning_Tasks/Importing_Data/Import_SFM_words_and_glosses/Import_Standard_Format_words_and_glosses.md">imported</a>)</p></td>
<td style="width: 58%"><p>This form comes from the <strong>Word</strong> line in the <a href="Interlinear_Texts/Word_Focus_Box_examples.md">word focus box</a>. The form appears as the label of the <a href="../../User_Interface/Field_Descriptions/Texts_&amp;_Words/wordform_field.md">top field</a> in the <strong>Wordform Analyses</strong> pane.</p>
<p>(Typically available for <a href="Bulk_Edit_Wordforms/Bulk_Edit_Wordforms_overview.md">bulk editing</a>.)</p></td>
</tr>
<tr>
<td style="width: 23%"><p><strong>Incomplete Analyses</strong></p></td>
<td style="width: 19%"><p><strong>Yes</strong> or <strong>No</strong></p></td>
<td style="width: 58%"><p><strong>Yes</strong> means that there is at least one analysis associated with the form (word) that is <em>not complete</em>, such as missing a <strong>Word Gloss</strong>. Content is required in all writing systems.</p>
<p><strong>No</strong> means all analyses are complete, in all writing systems.</p></td>
</tr>
<tr>
<td style="width: 23%"><p><strong>Number in Corpus</strong></p></td>
<td style="width: 19%"><p>Numerical values</p></td>
<td style="width: 58%"><p>The total number of times the form (word) is used in the texts.</p>
<p>For views with a <strong>Wordforms</strong> pane,</p>
<ul>
<li><p>words are <em>only</em> listed (and counted on the <a href="../../User_Interface/Toolbars/status_bar.md">Status bar</a>) <em>if the texts that contains them are</em> <a href="../../User_Interface/Toolbars/View_toolbar.md">selected for display</a>,</p></li>
<li><p>words that are only in texts which are not selected for display are <em>not</em> listed in the <strong>Wordforms</strong> pane (or counted on the Status bar).</p></li>
</ul></td>
</tr>
<tr>
<td style="width: 23%"><p><strong>Predicted Analyses</strong></p></td>
<td style="width: 19%"><p>Numerical values</p></td>
<td style="width: 58%"><p>The number of successful <a href="../../User_Interface/Menus/Parser/Parsing_words_overview.md">parses</a> of the word</p></td>
</tr>
<tr>
<td style="width: 23%"><p><strong>Spelling Status</strong></p></td>
<td style="width: 19%"><p><strong>Undecided</strong>, <strong>Correct</strong> or <strong>Incorrect</strong></p></td>
<td style="width: 58%"><p>From the <a href="../../User_Interface/Field_Descriptions/Texts_&amp;_Words/spelling_status_field.md">Spelling Status</a> field. (Typically available for <a href="Bulk_Edit_Wordforms/Bulk_Edit_Wordforms_overview.md">bulk editing</a>.)</p></td>
</tr>
<tr>
<td style="width: 23%"><p><strong>User Analyses</strong></p></td>
<td style="width: 19%"><p>Numerical values</p></td>
<td style="width: 58%"><p>The number of analyses for which the <strong>User Opinion</strong> is <a href="Word_Analyses/Specify_status_of_analysis.md">set</a> to <strong>Approve</strong></p></td>
</tr>
<tr>
<td style="width: 23%"><p><strong>Word Glosses</strong></p></td>
<td style="width: 19%"><p><strong>Word Gloss</strong> line contents</p></td>
<td style="width: 58%"><p><strong>Word Gloss</strong> line in the word focus box.</p>
<ul>
<li><p>If an analysis has multiple word glosses, they are separated with a <strong>/</strong> (forward slash). Commas separate word glosses from different analyses. See  <strong>Note</strong> below.</p></li>
</ul></td>
</tr>
<tr>
<td style="width: 23%"><p>Other Options</p></td>
<td style="width: 19%"><p>Content from</p></td>
<td style="width: 58%"><p>Description</p></td>
</tr>
<tr>
<td style="width: 23%"><p><strong>Abbreviation</strong></p></td>
<td style="width: 19%"><p><a href="../../User_Interface/Field_Descriptions/Texts_&amp;_Words/Abbreviation_field_Info.md">Abbreviation field</a></p></td>
<td style="width: 58%"><p><strong>Info</strong> tab <a href="Interlinear_Texts/Enter_text_metadata.md">metadata</a></p></td>
</tr>
<tr>
<td style="width: 23%"><p><strong>Comment</strong></p></td>
<td style="width: 19%"><p><a href="../../User_Interface/Field_Descriptions/Texts_&amp;_Words/Comment_field_info.md">Comment field</a></p></td>
<td style="width: 58%"><p><strong>Info</strong> tab metadata</p></td>
</tr>
<tr>
<td style="width: 23%"><p><strong>Genres</strong></p></td>
<td style="width: 19%"><p><a href="../../User_Interface/Field_Descriptions/Texts_&amp;_Words/Genres_field_Info.md">Genres field</a></p></td>
<td style="width: 58%"><p><strong>Info</strong> tab metadata</p></td>
</tr>
<tr>
<td style="width: 23%"><p><strong>Is Translation</strong></p></td>
<td style="width: 19%"><p><a href="../../User_Interface/Field_Descriptions/Texts_&amp;_Words/Text_is_a_translation_field_Info.md">Text is a Translation field</a> selection</p></td>
<td style="width: 58%"><p><strong>Info</strong> tab metadata</p>
<ul>
<li><p><strong>Yes</strong> indicates a check mark in the check box</p></li>
<li><p><strong>No</strong> indicates no check mark in the check box</p></li>
</ul></td>
</tr>
<tr>
<td style="width: 23%"><p><strong>Occurrence</strong></p></td>
<td style="width: 19%"><p>Search results in their contexts</p></td>
<td style="width: 58%"><p>The search text or value is typically displayed in a <strong>bold</strong> font. Exceptions to this include the use of some <a href="../../Basic_Tasks/Filtering_data/About_Regular_Expressions.md">regular expressions</a> in the <a href="Concordance/specify_concordance_criteria.md">search criteria</a>.</p></td>
</tr>
<tr>
<td style="width: 23%"><p><strong>Ref</strong></p></td>
<td style="width: 19%"><p>Part of the text's <a href="../../User_Interface/Field_Descriptions/Texts_&amp;_Words/Title_field_Info.md">title</a> and numerical values</p></td>
<td style="width: 58%"><p>Example: <strong>Canoes 2:1</strong> means the occurrence came from a text entitled "Canoes ....", and is from the second paragraph, first sentence of that paragraph.</p>
<p>Texts <a href="../../User_Interface/Toolbars/Insert_toolbar.md">included</a> from other FieldWorks programs can include other numbers, such as chapter and verse, followed by the paragraph segment.</p></td>
</tr>
<tr>
<td style="width: 23%"><p><strong>Source</strong></p></td>
<td style="width: 19%"><p><a href="../../User_Interface/Field_Descriptions/Texts_&amp;_Words/Source_field_info.md">Source field</a></p></td>
<td style="width: 58%"><p><strong>Info</strong> tab metadata</p></td>
</tr>
<tr>
<td style="width: 23%"><p><strong>Title</strong></p></td>
<td style="width: 19%"><p><a href="../../User_Interface/Field_Descriptions/Texts_&amp;_Words/Title_field_Info.md">Title field</a></p></td>
<td style="width: 58%"><p><strong>Info</strong> tab metadata</p></td>
</tr>
</tbody>
</table>

> [!NOTE]
>
> - In the **Word Glosses** column, you may see empty spaces between forward slashes (/) or separator commas. This happens when the analysis has multiple [Word Gloss fields](../../User_Interface/Field_Descriptions/Texts_&_Words/Word_Gloss_field.md), but one or more is not used or a different writing system was used for one of the word glosses.
>
> - The [Statistics](Statistics_overview.md) tool gives information which includes word and sentence totals.

## Related topics
[Interlinear Texts overview](Interlinear_Texts/texts_edit_overview.md)

[Filter Tests & Words](../../Basic_Tasks/Filtering_data/filter_Texts_Words.md)

[Merge word glosses](Word_Analyses/Merge_word_gloss.md)

[Number of Texts Analyses (Entries or Senses)](../../Basic_Tasks/Configure_Columns/Number_of_Text_Analyses.md)

[Word Gloss field](../../User_Interface/Field_Descriptions/Texts_&_Words/Word_Gloss_field.md) (**Words**)

[Configure Interlinear Lines](../../User_Interface/Menus/Tools/Configure_interlinear_lines_dialog_box.md)
