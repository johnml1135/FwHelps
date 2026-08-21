---
title: "Fill in the Pronunciation field"
source_title: "Fill in the Pronunciation field"
breadcrumb:
  - "Lexicography Tasks"
  - "Fill in the Pronunciation field"
source: "Lexicography_Tasks/Fill_in_the_Pronunciation_Field.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Lexicography_Tasks/Fill_in_the_Pronunciation_Field.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Bulk Edit Entries:Fill in the Pronunciation field"
  - "Lexicography tasks"
  - "IPA:Fill in the Pronunciation field"
related:
  - "Bulk Edit overview -> ../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md"
  - "Lexicography Tasks overview -> Dictionary_and_Lexicon_overview.md"
  - "Using regular expressions assistance -> ../Basic_Tasks/Filtering_data/Using_regular_expressions_assistance.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:98e9169022483121"
---

# Fill in the Pronunciation field

*Lexicography Tasks*

Use **Bu****lk** **Copy** to copy the **Citation Form** or **Lexeme Form** field content into the [Pronunciation field](../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Pronunciation_field.md). Then, use **Process** to convert each letter (or digraph) in the orthography into its corresponding IPA character. If necessary, you can use **Bulk Replace** to fix exceptions to the general rule.

1.  In the **Navigation Pane**, click **Lexicon**, and then click **Bulk Edit Entries**.

2.  [Use](../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) the **Configure Columns** dialog box to hide/show/move columns (fields) and select writing systems, if permitted. Show the **Citation Form** or **Lexeme Form** fields, and the **Pronunciation** field.

3.  [Filter](../Basic_Tasks/Filtering_data/filtering_data_overview.md) or [sort](../Basic_Tasks/Sorting_data/Sorting_data_overview.md) the data to display only applicable entries.

4.  Use the [Bulk Copy](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_Copy.md) tab to copy the citation or lexeme form into the **Pronunciation** field:

    - Click the **Bulk Copy** tab.

    - In the **Source Field** box, select **Citation Form** or **Lexeme Form**.

    - In the **Target Field** box, select **Pronunciation**.

    - In the **If the Target field is not empty** area, click the applicable options, considering if you want to overwrite any existing content in the **Pronunciation** fields.

    - In the left column, [select the rows](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/select_rows.md) you want to change.

    - Click **Preview**, review the pending changes, and then click **Apply**.

5.  [Use](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_Process_Entries.md) the **Process** tab features to convert each letter (or digraph) in the orthography into its corresponding IPA character (English examples: `make` = ![](../assets/images/Lexicography_Tasks/makephon.gif); `stitch` = ![](../assets/images/Lexicography_Tasks/stitchphon.gif).):

    - Click the **Process** tab.

    - Click the **Setup** button and then [choose the processor](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Using_Setup_Processor_dialog_box.md) (*not* supplied with FieldWorks) in the **Setup Processor** dialog box, or select the processor in the **Process** box.

    - [Select the rows](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/select_rows.md) you want to change.

    - Click **Preview**, review the pending changes, and then click **Apply**.

6.  [Use](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_replace.md) the **Bulk Edit** tab to fix any exceptions to the general rule.

> [!TIP]
>
> - For additional information about the purpose of this topic or when it may be of use to you, on the [Help](../User_Interface/Menus/Help/Help_overview.md) menu, point to **Resources** and then click **Introduction to Lexicography**.

## Related topics
[Bulk Edit overview](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md)

[Lexicography Tasks overview](Dictionary_and_Lexicon_overview.md)

[Using regular expressions assistance](../Basic_Tasks/Filtering_data/Using_regular_expressions_assistance.md)
