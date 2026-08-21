---
title: "Parsing words (Hermit Crab Parser)"
source_title: "Parsing words (Hermit Crab Parser)"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Parser"
  - "Parsing words (Hermit Crab Parser)"
source: "User_Interface/Menus/Parser/Parsing_words_(HermitCrab).htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Parser/Parsing_words_%28HermitCrab%29.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Parser:Parsing words (Hermit Crab Parser)"
  - "Phonological Rules:Phonological Rule-Based Parser"
  - "Phonological Rule-Based Parser"
related:
  - "About morpheme types -> ../../../Using_Tools/Lists_tools/About_Morpheme_Types.md"
  - "FieldWorks Project Utilities overview -> ../Tools/Language_Project_Utilities_overview.md"
  - "Parser menu overview -> Parser_menu_overview.md"
  - "Required Features field -> ../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/required_features.md"
  - "Words Analyses overview -> ../../../Using_Tools/Texts_&_Words_tools/Word_Analyses/Word_Analyses_overview.md"
fw_help_version: "9.3"
page_heading: "Parsing words (Hermit Crab)"
type: "topic"
content_hash: "sha256:e0ece58351883337"
---

# Parsing words (Hermit Crab Parser)

*User Interface › Menus › Parser*

The Hermit Crab (HC) parser is a morphological parser and generator for classical generative phonology and morphology. **See:** [Parsing words overview](Parsing_words_overview.md).

The *accuracy* of the analyses produced by this parser *directly* reflects the quality and completeness of the information you have entered in the **Lexicon** and the **Grammar** areas. You can see a summary of that information in the [Grammar Sketch](../../../Using_Tools/Grammar_tools/Grammar_Sketch/Grammar_Sketch_overview.md).

From [Lexicon](../../../Using_Tools/Lexicon_tools/Lexicon_overview.md), this parser can use all of the information used by the [default (XAmple) parser](Parsing_words.md). Also, to function as a *Phonological Rule-based* parser, it uses the following information:

- **Affix Process Rule** [field](../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Affix_Process_Rule_field.md) for any affix [lexeme forms](../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Lexeme_Form_field.md)

- **Affix Process Rule** [field](../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Affix_Process_Rule_fldAF.md) for any affix [allomorphs](../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Alt_Forms_lev_flds_ov.md)

From [Grammar](../../../Using_Tools/Grammar_tools/grammar_overview.md), this parser can use the all of the information used by the default (XAmple) parser, and *also* the following information:

- [Phonemes](../../../Using_Tools/Grammar_tools/Phonemes/Phonemes_overview.md)

- [Phonological Features](../../../Using_Tools/Grammar_tools/Phonological_Features/Phonological_Features_overview.md)

  - Feature name [abbreviation](../../Field_Descriptions/Grammar/Phonological_Features_fields/Abbreviation_field_(Ph_Features).md) and value name [abbreviation](../../Field_Descriptions/Grammar/Phonological_Features_fields/Abbreviation_field_(Value_Ph_Features).md).

- [Phonological Rules](../../../Using_Tools/Grammar_tools/Phonological_Rules/Phonological_Rules_overview.md)

  - The [order](../../../Using_Tools/Grammar_tools/Phonological_Rules/Specify_order_number.md) of phonological and metathesis rules.

Generally speaking, the way classical generative phonological rules like these work, one starts with an "underlying form" and then passes that through the series of ordered rules. The output of one rule is the input to the next rule, and the final result is the output of the final rule.

> [!IMPORTANT]
>
> - To make this parser function efficiently as a *Phonological Rule-based* parser, observe the following:
>
> - - Every phoneme used in the orthography must be defined as a phoneme. This includes orthographic hyphens and other characters.
>
>   - The phonological features need to uniquely identify each phoneme, including orthographic hyphens. It is crucial that every phoneme be uniquely identified by its phonological features.
>
>   - Fully specify each phoneme (not minimal specificity).
>
>   - Phonological features used in a rule should be explicit.
>
>   - Using a phoneme in a rule is more efficient (instead of some of its distinctive features).
>
>   - Avoid using archiphonemes that are upper case equivalents of a character in your orthography.
>
>   - Make sure every affix process rule is complete.
>
>   - For more information about this parser, on the [Help](../Help/Help_overview.md) menu, point to **Resources**, and then click **Introduction to Parsing**.
>
> - This parser handles only one word at a time, so the [Parse result](../../Field_Descriptions/Texts_&_Words/Parse_result_field.md) field will not show "**Successful**" for phrases, such as idioms.
>
> - See [Create a Pattern-Matching entry](../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Create_a_Template_Entry.md) for the **GuessRoots** feature. See Also: [About parser parameters](About_parser_parameters.md).

> [!TIP]
>
> - You can make a rule available (Active) or unavailable to parsers.**\
>   See:** [Active field (Ad hoc Rules)](../../Field_Descriptions/Grammar/Ad_hoc_Rules_fields/Active_field_Ad_Hoc_Rules.md), [Active field (Compound Rules)](../../Field_Descriptions/Grammar/Compound_Rules_fields/Compound_Rules_fields_overview.md), or [Active field (Phonological Rules)](../../Field_Descriptions/Grammar/Phonologocial_Rules_fields/Active_field_(Ph_Rules).md).
>
> - You can make an affix template table available (Active) or unavailable to parsers.**\
>   See:** [Active field (Affix Templates)](../../Field_Descriptions/Grammar/Category_Edit_fields/Active_field_templates.md).
>
> - **See Also:** [Strata as a string in the Hermit Crab properties](Strata_as_a_String_in_the_Hermit_Crab_properties.md)

## Related topics
[About morpheme types](../../../Using_Tools/Lists_tools/About_Morpheme_Types.md)

[FieldWorks Project Utilities overview](../Tools/Language_Project_Utilities_overview.md)

[Parser menu overview](Parser_menu_overview.md)

[Required Features field](../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/required_features.md)

[Words Analyses overview](../../../Using_Tools/Texts_&_Words_tools/Word_Analyses/Word_Analyses_overview.md)
