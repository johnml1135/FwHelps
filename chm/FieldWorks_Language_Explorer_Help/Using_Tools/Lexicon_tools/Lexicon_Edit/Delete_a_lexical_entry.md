---
title: "Delete a lexical entry"
source_title: "Delete a lexical entry"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Lexicon Edit"
  - "Delete a lexical entry"
source: "Using_Tools/Lexicon_tools/Lexicon_Edit/Delete_a_lexical_entry.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Lexicon_Edit/Delete_a_lexical_entry.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Delete:Entry (one)"
  - "lexical"
  - "Unwanted words"
  - "delete"
  - "Words:Words"
  - "delete unwanted"
related:
  - "Lexicon Edit overview -> lexicon_edit_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:3b014cc64bb5f166"
---

# Delete a lexical entry

*Using Tools › Lexicon tools › Lexicon Edit*

This topics helps you delete one lexical entry. [Bulk delete entries or sense](../Bulk_Edit_Entries/Bulk_Delete_Entries_Senses.md) helps you delete multiple lexical entries at the same time.

1.  In the **Navigation** **Pane**, click **Lexicon**, and then click **Lexicon Edit**, **Browse** or **Dictionary**.

2.  Click the entry you will delete.

3.  Do one of the following:

    - On the [Standard](../../../User_Interface/Toolbars/Standard_toolbar.md) toolbar, click ![](../../../assets/images/Using_Tools/Lexicon_tools/Lexicon_Edit/RedDeleteRecordX.GIF).

    - On the **Edit** menu, click **Delete Entry**.

    - In a columnar view, right-click the unwanted entry, and then select **Delete selected Entry**.

    The **Delete Entry** warning box appears. The deletion may affect [interlinearized texts](../../Texts_&_Words_tools/Interlinear_Texts/Analyze_Text_overview.md). In this case, the warning box information includes how many [analyses](../../Texts_&_Words_tools/Word_Analyses/Word_Analyses_overview.md) reference the entry.

4.  If you are sure you want to delete the lexical entry identified in the warning box, click **Delete**.

    The lexical entry is deleted from the **Lexicon**. It is also deleted from the **Primary Entry References** field of any other entry that referenced is as its main entry. If the entry was used in one or more [analyses](../../Texts_%26_Words_tools/Interlinear_Texts/Analyze_Text_overview.md) of words in [texts](../../Texts_%26_Words_tools/Texts_and_Words_overview.md), those analyses remain, but *without* reference to the deleted entry.

> [!TIP]
>
> - Until the language project is [saved](../../../User_Interface/Menus/File/Save.md), you can use [Undo](../../../User_Interface/Menus/Edit/Undo_and_Redo.md) to restore the entry.

## Related topics
[Lexicon Edit overview](lexicon_edit_overview.md)
