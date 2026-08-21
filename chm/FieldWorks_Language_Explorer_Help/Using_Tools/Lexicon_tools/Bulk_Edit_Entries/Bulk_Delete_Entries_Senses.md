---
title: "Bulk delete entries or senses"
source_title: "Bulk delete entries or senses"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Bulk Edit Entries"
  - "Bulk delete entries or senses"
source: "Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_Delete_Entries_Senses.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_Delete_Entries_Senses.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Delete:Bulk delete entries or senses"
  - "Delete:Entries (multiple)"
  - "lexical"
  - "Bulk Edit Entries:Bulk delete entries"
  - "Bulk Edit Entries:Bulk delete senses"
  - "Sense:Delete a sense or subsense"
  - "Click Copy"
  - "Bulk Edit"
  - "Delete several lexical entries"
related:
  - "Bulk Edit Entries -> Bulk_Edit_Entries_overview.md"
  - "Bulk Edit overview -> bulk_edit_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:1ac3faaf392f02c0"
---

# Bulk delete entries or senses

*Using Tools › Lexicon tools › Bulk Edit Entries*

**Delete** tab features allow you to delete entire entries or senses, or only contents from fields.

1.  In the **Navigation** **Pane** click **Lexicon**, and then click **Bulk Edit Entries**.

2.  Click the **Delete** tab.

3.  [Use](../../../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) the **Configure Columns** dialog box to hide/show/move columns and specify writing systems, if permitted.

4.  [Filter](../../../Basic_Tasks/Filtering_data/filtering_data_overview.md) or [sort](../../../Basic_Tasks/Sorting_data/Sorting_data_overview.md) the data to display only applicable entries or senses.

5.  In the left column, [select the rows](select_rows.md) you want to delete or change.

6.  In the **Item to delete** box, select the item to delete.

    - Review the explanatory statement that appears to the right of the **Bulk Edit Operation** label. Make sure the deletion is what you intended. For example, will you delete content in *rows* or *columns*. Make a different selection if necessary.

7.  Click **Preview**, review the pending changes, and then click **Apply**.

    The entries, senses or field contents with a check mark in the left column are deleted.

> [!IMPORTANT]
>
> - Your selection in the **Item to delete** box determines if the main pane is an **Entries** or **Senses** view. **See:** [Bulk Edit overview](bulk_edit_overview.md).
>
> - The **Configure Columns** dialog box uses the ![](../../../assets/images/Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_Edit_Symbol.GIF) symbol to indicate the fields that *may be* available for bulk editing, depending on the operation you want to do. For example, you *cannot* delete content from some fields, such as **Morph Type**.
>
> - If you delete pronunciations, you can choose to delete content from [Pronunciation fields](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Pronunciation_field.md) (**Pronunciation** column). Alternatively, you can delete entire pronunciations, which includes the content in associated [CV Pattern](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/cv_pattern_field.md), [Tone](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Tone_field.md) and [Location](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Location_field.md) fields.
>
> <!-- -->
>
> - If you selected **Senses** in the **Item to delete** box, many of the check boxes at the left edge of the **Senses** pane become unavailable (![](../../../assets/images/Using_Tools/Lexicon_tools/Bulk_Edit_Entries/UnavailableCheckbox.PNG)). This is because those entries only have one sense, which *cannot* be deleted.
>
>   For entries with more than one sense, the check box for the top sense (**Sense 1**) is initially unavailable, but subsequent senses are available for deletion. If you clear a check box for a sense, then the check box for the top sense becomes available.
>
>   The default is that the top sense is retained unless you choose to keep another sense, at which point you can choose to delete the top sense.

## Related topics
[Bulk Edit Entries](Bulk_Edit_Entries_overview.md)

[Bulk Edit overview](bulk_edit_overview.md)
