---
title: "Insert a variant form"
source_title: "Insert a variant form"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Lexicon Edit"
  - "Insert a variant form"
source: "Using_Tools/Lexicon_tools/Lexicon_Edit/Insert_a_variant_form.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Lexicon_Edit/Insert_a_variant_form.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Insert:Variant form"
  - "Create:Lexical entry:Create a minor entry"
  - "Variant Forms"
  - "Variant Forms:Insert a variant form"
  - "Minor entry"
  - "Lexical"
  - "Lexical:Insert a variant form"
related:
  - "Context-sensitive menus -> ../../../Basic_Tasks/Show_data/Context_sens_menus.md"
  - "Dialect Labels (Entry) field -> ../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Variants_level_fields/Dialect_Labels_(Entry)_variant.md"
  - "Lexicon Edit overview -> lexicon_edit_overview.md"
  - "Show Hidden Fields -> ../../../Basic_Tasks/Showing_and_hiding_fields/Show_Hidden_Fields.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:99f31c75ec174e05"
---

# Insert a variant form

*Using Tools › Lexicon tools › Lexicon Edit*

1.  In the **Navigation** **Pane**, click **Lexicon**, and then click **Lexicon Edit**.

2.  In the **Entries** pane, click the desired entry.

3.  In the **Entry** pane, click the **Variants** field label.

    An **Insert Variant** link and a menu button (![](../../../assets/images/Using_Tools/Lexicon_tools/Lexicon_Edit/Menu_Button_pic.GIF)) appear.

4.  Do one of the following:

    - Click the **Insert Variant** link.

    - Click the menu button ![](../../../assets/images/Using_Tools/Lexicon_tools/Lexicon_Edit/Menu_Button_pic.GIF) next to the field, and then click **Insert Variant**.

    - Click the menu button ![](../../../assets/images/Using_Tools/Lexicon_tools/Lexicon_Edit/Information_bar_Menu_button.PNG) on the [Information bar](../../../User_Interface/Toolbars/information_bar_overview.md), and then click **Insert Variant**.

    - On the [Insert](../../../User_Interface/Menus/Insert/Insert_overview.md) menu, click **Variant**.

    The **Find Variant** dialog box appears.

5.  In the dialog box, do any of the following:

    - If necessary, change the selection in the **Writing System** box.

    - In the **Variant** box, type the variant form.

    - If the variant appears in the **Lexical Entries** pane, click that entry, and then click **Link Selected**.

    - If the variant does not appear in the **Lexical Entries** pane, click **Create** to create a new variant form as entered in the **Variant** box.

    A set of [Variant-level fields](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Variants_level_fields/Variant_level_fields_overview.md) appears, with content in the **Variant Form** field. If you created a new form, a new lexical entry appears in the **Entries** pane.

6.  In the **Dialect Labels (Entry)** field, [choose Dialect Labels](Choose_a_dialect_label.md) (*optional*).

7.  In the **Variant Type** field, [choose Variant Types](Choose_variant_types.md).

8.  The **Show Minor Entry** field check box is selected (![](../../../assets/images/CheckedBox.PNG)) by default.\
    Clear (![](../../../assets/images/User_Interface/Menus/Tools/UncheckedBox.PNG)) this check box if you do *not* want the variant to be available for display as a minor entry in the dictionary.

9.  In the **Comment** field, enter a comment (*optional*).

10. If you created a new entry from the **Find Variant** dialog box, do the following to complete the new lexical entry:

    - Click the new entry in the **Entries** pane.

    - In the **Entry** pane, enter or select content in [fields](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Lexicon_Edit_fields_overview.md) as necessary.

> [!IMPORTANT]
>
> - Variant entries inserted this way do *not have a sense*. This may be important if you use a [parser](../../../User_Interface/Menus/Parser/Parsing_words_overview.md). You can [delete](delete_a_sense_or_subsense.md) or [insert](Insert_a_sense_or_subsense_in_an_entry.md) senses.
>
> In the **New Entry** dialog box, you cannot specify that the entry is a variant. However, you can [specify that an existing form is a variant](Specify_that_a_form_is_a_variant.md).
>
> - The [Variant of](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Variant_of_field.md) field contains the headword of the entry into which you inserted the variant form. The variant form has the same **Morph Type** selection as the **Variant of** entry.
>
> - You can [choose](Choose_Variant_of_entry.md) multiple entries or senses in a **Variants of** field if the variant type is the same for each one. You can also [add another Variant Info section](Add_another_Variant_Info_section.md) if they are *not* the same.
>
> - In [Dictionary](../Dictionary/Dictionary_overview.md), variants are displayed as [minor entries](../../../User_Interface/Menus/Tools/Configure_Dictionary/Main_Minor_entry.md).

## Related topics
[Context-sensitive menus](../../../Basic_Tasks/Show_data/Context_sens_menus.md)

[Dialect Labels (Entry) field](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Variants_level_fields/Dialect_Labels_(Entry)_variant.md)

[Lexicon Edit overview](lexicon_edit_overview.md)

[Show Hidden Fields](../../../Basic_Tasks/Showing_and_hiding_fields/Show_Hidden_Fields.md)
