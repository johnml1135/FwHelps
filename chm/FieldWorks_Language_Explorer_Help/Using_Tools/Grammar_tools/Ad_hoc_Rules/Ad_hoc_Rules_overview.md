---
title: "Ad hoc Co-occurrence Prevention Rules overview"
source_title: "Ad hoc Co-occurrence Prevention Rules overview"
breadcrumb:
  - "Using Tools"
  - "Grammar tools"
  - "Ad hoc Rules"
  - "Ad hoc Co-occurrence Prevention Rules overview"
source: "Using_Tools/Grammar_tools/Ad_hoc_Rules/Ad_hoc_Rules_overview.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Grammar_tools/Ad_hoc_Rules/Ad_hoc_Rules_overview.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Ad hoc Rules"
  - "Types:Ad hoc Co-occurrence Prevention Rules overview"
related:
  - "Ad hoc Rules fields overview -> ../../../User_Interface/Field_Descriptions/Grammar/Ad_hoc_Rules_fields/Ad_hoc_Rules_fields_overview.md"
  - "Grammar overview -> ../grammar_overview.md"
fw_help_version: "9.3"
type: "index"
content_hash: "sha256:abfff280eb9f5368"
---

# Ad hoc Co-occurrence Prevention Rules overview

*Using Tools › Grammar tools › Ad hoc Rules*

When one uses a morphological parser, like the parser offered in the FieldWorks Language Explorer (FLEx), it is not unusual for the parser to sometimes return a parse that is simply incorrect. These are sometimes due to allomorphs matching in places one would have not expected them to match. When one has used all the mechanisms provided by the parser to the best of one's ability and such incorrect parses continue to surface, one may well wish for some kind of mechanism to rule them out. FLEx provides "Ad hoc Co-occurrence prevention rules" for such situations. Note that it may be the case that later stages of this program will provide more well-motivated means to rule out these infelicitous parses, but for now, these ad hoc solutions suffice.

There are two main types of ad hoc co-occurrence prevention rules: morpheme-oriented and allomorph-oriented. If the crucial piece of information is an allomorph, use an allomorph-oriented one. If instead, it is the morpheme itself, no matter what form it surfaces as, use a morpheme-oriented one. You may also group two or more ad hoc rules together. **See:** [About Ad hoc Groups](About_Ad_hoc_Groups.md).

Ad hoc co-occurrence prevention rules are used by a parser while [parsing words](../../../User_Interface/Menus/Parser/Parsing_words_overview.md).

The **Ad hoc Rules** `Help` topics are the following:

[Ad hoc rules field content sources](Ad_hoc_Rules_field_content_sources.md)

[Delete an ad hoc rule](delete_an_ad_hoc_rule.md)

[Insert an ad hoc group](insert_an_ad_hoc_group.md)

[Insert an allomorph ad hoc rule](insert_an_allomorph_ad_hoc_rule.md)

[Insert a morpheme ad hoc rule](Insert_a_morpheme_ad_hoc_rule.md)

> [!TIP]
>
> - For a more complete description of ad hoc rules, point to **Resources** on the [Help](../../../User_Interface/Menus/Help/Help_overview.md) menu, and then click **Introduction to Parsing**.

## Related topics
[Ad hoc Rules fields overview](../../../User_Interface/Field_Descriptions/Grammar/Ad_hoc_Rules_fields/Ad_hoc_Rules_fields_overview.md)

[Grammar overview](../grammar_overview.md)
