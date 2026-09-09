---
title: "Allomorph Status field (entry level)"
source_title: "Allomorph Status field (entry level)"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Lexicon"
  - "Lexicon Edit fields"
  - "Entry level fields"
  - "Allomorph Status field (lexeme form)"
source: "User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Allomorph_Status_field.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Allomorph_Status_field.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Allomorph Status field"
related:
  - "Entry-level fields overview -> Entry_level_fields_overview.md"
  - "Lexicon Edit overview -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md"
fw_help_version: "9.3"
page_heading: "Allomorph Status field"
type: "topic"
content_hash: "sha256:df13fc99b24e6525"
---

# Allomorph Status field (entry level)

*User Interface › Field Descriptions › Lexicon › Lexicon Edit fields › Entry level fields*

**Full name:** **Allomorph Status**

**Abbreviation:** **-**

**Location:**

In the **Entry** pane (**Lexicon Edit**).

This field is between the **Lexeme Form** [field](Lexeme_Form_field.md) and the **Sense 1** [field](../Sense_level_fields/Sense_field.md). It refers to the lexeme form, not the entire entry.

(An **Is Abstract Form** [field](../Alternate_Forms_level_flds/Is_Abstract_Form_fld_Allomorph.md) is at the [Allomorphs level](../Alternate_Forms_level_flds/Alt_Forms_lev_flds_ov.md) for each of the allomorphs. This chooser and that check box work *independently* of each other.)

**Description:**

This field stores your choice regarding whether the associated lexeme form is *abstract* (a form that never appears as a *surface* morpheme) or an *elsewhere* form. There is a drop-down chooser with two options:

- If you choose **Is Abstract Form**, it is marked as abstract and is *ignored* by [parsers](../../../../Menus/Parser/Parsing_words_overview.md). However, if you [convert](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Convert_existing_form_or_allomorph.md) an existing form into an Affix Process, this field is automatically selected and the parser uses the process.

- WIf you choose **Is Elsewhere Form**, the parsers use the form.

This check box may be automatically selected, such as when you [enter a circumfix](../../../../../Morphology_and_Parsing_Tasks/circumfix_example.md), but normally you manually select or clear it.

**Tasks:**

- [Bulk change Is Abstract Form](../../../../../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_change_Is_Abstract_Form.md)

- [Specify a Form is Abstract](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_a_Form_is_Abstract.md)

**Field type:** Check box

**Writing systems:** Not Applicable

**Tip:**

You can control which entries and allomorphs are available to a computational [parser](../../../../Menus/Parser/Parsing_words_overview.md). Then you can get a parser working correctly on an incremental basis:

- Suppose you imported many entries or added many with **Collect Words**. If you pass a large number of them through the parser while your morphological modeling (environments, rules, features and so on) is incomplete, it will run longer and you may find many wrong analyses.

- Instead, use the **Bulk Edit Entries** feature to quickly set all the lexeme forms and allomorphs to **yes** (abstract), and then set a small subset of them to **no** (not abstract). When the parser yields correct analyses for that subset, then set more lexeme forms or allomorphs to **no**. Eventually, only lexeme forms and allomorphs that are actually abstract will be set to **y****es**.

> [!IMPORTANT]
>
> - If an [import](../../../../../Beginning_Tasks/Importing_Data/Import_overview.md) problem (or source file problem) caused no lexeme or citation form content to be imported for an entry, the [Lexeme Form](Lexeme_Form_field.md) field is empty, as expected. In addition, this field and the [Morph Type](Morph_Type_Field.md) and [Environments](Environments_field.md) fields are displayed *only when* you type content in the empty **Lexeme Form** field.

## Related topics
[Entry-level fields overview](Entry_level_fields_overview.md)

[Lexicon Edit overview](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md)
