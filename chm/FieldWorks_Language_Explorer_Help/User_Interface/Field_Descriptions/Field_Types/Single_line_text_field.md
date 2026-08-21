---
title: "Single-line text field"
source_title: "Single-line text field"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Field Types"
  - "Single-line text field"
source: "User_Interface/Field_Descriptions/Field_Types/Single_line_text_field.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Field_Types/Single_line_text_field.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Writing System:Single-line text field"
  - "Single-line text field"
  - "Enter:Enter (embed) characters in other writing system"
  - "Embed characters"
  - "Embedding:Embedding writing systems in fields"
related:
  - "Apply Style -> ../../Menus/Format/apply_a_style_to_text.md"
  - "Abbreviation of writing system -> ../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_General_tab.md"
  - "Field Types overview -> field_types_overview.md"
  - "Move a field -> ../../../Basic_Tasks/Moving_fields/Move_a_field.md"
  - "Select a writing system -> ../../Menus/Format/select_a_writing_system.md"
  - "Showing writing systems overview -> ../../../Basic_Tasks/Showing_Writing_Systems/Show_WSs_overview.md"
  - "User Interface overview -> ../../User_Interface_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:76de65e6216289f4"
---

# Single-line text field

*User Interface › Field Descriptions › Field Types*

A *single-line text field* ([example](Single_line_text_field_example_graphic.md)) stores only a single line or string of text, although for many you can [embed characters](../../Menus/Format/select_a_writing_system.md) in different writing systems (see below). These contrast with [multiparagraph text fields](Multiparagraph_text_field.md).

Here are some features of single-line text fields:

- Multiple paragraphs are *not* possible in these fields.

- You cannot apply *paragraph* styles. See **Variations** below.

- The line of text wraps automatically when the width of the field is too narrow to display the text on one line.\
  In addition, `Shift+Enter` forces a line break or controls where the line wraps.

- There is a limit to the length of the line of text, but these fields provide sufficient space for what you typically need to type. Some are limited to fewer than 4000 characters, but most permit many more characters.

- [Tables](../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Format_a_table.md) can be formatted with USFM markers in a [custom field](../../Menus/Tools/Custom_Fields/Custom_Fields_overview.md) of this [type](field_types_overview.md).

### Variations

- Most single-line text fields store multiple parallel strings of text, each with a different writing system so you can have translations of the string of text in different writing systems. Writing system identifiers are [displayed on the left end of each line](Single_line_text_field_example_graphic.md) to indicate the writing system for that line when more than one writing system is used. Usually, you can [configure writing systems for fields](../../../Basic_Tasks/Showing_Writing_Systems/configure_field_WSs.md) individually.

- In some, *not all*, you can embed characters using *other* writing systems. For those that permit embedding, the [writing system box](../../Toolbars/Format_toolbar.md) on the **Format** toolbar or **Writing Systems** on the **Format** menu are available so you can [select the writing system](../../Menus/Format/select_a_writing_system.md) in which you will embed the text. (If the font supports it, you can use the [Character Map](../../Menus/Insert/Using_Character_Map.md) to insert special characters, even in a line that does not support embedded text.)

- For some, you can use *character* styles to change selectively the appearance of words in the text. (However, others do *not* permit *any* formatting, such as some **Lexeme Form** field, although you *can* apply styles when you [configure the dictionary](../../Menus/Tools/Configure_Dictionary/Configure_Dictionary.md).)

- Most allow you to [configure which writing systems](../../../Basic_Tasks/Showing_Writing_Systems/configure_field_WSs.md) to display in that field using the menu button ![](../../../assets/images/Basic_Tasks/Showing_Writing_Systems/Menu_Button_pic.GIF) next to the field's label. The selections you make *do not* affect other fields.

- The [Title field](../Notebook/Title_field_Ntbk.md) in **Notebook** allows you to specify the writing system it uses, but only allows *one* writing system displayed at a time.

- Other single-line text fields are set by the program (or by you, in the case of [custom fields](../../Menus/Tools/Custom_Fields/Custom_Fields_overview.md)) to store only a single line of text using the default analysis or vernacular writing system. However, you may be permitted to embed text using other writing systems.

## Related topics
[Apply Style](../../Menus/Format/apply_a_style_to_text.md)

[Abbreviation of writing system](../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_General_tab.md)

[Field Types overview](field_types_overview.md)

[Move a field](../../../Basic_Tasks/Moving_fields/Move_a_field.md)

[Select a writing system](../../Menus/Format/select_a_writing_system.md)

[Showing writing systems overview](../../../Basic_Tasks/Showing_Writing_Systems/Show_WSs_overview.md)

[User Interface overview](../../User_Interface_overview.md)
