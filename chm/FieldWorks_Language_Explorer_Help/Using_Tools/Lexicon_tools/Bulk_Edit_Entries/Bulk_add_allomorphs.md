---
title: "Bulk add allomorphs"
source_title: "Bulk add allomorphs"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Bulk Edit Entries"
  - "Bulk add allomorphs"
source: "Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_add_allomorphs.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_add_allomorphs.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Bulk Edit Entries:Bulk add allomorphs"
related:
  - "Bulk Edit overview -> bulk_edit_overview.md"
  - "Lexicography Tasks overview -> ../../../Lexicography_Tasks/Dictionary_and_Lexicon_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:e67761933c9fb983"
---

# Bulk add allomorphs

*Using Tools › Lexicon tools › Bulk Edit Entries*

In [Bulk Edit Entries](Bulk_Edit_Entries_overview.md), you can use **Bulk Copy** to populate **Allomorph** fields with content from the **Lexeme Form** or **Citation Form** fields. You can then use the **Bulk Replace** tab or the **Process** tab to change each copy into actual allomorphs. See **Example** below.

1.  In the **Navigation** **Pane**, click **Lexicon**, and then select **Bulk Edit Entries**.

2.  Click the **Bulk Copy** tab.

3.  Do any of the following to display and then select the entries you will change:

    - [Use](../../../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) the **Configure Columns** dialog box to hide/show/move columns (fields) and select writing systems, if permitted. Show the **Headword** (or **Lexeme Form** or **Citation Form**) and **Allomorphs** fields.

    - [Filter](../../../Basic_Tasks/Filtering_data/filtering_data_overview.md) or [sort](../../../Basic_Tasks/Sorting_data/Sorting_data_overview.md) the data to display only applicable entries.

    - In the left column, [select the rows](select_rows.md) you want to change.

4.  In the **Bulk Edit Operation** pane, do the following:

    - In the **Source Field** box, select **Headword** (or **Lexeme Form** or **Citation Form**).

    - In the **Target Field** box, select **Allomorphs**.

    - In the **If the Target field is not empty** area, click the applicable option.

5.  Click **Preview**, review the pending changes, and then click **Apply**.

    The rows with a check mark in the left column change.

6.  At this point, the steps are too language specific to list here. However, consider the following:

    - You could use the context-sensitive menu command **Sorted From End** in the **Allomorphs** column or other custom filters to help you identify similar forms. Then you can edit them with bulk edit features or manually edit them in the column, for example, to strip off a final character.

    - Then, you can bulk add or copy environments, inflection classes or required features as needed.

### Example

- Suppose a language used a prefix *maN*- that has the following characteristics:

  - The *N* assimilates to the point of articulation of the following obstruent. So *N* becomes m before b or p; n before d, t, or s; and ng before k, g.

  - The initial obstruent of the stem then deletes. So *maN-tidak* becomes **manidak**; *maN-bili* becomes **mamili**, and so on.

- You could create allomorphs of the stems/roots which do not have the initial obstruent *and* have an environment that they occur after *mam* (or *man* or **mang**, as the case may be).

## Related topics
[Bulk Edit overview](bulk_edit_overview.md)

[Lexicography Tasks overview](../../../Lexicography_Tasks/Dictionary_and_Lexicon_overview.md)
