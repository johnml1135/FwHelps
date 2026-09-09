---
title: "Export a lexicon (lexeme-based SFM)"
source_title: "Export a lexicon (lexeme-based SFM)"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "File"
  - "Export"
  - "Export a lexicon (Stem-based MDF)"
source: "User_Interface/Menus/File/Export/Export_a_lexicon_MDF.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/File/Export/Export_a_lexicon_MDF.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Lexicon:Export a lexicon"
  - "Export:Lexicon (MDF)"
related:
  - "Dictionary Layouts -> ../../Tools/Configure_Dictionary/Dictionary_views.md"
  - "Export overview -> Export_overview.md"
  - "File menu overview -> ../File_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:fba0a7d9cc2c00f7"
---

# Export a lexicon (lexeme-based SFM)

*User Interface › Menus › File › Export*

You can export a lexicon into a [lexeme-based](../../Tools/Configure_Dictionary/Dictionary_views.md) MDF standard format. Subentries are exported as separate entries. The exported file actually includes writing system designators as part of the SFM code, so it is not pure MDF.

1.  Make sure the lexical data is ready to be exported. For example, you may need to use the [FieldWorks Project Utilities](../../Tools/Language_Project_Utilities_overview.md) to reassign the homograph numbers.

2.  With a **Lexicon** tool selected in the navigation pane, on the **File** menu, click **Export**.

    The **Export** dialog box appears.

3.  In the dialog box, do the following:

    - In the left pane, select the export method **Full Lexicon (lexeme-based) SFM**.

    - The **Show in folder** check box is selected (![](../../../../assets/images/CheckedBox.PNG)) by default. Then after export, the folder that has the export file opens and that file is selected. If you do not want this to happen, clear (![](../../../../assets/images/UncheckedBox.PNG)) this check box.

    - Click **Export**.

    The **Export to SFM** dialog box appears.

4.  In the dialog box, do the following:

    - Navigate to the folder where you want to save the exported data.

    - Enter a name for the file in the **File name** box.

    - Make sure **Standard Format files (\*.db)** appears in the **Save as type** box.

    - Click **Save**.

The **Exporting Full Lexicon (lexeme-based)** progress box appears. When the export is finished, the progress box and the **Export** dialog box close automatically.

> [!TIP]
>
> - If some characters do not appear correctly in the exported file, make sure the program you are using to read the file is set to display Unicode UTF-8.

## Related topics
[Dictionary Layouts](../../Tools/Configure_Dictionary/Dictionary_views.md)

[Export overview](Export_overview.md)

[File menu overview](../File_overview.md)
