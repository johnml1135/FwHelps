---
title: "Phonological Rule Based parser overview"
source_title: "Phonological Rule Based parser overview"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Parser"
  - "Phonological Rule-based (HC) parser overview"
source: "User_Interface/Menus/Parser/Phonological_Rule_Based_parser_overview.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Parser/Phonological_Rule_Based_parser_overview.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Parser:Phonological Rule Based parser overview"
related:
  - "Choose excluded properties -> ../../../Using_Tools/Grammar_tools/Phonological_Rules/Choose_excluded_properties.md"
  - "Choose required properties -> ../../../Using_Tools/Grammar_tools/Phonological_Rules/Choose_required_properties.md"
  - "Choose required categories -> ../../../Using_Tools/Grammar_tools/Phonological_Rules/Choose_required_categories.md"
  - "Parsing words overview -> Parsing_words_overview.md"
fw_help_version: "9.3"
type: "index"
content_hash: "sha256:3b44d78b27d2a9de"
---

# Phonological Rule Based parser overview

*User Interface › Menus › Parser*

The phonological rule-based (Hermit Crab) parser is a computational tool that produces an analysis for a given word form. You can choose it on the [Parser menu](Parser_menu_overview.md).

[Parsing words](Parsing_words_(HermitCrab).md) lists the required information that this parser uses to produce an analysis.

- This parser offers an *item and process* approach for both affixation and morphophonemics. That is, you can describe affixes as processes (such as infixation or reduplication) and you can also describe phonological rules.

- It is expected to work with the *item and arrangement* approach of the default (**XAmple**) parser. This means that you should be able to move *from* an item and arrangement description *to* an item and process description as you determine what these processes are.

  When you get to the point of trying this new parser and want to use processes, how might you describe such a process? That is, what are the pieces of a process? The approach we take is to think of what the input pattern is and then what the resulting output of the process should be. Therefore, all process rules will have an input pattern component and an output result component.

- Further, given the way this parser works for both affixes and phonology, you need to think generatively.

  For phonological rules, the rules are applied in order from the underlying form to the surface form.

  For affixation, the word is built from the root out. That is, each affix is attached to what has been built so far during the derivation.

  By contrast, the default (**XAmple**) parser searches for surface forms from the beginning of the word to the end of the word; that is, it basically looks for prefixes first, then roots, then suffixes.

> [!IMPORTANT]
>
> - For the most complete documentation, on the [Help](../Help/Help_overview.md) menu, point to **Resources**, and then click **Introduction to Parsing**.
>
> - It is recommended that if you want to try this parser, start in either a [backed up copy](../File/Backup_and_Restore/Backup_and_Restore_overview.md) of your main language project or a small test language project. You may want to request [technical support](../../../Overview/Technical_support.md).
>
>   Please [report](../../../Overview/information_for_bug_reports.md) anything that you notice about this new parser that might help us make it more effective.
>
> - Using this parser, or the [default (XAmple) parser](Default_XAmple_parser_overview.md), *contrasts* with [manually analyzing](../../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/Analyze_Text_overview.md) or [manually glossing](../../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/specify_the_word_gloss.md) the words in a text. It also *contrasts* with FieldWorks program-proposed analyses that are based on a previous user analysis that was manually done for an identically spelled word. These different analyses initially appear with different [background colors](../../../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/interlinear_views_colors.md).

## Related topics
[Choose excluded properties](../../../Using_Tools/Grammar_tools/Phonological_Rules/Choose_excluded_properties.md)

[Choose required properties](../../../Using_Tools/Grammar_tools/Phonological_Rules/Choose_required_properties.md)

[Choose required categories](../../../Using_Tools/Grammar_tools/Phonological_Rules/Choose_required_categories.md)

[Parsing words overview](Parsing_words_overview.md)
