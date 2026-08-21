---
title: "Using the Configure Dictionary dialog box"
source_title: "Using the Configure Dictionary dialog box"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Tools"
  - "Configure Dictionary"
  - "Using the Configure Dictionary dialog box"
source: "User_Interface/Menus/Tools/Configure_Dictionary/Using_the_Configure_Dictionary_dialog_box.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Tools/Configure_Dictionary/Using_the_Configure_Dictionary_dialog_box.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Dictionary:Using the Configure Dictionary dialog box"
  - "Dictionary:Dictionary preview pane"
  - "About:Before/Between/After boxes"
  - "Use or Using:Using the Configure Dictionary dialog box"
  - "Right-to-Left direction"
  - "Bi-directional dictionary"
  - "Hover for details (Config Dictionary)"
  - "Share:Shared configuration (Configure Dictionary)"
related:
  - "About the Dictionary-Context style -> ../../Format/Styles/About_the_Dictionary-Context_style.md"
  - "Configure Dictionary dialog box -> Configure_Dictionary.md"
  - "Configure Headword Numbers dialog box -> ../Configure_Headword_Numbers/Config_Hdwrd_Numbers_dialog_box.md"
  - "Custom Fields overview -> ../Custom_Fields/Custom_Fields_overview.md"
  - "Delete a duplicated field -> Delete_dup_Dict_field.md"
  - "Duplicate a field -> Duplicate_Dict_field.md"
  - "Exclude an entry from the dictionary -> ../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Exclude_an_entry_from_the_dictionary.md"
  - "Select a Dictionary layout -> ../../../../Using_Tools/Lexicon_tools/Dictionary/Select_a_dictionary_view.md"
  - "Technical Support -> ../../../../Overview/Technical_support.md"
  - "What is a publication? -> ../../../Field_Descriptions/Lists/Publications/What_is_a_Publication.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:cf9117214740e274"
---

# Using the Configure Dictionary dialog box

*User Interface › Menus › Tools › Configure Dictionary*

- [Use right-click to help configure the Dictionary layout](../../../../Using_Tools/Lexicon_tools/Dictionary/Use_right-click_to_help_configure_Dictionary_view.md) (*optional*).

Do these steps in the **Configure Dictionary** dialog box:

1.  [Choose the layout](Choose_a_dictionary_view.md) that you want to configure.

2.  Click [Manage Layouts](Manage_Dictionary_Views.md) to select views for publications, add, rename, reset, delete, export or import a layout.

3.  In the [left pane](About_the_left_pane.md), do any of these steps:

<!-- -->

2.  - Click any node (![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/Plus_box_expand.GIF)) to expand the hierarchical list.

    - Select (![](../../../../assets/images/CheckedBox.PNG)) or clear (![](../../../../assets/images/User_Interface/Menus/Tools/UncheckedBox.PNG)) check boxes to display or exclude data.

    - Click a label to *highlight* it (such as ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/Subsenses.png)). Then, do any of these steps:

      - Use ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/UpArrowButton2.png) (**Move Up**) or ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/DownArrowButton2.png) (**Move Down**) to [reorder](Reorder_fields_in_Configure_Dictionary.md) fields or nodes.

      - Use ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/CopyConfiguration2.png) (**Duplicate**), ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/DeleteConfiguration.png) (**Delete**) or ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/RenameDuplicateButton2.png)(**Edit Label**).

      - Click ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/HighlightButton.png) (*Highlight affected content*). Data controlled by the highlighted item gets a yellow background in the preview pane.

<!-- -->

4.  In the *right* pane, there are many optional things you can do for a selected *and* highlighted field or node.\
    Here are some you can review as examples:

    - If you see **This configuration is shared. Hover for details.** or **This item is configured somewhere else. Hover for details.** hold your mouse pointer over the statement. A pop-up box appears ([example](Hover_for_details_example.md)).

<!-- -->

1.  - If you see the **Display each** \<item\> **in a separate paragraph** check box, select it or clear it.

If selected, data controlled by that item ([Complex Form](Complex_Forms.md), [Variant Form](Variant_Forms.md), [Example](Examples.md), and so on) appears in a separate paragraph. Then it uses a paragraph style instead of a character style.

1.  - If a **Character Style for Content** or `Paragraph Style for content Control` appears, choose the style you want to use. Click the **Styles** button to open the [Styles](../../Format/Styles/Styles_overview.md) dialog box so you can add, delete or modify styles. **See Also:** [Styles for export](../../File/Pathway_Configuration_Tool/Styles_for_export.md) and [About Dictionary-Context style](../../Format/Styles/About_the_Dictionary-Context_style.md).

    - Enter symbols, punctuation, or spaces as desired in the **Before**, **Between** and **After** boxes ([Surrounding Context](Surrounding_Context.md)).

<!-- -->

1.  - If a **Writing systems** pane ([example](Writing_Systems.md)) is shown, select (![](../../../../assets/images/CheckedBox.PNG)) each writing system you want to use to display content from the current field.

      If **Default Vernacular** or **Default** **Analysis** has a check mark and you select another writing system, FLEx clears the ”default” check box. This prevents duplicate writing systems.

      If a **Writing systems** pane has more than one selected writing systems, click a writing system name (to *highlight* it). Then, click ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/UpArrowButton2.png) or ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/DownArrowButton2.png) to reorder the display of content from the current field (by writing system).

<!-- -->

1.  - If the **Display Writing System Abbreviations** check box is available, select it to display the [abbreviation](../../../Field_Descriptions/Field_Types/Single_line_text_field_example_graphic.md) for the writing systems used in the entry.

<!-- -->

1.  - If the **Sense Number Configuration** pane is shown for [senses](Senses_Subsenses.md), [configure the sense numbers](Sense_No_Config_Dict.md).

    - If you see the **If all senses share the grammatical information, show it first** check box, select it or clear it. **See:** [Grammatical Info](Grammatical_Info.md).

    - If you selected **Pictures** (![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Classified_Dictionary/Pictures.png)), choose **Left**, **Center** or **Right** with the **Alignment** control, and then enter values for the **Max Width** and **Max Height** in inches.

<!-- -->

5.  Click **OK**.

> [!IMPORTANT]
>
> - Styles that are selected for nodes (![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/Plus_box_expand.GIF)) are applied to all of their subordinate nodes and fields. So, if style control for a node or field shows **(none)**, click the parent nodes in the hierarchical structure until you see the node with a style ([example](Style_example.md)).
>
> - The layout that is selected in the **Choose the layout to configure** box when you click **OK** is the layout that is displayed each time you click **Dictionary** in the **Navigation Pane**. It is also the layout used in the [Dictionary Preview](../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/About_Lex_Edit_fld_levels.md) pane and the [Dictionary Entry](../Dictionary_Entry_dialog_box.md) dialog box.
>
> - You can specify whether a *right-to-left* vernacular language has the **Dictionary** layout oriented *right-to-left* or *left-to-right* using the **Direction** control with the **Dictionary-Normal** [style](../../Format/Styles/Styles_Paragraph_tab.md).
>
> - - When the **Direction** control for the **Dictionary-Normal** style is set to *right-to-left*, the layout aligns to the right, the headword is correctly moved to the right, and the justification is on the right. However, you need to examine the entries to make sure *all* the data is presented correctly. Request [technical support](../../../../Overview/Technical_support.md) if necessary.

## Related topics
[About the Dictionary-Context style](../../Format/Styles/About_the_Dictionary-Context_style.md)

[Configure Dictionary dialog box](Configure_Dictionary.md)

[Configure Headword Numbers dialog box](../Configure_Headword_Numbers/Config_Hdwrd_Numbers_dialog_box.md)

[Custom Fields overview](../Custom_Fields/Custom_Fields_overview.md)

[Delete a duplicated field](Delete_dup_Dict_field.md)

[Duplicate a field](Duplicate_Dict_field.md)

[Exclude an entry from the dictionary](../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Exclude_an_entry_from_the_dictionary.md)

[Select a Dictionary layout](../../../../Using_Tools/Lexicon_tools/Dictionary/Select_a_dictionary_view.md)

[Technical Support](../../../../Overview/Technical_support.md)

[What is a publication?](../../../Field_Descriptions/Lists/Publications/What_is_a_Publication.md)
