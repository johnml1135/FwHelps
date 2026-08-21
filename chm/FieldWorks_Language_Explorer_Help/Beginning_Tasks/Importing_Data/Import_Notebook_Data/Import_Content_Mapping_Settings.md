---
title: "Import Content Mapping Settings dialog box"
source_title: "Import Content Mapping Settings dialog box"
breadcrumb:
  - "Beginning Tasks"
  - "Importing Data"
  - "Import Notebook Data"
  - "Import Content Mapping Settings dialog box"
source: "Beginning_Tasks/Importing_Data/Import_Notebook_Data/Import_Content_Mapping_Settings.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Beginning_Tasks/Importing_Data/Import_Notebook_Data/Import_Content_Mapping_Settings.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Import:Standard Format anthropology data"
  - "Import:Import Content Mapping Settings"
related:
  - "Step 4 of 7: Content mapping -> Step_4_of_7_Content_mapping.md"
  - "Step 5 of 7: Key markers -> Step_5_of_7_Key_markers.md"
fw_help_version: "9.3"
page_heading: "Import Content Mapping Settings"
type: "topic"
content_hash: "sha256:2efe3d359c925c1e"
---

# Import Content Mapping Settings dialog box

*Beginning Tasks › Importing Data › Import Notebook Data*

A *field* is a unit of data in a Standard Format file that consists of a *marker* and a *text element*. The text element can be empty.

The list at the left displays Standard Format fields in the imported file with the marker that you selected in [Step 4 of 7: Content Mapping](Step_4_of_7_Content_mapping.md).

- In the **Destination in the FieldWorks Notebook** list, select a [Notebook field](../../../User_Interface/Field_Descriptions/Notebook/Notebook_fields_overview.md).

  The options in the pane at the right depend on the [field type](../../../User_Interface/Field_Descriptions/Field_Types/field_types_overview.md).

- To keep from importing the Standard Format marker and its data: **Destination in the FieldWorks Notebook** list, select **Don't Import**.

### Date field

FieldWorks imports the dates in the Standard Format file according to one or more formats that you define. In the list at the right, do any of the following:

- If you need to define a format to match some dates, click **Add**.

  The [Import Date Format Definition](Import_Date_Format_Definition.md) dialog box appears.

- If you can modify a format to match some dates, select it, and then click **Modify**.

  The [Import Date Format Definition](Import_Date_Format_Definition.md) dialog box appears.

- If a format does not match any dates, select it, and then click **Delete**.

### List reference field

1.  To interpret the imported text as one or more items, do any of the following:

    - If a field can contain multiple items, select the **Delimiters indicating multiple items in a line** check box, and then type the delimiters in the box.

    - For list items that have subitems, select the **Delimiters indicating subitems** check box, and then type the delimiters in the box.

    - If only part of a field contains items, select the **Only consider text between** check box, and then type the text that surrounds the items in the boxes.

    - If only the beginning of a field contains items, select the **Only consider text before** check box, and then type the text that follows the items in the box. That is, FieldWorks ignores the rest of the field starting at the text in the box.

    - To only import list items that already exist in the list, and discard all other list item, select **Throw away everything not already in the list**. Then, type a placeholder that indicates to you that this record needs additional work.

2.  Select either **Match items against abbreviations** or **Match items against names**. This affects the matching, and also any changes you enter in the **Text changes** box. Numeric OCM codes are considered abbreviations.\
    The imported text becomes the name and abbreviation of new list items.

3.  If you need to make changes to imported text items so that they match list items, do any of the following in the **Text changes** area:

    - To change an imported text item, click **Add**.

      The [List Import Options](List_Import_Options.md) dialog box appears.

    - To modify a change to an imported text item, select it, and then click **Modify**.

      The [List Import Options](List_Import_Options.md) dialog box appears.

    - To delete a change to an imported text item, select it, and then click **Delete**.

### Multi-paragraph text field

- If the writing system of the Standard Format marker is not the default writing system of the destination field, select a different writing system in the list.

  - If you need to add a writing system to the language project, click **Add**, point to **Vernacular Writing System** or **Analysis Writing System**, and then click a writing system, or **Define New** to [add a new writing system](../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/Add_a_new_writing_system.md).

- In the **Paragraph Style** box, select paragraph style you want to apply to the data imported with this marker.

  - If you need to [add a style](../../../User_Interface/Menus/Format/Styles/Styles_overview.md) to the language project, click **Styles**.

- Select one or more check boxes below **Start a new paragraph**.

### Text field

- If the writing system of the Standard Format marker is not the default (top) writing system of the destination field, select a different writing system in the list.

  - If you need to add a writing system to the language project, click **Add**, point to **Vernacular Writing System** or **Analysis Writing System**, and then click a writing system, or **Define New** to [add a new writing system](../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/Add_a_new_writing_system.md).

## Related topics
[Step 4 of 7: Content mapping](Step_4_of_7_Content_mapping.md)

[Step 5 of 7: Key markers](Step_5_of_7_Key_markers.md)
