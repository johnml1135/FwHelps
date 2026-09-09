---
title: "Convert existing form or allomorph"
source_title: "Convert existing form or allomorph"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Lexicon Edit"
  - "Convert existing form or allomorph into an Affix Process"
source: "Using_Tools/Lexicon_tools/Lexicon_Edit/Convert_existing_form_or_allomorph.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Lexicon_Edit/Convert_existing_form_or_allomorph.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Affix Process Rule (Lexicon Edit):Insert an Affix Process Rule field"
  - "Convert:Convert to Affix process (entry or allomorph)"
  - "Process Rule"
related:
  - "Affix Process Rule field -> ../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Affix_Process_Rule_field.md"
  - "Affix Process Rule field -> ../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Affix_Process_Rule_fldAF.md"
  - "Delete Allomorph -> delete_an_alternate_form.md"
  - "Lexicon Edit overview -> lexicon_edit_overview.md"
fw_help_version: "9.3"
page_heading: "Convert an existing form or allomorph into an Affix Process"
type: "topic"
content_hash: "sha256:db10a525cf011ac3"
---

# Convert existing form or allomorph

*Using Tools › Lexicon tools › Lexicon Edit*

You can convert an existing affix lexeme form or affix allomorph to be an Affix Process, *or* convert an Affix Process to be an affix lexeme form or affix allomorph. **See also:** [Insert an Affix Process allomorph](Insert_Affix_Process_Rule.md).

## Convert an existing affix lexeme form or allomorph to be an Affix Process

1.  Do one of these steps:

- Click the **Lexeme Form** [field](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Lexeme_Form_field.md) label.

- Click the **Affix Allomorph** [field](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Affix_allomorph_fld.md) label.

2.  Click the menu button ![](../../../assets/images/Using_Tools/Lexicon_tools/Lexicon_Edit/Menu_Button_pic.GIF) that appears, and then click **Convert to Affix Process**.

    An **Affix Process Rule** field appears.

The **Affix Allomorph** field becomes the **Affix Allomorph (Process)** [field](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Affix_allomorph_fld.md).

3.  [Build the affix process rule](Build_Affix_Process_Rule.md).

> [!IMPORTANT]
>
> - *Convert to* an Affix Process refers to changes that enable the following functionality:
>
>   Instead of merely saying, for example, that "**-um-**" is an infix and it can occur in these positions: **/ \# \[C\] \_** or **/ \# \_ \[V\]**", that there is a *process* that matches this sequence of segments and converts them to another sequence (including inserting "**-um-**" at the appropriate place).
>
> - The conversion *removes* the **Environments**, **Infix Positions** and **Infix Positions** fields. Existing content in those fields are lost.
>
> - For an existing allomorph, the **Affix Allomorph** field becomes the **Affix Allomorph (Process)** [field](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Affix_allomorph_fld.md).
>
> - The conversion selects (![](../../../assets/images/CheckedBox.PNG)) the **Is Abstract Form** [field](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Allomorph_Status_field.md).
>
> <!-- -->
>
> - A lexical entry can have a mix of regular allomorph(s) and process allomorph(s). It can also have more than one process allomorph, for example, in cases where different inflection classes have different infixation processes.

## Convert an Affix Process to be an affix form or an allomorph

This is reverse conversion, from an Affix Process to an affix lexeme form or allomorph.

1.  Do one of these steps:

- Right-click the **Lexeme Form** [field](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Lexeme_Form_field.md) label and then click **Convert to Affix Form**.

- Right click the **Affix Allomorph (Process)** [field](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Affix_allomorph_fld.md) label, and then click **Convert to Affix Allomorph**.

The **Affix Process Rule** field is removed, and the other applicable fields are restored.

2.  Enter contents in the restored fields as necessary.

## Related topics
[Affix Process Rule field](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Affix_Process_Rule_field.md) (Lexeme)

[Affix Process Rule field](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Affix_Process_Rule_fldAF.md) (Allomorph)

[Delete Allomorph](delete_an_alternate_form.md)

[Lexicon Edit overview](lexicon_edit_overview.md)
