---
title: "Add a custom field"
source_title: "Add a custom field"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Tools"
  - "Custom Fields"
  - "Add a Custom Field"
source: "User_Interface/Menus/Tools/Custom_Fields/add_a_custom_field.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Tools/Custom_Fields/add_a_custom_field.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Tables in lexical entry:Add a custom field"
  - "Add:Custom field"
  - "Custom Fields:Add a custom field"
  - "Table:Add a custom field"
related:
  - "Choose item for a custom list reference field (Lexicon) -> ../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_item_Cust_list_field.md"
  - "Configure Dictionary dialog box -> ../Configure_Dictionary/Configure_Dictionary.md"
  - "Custom Fields overview -> Custom_Fields_overview.md"
  - "Lexicon Edit fields overview -> ../../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Lexicon_Edit_fields_overview.md"
  - "Lexicon Edit overview -> ../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md"
  - "Notebook fields overview -> ../../../Field_Descriptions/Notebook/Notebook_fields_overview.md"
  - "Record Edit overview -> ../../../../Using_Tools/Notebook_tools/Record_Edit_overview/Record_Edit_overview.md"
  - "Tools overview -> ../Tools_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:f12eddde10d7ca47"
---

# Add a custom field

*User Interface › Menus › Tools › Custom Fields*

### Considerations:

- If you use [Send/Receive](../../../../Basic_Tasks/Collaborating_with_Others/Send_Receive_overview.md) to share data between FLEx and WeSay, the name of the custom field must match the name that is in the `Name in file` box for the associated field in WeSay. *Do not put spaces between the words in the name*. However, if WeSay already has an added field with content, FLEx creates a new custom field automatically when it receives that data from WeSay during the **Send/Receive** operation.

- If you will add a custom [list reference](../../../Field_Descriptions/Field_Types/List_reference_field.md) field to use with a *custom list*, [insert the custom list](../../../../Using_Tools/Lists_tools/Insert_a_custom_list.md) *first*.

- If you will present data in [tables](../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Format_a_table.md), add a **Single-line Text** field.

- [Custom Fields overview](Custom_Fields_overview.md) describes **Location** and **Writing System** options and more.

Do these steps:

1.  In the **Navigation** **Pane**, click one of these [areas](../../../Toolbars/Navigation/Navigation_Pane_overview.md), **Lexicon**, **Notebook** or **Texts & Words**. Then, click the desired tool (**Lexicon Edit** or **Record Edit**, and so on).

2.  On the **Tools** menu, point to **Configure**, and then click **Custom Fields**.

    If a ![](../../../../assets/images/LargeWarning.png) **Warning** message box appears read it carefully and then click **OK**. The **Custom Fields** dialog box appears.

3.  In the dialog box, do the following:

    - Click **Add** to create the new custom field.

    - In the **Custom Field Name** box, enter a name. Do not include any punctuation in the name.

    - In the **Location** box, select a location if the control is available.

    - In the **Description** box, enter a description of the field and its purpose.

    - In the **Type** box, select the [field type](../../../Field_Descriptions/Field_Types/field_types_overview.md).

    - For a **Single-line Text** or **Multiparagraph Text** field, select a **Writing System(s)** option.

    - For a **List Reference** field (single or multiple items), select the FieldWorks [list](../../../../Using_Tools/Lists_tools/List_item_usage_table.md) that has the list items you want available in the custom field.

    - Click **OK**.

    The custom field is added.

4.  If you need to add another custom field, close and then reopen the **Custom Fields** dialog box.

Otherwise, the custom fields may not be created correctly.

## Related topics
[Choose item for a custom list reference field (Lexicon)](../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_item_Cust_list_field.md)

[Configure Dictionary dialog box](../Configure_Dictionary/Configure_Dictionary.md)

[Custom Fields overview](Custom_Fields_overview.md)

[Lexicon Edit fields overview](../../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Lexicon_Edit_fields_overview.md)

[Lexicon Edit overview](../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md)

[Notebook fields overview](../../../Field_Descriptions/Notebook/Notebook_fields_overview.md)

[Record Edit overview](../../../../Using_Tools/Notebook_tools/Record_Edit_overview/Record_Edit_overview.md)

[Tools overview](../Tools_overview.md)
