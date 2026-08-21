---
title: "Import Standard Format Interlinear Texts - Pre-defined Mappings"
source_title: "Import Standard Format Interlinear Texts - Pre-defined Mappings"
breadcrumb:
  - "Beginning Tasks"
  - "Importing Data"
  - "Import Standard Format interlinear texts"
  - "Import Standard Format Interlinear Texts - Pre-defined Mappings"
source: "Beginning_Tasks/Importing_Data/Import_Interlinear_SFM/Import_SF_Interlinear_predefined_mappings.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Beginning_Tasks/Importing_Data/Import_Interlinear_SFM/Import_SF_Interlinear_predefined_mappings.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Mapping"
  - "Mapping:Pre-defined Mappings"
  - "Import Standard Format Interlinear Texts"
  - "Import:Pre-defined mappings - Import SF interlinear texts"
related:
  - "Import Standard Format interlinear texts overview -> Import_Standard_Format_interlinear_texts.md"
  - "Import Standard Format words and glosses - pre-defined mappings -> ../Import_SFM_words_and_glosses/Import_Standard_Format_wWords_and_glosses_-_Pre-defined_Mappings.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:b0116c4c8f7f6de9"
---

# Import Standard Format Interlinear Texts - Pre-defined Mappings

*Beginning Tasks › Importing Data › Import Standard Format interlinear texts*

This table shows the field mappings that are pre-defined. In [Step 2 of 3: Field Mapping](Step_2_of_3_Field_Mapping.md), you can override them as necessary.

|               |                     |      |     |         |                  |        |
|---------------|---------------------|------|-----|---------|------------------|--------|
| Code          | Destination         | Lang |     | Code    | Destination      | Lang   |
| ab            | Abbreviation        |      |     | lx      | Baseline         | {vern} |
| abb           | Abbreviation        |      |     | mp-e    | Source           | en     |
| au            | Source              |      |     | mp-s    | Source           | es     |
| author        | Source              |      |     | name    | New Text         |        |
| cmt           | Note                |      |     | nd      | Note             |        |
| co            | Comment             |      |     | nt      | Note             |        |
| com           | Note                |      |     | p       | Paragraph        |        |
| comp          | Source              |      |     | po      | Baseline         | {vern} |
| compiler      | Source              |      |     | ref     | Reference        |        |
| description-e | Comment             | en   |     | rf      | Reference        |        |
| dt            | Note                |      |     | s       | Baseline         | {vern} |
| en            | Note                | en   |     | sectn   | Title            |        |
| et            | Free Translation    | en   |     | sn      | Note             | es     |
| etitle        | Title               | en   |     | so      | Source           |        |
| f             | Free Translation    |      |     | source  | Source           |        |
| fe            | Free Translation    | en   |     | st      | Free Translation | es     |
| filename      | Title               |      |     | t       | Baseline         | {vern} |
| fn            | Note                |      |     | te      | Free Translation | en     |
| fr            | Free Translation    |      |     | ti      | Title            |        |
| fre           | Free Translation    |      |     | tit     | Title            |        |
| ft            | Free Translation    |      |     | title   | Title            |        |
| id            | Title               |      |     | title-e | Title            | en     |
| itm           | Title               |      |     | title-s | Title            | es     |
| l             | Literal Translation |      |     | title-v | Title            | {vern} |
| li            | Literal Translation |      |     | tn      | Reference        |        |
| lit           | Literal Translation |      |     | tx      | Baseline         | {vern} |
| lt            | Literal Translation |      |     | wn      | Note             |        |

> [!NOTE]
>
> - In this table, the **Lang** (Language) column refers to [two-letter language code](../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/Language_codes.md); en is English. es is Spanish, and {vern} the *default* [vernacular writing system](../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md) set up in your project.\
>   These appear as the **Code** in the **General** [tab](../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_General_tab.md) of the **Writing System Properties** dialog box.
>
> - For more information, on the [Help](../../../User_Interface/Menus/Help/Help_overview.md) menu, point to **Resources**, and then click **Technical Notes on Interlinear Import**.

## Related topics
[Import Standard Format interlinear texts overview](Import_Standard_Format_interlinear_texts.md)

[Import Standard Format words and glosses - pre-defined mappings](../Import_SFM_words_and_glosses/Import_Standard_Format_wWords_and_glosses_-_Pre-defined_Mappings.md)
