---
title: "Reduplication Examples"
source_title: "Reduplication Examples"
breadcrumb:
  - "Morphology and Parsing Tasks"
  - "Reduplication Examples"
source: "Morphology_and_Parsing_Tasks/reduplication_examples.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Morphology_and_Parsing_Tasks/reduplication_examples.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Reduplication Examples"
related:
  - "Category Edit overview -> ../Using_Tools/Grammar_tools/Category_Edit/Category_Edit_overview.md"
  - "Lexicon Edit overview -> ../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md"
  - "Morphology and Parsing Tasks overview -> Morphology_Parsing_Tasks_overview.md"
  - "Reduplication Example screen shots (pictures) -> reduplication_examples_screen_shots.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:2b7b2f68affeb421"
---

# Reduplication Examples

*Morphology and Parsing Tasks*

These two examples are intended to help you learn how to enter reduplication- related content in FLEx. Of course, real language data is often more complex. [Screen shots](reduplication_examples_screen_shots.md) of these examples help you see the steps and the inflected forms interlinearized.

## Example 1: Full Reduplication (inflectional affix)

From Bahasa Indonesia data, the word `pel` is a noun meaning *mop*. The plural form, *mops*, is `pel-pel`. The entire stem is reduplicated, so this is *full reduplication*. It is not clear if the reduplication morpheme is a prefix or suffix. For this example, let’s assume that additional unstated information helped determine that the reduplication is a suffix.

To create the lexical entry, you first use the **New Entry** dialog box and then do additional steps in the **Entry** pane.

1.  [Open](../Using_Tools/Lexicon_tools/Lexicon_Edit/Create_a_lexical_entry.md) the **New Entry** dialog box.

You have two choices regarding what to enter as the **Lexeme Form**. The first choice, a), is for cases where reduplication only occurs with one function. The second choice, b), is for cases where there are multiple reduplicative morphemes (for example, one that pluralizes a noun plus another one that intensifies an adverb).\
For this [example](reduplication_examples_screen_shots.md), we need to do choice a).

a\) In the **Lexeme Form** box, enter --`[…]`.

That is, enter *two* hyphens, left square bracket, three periods and a right square bracket. The first hyphen indicates a suffix. The second hyphen in this example is an instance of “constant segmental material,” part of the orthography itself. The position of the second hyphen indicates that constant segmental material *precedes* the reduplicated material. As shown in the entry [example](reduplication_examples_screen_shots.md) screen shot, the **Lexeme Form** *field* will only display the second hyphen, while *both* are displayed when shown as the headword in the preview pane.

\
b) In the **Lexeme Form** box, enter the word `Reduplication` (or similar) with no hyphens.

Continue by doing these steps in the **New Entry** dialog box:

1.  - In the **Morpheme Type** box, select **suffix**, if it is not already selected.

    - In the **Gloss** box, enter `Plural`.

    - In the **Affix Type** box, select **Inflectional**.

    - In the **Attaches to Category** box, select **Noun**.

    - Click **Create**.

<!-- -->

2.  With the new entry displayed in the **Entry** pane, do these steps:

    - Select (![](../assets/images/CheckedBoxBLACK.png)) the **Is Abstract Form** check box to indicate that the lexeme is an [abstract form](../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Allomorph_Status_field.md).

The **Is Abstract Form** field you need is just below the **Lexeme Form** field. If you do not see it, select **Show Hidden Fields**.

2.  - Optionally, you can enter content in the **Citation Form** field. It will be appear as the [headword](../User_Interface/Menus/Tools/Configure_Dictionary/Headword.md) (if [configured](../User_Interface/Menus/Tools/Configure_Dictionary/Configure_Dictionary.md) that way). For this [example](reduplication_examples_screen_shots.md), we will enter -**RDP** for full reduplication.

    - Click **Insert Allomorph** and enter `-[…]` as an [allomorph](../Using_Tools/Lexicon_tools/Lexicon_Edit/Insert_an_alternate_form.md).

<!-- -->

3.  [Insert an affix slot](../Using_Tools/Grammar_tools/Category_Edit/Insert_an_Affix_Slot.md) for a *noun* as follows:

    - Enter a slot name that indicates that the slot affects singular and plural.

      For this example, the slot name is `Number.`

    - Select the **Optional** check box.

4.  [Insert an affix template table](../Using_Tools/Grammar_tools/Category_Edit/Insert_an_affix_template.md) for slots used with nouns, and then [edit the table](../Using_Tools/Grammar_tools/Category_Edit/Edit_an_Affix_Template_Table.md) as follows:

    - Enter an appropriate template table name and description.

      For this example, the table name is `Noun`, and described with `Nouns use reduplication for number`.

    - Use **Insert Slot After STEM** to insert the slot (`Number`) into the table.

      The parentheses indicate that the slot is optional.

    - Right-click the slot (`Number`) in the table column heading and select **Add inflectional affix(es) to Number**. Select (![](../assets/images/CheckedBox.PNG)) **–RDP Plural** in the dialog box, and then click **OK**.

5.  Create the lexical entry for the lexeme form `pel`, with the morpheme type `stem`, the gloss `mop`, the grammatical category information `noun`.

6.  The reduplication information and lexical entries are now available for [interlinearizing](../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/Analyze_Text_overview.md) and the [parsers](../User_Interface/Menus/Parser/Parsing_words_overview.md).

## Example 2: Partial Reduplication

From Tagalog data, the word `bili` is a verb which means *to buy*; `bibili` is the future tense, *will buy*. Part of the stem is reduplicated, appearing as the prefix `bi`. Therefore, this is *partial* reduplication.

1.  Determine if the reduplication morpheme is derivational or inflectional.

    For this [example](reduplication_examples_screen_shots.md), the reduplication is *inflectional*, affecting tense. You will need this determination in subsequent steps.

2.  Determine the reduplication pattern.

    For this example, `bi` is reduplicated, so the pattern is **CV**. You will need to know this pattern for subsequent steps.

3.  [Insert a natural class](../Using_Tools/Grammar_tools/Natural_Classes/Insert_a_Natural_Class.md) of phonemes in the reduplication pattern.

    For this example, we need *one* for the consonants ([abbreviation](../User_Interface/Field_Descriptions/Grammar/Natural_Classes_fields/Abbreviation_field_Natural_Classes.md) of `C`) with at least the phoneme `b`, and *another* for vowels (abbreviation `V`) with at least the phoneme `i`.

4.  [Insert an Environment](../Using_Tools/Grammar_tools/Environments/Insert_an_environment.md) named `CV reduplication` with the syntax that matches the reduplication pattern, and with special markings.

    For this example, the proper syntax is `/_[C^1][V^1]`.

    `CV` is the reduplication pattern; the `^1` are indices that indicate matching items between this environment and the allomorph or lexeme form; the syntax *order* indicates that the reduplication pattern comes *before* the stem.

    **Note:** For a reduplication pattern of `CVC`, then `[C^1][V^1][C^2]` may be the correct pattern.

5.  [Create a lexical entry](../Using_Tools/Lexicon_tools/Lexicon_Edit/Create_a_lexical_entry.md) for the reduplication morpheme, entering the following in the **New Entry** dialog box:

    - In the **Lexeme Form** box, enter `[C^1][V^1]`, to match the reduplication pattern and the environment syntax.

    - In the **Morpheme Type** box, select **prefix**.

    - In the **Affix Type** box, select **inflectional**.

    - In the **Gloss** box, enter `Future` (or use the [Inflectional Affix Gloss Builder](../Using_Tools/Lexicon_tools/Lexicon_Edit/Using_Morphosyntactic_Gloss_Assistant.md)).

    - In the **Attaches to Category** box, select **Verb**.

    - Click **Create**.

6.  If desired, you can enter content in the **Citation Form** field, which is then used as the dictionary headword instead of the content from the **Lexeme Form** field. For this example, we will enter **CV** for partial reduplication (instead of the headword `[C^1][V^1]`).

7.  In the **Entry** pane for new entry, [choose the environment](../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_environments.md) `/_[C^1][V^1]` in the **Environments** field.

8.  [Insert an affix slot](../Using_Tools/Grammar_tools/Category_Edit/Insert_an_Affix_Slot.md) for a *verb*, as follows:

    - Enter a slot name that indicates that the slot affects tense.

      For this example, the slot name is `Tense`.

    - Select (![](../assets/images/CheckedBox.PNG)) the **Optional** check box.

9.  [Insert an affix template table](../Using_Tools/Grammar_tools/Category_Edit/Insert_an_affix_template.md) for slots used with verbs, and then [edit the template table](../Using_Tools/Grammar_tools/Category_Edit/Edit_an_Affix_Template_Table.md) as follows:

    - Enter an appropriate template table name and description.

      For this example, the table name is `Verb`, and described with `Verbs use reduplication for tense`. (You will likely use a better name and a more complete description.)

    - Use **Insert S****lot Before STEM** to choose the slot (`Tense`).

      The parentheses indicate that the slot is optional.

    - Use **Add inflectional morpheme to Tense** to choose the reduplication morpheme **CV-** **Future**.

10. Create the lexical entry for the lexeme form `bili`, with the morpheme type `stem`, the gloss `buy`, the grammatical category information `verb`.

    The reduplication information and lexical entries are now available for [interlinearizing](../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/Analyze_Text_overview.md) and the [parsers](../User_Interface/Menus/Parser/Parsing_words_overview.md).

> [!TIP]
>
> - For more information, point to **Resources** on the [Help](../User_Interface/Menus/Help/Help_overview.md) menu, and then click **Introduction to Parsing**. Reduplication is discussed under **Morphophonemics** and under **Reduplication as a process**.

## Related topics
[Category Edit overview](../Using_Tools/Grammar_tools/Category_Edit/Category_Edit_overview.md)

[Lexicon Edit overview](../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md)

[Morphology and Parsing Tasks overview](Morphology_Parsing_Tasks_overview.md)

<a href="reduplication_examples_screen_shots.md" style="font-weight: normal;">Reduplication Example screen shots (pictures)</a>
