---
title: "Required Features field (entry level)"
source_title: "Required Features field (entry level)"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Lexicon"
  - "Lexicon Edit fields"
  - "Entry level fields"
  - "Required Features field"
source: "User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/required_features_lex.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/required_features_lex.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Inflection Features:Required Features field (Lex Edit)"
  - "Required Features field"
  - "Required Features field:Required Features field (Lexicon Edit)"
related:
  - "Entry-level fields overview -> Entry_level_fields_overview.md"
  - "Lexicon Edit overview -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md"
fw_help_version: "9.3"
page_heading: "Required Features field"
type: "topic"
content_hash: "sha256:764ae1f98a326262"
---

# Required Features field (entry level)

*User Interface › Field Descriptions › Lexicon › Lexicon Edit fields › Entry level fields*

**Full name:** **Required Features**

**Location:**

In the **Entry** pane (**Lexicon Edit**).

For entries that are affixes, this field between the **Lexeme Form** [field](Lexeme_Form_field.md) and the **Sense 1** [field](../Sense_level_fields/Sense_field.md), at the [entry level](Entry_level_fields_overview.md).

(A separate **Required Features** field is at the [allomorphs level](../Alternate_Forms_level_flds/Alt_Forms_lev_flds_ov.md) for each inflectional or derivational affix allomorph.)

**Description:**

This field references and displays one or more [inflection features](../../../../../Using_Tools/Grammar_tools/Inflection_Features/About_Infl_Features_and_Types.md) that are required by the lexeme form in order to be licit.

If you choose an inflection feature to condition an affix allomorph, the lexeme form and all other allomorphs without a similar required feature are conditioned to *not* occur when that feature is present. So, in some cases you may be able to leave this "**Required Features**" field empty.

[Parsers](../../../../Menus/Parser/Parsing_words_overview.md) use features.

The inflection features stored in this field appear in the [Grammar Sketch](../../../../../Using_Tools/Grammar_tools/Grammar_Sketch/Grammar_Sketch_overview.md) under sections **Feature System** and **Allomorphy**.

**Tasks:**

- [Choose inflection features](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/choose_inflection_features.md)

**Field type:** [List reference field](../../../Field_Types/List_reference_field.md)

**Writing systems:** Best [analysis](../../../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md)

> [!TIP]
>
> - For derivational affixes, the [From Inflection Features](../Grammatical_Info_Details_fields/from_inflection_features_field.md) and [To Inflection features](../Grammatical_Info_Details_fields/To_Inflection_Features_field.md) fields appear under **Grammatical Info Details**.
>
> - If you use Stem Allomorph Labels, see [Insert a Stem Allomorph Label](../../../../../Using_Tools/Grammar_tools/Category_Edit/Insert_a_Stem_Allomorph_Label.md) for more information.
>
> - For a more complete description, point to **Resources** on the [Help](../../../../Menus/Help/Help_overview.md) menu, and then click **Introduction to Parsing**. Section 3.8 discusses affix allomorphs conditioned by features.
>
> - You *cannot* configure the dictionary to include content from this field.

## Related topics
[Entry-level fields overview](Entry_level_fields_overview.md)

[Lexicon Edit overview](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md)
