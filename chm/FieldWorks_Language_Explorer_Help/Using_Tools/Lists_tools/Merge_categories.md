---
title: "Merge categories"
source_title: "Merge categories"
breadcrumb:
  - "Using Tools"
  - "Lists tools"
  - "Merge categories"
source: "Using_Tools/Lists_tools/Merge_categories.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lists_tools/Merge_categories.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Merge"
  - "Merge:Categories"
  - "for Reversal Index"
  - "Category"
  - "reversal entry"
related:
  - "Lists fields overview -> ../../User_Interface/Field_Descriptions/Lists/Lists_fields_overview.md"
  - "Lists overview -> Lists_overview.md"
  - "Move a category -> Move_a_category.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:8f232b17d29ade89"
---

# Merge categories

*Using Tools › Lists tools*

In the [Reversal Index Categories](about_reversal_index_categories.md) list, you can merge a category into a different category or subcategory. You may want to consider whether *moving* the category may be better, because you *cannot use* **Undo** to reverse a merge. Also, see ![](../../assets/images/Important_Icon.gif) **Important** below.

1.  In the **Navigation** **Pane**, click **Lists**, and then click **Reversal Index Categories**.

2.  In the **Categories (or Parts of Speech)** pane, use the menu button on the [Information bar](../../User_Interface/Toolbars/information_bar_overview.md) to select the desired reversal index list.

3.  In the **Categories (or Parts of Speech)** pane, click the category you want to merge into another category or subcategory, *or* the category that *has the subcategory* you merge into another category or subcategory. (In the current version, *you cannot see the subcategories in this center pane*).

4.  In the **Category (or Part of Speech)** pane, click the **Name** field label for the category or subcategory you will merge.

    A menu button (![](../../assets/images/Using_Tools/Lists_tools/Menu_Button_pic.GIF)) appears.

5.  Click the menu button, and then select **Merge Category into**.

    The **Choose category to merge into** dialog box appears.

6.  Select the category or subcategory you want to merge the current category or subcategory into (the *receiving* category or subcategory), and then click **OK**.

    The two are merged into one. The merged category or subcategory is removed from the window. The **Category** field in each [reversal entry](../Lexicon_tools/Reversal_Indexes/reversal_indexes_overview.md) that used the merged category or subcategory automatically changes to use the *receiving* category or subcategory.

> [!IMPORTANT]
>
> - In the current version, if a receiving field has existing content using the same writing system [line](../../User_Interface/Field_Descriptions/Field_Types/Single_line_text_field.md), then the merged content is *not appended*, but is discarded. So, if a field contains information you want to keep, you should *first* copy and paste that information into the appropriate field.

## Related topics
[Lists fields overview](../../User_Interface/Field_Descriptions/Lists/Lists_fields_overview.md)

[Lists overview](Lists_overview.md)

[Move a category](Move_a_category.md)
