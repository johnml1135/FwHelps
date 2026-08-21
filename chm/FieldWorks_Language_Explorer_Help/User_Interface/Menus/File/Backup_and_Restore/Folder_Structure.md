---
title: "Folder Structure"
source_title: "Folder Structure"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "File"
  - "Backup and Restore"
  - "Folder Structure"
source: "User_Interface/Menus/File/Backup_and_Restore/Folder_Structure.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/File/Backup_and_Restore/Folder_Structure.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Movie or sound file"
  - "Folder Structure"
  - "Back up"
  - "Files:Folder Structure"
  - "SupportingFiles folder"
related:
  - "Backup and Restore overview -> Backup_and_Restore_overview.md"
  - "Backup folder -> Backup_folder.md"
  - "Creating Hyperlinks overview -> ../../../../Basic_Tasks/Creating_Hyperlinks/Creating_Hyperlinks_overview.md"
  - "Delete a FieldWorks project -> ../Delete_Fieldworks_project.md"
  - "Delete a link to a media file -> ../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/delete_a_sound_movie_file_link.md"
  - "Delete a picture -> ../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Delete_a_picture.md"
  - "Files that FieldWorks does not back up -> Files_that_FieldWorks_does_not_back_up.md"
  - "Linked Files tab -> ../Project_Properties/Project_Properties_Linked_Files_tab.md"
  - "Move or Copy Files dialog box -> ../Project_Properties/Move_or_Copy_Files.md"
  - "Open a FieldWorks project -> ../Delete_Fieldworks_project.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:d849ea1327fac5fe"
---

# Folder Structure

*User Interface › Menus › File › Backup and Restore*

For FieldWorks Version 9, there is a **Projects** folder, typically at C:\ProgramData\SIL\FieldWorks\Projects.

Otherwise, the folder is at the location you set in the [Project Locations](../Project_Locations.md) dialog box. You see the path as the **Location** in the [General](../Project_Properties/Project_Properties_General_tab.md) tab.

Inside the **Projects** folder is one folder for *each* language project, such as **Sena 3**.

Inside *each* of these folders is another set of folders; one of them is called **LinkedFiles**. It is the *default* folder for [linked files](../Project_Properties/Project_Properties_Linked_Files_tab.md) (the *only* location used by [Send/Receive](../../Send_Receive/Send_Receive_menu.md)). Folders in the **LinkedFiles** folder correspond to **Additional files to back up** options in the [Back up the Project](Back_up_this_Project.md) dialog box, and **Additional files to restore** options in the [Restore a Project](Restore_a_project.md) dialog box:

<table width="100%">
<tbody>
<tr style="height: 38px;">
<th style="width: 30%"><p>"Additional files to back up/restore" option</p></th>
<th style="width: 30%"><p>Corresponding folders</p></th>
<th style="width: 40%"><p>Does FieldWorks put files in the folder?</p></th>
</tr>
&#10;<tr style="height: 38px;">
<td style="width: 30%"><p><strong>Configuration settings</strong></p></td>
<td style="width: 30%"><p><strong>ConfigurationSettings</strong></p></td>
<td style="width: 40%"><p>Yes</p></td>
</tr>
<tr style="height: 94px;">
<td style="width: 30%"><p><strong>Linked files</strong></p></td>
<td style="width: 30%"><p><strong>LinkedFiles</strong> subfolders:</p>
<ul>
<li><p><strong>AudioVisual</strong></p></li>
<li><p><strong>Others</strong></p></li>
<li><p><strong>Pictures</strong></p></li>
</ul></td>
<td style="width: 40%"><p>Yes, <em>if</em> you clicked <strong>Move Files</strong> or <strong>Copy Files</strong> in the <strong>Move or Copy Files</strong> dialog box.<br />
No, <em>if</em> you clicked <strong>Leave Files</strong>.</p></td>
</tr>
<tr style="height: 38px;">
<td style="width: 30%"><p><strong>Customized spelling dictionary files</strong></p></td>
<td style="width: 30%"><p><strong>SpellingDictionaries</strong></p></td>
<td style="width: 40%"><p><em>Yes, if</em> you select this check box, then &lt;name&gt;<strong>.exc</strong> files for <em>only</em> majority languages (typically used as analysis writing systems).<br />
(Spelling for vernacular languages are stored internally as seen in the <a href="../../../../Using_Tools/Texts_%26_Words_tools/Word_list_overview.md">word list</a> and <strong>Spelling Status</strong> fields.)</p></td>
</tr>
<tr style="height: 38px;">
<td style="width: 30%"><p><strong>Supporting files</strong></p></td>
<td style="width: 30%"><p><strong>SupportingFiles</strong></p></td>
<td style="width: 40%"><p>No. Manually copy files into this folder.</p></td>
</tr>
</tbody>
</table>

> [!IMPORTANT]
>
> - **ConfigurationSettings** folder:\
>   This folder stores copies of files that specify your field visibility settings, column displays, and **Dictionary** and **Document** view configurations, interlinear configurations, and others.
>
> - For media files (pictures, video, sound files, and so on) which you did *not* already [move or copy](../Project_Properties/Move_or_Copy_Files.md) into the appropriate **LinkedFiles** subfolder (or into *custom* *subfolders*), *manually* *copy* them into the appropriate folders and subfolders.
>
> - - **AudioVisual** folder:\
>     This folder stores sound or movie files that you [linked](../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Insert_link_to_sound_or_movie.md) to [Pronunciations](../../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Pronunciation_field.md).
>
>   - **Others** folder:\
>     This folder stores text files or spread sheets, and any other files you open with hyperlinks inserted with the [Insert](../../Insert/Insert_overview.md) menu command **Link to File**.
>
>   - **Pictures** folder:\
>     This folder stores pictures you [inserted](../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Insert_a_picture.md) into [lexical senses](../../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Sense_field.md).
>
> - **SupportingFiles** folder: Use this folder for files that have no links to them, such as *fonts,* *keyboards*, or *encoding converters*. You could also store files here that you plan to use in the future.
>
> This folder is included in the **Send/Receive Project** operation. Files in that folder are subject to the 1 MB size limit. Merging of files can only happen if the filename extension is known.
>
> - If you moved your project folder to another location on your hard drive, then the default path above will not apply to you.

## Related topics
[Backup and Restore overview](Backup_and_Restore_overview.md)

[Backup folder](Backup_folder.md)

[Creating Hyperlinks overview](../../../../Basic_Tasks/Creating_Hyperlinks/Creating_Hyperlinks_overview.md)

[Delete a FieldWorks project](../Delete_Fieldworks_project.md)

[Delete a link to a media file](../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/delete_a_sound_movie_file_link.md)

[Delete a picture](../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Delete_a_picture.md)

[Files that FieldWorks does not back up](Files_that_FieldWorks_does_not_back_up.md)

[Linked Files tab](../Project_Properties/Project_Properties_Linked_Files_tab.md)

[Move or Copy Files dialog box](../Project_Properties/Move_or_Copy_Files.md)

[Open a FieldWorks project](../Delete_Fieldworks_project.md)
