---
title: "Date field"
source_title: "Date field"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Field Types"
  - "Date field"
source: "User_Interface/Field_Descriptions/Field_Types/date_field.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Field_Types/date_field.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Date field"
  - "Date Created/Modified"
  - "Dates"
  - "filtering"
related:
  - "Field Types overview -> field_types_overview.md"
  - "Lexicon Edit fields overview -> ../Lexicon/Lexicon_Edit_fields/Lexicon_Edit_fields_overview.md"
  - "Move a field -> ../../../Basic_Tasks/Moving_fields/Move_a_field.md"
  - "Notebook fields overview -> ../Notebook/Notebook_fields_overview.md"
  - "Restrict to items with date dialog box -> ../../../Basic_Tasks/Filtering_data/Using_Restrict_dialog_box.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:057fdf1ea7fb8a44"
---

# Date field

*User Interface › Field Descriptions › Field Types*

*Date* fields, such as **Date Created** and **Date of Event**, store a date.

- You can use [Configure Columns](../../../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) dialog box to display date fields in columns, and then [sort](../../../Basic_Tasks/Sorting_data/Sorting_data_overview.md) or [filter](../../../Basic_Tasks/Filtering_data/Using_Restrict_dialog_box.md) based on dates.

- Dates appear on the [status bar](../../Toolbars/status_bar.md).

- You can [configure the dictionary](../../Menus/Tools/Configure_Dictionary/Configure_Dictionary.md), [classified dictionary](../../Menus/Tools/Configure_Classified_Dictionary/Configuring_a_Classified_Dictionary_view.md) or [reversal indexes](../../Menus/Tools/Configure_Reversal_Index/Configuring_a_reversal_index_view.md) to include **Date Created** and **Date Modified**.

- You can [configure document](../../Menus/Tools/Configure_Document/Configuring_a_Document_view.md) to include **Date Created**, **Date Modified** and **Date of Event**.

> [!IMPORTANT]
>
> - In **Lexicon**, the **Date Modified** timestamp is updated for *all* associated lexical entries when you add or remove members of [lexical](../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Insert_a_lexical_relation.md) or [cross reference](../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Insert_a_CR_lexical_relation.md) relations.
>
>   For example, in a [part/whole](../../../Using_Tools/Lists_tools/About_Lexical_Relations.md) lexical relationship, if you had a *whole* `house` with *parts* `wall, floor`, and `ceiling,` the timestamp for each of these entries updates when you add another *part*, such as `door`. This happens even though you cannot see any visual change to those entries.
>
>   Be aware of this when you [sort](../../../Basic_Tasks/Sorting_data/Sort_data.md) or use the [Restrict](../../../Basic_Tasks/Filtering_data/Using_Restrict_dialog_box.md) feature in a **Date Modified** column.

## Related topics
[Field Types overview](field_types_overview.md)

[Lexicon Edit fields overview](../Lexicon/Lexicon_Edit_fields/Lexicon_Edit_fields_overview.md)

[Move a field](../../../Basic_Tasks/Moving_fields/Move_a_field.md)

[Notebook fields overview](../Notebook/Notebook_fields_overview.md)

[Restrict to items with date dialog box](../../../Basic_Tasks/Filtering_data/Using_Restrict_dialog_box.md)
