---
title: "Change the morph type"
source_title: "Change the morph type"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Lexicon Edit"
  - "Change the morph type"
source: "Using_Tools/Lexicon_tools/Lexicon_Edit/change_the_morph_type.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Lexicon_Edit/change_the_morph_type.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Change"
  - "Change:Morph type of an entry"
  - "Morpheme Types"
  - "Choose (See also: Select or Specify):Morph Type"
  - "Change (Lexicon)"
  - "Morpheme"
  - "Morph Type"
related:
  - "Change the tokens of morpheme types -> ../../Lists_tools/Change_the_tokens_for_morpheme_types.md"
  - "Insert an allomorph -> Insert_an_alternate_form.md"
  - "Lexicon Edit overview -> lexicon_edit_overview.md"
  - "Morph Type field -> ../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Morph_Type_Field.md"
  - "Show Hidden fields -> ../../../Basic_Tasks/Showing_and_hiding_fields/Show_Hidden_Fields.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:8756997edb35bc12"
---

# Change the morph type

*Using Tools › Lexicon tools › Lexicon Edit*

You initially specify a morpheme type when you use the [New Entry](Create_a_lexical_entry.md) dialog box or when you [insert an allomorph](Insert_an_alternate_form.md). Entries created in [Collect Words](../Collect_Words/Collect_Words_overview.md) are automatically assigned **Stem** as their morph type. You can [Bulk change the morph type](../../../Lexicography_Tasks/bulk_change_the_morph_type.md) or change one entry at a time.

1.  In the **Navigation** **Pane**, click **Lexicon**, and then click **Lexicon Edit**.

2.  In the **Entries** pane, click the desired entry.

3.  In the **Entry** pane, do the following:

    - Click the **Morph Type** field at the *entry* level (above **Sense 1**), *or* in a particular allomorph (**Allomorphs**).

    - Click the ellipsis button ![PIC](../../../assets/images/Ellipsis_button.PNG) that appears.

      The **Choose Morpheme Type** dialog box appears.

4.  Do any of these steps:

    - Select (![PIC](../../../assets/images/CheckedBox.PNG)) **Display usage figures** to see how many times each type is used in the project.

    - Select (![PIC](../../../assets/images/CheckedBox.PNG)) **Show all types** (*entry* level only) to see all types.

    - Click the type you want. Click **OK**.

> [!IMPORTANT]
>
> - At the *entry* level, the dialog box content is *initially* limited to those morpheme types that are applicable to the entry, based on the original selection. You can show and select other types.
>
> - A question box (![PIC](../../../assets/images/QuestionMark_blue.png)) appears if you try choose the morph type "root" or "bound root" for an entry that has [components](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Components_field.md). It informs you that a root cannot be divided and therefore cannot have components.
>
> - - You can choose to let FLEx delete the component references and change the morph type, *or* to cancel the pending morph type change.
>
> - For **Allomorphs**, depending on the morph type you select, an *affix* allomorph may become a *stem* allomorph, or a *stem* allomorph may become an *affix* allomorph.
>
> - Morpheme types are used by the [parsers](../../../User_Interface/Menus/Parser/Parsing_words_overview.md).

## Related topics
[Change the tokens of morpheme types](../../Lists_tools/Change_the_tokens_for_morpheme_types.md)

[Insert an allomorph](Insert_an_alternate_form.md)

[Lexicon Edit overview](lexicon_edit_overview.md)

[Morph Type field](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Morph_Type_Field.md)

[Show Hidden fields](../../../Basic_Tasks/Showing_and_hiding_fields/Show_Hidden_Fields.md)
