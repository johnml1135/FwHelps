---
title: "Bulk Click Copy"
source_title: "Bulk Click Copy"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Bulk Edit Entries"
  - "Bulk Click Copy"
source: "Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_Click_Copy.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_Click_Copy.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Bulk Edit Entries:Bulk Click Copy"
  - "Click Copy"
  - "Bulk Edit"
  - "Copy:Bulk Copy"
related:
  - "Bulk Edit overview -> bulk_edit_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:0427634951d11467"
---

# Bulk Click Copy

*Using Tools › Lexicon tools › Bulk Edit Entries*

In [Bulk Edit Entries](Bulk_Edit_Entries_overview.md), the **Click Copy** tab features allow you to copy some of the content in one field to another field. You do this simply by clicking the word or string you want to copy. This allows you automatic reordering of phrases depending on the word you click.

1.  In the **Navigation** **Pane**, click **Lexicon**, and then click **Bulk Edit Entries**.

2.  Click the **Click Copy** tab.

3.  Do one or more of the following to display and then select the senses or entries you will change:

    - [Use](../../../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) the **Configure Columns** dialog box to hide/show/move columns and select the writing systems, if permitted.

      Show the fields that contain the *source* information and the *target* fields. Only fields displayed as columns are available for selection in the **Target Field** box, and you can only copy into columns that are [text fields](../../../User_Interface/Field_Descriptions/Field_Types/Single_line_text_field.md), not into [list reference fields](../../../User_Interface/Field_Descriptions/Field_Types/List_reference_field.md).

    - [Filter](../../../Basic_Tasks/Filtering_data/filtering_data_overview.md) or [sort](../../../Basic_Tasks/Sorting_data/Sorting_data_overview.md) the data to display only applicable senses or entries.

4.  In the **Bulk Edit Operation** pane, do the following:

    - In the **Target Field** box, select the field into which you want to paste what you will click.

      If necessary, [configure the columns](../../../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) to display the desired target field.

    - In the **Copy** area, to copy *one* word, select **Word**; to copy the *entire string* (phrase) of content, select **String, reordered at word clicked**.

    - In the **If** **target** **is not empty** area, the default selection is **Append, separated by**. If you want to append the copied content to existing content, then enter punctuation (semicolon, comma, or similar) in the box as a separator, if necessary. Otherwise, select **Overwrite**.

5.  In a column, except the field specified in the **Target Field** box, click the word or string you want to copy. See **Tip** below.

    The word or string is copied into the column selected in the **Target Field** box.

    The changes are saved as you click.

> [!TIP]
>
> - The *reorder* feature automatically reorders words after the word you click.
>
>   For example, to copy is "`to be happy`," you can click "`happy`" to yield "`happy, to be`" or click "`be`" to yield "`be happy, to`." If you click "`to`" the phrase is copied without any reordering.
>
> - If you selected **Append**, you can click the source phrase as many times as necessary to get the desired word order in the target field.
>
> - In **Bulk Edit Entries**, the **Reversals** column is editable when it is selected as the **Target** field in the **Click Copy** tab. This allows you to enter a reversal entry or subentry, or edit existing ones. In a row, if you separate the forms with a semi-colon (**;**) this adds multiple reversal entries to the lexical entry, but if you separate multiple forms with a colon (**:**), this adds a reversal entry and subentry.

## Related topics
[Bulk Edit overview](bulk_edit_overview.md)
