---
title: "Specify a word gloss"
source_title: "Specify a word gloss"
breadcrumb:
  - "Using Tools"
  - "Texts & Words tools"
  - "Interlinear Texts"
  - "Specify a word gloss"
source: "Using_Tools/Texts_&_Words_tools/Interlinear_Texts/specify_the_word_gloss.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/specify_the_word_gloss.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Gloss:Specify a word gloss"
  - "Gloss:Gloss tab"
  - "Specify (See Also: Select or Choose)"
  - "Specify (See Also: Select or Choose):Word gloss"
  - "Free Translation"
  - "Literal Translation"
  - "Word Gloss/Word Gloss line"
  - "interlinear"
  - "Gloss a text"
related:
  - "About Gloss and Analyze tabs -> About_Gloss_Analyze_tabs.md"
  - "Configure Interlinear Lines dialog box -> ../../../User_Interface/Menus/Tools/Configure_interlinear_lines_dialog_box.md"
  - "Configure Interlinear Lines right-click -> Configure_Interlinear_lines_right_click.md"
  - "Texts & Words overview -> ../Texts_and_Words_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:f4bf4fa6e18934ce"
---

# Specify a word gloss

*Using Tools › Texts & Words tools › Interlinear Texts*

As you "gloss" the words in a text (specify only glosses and maybe word categories) or you manually [analyze the words in a text](Analyze_Text_overview.md), you need to specify a gloss for the word in the **Word Gloss** line of the [word focus box](Word_Focus_Box_examples.md).

1.  [Display the text in an interlinear view](Display_text_in_an_interlinear_view.md).

- To only "gloss" a word or text, click the **Gloss** tab. Otherwise, click the **Analyze** tab. (You can enter [free](Enter_a_Free_Translation.md) and [literal](Enter_a_Literal_Translation.md) translations and [notes](Enter_a_Note.md) in any **Gloss** or **Analyze** tab.)

2.  Select or clear [Add Words to Lexicon](About_Add_Words_to_Lexicon.md) on the **Text** pane [Information bar](../../../User_Interface/Toolbars/information_bar_overview.md) (select *only* for a monomorphemic language).

3.  Click the word for which you will specify a word gloss.

    The word appears in a word focus box.

4.  In the **Word Gloss** line, do one of the following:

    - Click the white box, and then enter a new gloss or edit the existing gloss. If you [configured](../../../User_Interface/Menus/Tools/Configure_interlinear_lines_dialog_box.md) the interlinear lines to show multiple writing systems, enter the gloss in each, as appropriate.

    - Click the down arrow ![](../../../assets/images/Using_Tools/Texts_&_Words_tools/Interlinear_Texts/Down_Arrow_pic.PNG), *if present*, and then select an existing gloss, or select **New word gloss**.

      If you select **New word gloss**, the **Word Gloss** line(s) clears (white text box becomes empty) so you can enter a new gloss. If you have multiple writing systems shown, the text box line for each writing system becomes empty.

      For multiple writing systems, only the default (top) line has a down arrow ![](../../../assets/images/Using_Tools/Texts_&_Words_tools/Interlinear_Texts/Down_Arrow_pic.PNG). When you click it, previously entered word glosses for each active writing system are displayed for your selection.

5.  When you are finished, [move to another word](../../../User_Interface/Menus/Data/Data_overview.md).

    If **Add Words to Lexicon** is selected, the word, word gloss and category are added to the Lexicon.

> [!IMPORTANT]
>
> - The **Word Gloss** down arrow ![](../../../assets/images/Using_Tools/Texts_&_Words_tools/Interlinear_Texts/Down_Arrow_pic.PNG) *only* occurs when the word has one or more analyses *and* the current analysis in use by the focus box has one or more word gloss. You can select one of those glosses.
>
>   You can click the down arrow in the **Word** line, select **New word gloss**, and then enter a new gloss in the **Word Gloss** line.
>
> - The **Word Gloss** down arrow ![](../../../assets/images/Using_Tools/Texts_&_Words_tools/Interlinear_Texts/Down_Arrow_pic.PNG) list will contain the selectable command "**\<Empty\>**" after you have left the word with the **Word Gloss** line empty and then return to that word. This allows you to examine and close the menu while retaining an empty **Word Gloss** line.
>
> - If you specify a different word gloss such that the previous word gloss is no longer referenced by the current analysis, the previous word gloss will be automatically removed from the **Word Gloss** list.
>
> - - Said another way, Language Explorer will not save an existing gloss if this is the only occurrence of that word/word gloss. So, if a word occurred multiple times with the same word gloss, when you add or type over (edit) the word gloss there will be another word gloss. In contrast, if that word/word gloss occurred only one time, when you add or type over the word gloss, is not kept by Language Explorer.

> [!TIP]
>
> - In [Word Analyses](../Word_Analyses/Word_Analyses_overview.md), you can [add](../Word_Analyses/Add_Word_Gloss.md) and [merge](../Word_Analyses/Merge_word_gloss.md) word glosses in an analysis, and as desired, [assign analyses](../Word_Analyses/Analysis_Usage_box_details.md) to words at the word-gloss level. You can right-click the word gloss and select a menu command to [show](../../../Basic_Tasks/Show_data/Context_sens_menus.md) the word gloss in other areas, such as **Concordance** or **Analyses**.
>
> - You can edit, and [cut, copy and paste](../../../User_Interface/Menus/Edit/Cut_copy_and_paste.md) the contents in the **Word Gloss** line.
>
> - The **Word Gloss** line is *not* the same line as the **Lex Gloss** line.

## Related topics
[About Gloss and Analyze tabs](About_Gloss_Analyze_tabs.md)

[Configure Interlinear Lines dialog box](../../../User_Interface/Menus/Tools/Configure_interlinear_lines_dialog_box.md)

[Configure Interlinear Lines right-click](Configure_Interlinear_lines_right_click.md)

[Texts & Words overview](../Texts_and_Words_overview.md)
