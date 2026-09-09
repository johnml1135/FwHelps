---
title: "Text preparation before analyzing"
source_title: "Text preparation before analyzing"
breadcrumb:
  - "Using Tools"
  - "Texts & Words tools"
  - "Interlinear Texts"
  - "Text preparation before interlinearizing"
source: "Using_Tools/Texts_&_Words_tools/Interlinear_Texts/Text_preparation_before_analyzing.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/Text_preparation_before_analyzing.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Insert:NBSP (non-breaking space)"
  - "Insert:Section Sign"
  - "Texts & Words:Text"
  - "preparation before interlinearizing"
  - "Prepare text for interlinearizing"
  - "Unicode"
  - "Analyze Texts (parse):Text preparation before analyzing"
  - "Text Chart tab:Text preparation before analyzing"
  - "Number:Numbers"
  - "word-forming"
  - "NBSP"
  - "insert:Text preparation before analyzing"
  - "Non-Break space"
  - "insert"
  - "insert:Insert a NBSP"
  - "Section Sign"
related:
  - "Insert new text -> Insert_new_Text.md"
  - "Parsing \n words overview -> ../../../User_Interface/Menus/Parser/Parsing_words_overview.md"
  - "Texts & \n Words overview -> ../Texts_and_Words_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:082bc8eff8c41ebd"
---

# Text preparation before analyzing

*Using Tools › Texts & Words tools › Interlinear Texts*

*Before* you paste text into a **Baseline** tab, make sure it is structured and edited as much as possible. If you gloss or analyze it *and then* try to clean up either the content in various [tabs](texts_edit_overview.md) and the [word list](../Word_list_overview.md) the effort will take much longer.

*![](../../../assets/images/Warning_Icon.gif)* **Caution**

- Review the important information in [Baseline Text writing systems](baseline_text_writing_systems.md) *before* you do any text analysis. If you are not careful, you can cause complications, such as duplicate words in the word list that will take a long time to correct.

Additionally, the considerations listed below will help you make efficient use of the screen area in the **Analyze** tab.

**Prerequisite**: Texts from non-FieldWorks sources must be in **Unicode** or [converted to Unicode](Convert_text_to_Unicode.md) before you paste them into the Language Explorer. Otherwise, some characters will not appear correctly. Interlinearizing will break words at each invalid character and will populate your word list with incomplete words.

Examples of other considerations regarding your text include the following:

- Inserting more text records that are *smaller* is recommended over fewer larger texts. Large texts are discouraged as they can slow the program (varies for different computers and language projects) and may be unwieldy to navigate through as you analyze.

- Type or [insert](../../../User_Interface/Menus/Insert/Insert_a_NBSP.md) non-breaking spaces (U+00A0 or Alt+0160), such as before exclamation points in some languages.

- The interlinearizer breaks sentences at the white space after periods, question marks, and exclamation points. You can [insert](../../../User_Interface/Menus/Insert/Insert_a_Section_Sign.md) the Section Sign § (U+00A7 or Alt+0167) to force section breaks. You may want to do this if you want text without any punctuation.

  For example, if you have sentences in an alphabetized list, remove any periods that appear after the label, such as `A.`, or replace them with a parenthesis, such as A`)` or A`]`.

  Similarly, the interlinearizer will break "`She yelled, 'Yea!' and waved her arms.`" just after the quote mark following the exclamation point.

- Carriage returns are treated as paragraph breaks, but are displayed as sentence breaks in the **Analyze** tab.

  Delete any *redundant* carriage returns to combine sentences that have been split across paragraph boundaries in the source file (for example, some mail programs break messages into one-line paragraphs).

  An extra carriage return in the data will be displayed as "**An empty paragraph**" in the **Analyze** tab.

- Table structures and tabs (from the `Tab` key) are stripped from the text. If the words were in a table, or if tabs were used to separate words in the source file, those words will bunch together.

  If possible, use a word processor to convert the table to text. Then, using the word processor, you may want to put the text that had been in a table, or that had been separated by tabs, into a bulleted list. The bullets are displayed but ignored by the interlinearizer.

- Numbers:

  - Typically, spell out numbers if you want to analyze them. For example, write, "`He ate three apples`" instead of "`He ate 3 apples`."

  - Numbers can be word-forming characters. Examples: Digits may augment the technical orthography, and some write the tone as a digit at the end of a word.

- [Word-forming apostrophes and glottal stops](../../../User_Interface/Menus/Insert/wordforming_apostophes.md) has information to help you use the correct apostrophe for words that require a word-forming character (such as in the *Sena* words `kang'ombe` or **ng'anga**), and glottal stops.

- Direct formatting and style formatting are generally stripped from the text, so you may not want to spend a lot of time formatting the text you will analyze.

- Do your best to ensure the correct spelling of each word. This will prevent the need to remove incorrect wordforms from the word list.

- Replace unnecessary capitalization of letters or words with lowercase letters. For example, change words that were entered in all capital letters for emphasis. Proper names or initial letters of sentences are allowed.

## Related topics
[Insert new text](Insert_new_Text.md)

[Parsing words overview](../../../User_Interface/Menus/Parser/Parsing_words_overview.md)

[Texts & Words overview](../Texts_and_Words_overview.md)
