---
title: "About Inflection Features and Feature Types"
source_title: "About Inflection Features and Feature Types"
breadcrumb:
  - "Using Tools"
  - "Grammar tools"
  - "Inflection Features"
  - "About features and feature types"
source: "Using_Tools/Grammar_tools/Inflection_Features/About_Infl_Features_and_Types.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Grammar_tools/Inflection_Features/About_Infl_Features_and_Types.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Inflection Features:About Inflection Features and Feature Types"
  - "Feature Types (Lists):About Inflection Features and Feature Types"
  - "About:Features and Feature Types"
  - "Gender"
related:
  - "Grammar overview -> ../grammar_overview.md"
  - "Parser menu overview -> ../../../User_Interface/Menus/Parser/Parser_menu_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:08974407b50cf7ed"
---

# About Inflection Features and Feature Types

*Using Tools › Grammar tools › Inflection Features*

FieldWorks Language Explorer (FLEx) allows you to define a morpho-syntactic feature system for the language you are working on. The inflection feature system is in addition to [phonological features](../Phonological_Features/About_Phonological_Features.md). This system consists of **Inflection Features** and **Feature Types**, and is included in the [Grammar Sketch](../Grammar_Sketch/Grammar_Sketch_overview.md). Inflection features are used to indicate things like gender and noun class in lexical entries. Computational [parsers](../../../User_Interface/Menus/Parser/Parsing_words_overview.md) also use them in various ways.

Inflection features and feature types are added automatically when you use the [Morphosyntactic Gloss Assistant](../../Lexicon_tools/Lexicon_Edit/Using_Morphosyntactic_Gloss_Assistant.md). For example, we can model things like gender and noun class using features. Without features, we would need to create distinct subcategories, say, for example feminine, masculine, and so on, or for noun class 1, noun class 2, and so on.

If you did not use the **Morphosyntactic Gloss Assistant**, or need to change or add an additional inflection feature, use the **Add Inflection Feature from Catalog** dialog box. *Avoid creating a new feature* unless *the feature you need is not in the catalog*. When you use the catalog, the features are correctly added to the system.

If you need to *manually* add or edit features or feature types, FLEx allows you to do so. **See** [Inflection Features overview](Inflection_Features_overview.md) and [Feature Types overview](../../Lists_tools/Feature_Types/Feature_Types_overview.md).

> [!TIP]
>
> - A *simple* feature is a pairing of a name with a value, such as `tense:present tense`, `aspect:perfective aspect`, and so on.
>
>   A *complex* feature is a named collection of two or more simple features, such as “`[`**subject agreement:\[person:third person, gender:feminine gender\]**`]`” where the collection name is “**subject agreement**” and the collection consists of two feature:values pairs: “**person:third person**” and “**gender:feminine gender**.”
>
>   [Feature types](../../Lists_tools/Feature_Types/Feature_Types_overview.md) are used to limit the set of feature:value pairs that are appropriate for certain situations, such as when dealing with agreement features.
>
> - You can use [Feature Sets](../../../User_Interface/Field_Descriptions/Grammar/Category_Edit_fields/Feature_Set_field_Category_Edit.md) with [Stem Allomorph Labels](../../../User_Interface/Field_Descriptions/Grammar/Category_Edit_fields/Stem_Allomorph_Label_field.md) to control stem allomorphy. [Insert a Stem Allomorph Label](../Category_Edit/Insert_a_Stem_Allomorph_Label.md) has more information.

> [!IMPORTANT]
>
> - It is *strongly recommended* that you [contact](../../../Overview/Technical_support.md) a FLEx consultant before you overtly add or edit features or feature types. If these are not handled correctly, [parsers](../../../User_Interface/Menus/Parser/Parsing_words_overview.md) may not analyze many of your wordforms.
>
> - For additional information about features and feature types, point to **Resources** on the [Help](../../../User_Interface/Menus/Help/Help_overview.md) menu, and then click **Introduction to Parsing**.

## Related topics
[Grammar overview](../grammar_overview.md)

[Parser menu overview](../../../User_Interface/Menus/Parser/Parser_menu_overview.md)
