---
title: "Fill in the Reversals field"
source_title: "Fill in the Reversals field"
breadcrumb:
  - "Lexicography Tasks"
  - "Fill in the Reversal field"
source: "Lexicography_Tasks/Fill_in_the_Reversals_Field.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Lexicography_Tasks/Fill_in_the_Reversals_Field.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Bulk Edit Entries:Fill in the Reversals field"
  - "Lexicography tasks"
related:
  - "Bulk Edit overview -> ../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md"
  - "Lexicography Tasks overview -> Dictionary_and_Lexicon_overview.md"
  - "Using regular expressions assistance -> ../Basic_Tasks/Filtering_data/Using_regular_expressions_assistance.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:d804076725b2090f"
---

# Fill in the Reversals field

*Lexicography Tasks*

Using the content [entered in Gloss fields](Fill_in_the_Gloss_Field.md) or **Definition** fields, you can use the **Bulk Edit** tools to populate one or more [reversal indexes](../Using_Tools/Lexicon_tools/Reversal_Indexes/reversal_indexes_overview.md). The [Reversal Entries field](../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/reversal_entries_field.md) in **Lexicon Edit** is called **Reversals** in [Bulk Edit Entries](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_Edit_Entries_overview.md). The **Definition** fields may have been populated by prior use of [Collect Words](../Using_Tools/Lexicon_tools/Collect_Words/Create_a_Lexical_entry_in_Collect_Words.md).

You need to decide which of the steps below are applicable to your situation. For example, you may not need to copy the entire contents from a **Definition** field into the **Reversals** field, so you can skip that step.

1.  In the **Navigation Pane**, click **Lexicon**, and then click **Bulk Edit Entries**.

2.  Click the **Bulk Copy** tab.

3.  [Use](../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) the **Configure Columns** dialog box to hide/show/move columns (fields) and select writing systems, if permitted. Show one or more **Gloss** and **Reversals** fields.

4.  [Use](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_Copy.md) the **Bulk Copy** tab to copy all glosses consisting of a *single* word into the **Reversal** field, as follows:

    - Click the **Bulk Copy** tab.

    - In the **Source Field** box at the bottom, select **Gloss**.

      (If **Gloss** fields are listed in more than one analysis writing system, make sure you select the correct one.)

    - In the **Target Field** box, select **Reversal**.

      (If **Reversal** fields are listed in more than one analysis writing system, make sure you select the correct one.)

    - In the **If the Target Field is not empty** area, select the applicable option, which is this case is typically **Do nothing**.

    - In the **Gloss** column, [filter for](../Basic_Tasks/Filtering_data/Using_Filter_for.md) single words using the following [regular expression](../Basic_Tasks/Filtering_data/About_Regular_Expressions.md):

      `^[^ ]+$`

      The regular expression consists of “caret, left-square-bracket, caret, space, right-square-bracket, plus sign, dollar-sign”. (You can cut and paste the regular expression into the **Filter for items containing** dialog box.)

    - In the left column, [select the rows](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/select_rows.md) you want to change.

    - Click **Preview**, review the pending changes, and then click **Apply**.

    Copies of the single word glosses appear in the **Reversals** field.

5.  [Use](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_Click_Copy.md) the **Click Copy** to copy a *single* word from the **Gloss** or **Definition** field into the **Reversal** field, as follows:

    - Click the **Click Copy** tab.

    - On the [View](../User_Interface/Toolbars/View_toolbar.md) toolbar, click![](../assets/images/Lexicography_Tasks/clear_filters.gif)to remove all filters.

    - In the **Target Field** box, select **Reversals** (in the correct writing system).

    - In the **Reversal** column, [filter for](../Basic_Tasks/Filtering_data/Using_Filter_for.md) **Blanks**.

    - In the **Copy** area, you should leave **Word** selected.

    - In the **If the Target Field is not empty** area, you can use the **Append** option, noting that the active filter allows only blank (empty) fields. However, you can select **Overwrite** any time you need to correct a mistake or you change your mind.

    - For each entry, click the word in the **Gloss** or **Definition** field that you want to use as the reversal index entry for that sense.

      Each word you click is copied into the **Reversals** field for the associate sense.

6.  Use the **Click Copy** tab to append *an additional* *word* from the **Gloss** or **Definition** field into the **Reversals** field, as follows.

    - In **Bulk Edit Entries**, **Click Copy** tab, make sure **Word** is selected in the **Copy** area.

    - In the **If the Target Field is not empty** area, select **Append, separated by**.

    - In the **separated** **by** box, type a space (press the space bar on your keyboard).

      Each word you click will be added to the end of the **Reversal** field.

7.  Use the **Click Copy** tab to copy the *entire* **Definition** field into the **Reversal** field, as follows:

    - In the **Copy** area, select **String, reordered at word clicked**.

      If you click on the first word in the **Gloss** or **Definition** field, the entire definition will be copied into the **Reversals** field. However, if you click on any other word, it will become the first word in the **Reversals** field. Any word in front of it will be placed at the end of the **Reversals** field with a comma between the two parts. For example, if you click on ‘quiet’ in the definition ‘to gradually become quiet’, it will copy ‘quiet, to gradually become’ into the **Reversals** field.

8.  Use the **Click Copy** tab to add *additional* reversal index entries to the **Reversals** field, as follows:

    - If you are filtering for **Blanks** in the **Reversal** column, click![](../assets/images/Lexicography_Tasks/clear_filters.gif) on the [View](../User_Interface/Toolbars/View_toolbar.md) toolbar to remove all filters.

    - In the **If the Target Field is not empty** area, select **Append, separated by**.

    - In the **separated** **by** box, put a semicolon followed by a space (; ).

    - In the **Copy** area, select **Word**.

      Each word you click will be added to the end of the **Reversals** field, but it will be separated from the first reversal index entry by a semicolon. The semicolon is used by FieldWorks to separate different index entries in the **Reversals** field.

    - In the **Copy** area, select **String, reordered at word clicked** if you want to add the entire definition instead of only a single word.

9.  Use the **Click Copy** tab to *replace* a reversal index entry in the **Reversals** field, as follows:

    - In the **If destination is not empty** area, select **Overwrite.**

    - Click a word in the **Gloss** or **Definition** field (or any other field), to overwrite (replace) whatever is in the **Reversals** field.

> [!TIP]
>
> - You can right-click any row (sense) and then select **Show Entry in Lexicon** to see the results of your changes. Similarly, you can see the changes in [Reversal Indexes](../Using_Tools/Lexicon_tools/Reversal_Indexes/reversal_indexes_overview.md).
>
> - For additional information about the propose of this topic or when it may be of use to you, on the [Help](../User_Interface/Menus/Help/Help_overview.md) menu, point to **Resources** and then click **Introduction to Lexicography**.

## Related topics
[Bulk Edit overview](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md)

[Lexicography Tasks overview](Dictionary_and_Lexicon_overview.md)

[Using regular expressions assistance](../Basic_Tasks/Filtering_data/Using_regular_expressions_assistance.md)
