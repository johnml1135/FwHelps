---
title: "Restore a project"
source_title: "Restore a project"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "File"
  - "Backup and Restore"
  - "Restore a project"
source: "User_Interface/Menus/File/Backup_and_Restore/Restore_a_project.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/File/Backup_and_Restore/Restore_a_project.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Restore"
  - "Restore:Restore a project"
  - "Restore:Restore a FW6 backup in FW7 or later"
  - "Replace Existing Project (Restore)"
related:
  - "Backup and \n Restore overview -> Backup_and_Restore_overview.md"
  - "Migrate \n FieldWorks 6.0.6 (or earlier) Project dialog box -> ../../../../Overview/Migrate_FieldWorks_6.0.4_(or_earlier)_Projects.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:47ac4329784be0c2"
---

# Restore a project

*User Interface › Menus › File › Backup and Restore*

To restore from a [backup file](Backup_files.md), do the steps in this topic (See ![](../../../../assets/images/Important_Icon.gif) **Important** below), *or* see [Copy a FieldWorks Project from another computer](Copy_a_FieldWorks_project_from_another_computer.md).

If you have used [Send/Receive](../../../../Basic_Tasks/Collaborating_with_Others/Send_Receive_overview.md) to [collaborate](../../../../Basic_Tasks/Collaborating_with_Others/Collaborating_with_Others_overview.md) with other users, you can *only* restore the project under a *different name*.

1.  If the backup file is stored on a removable media (for example, a CD-RW or thumb drive), insert it in the drive.

2.  Open the **Restore a Project** dialog box in any of the following ways:

    - On the **File** menu, point to **Project Management**, and then click **Restore a Project**.

    - Click **Restore a project from a backup file** in the [Language Explorer](../../../../Overview/Welcome_to_FieldWorks.md) or [Unable to Open Project](../Unable_to_Open_Project.md) dialog box.

The **Backup file to restore** area displays the file most recently backed up, and other versions you can select. **Includes** lists which **Additional files to restore** are included in the selected back up file.

3.  If **Default backup folder** is selected, do the following in the **Backup version to restore** pane:

    - Click the **Project** down arrow to select the desired project.

    - In the **Version** box, click the version you want to restore, based on the date/time stamp, or comment.

4.  To restore from a *different* [file, drive or folder](Backup_files.md), click **Another location**, and then click **Browse**.

    The **Browse for FieldWorks Language Project backup file** dialog box opens. Removable drives, such as a USB flash drive must be inserted or connected to the computer.

    - In the dialog box, click the project to restore, and then click **Open**.

5.  In the **Name of restored project** area, select one of the following:

    - **Original name** to *overwrite* the current project.

    - **Different name**. Edit the name in the box, as needed. (This is necessary if you use [Send/Receive](../../../../Basic_Tasks/Collaborating_with_Others/Send_Receive_considerations.md).)

6.  In the **Additional files to restore** area (Version 7 and later backup files), select (![](../../../../assets/images/CheckedBox.PNG)) or the clear (![](../../../../assets/images/UncheckedBox.PNG)) the check boxes to specify which [folders](Folder_Structure.md) to include in the restored project.

    - If a check box is not available for selection, the corresponding check box was not selected during the [back up](Back_up_this_Project.md), and is *not* in the backup file.

7.  Click **OK**.

    The Language Explorer window closes when the restore operation is working, and opens again when the operation is done. If the **Replace Existing Project** warning box appears, do one of the following:

    - To back up the existing project before the restore operation, select (![](../../../../assets/images/CheckedBox.PNG)) the check box, and then click **Yes**.

    - To restore over the existing project *without* backing it up, clear (![](../../../../assets/images/UncheckedBox.PNG)) the check box, and then click **Yes**.

    - Click **No** to *not* continue with the restore operation. Then, repeat steps above to make different selections in the **Restore a Project** dialog box.

    The [Linked Files folder](LinkedFiles_folder.md) question box, or the [Linked file in backup are older](Linked_files_in_backup_are_older.md) dialog box may appear.

> [!IMPORTANT]
>
> - With FieldWorks versions 7 and later, you can restore backup files from *previous* FieldWorks versions, *if a* pre-version 7 installation of FieldWorks is still installed and functional on your computer. (You can have FieldWorks Version 8 and another previous version (*except* version 7), such as FieldWorks 6.0.6, installed at the same time.)
>
> If you restore a backup file from FieldWorks 6 (or older version) into FieldWorks 7 or later, make sure the proper [folder for external files](../Project_Properties/Project_Properties_Linked_Files_tab.md) is selected. Move or copy files between folders, as needed.
>
> - - Also, the **Data Migration** progress indicator will appear. The migration may take several minutes or more.
>
> - Fonts — To allow each user to have their own font selections, the restored project may have different fonts than were used when the project was backed up. So, after the back up file is restored, open the [Font tab](../../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_Fonts_tab.md) for each writing system to verify that the fonts are set to your own preference.
>
> - Check boxes under **Additional files to restore** match the check boxes in the [Back up this Project](Back_up_this_Project.md) dialog box. Your **Additional files to back up** selections are the *default* selections in **Additional files to restore**.
>
> - With the FieldWorks program not running, you can double-click the backup file (`*.fwbackup`) to start a restore.
>
> <!-- -->
>
> - The **Unable to restore** information box appears for various reasons as described in the information box.

## Related topics
[Backup and Restore overview](Backup_and_Restore_overview.md)

[Migrate FieldWorks 6.0.6 (or earlier) Project dialog box](../../../../Overview/Migrate_FieldWorks_6.0.4_(or_earlier)_Projects.md)
