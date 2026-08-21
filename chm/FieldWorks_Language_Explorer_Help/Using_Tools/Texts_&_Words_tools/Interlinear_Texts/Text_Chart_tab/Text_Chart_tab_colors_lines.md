---
title: "Text Chart tab colors and line weights"
source_title: "Text Chart tab colors and line weights"
breadcrumb:
  - "Using Tools"
  - "Texts & Words tools"
  - "Interlinear Texts"
  - "Text Chart tab"
  - "Text Chart tab colors and line weights"
source: "Using_Tools/Texts_&_Words_tools/Interlinear_Texts/Text_Chart_tab/Text_Chart_tab_colors_lines.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/Text_Chart_tab/Text_Chart_tab_colors_lines.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Colors"
  - "Colors:Text Chart tab colors and line weights"
  - "Chart"
  - "Discourse charting"
  - "Discourse charting:Text Chart tab colors and line weights"
  - "Text Chart tab"
  - "Text Chart tab:Text Chart tab colors and line weights"
  - "Green"
  - "cell background color"
related:
  - "About Text Chart \n tab -> About_Text_Chart_tab.md"
  - "Change Text Chart \n tab font attributes -> change_text_chart_font.md"
  - "Interlinear Texts \n overview -> ../texts_edit_overview.md"
  - "Text \n Chart tab columns and rows -> Text_Chart_tab_columns_and_rows.md"
  - "Text Chart tab overview -> Text_chart_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:2edf371c27ee23b1"
---

# Text Chart tab colors and line weights

*Using Tools › Texts & Words tools › Interlinear Texts › Text Chart tab*

In The **Text Chart** tab, various colors (and sometimes brackets) are used and line weights are used.

## Colors used with text data and metadata

- **Independent clauses are black.**

- \[Blue within square brackets\] marks dependent clauses.

  - *\[Blue numbers and letters within square brackets\]* mark, as a place holder, the underlying location of the dependent clause relative to the independent clause.

- <a href="" class="popupspot" style="color: #008000;">[Green, with a dotted underline, within square brackets] marks quoted speech, whether direct or indirect</a>.

  - \[Green numbers and letters within square brackets\] mark, as a place holder, the underlying location of the quoted speech clause.

- \[Purple within square brackets\] marks song clauses.

  - \[Purple numbers and letters within square brackets\] mark, as a place holder, the underlying location of the song clause.

- (Orange, within parentheses) marks grammatical information such as Verb TAM, pronoun types, and demonstrative types. The [abbreviations](../../../../User_Interface/Field_Descriptions/Lists/Text_Chart_Markers_fields/abbreviation_fld_tcmrkers.md) that appear are stored in [Lists](../../../../User_Interface/Field_Descriptions/Lists/Text_Chart_Markers_fields/Text_Chart_Markers_fields_overview.md).

- Gray colored font is used for word glosses.

When words occur out of their default word order (the order they appeared in the **Baseline** tab), the following convention is used:

- \[*Red, within square brackets*\] marks the word(s) as moved from its default position ([preposed from](Mark_as_preposed_from.md) or [postposed from](Mark_as_postposed_from.md)).

- *Pink \<\<* *or* *\>\>*, without brackets, mark the default position from which word(s) were moved.

> [!NOTE]
>
> - When cell contents are subject to *multiple marks,* one color may override another. For example, for a dependent clause which is *also* quoted speech, then green (quoted speech) will override blue (dependent clause). The square brackets continue to indicate the range of each, but may appear in a different color.
>
> - [Colors](../interlinear_views_colors.md) of program-proposed analyses are also seen in the text chart.

### Edited Baseline content:

- If you edit **Baseline** tab content after you inserted the words into a text chart, some of the more-complex edits can cause words to be removed from the chart and put back in the bottom pane. In this case, the following colors and features appear (you may need to *Refresh* (**F5**) the window to see them):

  - Green background color indicates the cells where the edited words belong to preserve word order.

  - Blue vertical bars separate edited words from other uncharted words in the bottom pane. You will need to [reinsert](reinsert_words_into_chart.md) them before you insert other uncharted words.

## Line weights

- The [Nucleus group](../../../Lists_tools/Text_Chart/default_chart_columns.md) is separated from the other groups with a darker line weight.

- Three different line weights are used for the horizontal lines above and below rows:

  - The lightest-weight line appears between clauses.

  - The mid-weight line appears between sentences.

  - The heavier-weight line appears between paragraphs.

You specify these as you [mark the last row](Mark_last_row.md) of sentence or paragraph.

## Related topics
[About Text Chart tab](About_Text_Chart_tab.md)

[Change Text Chart tab font attributes](change_text_chart_font.md)

[Interlinear Texts overview](../texts_edit_overview.md)

[Text Chart tab columns and rows](Text_Chart_tab_columns_and_rows.md)

[Text Chart tab overview](Text_chart_overview.md)
