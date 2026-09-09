---
title: "Parsing words (XAmple Parser)"
source_title: "Parsing words (XAmple Parser)"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Parser"
  - "Parsing words (XAmple Parser)"
source: "User_Interface/Menus/Parser/Parsing_words.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Parser/Parsing_words.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Parser:Parsing words (XAmple Parser)"
  - "Order (see also Move)"
  - "Allomorph:Allomorph order for parser"
related:
  - "About morpheme types -> ../../../Using_Tools/Lists_tools/About_Morpheme_Types.md"
  - "FieldWorks Project Utilities overview -> ../Tools/Language_Project_Utilities_overview.md"
  - "Parser menu overview -> Parser_menu_overview.md"
  - "Parsing words overview -> Parsing_words_overview.md"
  - "Required Features field -> ../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/required_features.md"
  - "Words Analyses overview -> ../../../Using_Tools/Texts_&_Words_tools/Word_Analyses/Word_Analyses_overview.md"
fw_help_version: "9.3"
page_heading: "Parsing words (XAmple)"
type: "topic"
content_hash: "sha256:b5cefa63317ca2f6"
---

# Parsing words (XAmple Parser)

*User Interface › Menus › Parser*

The XAmple parser is the *default* computational [parser](Parser_menu_overview.md) in FieldWorks Language Explorer.

Your lexical entries and grammatical information define your current understanding of the overall word grammar of the language you are working on. The parser *uses* that information to produce analyses of [words](../../../Using_Tools/Texts_&_Words_tools/Word_list_overview.md) in [Texts & Words](../../../Using_Tools/Texts_&_Words_tools/Texts_and_Words_overview.md).

The accuracy of the analyses produced by this parser *directly* reflects the quality and completeness of the information you have entered in the **Lexicon** and the **Grammar** areas. You can see a summary of that information in the [Grammar Sketch](../../../Using_Tools/Grammar_tools/Grammar_Sketch/Grammar_Sketch_overview.md).

From [Lexicon](../../../Using_Tools/Lexicon_tools/Lexicon_overview.md), parsers use the following information (much of which is stored in **Grammar**):

- [Lexeme Form](../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Create_a_lexical_entry.md), [Affix Allomorphs](../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Insert_an_alternate_form.md) and [Stem Allomorphs](../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Insert_an_alternate_form.md), including:

  - [morpheme types](../../../Using_Tools/Lexicon_tools/Lexicon_Edit/change_the_morph_type.md)

  - [Grammatical Info](../../../Using_Tools/Lexicon_tools/Lexicon_Edit/change_the_grammatical_info.md), and any

  - [environments](../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_environments.md), [inflection classes](../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_an_inflection_class.md), [inflection features](../../../Using_Tools/Lexicon_tools/Lexicon_Edit/choose_inflection_features.md)/[Required Features](../../../Using_Tools/Lexicon_tools/Lexicon_Edit/choose_inflection_features.md), [Stem Allomorph Labels](../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_Stem_Allomorph_Label.md) and [Exception "Features"](../../../Using_Tools/Lexicon_tools/Lexicon_Edit/choose_exception_features.md). However, the parser ignore these for entries with [Is Abstract Form](../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_a_Form_is_Abstract.md) selected.

From [Grammar](../../../Using_Tools/Grammar_tools/grammar_overview.md), parsers use the following information:

- [Ad hoc co-occurrence prevention rules](../../../Using_Tools/Grammar_tools/Ad_hoc_Rules/Ad_hoc_Rules_overview.md)

- [Compound Rules](../../../Using_Tools/Grammar_tools/Compound_Rules/Compound_Rules_overview.md)

- Inflectional affixes in [slots](../../../Using_Tools/Grammar_tools/Category_Edit/Edit_an_Affix_Template_Table.md) which are in [affix template tables](../../../Using_Tools/Grammar_tools/Category_Edit/affix_template_table_example.md).

> [!IMPORTANT]
>
> - Allomorph order is *very* **important** for the parser, which works with the forms in this order: first allomorph, second allomorph, ..., nth allomorph, *then* lexeme form. You can [move allomorphs](../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Move_Allomorph.md) to change their order. This is particularly important when environments are used to constrain the forms as each allomorph automatically *inherits* the negation of the environments of any *preceding* allomorphs.
>
> - For more information, on the [Help](../Help/Help_overview.md) menu, point to **Resources**, and then click **Introduction to Parsing**. *Order of allomorphs* within a lexical entry is discussed in sections 3 and 4.
>
>   The **Introduction to Parsing** document also discusses, for example, affix allomorphs conditioned by inflection features (section 3), and how morpheme types are significant to the parser (section 4).
>
> - For words that require the use of [word-forming apostrophes](../Insert/wordforming_apostophes.md), you *must* use the correct apostrophe. Glottal stops are similar.
>
> - The parser handles only one word at a time, so the [Parse result](../../Field_Descriptions/Texts_&_Words/Parse_result_field.md) field will not show "**Successful**" for phrases, such as idioms.

> [!TIP]
>
> - You can make a rule available (Active) or unavailable to parsers.**\
>   See:** [Active field (Ad hoc Rules)](../../Field_Descriptions/Grammar/Ad_hoc_Rules_fields/Active_field_Ad_Hoc_Rules.md), [Active field (Compound Rules)](../../Field_Descriptions/Grammar/Compound_Rules_fields/Compound_Rules_fields_overview.md), or [Active field (Phonological Rules)](../../Field_Descriptions/Grammar/Phonologocial_Rules_fields/Active_field_(Ph_Rules).md).
>
> - You can make an affix template table available (Active) or unavailable to parsers.**\
>   See:** [Active field (Affix Templates)](../../Field_Descriptions/Grammar/Category_Edit_fields/Active_field_templates.md).

## Related topics
[About morpheme types](../../../Using_Tools/Lists_tools/About_Morpheme_Types.md)

[FieldWorks Project Utilities overview](../Tools/Language_Project_Utilities_overview.md)

[Parser menu overview](Parser_menu_overview.md)

[Parsing words overview](Parsing_words_overview.md)

[Required Features field](../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/required_features.md)

[Words Analyses overview](../../../Using_Tools/Texts_&_Words_tools/Word_Analyses/Word_Analyses_overview.md)
