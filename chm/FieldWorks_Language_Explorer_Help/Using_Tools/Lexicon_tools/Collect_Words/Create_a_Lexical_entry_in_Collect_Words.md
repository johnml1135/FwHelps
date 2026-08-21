---
title: "Create a lexical entry in Collect Words"
source_title: "Create a lexical entry in Collect Words"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Collect Words"
  - "Create a lexical entry in Collect Words"
source: "Using_Tools/Lexicon_tools/Collect_Words/Create_a_Lexical_entry_in_Collect_Words.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Collect_Words/Create_a_Lexical_entry_in_Collect_Words.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Lexical entry"
  - "Lexical entry:Create from Categorized Entry"
  - "Create"
  - "Create:Lexical entry"
  - "Create:Lexical entry:Lexical entry from Categorized Entry"
  - "Add:Entry to lexicon"
  - "New:Lexical entry"
  - "from Categorized Entry"
  - "Collect Words:Create a lexical entry in Collect Words"
related:
  - "Collect Words fields overview -> ../../../User_Interface/Field_Descriptions/Lexicon/Collect_Words_fields/Collect_Words_fields_overview.md"
  - "Collect Words overview -> Collect_Words_overview.md"
  - "Lexicography Tasks overview -> ../../../Lexicography_Tasks/Dictionary_and_Lexicon_overview.md"
  - "Writing Systems tab -> ../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:b0b4bd66299f07a0"
---

# Create a lexical entry in Collect Words

*Using Tools › Lexicon tools › Collect Words*

1.  In the **Navigation Pane**, click **Lexicon**, and then click **Collect Words**.

2.  In the lower part of the **Semantic Domain** (*right*) pane, [configure the columns](../../../Basic_Tasks/Configure_Columns/Configure_Columns_overview.md) to hide, show, or order columns, or to specify their writing systems.

See Also: [Collect Words with Dialect Labels](Collect_Words_with_Dialect_Labels.md).

3.  In the **Semantic Domains** (*center*) pane, select the semantic domain for new lexical entry. If necessary, [search for the semantic domain](Search_Semantic_Domains.md).

The **Semantic Domain** (*right*) pane displays a description of the domain, questions and examples. These help elicit appropriate vernacular words.

4.  In the lower-right pane, do the following:

    - In an empty row, click a cell in a **Word** column, and then type the form (citation or lexeme).

    - Press `Tab` to move to the next editable cell in the row. If that cell is in a **Word** column, type the form (citation or lexeme); if it is in a **Meaning** column, type a meaning (gloss or [initial definition](Collect_Words_initial_definition_considerations.md)).

    - Press `Tab` to move to the next cell, if any. Then type contents there.

    - When you are done with the row, press `Enter`.

A lexical entry is added. The word appears in the [Citation Form](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Citation_Form_field.md) or [Lexeme Form](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Lexeme_Form_field.md) field. The gloss appears in the [Gloss](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Gloss_field_Sense.md) field; the definition in the [Definition](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/definition_field.md) field. The semantic domain appears in the [Semantic Domain](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/semantic_domains_field.md) field for a sense. The [Morph Type](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Morph_Type_Field.md) field displays the morph type.

If you type the same word more than one time, or the word matches an existing lexical entry, FLEx attempts to *prevent* duplicate entries. When possible, any additional information is collected in one lexical entry. For example, if you typed the exact same word (form) and gloss for two different semantic domains, then the two semantic domains will appear in the **Semantic Domains** field in one entry. Otherwise, you might see additional senses or another entry with a homograph number.

> [!IMPORTANT]
>
> - For each semantic domain, do steps 3 and 4 repeatedly, considering each question in the top-right pane until you are satisfied with the numbers of words collected.
>
> - For affixes (e.g., 9.2.9), you need to type the tokens ([leading](../../../User_Interface/Field_Descriptions/Lists/Morpheme_Types_fields/leading_token_field_morpheme_types.md) and [trailing](../../../User_Interface/Field_Descriptions/Lists/Morpheme_Types_fields/trailing_token_field_morpheme_types.md)). This informs the program of the morph type for the affix entry. This is similar to typing [tokens](../../Lists_tools/About_Morpheme_Types.md) in the **New Entry** dialog box.
>
> - If you will type dialect labels with your new lexical entries, see [Collect Words with Dialect Labels](Collect_Words_with_Dialect_Labels.md).
>
> - The rows remain editable (have a white background color) until you leave the view or semantic domain, and then return.
>
> - - A row or cells with a darkened background color is not editable in this view. In this case, right-click it, and then click **Show Entry in Lexicon** to display it in [Lexicon Edit](../Lexicon_Edit/lexicon_edit_overview.md).
>
>   - If you see a row with darkened background, but you do not see any words in the row, then display additional columns until you see words in that row.
>
> <!-- -->
>
> - Later, you will need to complete the analysis of the word and develop a quality definition.
>
>   Entries created by this method may not have a [gloss](../../../Lexicography_Tasks/Fill_in_the_Gloss_Field.md), and do not initially have [Grammatical Info](../../../Lexicography_Tasks/Specify_Grammatical_Info.md). These are necessary when you [analyze](../../Texts_&_Words_tools/Interlinear_Texts/Analyze_Text_overview.md) or [parse](../../../User_Interface/Menus/Parser/Parsing_words_overview.md) texts. Case is also important.

## Related topics
[Collect Words fields overview](../../../User_Interface/Field_Descriptions/Lexicon/Collect_Words_fields/Collect_Words_fields_overview.md)

[Collect Words overview](Collect_Words_overview.md)

[Lexicography Tasks overview](../../../Lexicography_Tasks/Dictionary_and_Lexicon_overview.md)

[Writing Systems tab](../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md)
