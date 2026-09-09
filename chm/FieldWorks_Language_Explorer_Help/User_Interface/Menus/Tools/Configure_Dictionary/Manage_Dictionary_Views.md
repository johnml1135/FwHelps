---
title: "Manage Dictionary Layouts"
source_title: "Manage Dictionary Layouts"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Tools"
  - "Configure Dictionary"
  - "Manage Publication Layouts"
source: "User_Interface/Menus/Tools/Configure_Dictionary/Manage_Dictionary_Views.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Tools/Configure_Dictionary/Manage_Dictionary_Views.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Custom Fields:Import/Export custom fields"
  - "Dictionary Configuration Manager dialog box"
  - "Export:Dictionary configuration"
  - "Import:Dictionary configuration"
  - "Layouts:Manage Dictionary Layouts"
  - "Manage"
  - "Share:Shared configuration (Configure Dictionary)"
  - "reset"
related:
  - "About the Hybrid Dictionary layout -> About_the_Hybrid_Dictionary_view.md"
  - "Configure Dictionary dialog box -> Configure_Dictionary.md"
  - "Select a dictionary layout -> ../../../../Using_Tools/Lexicon_tools/Dictionary/Select_a_dictionary_view.md"
  - "Select a publication -> ../../../../Using_Tools/Lexicon_tools/Dictionary/Select_a_publication.md"
  - "Tools menu overview -> ../Tools_overview.md"
  - "Upload to Webonary -> ../../File/Upload_to_Webonary.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:d10ba4c5770a9921"
---

# Manage Dictionary Layouts

*User Interface › Menus › Tools › Configure Dictionary*

In this dialog box, you specify which layouts (previously called *views*) you want available for each [publication](../../../Field_Descriptions/Lists/Publications/What_is_a_Publication.md). You can also duplicate, rename, delete, reset, export and import layouts. **See Also:** [Manage Reversal Index Layouts](../Configure_Reversal_Index/Manage_Views_Reversal_Index.md).

1.  [Open](Configure_Dictionary.md) the **Configure Dictionary** dialog box.

2.  Click the **Manage Layouts** button.

    The **Manage** **Dictionary Layouts** dialog box appears.

The *left* pane lists [layouts](Dictionary_views.md). The *right* pane lists [publication](../../../Field_Descriptions/Lists/Publications/What_is_a_Publication.md).

3.  Do these steps to specify which layouts are available for publications:

    - In the left pane, click a layout.

    - In the right pane, select (![](../../../../assets/images/CheckedBox.PNG)) the publications you want available for that layout. Clear (![](../../../../assets/images/User_Interface/Menus/Tools/UncheckedBox.PNG)) all other publications.

The layout that you clicked in the *left* pane is available for use by the selected (![](../../../../assets/images/CheckedBox.PNG)) publications.

Repeat this step for other layouts, if desired. You will see the effect of this when you [select a publication](../../../../Using_Tools/Lexicon_tools/Dictionary/Select_a_publication.md) or [use](../../File/Upload_to_Webonary.md) the **Upload to Webonary** dialog box.

4.  Use any of these features:

### ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/CopyConfiguration2.png) Duplicate a layout:

1.  1.  Click the layout you want to duplicate.

    2.  Click ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/CopyConfiguration2.png) (**Duplicate the highlighted layout**).

### (F2) Rename a layout:

1.  1.  Click the layout that you want to rename.

    2.  Press the **F2** key or click the layout a second time (not a rapid double-click) to make the name editable.

    3.  Edit the name.

### ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/DeleteConfiguration.png) Delete a layout:

1.  1.  Click a layout that was added (duplicated or imported).

    2.  Click ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/DeleteConfiguration.png) (**Delete this custom layout**).

    3.  In the **Confirm** dialog box, click **Delete**.

### ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/ResetViewButton.png) Reset a layout:

You cannot reset a layout that you added (duplicated or imported).

1.  1.  Click a layout, and then click ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/ResetViewButton.png) (**Reset this layout**).

    2.  In the **Confirm Reset** dialog box, click **Reset**.

The layout *and* [headword numbers](../Configure_Headword_Numbers/Config_Hdwrd_Numbers_dialog_box.md) are reset to factory settings.

### ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/ExportView.png) Export a layout:

1.  1.  In the left pane, click the layout you want to export.

Any [custom fields](../Custom_Fields/Custom_Fields_overview.md), [custom lists](../../../../Using_Tools/Lists_tools/Insert_a_custom_list.md), [publications](../../../Field_Descriptions/Lists/Publications/What_is_a_Publication.md), and standard LIFT lists will be exported to a file.

[Styles](../../Format/Styles/Styles_overview.md) will be exported, except custom settings for these styles are not included: **Bulleted Lists**, **Numbered List** and **Homograph Number**.

1.  2.  Click ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/ExportView.png) (**Export the highlighted layout**).

    3.  In the window that opens, navigate to the location where you want to store the file. Click **Save**.

A \*.zip file is saved. Share this file so others can import your layout.

### ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/ImportView.png) Import a layout:

1.  1.  Click ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/ImportView.png) (**Import a layout**).

    2.  In the **Import a Layout** dialog box, click **Browse** to find the file you want to import.

    3.  When the path to the file appears in the **File Name** box (**Choose file to import** dialog box), do these steps:

      - Select (![](../../../../assets/images/SelectedRadioButton.png)) either **Overwrite existing layout named** \<name\> or **Use new layout named** \<name\>**-Imported1** (which *adds* the imported layout).

[Custom fields](../Custom_Fields/Custom_Fields_overview.md), [custom lists](../../../../Using_Tools/Lists_tools/Insert_a_custom_list.md), [publications](../../../Field_Descriptions/Lists/Publications/What_is_a_Publication.md) and lists will be imported.

The **Import Dictionary layout** dialog box informs you that [styles](../../Format/Styles/Styles_overview.md) will be entirely replaced (overwritten) by the ones in the file. However, custom settings for these styles are not included: **Bulleted Lists**, **Numbered List** and **Homograph Number**.

1.  - - Click **Import**.

The layout is imported. The dialog boxes close automatically. FLEx does a partial refresh. However, to see the lists, you need to close and reopen the project again.

5.  If the dialog box is open, click **Close**.

6.  If the **Configure Dictionary** dialog box is open, click **OK** or continue [configuring](Using_the_Configure_Dictionary_dialog_box.md) the layout.

7.  Close and reopen the project to see all the imported items.

## Related topics
[About the Hybrid Dictionary layout](About_the_Hybrid_Dictionary_view.md)

[Configure Dictionary dialog box](Configure_Dictionary.md)

[Select a dictionary layout](../../../../Using_Tools/Lexicon_tools/Dictionary/Select_a_dictionary_view.md)

[Select a publication](../../../../Using_Tools/Lexicon_tools/Dictionary/Select_a_publication.md)

[Tools menu overview](../Tools_overview.md)

[Upload to Webonary](../../File/Upload_to_Webonary.md)
