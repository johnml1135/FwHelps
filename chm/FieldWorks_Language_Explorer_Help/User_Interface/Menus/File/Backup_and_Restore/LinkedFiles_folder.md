---
title: "Linked Files folder question boxes"
source_title: "Linked Files folder question boxes"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "File"
  - "Backup and Restore"
  - "Linked Files folder question boxes"
source: "User_Interface/Menus/File/Backup_and_Restore/LinkedFiles_folder.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/File/Backup_and_Restore/LinkedFiles_folder.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Linked Files:LinkedFiles folder question box"
related:
  - "Backup and Restore overview -> Backup_and_Restore_overview.md"
  - "Delete this Media Link -> ../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/delete_a_sound_movie_file_link.md"
  - "Insert link to file -> ../../../../Basic_Tasks/Creating_Hyperlinks/Insert_a_hyperlink_to_a_file.md"
  - "Remove a hyperlink -> ../../../../Basic_Tasks/Creating_Hyperlinks/Remove_a_hyperlink.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:90524a4b707505e5"
---

# Linked Files folder question boxes

*User Interface › Menus › File › Backup and Restore*

As discussed in [Folder Structure](Folder_Structure.md), the *default* [folder for external files](../Project_Properties/Project_Properties_Linked_Files_tab.md) is the **LinkedFiles** folder. It is one of the subfolders of the *project* folder for the language project. The individual project folders are subfolders of the **Projects** folder.

When you [restore a project](Restore_a_project.md) that has linked files, question boxes may appear if you have a *non*-default folder selected in the [Linked Files](../Project_Properties/Project_Properties_Linked_Files_tab.md) tab.

- If the [folder for external files](../Project_Properties/Project_Properties_Linked_Files_tab.md) in the [backup file](Backup_files.md) was *not* the *default* folder, then the **Linked Files folder** question box appears.

  Do either of following:

  - To change the **Linked Files** folder selection to the *default* `folder`, and try to restore the files there, select **Yes**. Click **OK**.

  - To try to restore the files using the original path (*non*-default folder), select **No, please use original path**. Click **OK**.

    If FieldWorks cannot restore the linked files using the original path, then the **Cannot restore files in the Linked Files folder** question box appears.

    Do either of the following:

    - Select **Thanks, and change the default Linked Files location for this project**. Click **OK**.\
      This is the same as clicking **Yes** in the **Linked Files folder** question box (above). The **Linked Files folder** selection is changed to the default folder. If the files are accessible, they are restored into the default folder structure.

    - Select **No Thanks. Skip** **restoring the linked files**. Click **OK**.\
      The files are not restored.

> [!IMPORTANT]
>
> - [*S*end/Receive](../../Send_Receive/Send_Receive_menu.md) *uses only the default folder*.
>
> - *If the files are not accessible, they are not restored*. For example, suppose the backup file is set to store the linked files on a removable device, but that device is not currently installed.
>
> - Check to make sure links to pictures and other files work, and that media files [play](../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/play_sound_or_movie.md). As necessary, manually copy files to the proper folders, and remove and replace any links that do not work.

## Related topics
[Backup and Restore overview](Backup_and_Restore_overview.md)

[Delete this Media Link](../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/delete_a_sound_movie_file_link.md)

[Insert link to file](../../../../Basic_Tasks/Creating_Hyperlinks/Insert_a_hyperlink_to_a_file.md)

[Remove a hyperlink](../../../../Basic_Tasks/Creating_Hyperlinks/Remove_a_hyperlink.md)
