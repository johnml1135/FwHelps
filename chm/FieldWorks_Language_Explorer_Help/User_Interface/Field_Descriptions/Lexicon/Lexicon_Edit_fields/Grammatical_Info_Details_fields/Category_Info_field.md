---
title: "Category Info field"
source_title: "Category Info field"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Lexicon"
  - "Lexicon Edit fields"
  - "Grammatical Info Details fields"
  - "Category Info. field"
source: "User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Grammatical_Info_Details_fields/Category_Info_field.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Grammatical_Info_Details_fields/Category_Info_field.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Category"
  - "Category:Category Info field"
  - "Category:Category field (Compound Rules)"
  - "Clitics"
related:
  - "Delete Grammatical Info -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Delete_grammatical_info.md"
  - "Grammatical Info Details fields overview -> Gram_Info_Detls_fields_ovw.md"
  - "Lexicon Edit fields overview -> ../Lexicon_Edit_fields_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:9d00ba9f468d916f"
---

# Category Info field

*User Interface › Field Descriptions › Lexicon › Lexicon Edit fields › Grammatical Info Details fields*

**Full name:** **Category Info.**

**Abbreviation:** **ps**

**Locations:**

In the **Entry** pane (**Lexicon Edit**).

This field is at the [Grammatical Info Details level](Gram_Info_Detls_fields_ovw.md).

(A **Category Info** field appears for *each* **Grammatical Info** field ([sense level](../Sense_level_fields/Sense_level_fields_overview.md)) that contains *unique* content. They are displayed in the same order as the senses.)

**Description:**

As you specify the grammatical information for a sense or subsense (here "sense"), a **Category Info** field appears in the **Grammatical Info Details** area, if its content is unique. It typically contains a prose description of the associated **Grammatical Info** field.

For a *clitic*, this field shows only the category (or part of speech) and the [Attaches to Category](attaches_to_categories_field.md) field contains additional information. If the **Grammatical Info** field is set to **\<Not sure\>**, this field will contain “**Clitic of unknown category**.”

**Important:**

- If you [edit](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Using_Edit_Gram_Infodlg.md) content here (**Category Info** field), *all* senses in the current entry that use it are updated.

- If you [change](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/change_the_grammatical_info.md) content in the **Grammatical Info** field in a sense:

  - *only* that sense is changed, and

  - *another set* of **Grammatical Info** fields appear *if* the change makes it *unique*.

  - The set of fields is *automatically* [deleted](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Delete_grammatical_info.md) if you [delete](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/delete_a_sense_or_subsense.md) the only sense that used it or the change was such that the grammatical information is no longer used in the entry, *and* that grammatical information is not used by any interlinear text.

- Fields appear in sets. For example, you could see **Category Info**, [Inflection Class](Inflection_Class_field_Lex_Edit.md), [Inflection Features](from_inflection_features_field.md) and [Exception "Features"](exception_features_field.md) fields for a stem, but a different set for an affix.

- [Grammatical Info field](../Sense_level_fields/Grammatical_Info_field.md) has examples of the some corresponding fields.

- For more information, on the [Help](../../../../Menus/Help/Help_overview.md) menu point to **Resources**, and then click **Introduction to Parsing**.

**Tasks:**

- [Using Edit Grammatical Info dialog box](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Using_Edit_Gram_Infodlg.md)

- You can [configure the dictionary](../../../../Menus/Tools/Configure_Dictionary/Configure_Dictionary.md) to include the abbreviation of the selected category when you configure **Category Info** under [Grammatical Info](../../../../Menus/Tools/Configure_Dictionary/Grammatical_Info.md).

- **See also:** [Lexicon Edit overview](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md)

**Field type:** [List reference field](../../../Field_Types/List_reference_field.md)

**Writing systems:** Best [analysis](../../../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md)

## Related topics
[Delete Grammatical Info](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Delete_grammatical_info.md)

[Grammatical Info Details fields overview](Gram_Info_Detls_fields_ovw.md)

[Lexicon Edit fields overview](../Lexicon_Edit_fields_overview.md)
