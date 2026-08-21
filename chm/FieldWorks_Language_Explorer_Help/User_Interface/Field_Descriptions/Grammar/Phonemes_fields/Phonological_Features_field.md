---
title: "Phonological Features field (Phonemes)"
source_title: "Phonological Features field (Phonemes)"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Grammar"
  - "Phonemes fields"
  - "Phonological Features field"
source: "User_Interface/Field_Descriptions/Grammar/Phonemes_fields/Phonological_Features_field.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Grammar/Phonemes_fields/Phonological_Features_field.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Features"
  - "Phonological:Phonological Features field"
  - "Phonological Features:Phonological Features field (Phonemes)"
related:
  - "Grammar Sketch -> ../../../../Using_Tools/Grammar_tools/Grammar_Sketch/Grammar_Sketch_overview.md"
  - "Phonemes fields overview -> Phonemes_fields_overview.md"
  - "Phonological Features overview -> ../../../../Using_Tools/Grammar_tools/Phonological_Features/Phonological_Features_overview.md"
  - "Phonological Rules overview -> ../../../../Using_Tools/Grammar_tools/Phonological_Rules/Phonological_Rules_overview.md"
fw_help_version: "9.3"
page_heading: "Phonological Features field"
type: "topic"
content_hash: "sha256:00b42c28e643264b"
---

# Phonological Features field (Phonemes)

*User Interface › Field Descriptions › Grammar › Phonemes fields*

**Full name:** **Phonological Features**

**Location:** **Phoneme** pane of **Phonemes** ([Grammar](../../../../Using_Tools/Grammar_tools/grammar_overview.md))

**Description:**

This field stores one or more phonological features for the current phoneme.

The phonemes are essentially a short-hand (abbreviated representation) for the full set of features associated with that phoneme. It is much easier to say the phoneme, such as "e", than all its features. When a rule, is passed to a [parser](../../../Menus/Parser/Parsing_words_(HermitCrab).md), the phoneme is converted to its features.

When the parser is passed a wordform, it tries to "undo" the phonological rules to come up with the underlying forms of the morphemes involved in the posited parse. It then takes the segments/phonemes of the underlying form and converts them to their phonological features. Next it applies the phonological rules (from underlying form to surface form). These rules actually work on the phonological features, not on the phonemes. If the result matches the original input, then the parse is considered to be successful.

**Tasks:**

- [Bulk Edit Phoneme Features](../../../../Using_Tools/Grammar_tools/Bulk_Edit_Phoneme_Features/Bulk_Edit_Phoneme_Features.md)

- [Insert a phoneme](../../../../Using_Tools/Grammar_tools/Phonemes/Insert_a_phoneme.md) (phonological features can be automatically inserted)

- [Choose phonological features](../../../../Using_Tools/Grammar_tools/Phonemes/Choose_phonological_features.md)

- [Remove a phonological feature](../../../../Using_Tools/Grammar_tools/Phonemes/Remove_a_phonological_feature.md)

- **See also:** [Phonemes overview](../../../../Using_Tools/Grammar_tools/Phonemes/Phonemes_overview.md)

**Field type:** [Single-line text field](../../Field_Types/Single_line_text_field.md) – you *cannot* embed characters in other writing systems or embed styles.

**Writing systems:** English. You cannot apply styles or change the font or font size for content in this field.

**Grammar Sketch:** Under **Phonemes** and **Phonological Feature System**.

## Related topics
[Grammar Sketch](../../../../Using_Tools/Grammar_tools/Grammar_Sketch/Grammar_Sketch_overview.md)

[Phonemes fields overview](Phonemes_fields_overview.md)

[Phonological Features overview](../../../../Using_Tools/Grammar_tools/Phonological_Features/Phonological_Features_overview.md)

[Phonological Rules overview](../../../../Using_Tools/Grammar_tools/Phonological_Rules/Phonological_Rules_overview.md)
