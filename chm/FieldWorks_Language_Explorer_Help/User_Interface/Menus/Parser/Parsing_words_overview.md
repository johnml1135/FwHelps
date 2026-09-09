---
title: "Parsing words overview"
source_title: "Parsing words overview"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Parser"
  - "Parsing words overview"
source: "User_Interface/Menus/Parser/Parsing_words_overview.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Parser/Parsing_words_overview.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Parser"
  - "Parser:Parsing words overview"
  - "Parsing Words"
  - "Parsing Words:Parsing words overview"
  - "Parse words"
  - "Parse words:Parsing words overview"
related:
  - "Parser menu overview -> Parser_menu_overview.md"
  - "Try a Word -> Try_a_word.md"
  - "Try a Word additional information -> Try_a_Word_additional_information.md"
fw_help_version: "9.3"
type: "index"
content_hash: "sha256:398180af5d185159"
---

# Parsing words overview

*User Interface › Menus › Parser*

As stated in [Texts & Words overview](../../../Using_Tools/Texts_&_Words_tools/Texts_and_Words_overview.md), you "*parse"* wordforms (words) that are in texts in the **Texts & Words** area.

Parsing is not limited to one method or starting point. You can

- [manually analyze](../../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/Analyze_Text_overview.md) (manually "parse") *or* [manually gloss](../../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/specify_the_word_gloss.md) words

  - use ([approve](../Data/Data_overview.md)) analyses *suggested* by FLEx, based on previous manual analyses of identically spelled words

- use the [default](Default_XAmple_parser_overview.md) computational parser to *produce* analyses, or

- try the [Phonological Rule-based](Phonological_Rule_Based_parser_overview.md) computational parser to *produce* analyses.

Different [background colors](../../../using_tools/texts_&_words_tools/Interlinear_Texts/interlinear_views_background_colors.md) indicate if an analysis was *suggested* by FLEx or *produced* by a computational parser.

## Computational Parsing

To use either computational parser, *you need to develop constraints so the parser does not produce incorrect analyses and runs efficiently*. Constraints include various items of grammatical information that are stored in both [Lexicon Edit](../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md) and [Grammar](../../../Using_Tools/Grammar_tools/grammar_overview.md).

- [Parsing words (XAmple)](Parsing_words.md) lists the information used by the default parser.

- [Parsing words (Hermit Crab)](Parsing_words_(HermitCrab).md) lists the information used by this parser.

It is expected that the Hermit Crab parser will use all the information used by the default parser, and additionally, phonological rules, phonemes and their phonological features, and so on.

It is also expected that the default parser will be sufficient for all of the computational parsing needs of most users. *Some* users may need the Hermit Crab phonological rule-based parser for *some* of the words in their texts.

> [!IMPORTANT]
>
> - Here is another way to understand the difference between *manually* [analyzing](../../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/Analyze_Text_overview.md) words and using a computational [parser](Parsing_words_overview.md):
>
> <!-- -->
>
> - - Manual analyses: You make all the morpheme breaks yourself and the Language Explorer program suggests analyses you have made before when the very same word recurs.
>
>   - Computational parser: The parser suggests possible analyses for words that are brand new, if the lexicon has entries for each morpheme.
>
> - Example: Suppose *plays* and *walked* were analyzed (parsed) and that all four morphemes exist as lexical entries.
>
> <!-- -->
>
> - Without a parser running, Language Explorer will propose suggestions for future occurrences of *plays* and *walked* (light blue background color).
>
> - With a parser running, when you subsequently encounter *played* and *walks*, the parser will produce analysis suggestions (tan background [color](../../../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/interlinear_views_colors.md)) for these new words.
>
> <!-- -->
>
> - When both kinds of suggestions are available for a word, the program will suggest a user analysis (manual) in preference to a *parser-*produced analysis.
>
> - When more than one user analyses are available for a word, the program will suggest the one that is most frequently used.
>
> - Your colors may appear differently due to different screens or screen settings.
>
> - You can test the parser and see [parser reports](Parser_Test_Reports.md).
>
> - For a more complete discussion, on the [Help](../Help/Help_overview.md) menu, point to **Resources** and then click **Introduction to Parsing**.
>
> - - [Morphology and Parsing Tasks overview](../../../Morphology_and_Parsing_Tasks/Morphology_Parsing_Tasks_overview.md) lists some examples that were reproduced in these Helps.
>
> <!-- -->
>
> - **See Also:** [About the Novel Root Guesser](About_the_Novel_Root_Guesser.md) and [Strata as a string in the Hermit Crab properties](Strata_as_a_String_in_the_Hermit_Crab_properties.md).

## Related topics
[Parser menu overview](Parser_menu_overview.md)

[Try a Word](Try_a_word.md)

[Try a Word additional information](Try_a_Word_additional_information.md)
