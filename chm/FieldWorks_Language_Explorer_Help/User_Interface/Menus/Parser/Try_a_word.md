---
title: "Try a Word"
source_title: "Try a Word"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Parser"
  - "Try a word"
source: "User_Interface/Menus/Parser/Try_a_word.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Parser/Try_a_word.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Parser:Try a Word"
  - "Try a Word"
  - "Active:Try a Word"
related:
  - "Optional (slot) field -> ../../Field_Descriptions/Grammar/Category_Edit_fields/Optional_field.md"
  - "Parse result field -> ../../Field_Descriptions/Texts_&_Words/Parse_result_field.md"
  - "Parser menu overview -> Parser_menu_overview.md"
  - "Parsing words overview -> Parsing_words_overview.md"
  - "Requires more derivation field -> ../../Field_Descriptions/Grammar/Category_Edit_fields/requires_more_derivation_field.md"
  - "Texts & Words overview -> ../../../Using_Tools/Texts_&_Words_tools/Texts_and_Words_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:916e32be2e18e246"
---

# Try a Word

*User Interface › Menus › Parser*

The **Try a Word** dialog box uses the computational [parser](Parsing_words_overview.md) that is currently [selected](Parser_menu_overview.md). The results from **Try a Word** do *not* change or update any data or analyses displayed in **Texts and Words** data in any way ([more](Try_a_Word_additional_information.md)).

1.  You can open this dialog box in these ways:

- On the **Parser** menu, click **Try a** **Word**.

- Click the **reparse** button for a word in a [parser test report](Parser_Test_Reports.md).

The **Try a Word** dialog box appears.

2.  If the word you want to try does not appear in the **Word to try** box, type or paste it there.

    If you opened **Try a Word** from [Word Analyses](../../../Using_Tools/Texts_%26_Words_tools/Word_Analyses/Word_Analyses_overview.md), the current (selected) word appears. Otherwise, the last word you tried continues to appear.

3.  To see a trace in the **Results** pane, select the **Let me see all the detailed steps the parser tried** check box. Otherwise, leave the check box cleared to see only the result in the **Results** pane.

    - [Default (XAmple) parser](Parsing_words.md) only: Select or clear the **Let me break the word into its morphemes** check box. If selected, you can see and change the word analysis in the **Try a Word** dialog box.

      ![](../../../assets/images/Important_Icon.gif) **Important:** When this check box is selected, the morphemes that the parser tries are limited to those you can see in the analysis. This may speed up the parse, but it may also change the *result*. The most-frequently-used analysis appears by default. However, you can [select another existing analysis](../../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/Select_existing_analysis.md), or create new lexical data using down arrow ![](down_arrow_pic.png) list commands. You may want to do this if you expect a particular set of morphemes to parse successfully and they do not. You can then look at the details to try and figure out why the parse is failing.

4.  Click **Try it** or press `Enter`.

    The parser starts in the dialog box. In some cases, it may take 15 minutes or more to initially load the lexical and grammatical data. (Reloading is usually much quicker.) While the parser is working, the bottom pane of the dialog box shows the parser status, such as **Trying Wordform** \<word\>. Then, the results and the trace, if selected, appear in the **Results** pane.

- **Ctrl + F** opens a **Find** dialog box so you can search the **Results** pane.

5.  If you had selected the **Let me see all the detailed steps the parser tried** check box, you can do any of the following:

    - Click **Show Details** to see an explanation of the results.

    - In the **Parsing Details** section, click a ![](../../../assets/images/User_Interface/Menus/Parser/Plus_sign_box_in_Try_a_Word.GIF)box by a morpheme to follow a path of explanation regarding the success or failure of the parse.

    - Click a **Tell me more** button to see an explanation of why *Word Grammar* failed.

    - Click a **Try the next pass** button so you can see what the [next step](Try_the_next_pass_example.md) of the *Word Grammar* could be.

    - If the **Let me break the word into its morphemes** check box is selected, you can change the analysis of the word to try different morphemes. Then repeat steps 4 and 5.

> [!IMPORTANT]
>
> - **See Also:** [Try a Word additional information](Try_a_Word_additional_information.md).

## Related topics
[Optional (slot) field](../../Field_Descriptions/Grammar/Category_Edit_fields/Optional_field.md)

[Parse result field](../../Field_Descriptions/Texts_&_Words/Parse_result_field.md)

[Parser menu overview](Parser_menu_overview.md)

[Parsing words overview](Parsing_words_overview.md)

[Requires more derivation field](../../Field_Descriptions/Grammar/Category_Edit_fields/requires_more_derivation_field.md)

[Texts & Words overview](../../../Using_Tools/Texts_%26_Words_tools/Texts_and_Words_overview.md)
