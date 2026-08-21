---
title: "Direction field (Ph Rules)"
source_title: "Direction field (Ph Rules)"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Grammar"
  - "Phonological Rules fields"
  - "Direction field (Ph Rules)"
source: "User_Interface/Field_Descriptions/Grammar/Phonologocial_Rules_fields/Direction_field_(Ph_Rules).htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Grammar/Phonologocial_Rules_fields/Direction_field_%28Ph_Rules%29.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Phonological Features"
  - "Phonological Rules:Phonological Rules fields overview"
  - "Rules"
  - "phonological"
related:
  - "Grammar Sketch -> ../../../../Using_Tools/Grammar_tools/Grammar_Sketch/Grammar_Sketch_overview.md"
  - "Phonological Rules fields overview -> Phonological_Rules_fields_overview.md"
fw_help_version: "9.3"
page_heading: "Direction field - Phonological Rules"
type: "topic"
content_hash: "sha256:361507b12f8dd0d0"
---

# Direction field (Ph Rules)

*User Interface › Field Descriptions › Grammar › Phonological Rules fields*

**Full name:** **Direction**

**Locations:** This **Direction** field is near the top of the **Phonological Rule** pane or **Metathesis Rule** pane in **Phonological Rules** ([Grammar](../../../../Using_Tools/Grammar_tools/grammar_overview.md)).

**Description:**

This field stores how the current rule is to be applied, either simultaneously or iteratively in a particular direction (**left-to-right iterative**, **right-to-left iterative**).

- When a rule is applied iteratively from left-to-right, the input is scanned from left to right, looking for a match of the environment. As soon as the rule environment is matched, the rule is applied. The scanning then continues from that point on rightward in the (now modified) input.

- When the rule is applied right-to-left iteratively, it is similar except that the scan occurs from the right toward the left.

- When the rule is applied simultaneously, every matching environment in the input has the rule applied to it at the same time.

The phonological rule-based [parser](../../../Menus/Parser/Parsing_words_(HermitCrab).md) uses phonological rules.

**Tasks:**

- [Insert a phonological or metathesis rule](../../../../Using_Tools/Grammar_tools/Phonological_Rules/Insert_a_phonological_rule.md)

  - [Build a phonological rule](../../../../Using_Tools/Grammar_tools/Phonological_Rules/Build_a_phonological_rule.md)

  - [Build a metathesis rule](../../../../Using_Tools/Grammar_tools/Phonological_Rules/Build_a_metathesis_rule.md)

- [Delete a phonological rule](../../../../Using_Tools/Grammar_tools/Phonological_Rules/Delete_a_phonological_rule.md)

- **See also:** [Phonological Rules overview](../../../../Using_Tools/Grammar_tools/Phonological_Rules/Phonological_Rules_overview.md)

**Field type:** [List-reference](../../Field_Types/Single_line_text_field.md) — from a list you cannot control or edit.

**Writing systems:** English

**Grammar Sketch:** Under **Phonological Rules**

**Example:**

Suppose a language has a rule of final vowel deletion. Given a form like *kikua*, you get different results depending on whether the direction is left-to-right or right-to-left.

- For left-to-right rule application, the final *a* matches, so it is deleted. At this point the left-to-right scan is at the end of word (having already seen the *u* and passed over it). Nothing else matches so the result is *kiku*.

- For right-to-left rule application, the scan begins at the end of the word. The final *a* matches and is deleted. Now the scan continues leftward and the (now) final *u* matches so it, too, is deleted. The scan then continues leftward, but nothing else matches the environment. The result in this case is *kik*.

**Tip:** For more information, point to **Resources** on the [Help](../../../Menus/Help/Help_overview.md) menu, and then click **Introduction to Parsing**.

## Related topics
[Grammar Sketch](../../../../Using_Tools/Grammar_tools/Grammar_Sketch/Grammar_Sketch_overview.md)

[Phonological Rules fields overview](Phonological_Rules_fields_overview.md)
