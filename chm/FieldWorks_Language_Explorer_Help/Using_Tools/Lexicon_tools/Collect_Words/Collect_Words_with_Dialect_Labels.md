---
title: "Collect Words with Dialect Labels"
source_title: "Collect Words with Dialect Labels"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Collect Words"
  - "Collect Words with Dialect Labels"
source: "Using_Tools/Lexicon_tools/Collect_Words/Collect_Words_with_Dialect_Labels.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Collect_Words/Collect_Words_with_Dialect_Labels.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Collect Words:Collect Words with Dialect Labels"
  - "Dialect Labels:Collect Words with Dialect Labels"
related:
  - "Collect Words overview -> Collect_Words_overview.md"
  - "Dialect Labels (Sense) field -> ../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Dialect_Labels_(Sense).md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:538b05fa8d1442b2"
---

# Collect Words with Dialect Labels

*Using Tools › Lexicon tools › Collect Words*

In **Collect Words**, you rapidly [create lexical entries](Create_a_Lexical_entry_in_Collect_Words.md) that are categorized (classified) by [semantic domains](../../Lists_tools/List_item_usage_table.md).

When you [configure the columns](../../../Basic_Tasks/Configure_Columns/Configure_Columns_overview.md), you can display the **Dialect Labels (Sense)** column and choose a particular writing system for that column.

[Keyboards](../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_Keyboard_tab.md) will change automatically as the focus moves between columns with different writing systems (if set up correctly).

## Considerations

- [Dialect Labels](../../Lists_tools/About_Dialect_Labels.md) come from the **Dialect Labels** [list](../../Lists_tools/List_item_usage_table.md). In **Lists**, the [names](../../../User_Interface/Field_Descriptions/Lists/Dialect_Labels/Full_Name_field_(Dialect_Labels).md) and [abbreviations](../../../User_Interface/Field_Descriptions/Lists/Dialect_Labels/Abbreviation_field_(Dialect_Labels).md) of the dialect labels list items need to be entered in *all of the writing systems*, both vernacular and analysis, that are likely to be typed in the cells in **Collect Words**.

- You can type the name or abbreviation of the desired list item in any writing system for which there can be a match. The abbreviation of the list item that matches is displayed in the default *vernacular* writing system, not necessarily the one you typed.

To find matching list items, diacritics and case are ignored. This should facilitate a more rapid and easier user experience. However, currently punctuation is not ignored, so you may not want to use periods with your abbreviations.

The **Dialect Labels (Sense)** fields in **Lexicon Edit** also display the abbreviations in the default vernacular writing system.

## Related topics
[Collect Words overview](Collect_Words_overview.md)

[Dialect Labels (Sense) field](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Dialect_Labels_(Sense).md)
