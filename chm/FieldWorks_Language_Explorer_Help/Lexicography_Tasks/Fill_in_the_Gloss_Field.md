---
title: "Fill in the Gloss field"
source_title: "Fill in the Gloss field"
breadcrumb:
  - "Lexicography Tasks"
  - "Fill in the Gloss field"
source: "Lexicography_Tasks/Fill_in_the_Gloss_Field.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Lexicography_Tasks/Fill_in_the_Gloss_Field.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Bulk Edit Entries:Fill in the Gloss field"
  - "Lexicography tasks"
related:
  - "Bulk Edit overview -> ../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md"
  - "Lexicography Tasks overview -> Dictionary_and_Lexicon_overview.md"
  - "Using regular expressions assistance -> ../Basic_Tasks/Filtering_data/Using_regular_expressions_assistance.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:79809851468b8f33"
---

# Fill in the Gloss field

*Lexicography Tasks*

For lexical entries that have a definition, but not a gloss, you can fill in the [Gloss field](../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Gloss_field_Sense.md) as follows:

1.  Use **Bulk Copy** to copy all definitions consisting of a *single word* into the gloss field, as follows:

    - In the **Navigation Pane**, click **Lexicon**, and then click **Bulk Edit Entries**.

    - Click the **Bulk Copy** tab.

    - [Use](../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) the **Configure Columns** dialog box to display the **Definition** field and **Gloss** field.

    - In the **Source Field** box, select **Definition**.

    - In the **Target** **Field** box, select **Gloss**.

    - In the **Definition** column, [filter for](../Basic_Tasks/Filtering_data/Using_Filter_for.md) single words using the following [regular expression](../Basic_Tasks/Filtering_data/About_Regular_Expressions.md):

      `^[^ ]+$`

      The regular expression consists of “caret, left-square-bracket, caret, space, right-square-bracket, plus sign, and dollar-sign”. (You can cut and paste the regular expression into the **Filter for items containing** dialog box.)

    - In the left column, [select the rows](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/select_rows.md) you want to change.

    - Click **Preview**, review the pending changes, and then click **Apply**.

2.  Use **Click Copy** to copy individual words from a *longer definition* into the **Gloss** field, as follows:

    - In **Bulk Edit Entries**, click the **Click Copy** tab.

    - On the **View** [toolbar](../User_Interface/Toolbars/View_toolbar.md), click![](../assets/images/Lexicography_Tasks/clear_filters.gif)to remove all filters.

    - In the **Gloss** column [filter for](../Basic_Tasks/Filtering_data/Using_Filter_for.md) **Blanks**.

    - In the **Target Field** box, select **Gloss**.

    - For each entry, click the word in the **Definition** field that you want to use as the gloss for that entry.

      The word you click is automatically copied into the **Gloss** column, which is the **Gloss** field for that entry.

> [!TIP]
>
> - For additional information about the propose of this topic or when it may be of use to you, on the [Help](../User_Interface/Menus/Help/Help_overview.md) menu, point to **Resources** and then click **Introduction to Lexicography**.

## Related topics
[Bulk Edit overview](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md)

[Lexicography Tasks overview](Dictionary_and_Lexicon_overview.md)

[Using regular expressions assistance](../Basic_Tasks/Filtering_data/Using_regular_expressions_assistance.md)
