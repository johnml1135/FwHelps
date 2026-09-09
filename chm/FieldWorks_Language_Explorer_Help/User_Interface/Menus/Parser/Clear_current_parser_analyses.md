---
title: "Clear current parser analyses"
source_title: "Clear current parser analyses"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Parser"
  - "Clear Current Parser Analyses"
source: "User_Interface/Menus/Parser/Clear_current_parser_analyses.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Parser/Clear_current_parser_analyses.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Clear Current Word's Parser Analyses"
  - "Page Setup"
  - "Parser:Clear current parser analyses"
  - "Predicted Analyses"
related:
  - "Configure columns dialog box -> ../../../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md"
  - "Interlinear views background colors -> ../../../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/interlinear_views_colors.md"
fw_help_version: "9.3"
page_heading: "Clear Current Word's Parser Analyses"
type: "topic"
content_hash: "sha256:30d7c00cfba45853"
---

# Clear current parser analyses

*User Interface › Menus › Parser*

1.  In the [Navigation Pane](../../Toolbars/Navigation/Navigation_Pane_overview.md) click **Texts & Words**, and then select **Word Analyses**.

2.  In the **Wordforms** pane, click a word to select it.

3.  On the [Parser](Parser_menu_overview.md) menu, click **Clear Current Word's Parser Analyses**.

> [!NOTE]
>
> - **Clear Current Word's Parser Analyses** does the following for the *selected* word:
>
> - - [Parse result](../../Field_Descriptions/Texts_&_Words/Parse_result_field.md) fields change from **Successful** or **Failure** *to* **Untested**.
>
>   - Analyses set to **User Opinion Unknown** are deleted. Analyses that reflect user involvement, such as those set to **User Disapproved**, are *not* deleted.
>
>   - The numerical value in the **Predicted Analyses** [column](../../../Using_Tools/Texts_&_Words_tools/Word_list_columns.md) (if displayed in the **Wordforms** pane) changes to **0** (zero) indicating that there are currently no successful parses for the word.
>
> - The [Remove Parser-approved analyses](../Tools/Language_Project_Utilities_overview.md) utility on the **Tools** menu does the same for the *entire* [word list](../../../Using_Tools/Texts_&_Words_tools/Word_list_overview.md).
>
> - Use this **Parser** menu command or the utility when you think there are problems of any kind with the analyses that are returned by the parser, or when you simply want to remove parser-suggested analyses.
>
> - Then, you can use [Parse Current Word](Parse_Current_Word.md) or [Reparse all words](Reparse_all_words.md) to learn if **Failure** or **Successful** appears in the **Parse result** fields and if additional analyses are proposed by the selected [parser](Parsing_words_overview.md).

## Related topics
[Configure columns dialog box](../../../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md)

[Interlinear views background colors](../../../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/interlinear_views_colors.md)
