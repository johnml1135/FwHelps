---
title: "About Reversal Index Categories"
source_title: "About Reversal Index Categories"
breadcrumb:
  - "Using Tools"
  - "Lists tools"
  - "About Reversal Index Categories"
source: "Using_Tools/Lists_tools/about_reversal_index_categories.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lists_tools/about_reversal_index_categories.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "About:Reversal Index Categories"
  - "Reversal Indexes:Reversal Index Categories"
  - "Category"
  - "reversal entry"
  - "List:List subitem"
  - "Reversal Index Categories"
  - "Lists:About Reversal Index Categories"
related:
  - "Category field -> ../../User_Interface/Field_Descriptions/Lexicon/Reversal_Indexes_fields/category_field.md"
  - "Lists overview -> Lists_overview.md"
  - "Reversal Indexes overview -> ../Lexicon_tools/Reversal_Indexes/reversal_indexes_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:39ac5023046e10d9"
---

# About Reversal Index Categories

*Using Tools › Lists tools*

In [Lists](List_item_usage_table.md), **Reversal Index Categories** stores one or more lists of grammatical categories that are used *only* in **Category** fields in **Reversal Indexes**. You need to populate a list of categories for *each* reversal index.

**Reversal Index Categories** is different from other lists in these ways:

- The **Categories (or Parts of Speech)** pane has an [Information bar](../../User_Interface/Toolbars/information_bar_overview.md) with a menu button (![](../../assets/images/Information_bar_Menu_button.PNG)). You use it to select an analysis writing system. This controls which reversal index category list to display. Each list corresponds to a reversal index.

  This menu button is like the one in **Reversal Indexes**.

- The center pane is a *browse-style* pane in which you can [filter](../../Basic_Tasks/Filtering_data/filter_data.md), [sort](../../Basic_Tasks/Sorting_data/Sort_data.md), and access the [Configure Columns](../../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) dialog box.

- In the **Category (or Part of Speech)** pane, each [Subcategories](../../User_Interface/Field_Descriptions/Lists/Reversal_Index_Categories_fields/Subcategories_field_Reversal_Index_Categories.md) field serves as a header field that enables a menu button ![](../../assets/images/Using_Tools/Lists_tools/Menu_Button_pic.GIF) and an **Insert Subcategory** link.

- The menu button used with the **Name** fields (for categories or subcategories) allows you to [move a category](Move_a_category.md), [merge categories](Merge_categories.md), or [promote a category](Promote_or_Demote_a_list_item.md). If you add categories and subcategories from the catalog in an order that loses the hierarchy of the catalog, you should promote and move them to restore that order.

> [!IMPORTANT]
>
> - Suppose a language project had Portuguese, French and English analysis writing systems and it had two reversal indexes; Portuguese and French.
>
> - - The categories list for the Portuguese reversal index would use Portuguese and English.
>
>   - The categories list for the French reversal index would use French and English.
>
> In each case, the [Add from catalog](../Lexicon_tools/Lexicon_Edit/Using_Add_from_Catalog_dialog_box.md) populates the list in English (unless localized). You will need to *manually* enter the name and abbreviation in the other analysis writing system, if it is necessary or desired.
>
> - Currently, the center pane does *not* show subcategories. Instead, you see them in the right pane under the **Subcategories** fields. Also, the writing system of the selected reversal index is not displayed in the [Information bar](../../User_Interface/Toolbars/information_bar_overview.md), so you need to use the menu button to determine which list is displayed.

## Related topics
[Category field](../../User_Interface/Field_Descriptions/Lexicon/Reversal_Indexes_fields/category_field.md)

[Lists overview](Lists_overview.md)

[Reversal Indexes overview](../Lexicon_tools/Reversal_Indexes/reversal_indexes_overview.md)
