---
title: "About the Novel Root Guesser"
source_title: "About the Novel Root Guesser"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Parser"
  - "About the Novel Root Guesser.htm"
source: "User_Interface/Menus/Parser/About_the_Novel_Root_Guesser.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Parser/About_the_Novel_Root_Guesser.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "About the Novel Root Guesser"
  - "Guess Root Hermit Crab Parser"
  - "Novel Root Guesser"
  - "Parser"
related:
  - "Parser menu overview -> Parser_menu_overview.md"
  - "Parsing words overview -> Parsing_words_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:392d44d073728caa"
---

# About the Novel Root Guesser

*User Interface › Menus › Parser*

If your project is set up to use the Hermit Crab parser, FLEx has the ability to use that setup to guess the analyses even for words for which the root is not yet in the Lexicon.

### How it works

The Hermit Crab parser includes the ability to "un-apply rules", therefore it can determine all the potential affixes in a wordform, and thus guess that the remaining part is the root. Guessing the root is done by the use of one or more special entries in the lexicon that are called *pattern-matching* *entries*. If, after determining the affixes in the wordform, the remainder of the wordform matches the pattern-matching entry, then FLEx will suggest that this could be the root.

### To use this functionality

1.  On the **Parser** menu, point to **Choose Parser**, and then select **Phonological Rule-based Parser (HermitCrab.NET)**.

2.  On the **Parser** menu, click **Edit Parser** **Parameters** and then make sure that **GuessRoots** is selected (![](../../../assets/images/User_Interface/Menus/Parser/CheckBoxBlackCkMk.png)).

3.  [Create](../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Create_a_Template_Entry.md) a pattern-matching entry.

4.  [Insert](../../../Using_Tools/Grammar_tools/Natural_Classes/Insert_a_Natural_Class.md) any additional **Natural Classes** that you will need for the pattern-matching entry.

5.  On the **Parser** menu in Texts & Words, click **Parse all words** or **Parse Words in Text**.

### What will happen

For a word that has a root that matches the pattern-matching entry, and meets all the requirements of your parsing setup, here is what will happen in **Interlinear Texts**:

- The **Lex. Entries** row will show your pattern-matching entry as the root, and the rest of the word will appear as it would for any word with valid parse.

- The **Word** row will show you one or more possible analyses you can choose. Choose one.

- The **Morphemes** line will show the portion of the surface word that matched the pattern-matching entry for the chosen analysis.

- In the **Lex. Entries** row, you can click **Create New Entry** and then add this root to the Lexicon. The **Lexeme Form** field will be filled in so you will not have to add it.

> [!NOTE]
>
> - Clearing the **GuessRoots** checkbox does not delete any pattern-matching entries.
>
> - The XAmple parser can only provide analyses for words where all the morphemes, including the root/stem, are in the Lexicon.

## Related topics
[Parser menu overview](Parser_menu_overview.md)

[Parsing words overview](Parsing_words_overview.md)
