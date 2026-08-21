---
title: "Fill in the Citation Form field"
source_title: "Fill in the Citation Form field"
breadcrumb:
  - "Lexicography Tasks"
  - "Fill in the Citation Form field"
source: "Lexicography_Tasks/Fill_in_the_Citation_Form_Field.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Lexicography_Tasks/Fill_in_the_Citation_Form_Field.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Bulk Edit Entries:Fill in the Citation Form field"
  - "Lexicography tasks"
related:
  - "Bulk Edit overview -> ../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md"
  - "Lexicography Tasks overview -> Dictionary_and_Lexicon_overview.md"
  - "Using regular expressions assistance -> ../Basic_Tasks/Filtering_data/Using_regular_expressions_assistance.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:d18861199375880e"
---

# Fill in the Citation Form field

*Lexicography Tasks*

The first step in creating an entry is to enter the form of the lexeme in the **Lexeme** field. In many languages, the bare stem is not a naturally occurring word. Naturally occurring words must have inflectional affixes. Consequently, many dictionaries must use an inflected form as the citation form. If your language is like this, you must add the correct citation form in the [Citation Form field](../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Citation_Form_field.md). This is the procedure for filling in the **Citation Form** field.

1.  Use **Bulk Cop****y** to copy all the forms from the **Lexeme** field to the **Citation Form** field, as follows:

    - In the **Navigation Pane**, click **Lexicon**, and then click **Bulk Edit Entries**.

    - Click the **Bulk Copy** tab.

    - [Use](../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) the **Configure Columns** dialog box to display the **Lexeme** and **Citation Form** fields.

    - In the **Source Field** box, select **Lexeme**.

    - In the **Target Field** box, select **Citation Form**.

    - (If you only want to create a citation form for single words, do this step. However, if you want to create a citation form for all your entries (recommended), skip this step and go on to the “**Click review**” step.) In the **Lexeme** column, [filter for](../Basic_Tasks/Filtering_data/Using_Filter_for.md) single words, using the following [regular expression](../Basic_Tasks/Filtering_data/About_Regular_Expressions.md):

      `^[^ ]+$`

      The regular expression consists of “caret, left-square-bracket, caret, space, right-square-bracket, plus-sign, dollar-sign”. (You can cut and paste the regular expression into the **Filter for items containing** dialog box.)

    - (If you only want to create a citation form for a single grammatical category (such as Verb), do this step. If you want to create a citation form for all grammatical categories, go on to the next step.) [Use](../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) the **Configure Columns** dialog box to display the **Grammatical Info** field.

      In the **Grammatical Info** column [filter for](../Basic_Tasks/Filtering_data/Using_Filter_for.md) the grammatical category (such as Verb) that you want to create a citation form for.

    - In the left column, [select the rows](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/select_rows.md) you want to change.

    - Click **Preview**, review the pending changes, and then click **Apply**.

2.  Use **Bulk Replace** to delete all inflectional affixes from forms in the **Lexeme** field, as follows:

    (If the form you entered in the **Lexeme** field was the correct citation form, do this step. However, if the form you entered in the **Lexeme** field was the bare stem, skip this step and go to step 3.)

    - In **Bulk Edit Entries**, click the **Bulk Replace** tab.

    - [Use](../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) the **Configure Columns** dialog box to display the **Lexeme** field.

    - In the **Target Field** box, select **Lexeme**.

    - In the **Lexeme** column, [filter for](../Basic_Tasks/Filtering_data/Using_Filter_for.md) the affix that you want to delete.

    - [Select the rows](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/select_rows.md) you want to change.

    - Click **Setup**.

    - Click **More** to display the **Search Options**.

    - Select **Use regular expressions**.

    - In the **Find what** box, type the affix that you want to delete. If the affix is a prefix, put a carat (^) before the prefix. For example, type `^un` to delete a prefix ‘un-’. If the affix is a suffix, put a dollar sign after the suffix. For example, type `es$` to delete a suffix ‘-es’.

    - Do not type anything in the **Replace with** box. (Essentially, you are replacing something with nothing.)

    - Click **OK**.

    - Click **Preview**, review the pending changes, and then click **Apply**.

    - Repeat step 2 for each affix.

3.  Use **Bulk Replace** to add inflectional affixes to the forms in the **Citation Form** field, as follows:

    (If the form you entered in the **Lexeme** field was the bare stem, do this step. However, if the form you entered in the **Lexeme** field was the correct citation form, do step 2 instead of this step.)

    - In **Bulk Edit Entries**, click the **Bulk Replace** tab.

    - [Use](../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) the **Configure Columns** dialog box to display the **Citation Form** and **Grammatical Info** fields.

    - In the **Grammatical Info** column, [filter for](../Basic_Tasks/Filtering_data/Using_Filter_for.md) the grammatical category (such as *Verb*) that you want to add an affix to.

    - In the **Target Field** box, select **Citation Form**.

    - [Select the rows](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/select_rows.md) you want to change.

    - Click **Setup**.

    - Click **More** to display the **Search Options**.

    - Select **Use regular expressions**.

    - In the **Find what:** box, either type `^` (carat), if you want to add a prefix, or type `$` (dollar sign), if you want to add a suffix. (The regular expression `^` indicates the beginning of a word, and the regular expression `$` indicates the end of a word.)

    - In the **Replace with:** box, type the affix that you want to add. (Essentially, you are replacing nothing with something.)

    - Click **OK**.

    - Click **Preview**, review the pending changes, and then click **Apply**.

    - Repeat step 3 for each affix.

> [!TIP]
>
> - For additional information about the propose of this topic or when it may be of use to you, on the [Help](../User_Interface/Menus/Help/Help_overview.md) menu, point to **Resources** and then click **Introduction to Lexicography**.

## Related topics
[Bulk Edit overview](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md)

[Lexicography Tasks overview](Dictionary_and_Lexicon_overview.md)

[Using regular expressions assistance](../Basic_Tasks/Filtering_data/Using_regular_expressions_assistance.md)
