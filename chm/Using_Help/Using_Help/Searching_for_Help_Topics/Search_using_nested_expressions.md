---
title: "Search using nested expressions"
source_title: "Search using nested expressions"
breadcrumb:
  - "Using Help"
  - "Search for Information"
  - "Search using nested expressions"
source: "Using_Help/Searching_for_Help_Topics/Search_using_nested_expressions.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Help/Searching_for_Help_Topics/Search_using_nested_expressions.htm"
source_hash: "sha256:048514303a3761831b4e423add4a5a71154f5a1142ffb4b103d190ebce3c2774"
related:
  - "Find \r\n information using an advanced search -> Find_information_using_an_advanced_search.md"
  - "Search using \r\n boolean operators -> Search_using_boolean_operators.md"
type: "topic"
content_hash: "sha256:58e432d872e2412c"
---

# Search using nested expressions

*Using Help › Search for Information*

*Nested expressions* allow you to create complex searches (queries). For example, `control AND ((active OR dde) NEAR window)` finds topics containing the word *control* along with the words *active* and *window* close together, or containing *control* along with the words *dde* and *window* close together.

The basic rules for searching Help topics using nested expressions are as follows:

- You can use parentheses to nest (that is, group) expressions within a query. The expressions within parentheses are evaluated before the rest of the query.

- If a query does not contain a nested expression, it is evaluated from left to right. For example: `control NOT active OR dde` finds topics containing the word *control* without the word *active*, or topics containing the word *dde*. However, `control NOT (active OR dde)` finds topics containing the word *control* without either of the words *active* or *dde*.

- You *cannot* nest expressions more than five levels deep.

## Related topics
[Find information using an advanced search](Find_information_using_an_advanced_search.md)

[Search using boolean operators](Search_using_boolean_operators.md)
