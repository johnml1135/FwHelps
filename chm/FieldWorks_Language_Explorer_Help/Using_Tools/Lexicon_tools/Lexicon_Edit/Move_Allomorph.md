---
title: "Move an allomorph"
source_title: "Move an allomorph"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Lexicon Edit"
  - "Move an allomorph"
source: "Using_Tools/Lexicon_tools/Lexicon_Edit/Move_Allomorph.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Lexicon_Edit/Move_Allomorph.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Stem Allomorph"
  - "Affix Allomorph"
  - "Move (or reorder):Allomorph"
  - "Order (see also Move)"
  - "Allomorph"
  - "Allomorph:Move an allomorph"
  - "Allomorph:Allomorph order for parser"
related:
  - "Allomorphs-level fields overview -> ../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Alt_Forms_lev_flds_ov.md"
  - "Lexicon Edit overview -> lexicon_edit_overview.md"
  - "Merge allomorphs -> Merge_allomorphs.md"
  - "Swap Lexeme Form with Allomorph -> Swap_LexForm_with_Allomorph.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:d523be5f79c7d9cf"
---

# Move an allomorph

*Using Tools › Lexicon tools › Lexicon Edit*

If a lexical entry has *more than one* allomorph, (stem or affix allomorph), you can easily move them up or down to change their order within **Allomorphs** for the current entry.

To move an allomorph, do the following:

1.  In the **Navigation** **Pane**, click **Lexicon**, and then click **Lexicon Edit**.

2.  In the **Entries** pane, click entry that has the allomorphs you want to move.

3.  In the **Entry** pane, click the **Stem Allomorph** or **Affix Allomorph** field that you want to move.

    Links and a menu button (![](../../../assets/images/Using_Tools/Lexicon_tools/Lexicon_Edit/Menu_Button_pic.GIF)) appear.

4.  Click the menu button, and then click **Move Form Up** or **Move Form Down**.

    The allomorph moves up or down one position. You can repeat this to set the desired order.

> [!IMPORTANT]
>
> - Allomorph order is *very* **important** for the [parsers](../../../User_Interface/Menus/Parser/Parsing_words_overview.md), which works with them in this order: first allomorph, second allomorph, ..., nth allomorph, *then* lexeme form. This is particularly true when environments are used to constrain the forms as each allomorph automatically *inherits* the negation of the environments of any *preceding* allomorphs.
>
>   For more information, on the [Help](../../../User_Interface/Menus/Help/Help_overview.md) menu, point to **Resources**, and then click **Introduction to Parsing**. The order of allomorphs within a lexical entry is discussed under **Morphophonemics**.

## Related topics
[Allomorphs-level fields overview](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Alt_Forms_lev_flds_ov.md)

[Lexicon Edit overview](lexicon_edit_overview.md)

[Merge allomorphs](Merge_allomorphs.md)

[Swap Lexeme Form with Allomorph](Swap_LexForm_with_Allomorph.md)
