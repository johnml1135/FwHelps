---
title: "Try a Word additional information"
source_title: "Try a Word additional information"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Parser"
  - "Try a Word additional information"
source: "User_Interface/Menus/Parser/Try_a_Word_additional_information.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Parser/Try_a_Word_additional_information.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Try a Word:Try a Word additional information"
related:
  - "About parser parameters -> About_parser_parameters.md"
  - "Texts & Words overview -> ../../../Using_Tools/Texts_&_Words_tools/Texts_and_Words_overview.md"
  - "Try a Word -> Try_a_word.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:e8939fa027577807"
---

# Try a Word additional information

*User Interface › Menus › Parser*

[Try a Word](Try_a_word.md) uses the computational [parser](Parsing_words_overview.md) that is currently [selected](Parser_menu_overview.md).

- If the default parser is selected, you can change the analysis of the word directly in the **Try a Word** dialog box and try to reparse the word any number of times. (See **Note** below.)

  - You can [right-click](../../../Basic_Tasks/Show_data/Context_sens_menus.md) a morpheme in the analysis in **Try a Word** and "[jump](../../../Basic_Tasks/Show_data/Show_data_overview.md)" to **Lexicon** so you can edit the entry while **Try a Word** remains displayed. When you click **Try it**, the grammatical and lexical data is reloaded before the parse is tried.

- In the **Results** area, each red line ends with a comment in parentheses. Inside the parentheses, it always begins with **Reason:** and is followed by an explanation of the reason why the parser failed at this point, that is, when trying this sequence of allomorphs/morphemes.

- Sometimes the reason given is **Word** **grammar failed**. When that happens, the **Tell me more** button appears. Click this button for more information about why the *Word Grammar* failed.

- **Try the next pass** button appears while exploring why the *Word Grammar* failed. For an example and discussion, see [Try the next pass example](Try_the_next_pass_example.md).

- Even when a parse succeeds, it is possible to get some of these red lines, and information about the parse.

- The result of the parse in **Try a Word** does *not* affect or update the [Parse results field](../../Field_Descriptions/Texts_%26_Words/Parse_result_field.md) or any [columns](../../../Using_Tools/Texts_%26_Words_tools/Word_list_columns.md).

- The parser will pause from working on any [lower-priority parse operations](Parser_menu_overview.md) remaining in the [queue](../../Toolbars/status_bar.md) until you *close* the **Try a Word** dialog box.

- If a phrase appears in the **Word to try** box when you click **Try it**, an information box appears stating that the parser can process only one word at a time.

> [!NOTE]
>
> - The results from **Try a Word** do *not* change or update any data or analyses displayed in **Texts and Words** data in any way. However, it may appear like **Try a Word** is affecting the **Word Analyses** area even though it is not:
>
> When the parser is running and you are in the **Word Analyses** area, every time you click on a word, FLEx automatically invokes the **Parse Current Word** command, as if you had [chosen](Parse_Current_Word.md) this command. The results of that parse are then supposed to show for that word (there may be times when it doesn't, such as when it takes a very long time for the word to parse). By "results of that parse" we mean any analyses the parser suggests. If the parser fails, then nothing new will be added.
>
> *Key point*: After you invoke **Try a Word** on a word, the parser is running. So, if you go to some other word (word2) and come back to the first word (word1), FLEx will automatically invoke **Parse Current Word** on word1. As a result of this invocation of **Parse Current Word** (*not* the **Try a Word** invocation), you see the parses show up for the word. (FLEx also invoked **Parse Current Word** on word2.)
>
> If after running **Try a Word**, you could click the **Stop Parser** [menu](Parser_menu_overview.md) command, then you will see that there is no change to word1.
>
> - You can make a rule available (Active) or unavailable to parsers.**\
>   See:** [Active field (Ad hoc Rules)](../../Field_Descriptions/Grammar/Ad_hoc_Rules_fields/Active_field_Ad_Hoc_Rules.md), [Active field (Compound Rules)](../../Field_Descriptions/Grammar/Compound_Rules_fields/Active_field_Compound_Rules.md), or [Active field (Phonological Rules)](../../Field_Descriptions/Grammar/Phonologocial_Rules_fields/Active_field_(Ph_Rules).md).
>
> - You can make an affix template table available (Active) or unavailable to parsers.**\
>   See:** [Active field (Affix Templates)](../../Field_Descriptions/Grammar/Category_Edit_fields/Active_field_templates.md).
>
> - **Ctrl + F** opens a **Find** dialog box so you can search the **Results** pane.

## Related topics
[About parser parameters](About_parser_parameters.md)

[Texts & Words overview](../../../Using_Tools/Texts_%26_Words_tools/Texts_and_Words_overview.md)

[Try a Word](Try_a_word.md)
