---
title: "Dictionary Letter Headings overview"
source_title: "Dictionary Letter Headings overview"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Dictionary"
  - "Dictionary Letter Headings overview"
source: "Using_Tools/Lexicon_tools/Dictionary/Dictionary_Letter_Headings_overview.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Dictionary/Dictionary_Letter_Headings_overview.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Dictionary:Dictionary overview:Dictionary Letter Headings overview"
  - "Collation"
  - "sorting:Dictionary Letter Headings overview"
  - "Letter headings"
  - "Dictionary"
  - "Sort:Sort Key (writing system)"
  - "Sort"
related:
  - "Collation in FieldWorks -> ../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Collation_in_FieldWorks.md"
  - "Dictionary overview -> Dictionary_overview.md"
  - "Navigating in Dictionary -> Navigating_in_Dictionary.md"
  - "Reversal Indexes overview -> ../Reversal_Indexes/reversal_indexes_overview.md"
  - "Sorting tab -> ../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_Sorting_tab.md"
fw_help_version: "9.3"
type: "index"
content_hash: "sha256:b80e9ff9edf9fad1"
---

# Dictionary Letter Headings overview

*Using Tools › Lexicon tools › Dictionary*

*Letter headings* separate the lexical entries into groups based on the first letter or letters of the data in the column that has the [primary sort](../../../Basic_Tasks/Sorting_data/Sort_lexical_entries.md) in **Lexicon Edit**. Typically, this should be the **Headword**, **Citation Form** or **Lexeme Form** column. If the primary sort is on any other column, you will *not* see any letter headings.

You can set the primary sort on the **Headword**, **Citation Form** or **Lexeme Form** column, and then set a [secondary sort](../../../Basic_Tasks/Sorting_data/Sort_data.md) on another column such as the morph type or homograph number column. You can sort on a column that has data even if it is not [configured](../../../User_Interface/Menus/Tools/Configure_Dictionary/Configure_Dictionary.md) for display in the **Dictionary** view, or contains data in a different writing system.

- Letter headings are controlled primarily by the sort rules in **Sorting** tab. You get additional control over them with [Custom ICU Sort rules](../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Sort_Custom_ICU.md).

Here are two examples:

- Remove a parenthesis "(" that appears as a letter heading in **Dictionary** with a [rule](../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Collation_in_FieldWorks.md) like this:

`&[last tertiary ignorable] = '('`

- Remove the ligature Œ (U+0152/U+0153) as a letter heading and correct the sort order with a custom ICU [rule](../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Collation_in_FieldWorks.md) like this:

`&oe<<œ<<<OE<<<Œ`

- The **Dictionary-LetterHeading** [style](../../../User_Interface/Menus/Format/Styles/Styles_overview.md) defines how they look in **Dictionary** and in **Reversal Indexes**.

- If the writing system you used for headwords does not include all the information needed to sort the words correctly, you can [add](../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/Add_a_new_writing_system.md) another vernacular writing system and fill it in with a sort key for either the **Lexeme Form** or **Citation Form** fields. You will probably need to [get more help](../../../Overview/Technical_support.md).

Be aware that if you put sort keys in a custom field and sort on that custom field, there will not be any letter headings.

## Related topics
[Collation in FieldWorks](../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Collation_in_FieldWorks.md)

[Dictionary overview](Dictionary_overview.md)

[Navigating in Dictionary](Navigating_in_Dictionary.md)

[Reversal Indexes overview](../Reversal_Indexes/reversal_indexes_overview.md)

[Sorting tab](../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_Sorting_tab.md)
