---
title: "Insert new text"
source_title: "Insert new text"
breadcrumb:
  - "Using Tools"
  - "Texts & Words tools"
  - "Interlinear Texts"
  - "Insert new text"
source: "Using_Tools/Texts_&_Words_tools/Interlinear_Texts/Insert_new_Text.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/Insert_new_Text.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Insert:Text"
  - "new"
  - "Texts & Words:Insert new text"
  - "Enter:Vernacular text (Baseline tab)"
  - "Add:Text"
  - "New:Text"
  - "insert"
  - "Vernacular:Insert new text Texts & Words)"
  - "Baseline tab"
related:
  - "Import overview -> ../../../Beginning_Tasks/Importing_Data/Import_overview.md"
  - "Texts & Words overview -> ../Texts_and_Words_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:558eba84519be056"
---

# Insert new text

*Using Tools › Texts & Words tools › Interlinear Texts*

This topic gives steps to insert a new text while in **Texts & Words** area.

1.  If you will [paste](../../../User_Interface/Menus/Edit/Cut_copy_and_paste.md) content into a text, you *must* first [prepare it](Text_preparation_before_analyzing.md).

2.  On the **Navigation** **Pane**, click **Texts & Words**, and then select **Interlinear Texts**.

3.  To insert a new text, do one of the following:

    - On the [Insert](../../../User_Interface/Toolbars/Insert_toolbar.md) toolbar, click ![](../../../assets/images/Using_Tools/Texts_&_Words_tools/Interlinear_Texts/AddNew_Text.GIF).

    - On the **Insert** menu, click **New Text**.

    - Press the [shortcut keys](../../../User_Interface/Shortcuts/shortcut_keys_Texts_Words_tools.md) `Ctrl+T`.

    The **Select Writing System** dialog box appears if you have more than one vernacular writing systems*.* **See:** [Baseline text writing systems](baseline_text_writing_systems.md).

4.  If the dialog box appears, select a writing system, and click **OK**.

A new text entry appears in the **Texts** pane, and the **Text** pane appears with an empty **Title** box and tabs.

5.  In the **Text** pane **Title** box, enter a title for the text.

6.  Click the **Baseline** tab, and then type or paste text.

- Before you leave the **Baseline** tab *for any reason*, check the writing system displayed in the [Format](../../../User_Interface/Toolbars/Format_toolbar.md) toolbar to make sure the writing system of the words is the desired writing system, and is the *same* as the writing system you selected if the **Select Writing System** dialog box appeared. See ![](../../../assets/images/Important_Icon.gif) **Important** below.

7.  If you will let Language Explorer (FLEx) [guess word breaks](Guess_word_breaks.md) (for languages without spaces between the words), *let FLEx guess word breaks now*. See ![](../../../assets/images/Important_Icon.gif) **Important** below.

8.  Click the **Info** tab, and then enter information about the text in the **Comment** box.

> [!IMPORTANT]
>
> - If, for example, you set the text to use an *orthographic* writing system, but paste words that use a *phonetic* writing system (or vice versa), you will cause words to appear in the wrong [line](../../../User_Interface/Field_Descriptions/Field_Types/Single_line_text_field.md) of various fields such as the [Lexeme Form](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Lexeme_Form_field.md) field. It may not be immediately apparent, some rework might be necessary or you may have some compromised data.
>
> - As you leave the **Baseline** tab and move to any other area or tool, all new words in the current text are *immediately added* to the [word list](../Word_list_overview.md).
>
>   - If the text does not contain legitimate word breaks, the word list is populated with illegitimate wordforms that you *must* delete. However, you *must* first delete those words from the **Baseline** tab *before* you can [delete a wordform](../Word_Analyses/Delete_a_wordform.md) or [Bulk Delete](../Bulk_Edit_Wordforms/Bulk_delete_form_wordform.md) them.
>
>   - If the resulting illegitimate words are in the word list, Language Explorer will think the text has adequate word breaks and will not insert more, rendering the **Guess Word Breaks** utility useless in the current text.
>
>   - [Word-forming apostrophes and glottal stops](../../../User_Interface/Menus/Insert/wordforming_apostophes.md) has information to help you use the correct apostrophe for words that require a word-forming character (such as in the *Sena* words `kang'ombe` or **ng'anga**) and glottal stops.
>
> <!-- -->
>
> - You can [delete unwanted words](Delete_unwanted_words.md) from the text, yet leave them in the word list.

> [!NOTE]
>
> - The [Text](../../../User_Interface/Field_Descriptions/Notebook/Text_field_(Notebook).md) field in **Notebook** allows you to [enter a vernacular text](../../Notebook_tools/Record_Edit_overview/Enter_a_vernacular_text.md) to the corpus that is *also part of a notebook record*.

## Related topics
[Import overview](../../../Beginning_Tasks/Importing_Data/Import_overview.md)

[Texts & Words overview](../Texts_and_Words_overview.md)
