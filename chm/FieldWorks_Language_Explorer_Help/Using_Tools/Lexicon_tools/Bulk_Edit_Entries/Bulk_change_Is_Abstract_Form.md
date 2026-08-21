---
title: "Bulk change Is Abstract Form"
source_title: "Bulk change Is Abstract Form"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Bulk Edit Entries"
  - "Bulk change Is Abstract Form"
source: "Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_change_Is_Abstract_Form.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_change_Is_Abstract_Form.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Bulk Edit Entries:Bulk change Is Abstract Form"
related:
  - "Bulk Edit overview -> bulk_edit_overview.md"
  - "Lexicography Tasks overview -> ../../../Lexicography_Tasks/Dictionary_and_Lexicon_overview.md"
  - "Lexicon Edit fields overview -> ../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Lexicon_Edit_fields_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:47e8eb47eaae0473"
---

# Bulk change Is Abstract Form

*Using Tools › Lexicon tools › Bulk Edit Entries*

In [Bulk Edit Entries](Bulk_Edit_Entries_overview.md), you can change **yes** (![](../../../assets/images/CheckedBox.PNG)) or **no** (![](../../../assets/images/User_Interface/Menus/Tools/UncheckedBox.PNG)) selections in the **Is Abstract Form** field for entries, or in the **Is Abstract Form (Allomorph)** field for allomorphs.

1.  In the **Navigation** **Pane**, click **Lexicon**, and then click **Bulk Edit Entries**.

2.  Click the **List Choice** tab.

3.  [Use](../../../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) the **Configure Columns** dialog box to hide/show/move columns (fields) and select writing systems, if permitted. Show the **Headword** (or **Lexeme Form**) and **Is Abstract Form** fields, or **Allomorphs** and **Is Abstract Form (Allomorph)** fields.

4.  [Filter](../../../Basic_Tasks/Filtering_data/filtering_data_overview.md) or [sort](../../../Basic_Tasks/Sorting_data/Sorting_data_overview.md) the data as needed.

5.  In the left column, [select the rows](select_rows.md) you want to change.

6.  In the **Bulk Edit Operation** pane, do the following:

    - In the **Target Field** box, select **Is Abstract Form** or **Is Abstract Form (Allomorph)**.

    - In the **Change To** box, select **yes** or **no**.

7.  Click **Preview**, review the pending changes, and then click **Apply**.

    The rows with a check mark in the left column change.

> [!TIP]
>
> You can control which entries and allomorphs are available to a computational [parser](../../../User_Interface/Menus/Parser/Parsing_words_overview.md). Then you can get a parser working correctly on an incremental basis:
>
> - Suppose you imported many entries or added many with **Collect Words**. If you pass a large number of them through the parser while your morphological modelling (environments, rules, features and so on) is incomplete, it will run longer and you may find many wrong analyses.
>
> - Instead, use **Bulk Edit Entries** feature to quickly set all the entries and allomorphs to **yes** (abstract), and then set a small subset of them to **no** (not abstract). When the parser yields correct analyses for that subset, then set more entries or allomorphs to **no**. Eventually, only entries and allomorphs that are actually abstract will be set to **y****es**.

## Related topics
[Bulk Edit overview](bulk_edit_overview.md)

[Lexicography Tasks overview](../../../Lexicography_Tasks/Dictionary_and_Lexicon_overview.md)

[Lexicon Edit fields overview](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Lexicon_Edit_fields_overview.md)
