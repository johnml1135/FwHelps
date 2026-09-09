---
title: "Features field (Feature Types)"
source_title: "Features field (Feature Types)"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Lists"
  - "Feature Types fields"
  - "Features field (Feature Types)"
source: "User_Interface/Field_Descriptions/Lists/Feature_Types_fields/Features_field_Feature_Types.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Lists/Feature_Types_fields/Features_field_Feature_Types.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Feature Types (Lists)"
related:
  - "Feature Types fields overview -> Feature_Types_fields_overview.md"
  - "Inflection Features fields overview -> ../../Grammar/Inflection_Features_fields/Features_fields_overview.md"
  - "List item usage table -> ../../../../Using_Tools/Lists_tools/List_item_usage_table.md"
  - "Lists overview -> ../../../../Using_Tools/Lists_tools/Lists_overview.md"
fw_help_version: "9.3"
page_heading: "Features field"
type: "topic"
content_hash: "sha256:2b2f0986609f019a"
---

# Features field (Feature Types)

*User Interface › Field Descriptions › Lists › Feature Types fields*

**Full name:** **Features**

**Location:** **Feature Type** pane in the **Feature Types** list ([Lists](../../../../Using_Tools/Lists_tools/Lists_overview.md)).

**Description:**

This field references and displays [inflection features](../../Grammar/Inflection_Features_fields/Features_fields_overview.md) chosen for the current [named](Name_field_Feature_Types.md) feature type. Any complex feature that has this feature type can contain any of the inflection features listed in this field.

The features in this list appear in the [Grammar Sketch](../../../../Using_Tools/Grammar_tools/Grammar_Sketch/Grammar_Sketch_overview.md) under **Feature System**.

### Example:

Suppose we have a *type* of "agreement" and the *features* "gender" and "number" are associated with it (that is, in [Feature Types](Feature_Types_fields_overview.md) (**Lists**), we give it the *name* "agreement" and *refer to* "gender" and "number" here in the **Features** field). If we then make a complex feature of "subject agreement" and give it the *type* "agreement," then the complex feature "subject agreement" will show up as "subject agreement (gender, number)" in the dialog box when you [choose Inflectable features](../../../../Using_Tools/Grammar_tools/Category_Edit/Choose_inflectable_features.md).

**Tasks:**

- [Choose](../../../../Using_Tools/Lists_tools/choose_item_for_list_field.md) an item for a list reference field

- [Edit a list item](../../../../Using_Tools/Lists_tools/Edit_a_list_item_or_subitem.md)

- **See also:** [About Inflection Features and Feature Types](../../../../Using_Tools/Grammar_tools/Inflection_Features/About_Infl_Features_and_Types.md)

**Field type:** [List reference field](../../Field_Types/List_reference_field.md)

**Writing systems:** Best [analysis](../../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md)

> [!TIP]
>
> - If the **Choose Features** dialog box is empty, you need to [insert inflection features](../../../../Using_Tools/Lists_tools/Feature_Types/Insert_a_Feature_Type.md).
>
> - For more information, point to **Resources** on the [Help](../../../Menus/Help/Help_overview.md) menu, and then click **Introduction to Parsing**.

## Related topics
[Feature Types fields overview](Feature_Types_fields_overview.md)

[Inflection Features fields overview](../../Grammar/Inflection_Features_fields/Features_fields_overview.md)

[List item usage table](../../../../Using_Tools/Lists_tools/List_item_usage_table.md)

[Lists overview](../../../../Using_Tools/Lists_tools/Lists_overview.md)
