---
title: "Non-Base Characters as Graphemes"
source_title: "Non-Base Characters as Graphemes"
breadcrumb:
  - "Using Tools"
  - "Grammar tools"
  - "Phonemes"
  - "Non-Base Characters as Graphemes"
source: "Using_Tools/Grammar_tools/Phonemes/Non_Base_Characters_as_Graphemes.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Grammar_tools/Phonemes/Non_Base_Characters_as_Graphemes.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Combining characters as graphemes"
  - "Grapheme"
  - "Non-Base Characters as Graphemes"
  - "ZEdit"
  - "program"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:c2ce004d9726749e"
---

# Non-Base Characters as Graphemes

*Using Tools › Grammar tools › Phonemes*

Some FLEx users need to create phonemes that use only a Unicode combining character as the grapheme. See **Example** below.

### Considerations

- Keyboards usually require a series of key strokes to make a composite character. So how would you type just the combining character?

- A combining character without a base character may *not* be visible. If it is visible, it may not look the same as it does when it appears in combination with a base character.

Here is one way to enter a combining character into a [Grapheme](../../../User_Interface/Field_Descriptions/Grammar/Phonemes_fields/representation_field_phonemes.md) field:

1.  Do steps 1-5 in [Insert a Phoneme](Insert_a_phoneme.md), and then do the steps below to enter the grapheme.

2.  On the **Insert** menu, click **Special Character**.

    The **Character Map** dialog box opens.

3.  In the **Go to Unicode** box, type the Unicode value for the combining character. For example, for a Combining Circumflex Accent, you would type 0302.

    The character becomes highlighted in the dialog box. The bottom of the dialog box shows the value and its name, such as 'U+0302 Combining Circumflex Accent.'

4.  Click **Select**, and then click **Copy**.

    The character is copied to your clipboard.

5.  Click the **Grapheme** field, and then use **Ctrl+V** to paste the character from the clipboard into the field.

    That character may *not* be visible, or you may notice a tiny speck in the field. Although there may not be a visible change on your screen, the character has been copied to your clipboard. If you want to verify that there is a character on the clipboard, use [ZEdit](../../../Basic_Tasks/ZEdit.md):

    - Open ZEdit. In the ZEdit **Options** menu, point to **ReOpen As** and then click **UTF-8**.

    - Click the empty pane, and then paste (`Ctrl+V`) the character there.

    - On the ZEdit **Tools** menu, click **Show Character Codes**.

      The **View Character Codes** box appears. It shows the hexadecimal value of the character you pasted, which should be the same as what you typed in the **Go to Unicode** box (above).

    - Close ZEdit.

The parser will treat the combining character as a single-character phoneme, just like `/p/`, **/e/**, and so on.

6.  Make sure the **Description** field content clearly indicates that the phoneme consists solely of a combining character, especially when the grapheme is not visible or does not appear as it does when combined with a base character. This is also important for the [Grammar Sketch](../Grammar_Sketch/Grammar_Sketch_overview.md).

### Example - why you may want to do this

Some languages use combining characters in the orthography to systematically indicate a particular phonological trait, independent of the base character they combine with. Using a tilde (U+0303) to indicate nasalization or grave, acute, and circumflex accents (U+0300, U+0301, U+0302) to indicate tonemes are common practices in certain parts of Africa, for example. In languages with orthographies like these, it is often advantageous to declare a “nasalization” phoneme or a set of tonal phonemes in FLEx, so as to avoid having an inflated number of phonemes in FLEx compared to reality.

Take, for example, a language that has 10 vowel phonemes (a fairly common occurrence in West Africa). If the tilde (a combining character superimposed on the vowel) is used to indicate nasalization, and two diacritics (grave and acute, also combining characters) are used to indicate tonal differences, the phoneme list in FLEx will need to have a minimum of 13 entries (10 vowels, a tilde, and two accent marks) to handle everything used in the orthography. If the combining characters are not defined as independent phonemes, the list of phonemes in FLEx will have to include each of the possible combinations of vowel (base character), tilde (or not), and accent (or not). This makes for a total of 10 x 2 x 3 = 60 phonemes that will have to be defined. This is one scenario where it is useful to define a Unicode combining character as a phoneme independently of the base character it accompanies.

### Related topics

[Phonemes overview](Phonemes_overview.md)
