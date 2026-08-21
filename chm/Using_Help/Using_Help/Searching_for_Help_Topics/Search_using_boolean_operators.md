---
title: "Search using boolean operators"
source_title: "Search using boolean operators"
breadcrumb:
  - "Using Help"
  - "Search for Information"
  - "Search using boolean operators"
source: "Using_Help/Searching_for_Help_Topics/Search_using_boolean_operators.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Help/Searching_for_Help_Topics/Search_using_boolean_operators.htm"
source_hash: "sha256:048514303a3761831b4e423add4a5a71154f5a1142ffb4b103d190ebce3c2774"
related:
  - "Find \r\n information using an advanced search -> Find_information_using_an_advanced_search.md"
  - "Search \r\n using nested expressions -> Search_using_nested_expressions.md"
type: "topic"
content_hash: "sha256:87b7e5a4c3b18401"
---

# Search using boolean operators

*Using Help › Search for Information*

The AND, OR, NOT, and NEAR boolean operators enable you to precisely define your search by creating a relationship between search terms. If no operator is specified, AND is used. For example, the query `spacing border printing` is equivalent to `spacing AND border AND printing`. The following table shows how you can use each of these operators:

<table data-x-use-null-cells="" style="x-cell-content-align: top; width: 100%;" width="100%">
<thead>
<tr class="hcp1" data-valign="top">
<th><p>Search for</p></th>
<th><p>Example</p></th>
<th><p>Results</p></th>
</tr>
</thead>
<tbody>
<tr class="hcp1" data-valign="top">
<td><p>Both terms in<br />
the same topic.</p></td>
<td><p>dib AND<br />
palette</p></td>
<td><p>Topics containing both the words <code>dib</code> and <code>palette</code>.</p></td>
</tr>
<tr class="hcp1" data-valign="top">
<td><p>Either term in<br />
a topic.</p></td>
<td><p>raster OR<br />
vector</p></td>
<td><p>Topics containing either the word <code>raster</code> or the word <code>vector</code> or both.</p></td>
</tr>
<tr class="hcp1" data-valign="top">
<td><p>The first term without the<br />
second term.</p></td>
<td><p>ole NOT<br />
dde</p></td>
<td><p>Topics containing the word <code>ole</code>, but not the word <code>dde</code>.</p></td>
</tr>
<tr class="hcp1" data-valign="top">
<td><p>Both terms in the<br />
same topic, close together.</p></td>
<td><p>user NEAR<br />
kernel</p></td>
<td><p>Topics containing the word <code>user</code> within eight words of the word <code>kernel</code>.</p></td>
</tr>
</tbody>
</table>

> [!NOTE]
>
> - The \|, &, and ! characters *do not* work as boolean operators (you *must* use OR, AND, and NOT).

## Related topics
[Find information using an advanced search](Find_information_using_an_advanced_search.md)

[Search using nested expressions](Search_using_nested_expressions.md)
