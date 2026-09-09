---
title: "Regular expression operators table"
source_title: "Regular expression operators table"
breadcrumb:
  - "Basic Tasks"
  - "Filtering data"
  - "Regular Expression Operators table"
source: "Basic_Tasks/Filtering_data/Regular_Expression_Operators_table.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Basic_Tasks/Filtering_data/Regular_Expression_Operators_table.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Regular Expression:Regular expression operators table"
  - "Expression"
  - "Regular"
  - "Capture"
related:
  - "Bulk Edit Entries -> ../../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_Edit_Entries_overview.md"
  - "Find and Replace overview -> ../Find_and_Replace/Find_and_Replace_overview.md"
  - "Using regular expressions assistance -> Using_regular_expressions_assistance.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:01bfe18d0252b069"
---

# Regular expression operators table

*Basic Tasks › Filtering data*

Refer first to [Examples of regular expressions](Examples_of_Regular_Expressions.md) or [Examples of combinations of regular expressions](examples_of_combinations_of_regular_expressions.md). There is also a [Regular expression metacharacters table](Regular_Expression_Metacharacters_table.md).

|  |  |
|----|----|
| Character | Description |
| \| | Alternation. `A|B` matches either A or B |
| \* | Match 0 or more times. Match as many times as possible |
| \+ | Match 1 or more times. Match as many times as possible |
| ? | Match zero or one times. Prefer one |
| {n} | Match exactly n times |
| {n,} | Match at least n times. Match as many times as possible |
| {n,m} | Match between n and m times. Match as many times as possible, but not more than m |
| \*? | Match 0 or more times. Match as few times as possible |
| +? | Match 1 or more times. Match as few times as possible |
| ?? | Match zero or one times. Prefer zero |
| {n}? | Match exactly n times |
| {n,}? | Match at least n times, but no more than required for an overall pattern match |
| {n,m}? | Match between n and m times. Match as few times as possible, but not less than n |
| \*+ | Match 0 or more times. Match as many times as possible when first encountered, do not retry with fewer even if overall match fails (Possessive Match) |
| ++ | Match 1 or more times. Possessive match |
| ?+ | Match zero or one times. Possessive match |
| {n}+ | Match exactly n times |
| {n,}+ | Match at least n times. Possessive Match |
| {n,m}+ | Match between n and m times. Possessive Match |
| ( ... ) | [Capturing parentheses](../Find_and_Replace/Find_and_Replace_using_regular_expressions.md). Range of input that matched the parenthesized subexpression is available after the match |
| (?: ... ) | Non-capturing parentheses. Groups the included pattern, but does not provide capturing of matching text. Somewhat more efficient than capturing parentheses |
| (?\> ... ) | Atomic-match parentheses. First match of the parenthesized subexpression is the only one tried; if it does not lead to an overall pattern match, back up the search for a match to a position before the "`(?>`" |
| (?= ... ) | Look-ahead assertion. True if the parenthesized pattern matches at the current input position, but does not advance the input position |
| (?! ... ) | Negative look-ahead assertion. True if the parenthesized pattern does not match at the current input position. Does not advance the input position |
| (?\<= ... ) | Look-behind assertion. True if the parenthesized pattern matches text preceding the current input position, with the last character of the match being the input character just before the current position. Does not alter the input position. The length of possible strings matched by the look-behind pattern must not be unbounded (no \* or + operators.) |
| (?\<! ... ) | Negative Look-behind assertion. True if the parenthesized pattern does not match text preceding the current input position, with the last character of the match being the input character just before the current position. Does not alter the input position. The length of possible strings matched by the look-behind pattern must not be unbounded (no \* or + operators.) |
| (?i-i: ... ) | Evaluate the *parenthesized* expression with case insensitivity (the default) enabled `?i:` or disabled `?-i:`. |
| (?i-i) | Changes the case insensitivity setting: enabled `?i` or disabled `?-i`. |

## Related topics
[Bulk Edit Entries](../../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_Edit_Entries_overview.md)

[Find and Replace overview](../Find_and_Replace/Find_and_Replace_overview.md)

[Using regular expressions assistance](Using_regular_expressions_assistance.md)
