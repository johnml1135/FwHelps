---
title: "Find and Replace Text"
source_title: "Find and Replace Text"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Edit"
  - "Find and Replace Text"
source: "User_Interface/Menus/Edit/Find_and_Replace_Text.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Edit/Find_and_Replace_Text.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Replace"
  - "Texts & Words:Find and Replace Text"
  - "Find and Replace:Find and Replace Text (Texts & Words)"
related:
  - "Assign Analysis -> ../../../Using_Tools/Texts_&_Words_tools/Word_Analyses/Assign_analysis_usage.md"
  - "Edit menu overview -> Edit_overview.md"
  - "Find and Replace overview -> ../../../Basic_Tasks/Find_and_Replace/Find_and_Replace_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:9b0ef5f8586dadf0"
---

# Find and Replace Text

*User Interface › Menus › Edit*

In [Interlinear Text](../../../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/texts_edit_overview.md), [Concordance](../../../Using_Tools/Texts_&_Words_tools/Concordance/Concordance_overview.md) or [Word List Concordance](../../../Using_Tools/Texts_%26_Words_tools/Word_List_Concordance/Word_List_Concordance_overview.md), you use the **Find and Replace** dialog box to find *or* find and replace text in the *currently displayed* **Baseline** tab.

[Change occurrence of a spelling](../../../Using_Tools/Texts_%26_Words_tools/Word_Analyses/Change_Spelling/change_occurrences_of_a_spelling.md) is the *recommended* way to change the spelling of a word in the [text corpus](../../../Using_Tools/Texts_%26_Words_tools/Word_list_overview.md). It uses the [Change Spelling](../../../Using_Tools/Texts_%26_Words_tools/Word_Analyses/Change_Spelling/change_spelling_overview.md) dialog box, which allows control which can prevent duplicate words that you later may need to manually delete or other undesirable results, especially in [glossed](../../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/specify_the_word_gloss.md), [analyzed](../../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/Analyze_Text_overview.md) or [charted](../../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/Text_Chart_tab/Text_chart_overview.md) texts. If you have analyzed this text or other texts in which the word appears, you should *not* use the **Find and Replace** dialog box.

1.  To open the **Find and Replace** dialog box, do one of the following:

    - On the toolbar, click ![](../../../assets/images/Find_Replace_Text.GIF).

    - Press the [shortcut keys](../../Shortcuts/shortcut_keys_Texts_Words_tools.md) `Ctrl+Shift+F` (**Find** tab), or `Ctrl+H` (**Replace** tab).

    - On the **Edit** menu, click **Find**, or **Replace**.

2.  In the **Find** tab, do the following:

    - In the **Find what** box, enter the *search text* (that is, the character string, word, or phrase that you want to search for).

    - If necessary, click **More** to display the [Search Options](../../../Basic_Tasks/Find_and_Replace/Search_Options.md) pane, and then specify any search options for the **Find what** text.

    - Click **Find Next**.

3.  In the **Replace** tab, do the following:

    - In the **Find what** box, enter the *search text* (that is, the character string, word, or phrase that you want to search for).

    - If necessary, click **More** to display the [Search Options](../../../Basic_Tasks/Find_and_Replace/Search_Options.md) pane and then specify any search options for the **Find what** text.

    - In the **Replace with** box, enter the *replacement text*, and then do *any* of the following:

      If necessary, click **More** to display the **Search Options** pane, and then specify any replacement options for the **Replace with** text.

      Click **Replace** *once* to find the next occurrence, and then either click **Replace** again to replace that occurrence and then find the next occurrence, *or* click **Find Next** to *not* replace that occurrence and find the next occurrence. Repeat until all occurrences are found.

      Click **Replace All** to replace all occurrences at the same time.

4.  Click **Close**.

> [!IMPORTANT]
>
> - When you leave the **Baseline** tab or refresh the window (**F5**), any new words and spellings are added to the [word list](../../../Using_Tools/Texts_%26_Words_tools/Word_list_overview.md). Make sure the new spelling is correct or you may need to manually [delete unwanted words](../../../Using_Tools/Texts_%26_Words_tools/Word_Analyses/Delete_a_wordform.md) from the word list.
>
> <!-- -->
>
> - For special search or replacement criteria, refer to [Find or Replace Formatting](../../../Basic_Tasks/Find_and_Replace/Find_and_Replace_formatting.md) or [Find or Replace using regular expressions](../../../Basic_Tasks/Find_and_Replace/Find_and_Replace_using_regular_expressions.md).
>
> - You may want to [specify a spelling status](../../../Using_Tools/Texts_%26_Words_tools/Word_Analyses/Specify_spelling_status.md) for the word, particularly if you are using vernacular [spell checking](../../../Basic_Tasks/Spell_Checking/vernacular_spell_checking.md).

## Related topics
[Assign Analysis](../../../Using_Tools/Texts_%26_Words_tools/Word_Analyses/Assign_analysis_usage.md)

[Edit menu overview](Edit_overview.md)

[Find and Replace overview](../../../Basic_Tasks/Find_and_Replace/Find_and_Replace_overview.md)
