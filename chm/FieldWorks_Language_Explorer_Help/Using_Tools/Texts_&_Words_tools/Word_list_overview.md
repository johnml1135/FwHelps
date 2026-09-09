---
title: "Word list overview"
source_title: "Word list overview"
breadcrumb:
  - "Using Tools"
  - "Texts & Words tools"
  - "Word list overview"
source: "Using_Tools/Texts_&_Words_tools/Word_list_overview.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Texts_%26_Words_tools/Word_list_overview.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Baseline text writing systems:Word list overview"
  - "Texts & Words:Word list overview"
  - "Words"
  - "Words:Words overview"
  - "Words:Word list overview"
  - "Word list columns:Word list overview"
  - "Word list overview"
  - "Vernacular:Word list overview"
  - "word counts on status bar"
  - "Wordforms pane"
  - "Word list overview:Word list overview"
related:
  - "Change spelling -> Word_Analyses/Change_Spelling/change_spelling_overview.md"
  - "Export wordforms from word list -> ../../User_Interface/Menus/File/Export/Export_wordforms.md"
  - "Texts & Words overview -> Texts_and_Words_overview.md"
  - "Word Gloss field -> ../../User_Interface/Field_Descriptions/Texts_&_Words/Word_Gloss_field.md"
  - "Word list columns -> Word_list_columns.md"
fw_help_version: "9.3"
type: "index"
content_hash: "sha256:9ba033006fbb0f03"
---

# Word list overview

*Using Tools › Texts & Words tools*

The *word list* is the list of all the wordforms (words) in your corpus, any [imported words](../../User_Interface/Menus/Insert/Import_a_word_set.md), and words added during [vernacular spell checking](../../Basic_Tasks/Spell_Checking/vernacular_spell_checking.md). The word list appears in [Word List Concordance](Word_List_Concordance/Word_List_Concordance_overview.md), [Word Analyses](Word_Analyses/Word_Analyses_overview.md) and [Bulk Edit Wordforms](Bulk_Edit_Wordforms/Bulk_Edit_Wordforms_overview.md) in **Texts & Words**. It includes word glosses, word category information and statistical information (Number in Corpus, User Analyses and so on). The [Statistics](Statistics_overview.md) tool give additional statistical information.

This word list is *separate* from the entries in the [Lexicon](../Lexicon_tools/Lexicon_overview.md), even though the contents of the word list *may* be minimally different from the list of lexical entries.

- The word list contains full words such as "books" whereas the lexicon predominantly contains uninflected forms such as "book" and affixes such as "-s". For languages with little inflection (isolating languages), the difference between the two lists is minimal. For other languages (agglutinating), the two lists are very different.

- You *may* insert lexical entries (lexemes) based on these words, such as while you [gloss](Interlinear_Texts/specify_the_word_gloss.md) a monomorphemic language or while you [analyze](Interlinear_Texts/Analyze_Text_overview.md) a text (insert [morpheme breaks](Interlinear_Texts/Insert_or_remove_morpheme_breaks.md) and then [select the lexical sense](Interlinear_Texts/Select_the_lexical_sense_for_a_morpheme.md) for each). Otherwise, this word list and the lexical entries are separate*.*

> [!IMPORTANT]
>
> - When you [configure interlinear lines](../../User_Interface/Menus/Tools/Configure_interlinear_lines_dialog_box.md), notice that **Writing System** box is set to **Baseline** for the **Word**, **Morphemes**, and **Lex Entries** lines. In the context of writing systems, "Baseline" means any and all writing systems that were used in **Baseline** tabs.
>
> - - The **Baseline** tab allows you to [embed](../../User_Interface/Menus/Format/select_a_writing_system.md) words in any vernacular writing system that appears in the [Writing Systems tab](../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md). (You may embed words in an *analysis* writing system, but this *not* recommended, particularly if you want the word list to be a record of all the vernacular words in your corpus.)
>
>   - You can use the **Configure Interlinear Lines** dialog box to display additional **Word**, **Morphemes** or **Lex Entries** lines, and then select different *vernacular* writing systems for them, if you have more than one. (You cannot change the writing systems of *default set* of **Word**, **Morphemes** or **Lex Entries** lines which are set to **Baseline**. You cannot hide the default **Word** line.)
>
>   - The writing system of the *first word* in a text determines the directionality (left-to-right *or* right-to-left) for that entire text.
>
>   - The ![](../../assets/images/Important_Icon.gif) **Important** paragraphs in the [Guess word breaks](Interlinear_Texts/Guess_word_breaks.md) topic contain additional information about the word list.
>
> - For views with the word list (**Wordforms** pane), words with **Number in Corpus** of **0** (zero) are *only* listed, and counted on the [Status bar](../../User_Interface/Toolbars/status_bar.md), if texts that contains them are [included](../../User_Interface/Toolbars/Insert_toolbar.md). Then, you can see words that are **0**, without seeing words in *excluded* texts.
>
> - If you see duplicate wordforms that you cannot remove by [changing the spelling](Word_Analyses/Change_Spelling/change_spelling_overview.md) or [assigning analyses](Word_Analyses/Assign_analysis_usage.md), then run the **Merge Duplicate Wordforms** [utility](../../User_Interface/Menus/Tools/Language_Project_Utilities_overview.md).

## Related topics
[Change spelling](Word_Analyses/Change_Spelling/change_spelling_overview.md)

[Export wordforms from word list](../../User_Interface/Menus/File/Export/Export_wordforms.md)

[Texts & Words overview](Texts_and_Words_overview.md)

[Word Gloss field](../../User_Interface/Field_Descriptions/Texts_%26_Words/Word_Gloss_field.md) (in **Word Analyses**)

[Word list columns](Word_list_columns.md)
