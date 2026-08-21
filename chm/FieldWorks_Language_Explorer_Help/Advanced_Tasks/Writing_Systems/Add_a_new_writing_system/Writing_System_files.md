---
title: "Writing System files"
source_title: "Writing System files"
breadcrumb:
  - "Advanced Tasks"
  - "Writing Systems"
  - "Add a new writing system"
  - "Writing system files"
source: "Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/Writing_System_files.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/Writing_System_files.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Writing System:Files"
  - "Writing System"
  - "Writing System:WritingSystemRepository"
  - "Writing System:WritingSystemStore"
  - "File:Writing System files"
  - "Language definition files"
  - "Options dialog box:Writing System files"
  - "WritingSystemStore"
  - "WritingSystemRepository"
  - "Global:Global Writing System Changed"
  - "Global:Global Writing System Store"
related:
  - "Add a new writing system overview -> Add_a_new_writing_system_overview.md"
  - "Writing Systems overview -> ../Writing_Systems_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:17b611309a588e28"
---

# Writing System files

*Advanced Tasks › Writing Systems › Add a new writing system*

An \*.ldml writing system file contains data that defines a [writing system](../Modifying_a_Writing_System/Using_the_Writing_System_Properties_dialog_box.md).

FieldWorks (FLEx) works with writing system files from these folders:

- **WritingSystemStore** - there is one for *each* *project* in the **Projects** folder.

- **WritingSystemRepository** - there is *one* on your computer.

It is the main repository of writing system files on your computer. It can be used by multiple FLEx projects and by other programs. Writing system files may be copied from here into the **WritingSystemStore** folder for your project. If one you need is not available to [select](../Modifying_a_Writing_System/Using_the_Writing_System_Properties_dialog_box.md) (![](../../../assets/images/CheckedBox.PNG)) so you [add](Add_a_new_writing_system.md) one, it is added in the **WritingSystemStore** folder and replicated in this folder. Further, if you modify a writing system in a project, those changes update the files in both folders.

- If your computer is connected to the internet when you create a new writing system, FLEx will look for writing system files in the **SIL Locale Data Repository** (**SLDR**). It is the main SIL repository of writing system definitions. **See Also:** [Collection of Locale Data](../Modifying_a_Writing_System/Collection_of_Locale_data.md).

Therefore, you do not need to re-define a writing system for each project. You can use the writing system stored in the **WritingSystemRepository** folder or in the **SLDR**. Using the same writing system helps ensure that they are identical for different projects.

## Folder Locations

- The **General** [tab](../../../User_Interface/Menus/File/Project_Properties/Project_Properties_General_tab.md) of the **FieldWorks Project Properties** dialog box displays the path (URL) to your **Projects** folder.

- The **WritingSystemRepository** folder location: C:\ProgramData\SIL\WritingSystemRepository

## What you can do

- If a writing system was changed in another project and you want those changes to appear in the current project, you can use the **Update** in the **Vernacular Writing System Properties** dialog box or **Analysis Writing System Properties** dialog box. **See:** [Modifying a writing system overview](../Modifying_a_Writing_System/Modifying_a_writing_system_overview.md) or [Update a writing system](../Modifying_a_Writing_System/Update_a_writing_system.md).

> [!TIP]
>
> - If you have already defined a writing system on one computer, you can copy the writing system file to another computer after you install FieldWorks but before you [create a new FieldWorks project](../../../User_Interface/Menus/File/Create_a_new_Fieldworks_project.md) in which you intend to select the writing system.
>
> - The [writing system code](Writing_system_codes.md) appears as the **Code** in the **General** [tab](../Modifying_a_Writing_System/Writing_System_Properties_General_tab.md) of the **Writing System Properties** dialog box.

## Related topics
[Add a new writing system overview](Add_a_new_writing_system_overview.md)

[Writing Systems overview](../Writing_Systems_overview.md)

## Related links
<a href="https://scriptsource.org/cms/scripts/page.php?item_id=entry_detail&amp;uid=e9b9varyee" target="_blank" title="https://scriptsource.org/cms/scripts/page.php?item_id=entry_detail&amp;uid=e9b9varyee">About the SIL Locale Data repository (SLDR)</a>

<a href="https://en.wikipedia.org/wiki/Locale_(computer_software)" target="_blank" title="https://en.wikipedia.org/wiki/Locale_(computer_software)">Locale (Computer Software)</a>

<a href="http://cldr.unicode.org/" target="_blank" title="http://cldr.unicode.org/">Unicode CLDR Project</a>
