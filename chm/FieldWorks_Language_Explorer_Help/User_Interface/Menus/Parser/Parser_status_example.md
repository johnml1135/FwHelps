---
title: "Parser status example"
source_title: "Parser status example"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Parser"
  - "Parser status example"
source: "User_Interface/Menus/Parser/Parser_status_example.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Parser/Parser_status_example.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Parser:Parser status example"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:d39cf4d873cac4cb"
---

# Parser status example

*User Interface › Menus › Parser*

The parser will pause from working on lower-priority operations and give priority to any parse operation with a higher priority.

## Example

![](../../../assets/images/User_Interface/Menus/Parser/Status_Example.JPG)

This [status bar](../../Toolbars/status_bar.md) example shows the following queue (words not yet parsed): **631** low-priority words, **26** medium-priority words, and **0** high-priority words. It also displays the word currently being parsed.

This example resulted from this sequence of steps:

- **Parse All Words** (low priority) was clicked. Then, at the point when there were 631 words in the low-priority queue, **Parse Words in Text** (medium priority) was clicked.

  The parser paused from parsing the 631 low-priority words until all the medium-priority words were parsed.

  (*If* a high-priority operation, such as **Try a Word**, was commanded before the remaining 26 medium-priority words parsed, then the parser would pause from the medium-priority words until the high-priority operation was done.)

**Related Topics**

[Parser menu overview](Parser_menu_overview.md)

[Parsing words overview](Parsing_words_overview.md)

[Texts & Words overview](../../../Using_Tools/Texts_&_Words_tools/Texts_and_Words_overview.md)
