---
title: "Manage Reversal Index Layouts"
source_title: "Manage Reversal Index Layouts"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Tools"
  - "Configure Reversal Index"
  - "Manage Reversal Index layouts"
source: "User_Interface/Menus/Tools/Configure_Reversal_Index/Manage_Views_Reversal_Index.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Tools/Configure_Reversal_Index/Manage_Views_Reversal_Index.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Export:Reversal Index configuration"
  - "Import:Import Reversal Configuration'"
  - "Import:Reversal Index configuration"
  - "Layouts"
  - "Reversal Index Configuration Manager dialog box"
  - "Reversal Indexes:Reversal Index Configuration Manager dialog box"
  - "Share:Shared configuration (Reversal Indexes)"
  - "View:Manage Reversal Indexes Views"
  - "reset"
  - "Layouts:Manage Reversal Index Layouts"
related:
  - "Select a publication -> ../../../../Using_Tools/Lexicon_tools/Dictionary/Select_a_publication.md"
  - "Select a Reversal Index layout -> ../../../../Using_Tools/Lexicon_tools/Reversal_Indexes/Select_a_Reversal_index_view.md"
  - "Tools menu overview -> ../Tools_overview.md"
  - "Upload to Webonary -> ../../File/Upload_to_Webonary.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:ecdc35d4dbcd501b"
---

# Manage Reversal Index Layouts

*User Interface › Menus › Tools › Configure Reversal Index*

In the **Manage Reversal Index Layouts** dialog box, you specify which layouts you want available for each [publication](../../../Field_Descriptions/Lists/Publications/What_is_a_Publication.md). You can also duplicate, rename, delete, reset, export and import layouts.

Initially, there is [one layout](../../../../Using_Tools/Lexicon_tools/Reversal_Indexes/Insert_a_reversal_index.md) for each analysis writing system.\
**All Reversal Indexes** is *not* a layout that you can choose on the [Information bar](../../../Toolbars/information_bar_overview.md). It is a baseline template from which other layouts are derived.

- You can [configure](Configuring_a_reversal_index_view.md) **All Reversal Indexes**.

- You can reset (![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Reversal_Index/ResetViewButton.png)) other layouts to match **All Reversal Indexes**.

- You can reset (![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Reversal_Index/ResetViewButton.png)) **All Reversal Indexes** back to "factory settings" if you had experimented with a custom configuration.

Do these steps:

1.  [Open](Configure_Reversal_Index_dialog_box.md) the **Configure Reversal Index** dialog box.

2.  Click the **Manage Layouts** button.

    The **Manage** **Reversal Index Layout** dialog box appears.

The *left* pane lists layouts. The *right* pane lists publication.

3.  Do these steps to specify which layouts are available for publications:

    - In the left pane, click a layout.

    - In the right pane, select (![](../../../../assets/images/CheckedBox.PNG)) the publications you want available for that layout. Clear (![](../../../../assets/images/User_Interface/Menus/Tools/UncheckedBox.PNG)) all other publications.

The layout that you clicked in the *left* pane is available for use by the selected (![](../../../../assets/images/CheckedBox.PNG)) publications.

Repeat this step for other layout, if desired. Then, you will be able to [select a publication](../../../../Using_Tools/Lexicon_tools/Dictionary/Select_a_publication.md) or [use](../../File/Upload_to_Webonary.md) the **Upload to Webonary** dialog box.

4.  Use any of these features:

### ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Reversal_Index/CopyConfiguration2.png) Duplicate a layout:

1.  1.  Click the layout you want to duplicate.

    2.  Click ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Reversal_Index/CopyConfiguration2.png) (**Duplicate the highlighted layout**).

### (F2) Rename a layout:

1.  1.  Click the layout that you want to rename.

    2.  Press the **F2** key or click the layout a second time (not a rapid double-click) to make the name editable.

    3.  Edit the name.

### ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Reversal_Index/DeleteConfiguration.png) Delete a layout:

1.  1.  Click a layout that was added (duplicated or imported).

    2.  Click ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Reversal_Index/DeleteConfiguration.png) (**Delete this custom layout**).

    3.  In the **Confirm** dialog box, click **Delete**.

### ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Reversal_Index/ResetViewButton.png) Reset All Reversal Indexes:

1.  1.  Click **All Reversal Indexes**.

    2.  Click ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Reversal_Index/ResetViewButton.png) (**Reset this layout**).

    3.  In the **Confirm Reset** dialog box, click **Reset**.

**All Reversal Indexes** *and* [headword numbers](../Configure_Headword_Numbers/Config_Hdwrd_Numbers_dialog_box.md) are reset to factory settings.

### ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Reversal_Index/ResetViewButton.png) Reset a layout to match All Reversal Indexes:

1.  1.  Click a layout.

    2.  Click ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Reversal_Index/ResetViewButton.png) (**Reset this layout**).

    3.  In the **Confirm Reset** dialog box, click **Reset**.

The layout and [headword numbers](../Configure_Headword_Numbers/Config_Hdwrd_Numbers_dialog_box.md) are reset to match **All Reversal Indexes**.

### ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Reversal_Index/ExportView.png) Export a layout:

1.  1.  In the left pane, click the layout you want to export.

Any [custom fields](../Custom_Fields/Custom_Fields_overview.md), [custom lists](../../../../Using_Tools/Lists_tools/Insert_a_custom_list.md), [publications](../../../Field_Descriptions/Lists/Publications/What_is_a_Publication.md), and standard LIFT lists will be exported to a file.

[Styles](../../Format/Styles/Styles_overview.md) will be exported, except custom settings for these styles are not included: **Bulleted Lists**, **Numbered List** and **Homograph Number**.

1.  2.  Click ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Reversal_Index/ExportView.png) (**Export the highlighted layout**). In the window that opens, navigate to the location where you want to store the file. Click **Save**.

A \*.zip file is saved. You can share this file so others can import your layout.

### ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Reversal_Index/ImportView.png) Import a layout:

1.  1.  Click ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Reversal_Index/ImportView.png) (**Import a layout**).

    2.  In the **Import a Layout** dialog box, click **Browse** to find the file you want to import.

    3.  When the path to the file appears in the **File Name** box (**Choose file to import** dialog box), do these steps:

      - Select (![](../../../../assets/images/SelectedRadioButton.png)) either **Overwrite existing layout named** \<name\> or **Use new layout named** \<name\>**-Imported1** (which *adds* the imported layout).

[Custom fields](../Custom_Fields/Custom_Fields_overview.md), [custom lists](../../../../Using_Tools/Lists_tools/Insert_a_custom_list.md), [publications](../../../Field_Descriptions/Lists/Publications/What_is_a_Publication.md) and lists will be imported.

The **Import Dictionary Layout** dialog box informs you that [styles](../../Format/Styles/Styles_overview.md) will be entirely replaced (overwritten) by the ones in the file. However, custom settings for these styles are not included: **Bulleted Lists**, **Numbered List** and **Homograph Number**.

1.  - - Click **Import**.

The layout is imported. The dialog boxes close automatically. FLEx does a partial refresh. However, to see the lists, you need to close and reopen the project again.

5.  If the dialog box is open, click **Close**.

6.  If the **Configure Reversal Index** dialog box is open, click **OK** or continue [configuring](Configuring_a_reversal_index_view.md) the layout.

7.  Close and reopen the project to see all the imported items.

## Related topics
[Select a publication](../../../../Using_Tools/Lexicon_tools/Dictionary/Select_a_publication.md)

[Select a Reversal Index layout](../../../../Using_Tools/Lexicon_tools/Reversal_Indexes/Select_a_Reversal_index_view.md)

[Tools menu overview](../Tools_overview.md)

[Upload to Webonary](../../File/Upload_to_Webonary.md)
