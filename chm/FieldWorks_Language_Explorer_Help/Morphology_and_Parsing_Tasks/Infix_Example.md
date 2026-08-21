---
title: "Infixation Example"
source_title: "Infixation Example"
breadcrumb:
  - "Morphology and Parsing Tasks"
  - "Infixation Example"
source: "Morphology_and_Parsing_Tasks/Infix_Example.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Morphology_and_Parsing_Tasks/Infix_Example.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Infixation"
  - "example"
related:
  - "Infix Example screen shots (pictures) -> Infix_Example_screen_shot.md"
  - "Lexicon Edit overview -> ../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md"
  - "Morpheme Break examples -> ../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/Morpheme_Break_examples.md"
  - "Morphology and Parsing Tasks overview -> Morphology_Parsing_Tasks_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:2b173d1a0b36171e"
---

# Infixation Example

*Morphology and Parsing Tasks*

The following example is intended to help you understand how to enter infix-related content in Language Explorer. Of course, real language data is often more complex. You can see Language Explorer [screen shots](Infix_Example_screen_shot.md) of this example, including interlinearized words.

## Example: Infixation

From Tagalog data, the word `sulat` is a verb which means *to write* or *writing* (infinitive form). `Sumulat` means *to write* (actor focus) and **sinulat** means *to write* (object focus). The two focus morphemes are **–um-** and **–in-**, both of which are infixes.

### Create the lexical entry and related grammar content

1.  [Insert the natural classes](../Using_Tools/Grammar_tools/Natural_Classes/Insert_a_Natural_Class.md), `C` for consonants and `V` for vowels, if they do not exist. (You may need to [insert phonemes](../Using_Tools/Grammar_tools/Phonemes/Insert_a_phoneme.md) for the natural classes to be complete.)

2.  [Insert environments](../Using_Tools/Grammar_tools/Environments/Insert_an_environment.md) for the infixes with respect to the stem.

    For this example, the environment would be `/#[C] _ [V]`.

    The `#` indicates the beginning of the sequence within the stem, `[C]` is the [natural class](../Using_Tools/Grammar_tools/Natural_Classes/Natural_classes_overview.md) of consonants and `[V]` is the natural class of vowels. In other words, the environment for the infixes would be between the initial `s` and the `ulat`.

3.  [Create the lexical entry](../Using_Tools/Lexicon_tools/Lexicon_Edit/Create_a_lexical_entry.md) for the infix `–um-`, entering the following in the **New Entry** dialog box:

    - In the **Lexeme Form** box, enter `–um-`.

    - In the **Morpheme Type** box, select **infix**.

    - In the **Affix Type** box, select **Inflectional**.

    - In the **Gloss** box, enter `actor.focus` (or use the [Inflectional Affix Gloss Builder](../Using_Tools/Lexicon_tools/Lexicon_Edit/Using_Morphosyntactic_Gloss_Assistant.md)).

    - In the **Category** box, select **Verb**.

    - Click **Create**.

    - In the **Entry** pane for the newly created entry, [choose the Infix Position](../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_infix_positions.md) **/#\[C\]\_\[V\]**, which is the environment you previously created.

4.  Repeat the previous steps to create the lexical entry for the infix `–in–,` making the appropriate change of `–in–` (for `–um–)` and the gloss `object focus` (for `actor focus`).

5.  Create the lexical entry for the stem `sulat` (a *stem*, a *verb*, with the *gloss* `to.write`).

    The infix information and the lexical entry are now available for [interlinearizing](../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/Analyze_Text_overview.md) and the [parsers](../User_Interface/Menus/Parser/Parsing_words_overview.md).

> [!TIP]
>
> - For more information, point to **Resources** on the [Help](../User_Interface/Menus/Help/Help_overview.md) menu, and then click **Introduction to Parsing**. Infixation is discussed under **Morphophonemics** and under **Infixation as a process**.

## Related topics
[Infix Example screen shots (pictures)](Infix_Example_screen_shot.md)

[Lexicon Edit overview](../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md)

[Morpheme Break examples](../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/Morpheme_Break_examples.md)

[Morphology and Parsing Tasks overview](Morphology_Parsing_Tasks_overview.md)
