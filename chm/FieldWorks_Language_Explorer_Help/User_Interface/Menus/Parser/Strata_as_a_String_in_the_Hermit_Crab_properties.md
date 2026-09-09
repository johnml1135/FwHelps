---
title: "Strata as a String in the Hermit Crab properties"
source_title: "Strata as a String in the Hermit Crab properties"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Parser"
  - "Strata as a String in the Hermit Crab properties"
source: "User_Interface/Menus/Parser/Strata_as_a_String_in_the_Hermit_Crab_properties.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Parser/Strata_as_a_String_in_the_Hermit_Crab_properties.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Hermit Crab strata as a string"
  - "Strata as a string Hermit Crab properties"
related:
  - "About parser parameters -> About_parser_parameters.md"
  - "Affix Process Rule field -> ../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Affix_Process_Rule_field.md"
  - "Affix Process Rule field -> ../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Affix_Process_Rule_fldAF.md"
  - "Build an Affix Process Rule -> ../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Build_Affix_Process_Rule.md"
  - "Parsing Words (Hermit Crab parser) -> Parsing_words_(HermitCrab).md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:89a925692ea5c61a"
---

# Strata as a String in the Hermit Crab properties

*User Interface › Menus › Parser*

The notion of “strata” (levels) is a mechanism in the Hermit Crab parser that affects how it tries to break words into morphemes and where it attempts to apply phonological rules.

There are some strata that are built in to the Hermit Crab parser, and also a default sequence. The built-in strata (and their default sequence) are:

-  Morphology

  -  Compound Rules: All rules specified in the Compound Rules view of the Grammar area

  -  All derivational affixes, any affixes that are not specified for inflectional or derivational, and inflectional affixes that are not attached to a template

  -  Templates: all inflectional affixes that are attached to one or more slots of a template

-  Phonology: All phonological rules

-  Clitics: All clitic entries

If you want to modify this sequence, create a string that lists some of the strata, and possibly one or more specific affixes or phonological rules. When a specific item is listed, then the group that it would normally be in becomes “everything in that group except the item mentioned explicitly.”

For example if you want to order the specific phonological rules called PhonRule1 and PhonRule2 after the application of Clitics, we could create a Strata Sequence like this:

-  Strata: Morphology, Templates, Phonology, Clitics, (PhonRule1, PhonRule2)

In this case, “Phonology” means “all phonological rules except PhonRule1 and PhonRule2”. Within the stratum specified by the parentheses, the rules are unordered; the ordering happens in FLEx. PhonRule1 and PhonRule2 represent the name of the rule as specified in the Name field in the Phonological Rules tool in the Grammar area of FLEx.

Sometimes there are affixes that slow down the parser a lot, and moving them to a different location in the sequence might make a difference. Often affixes that achieve reduplication are candidates for this. If you want to do this for affixes named Affix10, Affix11, and Affix12, you might set up a Strata Sequence like this:

-  Strata: Morphology, Templates, (Affix10, Affix11, Affix12), Phonology, Clitics

In this case, the “Morphology” stratum considers all non-inflectional affixes except Affix10, Affix11, and Affix12, and then all the inflectional affixes (that is, those that are in templates) are considered. Next the affixes Affix10, Affix11, and Affix12 would be considered. Then all the phonological rule, and then the clitics.

There are various defaults about the strata related to whether they are mentioned explicitly or not:

-  If nothing is specified relative to strata, the default sequence is:

  -  Morphology, Phonology, Clitics

-  If the CompoundRules and Templates strata are not mentioned explicitly, they are included in Morphology.

-  If Morphology is not mentioned, it is the first stratum.

-  If Clitics is not mentioned, it is the final stratum.

-  If Phonology is not mentioned, it comes between Morphology and Clitics (but see Note below).

Normally phonological rules are not applied to clitics. But there is a setting in Parser Parameters called NotOnClitics that affects this.

NotOnClitics set to true is equivalent to:

-  Strata: Morphology, Phonology, Clitics

NotOnClitics set to false is equivalent to:

-  Strata: Morphology, Clitics, Phonology

The default value for NotOnClitics is True. Refer to [Edit]() [Parser]() [Parameters]() for how to adjust it.

To specify an affix in a stratum, use its Headword. (That is, its Citation Form if it has one, or else its Lexeme Form.) You need to include the token for its Morpheme Type. Thus, if Affix10 is a prefix, then you would specify it as Affix10-. To specify a Template, use what is in the Template Name field for that Template in the Category Edit view of the Grammar area. To specify a phonological rule, use what is in the Name field in the Phonological Rules tool in the Grammar area of FLEx. Use whatever Writing System is currently the Primary Analysis Writing System. Be sure that each item has a name filled in in that Writing System.

## Related topics
[About parser parameters](About_parser_parameters.md)

[Affix Process Rule field](../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Affix_Process_Rule_field.md) or [Affix Process Rule field](../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Affix_Process_Rule_fldAF.md)

[Build an Affix Process Rule](../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Build_Affix_Process_Rule.md)

[Parsing Words (Hermit Crab parser)](Parsing_words_(HermitCrab).md)
