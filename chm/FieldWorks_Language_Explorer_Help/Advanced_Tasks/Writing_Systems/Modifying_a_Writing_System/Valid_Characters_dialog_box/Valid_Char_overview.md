---
title: "Valid Characters dialog box overview"
source_title: "Valid Characters dialog box overview"
breadcrumb:
  - "Advanced Tasks"
  - "Writing Systems"
  - "Modifying a Writing System"
  - "Valid Characters dialog box"
  - "Valid Characters dialog box"
source: "Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Valid_Characters_dialog_box/Valid_Char_overview.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Valid_Characters_dialog_box/Valid_Char_overview.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Writing System:Valid Characters dialog box overview"
  - "Writing System:Unicode"
  - "Valid Characters"
  - "Valid Characters:Valid Characters dialog box"
  - "Characters"
  - "valid for writing system"
  - "valid for writing system:Valid Characters overview"
  - "Word-forming characters"
  - "Word-forming characters:Valid Characters overview"
fw_help_version: "9.3"
type: "index"
content_hash: "sha256:31c325e3e94964d9"
---

# Valid Characters dialog box overview

*Advanced Tasks › Writing Systems › Modifying a Writing System › Valid Characters dialog box*

- [Open](Open_the_Valid_Characters_dialog_box.md) the **Valid Characters** dialog box. Be aware that you [choose valid numbers](../Writing_System_Properties_Numbers_tab.md) in the **Numbers** tab.

At the top *left* corner, you see the name of the current writing system. It appears above the three tabs.

On the *right* side, the **Valid Characters** pane displays the list of characters that you determine to be valid for the current writing system.

Language Explorer primarily uses the default Unicode properties to determine if a character is word-forming or not. If a character is not defined in Unicode, or if you need to override the Unicode properties, then you need to add the character to the list in the **Word Forming** pane.

- Characters that consist of a base character and a combining mark (for example, a diacritic) appear as a single character. You cannot add combining marks independently as valid characters.

- If you are using a character as word-forming that Unicode defines as punctuation, you could use this dialog to [treat punctuation as word-forming characters](treat_punctuation_as_word_forming_characters.md). However, the *preferred solution* is to use a different character that is *already* defined as word-forming in the Unicode standard.

- Adding a punctuation character here will prevent interlinear texts from failing on that punctuation character.

Information about whether a character is word-forming or not, whether specified by the Unicode character properties or by its categorization in this dialog box, is used by FLEx exclusively in [Interlinear Texts](../../../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/texts_edit_overview.md). On the **Gloss** or **Analyze** tab, word breaks in the [baseline text](../../../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/baseline_text_writing_systems.md) are determined based on this information, with punctuation, symbols, and spaces causing a word break and word-forming characters avoiding one.

- Use the **Unicode Character Properties Editor** program to [add or modify a custom character](../Writing_System_Properties_Characters_tab.md).

### Things you can do

- *Add* characters in any of these ways:

- From a similar writing system, click the [Based On](Valid_Chars_Based_On_tab.md) tab.

- Manually, click the [Manual Entry](Valid_Chars_Manual_Entry_tab.md) tab.

- From a data source, click the [From Data](Valid_Chars_From_Data_tab.md) tab.

- *Remove* characters in any of these ways:

<!-- -->

  - Click a character in the **Valid Characters** pane, and then click **Remove**.

  - Right-click the character, and then click **Remove** in the menu that appears.

  - To remove all the characters, click **Remove All**.

<!-- -->

- *Move* a character between **Word Forming** and **Punctuation, Symbols & Spaces** in either of these ways:

- Right-click the character you want to move, and then click **Treat as not Word Forming** or **Treat as Word-Forming**.

- Click the character you want to move, and then click the up arrow or down arrow.

> [!TIP]
>
> - *Character information* appears when you let the pointer stay over a character. A Screen Tip displays the Unicode value and the name of the character.
>
> - If the [default font](../Writing_System_Properties_Fonts_tab.md) does not include one or more characters, they appear as (![](../../../../assets/images/Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Valid_Characters_dialog_box/RedExclMark.PNG)).
>
> - This list of valid characters has *replaced* the `WordFormingCharOverrides.XML` file.
>
> - Language definition files have .xml as their file name extension, such as seh.xml.
>
> **Related Topics**
>
> [Non-base characters as graphemes](../../../../Using_Tools/Grammar_tools/Phonemes/Non_Base_Characters_as_Graphemes.md)
>
> [Treat punctuation as word-forming characters](treat_punctuation_as_word_forming_characters.md)
>
> [Word-forming apostrophes and glottal stops](../../../../User_Interface/Menus/Insert/wordforming_apostophes.md)
>
> [Writing System Properties, Fonts tab](../Writing_System_Properties_Fonts_tab.md)
