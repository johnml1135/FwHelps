---
title: "Generate lexeme forms from citation forms"
source_title: "Generate lexeme forms from citation forms"
breadcrumb:
  - "Lexicography Tasks"
  - "Generate lexeme forms from citation forms"
source: "Lexicography_Tasks/Generate_citation_form.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Lexicography_Tasks/Generate_citation_form.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Bulk Edit Entries:Generate Lexeme Forms from Citation Forms"
  - "Lexicography tasks"
related:
  - "Bulk Edit overview -> ../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md"
  - "Lexicography Tasks overview -> Dictionary_and_Lexicon_overview.md"
  - "Using regular expressions assistance -> ../Basic_Tasks/Filtering_data/Using_regular_expressions_assistance.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:19da4902efb783d9"
---

# Generate lexeme forms from citation forms

*Lexicography Tasks*

In this topic, **Citation Form** field content is copied into **Lexeme Form** field and then inflectional affixes are removed, leaving only the stem.

For additional information about the propose of this topic or when it may be of use to you, on the [Help](../User_Interface/Menus/Help/Help_overview.md) menu, point to **Resources** and then click **Introduction to Lexicography**.

1.  In the **Navigation Pane**, click **Lexicon**, and then select **Bulk Edit Entries**.

2.  Click the **Bulk Copy** tab.

3.  [Use](../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) the **Configure Columns** dialog box to hide/show/move columns (fields) and select writing systems, if permitted. Show the **Citation** **Form** and **Lexeme Form** fields.

4.  Do the following:

    - [Filter](../Basic_Tasks/Filtering_data/Using_Filter_for.md) and [sort](../Basic_Tasks/Sorting_data/Sort_lexical_entries.md) the citation forms that you want to copy into the **Lexeme** **Form** field.

    - Examine the result of your filtering and sorting. Clear the check box at the end of each row you do not want to copy, or use the check box ![](../assets/images/Lexicography_Tasks/check_box_button.gif) button as needed.

5.  In the **Source** **Field** box, select **Citation** **Form**.

6.  In the **Target Field** box, select **Lexeme Form**.

7.  In the **If the Target field is not empty** area, you will most likely want **Do nothing**, the default selection. However, you may need to select **Overwrite** if the **Lexeme Form** fields contain incorrect content.

8.  Click **Preview** and review the pending changes.

9.  In the left column, [select the rows](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/select_rows.md) you want to change.

10. Click **Apply**.

    The **Lexeme Form** fields contain a copy of the **Citation Form** fields for the selected entries. (Next, you will remove any inflectional affixes.)

11. Click the **Bulk Replace** tab, and then in the **Target Field** box, select **Lexeme Form**.

12. [Filter for](../Basic_Tasks/Filtering_data/Using_Filter_for.md) and [sort](../Basic_Tasks/Sorting_data/Sort_lexical_entries.md) the lexeme forms from which you will remove one or more affix. Consider changing groups of only *closely related* entries to minimize subsequent editing to achieve properly spelled lexeme forms.

    For example, in English, entries for which the lexeme form ends in the letter “e” but which is removed when a suffix is attached (*wasting* from *waste*, *housing* from *house*, and so on) should be done separately from entries for which the final consonant is doubled when an affix is added (*rot* from *rotting*, *stop* from *stopping*, and so on.)

13. Click **Setup**.

    The **Bulk Replace Setup** dialog box appears.

14. In the **Search Options** area, select **Use Regular Expressions**.

    For help with regular expressions, see [About regular expressions](../Basic_Tasks/Filtering_data/About_Regular_Expressions.md).

15. In the **Find what** box, enter one of the following:

    - To delete a prefix, such as ‘un-‘ enter `^` followed by the prefix, such as `^un`. (The caret ^ is the regular expression for *beginning of line*.)

    - To delete a suffix, such as “-ed” enter the suffix followed by `$`, such as `ed$`. (The dollar sign `$` is the regular expression for *end of line*.)

16. If there is nothing to replace after the affix is removed, leave the **Replace with** box empty. However, if removing an affix requires the replacement of characters, enter those characters in the **Replace with** box.

    For example, in English, you would need to replace the letter “`e`” when removing the “`ing`” affix from the entries like *wasting* and *housing*.

17. Click **OK**.

18. It may be that you need to limit each “replace” operation to more specific sets of entries. So, [select the rows](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/select_rows.md) you want to change.

19. Click **Preview**, review the pending changes, and then click **Apply**.

The entries with a check mark appear without their prefixes or suffixes.

20. Examine your lexeme forms and determine if your next step is to continue removing affixes or doing other editing to make sure each lexeme form is properly spelled.

> [!TIP]
>
> - In **Bulk Edit Entries**, the **Lexeme Form** field is editable, so you can make spelling edits on a per entry basis *without* going to **Lexicon Edit**.
>
> - For additional information about the purpose of this topic or when it may be of use to you, on the [Help](../User_Interface/Menus/Help/Help_overview.md) menu, point to **Resources** and then click **Introduction to Lexicography**.

## Related topics
[Bulk Edit overview](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md)

[Lexicography Tasks overview](Dictionary_and_Lexicon_overview.md)

[Using regular expressions assistance](../Basic_Tasks/Filtering_data/Using_regular_expressions_assistance.md)
