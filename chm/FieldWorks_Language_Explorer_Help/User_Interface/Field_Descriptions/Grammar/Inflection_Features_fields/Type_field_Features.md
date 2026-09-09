---
title: "Type field (Features)"
source_title: "Type field (Features)"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Grammar"
  - "Inflection Features fields"
  - "Type field (Feature)"
source: "User_Interface/Field_Descriptions/Grammar/Inflection_Features_fields/Type_field_Features.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Grammar/Inflection_Features_fields/Type_field_Features.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Type fields:Type field (Inflection Feature)"
related:
  - "About Inflection Features and Feature Types -> ../../../../Using_Tools/Grammar_tools/Inflection_Features/About_Infl_Features_and_Types.md"
  - "Grammar Sketch -> ../../../../Using_Tools/Grammar_tools/Grammar_Sketch/Grammar_Sketch_overview.md"
  - "Inflection Features fields overview -> Features_fields_overview.md"
fw_help_version: "9.3"
page_heading: "Type field - Inflection Feature"
type: "topic"
content_hash: "sha256:6165aed0da23b50f"
---

# Type field (Features)

*User Interface › Field Descriptions › Grammar › Inflection Features fields*

**Full name:** **Type**

**Abbreviation:** **ty**

**Location:** This **Type** field is in the **Complex Feature** pane in **Inflection Features** ([Grammar](../../../../Using_Tools/Grammar_tools/grammar_overview.md)) for a complex feature.

**Description:**

For a complex feature, this field references and displays the [name](../../Lists/Feature_Types_fields/Name_field_Feature_Types.md) of a [feature type](../../Lists/Feature_Types_fields/Feature_Types_fields_overview.md) associated with the current inflection feature.

[Parsers](../../../Menus/Parser/Parsing_words_overview.md) use inflection features.

The *type* determines which inflection features this complex feature can contain. Thus, the feature type displayed in this field affects what can appear in the dialog boxes for [Inflectable Features field](../Category_Edit_fields/Inflectable_Features_field_Category_Edit.md) (**Grammar**) and [Inflection Features fields](../../Lexicon/Lexicon_Edit_fields/Grammatical_Info_Details_fields/Inflection_Features_field.md) (**Lexicon Edit**) regarding the current feature.

### Example:

Suppose we have a *type* of "agreement" and the *features* "gender" and "number" are associated with it (that is, in [Feature Types fields](../../Lists/Feature_Types_fields/Feature_Types_fields_overview.md) (**Lists**), we give it the *name* "agreement" and *refer to* "gender" and "number" in the [Features fields](../../Lists/Feature_Types_fields/Features_field_Feature_Types.md)). If we then make a complex feature of "subject agreement" and give it the *type* "agreement," then the complex feature "subject agreement" will show up as "subject agreement (gender, number)" in the dialog box when you [choose Inflectable features](../../../../Using_Tools/Grammar_tools/Category_Edit/Choose_inflectable_features.md).

**Tasks:**

- [Insert an inflection feature or complex feature](../../../../Using_Tools/Grammar_tools/Inflection_Features/Insert_a_Feature_or_Complex_Feature.md)

- **See also:** [Inflection Features overview](../../../../Using_Tools/Grammar_tools/Inflection_Features/Inflection_Features_overview.md)

**Field type:** [List reference field](../../Field_Types/List_reference_field.md)

**Writing systems:** Best [analysis](../../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md)

**Grammar Sketch:** Under **Morpho-syntactic Feature System**

**Tip:** For more information, point to **Resources** on the [Help](../../../Menus/Help/Help_overview.md) menu, and then click **Introduction to Parsing**.

## Related topics
[About Inflection Features and Feature Types](../../../../Using_Tools/Grammar_tools/Inflection_Features/About_Infl_Features_and_Types.md)

[Grammar Sketch](../../../../Using_Tools/Grammar_tools/Grammar_Sketch/Grammar_Sketch_overview.md)

[Inflection Features fields overview](Features_fields_overview.md)
