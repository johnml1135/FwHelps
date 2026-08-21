---
title: "Reference field"
source_title: "Reference field"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Lexicon"
  - "Lexicon Edit fields"
  - "Sense level fields"
  - "Reference field"
source: "User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Reference_field.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Reference_field.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Reference"
related:
  - "Lexicon Edit overview -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md"
  - "Sense-level fields overview -> Sense_level_fields_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:2803b35281f9cdbb"
---

# Reference field

*User Interface › Field Descriptions › Lexicon › Lexicon Edit fields › Sense level fields*

**Full name:** **Reference**

**Abbreviation:** **rf**

**Location:**

In the **Entry** pane (**Lexicon Edit**).

[Example](example_field.md), [Translation](Translation_field.md), [Type](Type_field.md), **Reference** and [Publish Example In](Publish_In_(Example).md) fields are added when you [insert an example](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Insert_an_example_in_a_sense.md) in a sense or subsense.

**Description:**

The [Find example sentence](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Find_example_sentence.md) feature puts content from the [Abbreviation](../../../Texts_%26_Words/Abbreviation_field_Info.md) field or [Title](../../../Texts_%26_Words/Title_field_Info.md) field into this field. The paragraph and line number (**1.2**, **2.3**, and so on) that matches the selected instance is appended to the abbreviation or title. This content appears as a hyperlink you can click to display the referenced text in **Interlinear Texts**.

You can also type or paste references that pertain to the associated example, translation and translation type.

**Tasks:**

- [Insert an example in a sense](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Insert_an_example_in_a_sense.md)

- You can [configure the dictionary](../../../../Menus/Tools/Configure_Dictionary/Configure_Dictionary.md) to show content from this field and associated fields when you configure [Examples](../../../../Menus/Tools/Configure_Dictionary/Examples.md). Similar content may appear when you configure [Extended Note](../../../../Menus/Tools/Configure_Dictionary/Extended_Note.md).

**Field type:** This text field does not display writing system identifiers or allow paragraphs.

**Writing systems:**

- If you insert an example *manually*, this field defaults to the top (default) [analysis](../../../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md) writing system. However, you can embed other analysis and vernacular [writing systems](../../../../Menus/Format/select_a_writing_system.md), and apply [styles](../../../../Menus/Format/apply_a_style_to_text.md).

- If you use the *Find example sentence* feature, the abbreviation of the text title or the title is used. If you entered an abbreviation in the default vernacular writing system, it is used. Otherwise, it searches for one in another writing system. If no abbreviation is found, then a title is used. Titles are truncated to 8 characters, but abbreviation are not truncated.

## Related topics
[Lexicon Edit overview](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md)

[Sense-level fields overview](Sense_level_fields_overview.md)
