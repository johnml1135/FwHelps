---
title: "Bulk replace nothing with something"
source_title: "Bulk replace nothing with something"
breadcrumb:
  - "Lexicography Tasks"
  - "Bulk replace nothing with something"
source: "Lexicography_Tasks/bulk_replace_nothing.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Lexicography_Tasks/bulk_replace_nothing.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Replace:Bulk Replace Nothing with Something"
  - "Bulk Edit Entries:Bulk replace nothing with something"
  - "Add:A word to many entries at the same time"
  - "Lexicography tasks"
related:
  - "Basic Tasks overview -> ../Basic_Tasks/Basic_Tasks_overview.md"
  - "Bulk Edit Entries overview -> ../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_Edit_Entries_overview.md"
  - "Bulk Edit overview -> ../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md"
  - "Bulk replace something with nothing -> bulk_replace_something.md"
  - "Lexicography Tasks overview -> Dictionary_and_Lexicon_overview.md"
  - "Using regular expressions assistance -> ../Basic_Tasks/Filtering_data/Using_regular_expressions_assistance.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:b9c52906b0da78c0"
---

# Bulk replace nothing with something

*Lexicography Tasks*

This topic helps you populate empty fields.

1.  In the **Navigation** **Pane**, click **Lexicon**, and then click a **Bulk Edit** tool.

2.  Click the **Bulk Replace** tab.

3.  [Use](../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) the **Configure Columns** dialog box to hide/show/move columns (fields) and select writing systems, if permitted.

4.  [Filter](../Basic_Tasks/Filtering_data/filtering_data_overview.md) or [sort](../Basic_Tasks/Sorting_data/Sorting_data_overview.md) the data as needed. In this case, you will want to display *blank* (empty) fields.

5.  In the left column, [select the rows](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/select_rows.md) you want to change.

6.  In the **Bulk Edit Operation** pane, do the following:

    - In the **Target Field** box, select the field in which you want to replace content.

    - Click **Setup**.

    The **Bulk Replace Setup** dialog box opens.

7.  In the dialog box, do the following:

    - Click **More** to display the [Search Options](../Basic_Tasks/Find_and_Replace/Search_Options.md), and then select **Use regular expressions**.

    - In the **Find what** box, enter the [regular expression](../Basic_Tasks/Filtering_data/About_Regular_Expressions.md) `^$`. Alternatively, click the ![](../assets/images/Lexicography_Tasks/RegExpAssistButton.png) button at the end of the **Find what** box, and then select the **^** **Beginning of line** and **\$** **End of line** characters from the menu of regular expressions that appears.

    - In the **Replace with** box, enter the desired replacement text.

    - Click **OK**.

8.  Click **Preview**, review the pending changes, and then click **Apply**.

> [!TIP]
>
> - For example, you could make a process, part of which is a variation of the above topic, to help you do the following:
>
>   If you have noun classes that take a different plural affix and you want to indicate the plural affix in a custom field, you could first fill in all the irregular affixes, and then use **Bulk Replace** to fill in all the regular ones.
>
> - For additional information about the purpose of this topic or when it may be of use to you, on the [Help](../User_Interface/Menus/Help/Help_overview.md) menu, point to **Resources** and then click **Introduction to Lexicography**.

## Related topics
[Basic Tasks overview](../Basic_Tasks/Basic_Tasks_overview.md)

[Bulk Edit Entries overview](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_Edit_Entries_overview.md)

[Bulk Edit overview](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md)

[Bulk replace something with nothing](bulk_replace_something.md)

[Lexicography Tasks overview](Dictionary_and_Lexicon_overview.md)

[Using regular expressions assistance](../Basic_Tasks/Filtering_data/Using_regular_expressions_assistance.md)
