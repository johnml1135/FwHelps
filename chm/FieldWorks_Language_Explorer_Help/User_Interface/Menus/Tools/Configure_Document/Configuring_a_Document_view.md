---
title: "Configuring a Document layout"
source_title: "Configuring a Document layout"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Tools"
  - "Configure Document"
  - "Configuring a Document layout"
source: "User_Interface/Menus/Tools/Configure_Document/Configuring_a_Document_view.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Tools/Configure_Document/Configuring_a_Document_view.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Document view (Notebook)"
related:
  - "Classifications -> Classifications.md"
  - "Configure Document Layout dialog box -> Configure_Document_View_dialog_box.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:b50cbb78ebf51601"
---

# Configuring a Document layout

*User Interface › Menus › Tools › Configure Document*

- [Use right-click to help configure Document layout](../../../../Using_Tools/Notebook_tools/Document_overview/Use_right-click_to_help_configure_Document_view.md) (optional).

Do the following in the **Configure Document Layout** [dialog box](Configure_Document_View_dialog_box.md):

Tip: Each [field](../../../Field_Descriptions/Notebook/Notebook_fields_overview.md) in **Record Edit** is listed. Some fields are grouped together, such as under **Classifications** or **Created/Modified**. You can configure each separately ([Example](Time_of_Event.md)).

1.  [Add a new document layout](Manage_Document_Views.md) (optional).

2.  Click the button, and choose the document layout to configure.

3.  Do *any* of the following in the *left* pane:

    - Click any ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/Plus_box_expand.GIF) to expand items in (field, group and so on) the hierarchical list.

    - Select (![](../../../../assets/images/CheckedBox.PNG)) each item that you want to display.

    - Clear (![](../../../../assets/images/User_Interface/Menus/Tools/UncheckedBox.PNG)) each item that you do not want to display.

      If a check box is cleared, any of its subordinate items are hidden as well.

    - Click an item to select it (to *highlight* it, such as ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Document/HighlightedTimeOfEvent.PNG)). Then, click ![](../../../../assets/images/User_Interface/Menus/Tools/Up_arrow.PNG) or ![](../../../../assets/images/User_Interface/Menus/Tools/Down_arrow.PNG) to reorder the display of contents from fields.

4.  For a highlighted item, do *any* of the following in the *right* pane (under **Record: \<name\>**):

    - Select or clear the **Display if data present** check box. The corresponding check box in the left pane is also selected or cleared. (This check box must be selected to enable other features in the right pane.)

    - If the **Configure now** link is shown, click it to move from a field label or header to the next appropriate field, and display configuration options for it.

    - If a **Writing systems** pane is shown, select (![](../../../../assets/images/CheckedBox.PNG)) each specific writing system you want to use to display content from the current field.

      **Note**: If **Default Vernacular** or **Default** **Analysis** is selected, you *cannot* select other (additional) writing systems. If you select other writing systems, the “default” check box is cleared to prevent duplicate writing systems. If you select a *default* writing system, but a list item does not have content in that writing system, the content in the *next* writing system with content is displayed.

      If you select one writing system for a list reference field, such as **Locations Abbreviation** or **Name**, but the abbreviation or name is *not* available in that writing system, then *nothing appears* for that selection.

      - If *multiple* writing systems are selected, click a writing system name (to highlight it). Then click ![](../../../../assets/images/User_Interface/Menus/Tools/Up_arrow.PNG) or ![](../../../../assets/images/User_Interface/Menus/Tools/Down_arrow.PNG) to reorder the display of content from the current item, based on writing systems.

    - [Select Document layout styles](Configuring_Document_view_styles.md).

    - If **Surrounding Context** is shown, enter words, symbols, punctuation, or spaces as desired in the **Before**, **Between** and **After** boxes. Select different [styles](Configuring_Document_view_styles.md) this content, if needed. **See Also:** [Surrounding Context](../Configure_Dictionary/Surrounding_Context.md).

    - If the **Display Writing System Abbreviations** check box is shown and is available, select it to display the [abbreviation](../../../Field_Descriptions/Field_Types/Single_line_text_field_example_graphic.md) for the writing system(s) used in the entry. Otherwise, clear the check box to *not* show the writing system(s) abbreviations.

5.  Click **OK**.

> [!IMPORTANT]
>
> - All the selections and styles you make are also applied to **Subrecord**, if it is selected. You cannot specify different fields, styles and so on separately for subrecords.

## Related topics
[Classifications](Classifications.md)

[Configure Document Layout dialog box](Configure_Document_View_dialog_box.md)
