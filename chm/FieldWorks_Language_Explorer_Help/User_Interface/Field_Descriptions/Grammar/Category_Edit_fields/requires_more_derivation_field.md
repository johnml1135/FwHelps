---
title: "Requires more derivation field"
source_title: "Requires more derivation field"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Grammar"
  - "Category Edit fields"
  - "Requires more derivation field"
source: "User_Interface/Field_Descriptions/Grammar/Category_Edit_fields/requires_more_derivation_field.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Grammar/Category_Edit_fields/requires_more_derivation_field.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Requires more derivation field"
related:
  - "Category Edit fields overview -> category_edit_fields_overview.md"
  - "Grammar Sketch -> ../../../../Using_Tools/Grammar_tools/Grammar_Sketch/Grammar_Sketch_overview.md"
  - "Optional field check box -> Optional_field.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:dad45cce1faa98a1"
---

# Requires more derivation field

*User Interface › Field Descriptions › Grammar › Category Edit fields*

**Full name:** **Requires more derivation**

**Location:** There is a **Requires more derivation** field below *each* **Table** field in the **Category (or Part of Speech)** pane of **Category Edit** ([Grammar](../../../../Using_Tools/Grammar_tools/grammar_overview.md)).

**Description:**

This check box affects [parsing](../../../Menus/Parser/Parsing_words_overview.md).

- A check mark (![](../../../../assets/images/CheckedBox.PNG)) means that you *must* have more derivation outside the inflection described by this template. In this case, this table must have at least one *required* (obligatory) slot. (Said another way, this template is a non-final template. When it applies, it does not yet make a well-formed word. It requires a derivational affix to change its category and then the resulting category may have an inflectional template to complete it.)

- No check mark (![](../../../../assets/images/UncheckedBox.PNG)) means that you do *not* need more derivation outside the template and, in fact, you *cannot have* derivation outside the inflection described by this template.\

**Tasks:**

- [Change the optionality of a slot](../../../../Using_Tools/Grammar_tools/Category_Edit/Change_the_optionality_of_a_slot.md)

- [Delete an affix template](../../../../Using_Tools/Grammar_tools/Category_Edit/Delete_an_Affix_Template.md)

- [Edit an affix template](../../../../Using_Tools/Grammar_tools/Category_Edit/Edit_an_Affix_Template_Table.md)

- [Insert an affix template](../../../../Using_Tools/Grammar_tools/Category_Edit/Insert_an_affix_template.md)

- **See also:** [Category Edit overview](../../../../Using_Tools/Grammar_tools/Category_Edit/Category_Edit_overview.md)

**Field type:** Check box

**Writing systems:** Not Applicable

**Grammar Sketch:** The choice you make here is indicated under **Inflection**.

> [!IMPORTANT]
>
> - For more information, point to **Resources** on the [Help](../../../Menus/Help/Help_overview.md) menu, and then click **Introduction to Parsing**. From section **2.1.4 D****erivation Outside of Inflection**:
>
>   - Create the "inside" inflectional template and mark it specially as a template that requires additional derivation (![](../../../../assets/images/CheckedBox.PNG)).
>
>     This template *must have* at least one slot that is required. If all of the slots are marked as being optional, the parser will arbitrarily treat them as if they are all required. The reason is that when all slots are optional, the implication is that the template is not needed. It also results in invalid instructions for the parser.
>
>   - Then, create the "outside" inflectional template.

## Related topics
[Category Edit fields overview](category_edit_fields_overview.md)

[Grammar Sketch](../../../../Using_Tools/Grammar_tools/Grammar_Sketch/Grammar_Sketch_overview.md)

[Optional field check box](Optional_field.md)
