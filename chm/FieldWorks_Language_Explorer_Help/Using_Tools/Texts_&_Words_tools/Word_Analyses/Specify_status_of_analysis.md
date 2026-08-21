---
title: "Specify the status of an analysis"
source_title: "Specify the status of an analysis"
breadcrumb:
  - "Using Tools"
  - "Texts & Words tools"
  - "Word Analyses"
  - "Specify the status of an analysis"
source: "Using_Tools/Texts_&_Words_tools/Word_Analyses/Specify_status_of_analysis.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Texts_%26_Words_tools/Word_Analyses/Specify_status_of_analysis.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Specify (See Also: Select or Choose)"
  - "Specify (See Also: Select or Choose):Status of an analysis"
  - "Texts & Words:Specify the status of an analysis"
related:
  - "Word Analyses overview -> Word_Analyses_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:3159ed61976591c2"
---

# Specify the status of an analysis

*Using Tools › Texts & Words tools › Word Analyses*

For each analysis, you may *Approve* or *Disapprove* it or specify that its status is *Unknown*. That is, you can indicate your opinion of each analysis. This does *not* change the [Parse result field](../../../User_Interface/Field_Descriptions/Texts_&_Words/Parse_result_field.md).

1.  On the **Navigation Pane**, click **Texts & Words**, and then click **Word** **Analyses**.

2.  In the **Wordforms** pane, click the wordform for which you want to indicate your opinion.

3.  In the **Wordform** pane, click the analysis for which you will indicate your opinion.

    A menu button ![](../../../assets/images/Using_Tools/Texts_&_Words_tools/Word_Analyses/Menu_Button_pic.GIF) and links appear.

4.  Do one or more of the following:

    - For an analysis in the **User Approved (Analyses)** area, click the menu button to the left of the **Analysis 1** (or **Analysis 2**, and so on) label, point to **User Opinion**, and then select **Unknown** or **Disapprove**.

    - For an analysis in the **User Opinion Unknown (Analyses Candidates)** area, click the menu button to the left of the **Analysis Candidate 1** (or **Analysis Candidate 2**, and so on) label, point to **User Opinion**, and then select **Approve** or **Disapprove**.

    - For an analysis in the **User Disapproved (Test Case Analyses)** area, click the menu button to the left of the **Test Case 1** (or **Test Case 2**, and so on) label, point to **User Opinion**, and then select **Approve** or **Unknown**.

    The following happens:

    - Analyses you approved move into the **User Approved (Analyses)** area. A **Gloss** line is added so you can type or paste the gloss for the word.

    - Analyses you disapprove move into the **User Disapproved (Test Case Analyses)** area.

    - Analyses for which you specify **Unknown** move to the **User Opinion Unknown (Analyses Candidates)** area.

> [!IMPORTANT]
>
> - In the [Analyze](../Interlinear_Texts/texts_edit_overview.md) tab, words that used the analysis you moved to **User Disapproved** or **User Unknown** change to use another *approved* analysis, if any. Otherwise, they lose their analyses. You may need to refresh the window (`F5`) to see this result.
>
> - When you [analyze](../Interlinear_Texts/Analyze_Text_overview.md) text, you can approve analyses. This occurs *as a result* of the way you choose to move *from* a word focus box *to another* word. You may inadvertently approve an analysis you had recently moved to **User Disapproved** or **User Unknown**. See [Shortcuts](../../../User_Interface/Shortcuts/shortcut_keys_Texts_Words_tools.md) and [Data](../../../User_Interface/Menus/Data/Data_overview.md) menu for more information.
>
>   You *cannot* specify a disapproved or unknown status of an analysis from the **Analyze** tab.
>
> - Analyses that are user disapproved but continue to show **Successful** in the [Parse result](../../../User_Interface/Field_Descriptions/Texts_&_Words/Parse_result_field.md) field indicate that your grammar or constraints (environments, rules, and so on) permit an invalid [parse](../../../User_Interface/Menus/Parser/Parsing_words_overview.md) and consequently need additional work.

## Related topics
[Word Analyses overview](Word_Analyses_overview.md)
