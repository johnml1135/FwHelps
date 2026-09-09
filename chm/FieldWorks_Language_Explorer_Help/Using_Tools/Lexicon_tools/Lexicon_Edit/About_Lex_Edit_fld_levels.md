---
title: "About Lexicon Edit field levels"
source_title: "About Lexicon Edit field levels"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Lexicon Edit"
  - "About Lexicon Edit field levels"
source: "Using_Tools/Lexicon_tools/Lexicon_Edit/About_Lex_Edit_fld_levels.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Lexicon_Edit/About_Lex_Edit_fld_levels.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Dictionary:Dictionary preview pane"
  - "Metadata"
  - "About:Lexical Entries and Senses"
related:
  - "Dictionary overview -> ../Dictionary/Dictionary_overview.md"
  - "Lexicon overview -> ../Lexicon_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:74c30f0874f25d7e"
---

# About Lexicon Edit field levels

*Using Tools › Lexicon tools › Lexicon Edit*

In **Lexicon Edit**, the **Entries** pane lists the entries. The `Entry` pane has [fields](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Lexicon_Edit_fields_overview.md) for the data in the selected entry. Thick horizontal lines separate **Entry** pane fields into groups. As viewed from top-to-bottom, these are the different levels:

## **Dictionary Preview**

- If shown, the top level is a [configured](../../../User_Interface/Menus/Tools/Configure_Dictionary/Configure_Dictionary.md) preview of the dictionary entry for the current lexical entry. (You can [show or hide](../../../User_Interface/Menus/View/View_overview.md) this preview pane.)

## **Entry-level fields**

The [Entry-level fields overview](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Entry_level_fields_overview.md) topic has two tables:

- The top table contains the **Lexeme Form** field and the set of fields that refer to the lexeme form as the "elsewhere allomorph." Therefore, it is not technically correct to define them as entry-level fields even though they appear above the **Sense 1** field.

- The bottom table refers to all the other fields that can appear above the **Sense 1** field. These fields are entry-level fields because the data in them must be applicable to each sense in the entry. Otherwise, add another entry. Homograph numbers are automatically generated to distinguish entries with identical headwords, but you can [change](../Browse/Change_homograph_numbers.md) or [reassign](../../../User_Interface/Menus/Tools/Language_Project_Utilities_overview.md) them.

## **Sense-level fields**

- Each sense or subsense has fields which store one of the lexical entry's meanings and associated data or metadata. The first sense is automatically created when you create the entry. You can manually [insert](Insert_a_sense_or_subsense_in_an_entry.md) more senses and subsenses. These are numbered automatically. Only [variants](../../Lists_tools/About_Entry_Types.md) can exist without at least one sense. **See:** [Sense-level fields overview](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Sense_level_fields_overview.md).

## **Variants-level fields**

- This section has fields that store variant forms of the current headword (lexeme or citation form), and associated data or metadata. **See:** [Variant-level fields overview](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Variants_level_fields/Variant_level_fields_overview.md). (There are some similar entry-level fields.)

## **Allomorphs-level fields**

- This section has fields that store allomorphs (stem or affix) of the current headword (lexeme or citation form), and associated data or metadata. **See:** [Allomorphs-level fields overview](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Alt_Forms_lev_flds_ov.md).

## **Grammatical Info Details-level fields**

- This section displays, in a semi-prose form, *all* **Grammatical Info** field content used by the senses in the current entry. Unused grammatical information is *automatically* deleted. **See:** [Grammatical Info level fields overview](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Grammatical_Info_Details_fields/Gram_Info_Detls_fields_ovw.md) and [Delete Grammatical Info](Delete_grammatical_info.md).

> [!TIP]
>
> - This section has fields that store information regarding whether or not an entry is a candidate to appear in **Dictionary**. **See:** [Publication Settings-level Fields overview](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Publication_Settings_flds/Publ_Set_level_fields_overview.md).
>
> ### Note
>
> - The level of a field can determine how other views, such as [Bulk Edit](../Bulk_Edit_Entries/bulk_edit_overview.md), display the lexical data and the total record values shown on the [Status bar](../../../User_Interface/Toolbars/status_bar.md). **See also:** [Target Field selection](../Bulk_Edit_Entries/Target_field_selection.md).
>
> - You can choose to show or hide fields individually with the [Field Visibility feature](../../../Basic_Tasks/Showing_and_hiding_fields/Show_hiding_flds_oview.md), or [show or hide groups of fields](../../../Basic_Tasks/Showing_and_hiding_fields/Hide_show_gps_of_flds.md).
>
> - In the dictionary preview pane, right-click the part of the entry that you want to edit, and then **Jump to field**. This will move the cursor to the [field](../../../User_Interface/Field_Descriptions/field_descriptions_overview.md) that stores that part of the entry.
>
> ### Related Topics
>
> [Dictionary overview](../Dictionary/Dictionary_overview.md)
>
> [Lexicon overview](../Lexicon_overview.md)
