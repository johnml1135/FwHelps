---
title: "Using Choose Items dialog box"
source_title: "Using Choose Items dialog box"
breadcrumb:
  - "Basic Tasks"
  - "Filtering data"
  - "Using Choose Items dialog box"
source: "Basic_Tasks/Filtering_data/Using_Choose_Items_dialog_box.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Basic_Tasks/Filtering_data/Using_Choose_Items_dialog_box.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Choose Items dialog box"
  - "using"
  - "Use or Using:Using Choose Items dialog box"
related:
  - "Basic Tasks overview -> ../Basic_Tasks_overview.md"
  - "Bulk Edit overview -> ../../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md"
  - "Filtering data overview -> filtering_data_overview.md"
  - "Filter Texts & Words -> filter_Texts_Words.md"
  - "Examples of combinations of regular expressions -> examples_of_combinations_of_regular_expressions.md"
  - "Examples of regular expressions -> Examples_of_Regular_Expressions.md"
fw_help_version: "9.3"
page_heading: "Using the Choose Items dialog box"
type: "topic"
content_hash: "sha256:5d6730ba2816de3c"
---

# Using Choose Items dialog box

*Basic Tasks › Filtering data*

The **Choose Items** dialog box is available when you [filter data](filter_data.md) on a column that is populated by (corresponds to) a [list reference field](../../User_Interface/Field_Descriptions/Field_Types/List_reference_field.md) (such as **Morph Type** or **Semantic Domains**). If the corresponding list has no list items, then this dialog box is empty.

1.  Select one of the following logic options (as available):

    - **Any checked item**

      This option sets the logic to display any selected item.

    - **No checked item**

      This option sets the logic to hide any selected item.

    - **All Checked items**

      This option sets the logic to display all items that match *all* the selected item(s). Entries, senses and so on that match all the selected items *and possibly other* cleared items are displayed.

    - **Exactly checked items**

      This option sets the logic to display *only* items that match *exactly* the selected item(s). Entries, senses and so on that have the selected item or set of items, but also additional items that are cleared are *not* displayed as they do not match *exactly* the selected item or set of selected items.

2.  Select or clear the check boxes as follows:

    - Select or clear the check box for those items (excluding subitems) you want to display or hide according to the logic you specified.

    - Use `Ctrl+click` to select the check box for the item and any subitems you want to display.

    - Clear one or more check box.

3.  Click **OK**.

> [!NOTE]
>
> - For columns that can contain only *one* list item, the dialog box contains only the **Any checked item** and **No check item** logic options.
>
>   Example: the **Morph Type** column in **Bulk Edit Entries**.
>
> - For columns that can contain *multiple* list items, the dialog box also includes the **All Checked items** and **Exactly check items** logic options.
>
>   Example: the **Semantic Domains** column in **Bulk Edit Entries**.

## Related topics
[Basic Tasks overview](../Basic_Tasks_overview.md)

[Bulk Edit overview](../../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md)

[Filtering data overview](filtering_data_overview.md)

[Filter Texts & Words](filter_Texts_Words.md)

[Examples of combinations of regular expressions](examples_of_combinations_of_regular_expressions.md)

[Examples of regular expressions](Examples_of_Regular_Expressions.md)
