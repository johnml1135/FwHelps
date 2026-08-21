---
title: "Export wordforms"
source_title: "Export wordforms"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "File"
  - "Export"
  - "Export Wordforms"
source: "User_Interface/Menus/File/Export/Export_wordforms.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/File/Export/Export_wordforms.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Words:Export wordforms"
  - "Export:Export wordforms"
  - "export to"
related:
  - "About writing systems -> ../../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md"
  - "Configure Interlinear lines dialog box -> ../../Tools/Configure_interlinear_lines_dialog_box.md"
  - "Export overview -> Export_overview.md"
  - "File overview -> ../File_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:576aa036ae042e00"
---

# Export wordforms

*User Interface › Menus › File › Export*

You can export [word list](../../../../Using_Tools/Texts_%26_Words_tools/Word_list_overview.md) wordforms to a Standard Format Marker (SFM) file, a Tab-delimited file (\*.txt) or an Extensible Markup Language (XML) file. You *cannot* specify which data to export (that is, filters, sorts or displayed/hidden columns do *not* affect the export). The default export contains data from the **Form**, **Word Glosses**, **Category**, **Number in Corpus**, **User Analyses** and **Predicted Analyses** [columns](../../../../Using_Tools/Texts_&_Words_tools/Word_list_columns.md).

1.  On the **File** menu, click **Export**.

    - If only **Export Interlinear** appears on the menu, select a different area or tool in the **Navigation Pane**.

    The **Export** dialog box appears.

2.  In the **Export** dialog box, do the following:

    - In the left pane, select an export method that contains **Wordforms**.

    - In the right pane, read about the selected method. The **Tab-delimited** method mentions, for example, that you can import the file into Word or Excel (See ![](../../../../assets/images/Important_Icon.gif) **Important** below.) If necessary, select a different method.

    - The **Show in folder** check box is selected (![](../../../../assets/images/CheckedBox.PNG)) by default. Then after export, the folder that has the export file opens and that file is selected. If you do not want this to happen, clear (![](../../../../assets/images/UncheckedBox.PNG)) this check box.

    - Click **Export**.

    A dialog box appears named **Export to** **SFM**, **Export to** **Tab-delimited** or **Export to** **XML**.

3.  In the dialog box, do the following:

    - Navigate to the folder where you want to save the exported data.

    - Enter a name for the exported data in the **File name** box.

    - In the **Save as type** box, the type, **Standard Format Files (\*.db)**, **Tab-delimited files (\*.txt)** or **XML files (\*.xml)**, is automatically selected. Do not change the selection.

4.  Click **Save**.

    The **Exporting** **Wordforms** progress box appears. The progress box and dialog box close when the export is finished.

> [!IMPORTANT]
>
> - **Wordforms Tab-delimited** exports wordforms that use the *default* *vernacular* writing system and glosses that use the *default* *analysis* writing system. Wordforms that use another writing system (in a **Baseline** tab) are *not* exported.
>
> - Characters may not appear correctly if you ignore the encoding when you open the Tab-delimited file.
>
>   - Microsoft Excel: Use Microsoft's **Text Import Wizard** to set the *file origin* to **Unicode (UTF-8)**.
>
>     To do this (steps may differ for different versions), start Microsoft Excel. In its **File** menu, click **Open**. In the **Open** dialog box, set the **Files of type** to **Text Files** (which includes *\*.txt*). In the **Open** dialog box, double-click the file you want to open. The **Text Import Wizard** should appear. Set the file origin to **Unicode (UTF-8)**, and then follow the steps in the wizard.
>
>   - Microsoft Word: Use Microsoft's **File Conversion** dialog box to set the *text encoding* to **Unicode (UTF-8)**.
>
>     To do this (steps may differ for different versions), start Microsoft Word. In its **File** menu, click **Open**. In the **Open** dialog box, set the **Files of type** to **All Files** (which includes *\*.txt*). In the **Open** dialog box, double-click the file you want to open. The **File Conversion** dialog box should appear. Set the *text encoding* to **Unicode (UTF-8)** and specify other settings, as necessary. Click **OK** to close that dialog box and import the file.

## Related topics
[About writing systems](../../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md)

[Configure Interlinear lines dialog box](../../Tools/Configure_interlinear_lines_dialog_box.md)

[Export overview](Export_overview.md)

[File overview](../File_overview.md)
