---
title: "Is Abstract Form field (Alternate Form)"
source_title: "Is Abstract Form field (Alternate Form)"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Lexicon"
  - "Lexicon Edit fields"
  - "Allomorphs level fields"
  - "Is Abstract Form field"
source: "User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Is_Abstract_Form_fld_Allomorph.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Is_Abstract_Form_fld_Allomorph.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Abstract:Is Abstract Form field (allomorph)"
  - "Is Abstract Form:Is Abstract Form field (Allomorph)"
related:
  - "Allomorphs-level fields overview -> Alt_Forms_lev_flds_ov.md"
  - "Lexicon Edit overview -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md"
fw_help_version: "9.3"
page_heading: "Is Abstract Form field"
type: "topic"
content_hash: "sha256:a8b1d3ca9b49920d"
---

# Is Abstract Form field (Alternate Form)

*User Interface › Field Descriptions › Lexicon › Lexicon Edit fields › Allomorphs level fields*

**Full name:** **Is Abstract Form**

**Abbreviation:** **ab**

**Location:**

In the **Entry** pane (**Lexicon Edit**).

This field is at the [Allomorphs level](Alt_Forms_lev_flds_ov.md) for each allomorph.

(An **IAllomorph Status** [field](../Entry_level_fields/Allomorph_Status_field.md) appears below the **Lexeme Form** [field](../Entry_level_fields/Lexeme_Form_field.md) and is for the lexeme form. This check box and that chooser work *independently* of each other.)

**Description:**

This field stores your choice regarding whether or not the allomorph is *abstract* (an allomorph form that never appears as a *surface* morpheme).

- When selected (![](../../../../../assets/images/CheckedBox.PNG)), the allomorph form is marked as abstract and is *ignored* by [parsers](../../../../Menus/Parser/Parsing_words_overview.md). However, if you [insert](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Insert_Affix_Process_Rule.md) an Affix Process allomorph, this field is automatically selected and the parser uses the process.

- When cleared (![](../../../../../assets/images/UncheckedBox.PNG)), the parser uses the allomorph.

**Field type:** Check box

**Tasks:**

- [Bulk change Is Abstract Form](../../../../../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Bulk_change_Is_Abstract_Form.md)

- [Specify a Form is Abstract](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_a_Form_is_Abstract.md)

**Writing systems:** Not Applicable

**Tip:**

You can control which entries and allomorphs are available to a computational [parser](../../../../Menus/Parser/Parsing_words_overview.md). Then you can get a parser working correctly on an incremental basis:

- Suppose you imported many entries or added many with **Rapid Words**. If you pass a large number of them through the parser while your morphological modeling (environments, rules, features and so on) is incomplete, it will run longer and you may find many wrong analyses.

- Instead, use the **Bulk Edit Entries** feature to quickly set all the lexeme forms and allomorphs to **yes** (abstract), and then set a small subset of them to **no** (not abstract). When the parser yields correct analyses for that subset, then set more lexeme forms or allomorphs to **no**. Eventually, only lexeme forms and allomorphs that are actually abstract will be set to **yes**.

## Related topics
[Allomorphs-level fields overview](Alt_Forms_lev_flds_ov.md)

[Lexicon Edit overview](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md)
