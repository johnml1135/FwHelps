---
title: "Import Standard Format lexical data"
source_title: "Import Standard Format lexical data"
breadcrumb:
  - "Beginning Tasks"
  - "Importing Data"
  - "Import Standard Format lexical data"
source: "Beginning_Tasks/Importing_Data/Import_Standard_Format_lexical_data.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Beginning_Tasks/Importing_Data/Import_Standard_Format_lexical_data.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "SFM Import"
  - "Import:Standard Format lexical data"
  - "TECkit"
  - "CC (Consistent Changes)"
  - "Standard Format import:Import Standard Format lexical data"
related:
  - "Import overview -> Import_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:47fcd1356ced327e"
---

# Import Standard Format lexical data

*Beginning Tasks › Importing Data*

You can import *Standard Format* (SFM) lexical data, typically from *Toolbox*. To do this, you map the markers to fields in FieldWorks, and specify the languages used in the data you will import. The FieldWorks Language Explorer provides a wizard to help with these tasks.

1.  Prepare your SFM data for import as follows:

    - Provide a way to convert the orthography for each language in your SFM file to Unicode if it is *not* already in Unicode. This could be a TECkit table, a CC (Consistent Changes) table, a Windows Code page, and so on. You may need to specify an [encoding converter](About_encoding_converters.md) while you map the language using the import wizard. Note that if you do not do this and use custom (hacked) encodings, some of your data (or characters) will come out as boxes or question marks.

    - You need to understand the use of each marker and have an idea of how these will map to FieldWorks entries and senses.

    - If you have multiple items in one field separated by a delimiter, you need to consider if you should split these into separate markers, if permitted for the field. See [Examples](Import_SFM_data_examples.md).

    - While we can import inconsistent categories (parts of speech) and other markers, the results will be more satisfactory if you can make these consistent prior to import.

    - If you mark homograph numbers or sense numbers in references, they *must* match what FieldWorks expects.

2.  Prepare the FieldWorks project for the import as follows:

    - Use the [FieldWorks Project Properties Writing Systems](../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md) tab to add each of the analysis and vernacular writing systems used in the data you will import.

    - It is important to back up your data. You can do this before you open the wizard or as one of the steps while using the wizard.

3.  If you will need a Keyman keyboard for one or more of the writing systems, you need to install the applicable keyboard(s) *before* you can enter or edit text in those writing systems. You can install the keyboard before or after importing the data. (Refer to **Keyman** `Help` for instructions.)

4.  On the **File** menu, click **Import Standard Format Lexicon**.

    The **Import Standard Format lexical data wizard** appears at [Step 1 of 8](step_1_of_8_overview_and_backup.md).

> [!NOTE]
>
> - You can also open this multiple-step wizard from the [Language Explorer](../../Overview/Welcome_to_FieldWorks.md) or [Unable to Open Project](../../User_Interface/Menus/File/Unable_to_Open_Project.md) dialog boxes.
>
> - You *cannot* import any data into [multiparagraph text fields](../../User_Interface/Field_Descriptions/Field_Types/Multiparagraph_text_field.md), nor into a **Number** (*Type*) custom field. If you need to [add](../../User_Interface/Menus/Tools/Custom_Fields/add_a_custom_field.md) a custom field, make sure it is a [single-line text](../../User_Interface/Field_Descriptions/Field_Types/Single_line_text_field.md) field.
>
> - For more information about importing, point to **Resources** on the [Help](../../User_Interface/Menus/Help/Help_overview.md) menu, and then click **Technical Notes on SFM Database Import**.
>
> - One experienced user offered [his process](Prepare_MDF_data.md) for preparing MDF data for import.

## Related topics
[Import overview](Import_overview.md)

<a href="http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&amp;cat_id=TECkit" target="_blank">TECkit - Text Encoding Conversion toolkit</a>
