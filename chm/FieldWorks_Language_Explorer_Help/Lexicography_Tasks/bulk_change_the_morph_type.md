---
title: "Bulk change the Morph Type"
source_title: "Bulk change the Morph Type"
breadcrumb:
  - "Lexicography Tasks"
  - "Bulk change the morph type"
source: "Lexicography_Tasks/bulk_change_the_morph_type.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Lexicography_Tasks/bulk_change_the_morph_type.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Bulk Edit Entries:Bulk change Morph Type"
  - "Lexicography tasks"
related:
  - "Bulk Edit overview -> ../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md"
  - "Lexicography Tasks overview -> Dictionary_and_Lexicon_overview.md"
  - "Using regular expressions assistance -> ../Basic_Tasks/Filtering_data/Using_regular_expressions_assistance.md"
fw_help_version: "9.3"
page_heading: "Bulk change Morph Type"
type: "topic"
content_hash: "sha256:bf7ad1f96069db8b"
---

# Bulk change the Morph Type

*Lexicography Tasks*

In [Bulk Edit Entries](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_Edit_Entries_overview.md), you can use the **List Choice** tab features to change the [morph type](../Using_Tools/Lists_tools/About_Morpheme_Types.md) for multiple entries at the same time.

1.  In the **Navigation** **Pane**, click **Lexicon**, and then click **Bulk Edit Entries**.

2.  Click the **List Choice** tab.

3.  [Use](../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) the **Configure Columns** dialog box to hide/show/move columns (fields) and select writing systems, if permitted. Show the **Headword** (or **Lexeme Form**) and **Morph** **Type** fields.

4.  [Filter](../Basic_Tasks/Filtering_data/filtering_data_overview.md) or [sort](../Basic_Tasks/Sorting_data/Sorting_data_overview.md) the data as needed. For example, to change the morph type of an idiom, you could filter the **Headword** field for those entries containing a space. To change the morph type of a derivative, you could filter the **Headword** field for those entries containing a derivational affix.

5.  In the left column, [select the rows](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/select_rows.md) you want to change.

6.  In the **Bulk Edit Operation** pane, do the following:

    - In the **Target Field** box, select **Morph** **Type**.

    - In the **Change To** box, select the morph type you want to assign to the selected entries.

7.  Click **Preview**, and then review the pending changes:

    - Review the selected entries to see if the fundamental type will change. Changes such as from *stem* to *suffixing interfix* is an example of a fundamental type change. These will cause a warning box to appear *after* you click **Apply**.

8.  Click **Apply**.

    - If the **Changing fundamental type** warning box appears, click **Cancel** to stop bulk edit process, or click **OK** to allow the changes.

    - If you clicked **Cancel**, [select](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/select_rows.md) different rows for bulk edit. Then you can bulk change the morph types in appropriate groups.

> [!TIP]
>
> - For additional information about the purpose of this topic or when it may be of use to you, on the [Help](../User_Interface/Menus/Help/Help_overview.md) menu, point to **Resources** and then click **Introduction to Lexicography**.

## Related topics
[Bulk Edit overview](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md)

[Lexicography Tasks overview](Dictionary_and_Lexicon_overview.md)

[Using regular expressions assistance](../Basic_Tasks/Filtering_data/Using_regular_expressions_assistance.md)
