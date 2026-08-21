---
title: "Shoebox Toolbox style sort order"
source_title: "Shoebox Toolbox style sort order"
breadcrumb:
  - "Advanced Tasks"
  - "Writing Systems"
  - "Modifying a Writing System"
source: "Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Shoebox_Toobox_style_sort_order.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Shoebox_Toobox_style_sort_order.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Collation"
  - "Shoebox Toolbox style sort order"
  - "Sort:Shoebox-style sort order"
  - "Sorting:Sorting"
  - "sorting:Shoebox-style sort order"
related:
  - "Sort - Custom Simple rules -> Sort_Custom_Simple_rules.md"
  - "Writing System Properties, Sorting tab -> Writing_System_Properties_Sorting_tab.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:0ae86b54025d8c0d"
---

# Shoebox Toolbox style sort order

*Advanced Tasks › Writing Systems*

In the **Sorting** tab, you can choose **Custom Simple (Shoebox style) rules**. [Sort - Custom Simple rules](Sort_Custom_Simple_rules.md) has steps. These simple rules do *not* control alphabetized headers in [XHTML export](../../../User_Interface/Menus/File/Export/Export_overview.md) files. [Sort - Custom ICU Rules](Sort_Custom_ICU.md) do.

###  Here is additional information

For many languages, simple rules can be written with up to three levels of minor variation (typically base, accented, and caps). A sequence of characters is considered a single collation element.

### Primary distinctions

A primary distinction is the strongest difference between collation elements. Dictionaries are usually divided into different sections by the primary distinctions which are usually base characters.

Primary distinctions are listed on separate lines with the collation element(s) on the first line sorting before those on following lines.

Given the following sort rule:

a

A

b

B

e

E

t

T

The following strings are ordered.

bat

bet

Bat

BAT

Bet

BET

### Secondary distinctions

Secondary distinctions allow collation elements to be considered similar (by giving them the same primary distinction) yet still retain differences when there are no primary distinctions to further distinguish between characters. A secondary difference is ignored when there is a primary difference anywhere in the strings. The difference between an accented character and it's base character is usually considered a secondary difference.

Secondary distinctions are listed within a line (usually separated by space).

Given the following sort rule:

e é

m

r R

s

u

The following strings are ordered.

resume

résumé

Resume

Résumé

resumes

résumés

Resumes

Résumés

### Tertiary distinctions

Tertiary distinctions allow one more level of distinction in the same manner as secondary distinctions. Tertiary distinctions are usually between the case of a character, such as the difference between characters é and É.

Tertiary distinctions are surrounded by parenthesis within the secondary distinctions.

Given the following sort rule:

(e E) (é É)

m

(r R)

s

u

The following strings are ordered.

resume

Resume

résumé

Résumé

resumes

Resumes

résumés

Résumés

Character escaping

Characters may be escaped by using \uXXXX (where XXXX is the hexadecimal value of the unicode code point):

(a A) (\u00e0 \u00c0)

(b B)

...

...

(n N)

(ng Ng NG)

...

## Related topics
[Sort - Custom Simple rules](Sort_Custom_Simple_rules.md)

[Writing System Properties, Sorting tab](Writing_System_Properties_Sorting_tab.md)
