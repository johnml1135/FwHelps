---
title: "Bulk change writing system"
source_title: "Bulk change writing system"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Bulk Edit Entries"
  - "Bulk change writing system"
source: "Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_change_writing_system.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_change_writing_system.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Bulk Edit Entries:Bulk change writing system"
  - "Change:Writing systems"
  - "Change:Writing system of words"
related:
  - "Basic Tasks overview -> ../../../Basic_Tasks/Basic_Tasks_overview.md"
  - "Bulk Edit overview -> bulk_edit_overview.md"
  - "Lexicography Tasks overview -> ../../../Lexicography_Tasks/Dictionary_and_Lexicon_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:f973d0557d333fd9"
---

# Bulk change writing system

*Using Tools › Lexicon tools › Bulk Edit Entries*

Suppose you imported data or typed words into the wrong line of a [single-line text](../../../User_Interface/Field_Descriptions/Field_Types/Single_line_text_field.md) field, such as **Gloss**. You could have, for example, Portuguese words in an English line, and the [Format toolbar](../../../User_Interface/Toolbars/Format_toolbar.md) list would show English. Here is one way to correct such a problem using **Bulk Copy** and then **Bulk Replace**, without using regular expressions. Adapt this process to your situation.

1.  In the **Navigation** **Pane**, click **Lexicon**, and then click **Bulk Edit Entries**.

2.  Click the **Bulk Copy** tab.

3.  [Use](../../../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) the **Configure Columns** dialog box to hide/show/move columns and specify writing systems. You will need to show two columns for the field with words in the wrong writing system, with each column using a different, but specific, writing system. Do *not* use **Default Analysis** or **Default Vernacular**.

4.  [Filter](../../../Basic_Tasks/Filtering_data/filtering_data_overview.md) or [sort](../../../Basic_Tasks/Sorting_data/Sorting_data_overview.md) the data to display only applicable entries or senses.

5.  In the left column, [select the rows](select_rows.md) you want to change.

6.  In the **Bulk Edit Operation** pane, do the following:

    - In the **Source Field** box, select the field that has words in the wrong line. For example, **Glosses (Eng)**.

    - In the **Target Field** box, select the field into which you want to copy those words. For example, **Glosses (Por)**.

    - Click **Preview**, and then click **Apply**.

    The words are now in the correct line of the single-line text field, but are still use the wrong writing system. So, now you need to use **Bulk Replace** to change the writing system.

7.  Click the **Bulk Replace** tab, and then click **Setup**.

8.  In the **Target Field** box, select the field that has words in the wrong writing system. For example, **Glosses (Por)**.

9.  Do the following in the **Bulk Replace Setup** dialog box:

    - Click **More** to open **Search Options**.

    - Click the **Find what** box, but leave it empty.

    - Click the **Format** button, point to **Writing Systems**, and then click the writing system that is incorrectly used.

    - Click the **Replace with** box, but leave it empty.

    - Click the **Format** button, point to **Writing Systems**, and then click the writing system that you want to use for the words.

    - Under the **Find what** and **Replace with** boxes, **Format**: shows the two writing systems. If they are both correct, continue. Otherwise, use the **Format** button to change a writing system again.

    - Click **OK**.

10. Click **Preview**, review the pending changes, and then click **Apply**.

    For the rows with a check mark in the left column, the words in the **Target Field** column change to use the writing system.

> [!TIP]
>
> - In the **Normal** [style](../../../User_Interface/Menus/Format/Styles/Styles_Font_tab.md), you can temporarily change the color of a writing system to help you distinguish words by the writing systems they use.

## Related topics
[Basic Tasks overview](../../../Basic_Tasks/Basic_Tasks_overview.md)

[Bulk Edit overview](bulk_edit_overview.md)

[Lexicography Tasks overview](../../../Lexicography_Tasks/Dictionary_and_Lexicon_overview.md)
