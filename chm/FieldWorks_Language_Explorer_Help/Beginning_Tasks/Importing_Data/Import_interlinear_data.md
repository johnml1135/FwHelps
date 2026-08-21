---
title: "Import interlinear data"
source_title: "Import interlinear data"
breadcrumb:
  - "Beginning Tasks"
  - "Importing Data"
  - "Import FieldWorks interlinear FLExText data"
source: "Beginning_Tasks/Importing_Data/Import_interlinear_data.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Beginning_Tasks/Importing_Data/Import_interlinear_data.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Import:FLExText Interlinear data"
  - "Interlinear Media"
  - "Interlinear data"
  - "Media Interlinear"
  - "import"
related:
  - "Import overview -> Import_overview.md"
  - "Import Standard Format Interlinear Texts - Pre-defined Mappings -> Import_Interlinear_SFM/Import_SF_Interlinear_predefined_mappings.md"
  - "Writing System files -> ../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/Writing_System_files.md"
fw_help_version: "9.3"
page_heading: "Import FieldWorks interlinear (FLExText) data"
type: "topic"
content_hash: "sha256:210f957f747f6696"
---

# Import interlinear data

*Beginning Tasks › Importing Data*

FLExText interlinear data was created by a FieldWorks [interlinear export](../../User_Interface/Menus/File/Export/Export_Interlinear.md), or by an export of transcriptions and free translations from SayMore. If the interlinear data you want to import is different, see [Import overview](Import_overview.md) for other import options.

1.  Open the language project into which you will import the interlinear data.

2.  [Back up the project](../../User_Interface/Menus/File/Backup_and_Restore/Back_up_this_Project.md) (recommended).

3.  [Stop the parser](../../User_Interface/Menus/Parser/Start_or_Stop_Parser.md), if it is running.

4.  In the **Navigation Pane**, click **Texts & Words**, and then click **Interlinear Texts**.

5.  If your FLExText data has audio files, on the **Tools** menu, point to **Configure** and then click **Interlinear**.

- Then, select the desired writing system for the **Media** line in the **Configure Interlinear Lines** [dialog box](../../User_Interface/Menus/Tools/Configure_interlinear_lines_dialog_box.md).

6.  On the [File](../../User_Interface/Menus/File/File_overview.md) menu, point to **Import**, and then click **FLExText Interlinear**.

    The **FieldWorks interlinear (FLExText) file** dialog box appears.

7.  Click **Browse**. Select the FLExText interlinear file, and then click **Open**.

    The path and file name appear in the box next to the **Browse** button.

8.  Click **OK**.

If a writing system is used in the FLExText file that is not currently used in the open language project, one or more warning boxes appear.

1.  - **OK** adds the named writing system to the language project and allows the import operation to continue.

    - **Cancel** aborts the import operation. Then the **Import Failed** warning box appears. Click **OK**.

> [!NOTE]
>
> - The FLExText interlinear is an XML format.
>
> - SayMore (<a href="https://software.sil.org/saymore/" target="_blank" title="https://software.sil.org/saymore/">https://software.sil.org/saymore/</a>) is a tool used for language documentation.
>
> - Some users make these files with [ELAN](Import_overview.md).

## Related topics
[Import overview](Import_overview.md)

[Import Standard Format Interlinear Texts - Pre-defined Mappings](Import_Interlinear_SFM/Import_SF_Interlinear_predefined_mappings.md)

[Writing System files](../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/Writing_System_files.md)
