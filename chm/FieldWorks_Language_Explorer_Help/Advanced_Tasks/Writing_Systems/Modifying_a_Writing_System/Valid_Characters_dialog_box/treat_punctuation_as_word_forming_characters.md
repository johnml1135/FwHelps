---
title: "Treat punctuation as word-forming characters"
source_title: "Treat punctuation as word-forming characters"
breadcrumb:
  - "Advanced Tasks"
  - "Writing Systems"
  - "Modifying a Writing System"
  - "Valid Characters dialog box"
  - "Treat punctuation as word-forming characters"
source: "Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Valid_Characters_dialog_box/treat_punctuation_as_word_forming_characters.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Valid_Characters_dialog_box/treat_punctuation_as_word_forming_characters.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Treat punctuation as word-forming characters"
  - "Word-forming characters"
  - "Word-forming characters:Treat punctuation as word-forming characters"
related:
  - "Valid Characters dialog box -> Valid_Char_overview.md"
  - "Word-forming apostrophes and glottal stops -> ../../../../User_Interface/Menus/Insert/wordforming_apostophes.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:264f0a305a42233c"
---

# Treat punctuation as word-forming characters

*Advanced Tasks › Writing Systems › Modifying a Writing System › Valid Characters dialog box*

After you have added valid characters in the **Valid Characters** dialog box, you might need to treat some punctuation characters as word-forming.

Failure to treat some punctuation characters as word-forming might result in the following:

- In normal editing, when you perform an action that is dependent on character type (such as double-clicking to select a word), it might produce unexpected results.

  Example: In Sena, if you do not treat the hyphen as word-forming, when you double-click the word `okha-okha`, only the half in which you click will be selected.

- When you interlinearize text, some wordforms will incorrectly be interpreted as multiple words instead of being correctly interpreted as a single word.

  Example: In Sena, if you do not treat the apostrophe as word-forming, the wordform `kun'khonda`, will incorrectly appear as `kun` and `khonda` separated by an apostrophe.

In the **Valid Characters** dialog box, do the following:

- Right-click a character in the **Punctuation, Symbols & Spaces** area, and then click **Treat as Word-Forming**.

> [!NOTE]
>
> - If treating a punctuation character as word-forming produces a worse result, right-click the character in the **Word Forming** area, and then click **Treat as Not Word Forming**.
>
> - A benefit of treating punctuation as word-forming is that other FieldWorks programs can use the information. A disadvantage of treating punctuation as word-forming is that programs external to FieldWorks (such as Microsoft Word) will not be able to use the information. So, rather than treating punctuation as word-forming, we recommend that you use Unicode word-forming characters.
>
> - If a character is word-forming in Unicode, it will appear in the correct section of characters in the **Valid Characters** dialog box.

## Related topics
[Valid Characters dialog box](Valid_Char_overview.md)

[Word-forming apostrophes and glottal stops](../../../../User_Interface/Menus/Insert/wordforming_apostophes.md)
