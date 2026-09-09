---
title: "Import LinguaLinks data"
source_title: "Import LinguaLinks data"
breadcrumb:
  - "Beginning Tasks"
  - "Importing Data"
  - "Import LinguaLinks data"
source: "Beginning_Tasks/Importing_Data/import_lingualinks_data.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Beginning_Tasks/Importing_Data/import_lingualinks_data.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Import:LinguaLinks data"
  - "LinguaLinks data"
  - "import"
related:
  - "Import overview -> Import_overview.md"
  - "Writing System files -> ../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/Writing_System_files.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:8bc41614debaa545"
---

# Import LinguaLinks data

*Beginning Tasks › Importing Data*

This import process will add items to your lexicon, wordforms, texts, and some lists. If you already have dictionary items and interlinearized texts in your FieldWorks project, this import will add many duplicate entries and wordforms, which can make a mess of your data. If you are not importing into a new FieldWorks project, be sure you [back up your data](../../User_Interface/Menus/File/Backup_and_Restore/Back_up_this_Project.md) prior to import.

- *Before* you begin, on the [Help](../../User_Interface/Menus/Help/Help_overview.md) menu point to **Resources** and then click **Technical Notes on LinguaLinks Import**. You will need information contained in this document during the process.

To import *LinguaLinks* data (`.xml` file), do the following:

1.  In *LinguaLinks*, [prepare the LinguaLinks data](Prepare_Lingualinks_data.md).

2.  In FieldWorks Language Explorer, [stop the parser](../../User_Interface/Menus/Parser/Start_or_Stop_Parser.md), if it is running.

3.  On the **File** menu, point to **Import**, and then click **LinguaLinks Data**.

    The **Import LinguaLinks Data** dialog box appears.

4.  Click **Browse** and then choose the LinguaLinks file you exported.

    The path and file name appear in the **LinguaLinks XML file** box and a list of languages appears in the **LL Language Definition** column.

5.  In the **Language mapping** pane, click a language that does not have a writing system listed in the **FW Writing System** column, and then click **Specify**.

    The [Specify FieldWorks writing system](Specify_language_mapping_dialog_box.md) dialog box appears.

    - In the **Specify FieldWorks writing system** dialog box, specify the appropriate writing system and encoding converter.

6.  Repeat step **5** until a FieldWorks writing system and encoding converter (if necessary) are specified for each item in the **LL Language Definition** column and the **Import** button becomes available.

7.  Click **Import**.

    A **LinguaLinks Import progress** box appears indicating the status of the import process. When completed, the **LinguaLinks Import Successful** message box appears.

8.  Click **OK**.

## Related topics
[Import overview](Import_overview.md)

[Writing System files](../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/Writing_System_files.md)
