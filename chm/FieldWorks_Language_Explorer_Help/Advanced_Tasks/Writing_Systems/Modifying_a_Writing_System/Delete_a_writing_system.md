---
title: "Delete a writing system"
source_title: "Delete a writing system"
breadcrumb:
  - "Advanced Tasks"
  - "Writing Systems"
  - "Modifying a Writing System"
  - "Delete a writing system"
source: "Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Delete_a_writing_system.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Delete_a_writing_system.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Delete:Writing system"
  - "Writing System:Delete a writing system"
  - "Project:Writing system"
  - "Delete"
  - "Delete a writing system"
  - "WritingSystemStore"
  - "WritingSystemRepository"
related:
  - "Modifying a writing system overview -> Modifying_a_writing_system_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:b0ae5b430ea1f3de"
---

# Delete a writing system

*Advanced Tasks › Writing Systems › Modifying a Writing System*

Read the ![](../../../assets/images/Important_Icon.gif) **Important** information below.

If you are sure you want to continue, do these steps:

1.  [Back up](../../../User_Interface/Menus/File/Backup_and_Restore/Back_up_this_Project.md) the project if you are *not* collaborating (*recommended*).

2.  [Open](Open_Writing_System_Properties_dlgbox.md) the **Writing System Properties** dialog box.

3.  Do one of these steps:

    - Right-click the writing system, and then click **Delete** \<writing system\>.

    - Click the ![](../../../assets/images/Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Add_Button.png) (Add) button and then click **View hidden Writing System**. If the writing system you want to delete is in the list, click it. Then, click **Delete** if the button is available.

<!-- -->

4.  If a ![](../../../assets/images/Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/WarningIcon.png) **Delete Writing System** warning box appears and you are sure, click **Delete**.

5.  Click **OK** to close the **Writing System Properties** dialog box and delete the writing system.

> [!IMPORTANT]
>
> - [Discuss](../../../Basic_Tasks/Collaborating_with_Others/Send_Receive_considerations.md) deletion if you *are* collaborating using [Send/Receive](../../../Basic_Tasks/Collaborating_with_Others/Send_Receive_overview.md).
>
> - Here is what happens when you delete a writing system:
>
> - - *All data* that use it, *including* [embedded](../../../User_Interface/Menus/Format/select_a_writing_system.md) data, are permanently deleted. Its [writing system file](../Add_a_new_writing_system/Writing_System_files.md) *remains* in the **WritingSystemRepository**, but is deleted from the **WritingSystemStore**.
>
> Exception: If the writing system you deleted was used as *both* a vernacular and analysis writing system.
>
> Example: Suppose a project had Sena as both a vernacular and analysis writing system. If you [hide](Hide_or_show_a_writing_system.md) or delete Sena from the list of analysis writing systems, Sena will no longer appear in the list of writing systems in the **Analysis Writing Systems Properties** dialog box. None of the fields that use analysis writing systems will display that writing system or any data that use it, unless it was embedded in another writing system.
>
> Then, if you later delete Sena from the list of vernacular writing systems, all the data that use Sena are deleted from all fields, including embedded data.
>
> - In the **Hidden Writing Systems** dialog box, the **Delete** button is *not* available if the writing system is only in the *other* **Writing Systems** [pane](../Add_a_new_writing_system/About_Writing_Systems.md) list (vernacular or analysis).
>
> - A ![](../../../assets/images/Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/WarningIcon.png) **Delete Writing System** warning box appears where there are data that will be deleted, in addition to the writing system file.
>
> - Consider [merging](Merge_writing_systems.md) writing systems. Then data are appended to other existing data and are preserved to the extent that the font can display it.
>
> - There must be at least one vernacular and one analysis [writing system](../Add_a_new_writing_system/About_Writing_Systems.md).
>
> The English version of FLEx always adds **English** to the analysis writing systems, so that you can view the English content in the standard lists.
>
> You can add other analysis writing systems for your work and you can [change the user interface language](../../../User_Interface/Menus/Tools/Options/Change_Interface_Language.md), but do *not delete* **English**.

## Related topics
[Modifying a writing system overview](Modifying_a_writing_system_overview.md)
