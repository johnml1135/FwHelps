---
title: "Parse current word"
source_title: "Parse current word"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Parser"
  - "Parse current word"
source: "User_Interface/Menus/Parser/Parse_Current_Word.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Parser/Parse_Current_Word.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Parser:Parse current word"
  - "Current Word"
related:
  - "Parser menu overview -> Parser_menu_overview.md"
  - "Parsing words overview -> Parsing_words_overview.md"
  - "Remove Parser-approved analysis utility -> ../Tools/Language_Project_Utilities_overview.md"
  - "Texts & Words overview -> ../../../Using_Tools/Texts_&_Words_tools/Texts_and_Words_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:45ff17213cbb65a4"
---

# Parse current word

*User Interface › Menus › Parser*

**Parse Current Word** [starts](Start_or_Stop_Parser.md) the parser that is currently [selected](Parser_menu_overview.md), if it is not already running. It also loads the grammar and lexical data, if they are not already loaded into the parser.

1.  In **Texts & Words**, select **Word List Concordance**, **Word Analyses** *or* **Bulk Edit Wordforms**.

2.  In the **Wordforms** pane, select the word you want to parse.

3.  If necessary, use [Clear Current Word's Parser Analysis](Clear_current_parser_analyses.md).

4.  On the **Parser** menu, click **Parse Current Word**.

    The [status bar](../../Toolbars/status_bar.md) shows the status of the parser, but the window ([columns](../../../Using_Tools/Texts_&_Words_tools/Word_list_columns.md) and [Parse result field](../../Field_Descriptions/Texts_&_Words/Parse_result_field.md)) may not change after the parser is finished. Refresh (**F5**) the window, if necessary.

5.  Any of the following results may occur:

    - The **Parse result** field will show **Successful** *or* **Failure**.

    - If displayed, the values in the **Predicted Analysis** and **Conflicting Opinions** columns could change, depending on the result.

    - A new analysis may appear in the **Wordform Analyses** pane.

> [!TIP]
>
> - You can make a rule available (Active) or unavailable to parsers.**\
>   See:** [Active field (Ad hoc Rules)](../../Field_Descriptions/Grammar/Ad_hoc_Rules_fields/Active_field_Ad_Hoc_Rules.md), [Active field (Compound Rules)](../../Field_Descriptions/Grammar/Compound_Rules_fields/Compound_Rules_fields_overview.md), or [Active field (Phonological Rules)](../../Field_Descriptions/Grammar/Phonologocial_Rules_fields/Active_field_(Ph_Rules).md).
>
> - You can make an affix template table available (Active) or unavailable to parsers.**\
>   See:** [Active field (Affix Templates)](../../Field_Descriptions/Grammar/Category_Edit_fields/Active_field_templates.md).

## Related topics
[Interlinear view background colors](../../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/interlinear_views_background_colors.md)

[Parser menu overview](Parser_menu_overview.md)

[Parsing words overview](Parsing_words_overview.md)

[Remove Parser-approved analysis utility](../Tools/Language_Project_Utilities_overview.md)

[Texts & Words overview](../../../Using_Tools/Texts_&_Words_tools/Texts_and_Words_overview.md)
