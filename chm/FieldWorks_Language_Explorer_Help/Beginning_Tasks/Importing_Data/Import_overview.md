---
title: "Import overview"
source_title: "Import overview"
breadcrumb:
  - "Beginning Tasks"
  - "Importing Data"
  - "Import overview"
source: "Beginning_Tasks/Importing_Data/Import_overview.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Beginning_Tasks/Importing_Data/Import_overview.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Texts & Words:Import overview"
  - "import SFM"
  - "MDF Standard Format"
  - "SFM Import"
  - "Import"
  - "Import:Import overview"
  - "ELAN"
  - "ELAN:Import from ELAN"
related:
  - "Beginning Tasks overview -> ../Beginning_Tasks_overview.md"
  - "Collaborating with Others overview -> ../../Basic_Tasks/Collaborating_with_Others/Collaborating_with_Others_overview.md"
  - "Send/Receive menu overview -> ../../User_Interface/Menus/Send_Receive/Send_Receive_menu.md"
fw_help_version: "9.3"
type: "index"
content_hash: "sha256:a26de0ed1a1a3ba9"
---

# Import overview

*Beginning Tasks › Importing Data*

## Lexical data

- [Import LIFT Lexical data](import_lift_lex.md) (*Lexicon Interchange FormaT*)

You can choose merge setting and then import a LIFT file.

**See Also:** [Receive Lexicon (LIFT)](../../User_Interface/Menus/Send_Receive/Get_a_lexicon.md).

- [Import Standard Format lexical data](Import_Standard_Format_lexical_data.md)

You can import lexical data that is marked with Standard Format (SF) markers.

- [Import from The Combine](Import_from_The_Combine.md)

You can import a \*.zip file that was exported from The Combine.

(<a href="https://thecombine.app/login" target="_blank" title="https://thecombine.app/login">https://thecombine.app/login</a>)

## Interlinear Texts

- [Import Standard Format interlinear](Import_Interlinear_SFM/Import_Standard_Format_interlinear_texts.md)

  This command allows you to import **Baseline** tab words (the text) and free-form text annotations that are marked up with Standard Format markers (SFM). You can specify an [encoding converter](About_encoding_converters.md) when you map the data to fields in FLEx. You will need to make the morpheme breaks again and do other [interlinear](../../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/Analyze_Text_overview.md) work after the import is finished.

- [Import FieldWorks Interlinear (FLExText) data](Import_interlinear_data.md)

  When you [export interlinear texts](../../User_Interface/Menus/File/Export/Export_Interlinear.md), the format option **FLExText Interlinear** creates a file with a filename extension of \*.flextext. Use *this* import option to import these FLExText files into FieldWorks.

  Currently, the **Baseline** tab words (the text) and **Free** translations, are imported, but *not* include **Lit** or **Note** lines, or text charts. It does not change the lexicon. The **Info** tab data is imported, except any **Genres** field selections.

- [Import Standard Format words and glosses](Import_SFM_words_and_glosses/Import_Standard_Format_words_and_glosses.md)

  This command allows you to import words and their glosses for files that are with Standard Format (SF) markers. In **Word Analyses**, you will see the imported words appear in the **Form** [column](../../Using_Tools/Texts_%26_Words_tools/Word_list_columns.md) and the glosses in the **Word Glosses** column. Nothing is added to **Baseline** tabs in **Interlinear Texts**.

## Anthropology data

- [Import Standard Format](Import_Notebook_Data/Import_SF_anthro_data.md)

  This command allows you to import Standard Format data into the **Notebook** area. An import wizard allows you to back up the project, choose setting and then import the Standard Format anthropological data.

## Grammatical Category

- [Import Translated Grammatical Category Content](Import_Translated_Grammatical_Category_Content.md)

FLEx allows you to populate grammatical category information with translations for non-English analysis writing systems.

- [Import Phonology](Import_Phonology.md)

This import the lists of [phonological features](../../User_Interface/Field_Descriptions/Grammar/Phonological_Features_fields/Phonological_Features_fields_overview.md), [phonemes](../../User_Interface/Field_Descriptions/Grammar/Phonemes_fields/Phonemes_fields_overview.md), [Natural Classes](../../User_Interface/Field_Descriptions/Grammar/Natural_Classes_fields/natural_classes_fields_overview.md) and [Phonological Rules](../../User_Interface/Field_Descriptions/Grammar/Phonologocial_Rules_fields/Phonological_Rules_fields_overview.md) that were [exported](../../User_Interface/Menus/File/Export/Export_Phonology_as_XML_file.md) as an XML file.

## Lists

- [Import Translated List Content](Import_Translated_List_Content.md)

  FLEx allows you to import localized lists.

## Other

- **ELAN** download a set of instructions from

<a href="https://tla.mpi.nl/tools/tla-tools/elan/thirdparty/" target="_blank" title="https://tla.mpi.nl/tools/tla-tools/elan/thirdparty/">https://tla.mpi.nl/tools/tla-tools/elan/thirdparty/</a>.

or [Get more help](../../Overview/Technical_support.md).

- [Import LinguaLinks data](import_lingualinks_data.md)

  A dialog box allows you to specify a FieldWorks writing system and encoding converter for each language used in the LinguaLinks file. The import includes the lexical data, text (word list, interlinearized text), and list items. You will need to add the grammar rules manually.

> [!TIP]
>
> - **See Also:** [Get Project](../../User_Interface/Menus/Send_Receive/Get_a_project.md).
>
> - You can also import dictionary and reversal index layout files. See [Manage Dictionary Layouts](../../User_Interface/Menus/Tools/Configure_Dictionary/Manage_Dictionary_Views.md) or [Manage Reversal Index Layouts](../../User_Interface/Menus/Tools/Configure_Reversal_Index/Manage_Views_Reversal_Index.md).
>
> - For more information about importing, point to **Resources** on the [Help](../../User_Interface/Menus/Help/Help_overview.md) menu, and then click **Technical Notes on LinguaLinks Import** or **Technical Notes on SFM Database Import**.

## Related topics
[Beginning Tasks overview](../Beginning_Tasks_overview.md)

[Collaborating with Others overview](../../Basic_Tasks/Collaborating_with_Others/Collaborating_with_Others_overview.md)

[Send/Receive menu overview](../../User_Interface/Menus/Send_Receive/Send_Receive_menu.md)
