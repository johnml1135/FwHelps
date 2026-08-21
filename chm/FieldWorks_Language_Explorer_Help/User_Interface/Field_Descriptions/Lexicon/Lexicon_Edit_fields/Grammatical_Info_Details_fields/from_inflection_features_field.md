---
title: "From Inflection Features field"
source_title: "From Inflection Features field"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Lexicon"
  - "Lexicon Edit fields"
  - "Grammatical Info Details fields"
  - "From Inflection Features field"
source: "User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Grammatical_Info_Details_fields/from_inflection_features_field.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Grammatical_Info_Details_fields/from_inflection_features_field.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "From"
related:
  - "Grammatical Info Details fields overview -> Gram_Info_Detls_fields_ovw.md"
  - "Lexicon Edit overview -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md"
  - "Lexicon Edit fields overview -> ../Lexicon_Edit_fields_overview.md"
  - "Required Features field -> ../Entry_level_fields/required_features_lex.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:7c613c99408ef34e"
---

# From Inflection Features field

*User Interface › Field Descriptions › Lexicon › Lexicon Edit fields › Grammatical Info Details fields*

**Full name:** **From Inflection Features**

**Abbreviation:** **fif**

**Location:**

In the **Entry** pane (**Lexicon Edit**).

For affix entries for which the **Affix Type** is set to **Derivational**, this field is at the [Grammatical Info Details level](Gram_Info_Detls_fields_ovw.md).

**See also:** [To Inflection Features field](To_Inflection_Features_field.md).

**Description:**

If a *derivational* affix requires a stem to have a feature, choose the feature in this field.

This field may reference and display any of the following:

- [abbreviations](../../../Grammar/Inflection_Features_fields/abbreviation_field_feature_features.md) of the **Names** of one or more features or complex features

- [abbreviations](../../../Grammar/Inflection_Features_fields/Abbr_field_value_features.md) of the **Value Names** of one or more features.

The features and complex features need to be selected in the [Inflectable Features](../../../Grammar/Category_Edit_fields/Inflectable_Features_field_Category_Edit.md) field for the particular category (`Category Edit`, [Grammar](../../../Grammar/Grammar_fields_overview.md)) to be available here.

[Parsers](../../../../Menus/Parser/Parsing_words_overview.md) use inflection features.

**Tasks:**

- [Choose inflection features](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/choose_inflection_features.md)

- You can [configure the dictionary](../../../../Menus/Tools/Configure_Dictionary/Configure_Dictionary.md) to include the abbreviation of the selected inflection features when you configure **Features** under [Grammatical Info](../../../../Menus/Tools/Configure_Dictionary/Grammatical_Info.md).

**Field type:** [List reference field](../../../Field_Types/List_reference_field.md)

**Writing systems:** Best [analysis](../../../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md)

**Tip:**

- Typically, you select the **Affix Type**, and categories for **Attaches to Category** and **Changes to Category** in the [New Entry](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Create_a_lexical_entry.md) dialog box. You may change them when you use the [Edit Grammatical Info](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Using_Edit_Gram_Infodlg.md) dialog box.

- For more details about inflection classes, such as a discussion about when you may want to use inflection *classes* versus inflection *features*, on the [Help](../../../../Menus/Help/Help_overview.md) menu point to **Resources**, and then click **Introduction to Parsing**.

## Related topics
[Grammatical Info Details fields overview](Gram_Info_Detls_fields_ovw.md)

[Lexicon Edit overview](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md)

[Lexicon Edit fields overview](../Lexicon_Edit_fields_overview.md)

[Required Features field](../Entry_level_fields/required_features_lex.md)
