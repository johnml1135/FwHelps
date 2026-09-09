---
title: "Bulk add CV Pattern"
source_title: "Bulk add CV Pattern"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Bulk Edit Entries"
  - "Bulk add CV Pattern"
source: "Lexicography_Tasks/Bulk_add_CV_Pattern.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Lexicography_Tasks/Bulk_add_CV_Pattern.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Bulk Edit Entries:Bulk add CV Pattern"
  - "CV Pattern"
  - "Add:Bulk add CV Pattern"
  - "bulk change"
  - "Lexicography tasks"
related:
  - "Bulk Edit overview -> ../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md"
  - "Lexicography Tasks overview -> Dictionary_and_Lexicon_overview.md"
  - "Using regular expressions assistance -> ../Basic_Tasks/Filtering_data/Using_regular_expressions_assistance.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:536368bc315aa250"
---

# Bulk add CV Pattern

*Using Tools › Lexicon tools › Bulk Edit Entries*

In [Bulk Edit Entries](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_Edit_Entries_overview.md), use **Bulk Copy** to populate **CV Pattern** fields with content from the **Pronunciation** field. (Generally the **Pronunciation** field is the best indicator of the CV pattern of the headword, but you may want to use the **Citation Form** or **Lexeme Form** field instead). Then, use the **Bulk Replace** tab to change each consonant with a `C` and each vowel with a `V`.

1.  In the **Navigation** **Pane**, click **Lexicon**, and then select **Bulk Edit Entries**.

2.  Click the **Bulk Copy** tab.

3.  Do any of the following to display and then select the entries you will change:

    - [Use](../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) the **Configure Columns** dialog box to hide/show/move columns (fields) and select writing systems, if permitted.

      Show the **Pronunciation** (or **Headword**, **Lexeme Form**, or **Citation Form**) and **CV Pattern** fields.

    - [Filter](../Basic_Tasks/Filtering_data/filtering_data_overview.md) or [sort](../Basic_Tasks/Sorting_data/Sorting_data_overview.md) the data to display only applicable entries. For example, you may set a filter to display only entries with blank (empty) **CV Pattern** fields.

4.  In the **Bulk Edit Operation** pane, do the following:

    - In the **Source Field** box, select **Pronunciation** field.

    - In the **Target Field** box, select **CV Pattern**.

    - In the **If the Target field is not empty** area, click the applicable option. If you set a filter to show only *blank* (empty) **CV Pattern** entries, any option will work.

5.  In the left column, [select the rows](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/select_rows.md) you want to change.

6.  Click **Preview**, review the pending changes, and then click **Apply**.

    Do the steps in [Bulk change CV Pattern](Bulk_change_CV_Pattern.md) to change the vowels into `V`'s and the consonants into `C`'s.

> [!TIP]
>
> - For additional information about the purpose of this topic or when it may be of use to you, on the [Help](../User_Interface/Menus/Help/Help_overview.md) menu, point to **Resources** and then click **Introduction to Lexicography**.
>
> - In [Fill in the Pronunciation field](Fill_in_the_Pronunciation_Field.md), the examples given were `make` `=` ![](../assets/images/Lexicography_Tasks/makephon.gif) and `stitch` = ![](../assets/images/Lexicography_Tasks/stitchphon.gif) (with tᶘ an affricate). Their CV patterns would be `CVVC` and `CCVC`, respectively.

## Related topics
[Bulk Edit overview](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md)

[Lexicography Tasks overview](Dictionary_and_Lexicon_overview.md)

[Using regular expressions assistance](../Basic_Tasks/Filtering_data/Using_regular_expressions_assistance.md)
