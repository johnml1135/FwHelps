---
title: "Variant Form field"
source_title: "Variant Form field"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Lexicon"
  - "Lexicon Edit fields"
  - "Variant level fields"
  - "Variant Form field"
source: "User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Variants_level_fields/Variant_Form_field.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Variants_level_fields/Variant_Form_field.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Variants"
  - "fields relate to"
related:
  - "Lexicon Edit overview -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md"
  - "Show data -> ../../../../../Basic_Tasks/Show_data/Show_in_from_Lexicon.md"
  - "Variants-level fields overview -> Variant_level_fields_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:10e00f6821944391"
---

# Variant Form field

*User Interface › Field Descriptions › Lexicon › Lexicon Edit fields › Variant level fields*

**Full name:** **Variant Form**

**Location:**

In the **Entry** pane (**Lexicon Edit**).

In an entry that *has* a variant, this field is at the [Variants level](Variant_level_fields_overview.md).

**Description:**

Each **Variant Form** field stores one variant form of the headword (lexeme form or citation form). Associated fields include [Variant Type](Variant_Type_field.md), [Show Minor Entry](Show_Minor_Entry_Var_level.md), and [Comment](Comment_field_Variants.md).

When you enter a variant form in this field, Language Explorer creates a variant entry. The headword of that variant entry is the variant form that you enter here. The [Variant Of](../Entry_level_fields/Variant_of_field.md) field in the variant entry references the headword of this entry.

**Tasks:**

- [Insert a variant form](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Insert_a_variant_form.md)

- Right-click the form or the field label, and then click any of the following:

  - **Show Entry in Lexicon**

  - **Show Form in Concordance**

  - **Delete Variant** deletes the variant entry shown in this field, and deletes the associated [fields](Variant_level_fields_overview.md) from the current entry.

  - **Delete Reference** deletes only the reference from the variant entry to the current entry, but does not delete the variant entry.

- You can [configure the dictionary](../../../../Menus/Tools/Configure_Dictionary/Configure_Dictionary.md) to include the variants when you configure [Variant Forms](../../../../Menus/Tools/Configure_Dictionary/Variant_Forms.md) or [Variant Forms (Inflectional-Variants)](../../../../Menus/Tools/Configure_Dictionary/Variant_Forms_(Inflectional_Variants).md).

**Field type:** [Single-line text field](../../../Field_Types/List_reference_field.md)

**Writing systems:** one or more [vernacular](../../../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md)

**Tip:**

In a *variant* entry, the **Variant of** field allows you to [Choose an entry or sense](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_Variant_of_entry.md) with the **Choose Lexical Entry or Sense** dialog box.

- If you choose an *entry*, that variant entry appears in a **Variant Form** field described above.

- If you choose a *sense*, that variant entry appears in a [Variant of Sense](../Sense_level_fields/Variant_of_Sense_field.md) field.

## Related topics
[Lexicon Edit overview](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md)

[Show data](../../../../../Basic_Tasks/Show_data/Show_in_from_Lexicon.md)

[Variants-level fields overview](Variant_level_fields_overview.md)
