---
title: "Import Standard Format interlinear texts"
source_title: "Import Standard Format interlinear texts"
breadcrumb:
  - "Beginning Tasks"
  - "Importing Data"
  - "Import Standard Format interlinear texts"
  - "Import Standard Format interlinear texts"
source: "Beginning_Tasks/Importing_Data/Import_Interlinear_SFM/Import_Standard_Format_interlinear_texts.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Beginning_Tasks/Importing_Data/Import_Interlinear_SFM/Import_Standard_Format_interlinear_texts.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "SFM Import"
  - "Import:Standard Format interlinear texts"
  - "Standard Format import:Import Standard Format interlinear texts"
related:
  - "Import overview -> ../Import_overview.md"
  - "Import Standard Format Words and Glosses -> ../Import_SFM_words_and_glosses/Import_Standard_Format_words_and_glosses.md"
  - "Writing System files -> ../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/Writing_System_files.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:b5eb03840360d0c0"
---

# Import Standard Format interlinear texts

*Beginning Tasks › Importing Data › Import Standard Format interlinear texts*

You can import standard format interlinear data. You can import one or more files. Each file can contain one or more texts.

You can import the vernacular words that appear on the **Baseline** tab, and content for the **Free** (Free Translation), **Lit** (Literal Translation), and **Note** lines. Currently, the import can also include **Info** tab metadata for the **Title**, **Abbreviation**, **Source**, and **Comment** fields.

To import standard format interlinear texts, do the following:

1.  Open the project into which you will import the interlinear texts.

2.  In the Navigation Pane, click **Texts** **&** **Words**.

3.  [Back up](../../../User_Interface/Menus/File/Backup_and_Restore/Back_up_this_Project.md) that language project (strongly *recommended*).

4.  [Stop the parser](../../../User_Interface/Menus/Parser/Start_or_Stop_Parser.md), if it is running.

5.  On the [File](../../../User_Interface/Menus/File/File_overview.md) menu, point to **Import**, and then click **Standard Format Interlinear**.

    The **Import Standard Format interlinear texts** dialog box opens to [Step 1 of 3: Import Files.](Step_1_of_3_Import_Files.md)

> [!IMPORTANT]
>
> - Some mappings are pre-defined ([table](Import_SF_Interlinear_predefined_mappings.md)).
>
> - The text in the import file must be marked up with Standard Format markers (SFM). If you import multiple texts or files at the same time, consistent used of markers across all the texts yields the best results.
>
>   Ideally, the *beginning* of each text should be a marked:
>
>   - Use **New Text**, one of the destinations in the [Modify Mapping](Step_2_of_3_Field_Mapping.md) dialog box, as the destination for the marker which indicates the beginning of a new text (or the first one), *when that marker does not contain any data to import*.
>
>   - Otherwise, consider mapping **\name** to **Title (of text)**, or a similar mapping, as your markers and data require.
>
>   - One or more segment markers (![](../../../assets/images/Beginning_Tasks/Importing_Data/Import_Interlinear_SFM/SegMarker.png)) may appear in the **Baseline** tab.
>
>   Another way to work with multiple texts in one file is this:
>
>   - The import operation allows any number of header fields (title, abbreviation, comment and source) to occur together; but, once the import operation gets into actual text fields, the start of a new text is automatically initiated as soon as it encounters another set of header fields.
>
>     If your data is *not* consistently marked, this option may yield undesirable results.
>
> - After importing, you will need to [insert morpheme breaks](../../../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/Insert_or_remove_morpheme_breaks.md) and other aspects of [interlinearization](../../../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/Analyze_Text_overview.md) again.
>
> - For more information, on the [Help](../../../User_Interface/Menus/Help/Help_overview.md) menu, point to **Resources**, and then click **Technical Notes on Interlinear Import**.
>
> - - Currently, some data cannot be imported, so those fields should be set to **Don't Import**.

## Related topics
[Import overview](../Import_overview.md)

[Import Standard Format Words and Glosses](../Import_SFM_words_and_glosses/Import_Standard_Format_words_and_glosses.md).

[Writing System files](../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/Writing_System_files.md)
