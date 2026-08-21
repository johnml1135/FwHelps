---
title: "Step 2 of 3: Field Mapping"
source_title: "Step 2 of 3: Field Mapping"
breadcrumb:
  - "Beginning Tasks"
  - "Importing Data"
  - "Import Standard Format interlinear texts"
  - "Step 2 of 3: Field Mapping"
source: "Beginning_Tasks/Importing_Data/Import_Interlinear_SFM/Step_2_of_3_Field_Mapping.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Beginning_Tasks/Importing_Data/Import_Interlinear_SFM/Step_2_of_3_Field_Mapping.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Mapping"
  - "Mapping:Step 2 of 3: Field Mapping"
  - "Import:Standard Format interlinear texts"
  - "Modify Mapping dialog box"
  - "ZEdit"
  - "program"
related:
  - "About encoding converters -> ../About_encoding_converters.md"
  - "Encoding Converters overview -> ../../../Advanced_Tasks/Writing_Systems/Encoding_Converters/Encoding_Converters_overview.md"
  - "Import Standard Format interlinear texts -> Import_Standard_Format_interlinear_texts.md"
  - "Import Standard Format interlinear texts - pre-defined mappings -> Import_SF_Interlinear_predefined_mappings.md"
fw_help_version: "9.3"
page_heading: "Step 2 of 3: Field Mapping - Import SF interlinear text"
type: "topic"
content_hash: "sha256:35a440183365a870"
---

# Step 2 of 3: Field Mapping

*Beginning Tasks › Importing Data › Import Standard Format interlinear texts*

1.  Click a marker that needs a destination, a writing system, or an encoding converter, and then click **Modify**.

    The **Modify Mapping** dialog box appears. The marker you selected is identified near the top of the dialog box.

2.  Do the following in the **Modify Mapping** dialog box:

    - Click the destination for the current marker (identified in the dialog box), or select **Don't Import**.

    - In the **Writing System** box, select a writing system.

      If a writing system is *not* in the list, click **Add** and then point to **Vernacular Writing System** or **Analysis Writing System** to display a longer list. Click a writing system in the list, or click **Define New** to [add a new writing system](../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/Add_a_new_writing_system.md).

    - In the **Encoding Converters** box, select an encoding convert from the list, *if one is necessary*. If the data is already in Unicode, select **Already in Unicode**.

      If an encoding converter you need is *not* in the list, click **Add** to open the [Encoding Converters Properties](../../../Advanced_Tasks/Writing_Systems/Encoding_Converters/Encoding_Converters_Properties_tab.md) tab. Then, add an encoding converter.

    - Click **OK**.

3.  Repeat the steps above for *each* marker that needs to be mapped.

4.  When all the markers are mapped, click **Next**.

    [Step 3 of 3: Ready to Import](Step_3_of_3_Ready_to_Import.md) appears.

> [!TIP]
>
> - You can open the import file in a program, such as [ZEdit](../../../Basic_Tasks/ZEdit.md), to see the markers and data *while* you use the **Modify Mapping** dialog box. In some cases, it may be necessary to review and correct markers in the import file before you attempt to import the file again.
>
> <!-- -->
>
> - If you click **Cancel**, the **Save Settings** question box appears.
>
>   - If you click **Yes**, your settings are saved for the current import file. Then you will not need to specify them all again for that file.
>
>   - If you click **No**, your setting are not saved.

## Related topics
[About encoding converters](../About_encoding_converters.md)

[Encoding Converters overview](../../../Advanced_Tasks/Writing_Systems/Encoding_Converters/Encoding_Converters_overview.md)

[Import Standard Format interlinear texts](Import_Standard_Format_interlinear_texts.md)

[Import Standard Format interlinear texts - pre-defined mappings](Import_SF_Interlinear_predefined_mappings.md)
