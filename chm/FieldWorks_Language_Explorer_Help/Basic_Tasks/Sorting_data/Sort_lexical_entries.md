---
title: "Sort lexical entries"
source_title: "Sort lexical entries"
breadcrumb:
  - "Basic Tasks"
  - "Sorting data"
  - "Sort lexical entries"
source: "Basic_Tasks/Sorting_data/Sort_lexical_entries.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Basic_Tasks/Sorting_data/Sort_lexical_entries.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Sort:Sort lexical entries"
related:
  - "Sorting data overview -> Sorting_data_overview.md"
  - "Lexicon overview -> ../../Using_Tools/Lexicon_tools/Lexicon_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:c9596a5491cc03c9"
---

# Sort lexical entries

*Basic Tasks › Sorting data*

1.  In the **Navigation** **Pane**, click **Lexicon**, and then select **Lexicon Edit**, **Browse**, or **Bulk Edit Entries**.

2.  Do the steps in [Sort data](Sort_data.md).

> [!TIP]
>
> - Sort orders you set in **Lexicon Edit**, **Browse** or **Bulk Edit Entries** affect *all three* views in the *same* open [window](../../User_Interface/Menus/Window/Window_overview.md). Sorts do not affect other windows that are open to the language project.
>
> - For columns that have rows with multiple items, the sort will add rows to the display so that there is only one item per row.
>
>   For example, if the entry '`able`' was assigned three semantic domains, when you sort on the **Semantic Domains** column, '`able`' would appear in three rows in **Browse** and as three entries in the **Entries** pane. ([Bulk Edit Entries overview](../../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_Edit_Entries_overview.md) describes how the **Target Field** selection determines if the main pane is an **Entrie**s or **Senses** view.
>
>   These rows or entries are *not* editable independently, so edits you make are reflected in each row or displayed occurrence of that entry. When you sort on a different column, those rows collapse back down and the new sort is displayed.
>
> - Any rows that have an empty cell in the sorted column are collected at the top or bottom, reflecting the ascending or descending order.
>
> - If you sort a **Grammatical Info** column, for example, the **Lexeme** column may appear in a random order. In this case, you may find a secondary sort (`Shift+Click`) useful. In addition, for larger lexicons, you may want to [filter the data](../Filtering_data/filter_lexical_entries.md) in one or more columns while the data is sorted to help display the desired content in more manageable amounts.
>
>   - When you sort and filter on *different* columns, you need to be careful as you interpret the counts on the [status bar](../../User_Interface/Toolbars/status_bar.md). For example, suppose you sort by gloss, but filter on lexeme form. The sort order still causes there to be a row for each sense, but all those for a given entry will have the same lexeme form, so either all will match or none will match. However, the count will still be the number of *senses* whose associated entry has a matching lexeme form.

> [!IMPORTANT]
>
> - Currently, you *cannot* sort or filter reversal index entries in **Reversal Indexes**.

## Related topics
[Sorting data overview](Sorting_data_overview.md)

[Lexicon overview](../../Using_Tools/Lexicon_tools/Lexicon_overview.md)
