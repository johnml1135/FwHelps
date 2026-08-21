---
title: "Choose Inflection Class"
source_title: "Choose Inflection Class"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Lexicon Edit"
  - "Choose an inflection class"
source: "Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_an_inflection_class.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_an_inflection_class.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Inflection Class"
  - "Inflection Class:Choose Inflection Class"
  - "Choose (See also: Select or Specify):Inflection Class (Lexicon & Grammar)"
  - "About:Inflection classes"
  - "Declension"
related:
  - "Bulk change the inflection class -> ../Bulk_Edit_Entries/bulk_change_inflect_class.md"
  - "Default Inflection Class field -> ../../../User_Interface/Field_Descriptions/Grammar/Category_Edit_fields/Default_Inflection_Class_field.md"
  - "Inflection Class field (Compound Rules) -> ../../../User_Interface/Field_Descriptions/Grammar/Compound_Rules_fields/inflection_class_field_compound_rules.md"
  - "Lexicon Edit overview -> lexicon_edit_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:eff57f8e1e3daab8"
---

# Choose Inflection Class

*Using Tools › Lexicon tools › Lexicon Edit*

Inflection classes are used by the [parsers](../../../User_Interface/Menus/Parser/Parsing_words_overview.md). Consider the following as you choose inflection classes:

|  |  |  |  |
|----|----|----|----|
| Entry | Number of Inflection Classes Permitted | Associated Field(s) | Field Location |
| Non-Affix | One for each sense with unique grammatical info | [Inflection Class field](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Grammatical_Info_Details_fields/Inflection_Class_field_Lex_Edit.md) | Below [Grammatical Info Details](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Grammatical_Info_Details_fields/grammatical_info_details_field.md) |
| Affix (Inflectional *or* Derivational) | One or more | [Inflection Classes field](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/inflection_classes_field_entry_level.md) | Below **Lexeme Form** field |
| Affix, Derivational | **From**/**To** inflection class pair | [From Inflection Class](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Grammatical_Info_Details_fields/from_inflection_class_field.md) *and* [To Inflection Class](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Grammatical_Info_Details_fields/To_Inflection_Class_field.md) fields | Below [Grammatical Info Details](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Grammatical_Info_Details_fields/grammatical_info_details_field.md) |
| Affix Allomorph | One or more | [Inflection Classes fields](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Inflection_classes_fld_Allomorph.md) | Below [Affix Allomorph field](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Affix_allomorph_fld.md) |
| *Non-headed* compound rule | One | [Inflection Class field](../../../User_Interface/Field_Descriptions/Grammar/Compound_Rules_fields/inflection_class_field_compound_rules.md) | In [Compound Rules](../../Grammar_tools/Compound_Rules/Compound_Rules_overview.md), ([Grammar](../../Grammar_tools/grammar_overview.md)) |

### In Lexicon Edit, do the following:

1.  In the **Navigation** **Pane**, click **Lexicon**, and then click **Lexicon Edit**.

2.  In the **Entries** pane, click the desired entry.

3.  In the **Entry** pane, if you cannot see the appropriate **Inflection Class** or **Inflection Classes** field, or **From**/**To Inflection Class** field pair, [show hidden fields](../../../Basic_Tasks/Showing_and_hiding_fields/Show_Hidden_Fields.md).

4.  Click the appropriate field, and then click the ellipsis button ![](../../../assets/images/Ellipsis_button.PNG) that appears.

    The **Choose Inflection Class or Choose Inflection Classes** dialog box appears.

5.  Do any of the following:

    - Select (![](../../../assets/images/CheckedBox.PNG)) **Display usage figures** to see how many times each **Inflection Class** or subclass is used in the project.

    - Click the "**Edit the Inflection Classes for** **\<name\>**" link to [insert](../../Grammar_tools/Category_Edit/Insert_an_Inflection_Class.md) or edit an inflection class or subclass.

    - Select (![](../../../assets/images/CheckedBox.PNG)) one or more inflection classes (as permitted by the field). Click **OK**.

    - Repeat the steps above if the entry requires more than one inflection class, such as for **From/To** pairs.

### In Grammar Compound Rules, do the following:

1.  In the **Navigation** **Pane**, click **Grammar**, and then click **Compound Rules**.

2.  In the **Compound Rules** pane, click the *non-headed* compound rule for which you will choose an inflection class.

3.  In the right pane, if you cannot see the **Inflection Class** field, [show hidden fields](../../../Basic_Tasks/Showing_and_hiding_fields/Show_Hidden_Fields.md).

    Hidden fields appear.

4.  Click the **Inflection Class** field, and then click the ellipsis button ![](../../../assets/images/Ellipsis_button.PNG) that appears.

    The **Choose Inflection Class** dialog box appears.

5.  Do one of the following:

    - Click the "**Edit the Inflection Classes for** **\<name\>**" link so you can [insert](../../Grammar_tools/Category_Edit/Insert_an_Inflection_Class.md) an inflection class.

    - Click the inflection class you want to display. Click **OK**.

> [!TIP]
>
> - For more information on inflection classes, point to **Resources** on the [Help](../../../User_Interface/Menus/Help/Help_overview.md) menu, and then click **Introduction to Parsing**.

## Related topics
[Bulk change the inflection class](../Bulk_Edit_Entries/bulk_change_inflect_class.md)

[Default Inflection Class field](../../../User_Interface/Field_Descriptions/Grammar/Category_Edit_fields/Default_Inflection_Class_field.md)

[Inflection Class field (Compound Rules)](../../../User_Interface/Field_Descriptions/Grammar/Compound_Rules_fields/inflection_class_field_compound_rules.md)

[Lexicon Edit overview](lexicon_edit_overview.md)
