---
title: "Sort Custom ICU rules"
source_title: "Sort Custom ICU rules"
breadcrumb:
  - "Advanced Tasks"
  - "Writing Systems"
  - "Modifying a Writing System"
  - "Sort - Custom ICU rules"
source: "Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Sort_Custom_ICU.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Sort_Custom_ICU.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Collation"
  - "Custom:Sort Method Custom ICU rules"
  - "Dictionary:Letter Headings"
  - "ICU:Sort Method Custom ICU rules"
  - "Sort Method Custom ICU rules"
  - "Sort:Sort - Custom ICU rules"
  - "Sorting:Sorting"
  - "sorting:Sort - Custom ICU rules"
related:
  - "Pathway multigraphs -> ../../../User_Interface/Menus/File/Pathway_Configuration_Tool/Pathway_multigraphs.md"
  - "Sorting tab, Writing System Properties dialog box -> Writing_System_Properties_Sorting_tab.md"
  - "Using the Character Map -> ../../../User_Interface/Menus/Insert/Using_Character_Map.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:901b5fc6e793264e"
---

# Sort Custom ICU rules

*Advanced Tasks › Writing Systems › Modifying a Writing System*

Sort orders ([collations](Collation_in_FieldWorks.md)) vary from culture to culture. You can add custom ICU rules which will override the *Unicode Standard* default sort order.

- You will need a way to enter the characters for your rules. Make sure [Keyman](Writing_System_Properties_Keyboard_tab.md) is running if you use it. You can use [shortcut keys](../../../User_Interface/Shortcuts/Shortcut_keys_to_edit_text.md).

[Use](Writing_System_Properties_Sorting_tab.md) the **Sorting** tab to do these steps:

1.  Click the **Sort** down arrow (![](../../../assets/images/Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/SortDownArrow.png)) and then click **Custom ICU rules**.

2.  Do *any* of these steps in the pane under the **Sort** control:

    - If that pane is *empty*, click the pane to put the insertion point there.

    - If that pane has existing rules:

      - Edit or delete rules.

      - Move the insertion point at the end of the rule *after which* you want to add a rule. Then, press `Enter` to add a new line.

    - Enter one or more new collation [rules](Collation_in_FieldWorks.md).

Begin each new rule with "`&`" and use "**\<**" between the letters in the rule. No other separators or symbols are permitted between them.

3.  [Test](Writing_System_Properties_Sorting_tab.md) your rules.

> [!TIP]
>
> - You can [specify a secondary sort order](../../../Using_Tools/Lists_tools/Change_the_secondary_sort_order.md) based on [morpheme types](../../../Using_Tools/Lists_tools/About_Morpheme_Types.md).

## Related topics
[Pathway multigraphs](../../../User_Interface/Menus/File/Pathway_Configuration_Tool/Pathway_multigraphs.md)

[Sorting tab, Writing System Properties dialog box](Writing_System_Properties_Sorting_tab.md)

[Using the Character Map](../../../User_Interface/Menus/Insert/Using_Character_Map.md)

## Related links
<a href="https://home.unicode.org/" target="_blank" title="https://home.unicode.org/">https://www.unicode.org</a>
