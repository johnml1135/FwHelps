---
title: "Environment String Representation examples"
source_title: "Environment String Representation examples"
breadcrumb:
  - "Using Tools"
  - "Grammar tools"
  - "Environments"
  - "Environment String Representation examples"
source: "Using_Tools/Grammar_tools/Environments/Environment_String_Rep_examples.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Grammar_tools/Environments/Environment_String_Rep_examples.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Grapheme"
  - "Environment"
  - "Syntax"
  - "environment"
related:
  - "Insert an environment -> Insert_an_environment.md"
  - "Environments overview -> Environments_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:3ffefafc8aef7081"
---

# Environment String Representation examples

*Using Tools › Grammar tools › Environments*

This topic gives examples of proper syntax for **String Representations** and their meaning. Enter a similar meaning in the **Definition** field for each environment you add.

When the **Meaning** column says 'phoneme' it means *a representation of* a phoneme.

|  |  |
|----|----|
| Environment (Left-to-Right) | Meaning |
| `/ m _` | after an `m` *phoneme* |
| `/ [V] _` | after a vowel (assuming there is a **Natural Class** of vowels with the *abbreviation* of `V`) |
| `/ # i _` | after a word initial `i` *phoneme* |
| `/ # [V] _` | after a word initial vowel (assuming there is a **Natural Class** of vowels with the *abbreviation* of `V`) |
| `/ [V] y _` | after a vowel (assuming there is a **Natural Class** of vowels with the *abbreviation* of `V`) and a `y` *phoneme* |
| `/ _ i` | before an `i` *phoneme* |
| `/ _ [C]` | before a consonant (assuming there is a **Natural Class** of with the *abbreviation* of `C`) |
| `/ m _ w` | between an `m` and an `w` *phoneme* |
| `/ [C] _ [C]` | between two consonants (assuming there is a natural class of consonants with the *abbreviation* of `C`) |
| `/ ai _` | after an `a` and an **i** *phoneme* |
| `/ _ ai` | before an `a` and an `i` *phoneme* |
| `/ _ (a)i` | before an optional `a` and an `i` *phoneme*; that is, either before `ai` or before `i` |
| `/ _ ([C]) #` | before an optional word final consonant (assuming there is a natural class of consonants with the *abbreviation* of `C`); that is, either before a word final consonant or word finally |
| `/_[C^1][V^1]` | For [partial reduplication](../../../Morphology_and_Parsing_Tasks/reduplication_examples.md), `CV` is the reduplication pattern; the `1` integers act as index items that indicate matching items between this environment and the allomorph (or lexeme form); the `^` carets are separators; the syntax order indicates that the reduplication patters comes before the stem. |

> [!IMPORTANT]
>
> - If the font associated with your vernacular writing system does *not* include the syntactic elements you need for the environment, specifically `/`, `_`, `[`, `]`, `(`, `)`, and `#`, they may appear as square boxes.
>
>   In this case, you can select each character that does not appear correctly and [change the writing system](../../../User_Interface/Menus/Format/select_a_writing_system.md) to an analysis writing system that includes that syntactic element. The [parsers](../../../User_Interface/Menus/Parser/Parsing_words_overview.md) accept environments with multiple writing systems.
>
> - “`/`” (forward slash) must begin each environment.
>
> - “`_`” (underscore character) represents the location of the form (lexeme *or* allomorph) itself.
>
> - An environment may use a [natural class](../Natural_Classes/Natural_classes_overview.md) or it may use any grapheme of any [phoneme](../Phonemes/Phonemes_overview.md).
>
>   “`[ ]`” (square brackets) are *required* in environments that use a natural class, but are *not* used in environments that use a grapheme of a phoneme. Examples:
>
>   - `/_[V]` *must* have a *natural class* with the [abbreviation](../../../User_Interface/Field_Descriptions/Grammar/Natural_Classes_fields/Abbreviation_field_Natural_Classes.md) “`V.`”
>
>   - `/m_` uses the `m` [grapheme](../../../User_Interface/Field_Descriptions/Grammar/Phonemes_fields/representation_field_phonemes.md) of some *phoneme*.
>
> - “`( )`” (parenthesis) indicate *optional* phonemes or natural classes.
>
> - “`#`” (pound sign) is a predefined word boundary marker.

> [!TIP]
>
> - For more information, including *right-to-left* writing system examples, point to **Resources** on the [Help](../../../User_Interface/Menus/Help/Help_overview.md) menu, and then click **Introduction to Parsing**.

## Related topics
[Insert an environment](Insert_an_environment.md)

[Environments overview](Environments_overview.md)
