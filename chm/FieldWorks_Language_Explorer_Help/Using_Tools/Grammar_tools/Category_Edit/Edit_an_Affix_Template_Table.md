---
title: "Edit an affix template"
source_title: "Edit an affix template"
breadcrumb:
  - "Using Tools"
  - "Grammar tools"
  - "Category Edit"
  - "Edit an affix template"
source: "Using_Tools/Grammar_tools/Category_Edit/Edit_an_Affix_Template_Table.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Grammar_tools/Category_Edit/Edit_an_Affix_Template_Table.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Add:Inflectional morpheme to a slot in affix template"
  - "Affix Template"
  - "Edit"
  - "Edit:Affix template"
  - "Inflectional morpheme"
  - "Morpheme"
  - "Move (or reorder)"
  - "Move (or reorder):Affix up or down in Affix Template Table"
  - "New:Lexical entry"
  - "Order (see also Move)"
  - "Reorder Slots in template table"
  - "Slot"
  - "Table:Table"
  - "Template"
  - "add to slot"
  - "from affix template table"
related:
  - "Active field -> ../../../User_Interface/Field_Descriptions/Grammar/Category_Edit_fields/Active_field_templates.md"
  - "Category Edit overview -> Category_Edit_overview.md"
  - "Open a project -> ../../../User_Interface/Menus/File/Open_a_language_project.md"
  - "Template table example -> affix_template_table_example.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:f19b2e8ad989f526"
---

# Edit an affix template

*Using Tools › Grammar tools › Category Edit*

1.  In the **Navigation Pane**, click **Grammar**, and then click **Category Edit**.

2.  In the center column, click the **Category** that has the [template table](affix_template_table_example.md) you will edit.

    Column *headers (*except **STEM**) are slot names. Headers have different right-click menus than affixes (table content).

Do any of the steps below.

3.  Right-click **STEM**, and then select **Insert Slot Before STEM** *or* **Insert Slot After STEM**.

    Select a slot in the **Choose Slot** dialog box, and then click **OK**. That slot appears in table.

    - If the slot you need is *not* in the dialog box, click **Add an optional slot to \<category\>** or **Add an obligatory slot to \<category\>**.

      A new slot named **Type slot name here** appears. Select and rename the **Type slot name here** column heading.

      (**Type slot name here** may change to **Unnamed1**, **Unnamed2**, and so on when you click it.)

4.  Right-click a slot name (column header), and then select one of these commands:

    - **Add inflectional affix(es) to \<****slot** `name>`

      The **Choose Inflectional Affixes** dialog box appears. If necessary, [configure the columns](../../../Basic_Tasks/Configure_Columns/Configure_Columns_overview.md) in this dialog box to help you identify the inflectional affix. Select an affix, and then click **OK**.

      If the affix you want does not exist, click the **Create new inflectional affix** link. The **New Entry** dialog box appears so you can [add an affix entry](../../Lexicon_tools/Lexicon_Edit/Create_a_lexical_entry.md).

    - **Insert Slot Before \<**`name>` *or* **Insert Slot After** `<name>`. In the **Choose Slot** dialog box, select a slot and then click **OK**. If the slot you want does not exist, click **Add an optional slot** *or* **Add an obligatory slot**.

    - **Move** **\<slot name\>** **forward one Slot** *or* **Move** **\<slot name\>** **back one Slot**.

    - **Change Optionality of** `<name>` **Slot**

    - **Remove** **\<name\>** **Slot**

      The slot is removed from the template. (The slot is *not* deleted from the language project but remains available for other templates).

5.  Right-click an affix in a column or a space in a column below the slot name, and then select one of these commands:

    - **Add inflectional affix(es) to \<**`slot name>`

      The **Choose Inflectional Affixes** dialog box appears. Select an affix, and then click **OK**.

      If the affix you want does not exist, click the **Create new inflectional affix** link. The **New Entry** dialog box appears so you can [add an affix entry](../../Lexicon_tools/Lexicon_Edit/Create_a_lexical_entry.md).

    - **Remove** **\<affix\>** **from** **\<slot name\>**

      The affix is removed from the slot.

    - **Move \<affix\> Affix Down** *or* **Move \<affix\> Affix Up**

    - **Show Entry in Lexicon** to see the affix in **Lexicon Edit**.

    6.  Select (![](../../../assets/images/CheckedBoxBLACK.png)) or clear (![](../../../assets/images/UncheckedBox.PNG)) the [Requires more derivation](../../../User_Interface/Field_Descriptions/Grammar/Category_Edit_fields/requires_more_derivation_field.md) field check box.

> [!NOTE]
>
> - For a discussion regarding the check box in the **Requires more derivation**, point to **Resources** on the [Help](../../../User_Interface/Menus/Help/Help_overview.md) menu, and then click **Introduction to Parsing**. See the section **Derivation Outside of Inflection**.
>
> - Content in the tables are used by [Stem Allomorph Labels](../../../User_Interface/Field_Descriptions/Grammar/Category_Edit_fields/Stem_Allomorph_Label_field.md).
>
> - Sample project **Sena 3**, included with FieldWorks, has affix template tables.

## Related topics
[Active field](../../../User_Interface/Field_Descriptions/Grammar/Category_Edit_fields/Active_field_templates.md)

[Category Edit overview](Category_Edit_overview.md)

[Open a project](../../../User_Interface/Menus/File/Open_a_language_project.md)

[Template table example](affix_template_table_example.md)
