---
title: "FieldWorks Project Utilities overview"
source_title: "FieldWorks Project Utilities overview"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Tools"
  - "Utilities"
  - "FieldWorks Project Utilities overview"
source: "User_Interface/Menus/Tools/Language_Project_Utilities_overview.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Tools/Language_Project_Utilities_overview.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Utilities"
  - "Homograph numbers:Reassign Homographs Utility"
  - "Error"
  - "Error:Error messages"
  - "solving"
  - "Merge duplicate wordforms"
  - "FieldWorks Stopped Working error message"
  - "Reversal Subentry sort order"
  - "Reversal Subentry sort order:FieldWorks Project Utilities overview"
related:
  - "Change the Grammatical Info -> ../../../Using_Tools/Lexicon_tools/Lexicon_Edit/change_the_grammatical_info.md"
  - "Change homograph numbers -> ../../../Using_Tools/Lexicon_tools/Browse/Change_homograph_numbers.md"
  - "Export overview -> ../File/Export/Export_overview.md"
  - "Export Through Pathway -> ../File/Pathway_Configuration_Tool/Export_Through_Pathway.md"
  - "Import overview -> ../../../Beginning_Tasks/Importing_Data/Import_overview.md"
  - "Publish Entry In field -> ../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Publication_Settings_flds/Publish_In_(Publication_Settings).md"
  - "Tools menu overview -> Tools_overview.md"
fw_help_version: "9.3"
type: "index"
content_hash: "sha256:1af61a5e5c2a240e"
---

# FieldWorks Project Utilities overview

*User Interface › Menus › Tools › Utilities*

> [!IMPORTANT]
>
> - You cannot use **Undo** to reverse the changes these utilities. If you use Send/Receive, discuss this with those you collaborate with before you use any of the utilities. You should consider [backing up](../File/Backup_and_Restore/Back_up_this_Project.md) the language project. If the results of using a utility are not satisfactory, you need to [restore](../File/Backup_and_Restore/Restore_a_project.md) a previously backed-up version of the language project.
>
> - You will probably want to [get more help](../../../Overview/Technical_support.md) before you use these utilities.
>
> To run one or more of the utilities listed below, select the ones you want to run, read *all* of the information and *cautions* in the **Description** pane for each utility. Then, click **Run Checked Utilities Now**. When finished, click **Close**.

## Utilities - (*Not* an exhaustive list)

- [Convert variants to irregularly inflected form variants](Convert_variants_utility.md)

- [Convert irregularly inflected form variants to variants](Convert_variants_utility.md)

<!-- -->

- **Delete Entries and Senses that are not used in interlinear texts**

Use this utility to *delete all entries and senses* that are not referenced in the *current set* ([chosen for display](../../../Basic_Tasks/Filtering_data/Choose_Texts.md)) of interlinear texts. [Back up your project](../File/Backup_and_Restore/Back_up_this_Project.md) before you use this utility, and carefully read the **Cautions** displayed in the dialog box. A **Delete Entries Confirmation** warning box appears and shows the number of entries that will be deleted.

- **Find and fix errors in a FieldWorks data (XML) file**

  If you think possible data corruption may be the cause of a FieldWorks crash, run this utility on that language project. If necessary, request [technical support](../../../Overview/Technical_support.md).

- 1.  [Open](../File/Open_a_language_project.md) a *different* language project.

  2.  Close the project that you think may have data errors.

  3.  On the **Tools** menu, click **Utilities**.

  4.  Select (![](../../../assets/images/CheckedBox.PNG)) this utility, click **Run Checked Utilities Now**.

  5.  In the **Fix Data Errors in Project** dialog box, select the project that you think may have errors, and then click **Fix Links**.

  6.  After the **Progress Dialog** closes, if any errors were found, the **Errors found or fixed** window appears. Click **OK** to close it.

<!-- -->

- **Force Rechecking Word Breaks**

The utility clears an internal flag that FLEx used to know if a text's analysis it up-to-date.

- **Merge Duplicate Wordforms**

  If you see duplicate wordforms in the [word list](../../../Using_Tools/Texts_%26_Words_tools/Word_list_overview.md) shown in **Word List Concordance** or **Word Analyses**, you can use this utility to merge duplicates into a single wordform.

  - You cannot undo merged wordforms, so it is strongly recommended that you [back up the project](../File/Backup_and_Restore/Back_up_this_Project.md) *before* you run this utility.

  - After you run the utility, you may want to close and reopen Language Explorer to fully refresh the data.

  - All analyses are kept, so you need to review and [delete](../../../Using_Tools/Texts_%26_Words_tools/Word_Analyses/Delete_an_analysis.md) any duplicate analyses.

  - The [Spelling status](../../../Using_Tools/Texts_%26_Words_tools/Word_Analyses/Specify_spelling_status.md) will be set to **Correct** if any instances of the wordform were set to correct. Otherwise, it remains **Undecided**.

  - To run this utility on the currently open project, select (![](../../../assets/images/CheckedBox.PNG)) **Merge Duplicate Wordforms**, and then click **Run Checked Utilities Now**. Click **Close** when it is finished.

<!-- -->

- **Reassign Homographs**

  Use this utility when the language project has entries with duplicate or missing homograph numbers, or when there are gaps in the homographs' number sequences. You may want to run this utility before you export the lexical data.

- **Remove circular reverences to complex forms**

Use this tool if Language Explorer disappears or produces a "FieldWorks has stopped working" message box when you try to look at the [Dictionary](../../../Using_Tools/Lexicon_tools/Dictionary/Dictionary_overview.md).

- **Remove Parser-approved analyses**

  Use this utility when you think there are problems of any kind with the analyses that are returned by a parser, or when you simply want to remove *all* parser-approved analyses for the *entire* [word list](../../../Using_Tools/Texts_&_Words_tools/Word_list_overview.md). The [Parse result](../../Field_Descriptions/Texts_&_Words/Parse_result_field.md) field for the remaining analyses changes to show **Untested**.

  To remove the parser-approved analyses from *one* word, use [Clear Current Word's Parser Analyses](../Parser/Clear_current_parser_analyses.md) on the **Parser** [menu](../Parser/Parser_menu_overview.md).

- **Sort Reversal Subentries**

Run this utility when you want your reversal subentries to be sorted alphabetically (in contrast to a manually chosen order, such as by frequency of use).

- **Use standard Part of Speech GUIDs**

Use this utility to make the part of speech GUIDs for your project match the GOLD standard. If your project was created before FieldWorks version 8.1 and you want to use the data as part of a multi-language query, use this utility to standardize the internal identifiers (GUIDs).

- **Write Everything**

Use this utility to write all CmObjects out fresh (updates the fwdata file) towards fixing send/receive problems.

## Related topics
[Change the Grammatical Info](../../../Using_Tools/Lexicon_tools/Lexicon_Edit/change_the_grammatical_info.md)

[Change homograph numbers](../../../Using_Tools/Lexicon_tools/Browse/Change_homograph_numbers.md)

[Export overview](../File/Export/Export_overview.md)

[Export Through Pathway](../File/Pathway_Configuration_Tool/Export_Through_Pathway.md)

[Import overview](../../../Beginning_Tasks/Importing_Data/Import_overview.md)

[Publish Entry In field](../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Publication_Settings_flds/Publish_In_(Publication_Settings).md)

[Tools menu overview](Tools_overview.md)
