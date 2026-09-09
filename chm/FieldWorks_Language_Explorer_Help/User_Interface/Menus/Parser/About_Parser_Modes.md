---
title: "About Interlinear Modes"
source_title: "About Interlinear Modes"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Parser"
  - "About Interlinear Modes"
source: "User_Interface/Menus/Parser/About_Parser_Modes.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Parser/About_Parser_Modes.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "About Interlinear Modes"
  - "Interlinear Modes (about)"
  - "Modes for Interlinear"
  - "Parser"
related:
  - "Interlinear views colors -> ../../../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/interlinear_views_colors.md"
  - "Parser menu overview -> Parser_menu_overview.md"
  - "Parsing words overview -> Parsing_words_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:6cb87affcbd40f60"
---

# About Interlinear Modes

*User Interface › Menus › Parser*

On the **Parser** [menu](Parser_menu_overview.md), you can select one of these two interlinear modes: **Text Glossing** or **Parsing Development**.

- The **Text Glossing** mode prioritizes the user opinion.

Select this mode if your goal is to get as much text glossed as possible, and you don't care if the automatic parser is set up with all the details of the language you are describing.

- The **Parsing Development** mode prioritizes the [parser](Parsing_words_overview.md) opinion.

Select this mode if you are working on setting up the parser to recognize valid words, or have the parser fail when it encounters invalid words.

Sometimes the process of getting the parser to recognized more valid words is enough to also rule out some invalid words, but often that is a side effect. Sometimes "ruling out" takes a more specific effort. And whether that effort is worth it is a decision each user would need to make individually. You might want to [get more help](../../../Overview/Technical_support.md).

> [!NOTE]
>
> - The colors you see in the interlinear are discussed in the topic called [Interlinear views colors](../../../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/interlinear_views_colors.md).
>
> - The differences between these modes include:
>
> - When a word is approved in the **Parsing Development** mode, an outline is shown around it to make it more clear whether the parser gave a successful analysis for it or not. In the **Text Glossing** mode, there is no outline.
>
> - If the outline is blue, it means that the chosen analysis either failed in the parser, or has not yet been tested by the parser yet.
>
> - If the outline is tan, then the chosen analysis was successful in the parser, regardless of what the user has said about it.
>
> - Note that there may be additional analyses besides the one that is showing, and some may be successful in the parser or disapproved by the user. The outline is only giving information about the chosen analysis.
>
> - When a word has not been approved, then in both modes the solid shading indicates whether the suggestion that is showing came from the parser or from the user (or the lexicon).
>
> - When a word has more than one analysis, the list of possible analyses (that you see when you click on the **Word** line) presents the analyses in a specific order, based on priority.
>
> Different priorities are used in the two modes.
>
> - In both modes, the analysis at the top of the list is the one showing, and the shading only applies to the analysis that is showing. There may be other analyses with different opinions.
>
> - When a word has an analysis that is approved by both the user and the parser, the **Text Glossing** mode places the user analysis higher in the list, whereas the **Parsing Development** mode places the parser analysis higher.
>
> - When a word has one analysis that is approved by the parser but not the user, and another approved by the user but not the parser, then in the **Parsing Development** mode, the parser-approved analysis will have priority, whereas in the **Text Glossing** mode the user-approve analysis will have priority.
>
> - When a word has an analysis that is Disapproved by the user, in the **Parsing Development** mode this will not prevent a parser-approved analysis from showing. In the **Text Glossing** mode, the word will appear the same as a word that doesn't parse, even if there is a parser-approved analysis.

## Related topics
[Interlinear views colors](../../../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/interlinear_views_colors.md)

[Parser menu overview](Parser_menu_overview.md)

[Parsing words overview](Parsing_words_overview.md)
