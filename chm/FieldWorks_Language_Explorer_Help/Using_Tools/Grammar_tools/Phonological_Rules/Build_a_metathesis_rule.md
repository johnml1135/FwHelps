---
title: "Build a metathesis rule"
source_title: "Build a metathesis rule"
breadcrumb:
  - "Using Tools"
  - "Grammar tools"
  - "Phonological Rules"
  - "Build a metathesis rule"
source: "Using_Tools/Grammar_tools/Phonological_Rules/Build_a_metathesis_rule.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Grammar_tools/Phonological_Rules/Build_a_metathesis_rule.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Phonological Rules"
  - "Metathesis Rules"
related:
  - "Configure Columns -> ../../../Basic_Tasks/Configure_Columns/Configure_Columns_overview.md"
  - "Natural Class overview -> ../Natural_Classes/Natural_classes_overview.md"
  - "Parsing words (Hermit Crab parser) -> ../../../User_Interface/Menus/Parser/Parsing_words_(HermitCrab).md"
  - "Phonological Features overview -> ../Phonological_Features/Phonological_Features_overview.md"
  - "Phonological Rules overview -> Phonological_Rules_overview.md"
  - "Phonemes overview -> ../Phonemes/Phonemes_overview.md"
  - "Specify the order of phonological rules -> Specify_order_number.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:e0de08d5e0077e68"
---

# Build a metathesis rule

*Using Tools › Grammar tools › Phonological Rules*

In a metathesis rule, you insert items in the **Input** row of the table. In the **Switch these items** columns, Language Explorer transposes and displays the phonemes in the **Result** row.

After you [insert](Insert_a_phonological_rule.md) or [duplicate](Duplicate_a_phonological_rule.md) a rule do any of these steps as needed:

1.  In the **Rule Formula** [field](../../../User_Interface/Field_Descriptions/Grammar/Phonologocial_Rules_fields/Rule_Formula_field_(Ph_Rules).md), click the position in the **Input** row where you want the insertion point, and then insert any of the following:

    - **Phoneme**

      The **Choose Phoneme** dialog box appears.

    - **Natural Class**

      The **Choose Natural Class** dialog box appears.

    - **Phonological Feature(s)**

      The **Choose Phonological Features** dialog box appears.

    - **Word boundary (#)**

      **\#** (a word boundary marker) is inserted.

    - **Morpheme boundary (+)**

      **+** (a word boundary marker) is inserted.

2.  If a dialog box appears and shows the item you want, select the item, and then click **OK**. If the item you need is *not* shown in a dialog box, click the link near the bottom of that dialog box so you can insert the new item. Then return to this field and continue.

    - In the **Choose Phonological Features** dialog box, if the phonological feature you need is shown, click it. Then, in the **Value** column select **+**, **-**, or a custom value you inserted. Repeat this for each one you need to insert. Click **OK**.

    The selected item is inserted in the rule and the cursor remains adjacent to the inserted item.

3.  Repeat the above steps for each column, as necessary.

    - A message, such as "The item in this cell must be removed before a new item can be inserted." might appear if you insert something incorrectly. To replace content in a cell you may be able to select it, and then press **Delete**. Then, click the desired insert option.

## Related topics
[Configure Columns](../../../Basic_Tasks/Configure_Columns/Configure_Columns_overview.md)

[Natural Class overview](../Natural_Classes/Natural_classes_overview.md)

[Parsing words (Hermit Crab parser)](../../../User_Interface/Menus/Parser/Parsing_words_(HermitCrab).md)

[Phonological Features overview](../Phonological_Features/Phonological_Features_overview.md)

[Phonological Rules overview](Phonological_Rules_overview.md)

[Phonemes overview](../Phonemes/Phonemes_overview.md)

[Specify the order of phonological rules](Specify_order_number.md)
