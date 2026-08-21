---
title: "Word-forming apostrophes and glottal stops"
source_title: "Word-forming apostrophes and glottal stops"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Insert"
  - "Word-forming apostrophes"
source: "User_Interface/Menus/Insert/wordforming_apostophes.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Insert/wordforming_apostophes.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Keyboard (Keyman or MSKLC)"
  - "Keyboard (Keyman or MSKLC):Wordforming apostrophes"
  - "Apostrophes"
  - "word-forming"
  - "MSKLC keyboard"
  - "Word-forming characters"
  - "Word-forming characters:Word-forming apostrophes and glottal stops"
  - "Glottal stops"
related:
  - "Citation Form field -> ../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Citation_Form_field.md"
  - "Insert overview -> Insert_overview.md"
  - "Lexeme Form field -> ../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Lexeme_Form_field.md"
  - "Technical Support -> ../../../Overview/Technical_support.md"
  - "Text Edit overview -> ../../../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/texts_edit_overview.md"
  - "Treat punctuation as word-forming characters -> ../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Valid_Characters_dialog_box/treat_punctuation_as_word_forming_characters.md"
  - "Valid Characters dialog box -> ../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Valid_Characters_dialog_box/Valid_Char_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:f7902f1ac44f9022"
---

# Word-forming apostrophes and glottal stops

*User Interface › Menus › Insert*

## Apostrophes

Some words, such as the *Sena* word *kang'ombe*, use apostrophes as word-forming characters. However, not all apostrophes can be used as [word-forming characters](../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Valid_Characters_dialog_box/treat_punctuation_as_word_forming_characters.md). Language Explorer (FLEx) uses the Unicode properties for characters to decide which apostrophes are simply punctuation. This is crucial towards allowing FLEx to correctly find wordforms when it processes a text. Specifically, an incorrect apostrophe entered in a **Baseline** tab will cause that single word to appear as *two* words in the **Gloss** and **Analyze** tabs, such as *kang* and *'***ombe** from *kang'ombe*. As long as FLEx can correctly find the wordforms, then the [parsers](../Parser/Parsing_words_overview.md) will see correct wordforms, not partial wordforms.

Use **U+**`0027` `APOSTROPHE` or `02bc` `MODIFIER LETTER APOSTROPHE` for the word-forming apostrophe *rather than* `2019 Right Single Quote mark`.

`02bc` `MODIFIER LETTER APOSTROPHE` is defined as word-forming in the Unicode Standard so its use would be appropriate, but it has disadvantages:

- Not all fonts include this code point. For example, *Times New Roman* does not, but *Doulos SIL* and *Charis SIL* both include it. So, as long as you use either of those fonts or another font that you know includes it, `02bc` would work.

- You will need a MSKLC (*Microsoft Keyboard Layout Creator*) or a Keyman keyboard to enter any `02bc` characters.

If you already have a special keyboard, adding this (`02bc`) probably would not be too hard. Otherwise, use `0027` `APOSTROPHE`. This does not have the rounded appearance, but it is available in all fonts and does not require anything special to enter it.

> [!TIP]
>
> - In Microsoft Word, you can disable the *smart quote* capability so it will enter `0027` instead of converting it to `2019` as you type.
>
> - You can examine the apostrophes discussed above in the [Character Map](Using_Character_Map.md).
>
> - You should reserve `2018` `Left Single Quote mark` and `2019` `Right Single Quote mark` for use as real quotation marks.
>
> - If you really need to use `2019`, add it to the list of [valid characters](../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Valid_Characters_dialog_box/Valid_Char_overview.md).

### Glottal Stops

(Adapted from**:** <a href="https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&amp;id=EncodingFAQ" target="_blank" title="https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&amp;id=EncodingFAQ">https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&amp;id=EncodingFAQ</a>)

If you want something that looks like a curly quote you should use **U+02BC MODIFIER LETTER APOSTROPHE**. You could use **2019 RIGHT SINGLE QUOTATION MARK**, but there are at least two issues with that. It is considered punctuation with different properties than an orthographic character and if you use quote marks there is nothing to distinguish between the two characters. (Our Roman fonts (Doulos SIL, Charis SIL, Andika Basic and Gentium Basic) all have an alternate glyph for **02BC MODIFIER LETTER APOSTROPHE** which is a bit larger than normal to help distinguish the glyph from **2019 RIGHT SINGLE QUOTATION MARK**.)

Many orthographies have used something that looks like the straight quote. There were so many problems with using **0027 APOSTROPHE** for this character that we requested the addition of a character to Unicode for that. You should use **A78C LATIN SMALL LETTER SALTILLO** (one language even "cases" this and **A78B** is used for the uppercase). (Our Roman fonts (Doulos SIL, Charis SIL, Andika Basic and Gentium Basic) all have an alternate glyph for **A78C LATIN SMALL LETTER SALTILLO** and **A78B LATIN CAPITAL LETTER SALTILLO** which are a bit larger than normal to help distinguish the glyph from **0027 APOSTROPHE**.)

**02BE MODIFIER LETTER RIGHT HALF RING** is sometimes used for transliterating Arabic hamza (glottal stop). This looks different from both **A78C LATIN SMALL LETTER SALTILLO** and **02BC MODIFIER LETTER APOSTROPHE** and might be a good option for traditions which recognize the transliterated hamza.

Some Saskatchewan orthographies use an upper and lowercase glottal stop. Those are **0241 LATIN CAPITAL LETTER GLOTTAL STOP** and **0242 LATIN SMALL LETTER GLOTTAL STOP**.

Of course, the IPA representation is **0294 LATIN LETTER GLOTTAL STOP** and some languages also use this in their orthographies (where casing is not required).

## Related topics
[Citation Form field](../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Citation_Form_field.md)

[Insert overview](Insert_overview.md)

[Lexeme Form field](../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Lexeme_Form_field.md)

[Technical Support](../../../Overview/Technical_support.md)

[Text Edit overview](../../../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/texts_edit_overview.md)

[Treat punctuation as word-forming characters](../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Valid_Characters_dialog_box/treat_punctuation_as_word_forming_characters.md)

[Valid Characters dialog box](../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Valid_Characters_dialog_box/Valid_Char_overview.md)
