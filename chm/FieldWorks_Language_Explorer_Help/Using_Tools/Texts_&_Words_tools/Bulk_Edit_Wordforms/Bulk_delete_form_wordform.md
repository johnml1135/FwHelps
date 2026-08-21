---
title: "Bulk delete forms or wordforms"
source_title: "Bulk delete forms or wordforms"
breadcrumb:
  - "Using Tools"
  - "Texts & Words tools"
  - "Bulk Edit Wordforms"
  - "Bulk delete forms"
source: "Using_Tools/Texts_&_Words_tools/Bulk_Edit_Wordforms/Bulk_delete_form_wordform.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Texts_%26_Words_tools/Bulk_Edit_Wordforms/Bulk_delete_form_wordform.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Delete:Bulk delete forms or wordforms"
  - "Texts & Words:Bulk delete forms or wordforms"
  - "Words:Bulk Edit Wordforms"
  - "Bulk Edit Wordforms (See: Texts & Words overview):Bulk delete forms or wordforms"
related:
  - "Bulk Edit overview -> ../../Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md"
  - "Delete a wordform -> ../Word_Analyses/Delete_a_wordform.md"
  - "Delete unwanted wordforms -> ../Interlinear_Texts/Delete_unwanted_words.md"
  - "Word list overview -> ../Word_list_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:a977fcc71283a0c3"
---

# Bulk delete forms or wordforms

*Using Tools › Texts & Words tools › Bulk Edit Wordforms*

In [Bulk Edit Wordforms](Bulk_Edit_Wordforms_overview.md), the **Delete** tab allows you to delete *unused* forms (of wordforms) or *entire* wordforms (analyses and all). For example, you may have previously entered forms in both orthographic and phonetic writing systems, but now you want to delete all the phonetic forms.

1.  In the **Navigation pane** click **Texts & Words**, and then click **Bulk Edit Wordforms**.

2.  In the **Wordforms** pane, click the **Delete** tab.

3.  [Configure columns](../../../Basic_Tasks/Configure_Columns/Configure_Columns_overview.md) to hide/show/move columns, and specify the writing systems displayed.

4.  [Filter](../../../Basic_Tasks/Filtering_data/filtering_data_overview.md) or [sort](../../../Basic_Tasks/Sorting_data/Sorting_data_overview.md) the data to display only applicable wordforms, such as only those for which the **Number in Corpus** is **0** (zero).

5.  In the **Bulk Edit Operation** pane **Item to delete** box, select one of the following:

    - **Form**

    - **Form (\<writing system\>)**,if a particular writing system is configured to appear for one or more **Form** columns.

    - **Wordforms (rows)**.

6.  In the left column, [select the rows](Bulk_Edit_Change_Spellings_selections.md) you want to change.

7.  Click **Preview**, and then review the pending deletions.

    - Make sure *only* rows you want to delete have a check mark (![](../../../assets/images/Using_Tools/Texts_&_Words_tools/Bulk_Edit_Wordforms/CheckMark.PNG)) in the left column.

8.  If you want start over, click **Clear**. Otherwise, click **Apply**.

    The pending deletion operation occurs.

> [!IMPORTANT]
>
> - The total number of forms listed in the **Wordforms** pane depends on how many texts are [included](../../../User_Interface/Toolbars/Insert_toolbar.md). Forms from excluded texts are **not** displayed in the pane.
>
> - A **Number in Corpus** of **0** (zero) occurs for words no longer used in any *texts*. However, some vernacular words may continue to appear in vernacular metadata, such as in [Info tab fields](../../../User_Interface/Field_Descriptions/Texts_%26_Words/Texts_%26_Words_fields_overview.md). Such words remain in the [vernacular spelling dictionary](../../../Basic_Tasks/Spell_Checking/vernacular_spell_checking.md) even if you delete them from the word list.
>
> - The **Configure Columns** dialog box uses the ![](../../../assets/images/Using_Tools/Texts_&_Words_tools/Bulk_Edit_Wordforms/Bulk_Edit_Symbol.GIF) symbol to indicate the fields that *may* be available for bulk editing, depending on the operation you want to do.

## Related topics
[Bulk Edit overview](../../Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md)

[Delete a wordform](../Word_Analyses/Delete_a_wordform.md)

[Delete unwanted wordforms](../Interlinear_Texts/Delete_unwanted_words.md)

[Word list overview](../Word_list_overview.md)
