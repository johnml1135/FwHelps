---
title: "Specify grammatical info"
source_title: "Specify grammatical info"
breadcrumb:
  - "Lexicography Tasks"
  - "Specify grammatical info"
source: "Lexicography_Tasks/Specify_Grammatical_Info.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Lexicography_Tasks/Specify_Grammatical_Info.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Bulk Edit Entries:Specify grammatical info"
  - "Specify (See Also: Select or Choose)"
  - "Specify (See Also: Select or Choose):Grammatical info"
  - "Lexicography tasks"
related:
  - "Add from Catalog -> ../Using_Tools/Lexicon_tools/Lexicon_Edit/Using_Add_from_Catalog_dialog_box.md"
  - "Bulk Edit overview -> ../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md"
  - "Lexicography Tasks overview -> Dictionary_and_Lexicon_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:26807f43f10b9131"
---

# Specify grammatical info

*Lexicography Tasks*

In FieldWorks Language Explorer, you specify the [grammatical info](../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Grammatical_Info_field.md) (category, inflection class, slot, and so on) for each sense of each entry. If your language has inflectional or derivational affixes that can indicate the grammatical category of the word, you can use these affixes to identify and specify the grammatical category.

For example, in English the derivational suffixes `-ment` and `-tion` produce nouns, the suffixes **-ize** and **-ate** produce verbs, the suffixes **-ful** and **-able** produce adjectives, and the suffix **-ly** produces adverbs. If your language has affixes like these, you can use them to specify the grammatical category for large groups of words all at once.

You can use the steps below as a model from which you can create an efficient bulk edit process that works best for your language.

1.  In the **Navigation Pane**, click **Lexicon**, and then click **Bulk Edit Entries**.

2.  Click the **List Choice** tab.

3.  [Use](../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) the **Configure Columns** dialog box to hide/show/move columns (fields) and select writing systems, if permitted. Show the **Citation Form** or **Lexeme Form** field, and the **Grammatical Category** field.

4.  In the **Lexeme Form** column for *derivational* suffixes, or **Citation Form** field for *inflectional* suffixes, do the following:

    - [Filter for](../Basic_Tasks/Filtering_data/Using_Filter_for.md) a particular affix.

      For example, you can filter for the suffix “`ment`” or “`tion`,” specifying **At end** in the **Filter for items containing** dialog box.

    - Examine the result of your filter.

5.  In the **Target Field** box, select **Grammatical Category**.

6.  In the **Change To** box, select the desired grammatical category.

7.  In the left column, [select the rows](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/select_rows.md) you want to change.

8.  Click **Preview**, review the pending changes, and then click **Apply**.

9.  Repeat for words with each affix as necessary.

> [!TIP]
>
> - For additional information about the purpose of this topic or when it may be of use to you, on the [Help](../User_Interface/Menus/Help/Help_overview.md) menu, point to **Resources** and then click **Introduction to Lexicography**.

## Related topics
[Add from Catalog](../Using_Tools/Lexicon_tools/Lexicon_Edit/Using_Add_from_Catalog_dialog_box.md)

[Bulk Edit overview](../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md)

[Lexicography Tasks overview](Dictionary_and_Lexicon_overview.md)
