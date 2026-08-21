---
title: "Bulk Edit overview"
source_title: "Bulk Edit overview"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Bulk Edit Entries"
  - "Bulk Edit overview"
source: "Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Bulk Edit Entries:Bulk Edit overview"
  - "Processor"
related:
  - "Configure Columns -> ../../../Basic_Tasks/Configure_Columns/Configure_Columns_overview.md"
  - "Lexicon overview -> ../Lexicon_overview.md"
fw_help_version: "9.3"
type: "index"
content_hash: "sha256:e9a8708bc006484c"
---

# Bulk Edit overview

*Using Tools › Lexicon tools › Bulk Edit Entries*

Bulk Edit tools allow you to change multiple items at the same time.

- **Lexicon**: [Bulk Edit Entries overview](Bulk_Edit_Entries_overview.md) and [Bulk Edit Reversal Entries overview](../Bulk_Edit_Reversal_Entries/bulk_edit_reversal_entries_overview.md) list tasks for lexical entries, senses, variants, allomorphs or reversal entries.

  - You will see various behaviors. For example, in the **List Choice** tab, depending on the settings of the list and list reference field, you may choose an item from a drop down list, or from a dialog box. Further, depending on the list reference field you may be able to select only one or multiple list items in the dialog box.

  - [Lexicography Tasks overview](../../../Lexicography_Tasks/Dictionary_and_Lexicon_overview.md) lists additional tasks.

- **Texts & Words**: [Bulk Edit Wordforms overview](../../Texts_&_Words_tools/Bulk_Edit_Wordforms/Bulk_Edit_Wordforms_overview.md) lists tasks for [wordforms](../../Texts_&_Words_tools/Word_list_overview.md).

You can use bulk edit tools in many different ways. Use the task topics listed in the overview topics (above) as examples.

> [!IMPORTANT]
>
> - In bulk edit tools, the [Target Field selection](Target_field_selection.md) determines the [Information bar](../../../User_Interface/Toolbars/information_bar_overview.md) label (**Entries**, **Senses**, and so on). It also determines how lexical information appears in the rows. Row contents can affect the following:
>
>   - The [Status bar](../../../User_Interface/Toolbars/status_bar.md) can show the current entry and total number of entries, *or* the current sense and total number of senses, and so on.
>
>   - Check boxes allow you to [select the rows](select_rows.md) you want to change. Their behavior may change:
>
>     Typically, each check box is selected or cleared independently. However, when an **Entries** view is [sorted](../../../Basic_Tasks/Sorting_data/Sort_data.md) on sense-level data, each sense is shown in an individual row and the check boxes in those rows are selected or cleared *as a set* for each entry. For example, if you select a row for one sense, *all* the rows for that entry receive a check mark.
>
>   - In some cases, the check boxes may be unavailable for selection. For example, you cannot [delete](Bulk_Delete_Entries_Senses.md) the last sense from most entries.
>
> - The **Configure Columns** dialog box uses the ![](../../../assets/images/Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_Edit_Symbol.GIF) symbol to indicate the fields that may be available as target fields (**Target Field** box). Fields without the symbol are typically available as source fields (**Source Field** box) or useful for sorting and filtering data.
>
>   Some fields with the ![](../../../assets/images/Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_Edit_Symbol.GIF) symbol may not be available in *all* boxes, such as in the **Item to delete** box (**Delete** tab). For example, you cannot bulk *delete* the **Morph Type** field contents, although you can bulk *change* them in **List Choice**.
>
> - There are many possible permutations of selections, [filters](../../../Basic_Tasks/Filtering_data/filter_data.md) and [sorts](../../../Basic_Tasks/Sorting_data/Sorting_data_overview.md) that change the row content and total number of rows.
>
>   **Example** (assumes *no* active filters):
>
>   Suppose the **Target Field** box selection is **Lexeme Form** (an entry-level field). The Information bar label is **Entries**.
>
>   - When *sorted* on an entry-level field, there is *one row for each entry*.
>
>     All the senses and other data for an entry are displayed in the same row and the total number of rows matches the number of entries.
>
>   - When *sorted* on a sense-level field, each sense appears in an *individual row*.
>
>     The total number of rows reflects the number of senses plus the number of entries without any senses (variants only). Data is repeated to complete the added rows.
>
>   - When *sorted* on an allomorph-level field, each allomorph appears in an *individual row*.
>
>     Each entry without any allomorphs appear in their own row; entries with one allomorph appear once; entries with more than one allomorph appear once *for each* allomorph. Data is repeated to complete the added rows.

## Related topics
[Configure Columns](../../../Basic_Tasks/Configure_Columns/Configure_Columns_overview.md)

[Lexicon overview](../Lexicon_overview.md)
