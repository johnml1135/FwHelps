---
title: "Backup files"
source_title: "Backup files"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "File"
  - "Backup and Restore"
  - "Backup files"
source: "User_Interface/Menus/File/Backup_and_Restore/Backup_files.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/File/Backup_and_Restore/Backup_files.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Backup"
  - "Backup:Backup files"
related:
  - "Backup and Restore overview -> Backup_and_Restore_overview.md"
  - "Backup folder -> Backup_folder.md"
  - "FieldWorks project names -> FieldWorks_project_names.md"
  - "Project Locations -> ../Project_Locations.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:9e2a6cae45e243db"
---

# Backup files

*User Interface › Menus › File › Backup and Restore*

A FieldWorks project consists of data related to a particular language and the people who speak it.

A backup file is a compressed file containing project data. It might contain additional files related to the project.

All FieldWorks programs can store data in a project, [back up a project](Back_up_this_Project.md), or [restore a project](Restore_a_project.md) from a backup file.

FieldWorks uses built-in Zip software to back up and restore projects.

## Backup file contents

- An \*.fwbackup file is a backup file. (An \*.fwdata file is an XML file which contains the project data.)

- The **BackupSettings** subfolder contains the BackupSettings.xml file.

  The **Restore a Project** dialog box displays some of the settings for the backup file that you selected.

  However, the settings in the backup file do not replace the current backup settings for the project.

- The WritingSystemStore subfolder contains writing system files.

- Other subfolders might contain additional files if you select check boxes in the **Additional files to back up** area in the **Back up this Project** dialog box. **See Also:** [Folder Structure](Folder_Structure.md).

## Backup file names

In FieldWorks 7 or later, each backup file has a unique name that consists of:

- [project name](FieldWorks_project_names.md)

- date and time when the project was backed up (yyyy-mm-dd hhmm)

- optional short description of the version from the **Comment** box in the **Back up this Project** dialog box

- .fwbackup file name extension.

**Example:** "![](../../../../assets/images/User_Interface/Menus/File/FileIcon.png) `Sena 3 2017-5-02 1015 with sound files.fwbackup".`

> [!TIP]
>
> - You can double-click the backup file (`*.fwbackup`) to start a restore operation while the FieldWorks program is not running. This is similar to using **Restore** in the [Unable to Open Project](../Unable_to_Open_Project.md) dialog box.
>
> - If you change the filename extension from \*.fwbackup to \*.zip, your computer will recognize the file as a Zip file. Then, you can manually use your Zip software to explore the folder contents. While this is not usually necessary, you might, for example, want to copy a file without restoring the project.

## Related topics
[Backup and Restore overview](Backup_and_Restore_overview.md)

[Backup folder](Backup_folder.md)

[FieldWorks project names](FieldWorks_project_names.md)

[Project Locations](../Project_Locations.md)
