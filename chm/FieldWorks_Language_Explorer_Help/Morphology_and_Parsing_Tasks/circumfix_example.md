---
title: "Circumfix Example"
source_title: "Circumfix Example"
breadcrumb:
  - "Morphology and Parsing Tasks"
  - "Circumfix Example"
source: "Morphology_and_Parsing_Tasks/circumfix_example.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Morphology_and_Parsing_Tasks/circumfix_example.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Circumfix Example"
related:
  - "Circumfix Example screen shots (pictures) -> Circumfix_example_screen_shot.md"
  - "Lexicon Edit overview -> ../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md"
  - "Morphology and Parsing Tasks overview -> Morphology_Parsing_Tasks_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:d074d4460bd8a445"
---

# Circumfix Example

*Morphology and Parsing Tasks*

This example is provided to help you understand how to enter circumfix-related content for use with the [XAmple parser](../User_Interface/Menus/Parser/Parsing_words.md). Of course, real language data is often more complex. You can see Language Explorer [screen shots](Circumfix_example_screen_shot.md) of this example, including the interlinearized word. Circumfixes are handled *differently* with the [Hermit Crab parser](../User_Interface/Menus/Parser/Parsing_words_(HermitCrab).md).

## Example: Prefix/Suffix Circumfix

From Bahasa Indonesia data, the word `bangun` is a verb meaning *to wake up*. The noun `kebangunan`, which means *awakening*, is derived with the addition of the `ke-` prefix and the `–an` suffix. These affixes act together to form a single morpheme (nominalizer morpheme), even though they are on opposite ends of the stem.

### Create the lexical entry

1.  [Create the lexical entry](../Using_Tools/Lexicon_tools/Lexicon_Edit/Create_a_lexical_entry.md) for the circumfix, entering the following in the **New Entry** dialog box:

    - In the **Lexeme Form** box, enter `ke-…-an`.

      That is, enter the prefix, the prefix [token](../Using_Tools/Lists_tools/Change_the_tokens_for_morpheme_types.md) (here a hyphen), three periods, the suffix token (here a hyphen), and the suffix.

      *Alternatively*, you can simply separate the prefix and suffix portions by a space, such as `ke- -an`.

    - In the **Morpheme Type** box, select **circumfix**.

    - In the **Gloss** box, enter `NMLZR` (for nominalizer morpheme).

    - In the **Affix Type** box, select **Derivational**.

    - In the **Attaches to Category** box, select **Verb**.

    - In the **Changes to Category** box, select **Noun**.

    - Click **Create**.

    The entry is added to the lexicon. Notice that the **Is Abstract Form** check box was automatically selected (![](../assets/images/CheckedBox.PNG)).

    Also, two affix allomorph entries are also automatically inserted, based on the position of the tokens used in the lexeme form. For this example, allomorphs for both the prefix `ke` and the suffix `an` were inserted.

2.  In the **Morph Type** fields for the automatically-inserted affix allomorphs, verify that the morpheme types are correct. [Change any morpheme type](../Using_Tools/Lexicon_tools/Lexicon_Edit/change_the_morph_type.md) that is not correct.

3.  If either of the automatically-inserted allomorphs *have* allomorphs, manually [insert their allomorph(s)](../Using_Tools/Lexicon_tools/Lexicon_Edit/Insert_an_alternate_form.md).

    **Note:** The parser does *not* recognize the morph type **circumfix**. So if an allomorph is added with the morph type set to **circumfix**, the parser will not know what to do with it. You need to separate halves of the circumfix as distinct allomorphs, setting their morpheme type to **prefix** (or **infix**) for the initial half and to **suffix** for the final half.

    For this example, no additional allomorphs are inserted.

4.  [Insert environments](../Using_Tools/Grammar_tools/Environments/Insert_an_environment.md) and then [choose the environments](../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_environments.md) that are appropriate for each affix allomorph, remembering that the environments are independent of each other.

    The lexical entry and the circumfix information are now available for [interlinearizing](../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/Analyze_Text_overview.md) and the [parsers](../User_Interface/Menus/Parser/Parsing_words_overview.md). Parsers require both the prefix and suffix members to appear *simultaneously* for them to be parsed as an instance of this entry.

    For this example, no environments are required.

> [!TIP]
>
> - For more information, point to **Resources** on the [Help](../User_Interface/Menus/Help/Help_overview.md) menu, and then click **Introduction to Parsing**. Circumfixes are discussed under **Lexical Entry Considerations**.

## Related topics
[Circumfix Example screen shots (pictures)](Circumfix_example_screen_shot.md)

[Lexicon Edit overview](../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md)

[Morphology and Parsing Tasks overview](Morphology_Parsing_Tasks_overview.md)
