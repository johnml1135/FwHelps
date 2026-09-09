---
title: "Using regular expressions assistance"
source_title: "Using regular expressions assistance"
breadcrumb:
  - "Basic Tasks"
  - "Filtering data"
  - "Using regular expressions assistance"
source: "Basic_Tasks/Filtering_data/Using_regular_expressions_assistance.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Basic_Tasks/Filtering_data/Using_regular_expressions_assistance.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Regular Expression"
  - "Regular Expression:Using regular expressions assistance"
  - "Use or Using:Using regular expressions assistance"
related:
  - "Basic Tasks overview -> ../Basic_Tasks_overview.md"
  - "Filtering data overview -> filtering_data_overview.md"
  - "Examples of combinations of regular expressions -> examples_of_combinations_of_regular_expressions.md"
  - "Examples of regular expressions -> Examples_of_Regular_Expressions.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:32660f619e679cf6"
---

# Using regular expressions assistance

*Basic Tasks › Filtering data*

*Regular expression assistance* buttons (![](../../assets/images/Basic_Tasks/Filtering_data/RegExpAssistButton.png)) appear in dialog boxes when you [specify concordance criteria](../../Using_Tools/Texts_&_Words_tools/Concordance/Manually_specify_concordance_criteria.md), [bulk replace](../../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_replace.md) or [filter data](filter_data.md). These buttons can help you choose regular expression [metacharacters](Regular_Expression_Metacharacters_table.md) and [operators](Regular_Expression_Operators_table.md) as you construct a [regular expression](About_Regular_Expressions.md).

To make the buttons available, select (![](../../assets/images/CheckedBox.PNG)) **Use Regular Expressions** or select (![](../../assets/images/SelectedRadioButton.png)) **Match for regular expressions**. Then, click a button to see a list of metacharacters and operators.

Use combinations of the following steps to put metacharacters or operators in an **Enter text to search for** box, **Find What** box, or **Replace with** box:

- Type text characters, and *then* select a regular expression component from the list.

- Select a regular expression component from the list, and *then* type text characters.

### Example

- To find any one of the set of vowels `a`, `e`, `i`, `o` or `u`, you will want `[aeiou]` in the search string.

  To do this you can either type `aeiou`, select those characters, and then select **\[ \] Any one character in the set**, *or* you can select **\[ \] Any one character in the set**, and then type `aeiou` between the brackets.

## Related topics
[Basic Tasks overview](../Basic_Tasks_overview.md)

[Filtering data overview](filtering_data_overview.md)

[Examples of combinations of regular expressions](examples_of_combinations_of_regular_expressions.md)

[Examples of regular expressions](Examples_of_Regular_Expressions.md)
