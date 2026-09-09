---
title: "Bulk change CV Pattern"
source_title: "Bulk change CV Pattern"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Bulk Edit Entries"
  - "Bulk change CV Pattern"
source: "Lexicography_Tasks/Bulk_change_CV_Pattern.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Lexicography_Tasks/Bulk_change_CV_Pattern.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Bulk Edit Entries:Bulk change CV Pattern"
  - "CV Pattern"
  - "bulk change"
  - "Lexicography tasks"
related:
  - "Bulk Edit overview -> ../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md"
  - "Lexicography Tasks overview -> Dictionary_and_Lexicon_overview.md"
  - "Using regular expressions assistance -> ../Basic_Tasks/Filtering_data/Using_regular_expressions_assistance.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:16adbae464ed735e"
---

# Bulk change CV Pattern

*Using Tools › Lexicon tools › Bulk Edit Entries*

This topic helps you change any content in the **CV Pattern** field, such as content [added with Bulk Copy](Bulk_add_CV_Pattern.md), by replacing each consonant with a `C` and each vowel with a `V`. See **Tip** below.

1.  In the **Navigation** **Pane**, click **Lexicon**, and then click **Bulk Edit Entries**.

2.  Click the **Bulk Replace** tab.

3.  Do any of the following to display and then select the entries you will change:

    - [Use](../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) the **Configure Columns** dialog box to hide/show/move columns (fields) and select writing systems, if permitted. Show the **CV Pattern** field.

    - [Filter](../Basic_Tasks/Filtering_data/filtering_data_overview.md) or [sort](../Basic_Tasks/Sorting_data/Sorting_data_overview.md) the data to display only applicable entries.

    - In the left column, [select the rows](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/select_rows.md) you want to change.

4.  In the **Target Field** box, select **CV Pattern**.

5.  Click **Setup**, and then do the following steps in the **Find and Replace** dialog box:

    - Click **More**, and then select **Use regular expressions**.

    - In the **Find What** box, construct a [regular expression](../Basic_Tasks/Filtering_data/About_Regular_Expressions.md) to find all the vowels.

    - In the **Replace with** box, enter a `V`, and then click **OK**.

    - Click **Preview**, and then examine the **CV Pattern** field to see that the vowels are set to be replaced with a `V`. Make changes as needed. Alternatively, click **Clear** to reset the window so you can begin again.

    - Click **Apply**.

      The vowels are each replaced with a `V`.

6.  Click **Setup**, and then do the following steps in the **Find and Replace** dialog box:

    - Click **More**, and then select **Use regular expressions**, if it is not already selected.

    - In the **Find What** box, construct a [regular expression](../Basic_Tasks/Filtering_data/About_Regular_Expressions.md) to find all characters that are *not* `V`.

    - In the **Replace with** box, enter a `C`, and then click **OK**.

    - Click **Preview**, and then examine the **CV Pattern** field to see that characters that are not `V` are to be replaced with a `C`.

    - Click **Apply**.

      The column should contain only `C`'s and `V`'s for the selected (checked) entries.

7.  Review the results and manually correct any as necessary.

> [!TIP]
>
> - For additional information about the purpose of this topic or when it may be of use to you, on the [Help](../User_Interface/Menus/Help/Help_overview.md) menu, point to **Resources** and then click **Introduction to Lexicography**.
>
> - In [Fill in the Pronunciation field](Fill_in_the_Pronunciation_Field.md), the examples given were the `make =` ![](../assets/images/Lexicography_Tasks/makephon.gif) and stitch = ![](../assets/images/Lexicography_Tasks/stitchphon.gif) (with tᶘ an affricate). Their CV patterns would be `CVVC` and `CCVC`, respectively.

## Related topics
[Bulk Edit overview](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md)

[Lexicography Tasks overview](Dictionary_and_Lexicon_overview.md)

[Using regular expressions assistance](../Basic_Tasks/Filtering_data/Using_regular_expressions_assistance.md)
