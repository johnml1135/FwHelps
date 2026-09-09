---
title: "Guess word breaks"
source_title: "Guess word breaks"
breadcrumb:
  - "Using Tools"
  - "Texts & Words tools"
  - "Interlinear Texts"
  - "Guess word breaks"
source: "Using_Tools/Texts_&_Words_tools/Interlinear_Texts/Guess_word_breaks.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/Guess_word_breaks.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Show:Show Invisible Spaces"
  - "Word breaks"
  - "Guess Word Breaks"
  - "Zero-width space"
  - "insert"
  - "ZWSP"
related:
  - "Interlinear Texts overview -> texts_edit_overview.md"
  - "Insert menu overview -> ../../../User_Interface/Menus/Insert/Insert_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:a2e0b5dd470d10a6"
---

# Guess word breaks

*Using Tools › Texts & Words tools › Interlinear Texts*

For languages that do *not* typically use spaces between words, you can use the **Guess Word Breaks** feature. The feature inserts a *Zero-width space* punctuation (ZWSP) character between words based on existing lexical entries (stems and roots) and existing words in the [word list](../Word_list_overview.md). See ![](../../../assets/images/Important_Icon.gif) **Important** below before you attempt this topic.

To let Language Explorer guess word breaks, do the following:

1.  In the [Navigation Pane](../../../User_Interface/Toolbars/Navigation/Navigation_Pane_overview.md), click **Texts & Words**, and then select **Interlinear Texts**.

2.  In the **Text** pane, click the **Baseline** tab.

3.  [Insert a new text](Insert_new_Text.md), but *do not* leave the **Baseline** tab to move into another Language Explorer area. Or, select an existing text.

4.  On the **Insert** [menu](../../../User_Interface/Menus/Insert/Insert_overview.md) menu, click **Guess Word Breaks**.

    ZWSP characters are added between words, and the **Invisible Spaces** feature is automatically selected (**View** [menu](../../../User_Interface/Menus/View/View_overview.md)).

5.  Review the proposed word breaks. If necessary, do any of the following to manually change where the ZWSP characters are located:

    - On the **Insert** menu, click the **Click Inserts Invisible Space** command. Then with your mouse pointer (![](../../../assets/images/Using_Tools/Texts_&_Words_tools/Interlinear_Texts/InsertZXSP.png)), click each location where you want to insert a ZWSP character.

    - Copy and paste a ZWSP character to manually insert a word break.

    - Delete an unwanted ZWSP character to manually remove a word break.

    - [Undo](../../../User_Interface/Menus/Edit/Undo_and_Redo.md) the most recent change, if necessary.

> [!IMPORTANT]
>
> - If you leave the **Baseline** tab and move to any other area (even to the **Info** tab), the current text is immediately added to the [word list](../Word_list_overview.md).
>
>   If the text does not contain legitimate word breaks, the word list is populated with *illegitimate words* that you must delete. However, you need to delete the *text* in the **Baseline** tab *before* you can delete those words.
>
>   If the resulting illegitimate words are in the word list, Language Explorer will think the text has adequate word breaks and will not insert more, rendering this feature useless in the current text.
>
> - Before you use this feature, you may want to [open a second window](../../../User_Interface/Menus/Window/Window_overview.md) in which to view **Lexicon Edit** or **Words Analyses**.

> [!NOTE]
>
> - You can use this feature in *any* **Baseline** tab, such as in **Word List Concordance**. It is recommended that you use it in **Interlinear Texts** because it offers the largest display of the **Baseline** tab view.
>
> - The *Zero-width space* punctuation character is Unicode U+200B.
>
> - - It is intended for invisible word separation. It is a non-printing character.
>
>   - It has no width, but when you select **Invisible Spaces** ([View](../../../User_Interface/Menus/View/View_overview.md) menu), a vertical gray bar appears at the location of each ZWSP character. Then, you can easily select, copy, paste, or delete them.
>
>   - For more, see: <a href="https://en.wikipedia.org/wiki/Zero-width_space" target="_blank" title="https://en.wikipedia.org/wiki/Zero-width_space">https://en.wikipedia.org/wiki/Zero-width_space</a> or <a href="https://www.fileformat.info/info/unicode/char/200b/index.htm" target="_blank" title="https://www.fileformat.info/info/unicode/char/200b/index.htm">https://www.fileformat.info/info/unicode/char/200b/index.htm</a>.
>
> - ZWSP characters allow you to [gloss or interlinearize](texts_edit_overview.md) individual words in the text.
>
> - You cannot insert a ZWSP character adjacent to a real space.

## Related topics
[Interlinear Texts overview](texts_edit_overview.md)

[Insert menu overview](../../../User_Interface/Menus/Insert/Insert_overview.md)
