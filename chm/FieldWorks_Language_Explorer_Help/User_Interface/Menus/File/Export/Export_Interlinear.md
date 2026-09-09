---
title: "Export interlinear texts"
source_title: "Export interlinear texts"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "File"
  - "Export"
  - "Export Interlinear texts"
source: "User_Interface/Menus/File/Export/Export_Interlinear.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/File/Export/Export_Interlinear.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "XML"
  - "OpenOffice"
  - "export to"
  - "Microsoft Word"
  - "Export:Interlinear texts"
  - "Export:Texts"
  - "interlinear"
  - "XLingPaper"
  - "export interlinear to"
  - "ELAN"
  - "ELAN:Export interlinear to"
related:
  - "Export overview -> Export_overview.md"
  - "Import overview -> ../../../../Beginning_Tasks/Importing_Data/Import_overview.md"
  - "File menu overview -> ../File_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:738d4ee93ccdfcf0"
---

# Export interlinear texts

*User Interface › Menus › File › Export*

You can export the interlinearized text currently as displayed in the [Print View](../../../../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/Print_View_Tab_overview.md) tab. You can also choose multiple texts to export into a single document.

`FLExText (FieldWorks XML), XML`, HTM, and `ODT` formats are available. The right pane of the **Export Interlinear** dialog box describes the selected **Format**/**Extension** export method.

1.  In the **Navigation Pane**, click **Texts & Words**, and then click **Interlinear Text**.

2.  In the **Texts** pane, click a text you want to export.

3.  In the **Text** pane, click the **Print View** tab.

4.  [Configure Interlinear Lines](../../Tools/Configure_interlinear_lines_dialog_box.md) to show the desired lines in the desired order and with the desired writing systems. **See also**: [Comment Field](../../../Field_Descriptions/Texts_&_Words/Comment_field_info.md).

    (Changes made here do *not* affect the **Gloss** or **Analyze** tabs.)

5.  On the **File** menu, click **Export Interlinear**.

    The **Export Interlinear** dialog box appears.

6.  In the dialog box, do the following:

    - In the left pane, select an export method.

    - In the right pane, read about the selected export method. If necessary, select a different export method.

    - The **Show in folder** check box is selected (![](../../../../assets/images/CheckedBox.PNG)) by default. Then after export, the folder that has the export file opens and that file is selected. If you do not want this to happen, clear (![](../../../../assets/images/UncheckedBox.PNG)) this check box.

    - Click **Export**.

    If the [Choose Texts](../../../../Basic_Tasks/Filtering_data/Choose_Texts.md) dialog box appears, select (![](../../../../assets/images/CheckedBox.PNG)) the check box for each text or [text node](../../../../Basic_Tasks/Filtering_data/Choose_Texts.md) you want to export into *a single document*. Click **OK**.

    The **Export to** \<extension\> dialog box appears.

7.  In the dialog box, do the following:

    - Click the folder where you want to save the file.

    - Enter a name for the file in the **File name** box.

    - In the **Save as type** box, leave the default selection, which was set automatically.

      We recommend that you write down the file name and extension so that you are sure to remember it later. There may be a *second* file with a similar name, but with “**Phase1-**“ added to the name. It is a temporary file and should be ignored.

8.  Click **Save**.

9.  If you exported to **Microsoft Word XML**, [run the XML Macro](Run_XML_Macro.md) to correct alignment problems.

> [!TIP]
>
> - Styles are created in Microsoft Word or OpenOffice/LibreOffice when you export to **Word XML** or **OpenOffice Writer** or **LibreOffice Writer**. Each of these styles contain **Interlin** in their names, such as **Interlin Citation**, **Interlin Morpheme** and so on.
>
>   - You may want to change one or more styles.
>
> - **Known issues:**
>
>   - Sometimes, in Microsoft Word when modifying styles used to stylize the interlinear text that you exported, the effect of the styles may *not* appear, that is, applying or changing an applied style may have no apparent effect. The work-around seems to be using **Undo** and then **Redo** (`Ctrl+Z` and `Ctrl+Y` in Word) to undo and redo the style application.
>
>   - Sometimes the document produced by exporting to Microsoft Word does not open automatically. The workaround is to simply open the document from inside Microsoft Word.
>
> - If some characters do not appear correctly in the exported file, make sure the program you are using to read the file is set to display **Unicode UTF-8**.
>
> - The XLingPaper package is a tool to aid the linguist in writing linguistic papers. XLingPaper User Documentation is available on the [Help](../../Help/Help_overview.md) menu (point to **Resources**, and then click **Editing Linguistics Papers Using XLingPaper**).

## Related topics
[Export overview](Export_overview.md)

[Import overview](../../../../Beginning_Tasks/Importing_Data/Import_overview.md)

[File menu overview](../File_overview.md)
