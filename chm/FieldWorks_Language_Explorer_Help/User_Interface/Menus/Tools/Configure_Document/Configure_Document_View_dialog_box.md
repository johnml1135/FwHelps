---
title: "Configure Document Layout dialog box"
source_title: "Configure Document Layout dialog box"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Tools"
  - "Configure Document"
  - "Configure Document Layout dialog box"
source: "User_Interface/Menus/Tools/Configure_Document/Configure_Document_View_dialog_box.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Tools/Configure_Document/Configure_Document_View_dialog_box.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "View:Configure Document View dialog box"
  - "Before"
  - "Between"
  - "After context boxes:Configure Document View dialog box"
  - "Layouts"
related:
  - "Classifications -> Classifications.md"
  - "Tools overview -> ../Tools_overview.md"
  - "Notebook overview -> ../../../../Using_Tools/Notebook_tools/Notebook_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:b8357814e8d2b1d9"
---

# Configure Document Layout dialog box

*User Interface › Menus › Tools › Configure Document*

This dialog box allows you to choose *which* available data to display, and *how* to display that data in the **Document** [layout](../../../../Using_Tools/Notebook_tools/Document_overview/Document_overview.md). (Data that you excluded with [filters](../../../../Basic_Tasks/Filtering_data/Filter_Notebook_records.md) is not available for display.)

1.  In the Navigation Pane, click **Notebook**, and then click **Document**.

2.  Do one of the following to open the dialog box:

    - [Use a right-click menu command](../../../../Using_Tools/Notebook_tools/Document_overview/Use_right-click_to_help_configure_Document_view.md) (*optional*).

    - On the **Tools** menu, point to **Configure**, and then click **Document**.

      The **Configure Document Layout** dialog box appears.

3.  In the dialog box, do any of the following:

    - [Add, rename, or delete a layout](Manage_Document_Views.md).

    - Click the down arrow (![](../../../../assets/images/DownArrow.png)), and then click the desired layout.

    - [Configure](Configuring_a_Document_view.md) field content, surrounding context, styles and so on.

      - If you clear (![](../../../../assets/images/User_Interface/Menus/Tools/UncheckedBox.PNG)) **Subrecords**, no subrecords are displayed.

      - If you select (![](../../../../assets/images/CheckedBox.PNG)) **Subrecords**, you can [filter](../../../../Basic_Tasks/Filtering_data/Filter_Notebook_records.md) subrecords to specify which of them to display. Displayed *sub*records use the same configuration as records.

4.  Click **OK**.

> [!TIP]
>
> - [Styles you select](Configuring_Document_view_styles.md) here in the **Configure Document Layout** dialog box are applied only to the **Document** layout, not to fields in **Record Edit**.
>
> - - *However*, some styles you [apply](../../Format/apply_a_style_to_text.md) to particular content in fields can override the style set here and appear in the **Document** layout. For example, if you apply the styles **Added Text** or **Deleted Text** to content in a field, those style attributes will appear in the **Document** layout.
>
> - The configuration you specify with this dialog box also controls the [print content](../../File/Print_content.md) when you [print](../../File/Print.md) from **Record Edit**.

## Related topics
[Classifications](Classifications.md)

[Tools overview](../Tools_overview.md)

[Notebook overview](../../../../Using_Tools/Notebook_tools/Notebook_overview.md)
