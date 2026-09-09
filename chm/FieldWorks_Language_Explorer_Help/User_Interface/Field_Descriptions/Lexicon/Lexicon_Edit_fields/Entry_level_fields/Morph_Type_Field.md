---
title: "Morph Type field (entry level)"
source_title: "Morph Type field (entry level)"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Lexicon"
  - "Lexicon Edit fields"
  - "Entry level fields"
  - "Morph Type field (lexeme form)"
source: "User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Morph_Type_Field.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Morph_Type_Field.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Morph Type:Morph Type field (lexeme form)"
related:
  - "About morpheme types -> ../../../../../Using_Tools/Lists_tools/About_Morpheme_Types.md"
  - "Attaches to Categories field -> ../Grammatical_Info_Details_fields/attaches_to_categories_field.md"
  - "Entry-level fields overview -> Entry_level_fields_overview.md"
  - "Lexicon Edit overview -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md"
fw_help_version: "9.3"
page_heading: "Morph Type field"
type: "topic"
content_hash: "sha256:b1dd3ce645326317"
---

# Morph Type field (entry level)

*User Interface › Field Descriptions › Lexicon › Lexicon Edit fields › Entry level fields*

**Full name:** **Morph Type**

**Abbreviation:** **mt**

**Location:**

In the **Entry** pane (**Lexicon Edit**).

This field is between the **Lexeme Form** [field](Lexeme_Form_field.md) and the **Sense 1** [field](../Sense_level_fields/Sense_field.md). It refers to the lexeme form, not the entire entry.

(A separate **Morph Type** field is at the [allomorphs level](../Alternate_Forms_level_flds/Alt_Forms_lev_flds_ov.md) for each allomorph.)

**Description:**

This field references and displays the [name](../../../Lists/Morpheme_Types_fields/Name_field_Morpheme_Types.md) of the morpheme type of the lexeme form. Morpheme types are stored in the **Morpheme Types** [list](../../../../../Using_Tools/Lists_tools/List_item_usage_table.md). You cannot show morph types in the dictionary.

[Parsers](../../../../Menus/Parser/Parsing_words_overview.md) use morpheme types.

**Tasks:**

- You choose a morph type when you [create the lexical entry](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Create_a_lexical_entry.md) in the **New Entry** dialog box.

- [Change the morpheme type](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/change_the_morph_type.md)

**Field type:** [List reference field](../../../Field_Types/List_reference_field.md)

**Writing systems:** Best [analysis](../../../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md)

**Tip:**

- For affixes, you can configure the dictionary to display the [abbreviation](../../../Lists/Morpheme_Types_fields/abbreviation_field_morpheme_types.md) of the morph type when you configure [Grammatical Info](../../../../Menus/Tools/Configure_Dictionary/Grammatical_Info.md).

- For more information, on the [Help](../../../../Menus/Help/Help_overview.md) menu point to **Resources**, and then click **Introduction to Parsing**. Section 4 includes a discussion about morpheme types that are significant to the [parsers](../../../../Menus/Parser/Parsing_words_overview.md).

> [!IMPORTANT]
>
> - If an [import](../../../../../Beginning_Tasks/Importing_Data/Import_overview.md) problem (or source file problem) caused no lexeme or citation form content to be imported for an entry, the [Lexeme Form](Lexeme_Form_field.md) field is empty, as expected. But also, this **Morph Type** field is not displayed *until* you type content in the empty **Lexeme Form** field.

## Related topics
[About morpheme types](../../../../../Using_Tools/Lists_tools/About_Morpheme_Types.md)

[Attaches to Categories field](../Grammatical_Info_Details_fields/attaches_to_categories_field.md)

[Entry-level fields overview](Entry_level_fields_overview.md)

[Lexicon Edit overview](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md)
