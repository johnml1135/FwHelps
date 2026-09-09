---
title: "Linked files in backup are older"
source_title: "Linked files in backup are older"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "File"
  - "Backup and Restore"
  - "Linked Files in backup are older"
source: "User_Interface/Menus/File/Backup_and_Restore/Linked_files_in_backup_are_older.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/File/Backup_and_Restore/Linked_files_in_backup_are_older.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Linked Files:Linked Files in backup are older"
related:
  - "Backup and Restore overview -> Backup_and_Restore_overview.md"
  - "Backup files -> Backup_files.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:6507aa180b069cc0"
---

# Linked files in backup are older

*User Interface › Menus › File › Backup and Restore*

When you [back up a project](Back_up_this_Project.md), you can also include files that are in a **Linked Files** [folder](Folder_Structure.md). When you [restore a project](Restore_a_project.md) from a backup file that includes the **Linked Files** folder, that folder and the current **Linked Files** folder usually have files with the same name. For these files, the date and time stamp are compared.

If one or more files in the current folder are *newer* than the ones in the backup file, then the **Linked Files in backup are older** question box appears.

Do one of the following:

- To *not* overwrite newer files with older files, select **Keep newer files in the folder**, and then click **OK**.

- To use all the files in the backup file, even if some are older than what is in the current **Linked Files** folder, click **Use the older files from the backup**, and then click **OK**.

> [!IMPORTANT]
>
> - The **Cancel** button does *not* stop the restore operation. The restoration continues, but *without* restoring the linked files. In this case, check each link to see if it displays or plays the desired file; manually replace incorrect files to correct any problems you find.

## Related topics
[Backup and Restore overview](Backup_and_Restore_overview.md)

[Backup files](Backup_files.md)
