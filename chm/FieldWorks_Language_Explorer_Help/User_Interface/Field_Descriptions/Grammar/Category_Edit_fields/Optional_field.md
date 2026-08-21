---
title: "Optional field (Category Edit)"
source_title: "Optional field (Category Edit)"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Grammar"
  - "Category Edit fields"
  - "Optional field"
source: "User_Interface/Field_Descriptions/Grammar/Category_Edit_fields/Optional_field.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Grammar/Category_Edit_fields/Optional_field.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Optional:Optional field"
  - "Slot"
related:
  - "Change the optionality of a slot -> ../../../../Using_Tools/Grammar_tools/Category_Edit/Change_the_optionality_of_a_slot.md"
  - "Category Edit fields overview -> category_edit_fields_overview.md"
  - "Grammar Sketch -> ../../../../Using_Tools/Grammar_tools/Grammar_Sketch/Grammar_Sketch_overview.md"
fw_help_version: "9.3"
page_heading: "Optional field"
type: "topic"
content_hash: "sha256:f0d6d2e70b26148b"
---

# Optional field (Category Edit)

*User Interface › Field Descriptions › Grammar › Category Edit fields*

**Full name:** **Optional**

**Location:** There is an **Optional** field below *each* **Slot Name** field in the **Category (or Part of Speech)** pane of **Category Edit** ([Grammar](../../../../Using_Tools/Grammar_tools/grammar_overview.md)).

**Description:**

This check box allows you to specify whether the affix slot is *optional* or *obligatory*.

- When selected (![](../../../../assets/images/CheckedBox.PNG)), the slot is *optional* and the slot name appears in parenthesis.

- When cleared (![](../../../../assets/images/User_Interface/Menus/Tools/UncheckedBox.PNG)), the slot is *obligatory* and the slot name appears *without* parenthesis.

Your choice affects computational [parsing](../../../Menus/Parser/Parsing_words_overview.md): If an obligatory slot exists for a grammatical category, then any lexical entries that use this grammatical category require inflection for a successful parse. If no inflection is specified for a given entry, then the [Parse result field](../../Texts_%26_Words/Parse_result_field.md) will show **Failure**. You can use [Try a Word](../../../Menus/Parser/Try_a_word.md) to see the trace that will indicate the reason for the failed parse.

[Affix Template table](Table_field.md) and [Grammatical Info Details fields](../../Lexicon/Lexicon_Edit_fields/Grammatical_Info_Details_fields/grammatical_info_details_field.md) and corresponding columns in browse panes and views indicate your choice ([example](../../../../Using_Tools/Grammar_tools/Category_Edit/affix_template_table_example.md)).

**Tasks:**

- [Change the optionality of a slot](../../../../Using_Tools/Grammar_tools/Category_Edit/Change_the_optionality_of_a_slot.md)

- [Edit an affix template](../../../../Using_Tools/Grammar_tools/Category_Edit/Edit_an_Affix_Template_Table.md)

- **See also:** [Category Edit overview](../../../../Using_Tools/Grammar_tools/Category_Edit/Category_Edit_overview.md)

**Field type:** Check box

**Writing systems:** Not Applicable

**Grammar Sketch:** Under **Inflection**

**Note:**

- For templates that are marked as [requires more derivation](requires_more_derivation_field.md), you need at least one obligatory slot.

- For more information, point to **Resources** on the [Help](../../../Menus/Help/Help_overview.md) menu, and then click **Introduction to Parsing**.

## Related topics
[Change the optionality of a slot](../../../../Using_Tools/Grammar_tools/Category_Edit/Change_the_optionality_of_a_slot.md)

[Category Edit fields overview](category_edit_fields_overview.md)

[Grammar Sketch](../../../../Using_Tools/Grammar_tools/Grammar_Sketch/Grammar_Sketch_overview.md)
