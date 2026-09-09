---
title: "Example Find and Replace using regular expressions"
source_title: "Example Find and Replace using regular expressions"
breadcrumb:
  - "Basic Tasks"
  - "Find and Replace"
  - "Example Find and Replace using regular expressions"
source: "Basic_Tasks/Find_and_Replace/Example_Find_and_Replace_using_regular_expressions.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Basic_Tasks/Find_and_Replace/Example_Find_and_Replace_using_regular_expressions.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Regular Expression:Example Find and Replace using regular expressions"
  - "Example:Example Find and Replace using regular expressions"
related:
  - "Find and Replace overview -> Find_and_Replace_overview.md"
  - "Examples of regular expressions -> ../Filtering_data/Examples_of_Regular_Expressions.md"
  - "Examples of combinations of regular expressions -> ../Filtering_data/examples_of_combinations_of_regular_expressions.md"
  - "Using regular expressions assistance -> ../Filtering_data/Using_regular_expressions_assistance.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:f4926856b5f862ab"
---

# Example Find and Replace using regular expressions

*Basic Tasks › Find and Replace*

Here is an example a FLEx user has used.

The need was to change "(être) gentil" in the gloss field to "gentil (être)" for all entries that started with (être) and those with (avoir).

The **Bulk Replace** tab in **Bulk Edit Entries** was used. The dialog box looked like this:

![](../../assets/images/Basic_Tasks/Find_and_Replace/Setupdlgbox.png)

- **Find what:** `^(\(être\))\s(.*)`

- **Replace with:** `$2 $1`

> [!TIP]
>
> - The search looks for (être) at the beginning of the field. The outer parentheses are to remember everything inside for the replacement. \\ is used to look for an actual ( since normally ( and ) are metacharacters. \s is a white space. .\* is everything else and since it is in parenthesis, it is remembered for replacement. In the replacement \$2 writes out what was in the second parentheses, and \$1 writes out what was in the first parentheses.
>
> - Then, you need to replace être with avoir for the second pass to handle (avoir).

## Related topics
[Find and Replace overview](Find_and_Replace_overview.md)

[Examples of regular expressions](../Filtering_data/Examples_of_Regular_Expressions.md)

[Examples of combinations of regular expressions](../Filtering_data/examples_of_combinations_of_regular_expressions.md)

[Using regular expressions assistance](../Filtering_data/Using_regular_expressions_assistance.md)
