---
title: "Inflection Classes field (entry level)"
source_title: "Inflection Classes field (entry level)"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Lexicon"
  - "Lexicon Edit fields"
  - "Entry level fields"
  - "Inflection Classes field"
source: "User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/inflection_classes_field_entry_level.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/inflection_classes_field_entry_level.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Inflection Class:Inflection Classes field (Entry level)"
  - "Declension"
related:
  - "Entry-level fields overview -> Entry_level_fields_overview.md"
  - "Lexicon Edit overview -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md"
fw_help_version: "9.3"
page_heading: "Inflection Classes field"
type: "topic"
content_hash: "sha256:bbb6cdb62e28396e"
---

# Inflection Classes field (entry level)

*User Interface › Field Descriptions › Lexicon › Lexicon Edit fields › Entry level fields*

**Full name:** **Inflection Classes**

**Abbreviation:** **c****l**

**Location:**

In the **Entry** pane (**Lexicon Edit**).

For entries that are affixes, this field is between the **Lexeme Form** [field](Lexeme_Form_field.md) and the **Sense 1** [field](../Sense_level_fields/Sense_field.md), at the [entry-level](Entry_level_fields_overview.md).

(There is also an [Inflection Classes](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/About_Lex_Edit_fld_levels.md) field at the **Allomorphs** level for each affix allomorph.)

**Description:**

This field references and displays the [names](../../../Grammar/Category_Edit_fields/name_field_inflection_class_category_edit.md) of one or more inflection classes which are stored under the [Inflection Class Info](../../../Grammar/Category_Edit_fields/Inflection_Class_Info_field_Category_Edit.md) field in **Category Edit** ([Grammar](../../../Grammar/Grammar_fields_overview.md)).

[Parsers](../../../../Menus/Parser/Parsing_words_overview.md) use inflection classes.

**Tasks:**

- [Choose an inflection class](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_an_inflection_class.md) (has a table of related fields)

**Field type:** [List reference field](../../../Field_Types/List_reference_field.md)

**Writing systems:** Best [analysis](../../../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md)

> [!TIP]
>
> - You *cannot* configure the dictionary to include content from this field.
>
> - You can choose the affix type **Inflectional** in the [New Entry](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Create_a_lexical_entry.md) dialog box and in the [Edit Grammatical Info](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Using_Edit_Gram_Infodlg.md) dialog box.
>
> - A derivational affix may only attach to a stem of a particular inflection class. The result of attaching the derivational affix will be a stem and, since stems can have a single inflection class, the [To Inflection Class](../Grammatical_Info_Details_fields/To_Inflection_Class_field.md) can define which inflection class that is. **See also:** [From Inflection Class field](../Grammatical_Info_Details_fields/from_inflection_class_field.md).
>
> - For entries that are *not* affixes, there is an [Inflection Class](../Grammatical_Info_Details_fields/Inflection_Class_field_Lex_Edit.md) field at the **Grammatical Info Details** level.
>
> - For more details about inflection classes, such as a discussion about when you may want to use inflection *classes* versus inflection *features*, on the [Help](../../../../Menus/Help/Help_overview.md) menu point to **Resources**, and then click **Introduction to Parsing**.

## Related topics
[Entry-level fields overview](Entry_level_fields_overview.md)

[Lexicon Edit overview](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md)
