---
title: "Create a Pattern Matching Entry"
source_title: "Create a Pattern Matching Entry"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Lexicon Edit"
  - "Create a Pattern Matching Entry"
source: "Using_Tools/Lexicon_tools/Lexicon_Edit/Create_a_Template_Entry.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Lexicon_Edit/Create_a_Template_Entry.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Create"
  - "Create a Pattern Matching Entry"
  - "Pattern Matching Entry"
  - "Create:Create a Pattern-Matching Entry"
related:
  - "Lexicon Edit fields overview -> ../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Lexicon_Edit_fields_overview.md"
  - "Lexicon Edit overview -> lexicon_edit_overview.md"
  - "Parsing words overview -> ../../../User_Interface/Menus/Parser/Parsing_words_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:670be7a1bc7fac6b"
---

# Create a Pattern Matching Entry

*Using Tools › Lexicon tools › Lexicon Edit*

[About parser parameters](../../../User_Interface/Menus/Parser/About_parser_parameters.md) informs you that **GuessRoots** is one of the parameters you can select in the **Parser Parameters** dialog box.

[About the Novel Root Guesser](../../../User_Interface/Menus/Parser/About_the_Novel_Root_Guesser.md) provides an overview of the *Novel Root Guesser* feature.

If you will use the Hermit Crab (HC) parser to guess roots, you will need to create one or more *pattern-matching* entries. If you have not created at least one pattern-matching entry, then root guessing *will not happen* even when **GuessRoots** is selected.

- [Create a lexical entry](Create_a_lexical_entry.md) with a [Lexeme Form](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Lexeme_Form_field.md) that is a pattern constructed from [natural classes.](../../Grammar_tools/Natural_Classes/Natural_classes_overview.md)

Then, that entry is used as a pattern-matching entry by the root guesser.

- You can create the pattern from any natural class that is defined in the **Natural Classes** [tool](../../Grammar_tools/Natural_Classes/Natural_classes_overview.md) ([Grammar](../../Grammar_tools/grammar_overview.md)).

- If you need to refer to "any possible character", you can create a natural class for that. For example, you might create a natural class based on features, name it Segment, with the abbreviation Seg, and define it as having the feature Seg:+

- When constructing a pattern in an entry, the elements you can use are:

- A natural class will match any single character in that natural class. Examples: \[C\]\[V\] or \[Seg\]

- A \* means zero or more of that natural class. Examples: \[Seg\]\* or \[C\]\[V\]\[C\]\*

- Parentheses around a natural class means *optional*. Example: \[C\](\[C\])\[V\]

- When you create these entries, create a separate entry for each category that you want the root guesser to guess.

- You may also add inflection classes, inflection features, or stem allomorph labels if those are part of the constraints for roots of this category. Create a separate entry for each possibility that should be guessed.

## Related topics
[Lexicon Edit fields overview](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Lexicon_Edit_fields_overview.md)

[Lexicon Edit overview](lexicon_edit_overview.md)

[Parsing words overview](../../../User_Interface/Menus/Parser/Parsing_words_overview.md)
