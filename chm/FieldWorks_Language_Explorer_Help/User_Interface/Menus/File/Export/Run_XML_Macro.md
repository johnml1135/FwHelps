---
title: "Run XML Macro"
source_title: "Run XML Macro"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "File"
  - "Export"
  - "Run XML Macro"
source: "User_Interface/Menus/File/Export/Run_XML_Macro.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/File/Export/Run_XML_Macro.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Run XML Macro"
  - "Macro"
  - "run for XML"
  - "Clean up XML export"
related:
  - "Export Interlinear overview -> Export_Interlinear.md"
  - "File menu overview -> ../File_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:fd330da6e1e20849"
---

# Run XML Macro

*User Interface › Menus › File › Export*

You can export the glossed or analyzed (interlinearized) text displayed in [Print View](../../../../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/Print_View_Tab_overview.md) tab into a Microsoft Word `XML` format. For export to *Word 2003*, you need to run a macro that was installed on your hard drive when you installed FieldWorks. The macro will correct misalignments.

1.  Open this file:

`C:\Program Files\SIL\FieldWorks 9\Language Explorer\Export Templates\Interlinear\Interlinear Macros and Instructions.doc.`

- If the **Security Warning** box is displayed, but the **Enable Macros** button is *not* available, you may need to change the **Macro Security** level in Word.

To do this, in Word open the **Security** dialog box (**Tools**\\**Macro**\\**Security**), and then choose **Medium**, instead of **High** or **Very High**.

- Alternatively, in the **Security Warning** box, you can click **Disable Macros** to open the file so you can at least read it.

2.  Install the `FieldWorks_Interlinear_Macros` macro into `Normal.dot` as follows:

    - In Word, on the **Tools** menu, point to **Macro**, and then select **Macros**.

    - In the **Macros** dialog box, click **Organizer**.

    The **Organizer** dialog box appears.

3.  In the **Organizer** dialog box **Macro Project Items** tab, and then do the following:

    - Click the left **Close File** button, which immediately changes to **Open File**.

    - Click the button again, and open the following file given in step **1** above`.`

    - At this point the left pane will contain **FieldWorks_Interlinear_Macros**. Click this file, and then click **Copy**, to copy it into right pane (**In Normal.dot**).

4.  In the **Organizer** dialog box, click the **Toolbars** tab, and then do the following:

    - *If* **FieldWorks_Interlinear** is *not* in the left pane, click the left **Close File** button, which changes to **Open File**. Then, click the button again, and open the file given in step **1** above.

    - *If* (or *when*) **FieldWorks_Interlinear** *is in* the left pane, click it, and then click **Copy**, to copy it into right pane (**In Normal.dot**).

    - Click **Close**.

    The macro is now available for toolbar setup.

5.  Close the *Interlinear Macros and Instructions.doc* file.

6.  If you have not already done so, [export the interlinear text](Export_Interlinear.md) (from Language Explorer).

7.  In Word, open the file containing the exported interlinear text.

8.  In Word, with the interlinear export file open, right-click the toolbars area, and then select **FieldWorks Interlinear**.

    A new toolbar appears with **Adjust boxes** and **Adjust tables** buttons.

9.  To re-align display, click **Adjust boxes**. When that is finished, click **Adjust tables**.

> [!TIP]
>
> - For additional help refer again to *Interlinear Macros and Instructions.doc* file.
>
> - In Word, various styles are applied to the items in the interlinearized text. Notice that some words and morphemes appear **bold** or *italic*. You can click each word or morpheme to learn the applied style. You can then modify any style, including colors as desired.

## Related topics
[Export Interlinear overview](Export_Interlinear.md)

[File menu overview](../File_overview.md)
