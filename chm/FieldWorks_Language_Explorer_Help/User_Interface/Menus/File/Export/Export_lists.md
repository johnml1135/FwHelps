---
title: "Export lists"
source_title: "Export lists"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "File"
  - "Export"
  - "Export Lists"
source: "User_Interface/Menus/File/Export/Export_lists.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/File/Export/Export_lists.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Export:Lists"
  - "export to"
  - "List:Export"
related:
  - "About writing systems -> ../../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md"
  - "Export overview -> Export_overview.md"
  - "File menu overview -> ../File_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:085d4c110d3d3433"
---

# Export lists

*User Interface › Menus › File › Export*

You can export [lists](../../../../Using_Tools/Lists_tools/Lists_overview.md) and the **Grammatical Categories (or Parts of Speech)** list ([Grammar](../../../../Using_Tools/Grammar_tools/grammar_overview.md) area) into a *single* Standard Format Marker (SFM) file, a Tab-delimited file (\*.txt), or an Extensible Markup Language (XML) file. The export function exports data from *only* (and *all* of) those lists that are mentioned in the right pane of the **Export** dialog box, not only the current list. Some lists, such as **Restrictions** and **Status**, are excluded and *cannot* be exported. To export selected lists and writing systems, see [Export Translated Lists](Export_Translated_Lists.md).

1.  In the **Navigation Pane**, click any area *except* **Texts & Words**.

2.  On the **File** menu, click **Export**.

    The **Export** dialog box appears.

3.  In the **Export** dialog box, do the following:

    - In the left pane, select an export method that contains **Lists**.

    - In the right pane, review the information about the current selection. If necessary, select a different export method. (See ![](../../../../assets/images/Important_Icon.gif) **Important** below.)

    - The **Show in folder** check box is selected (![](../../../../assets/images/CheckedBox.PNG)) by default. Then after export, the folder that has the export file opens and that file is selected. If you do not want this to happen, clear (![](../../../../assets/images/UncheckedBox.PNG)) this check box.

    - Click **Export**.

    A dialog box appears named either **Export to SFM**, **Export to** **Tab-delimited**, or **Export to** **XML**.

4.  In the dialog box, do the following:

    - Navigate to the folder where you want to save the exported data.

    - Enter a name for the exported data in the **File name** box.

    - In the **Save as type** box, the type, **Standard Format files (\*.db), Tab-delimited files (\*.txt) or XML files (\*.xml)**, is automatically selected. Do not change the selection.

5.  Click **Save.**

    The **Exporting Lists** progress box appears. The progress box and dialog box close when the export is finished.

> [!IMPORTANT]
>
> - **All Lists XML** exports all lists into a single XML file. The instructions are in the **Export** dialog box, *not* in these Helps.
>
> <!-- -->
>
> - **Lists Tab-delimited** exports data in the *default vernacular* and default analysis writing systems. Consequently, list content in English will not appear in the exported file if English is not the default analysis writing system.
>
> - Characters may not appear correctly if you ignore the encoding when you open the Tab-delimited file.
>
>   - Microsoft Excel: Use Microsoft's **Text Import Wizard** to set the file origin to **Unicode (UTF-8)**.
>
>     To do this (steps may differ for different versions), start Microsoft Excel. In its **File** menu, click **Open**. In the **Open** dialog box, set the **Files of type** to **Text Files** (which includes \*.txt). In the **Open** dialog box, double-click the file you want to open. The **Text Import Wizard** should appear. Set the file origin to **Unicode (UTF-8)**, and then follow the steps in the wizard.
>
>   - Microsoft Word: Use Microsoft's **File Conversion** dialog box to set the text encoding to **Unicode (UTF-8)**.
>
>     To do this (steps may differ for different versions), start Microsoft Word. In its **File** menu, click **Open**. In the **Open** dialog box, set the **Files of type** to **All Files** (which includes \*.txt). In the **Open** dialog box, double-click the file you want to open. The **File Conversion** dialog box should appear. Set the text encoding to **Unicode (UTF-8)** and specify other settings, as necessary. Click **OK** to close that dialog box and import the file.

### ****Related Topics****

[About writing systems](../../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md)

[Export overview](Export_overview.md)

[File menu overview](../File_overview.md)
