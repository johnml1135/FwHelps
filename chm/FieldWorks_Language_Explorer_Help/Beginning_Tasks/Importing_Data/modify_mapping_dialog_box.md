---
title: "Modify Mapping dialog box"
source_title: "Modify Mapping dialog box"
breadcrumb:
  - "Beginning Tasks"
  - "Importing Data"
  - "Modify Mapping dialog box"
source: "Beginning_Tasks/Importing_Data/modify_mapping_dialog_box.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Beginning_Tasks/Importing_Data/modify_mapping_dialog_box.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Mapping"
  - "Mapping:Modify Mapping dialog box"
  - "Import:Modify Mapping dialog box"
related:
  - "About Lexical Relations -> ../../Using_Tools/Lists_tools/About_Lexical_Relations.md"
  - "Import SFM data examples -> Import_SFM_data_examples.md"
  - "Import Standard Format Lexical data -> Import_Standard_Format_lexical_data.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:3dd90ccfc55f8be0"
---

# Modify Mapping dialog box

*Beginning Tasks › Importing Data*

The **Modify Mapping** dialog box appears when you click **Modify** in the **Import Standard Formal lexical data** wizard, [Step 4 of 8: Content mapping](Step_4_of_8_Content_mapping.md). In the dialog box, the **Marker** area indicates the particular marker that was selected in the wizard when you clicked **Modify**. This is the current marker.

1.  For the marker indicated in the **Modify Mapping** area, do one or more of the following:

    The availability of some features on the right side of the dialog box will vary, depending upon other current selections.

    - Select or clear **Don't Import** to exclude or include lines with the current marker.

    - Select **Default – Import Residue Auto** to automatically send each line in the import file with the current marker to a field based on its context in the import file. (The accuracy of this feature may depend on the [readiness](Examine_import_preview_results_errors.md) of the import data. After the import is completed, you need to verify that the data was imported to correct fields.)

      If you select **Don't Import** when **Default – Import Residue Auto** is also selected, **Don't Import** selection overrides **Default – Import Residue Auto** (which remains selected but unavailable).

    - In the **Destination in FieldWorks Language Explorer** area, navigate to and select the field into which you want to import the data that has the current marker. (The **Don't Import** and **Default – Import Residue Auto** check boxes must be cleared.)

    - If the destination field you need is not listed, click **Add Custom field**. Then after you [add the custom field](../../User_Interface/Menus/Tools/Custom_Fields/add_a_custom_field.md), select it as the **Destination in FieldWorks Language Explorer**.

    - Select a *Language Descriptor*, or click *Add* to [add a language mapping](Step_3_of_8_Language_mapping.md).

      If the **FW Writing System** setting in [Step 3 of 8](Step_3_of_8_Language_mapping.md) is set to **ignore** for the language you select, marker will continued to be ignored, as indicated by the colored background in the **Content mapping** area of the wizard (step 4 of 8).

    - Select **Name** or **Abbreviation** for the field content.

    - If you mapped the marker to **Cross Reference** or to **Lexical Relation**, select the **Lexical Reference Type**. (Normally, this field label is **Not An Active Field**.)

2.  Click **OK**.

> [!TIP]
>
> - Click **Show Info** to see a description of the current selection in the **Destination in Language Explorer** pane. Click **Hide Info** to close that information pane.

## Related topics
[About Lexical Relations](../../Using_Tools/Lists_tools/About_Lexical_Relations.md)

[Import SFM data examples](Import_SFM_data_examples.md)

[Import Standard Format Lexical data](Import_Standard_Format_lexical_data.md)
