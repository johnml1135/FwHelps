---
title: "Duplicate a field (Dictionary)"
source_title: "Duplicate a field (Dictionary)"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Tools"
  - "Configure Dictionary"
  - "Duplicate a field (Dictionary)"
source: "User_Interface/Menus/Tools/Configure_Dictionary/Duplicate_Dict_field.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Tools/Configure_Dictionary/Duplicate_Dict_field.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Dictionary:Using the Configure Dictionary dialog box"
  - "Duplicate a field (Dictionary)"
related:
  - "Configure Dictionary dialog box -> Configure_Dictionary.md"
  - "Delete a duplicated field -> Delete_dup_Dict_field.md"
  - "Lexical Relation Types - example -> Lexical_Relation_Types_example.md"
  - "Tools overview -> ../Tools_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:b2a667c578560f54"
---

# Duplicate a field (Dictionary)

*User Interface › Menus › Tools › Configure Dictionary*

In the [left pane](About_the_left_pane.md), you can duplicate a field or a (![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/Plus_box_expand.GIF)) node (a collection of fields or other nodes). You configure the original and copy separately, such as with different writing systems or surrounding context.

In the *left* pane, do the following:

1.  Click the label of the field or node that you want to duplicate.

    The label is highlighted, such as ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/Selected_duplication_item.PNG).

2.  Click ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/CopyConfiguration2.png) (**Duplicate**).

    A copy appears in the left pane, *below* the original. It has a copy number in parentheses. It is highlighted so you can edit the label and configure it.

3.  Optionally, click ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/RenameDuplicateButton2.png) (**Edit Label**).

    - In the **Rename** dialog box, type a new "copy identifier" to replace the number in parentheses.

    - Click **OK**.

The copy identifier you typed appears after the name, which does *not* change.

4.  [Configure](Using_the_Configure_Dictionary_dialog_box.md) the original and copy separately.

5.  Click **OK**.

### Example

The order of the fields in the *left* pane determines the order that their data are displayed.

Suppose a field has data in two different analysis writing systems and you want to change the order in which they are presented for this field.

You could do this:

- Click the label of the field in the *left* pane. Then in the *right* pane, click the label of one of the writing systems and click ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/UpArrowButton2.png) (**Move Up**) or ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/DownArrowButton2.png) (**Move Down**) to change the order of the writing systems.

Alternatively, you could do this:

1.  In the *left* pane, click the label of the field. Click **Duplicate**. In the *right* pane, select (![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/CheckedBox.PNG)) the analysis writing system you want to display last. Clear the check box (![](../../../../assets/images/User_Interface/Menus/Tools/UncheckedBox.PNG)) for the other writing system.

2.  In the *left* pane, click the original field label to highlight it. In the *right* pane, select (![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/CheckedBox.PNG)) the analysis writing system you want to display first. Clear the check box for the other writing system.

Only the duplicate method lets you apply character styles and surrounding context (**Before**, **Between** and **After**) independently.

> [!NOTE]
>
> - This affects the display in the [Dictionary](../../../../Using_Tools/Lexicon_tools/Dictionary/Dictionary_overview.md), the [preview pane](../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/About_Lex_Edit_fld_levels.md), [Dictionary Entry dialog box](../Dictionary_Entry_dialog_box.md), and configured [exports](../../File/Export/Export_a_configured_dictionary.md).

## Related topics
[Configure Dictionary dialog box](Configure_Dictionary.md)

[Delete a duplicated field](Delete_dup_Dict_field.md)

[Lexical Relation Types - example](Lexical_Relation_Types_example.md)

[Tools overview](../Tools_overview.md)
