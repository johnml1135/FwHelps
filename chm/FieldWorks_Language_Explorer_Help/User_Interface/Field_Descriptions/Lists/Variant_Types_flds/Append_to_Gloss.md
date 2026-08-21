---
title: "Append to Gloss"
source_title: "Append to Gloss"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Lists"
  - "Variant Types fields"
  - "Append to Gloss"
source: "User_Interface/Field_Descriptions/Lists/Variant_Types_flds/Append_to_Gloss.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Lists/Variant_Types_flds/Append_to_Gloss.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Variant Forms:Append to Gloss"
  - "Append to Gloss"
  - "Append to Gloss:Append to Gloss field"
related:
  - "About 
 Variant Types -> ../../../../Using_Tools/Lists_tools/About_Variants.md"
  - "Convert 
 variants utility -> ../../../Menus/Tools/Convert_variants_utility.md"
  - "Lists 
 overview -> ../../../../Using_Tools/Lists_tools/Lists_overview.md"
  - "Prepend to Gloss -> Prepend_to_Gloss.md"
  - "Variant Types 
 fields overview -> variant_types_flds_overview.md"
fw_help_version: "9.3"
page_heading: "Append to Gloss field"
type: "topic"
content_hash: "sha256:38ddd0f4ea14e99e"
---

# Append to Gloss

*User Interface › Field Descriptions › Lists › Variant Types fields*

**Full name:** **Append to Gloss**

**Location:** **Variant Type** pane of the **Variant Types** ([Lists](../../../../Using_Tools/Lists_tools/List_item_usage_table.md))

**Description:** This field appears only if the variant type is for an [irregularly inflected form](Irregularly_Inflected_Form.md). You can [convert variant types](../../../Menus/Tools/Convert_variants_utility.md). What you type in this field comes after (is appended to) the gloss ([example](Append_to_Gloss_example.md)).

**Tasks:**

- In this field, type `.pl` or **.PL** for plurals, `.pst` or `.PST`, for past tense, and so on.

Then the parser will parse these irregular variant forms, using the gloss of the singular form *plus* what is in this field.

Typing the period (**.**) is optional: If you do not type a period FLEx will add it automatically; if you type another character, such as a plus sign (**+**), the period is not added.

**Field type:** [Single-line text field](../../Field_Types/Single_line_text_field.md)– you *cannot* embed characters in other writing systems or embed styles

**Writing systems:** One or more [analysis](../../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md)

**Tip:**

- <a href="https://www.eva.mpg.de/lingua/resources/glossing-rules.php" target="_blank" title="https://www.eva.mpg.de/lingua/resources/glossing-rules.php">https://www.eva.mpg.de/lingua/resources/glossing-rules.php</a> has examples.

- On the [Help](../../../Menus/Help/Help_overview.md) menu, point to **Resources**, and then click **Introduction to Parsing** for additional information about irregularly inflected forms.

## Related topics
[About Variant Types](../../../../Using_Tools/Lists_tools/About_Variants.md)

[Convert variants utility](../../../Menus/Tools/Convert_variants_utility.md)

[Lists overview](../../../../Using_Tools/Lists_tools/Lists_overview.md)

[Prepend to Gloss](Prepend_to_Gloss.md)

[Variant Types fields overview](variant_types_flds_overview.md)
