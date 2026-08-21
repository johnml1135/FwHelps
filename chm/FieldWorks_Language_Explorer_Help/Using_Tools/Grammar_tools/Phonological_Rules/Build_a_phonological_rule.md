---
title: "Build a phonological rule"
source_title: "Build a phonological rule"
breadcrumb:
  - "Using Tools"
  - "Grammar tools"
  - "Phonological Rules"
  - "Build a phonological rule"
source: "Using_Tools/Grammar_tools/Phonological_Rules/Build_a_phonological_rule.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Grammar_tools/Phonological_Rules/Build_a_phonological_rule.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Phonological Rules"
  - "Metathesis Rules"
  - "Alpha variables"
  - "phonological rules"
related:
  - "Configure Columns -> ../../../Basic_Tasks/Configure_Columns/Configure_Columns_overview.md"
  - "Parsing words (Hermit Crab parser) -> ../../../User_Interface/Menus/Parser/Parsing_words_(HermitCrab).md"
  - "Phonological Rules overview -> Phonological_Rules_overview.md"
  - "Specify the order of phonological rules -> Specify_order_number.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:f8168c9a32ba9650"
---

# Build a phonological rule

*Using Tools › Grammar tools › Phonological Rules*

After you [insert](Insert_a_phonological_rule.md) or [duplicate](Duplicate_a_phonological_rule.md) a rule, do any of these steps as needed:

1.  In the **Rule Formula** [field](../../../User_Interface/Field_Descriptions/Grammar/Phonologocial_Rules_fields/Rule_Formula_field_(Ph_Rules).md), click the position in the rule where you want the insertion point, and then click any of the following:

    - **Phoneme**

      The **Choose Phoneme** dialog box appears.

    - **Natural Class**

      The **Choose Natural Class** dialog box appears.

    - Click the ellipsis button **![](../../../assets/images/Ellipsis_button.PNG)** to choose an environment

      The **Choose Environment** dialog box appears.

    - **Phonological Feature(s)**

      The **Choose Phonological Features** dialog box appears.

    - **Word boundary (#)**

      **\#** (a word boundary marker) is inserted.

    - **Morpheme boundary (+)**

      **+** (a word boundary marker) is inserted.

2.  If a dialog box appears and shows the item you want, select the item, and then click **OK**. If the item you need is *not* shown in a dialog box, click the link near the bottom of that dialog box so you can insert the new item. Then return to this field and continue.

    - In the **Choose Phonological Features** dialog box, if the phonological feature you need is shown, click it. Then, in the **Value** column select a value **+**, **-**, or a custom value you inserted. Or, select **agree** or **disagree**. Repeat this for each one you need to insert. Click **OK**.

    The selected item is inserted in the rule and the cursor remains adjacent to the inserted item.

3.  Repeat the above steps for each position in the rule.

4.  To delete an item or column you inserted, select the item or space (if empty) in the **Input** row, and then press the `Backspace` or `Delete` key.

5.  Click an item in the rule, and then right-click that item to display a context-sensitive menu. Click one of these menu commands:

    - **Occurs exactly once**

    - **Occurs zero or more times**

    - **Occurs one or more times**

    - [Set occurrence (min. and max.)](Set_occurrence.md)

    - [Set Phonological Features](Set_phonological_features.md)

    - **Show in Natural Class**

    - **Show in Phonemes**

> [!NOTE]
>
> - Even though the **Rule Formula** field lines allows you to add more than one item to a line, add only one item per line. The Hermit Crab parser requires there to be one item per line. You might want to [get more help](../../../Overview/Technical_support.md).
>
> - In the **Rule Formula** field, when you choose a one or more phonological features, a natural class is automatically generated in [Natural Classes](../Natural_Classes/Natural_classes_overview.md).
>
> - [Phonological Features field](../../../User_Interface/Field_Descriptions/Grammar/Phonemes_fields/Phonological_Features_field.md) contains a description of phonological features, rules and phonemes.
>
> - For more information, point to **Resources** on the [Help](../../../User_Interface/Menus/Help/Help_overview.md) menu, and then click **Introduction to Parsing**.

## Related topics
[Configure Columns](../../../Basic_Tasks/Configure_Columns/Configure_Columns_overview.md) (in dialog boxes)

[Parsing words (Hermit Crab parser)](../../../User_Interface/Menus/Parser/Parsing_words_(HermitCrab).md)

[Phonological Rules overview](Phonological_Rules_overview.md)

[Specify the order of phonological rules](Specify_order_number.md)
