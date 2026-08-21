---
title: "Lexeme Form field"
source_title: "Lexeme Form field"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Lexicon"
  - "Lexicon Edit fields"
  - "Entry level fields"
  - "Lexeme Form field"
source: "User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Lexeme_Form_field.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Lexeme_Form_field.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Lexeme Form:Lexeme Form field"
  - "Rule"
related:
  - "Audio files overview -> ../../../../../Basic_Tasks/Audio_files/Audio_files_overview.md"
  - "Change entry type -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/change_the_entry_type.md"
  - "Change the Morph Type -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/change_the_morph_type.md"
  - "Choose Environments -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_environments.md"
  - "Enter a citation form -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Enter_a_citation_form.md"
  - "Entry-level fields overview -> Entry_level_fields_overview.md"
  - "Bulk Edit overview -> ../../../../../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md"
  - "Insert an allomorph -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Insert_an_alternate_form.md"
  - "Lexicon Edit overview -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md"
  - "Morphological and Parsing Tasks overview -> ../../../../../Morphology_and_Parsing_Tasks/Morphology_Parsing_Tasks_overview.md"
  - "Show data overview -> ../../../../../Basic_Tasks/Show_data/Show_data_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:f2ce013bb4366fd6"
---

# Lexeme Form field

*User Interface › Field Descriptions › Lexicon › Lexicon Edit fields › Entry level fields*

**Full name:** **Lexeme Form**

**Abbreviation:** **lx**

**Location:**

In the **Entry** pane (**Lexicon Edit**).

This field is at the top of the **Entry** pane, below the dictionary preview pane.

**Description:**

This field stores the orthographic form that represents this lexeme. This is typically the bare stem (the form of the word without any inflectional affixes).

- If the bare stem is not a well-formed word, it is common to use the **Citation Form** field to indicate whatever form is appropriate to serve as the dictionary headword.
- If an entry has more than one form (allomorphs), enter either the most common form (the "elsewhere allomorph" or the "underlying form") in the **Lexeme Form** field.\
  [Enter](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Insert_an_alternate_form.md) all of the other allomorphs in the fields at the **Allomorphs** [level](../Alternate_Forms_level_flds/Alt_Forms_lev_flds_ov.md).

Language Explorer uses the contents from this field as the dictionary headword, *unless* the **Citation Form** field also has content (then, the **Citation Form** field content is used). You typically [configure the dictionary](../../../../Menus/Tools/Configure_Dictionary/Configure_Dictionary.md) to display [Headword](../../../../Menus/Tools/Configure_Dictionary/Headword.md), but you may select [Citation Form](../../../../Menus/Tools/Configure_Dictionary/Citation_Form.md) or [Lexeme Form](../../../../Menus/Tools/Configure_Dictionary/Lexeme_Form.md).

**Tasks:**

- [Specify that form is complex (has components)](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_that_Form_is_Complex.md)

- [Specify that form is a variant](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_that_a_form_is_a_variant.md)

- [Specify that a form is abstract](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_a_Form_is_Abstract.md)

- [Swap Lexeme Form with allomorph](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Swap_LexForm_with_Allomorph.md)

- [Convert an existing form into an Affix Process](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Convert_existing_form_or_allomorph.md)

  - [Build an Affix Process Rule](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Build_Affix_Process_Rule.md)

- [Create a Pattern-Matching Entry](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Create_a_Template_Entry.md) (for use by the Hermit Crab [parser](../../../../Menus/Parser/Parsing_words_(HermitCrab).md))

**Right-click options:**

- [Show](../../../../../Basic_Tasks/Show_data/Show_in_from_Lexicon.md):

  - Right-click the form for **Show Entry in Concordance** or **Show Lexeme Form in Concordance**. (**Show Entry** includes allomorphs.)

  - Right-click the field label or use the menu button for **Show Lexeme Form in Concordance** ([example](../../../../../Basic_Tasks/Show_data/Context_sens_menus.md)).

**Field type:** [Single-line text field](../../../Field_Types/Single_line_text_field.md) – you *cannot* embed characters in other writing systems or embed styles

**Writing systems:** One or more [vernacular](../../../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md)\
([Spell checking](../../../../../Basic_Tasks/Spell_Checking/vernacular_spell_checking.md) is not enabled in this field.)

> [!IMPORTANT]
>
> - The [Lexicon](../../../../../Using_Tools/Lexicon_tools/Lexicon_overview.md) **Browse** and **Bulk Edit Entries** views have a column labeled **Headword**. There is *no* field in **Lexicon Edit** with this label. Instead, the **Headword** column content is from **Lexeme Form** field, *unless* there is content in the **Citation Form** field.
>
> - If an [import](../../../../../Beginning_Tasks/Importing_Data/Import_overview.md) problem (or source file problem) caused no lexeme or citation form content to be imported for an entry, this field is empty, as expected.
>
> - If a lexeme form (or a citation form) requires the use of an apostrophe as a word-forming character (such as in the *Sena* words `kang'ombe` or **ng'anga**), refer to [Word-forming apostrophes and glottal stops](../../../../Menus/Insert/wordforming_apostophes.md) for information to help you use the correct apostrophe.
>
> - For more information about "elsewhere allomorphs", on the **Help** [menu](../../../../Menus/Help/Help_overview.md) point to **Resources** and then click **Introduction to Parsing**.

## Related topics
[Audio files overview](../../../../../Basic_Tasks/Audio_files/Audio_files_overview.md)

[Change entry type](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/change_the_entry_type.md)

[Change the Morph Type](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/change_the_morph_type.md)

[Choose Environments](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_environments.md)

[Enter a citation form](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Enter_a_citation_form.md)

[Entry-level fields overview](Entry_level_fields_overview.md)

[Bulk Edit overview](../../../../../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md)

[Insert an allomorph](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Insert_an_alternate_form.md)

[Lexicon Edit overview](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md)

[Morphological and Parsing Tasks overview](../../../../../Morphology_and_Parsing_Tasks/Morphology_Parsing_Tasks_overview.md)

[Show data overview](../../../../../Basic_Tasks/Show_data/Show_data_overview.md)
