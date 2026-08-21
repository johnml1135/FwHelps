---
title: "Bulk change Publications"
source_title: "Bulk change Publications"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Bulk Edit Entries"
  - "Bulk change Publications"
source: "Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_change_publications.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_change_publications.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Bulk Edit Entries:Bulk change Publications"
  - "Publication:Publications"
  - "bulk change"
related:
  - "Bulk Edit overview -> bulk_edit_overview.md"
  - "Sorting data overview -> ../../../Basic_Tasks/Sorting_data/Sorting_data_overview.md"
  - "Specify publishable lexical data -> ../Lexicon_Edit/Specify_publishable_lexical_data.md"
  - "What is a publication? -> ../../../User_Interface/Field_Descriptions/Lists/Publications/What_is_a_Publication.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:a4454408bbc5b887"
---

# Bulk change Publications

*Using Tools › Lexicon tools › Bulk Edit Entries*

Publications stored in the **Publications** [list](../../Lists_tools/List_item_usage_table.md) are automatically displayed in *all* the **Publish** \<item\> **In** [fields](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Lexicon_Edit_fields_overview.md) in **Lexicon Edit**.

There is a [Publish Entry In](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Publication_Settings_flds/Publish_In_(Publication_Settings).md) field for the entire *entry*, a [Publish Pronunciation In](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Publish_In_(Pronunciations).md) field for each *publication*, a [Publish Sense In](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Publish_In_(Sense).md) field for each *sense*, a [Publish Example In](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Publish_In_(Example).md) field for each *example*, and a [Publish Picture In](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Publish_In_(Pictures).md) field for each picture. So, all entries, pronunciations, senses, examples and pictures are assumed to be [publishable](../Lexicon_Edit/Specify_publishable_lexical_data.md) by default.

In the various **Publish In** fields,

- keep (or display) a publication include the lexical data for *that* publication,

- remove a publication to exclude the lexical data for *that* publication.

Here is *one of many possible ways* you can do this with **Bulk Edit** features. In this sample task, suppose that you want to [export](../../../User_Interface/Menus/File/Export/Export_overview.md) lexical data for a pocket dictionary, and that this pocket dictionary publication must `not` include data marked as *offense*.

1.  [Create](../../Lists_tools/Create_new_publication.md) a new publication named **Pocket Dictionary**.

2.  In [Usages fields](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Usages_field.md) (**Lexicon Edit**), [choose](../Lexicon_Edit/Choose_Usages.md) **offensive** in each sense that contains offensive data.

3.  In the **Navigation** **Pane**, click **Lexicon**, and then click **Bulk Edit Entries**.

4.  Click the **List Choice** tab.

5.  [Use](../../../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) the **Configure Columns** dialog box to hide/show/move columns (fields) and select writing systems, if permitted.

    - Show the columns for the **Usages** field and for the [Publish In (Sense)](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Publish_In_(Sense).md) field.

6.  [Filter](../../../Basic_Tasks/Filtering_data/filtering_data_overview.md) the **Usages** column to only show senses that contain "**offensive**".

7.  In the left column, [select the rows](select_rows.md) you want to change.

8.  In the **Bulk Edit Operation** pane, do the following:

    - In the **Target Field** box, select **Publish Sense In**.

    - Below **Change To**, click the **Choose** button.

    - In the **Choose Publish Sense In** chooser, select (![](../../../assets/images/CheckedBox.PNG)) **Pocket Dictionary**. Then, select **Remove from existing items** to remove that publication from the selected rows (entries). Click **OK**.

9.  Click **Preview**, review the pending changes, and then click **Apply**.

    The **Pocket Dictionary** publication is removed from the selected senses. Now, in **Dictionary** with **Pocket Dictionary** [selected](../Dictionary/Dictionary_overview.md) ([example](../Dictionary/Select_a_publication.md)), the offensive data is *not* displayed or available for [publishing](../../../User_Interface/Menus/File/Export/Export_overview.md).

> [!TIP]
>
> - The **Choose Publish Sense In** chooser does *not* attempt to reflect the publications currently displayed in the senses, because each senses could contain different publications. So in the chooser, you select the publications you want to remove.
>
> - Because there are so many different ways to use **Bulk Edit** features, such as with the [Status](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Status_field.md) field or other fields in addition to the **Usages** field, use this Help topic as an example from which to design your own processes.
>
> - **Add to existing items** adds the selected publication to the selected rows.
>
> - **Replace existing items** will remove any publications from selected entries and replace them with the selected publication.

## Related topics
[Bulk Edit overview](bulk_edit_overview.md)

[Sorting data overview](../../../Basic_Tasks/Sorting_data/Sorting_data_overview.md)

[Specify publishable lexical data](../Lexicon_Edit/Specify_publishable_lexical_data.md) / [What is a publication?](../../../User_Interface/Field_Descriptions/Lists/Publications/What_is_a_Publication.md)
