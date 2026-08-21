---
title: "Stem Allomorph Label field (entry level)"
source_title: "Stem Allomorph Label field (entry level)"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Lexicon"
  - "Lexicon Edit fields"
  - "Entry level fields"
  - "Stem Allomorph Label field (lexeme form)"
source: "User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/stem_allomorph_label_field_lex_form.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/stem_allomorph_label_field_lex_form.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Allomorphy"
related:
  - "Choose inflection features for a Feature Set -> ../../../../../Using_Tools/Grammar_tools/Category_Edit/Choose_Inflection_features.md"
  - "Entry-level fields overview -> Entry_level_fields_overview.md"
  - "Lexicon Edit overview -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md"
fw_help_version: "9.3"
page_heading: "Stem Allomorph Label field"
type: "topic"
content_hash: "sha256:beda57d77722d94a"
---

# Stem Allomorph Label field (entry level)

*User Interface › Field Descriptions › Lexicon › Lexicon Edit fields › Entry level fields*

**Full name:** **Stem Allomorph Label**

**Location:**

In the **Entry** pane (**Lexicon Edit**). Specifically:

- This field is between the **Lexeme Form** [field](Lexeme_Form_field.md) and the **Sense 1** [field](../Sense_level_fields/Sense_field.md) for *non-affix* entries. It refers to the lexeme form, not the entire entry.

- A separate **Stem **Allomorph Label**** field for each *allomorph* is at the [Allomorphs level](../Alternate_Forms_level_flds/Alt_Forms_lev_flds_ov.md).

- A separate **From **Allomorph Label** Name** field for *derivational affixes* is at the [Grammatical Info Details level](../Grammatical_Info_Details_fields/grammatical_info_details_field.md).

**Description:**

This field displays and references the [name](../../../Grammar/Category_Edit_fields/Stem_Allomorph_Label_field.md) of a Stem Allomorph Label, which is stored in **Category Edit** ([Grammar](../../../../../Using_Tools/Grammar_tools/grammar_overview.md)).

For each Stem Allomorph Label, you can define one or more sets of inflection features (a [Feature Set](../../../Grammar/Category_Edit_fields/Feature_Sets_field_Category_Edit.md)) that must be present for a particular stem allomorph to be licit. That is, use Stem Allomorph Labels to control stem allomorphy (*not* affix allomorphy) that is dependent *not* on phonological issues, but on the presence of certain inflection features. [Parsers](../../../../Menus/Parser/Parsing_words_overview.md) use Stem Allomorph Labels. [Insert a Stem Allomorph Label](../../../../../Using_Tools/Grammar_tools/Category_Edit/Insert_a_Stem_Allomorph_Label.md) has more information.

The Stem Allomorph Label appears in the [Grammar Sketch](../../../../../Using_Tools/Grammar_tools/Grammar_Sketch/Grammar_Sketch_overview.md) under **Allomorphy**. You cannot display Stem Allomorph Labels in [Dictionary](../../../../../Using_Tools/Lexicon_tools/Dictionary/Dictionary_overview.md).

For a more complete description, point to **Resources** on the [Help](../../../../Menus/Help/Help_overview.md) menu, and then click **Introduction to Parsing**.

**Tasks:**

- [Choose a Stem Allomorph Label](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_Stem_Allomorph_Label.md)

**Field type:** [List reference field](../../../Field_Types/List_reference_field.md)

**Writing systems:** Best [analysis](../../../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md)

## Related topics
[Choose inflection features for a Feature Set](../../../../../Using_Tools/Grammar_tools/Category_Edit/Choose_Inflection_features.md)

[Entry-level fields overview](Entry_level_fields_overview.md)

[Lexicon Edit overview](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md)
