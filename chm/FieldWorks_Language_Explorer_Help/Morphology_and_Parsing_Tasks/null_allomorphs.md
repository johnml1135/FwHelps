---
title: "Null Allomorphs"
source_title: "Null Allomorphs"
breadcrumb:
  - "Morphology and Parsing Tasks"
  - "Null Allomorphs"
source: "Morphology_and_Parsing_Tasks/null_allomorphs.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Morphology_and_Parsing_Tasks/null_allomorphs.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Null"
  - "Zero"
  - "Zero allomorphs"
  - "Allomorph:Null Allomorphs"
related:
  - "Category Edit (Grammar) overview -> ../Using_Tools/Grammar_tools/Category_Edit/Category_Edit_overview.md"
  - "Lexicon Edit overview -> ../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md"
  - "Morphology and Parsing Tasks overview -> Morphology_Parsing_Tasks_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:ae4eda62315d7ec1"
---

# Null Allomorphs

*Morphology and Parsing Tasks*

Typically, one wants to avoid having any null allomorphs (also referred to as a *zero morph*, consisting of no phonetic form), if for no other reason than they slow down the [parsers](../User_Interface/Menus/Parser/Parsing_words_overview.md). However, if having one proves to be the best analysis, do the following to indicate that the allomorph is null:

1.  In the [Affix Allomorph](../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Affix_allomorph_fld.md) or [Stem Allomorph](../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Stem_Allomorph_fld.md) field (**Allomorphs** area) for the null allomorph, enter the following:

    - ![](../assets/images/Morphology_and_Parsing_Tasks/empty_set_null_allo.gif), the empty set character, *if* available in the [font](../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_Fonts_tab.md) you are using.

      It is Unicode hex code 2205, available on the [Character Map](../User_Interface/Menus/Insert/Using_Character_Map.md) (for `Doulos SIL` font).

    - Otherwise, if you have a suitable keyboard and font, use whatever keystrokes required by that particular keyboard to generate Unicode value 2205.

    - You may also have a null form as the [Lexeme Form](../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Lexeme_Form_field.md). The empty set character or other alternatives would be similarly used. You may want to enter an empty set character in the **Citation Form** field. The citation form becomes the headword in the dictionary entry.

2.  [Insert environments](../Using_Tools/Grammar_tools/Environments/Insert_an_environment.md) and then [choose the environments](../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_environments.md) to constrain the null allomorph as specifically as possible. This will minimize the chance that it will cause invalid parses.

> [!TIP]
>
> - **Example:** In the English phrase *two sheep-*![](../assets/images/Morphology_and_Parsing_Tasks/empty_set_null_allo.gif), the plural marker is a null, which is an allomorph of the *–s* in *two goats* *(at least under one analysis)*.
>
>   Similarly, one can choose to analyze certain forms as always having a null affix. For example, in English, if one wished, one could posit a null for the phrase *I like*-![](../assets/images/Morphology_and_Parsing_Tasks/empty_set_null_allo.gif) *it.* The null affix (or *zero affix*) is the lack of an expected affix analyzed as another affix. So, in the example *I like*-![](../assets/images/Morphology_and_Parsing_Tasks/empty_set_null_allo.gif) *it*, the verb conjugation has a null affix, as opposed to the third-person singular *–s* present in *he likes it*.
>
> - Unconstrained nulls can make the [parser](../User_Interface/Menus/Parser/Parsing_words_overview.md) run a lot longer. So if you are trying to decide between using a null and a non-null allomorph (for example, if you can easily split two morphemes either as a null plus segmental material or as some segmental material for the first and some segmental material for second), then you may well want to go with the second option and avoid using a null.
>
> - For more information, point to **Resources** on the [Help](../User_Interface/Menus/Help/Help_overview.md) menu, and then click **Introduction to Parsing**. **Null Allomorphs** is under **Lexical Entry Considerations**.

## Related topics
[Category Edit (Grammar) overview](../Using_Tools/Grammar_tools/Category_Edit/Category_Edit_overview.md)

[Lexicon Edit overview](../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md)

[Morphology and Parsing Tasks overview](Morphology_Parsing_Tasks_overview.md)
