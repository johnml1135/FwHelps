---
title: "Using Filter for"
source_title: "Using Filter for"
breadcrumb:
  - "Basic Tasks"
  - "Filtering data"
  - "Using Filter for"
source: "Basic_Tasks/Filtering_data/Using_Filter_for.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Basic_Tasks/Filtering_data/Using_Filter_for.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Filter:Using Filter for"
  - "Use or Using:Using Filter for"
related:
  - "Basic Tasks overview -> ../Basic_Tasks_overview.md"
  - "Filtering data overview -> filtering_data_overview.md"
  - "Examples of combinations of regular expressions -> examples_of_combinations_of_regular_expressions.md"
  - "Examples of regular expressions -> Examples_of_Regular_Expressions.md"
  - "Using regular expressions assistance -> Using_regular_expressions_assistance.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:43515b4624d7924c"
---

# Using Filter for

*Basic Tasks › Filtering data*

**Filter for...** allows you to create a custom filter when you [filter data](filter_data.md).

1.  Click the [down arrow](Filter_data_down_arrow_menu_pic.md) below the column heading in the desired column.

    A list that includes **Filter for** appears.

2.  Click **Filter for**.

    The **Filter for items containing** dialog box appears.

3.  Select **Anywhere**, **Whole Item**, **At End**, **At Start** or **Match for regular expressions**.

    If you select **Match for regular expressions**, the [regular expression assistance](Using_regular_expressions_assistance.md) button (![](../../assets/images/Basic_Tasks/Filtering_data/RegExpAssistButton.png) or ![](../../assets/images/Basic_Tasks/Filtering_data/Reg_Expres_Help_button.GIF)) at the right end of the text box becomes available. Click it to access regular expression [metacharacters](Regular_Expression_Metacharacters_table.md) and [operators](Regular_Expression_Operators_table.md) you can use as you construct a regular expression.

4.  If necessary, select **Match case** or **Match diacritics**, or both.

5.  In the **Enter text to search for** box, enter the characters or [regular expression](About_Regular_Expressions.md) as the filter criteria. (**See also:** [Special Characters](../../User_Interface/Menus/Insert/Using_Character_Map.md) on the **Insert** menu.)

6.  Click **OK**.

    Entries that match the filter criteria are displayed.

> [!IMPORTANT]
>
> - FieldWorks *automatically* adds one or two characters to those you enter in the **Filter for items containing** dialog box. After you close the dialog box, these appear in the column (below the heading) in which you set the filter. *Do not type these characters manually*.
>
>   Specifically:
>
>   **At start** adds a leading **\#**; **At end** adds a trailing **\#**; **Whole item** adds leading and trailing **\#**; **Match for regular expression** adds leading and trailing **/**. (**Anywhere** does *not* add any characters.)
>
> - The **Filter for** feature discussed here is similar but *not* the same as the **Find and Replace** feature found in [Bulk Edit Entries](../../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_Edit_Entries_overview.md).

## Related topics
[Basic Tasks overview](../Basic_Tasks_overview.md)

[Filtering data overview](filtering_data_overview.md)

[Examples of combinations of regular expressions](examples_of_combinations_of_regular_expressions.md)

[Examples of regular expressions](Examples_of_Regular_Expressions.md)

[Using regular expressions assistance](Using_regular_expressions_assistance.md)
