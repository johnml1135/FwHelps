---
title: "Fill in the Tone field"
source_title: "Fill in the Tone field"
breadcrumb:
  - "Lexicography Tasks"
  - "Fill in the Tone field"
source: "Lexicography_Tasks/Fill_in_the_Tone_Field.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Lexicography_Tasks/Fill_in_the_Tone_Field.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Bulk Edit Entries:Fill in the Tone field"
  - "Lexicography tasks"
related:
  - "Bulk Edit overview -> ../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md"
  - "Lexicography Tasks overview -> Dictionary_and_Lexicon_overview.md"
  - "Using regular expressions assistance -> ../Basic_Tasks/Filtering_data/Using_regular_expressions_assistance.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:a28c3a3bfaf41073"
---

# Fill in the Tone field

*Lexicography Tasks*

Use **Bulk Copy** to copy pronunciations into the **Tone** fields and then **Bulk Replace** to remove all consonants. Next, use a processor in **Bulk** **Process** to convert remaining vowels to tone or stress marks—this typically requires assistance.

1.  In the **Navigation Pane**, click **Lexicon**, and then click **Bulk Edit Entries**.

2.  In the **Entries** pane, click the **Bulk Copy** tab, and then do any of the following to display and then select the entries you will change.

    - [Use](../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) the **Configure Columns** dialog box to hide/show/move columns (fields) and select writing systems, if permitted. Show the **Pronunciation** and **Tone** fields.

    - [Filter](../Basic_Tasks/Filtering_data/filtering_data_overview.md) or [sort](../Basic_Tasks/Sorting_data/Sorting_data_overview.md) the data to display only applicable entries.

3.  Do the following in the **Bulk Copy** tab:

    - In the **Source Field** box, select **Pronunciation**.

    - In the **Target Field** box, select **Tone**.

    - In the **If the Target Field is not empty** area, select the applicable option, considering if you want to overwrite any existing **Tone** field content.

    - In the left column, [select the rows](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/select_rows.md) you want to change.

    - Click **Preview**, review the pending changes, and then click **Apply**.

4.  Click the **Bulk Replace** tab, and then do the following:

    (The goal is to delete all consonants.)

    - In the **Target Field** box, select **Tone**.

    - Click the **Setup** button.

    - In the **Bulk Replace Setup** dialog box, click **More** to display the **Search Options**, and then click **Use regular expressions**.

    - In the **Find what** box, construct a [regular expression](../Basic_Tasks/Filtering_data/About_Regular_Expressions.md) to find all the consonants. You can click ![](../assets/images/Lexicography_Tasks/RegExpAssistButton.png) to display the regular expression assistant.

    - Make sure the **Replace with** box is empty, and then click **OK**.

    - [Select the rows](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/select_rows.md) you want to change.

    - Click **Preview**, review the pending changes, and then click **Apply**.

5.  In the **Process** tab, use a processor (*not* supplied with FieldWorks) to change the vowels into stress or tone marks.

    - Alternatively, you may be able to use [Bulk Replace](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_replace.md) features to change them.

> [!TIP]
>
> - For additional information about the purpose of this topic or when it may be of use to you, on the [Help](../User_Interface/Menus/Help/Help_overview.md) menu, point to **Resources** and then click **Introduction to Lexicography**.

## Related topics
[Bulk Edit overview](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md)

[Lexicography Tasks overview](Dictionary_and_Lexicon_overview.md)

[Using regular expressions assistance](../Basic_Tasks/Filtering_data/Using_regular_expressions_assistance.md)
