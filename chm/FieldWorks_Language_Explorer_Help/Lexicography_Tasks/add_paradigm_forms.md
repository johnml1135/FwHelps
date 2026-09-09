---
title: "Add paradigm (Inflected) forms"
source_title: "Add paradigm (Inflected) forms"
breadcrumb:
  - "Lexicography Tasks"
  - "Add paradigm (Inflected) forms"
source: "Lexicography_Tasks/add_paradigm_forms.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Lexicography_Tasks/add_paradigm_forms.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Bulk Edit Entries:Add paradigm (Inflected) forms"
  - "Lexicography tasks"
  - "Paradigm Forms"
related:
  - "Bulk Edit overview -> ../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md"
  - "Lexicography Tasks overview -> Dictionary_and_Lexicon_overview.md"
  - "Lexicon overview -> ../Using_Tools/Lexicon_tools/Lexicon_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:731ac43c89af0ea5"
---

# Add paradigm (Inflected) forms

*Lexicography Tasks*

Currently, Language Explorer has no fields in which you can to collect and organize paradigm (inflected) forms of words. However, you can add custom fields, copy lexeme forms into them, and then append inflectional affixes.

1.  In the **Navigation Pane**, click **Lexicon**, and then click **Bulk Edit Entries**.

2.  Click the **Bulk Copy** tab.

3.  [Add a custom field](../User_Interface/Menus/Tools/Custom_Fields/add_a_custom_field.md) for your p**aradigm** f**orms. Select t**he top (default) vernacular writing system, and give it meaningful name. Repeat as necessary.

4.  [Use](../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) the **Configure Columns** dialog box to hide/show/move columns (fields) and select writing systems, if permitted.

5.  [Filter](../Basic_Tasks/Filtering_data/Using_Filter_for.md) and [sort](../Basic_Tasks/Sorting_data/Sort_lexical_entries.md) the entries that you want to copy into the custom field.

6.  In the **Source** **Field** box, select **Lexeme Form**.

7.  In the **Target Field** box, select the appropriate custom field.

8.  In the **If the Target field is not empty** area, select the desired option.

    Initially, **Do nothing** is an appropriate selection as the custom form field is empty. When there is content in the field, you need to select **Append, separated by** and then enter a semicolon or other punctuation in the box.

9.  In the left column, [select the rows](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/select_rows.md) you want to change

10. Click **Preview**, and then review the pending changes.

The column shows any existing content, an arrow ![](../assets/images/Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Blue_Arrow.GIF), and then the new content.

11. Click **Apply**.

    A copy of the lexeme form appears in the custom field.

12. Click the **Bulk Replace** tab.

13. In the **Target Field** box, select the custom field.

14. Click **Setup**.

    The **Bulk Replace Setup** dialog box appears.

15. In the **Search Options** area, click **Use regular expressions**.

    For help with regular expressions, see [About regular expressions](../Basic_Tasks/Filtering_data/About_Regular_Expressions.md).

16. Do one of the following:

    - To add a prefix, in the **Find what** box, enter a caret (`^`, which means *Beginning of line*), and then enter the prefix in the **Replace with** box.

    - To add a suffix, in the **Find what** box, enter a dollar sign (`$`, which means *End of line*), then enter the suffix in the **Replace with** box.

17. Click **OK**.

18. Click **Preview**, review the pending changes, and then click **Apply**.

19. Repeat the steps above for each inflected form.

> [!TIP]
>
> - For additional information about the purpose of this topic or when it may be of use to you, on the [Help](../User_Interface/Menus/Help/Help_overview.md) menu, point to **Resources** and then click **Introduction to Lexicography**.

## Related topics
[Bulk Edit overview](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md)

[Lexicography Tasks overview](Dictionary_and_Lexicon_overview.md)

[Lexicon overview](../Using_Tools/Lexicon_tools/Lexicon_overview.md)
