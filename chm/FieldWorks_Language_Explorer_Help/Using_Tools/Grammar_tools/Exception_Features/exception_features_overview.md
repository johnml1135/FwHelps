---
title: "Exception Features overview"
source_title: "Exception Features overview"
breadcrumb:
  - "Using Tools"
  - "Grammar tools"
  - "Exception \"Features\""
  - "Exception \"Features\" overview"
source: "Using_Tools/Grammar_tools/Exception_Features/exception_features_overview.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Grammar_tools/Exception_Features/exception_features_overview.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Features"
  - "Exception Features overview"
  - "Exception Feature:Exception Features overview"
related:
  - "Choose exception \"features\" -> ../../Lexicon_tools/Lexicon_Edit/choose_exception_features.md"
  - "Exception Features fields overview -> ../../../User_Interface/Field_Descriptions/Grammar/Exception_Features_fields/Exception_Features_fields_overview.md"
  - "Grammar overview -> ../grammar_overview.md"
fw_help_version: "9.3"
type: "index"
content_hash: "sha256:58962f84f8e9e749"
---

# Exception Features overview

*Using Tools › Grammar tools › Exception \"Features\"*

**Exception "Features"** are used in the [Lexicon](../../Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md) **Exception Features** field.

Even when one has correctly classified the affixes in a language as being derivational or inflectional, sometimes a morphological parser will find combinations of stem and affix that are simply incorrect.

[Parsers](../../../User_Interface/Menus/Parser/Parsing_words_overview.md) allow you to rule out incorrect combinations using exception “features.” The basic idea is to tag the affix with an exception “feature.” The only time the parser will then allow this affix to occur is when the stem to which it attaches also has been **tagged with the same** exception “feature.” Thus, you can restrict the productivity of the affix to occur only on certain stems. Note that this is only possible for affixes that have been classified as either being derivational or inflectional. Exception “features” are *not* available for unclassified affixes.

If a given affix has two or more exception “features,” then the stem to which it attaches must be tagged with all of the exception “features” that the affix has. Note that if an affix does not have any exception “features” but the stem to which it is being attached does have one or more exception “features,” then the affix will still be allowed to attach (as far as the exception “features” are concerned).

The **Exception** "**Features"** `Help` topics are the following:

[Insert an exception "feature"](insert_an_exception_feature.md)

[Delete an exception "feature"](Delete_an_Exception_Feature.md)

## Related topics
[Choose exception "features"](../../Lexicon_tools/Lexicon_Edit/choose_exception_features.md) (**Lexicon Edit**)

[Exception Features fields overview](../../../User_Interface/Field_Descriptions/Grammar/Exception_Features_fields/Exception_Features_fields_overview.md)

[Grammar overview](../grammar_overview.md)
