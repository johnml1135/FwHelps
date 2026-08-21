---
title: "Active field Ad Hoc Rules"
source_title: "Active field Ad Hoc Rules"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Grammar"
  - "Ad hoc Rules fields"
  - "Active field Ad Hoc Rules"
source: "User_Interface/Field_Descriptions/Grammar/Ad_hoc_Rules_fields/Active_field_Ad_Hoc_Rules.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Grammar/Ad_hoc_Rules_fields/Active_field_Ad_Hoc_Rules.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Active"
  - "Active:Active field Ad Hoc Rules"
related:
  - "Ad hoc Rules fields overview -> Ad_hoc_Rules_fields_overview.md"
  - "Ad hoc Co-occurrence Prevention Rules overview -> ../../../../Using_Tools/Grammar_tools/Ad_hoc_Rules/Ad_hoc_Rules_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:0d504a84c1f17c97"
---

# Active field Ad Hoc Rules

*User Interface › Field Descriptions › Grammar › Ad hoc Rules fields*

**Full name:** **Active**

**Location:** There is an **Active** field associated with *each* rule in **Ad hoc Rules** ([Grammar](../../../../Using_Tools/Grammar_tools/grammar_overview.md)).

**Description:**

You can select or clear this check box to see what effect the rule has on [parsing](../../../Menus/Parser/Parsing_words_overview.md).

- Selected (![](../../../../assets/images/CheckedBox.PNG)) means:

  - The rule is available for use by either parser the next time you run one of them.

  - The rule is included in the grammar sketch.

- Cleared (![](../../../../assets/images/UncheckedBox.PNG)) means:

  - The rule is *not* available to either parser, and is therefore ignored the next time you run one of them.

    As seen in [Word Analyses](../../../../Using_Tools/Texts_&_Words_tools/Word_Analyses/Word_Analyses_overview.md), clearing this check box has the same effect as if you had deleted the rule; but the rule is not actually deleted.

    The font changes to a lighter color, which indicates the rule is not active. However, you can continue to edit an inactive rule.

  - The rule is not included in the grammar sketch.\

**Field type:** Check box

**Writing systems:** Not Applicable

## Related topics
[Ad hoc Rules fields overview](Ad_hoc_Rules_fields_overview.md)

[Ad hoc Co-occurrence Prevention Rules overview](../../../../Using_Tools/Grammar_tools/Ad_hoc_Rules/Ad_hoc_Rules_overview.md)
