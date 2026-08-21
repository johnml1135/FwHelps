---
title: "Build an Affix Process Rule"
source_title: "Build an Affix Process Rule"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Lexicon Edit"
  - "Build an Affix Process Rule"
source: "Using_Tools/Lexicon_tools/Lexicon_Edit/Build_Affix_Process_Rule.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Lexicon_Edit/Build_Affix_Process_Rule.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Affix Process Rule (Lexicon Edit)"
  - "Affix Process Rule (Lexicon Edit):Build an Affix Process Rule"
  - "Build an Affix Process Rule"
  - "Phonological Rules"
  - "Process Rule"
  - "Rule"
related:
  - "Edit a natural class -> ../../Grammar_tools/Natural_Classes/Edit_a_natural_class.md"
  - "Lexicon Edit overview -> lexicon_edit_overview.md"
  - "Phonological Features field (Phonemes) -> ../../../User_Interface/Field_Descriptions/Grammar/Phonemes_fields/Phonological_Features_field.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:8b2d641f3d35aab1"
---

# Build an Affix Process Rule

*Using Tools › Lexicon tools › Lexicon Edit*

You can [Insert Affix Process](Insert_Affix_Process_Rule.md) or [Convert an existing form or allomorph into an Affix Process](Convert_existing_form_or_allomorph.md).

Then, there can be an **Affix Process Rule** [field](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Affix_Process_Rule_field.md) for the lexeme form, and separate **Affix Process Rule** [fields](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Affix_Process_Rule_fldAF.md) for one or more allomorphs. These fields store a table and **Result** line. The table represents the structure of the stem that this process applies to. Insert content into the **Input** row to specify part of the structure of the stem. The **X** stands for "whatever is left over". Cells are automatically indexed with numbers in the **Index** row. The **Result** line specifies which parts of the **Input** are to occur in the **Result** and in what order. The index numbers in the **Result** line correspond to items in the **Input**. For more information, on the **Help** menu point to **Resources** and then click **Introduction to Parsing**.

1.  In the **Affix Process Rule** field, click the cell in the **Input** row where you want to insert an item (phoneme, natural class and so on), and then click one of these insert options:

    - **Phoneme**

      The **Choose Phoneme** dialog box appears.

    - **Natural Class**

      The **Choose Natural Class** dialog box appears.

    - **Phonological Feature(s)**

      The **Choose Phonological Features** dialog box appears.

    - **Morpheme boundary (+)**

      A **+** (word boundary marker) is inserted.

    - **Column**

      A column is added to the table to the left or right of the insertion point, depending on where it is.

2.  If a dialog box appears and shows the item you want, select the item, and then click **OK**. If the item you need is *not* shown in a dialog box, click the link near the bottom of that dialog box so you can insert the new item. Then return to this field and continue.

    The selected item is inserted in the rule and the cursor remains adjacent to the inserted item.

    - In the **Choose Phonological Features** dialog box, if the feature you need is shown, click it. Then, in the **Value** column select **+**, **-** or a custom value you inserted. Repeat this step for each feature you want to insert. Click **OK**.

3.  Repeat the above steps for each cell in the input row, as needed.

4.  If necessary, for a phonological feature in the **Input** row, right-click it and then click one of these commands that appear as links:

    - **Phonological Features** opens the **Choose Phonological Features** dialog box. Change the values for one or more phonological features. Click **OK**.

    - **Show in Natural Classes list** shows natural class in **Natural Classes** ([Grammar](../../Grammar_tools/grammar_overview.md)). Change the phonological feature in the **Phonological Features** [field](../../../User_Interface/Field_Descriptions/Grammar/Natural_Classes_fields/Phonological_Features_fld(NC).md) as needed. Click ![PIC](../../../assets/images/User_Interface/Toolbars/GreenBackArrow.GIF) (**Back**) to return.

5.  Click the **Result** line to position the insertion point, and then click any of the following insert options:

    - **Phoneme**

      The **Choose Phoneme** dialog box appears. Click a phoneme. Click **OK**.

    - **1**, **2**, **3** or **4** (index numbers)

      The index number is added to the **Result**. You can select and delete index numbers from the **Result**, but there must always be at least one index number or the rule will be problematic.

6.  Optionally, do these steps:

    - Click the **Result** line after the desired index number, and then click **Set Phonological Features**.

In the dialog box, choose the value for one or more phonological features. Click **OK**.

- Click the **Result** line after the desired index number, and then click **Set Natural Class**.

In the dialog box, choose the natural class. Click **OK**.

7.  If necessary, for phonemes in the **Input** row *or* in the **Result**, right-click the phoneme, and then click **Show in Phonemes list**. The window changes to show the phoneme in **Phonemes** ([Grammar](../../Grammar_tools/grammar_overview.md)). [Edit the phoneme](../../Grammar_tools/Phonemes/Edit_a_phoneme.md) as needed. Click ![PIC](../../../assets/images/User_Interface/Toolbars/GreenBackArrow.GIF) (**Back**) to return.

8.  Repeat any of the steps above as necessary.

> [!NOTE]
>
> - Which insert options are available depends on the position of the insertion point. Examples:
>
>   - **Word Boundary** is only available when the insertion point is at the left- or right-most cells in the **Input** row.
>
>   - **Column** is only available when there are two or more cells with content and the insertion point is in one of those cells. (The column is inserted as close to the insertion point as possible, and the insertion point moves to the new column.)
>
> - Use the arrow keys to move between the cells in the table, and the `Tab` key to move from the table to the **Result** area.
>
> - For more information, point to **Resources** on the [Help](../../../User_Interface/Menus/Help/Help_overview.md) menu, and then click **Introduction to Parsing**. Affix process rules are discussed under **Item and Process**.

## Related topics
[Edit a natural class](../../Grammar_tools/Natural_Classes/Edit_a_natural_class.md)

[Lexicon Edit overview](lexicon_edit_overview.md)

[Phonological Features field (Phonemes)](../../../User_Interface/Field_Descriptions/Grammar/Phonemes_fields/Phonological_Features_field.md)
