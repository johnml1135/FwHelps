---
title: "Default XAmple parser overview"
source_title: "Default XAmple parser overview"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Parser"
  - "Default XAmple parser overview"
source: "User_Interface/Menus/Parser/Default_XAmple_parser_overview.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Parser/Default_XAmple_parser_overview.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Parser:Default XAmple parser overview"
related:
  - "Parser menu overview -> Parser_menu_overview.md"
  - "Parsing words overview -> Parsing_words_overview.md"
fw_help_version: "9.3"
type: "index"
content_hash: "sha256:f7165c83756f8222"
---

# Default XAmple parser overview

*User Interface › Menus › Parser*

The default (XAmple) parser is a computational tool that produces a morphological analysis for a given word form. You can choose it on the [Parser menu](Parser_menu_overview.md).

[Parsing words](Parsing_words.md) lists the required information that this parser uses to produce an analysis. Generally speaking, to produce a morphological analysis, the parser needs to do the following:

- Find the affixes and stem(s) in the given word.

  - To do this, the parser needs to know forms (and glosses) of stems and affixes.

- Apply "constraints" to make sure the affixes can go with the rest of the word (stem and other affixes):

  - Which affixes can go with which stems.

  - The relative order of the affixes.

  - When a particular shape of a form is legitimate or when it is not.

This parser uses an *item and arrangement* approach. The [phonological rule-based parser](Parsing_words_(HermitCrab).md) uses an *item and process* approach.

> [!IMPORTANT]
>
> - Using this computational parser, or the phonological rule-based parser, *contrasts* with [manually analyzing](../../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/Analyze_Text_overview.md) or [manually glossing](../../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/specify_the_word_gloss.md) the words in a text.
>
> - It also *contrasts* with FieldWorks *program-proposed* analyses that are based on a previous user analysis that was manually done for an identically spelled word. These different analyses initially appear with different [background colors](../../../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/interlinear_views_colors.md).

## Related topics
[Parser menu overview](Parser_menu_overview.md)

[Parsing words overview](Parsing_words_overview.md)
