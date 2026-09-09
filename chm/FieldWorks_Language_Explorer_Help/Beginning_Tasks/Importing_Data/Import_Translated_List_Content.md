---
title: "Import Translated List Content"
source_title: "Import Translated List Content"
breadcrumb:
  - "Beginning Tasks"
  - "Importing Data"
  - "Import Translated List Content"
source: "Beginning_Tasks/Importing_Data/Import_Translated_List_Content.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Beginning_Tasks/Importing_Data/Import_Translated_List_Content.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Lists"
  - "Import:Translated List Content"
  - "Import Translated List Content"
  - "Localization:Import Translated List Content"
  - "Translated List"
  - "Translated List:Import Translated List Content"
  - "List:Import Translated List Content"
  - "List:Translated Lists"
related:
  - "Change the user interface language -> ../../User_Interface/Menus/Tools/Options/Change_Interface_Language.md"
  - "File menu overview -> ../../User_Interface/Menus/File/File_overview.md"
  - "Import Translated Grammatical Category Content -> Import_Translated_Grammatical_Category_Content.md"
  - "Import overview -> Import_overview.md"
  - "Writing System files -> ../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/Writing_System_files.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:4b423b538a78bfe1"
---

# Import Translated List Content

*Beginning Tasks › Importing Data*

If you have files that contain one or more [localized lists](../../User_Interface/Menus/Tools/Options/User_interface_languages_for_lists.md), you can import the lists into the current language project. The translated list file could be one that someone previously edited in **Lists** and then [exported](../../User_Interface/Menus/File/Export/Export_Translated_Lists.md) for you to import.

If your *default* analysis [writing system](../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md) matches the language of the translated lists, the available translated lists you import will appear in that language.

1.  In the Navigation Pane, click **Lexicon Edit** or another view that does *not* display list content. This will help prevent a delay or other problems as FLEx repaints the screen that is displaying a list.

2.  Consider that you might want to [back up the project](../../User_Interface/Menus/File/Backup_and_Restore/Back_up_this_Project.md).\
    See [Send/receive considerations](../../Basic_Tasks/Collaborating_with_Others/Send_Receive_considerations.md) if you use Send/Receive with others.

3.  [Stop the parser](../../User_Interface/Menus/Parser/Start_or_Stop_Parser.md), if it is running (*recommended*).

4.  Make sure all the analysis writing systems that are in the file are defined for the language project. [Add writing systems](../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md), as necessary.

5.  On the **File** menu, point to **Import**, and then click **Translated List Content**.

    The **Open Translated Lists File** dialog box appears.

6.  Click the file (\***.xml** or \***.zip**) with the writing system and content you want to import, and then click **Open**.

    The list or lists are updated to include content in the additional writing systems. Specifically, the English name of each list items must match before any content in imported into that list item. Typically if you are currently displaying a list, you will see the center pane of the list flash or wiggle while the list items update. During this time, you cannot click any of the list items in that list or click another area or list in the Navigation Pane. This could take a few minutes or longer.

7.  After the import is finished, examine the lists and list items.

If the results are not satisfactory, [restore the project](../../User_Interface/Menus/File/Backup_and_Restore/Restore_a_project.md). Then, do *one* of the following:

1.  - Manually edit the file, and then import it again.

    - Edit the list(s) in the *source* language project, [export the list(s)](../../User_Interface/Menus/File/Export/Export_Translated_Lists.md), and then import the updated file again into the *destination* project.

> [!IMPORTANT]
>
> - Sources of such files include:
>
> - - [Language packs](../../User_Interface/Menus/Tools/Options/Language_Packs_example.md) you *installed* with the master installer.
>
>   - Download them from <a href="https://software.sil.org/fieldworks/download/localizations/" target="_blank" title="https://software.sil.org/fieldworks/download/localizations/">https://software.sil.org/fieldworks/download/localizations/</a>.
>
>   - Request files from `FLEx_Localization@sil.org`.
>
>   - Request [technical support](../../Overview/Technical_support.md).

> [!NOTE]
>
> - LocalizedLists files are *installed* on your computer at these locations, but you normally will not need to do anything with them: C:\Program Files\SIL\FieldWorks 9\Templates

## Related topics
[Change the user interface language](../../User_Interface/Menus/Tools/Options/Change_Interface_Language.md)

[File menu overview](../../User_Interface/Menus/File/File_overview.md)

[Import Translated Grammatical Category Content](Import_Translated_Grammatical_Category_Content.md)

[Import overview](Import_overview.md)

[Writing System files](../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/Writing_System_files.md)
