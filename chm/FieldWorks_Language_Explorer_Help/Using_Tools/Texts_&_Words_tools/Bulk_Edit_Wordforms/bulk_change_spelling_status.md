---
title: "Bulk change spelling status"
source_title: "Bulk change spelling status"
breadcrumb:
  - "Using Tools"
  - "Texts & Words tools"
  - "Bulk Edit Wordforms"
  - "Bulk change Spelling Status"
source: "Using_Tools/Texts_&_Words_tools/Bulk_Edit_Wordforms/bulk_change_spelling_status.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Texts_%26_Words_tools/Bulk_Edit_Wordforms/bulk_change_spelling_status.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Texts & Words:Bulk change Spelling Status"
  - "Bulk Edit Wordforms (See: Texts & Words overview):Bulk change spelling status"
related:
  - "About spelling dictionary files -> ../../../Basic_Tasks/Spell_Checking/dictionary_files.md"
  - "Bulk Edit overview -> ../../Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md"
  - "Bulk Edit Wordforms overview -> Bulk_Edit_Wordforms_overview.md"
  - "Spelling Status field -> ../../../User_Interface/Field_Descriptions/Texts_&_Words/spelling_status_field.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:d2771db7e328364d"
---

# Bulk change spelling status

*Using Tools › Texts & Words tools › Bulk Edit Wordforms*

You can change the spelling status of multiple words at the same time. A **Spelling Status** of **Correct** adds words to the *vernacular* spelling dictionary [files](../../../Basic_Tasks/Spell_Checking/Vernacular_spelling_dictionary_files.md); **Incorrect** and **Undecided** remove them.

1.  In the **Navigation Pane**, click **Texts & Words**, and then click **Bulk Edit Wordforms** (if not already displayed).

2.  If necessary, [configure the columns](../../../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) to hide/show/move columns, and specify writing systems, if permitted. Show the **Spelling Status** and the **Number in Corpus** columns.

3.  In the **Wordforms** pane, [filter](../../../Basic_Tasks/Filtering_data/filtering_data_overview.md) or [sort](../../../Basic_Tasks/Sorting_data/Sorting_data_overview.md) the data to display only applicable words.

    - In **Number in Corpus**, select **Greater than 0**, or another appropriate filter.

    - In **Spelling Status**, select **Undecided**, or another status.

4.  In the left column, [select the rows](Bulk_Edit_Change_Spellings_selections.md) you want to change.

5.  Click the **List Choice** tab.

6.  In the **List Choice** tab, do the following:

    - In the **Target Field** box, select **Spelling Status**.

    - In the **Change To** box, select **Correct**, **Incorrect**, or **Undecided**.

7.  Click **Preview**, and then review the pending changes.

    - Make sure only the rows you want to change are [selected](Bulk_Edit_Change_Spellings_selections.md). If necessary, click **Clear** and then repeat any of the above steps.

8.  Click **Apply**.

    The spelling status for the words with a check mark in the left column are changed.

> [!TIP]
>
> - Some commands, such as **Edit Spelling Status** on the [Tools](../../../User_Interface/Menus/Tools/Tools_overview.md) menu, and other FieldWorks programs may allow you go directly to **Bulk Edit Wordforms** with column filters preset. In this case, you can ignore some of the steps given above.

## Related topics
[About spelling dictionary files](../../../Basic_Tasks/Spell_Checking/dictionary_files.md)

[Bulk Edit overview](../../Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md)

[Bulk Edit Wordforms overview](Bulk_Edit_Wordforms_overview.md)

[Spelling Status field](../../../User_Interface/Field_Descriptions/Texts_%26_Words/spelling_status_field.md)
