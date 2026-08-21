---
title: "Custom Fields overview"
source_title: "Custom Fields overview"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Tools"
  - "Custom Fields"
  - "Custom Fields overview"
source: "User_Interface/Menus/Tools/Custom_Fields/Custom_Fields_overview.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Tools/Custom_Fields/Custom_Fields_overview.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Writing System:Writing systems for custom fields"
  - "Import:Weather data"
  - "Notebook"
  - "Custom:Custom Fields overview"
  - "Weather"
  - "Notebook data"
  - "Import Weather data"
  - "Custom Fields"
  - "Custom Fields:Custom Fields overview"
related:
  - "Configure Dictionary Layout dialog box -> ../Configure_Dictionary/Configure_Dictionary.md"
  - "Configure Document Layout dialog box -> ../Configure_Document/Configure_Document_View_dialog_box.md"
  - "Configure Interlinear Lines dialog box -> ../Configure_interlinear_lines_dialog_box.md"
  - "Custom Fields limits -> custom_fields_limits.md"
  - "Format a table -> ../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Format_a_table.md"
  - "Lexicon overview -> ../../../../Using_Tools/Lexicon_tools/Lexicon_overview.md"
  - "Tools overview -> ../Tools_overview.md"
fw_help_version: "9.3"
type: "index"
content_hash: "sha256:92830b5a1cac2d74"
---

# Custom Fields overview

*User Interface › Menus › Tools › Custom Fields*

A *field* is a part of a lexical entry or record that stores a particular kind of information. You can add additional fields, called *custom fields*.

A **Custom Fields** dialog box opens from the **Tools** [menu](../Tools_overview.md), under **Configure**. If you open one while in **Lexicon** or **Notebook** a **Custom Fields** dialog box opens with all features available. If you open one while in **Texts & Words**, you can only add custom fields as [single-line texts fields](../../../Field_Descriptions/Field_Types/Single_line_text_field.md).

Be aware that you *only* see the custom fields that were added in the current [area](../../../Toolbars/Navigation/Navigation_Pane_overview.md), not all of them.

The dialog boxes have these controls:

|  |  |
|----|----|
| Label | Allows you to |
| **Add** | [add](add_a_custom_field.md) a custom field |
| **Delete** | [delete](Delete_a_custom_field.md) a custom field |
| **Custom Field Name** | enter the name the field |
| **Location** | choose where the field appears (see below) |
| **Description** | enter metadata (seen only in this dialog box) |
| **Type** | choose the [field type](../../../Field_Descriptions/Field_Types/field_types_overview.md) |
| **List** | choose the FieldWorks [list](../../../../Using_Tools/Lists_tools/List_item_usage_table.md) |
| **Writing System(s)** | choose one of the [writing system](../../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md) options. |

> [!IMPORTANT]
>
> - In **Lexicon**, **Location** options:
>
>   **Entry** puts the custom field at the [entry level](../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/About_Lex_Edit_fld_levels.md) (above the first sense).
>
>   **Sense** puts one in each sense and subsense.
>
>   **Example** puts one with each **Example** field set.
>
>   **Allomorph** puts one with each **Affix Allomorph** or **Stem Allomorph** field set.
>
> - In **Notebook**, **Location** option:
>
>   **Record** puts the custom field near to the bottom of the set of fields.
>
> - In **Texts & Words**, **Location** option:
>
> **Segment** puts the custom field with the **FREE** or **LIT** lines.
>
> - In the **Writing System(s)** box, if you select:
>
>   - **First Analysis** or **First Vernacular** writing system, you will be able to [embed](../../Format/select_a_writing_system.md) other writing systems and [styles](../../Format/Styles/Styles_overview.md).
>
>   - For a selection that includes "**All**," such as **All Analysis Writing Systems**, you will *not* be able to embed other writing systems or styles. The "**All**" options are not available in **Texts & Words**.
>
>   <!-- -->
>
>   - You *cannot* change the location or writing system after the custom field was added. But, you can [modify](modify_a_custom_field.md) the name and description.
>
>   - If you will add a custom [list reference](../../../Field_Descriptions/Field_Types/List_reference_field.md) field to use with a custom *list*, [insert the custom list](../../../../Using_Tools/Lists_tools/Insert_a_custom_list.md) *first*.
>
>   - You can [export and import](../Configure_Dictionary/Manage_Dictionary_Views.md) custom fields with shared **Dictionary** views.
>
>   - If you have weather data in the SIL FieldWorks Data Notebook file or another SFM anthropology file that you will [import](../../../../Beginning_Tasks/Importing_Data/Import_Notebook_Data/Import_SF_anthro_data.md), [insert a custom list](../../../../Using_Tools/Lists_tools/Insert_a_custom_list.md) named **Weather** list, and add a custom field named **Weather**. Then, [map](../../../../Beginning_Tasks/Importing_Data/Import_Notebook_Data/Step_4_of_7_Content_mapping.md) the weather data to that custom field.

## Related topics
[Configure Dictionary Layout dialog box](../Configure_Dictionary/Configure_Dictionary.md)

[Configure Document Layout dialog box](../Configure_Document/Configure_Document_View_dialog_box.md)

[Configure Interlinear Lines dialog box](../Configure_interlinear_lines_dialog_box.md)

[Custom Fields limits](custom_fields_limits.md)

[Format a table](../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Format_a_table.md)

[Lexicon overview](../../../../Using_Tools/Lexicon_tools/Lexicon_overview.md)

[Tools overview](../Tools_overview.md)
