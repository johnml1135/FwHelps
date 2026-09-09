---
title: "Copy a FieldWorks project from another computer"
source_title: "Copy a FieldWorks project from another computer"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "File"
  - "Backup and Restore"
  - "Copy a FieldWorks project from another computer"
source: "User_Interface/Menus/File/Backup_and_Restore/Copy_a_FieldWorks_project_from_another_computer.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/File/Backup_and_Restore/Copy_a_FieldWorks_project_from_another_computer.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "FieldWorks project"
  - "Copy:FieldWorks project from another computer"
  - "Files:Copy a FieldWorks project from another computer"
  - "Share:Copy a FieldWorks project from another computer"
related:
  - "Backup and Restore overview -> Backup_and_Restore_overview.md"
  - "Collaborating with Others overview -> ../../../../Basic_Tasks/Collaborating_with_Others/Collaborating_with_Others_overview.md"
  - "Folder structure -> Folder_Structure.md"
  - "Project Locations dialog box -> ../Project_Locations.md"
  - "Unable to Open Project dialog box -> ../Unable_to_Open_Project.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:7b43522621a8327e"
---

# Copy a FieldWorks project from another computer

*User Interface › Menus › File › Backup and Restore*

1.  [Back up](Back_up_this_Project.md) the FieldWorks project on the *source* computer.

    - If the *source* computer uses FieldWorks 6 or earlier: Select the **Include a human readable (XML) backup** check box.

2.  If needed, install the same or a newer version of FieldWorks on the *destination* computer.

3.  Copy the [backup file](Backup_files.md) from the *source* computer to the [backup folder](Backup_folder.md) on the *destination* computer.

4.  Copy any [files that were not backed up](Files_that_FieldWorks_does_not_back_up.md) from the *source* computer to the *destination* computer. **See Also:** [Spelling dictionary files](../../../../Basic_Tasks/Spell_Checking/dictionary_files.md).

5.  Start FieldWorks Language Explorer on the *destination* computer.

    - If the **Unable to Open Project** dialog box appear, click **Restore**. Otherwise, on the **File** menu, point to **Project Management**, and then click **Restore a Project**.

      The **Restore a Project** dialog box appears.

    - [Restore the project](Restore_a_project.md) from the backup file that you copied from the *source* computer.

    6.  In the restored project, verify that functions which depend on external files continue to work. Here are some examples:

    - [Sound and video files](../../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/media_file_field.md), [pictures](../../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Picture_field.md) or other files accessed by [hyperlinks](../../../../Basic_Tasks/Creating_Hyperlinks/Creating_Hyperlinks_overview.md).

    - [Fonts](../../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_Fonts_tab.md), [keyboards](../../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_Keyboard_tab.md), [encoding converters](../../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_Converters_tab.md), and so on.

    - Make sure the correct [spelling dictionary file](../../../../Basic_Tasks/Spell_Checking/dictionary_files.md) is [selected](../../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_General_tab.md) for each writing system.

###  Note - Reasons to copy

- Make a project on a computer consistent with the master version from another computer.

- Copy a project to a new computer. (You planned in advance to make the copy.)

- Copy a project to a new computer after a hardware failure. (You did not plan in advance to make the copy.)

  - If you back up the local disk of a computer regularly, we recommend that you include the project data folders.

  - The **Project Locations** dialog box displays the parent folder for FieldWorks project data folders.

  - To recover from a hardware failure, if you use a backup of the local disk that includes the project data folders, you will not need to restore projects individually from FieldWorks backup files.

## Related topics
[Backup and Restore overview](Backup_and_Restore_overview.md)

[Collaborating with Others overview](../../../../Basic_Tasks/Collaborating_with_Others/Collaborating_with_Others_overview.md)

[Folder structure](Folder_Structure.md)

[Project Locations dialog box](../Project_Locations.md)

[Unable to Open Project dialog box](../Unable_to_Open_Project.md)
