---
title: "Export filtered lexicon (LIFT)"
source_title: "Export filtered lexicon (LIFT)"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "File"
  - "Export"
  - "Export filtered lexicon (LIFT)"
source: "User_Interface/Menus/File/Export/Export_filtered_lexicon_LIFT.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/File/Export/Export_filtered_lexicon_LIFT.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Lexicon:Export a lexicon"
  - "Export:LIFT lexicon"
  - "Export:Filtered lexicon (LIFT)"
  - "Export:Lexicon (WeSay)"
  - "LIFT lexical data"
  - "Export"
  - "Export:Export a lexicon (LIFT)"
  - "WeSay"
related:
  - "Export overview -> Export_overview.md"
  - "FieldWorks \n Project Utilities -> ../../Tools/Language_Project_Utilities_overview.md"
  - "File menu overview -> ../File_overview.md"
  - "Import \n LIFT lexical data -> ../../../../Beginning_Tasks/Importing_Data/import_lift_lex.md"
fw_help_version: "9.3"
page_heading: "Export a filtered lexicon (LIFT)"
type: "topic"
content_hash: "sha256:8dc6eb0bfb176e17"
---

# Export filtered lexicon (LIFT)

*User Interface › Menus › File › Export*

The **Filtered Lexicon LIFT 0.13 XML** export method exports data stored in **Lexicon Edit** fields. WeSay, [Lexique Pro](Export_to_Lexique_Pro.md) and FLEx can open \*.lift files.

1.  Make sure the lexical data is ready to be exported.

2.  [Filter the lexical data](../../../../Basic_Tasks/Filtering_data/filter_data.md) to limit which entries are exported (*optional*).

3.  On the **File** menu, click **Export**.

4.  In the **Export** dialog box, do the following:

<!-- -->

1.  - Click **Filtered Lexicon LIFT 0.13 XML**.

    - Clear (![](../../../../assets/images/UncheckedBox.PNG)) the **Show in folder** check box (selected by default) if you do *not* want the folder that has the export file to open after the export process is done.

    - Clear (![](../../../../assets/images/UncheckedBox.PNG)) the **Copy pictures and media file to the export folder** check box (selected by default) if you do *not* need to include pictures and media (audio, and so on) as part of the export file set.

    - Click **Export**.

<!-- -->

5.  In the **Browse for Folder** dialog box, do the following:

    - Navigate to the folder where you want to save the data. If necessary, click **Make New Folder**, and then enter a name for the new folder.

    - Click **OK**.

    - If there is an existing file in the selected folder, the **LIFT Export** message box appears. Click **OK** to overwrite the file, *or* click **Cancel** and then choose a different folder.

A progress box appears. When the export is finished, the progress box and the **Export** dialog box close automatically.

> [!IMPORTANT]
>
> - [Send/Receive](../../../../Basic_Tasks/Collaborating_with_Others/Send_Receive_overview.md) is the *recommended* way to exchange lexical data with WeSay and other FLEx users. It uses a [Chorus](../../../../Glossary_of_Terms.md#C) repository.
>
> - LIFT (*Lexicon Interchange FormaT*) files contain primarily *lexical* data stored in **Lexicon Edit** fields, with some exceptions (such as some **Grammatical Info Details** fields). Consider the following if you will exchange lexical data with LIFT exports/imports:
>
>   *Before* you share any LIFT files, you might want to give them
>
>   - a [backup file](../Backup_and_Restore/Backup_files.md) because it contains more data
>
>   - [other files that are not backed up](../Backup_and_Restore/Files_that_FieldWorks_does_not_back_up.md).
>
>   Then when your LIFT files are imported, the other FLEx user will have a more complete language project.

## Related topics
[Export overview](Export_overview.md)

[FieldWorks Project Utilities](../../Tools/Language_Project_Utilities_overview.md)

[File menu overview](../File_overview.md)

[Import LIFT lexical data](../../../../Beginning_Tasks/Importing_Data/import_lift_lex.md)

## Related links
<a href="https://software.sil.org/wesay/" target="_blank" title="https://software.sil.org/wesay/">https://software.sil.org/WeSay/</a>
