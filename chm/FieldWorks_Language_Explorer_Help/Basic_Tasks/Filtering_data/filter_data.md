---
title: "Filter data"
source_title: "Filter data"
breadcrumb:
  - "Basic Tasks"
  - "Filtering data"
  - "Filter data"
source: "Basic_Tasks/Filtering_data/filter_data.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Basic_Tasks/Filtering_data/filter_data.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Filter:Filter data"
  - "Regular Expression:Filter data"
  - "Restrict"
  - "numerical values or dates"
  - "numerical values or dates:Filter data"
  - "Columns"
related:
  - "Filtering data overview -> filtering_data_overview.md"
  - "Using filter for -> Using_Filter_for.md"
  - "Using regular expressions assistance -> Using_regular_expressions_assistance.md"
  - "Word list columns -> ../../Using_Tools/Texts_&_Words_tools/Word_list_columns.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:1476f38d5a491331"
---

# Filter data

*Basic Tasks › Filtering data*

1.  If necessary, use the [Configure Columns](../Configure_Columns/Configure_Columns_overview.md) dialog box to add or remove columns in the displayed view.

2.  In the column on which you want to filter data, click the [down arrow](Filter_data_down_arrow_menu_pic.md) just under a column heading.

    A list appears with filter options you can select. (**Show All** normally appears.) The options in the list vary depending on the content of the column.

3.  In the list, select any of the following *as available* in the column:\
    **Show All**, **Blanks**, **Non-blanks**, **Spelling Errors**, **Filter for**, **Yes**, **No**, **Choose**, **Restrict**, **Greater than 0**, **Correct**, and so on.

    One of the following happens:

    - The displayed content changes to reflect the current selection.

    - The [Filter for items containing](Using_Filter_for.md) dialog box appears so you can specify filter criteria, including [regular expressions](About_Regular_Expressions.md), if desired.

    - The [Choose Items](Using_Choose_Items_dialog_box.md) dialog box appears so you can select items ([list](../../Using_Tools/Lists_tools/Lists_overview.md) items) to filter for and logic options.

      This dialog box is available if the column is populated by (corresponds to) a [list reference field](../../User_Interface/Field_Descriptions/Field_Types/List_reference_field.md).

    - The [Restrict to items with](Using_Restrict_dialog_box.md) (**values** or **dates**) dialog box appears so you can select a restriction criterion, and enter a value or a date.

      This dialog box is available if the column displays a numerical value or date.

> [!TIP]
>
> - The filter options are available only if appropriate for the typical content in the field. For example, some fields do not include **Blanks** and **Non-blanks** as they always have content and these options would be meaningless.
>
> - You can [sort](../Sorting_data/Sorting_data_overview.md) and filter data simultaneously.
>
> - The [status bar](../../User_Interface/Toolbars/status_bar.md) indicates when a filter is active.
>
> - **Spelling Status** columns contain unique filter options:\
>   **Undecided**, **Correct**, **Incorrect**, **Exclude Undecided**, **Exclude Correct**, and **Exclude Incorrect**.
>
> - If you turn off [Show Vernacular Spelling Errors](../../User_Interface/Menus/Tools/Tools_overview.md), then some filter options are not displayed.
>
> - You can [choose texts](Choose_Texts.md) in the **Form** column in **Word List Concordance** and **Word Analyses**, and the **Title** column in **Interlinear Texts**.

## Related topics
[Filtering data overview](filtering_data_overview.md)

[Using filter for](Using_Filter_for.md)

[Using regular expressions assistance](Using_regular_expressions_assistance.md)

[Word list columns](../../Using_Tools/Texts_%26_Words_tools/Word_list_columns.md) (**Spelling Status**)
