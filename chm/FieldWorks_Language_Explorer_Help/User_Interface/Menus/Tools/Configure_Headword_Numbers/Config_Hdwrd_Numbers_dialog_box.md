---
title: "Configure Headword Numbers dialog box"
source_title: "Configure Headword Numbers dialog box"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Tools"
  - "Configure Headword Numbers"
  - "Configure Headword Numbers dialog box"
source: "User_Interface/Menus/Tools/Configure_Headword_Numbers/Config_Hdwrd_Numbers_dialog_box.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Tools/Configure_Headword_Numbers/Config_Hdwrd_Numbers_dialog_box.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Homograph numbers:Configure Headword Numbers"
  - "Dictionary"
  - "Headword Numbers:Configure Headword Numbers"
related:
  - "Styles dialog box -> ../../Format/Styles/Styles_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:a0188993a736a0aa"
---

# Configure Headword Numbers dialog box

*User Interface › Menus › Tools › Configure Headword Numbers*

A "headword" consists of the lexeme or citation form plus any homograph number. *A referenced* headword can also include the sense number if a specific sense was [chosen](../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_components_for_Components_field.md).

The choices you make in this dialog box affect the *current* **Dictionary** [layout](../Configure_Dictionary/Manage_Dictionary_Views.md) or *current* **Reversal Index** [layout](../Configure_Reversal_Index/Manage_Views_Reversal_Index.md).

For **Classified Dictionary**, see: [Configure Headword Numbers dialog box - Classified Dictionary](Configure_Headword_Numbers_dialog_box_Classified_Dictionary.md).

You cannot open this dialog box directly from any menu command. Instead, you open it from the dialog box you use to configure the Dictionary, Reversal Indexes or Classified Dictionary. When you click any of the nodes that controls the display of a headword or referenced headword, such as [Headword](../Configure_Dictionary/Headword.md) or [Referenced Headword](../Configure_Dictionary/Cross_References.md), then the **Configure Headword Numbers** button appears. It opens this dialog box.

1.  Do one of these steps:

    - For **Dictionary**, [choose](../Configure_Dictionary/Choose_a_dictionary_view.md) or [select](../../../../Using_Tools/Lexicon_tools/Dictionary/Select_a_dictionary_view.md) a layout.

    - For **Reversal Indexes**, [choose](../Configure_Reversal_Index/Choose_a_Reversal_Index_view.md) or [select](../../../../Using_Tools/Lexicon_tools/Reversal_Indexes/Select_a_Reversal_index_view.md) a layout (a writing system).

2.  When the desired layout is displayed, open the **Configure Headword Numbers** dialog box:

    - From within the **Configure Dictionary** or **Configure Reversal Indexes** dialog box, click a **Configure Headword Numbers** button.

The button is displayed when you configure any node that controls the display of headwords.

3.  To not show homograph numbers on entry headwords, select (![](../../../../assets/images/SelectedRadioButton.png)) **None**.

Otherwise, select (![](../../../../assets/images/SelectedRadioButton.png)) **Before** or **After** to control whether they appear *before* or *after* the headword.

Then, do *any* of these steps:

- The **Character style of homograph numbers** button displays the [style](../../Format/Styles/About_Headword_Number_styles.md) that is used for homograph numbers. Click the **Styles** button and modify the style.

- The **Character style of sense numbers** button displays the [style](../../Format/Styles/About_Headword_Number_styles.md) that is used for sense numbers. Click the **Styles** button and modify the style.

4.  Below **References should include (if significant)**, select or clear **Homograph Numbers** or **Sense Numbers** as desired.

If selected (![](../../../../assets/images/CheckedBox.PNG)), any numbers appear with *referenced* headwords.

If cleared (![](../../../../assets/images/User_Interface/Menus/Tools/UncheckedBox.PNG)), no numbers are displayed.

5.  If you will use characters other than 0-9 for homograph and sense numbers, do these steps:

    - Click the **Writing System for homograph and sense numbers** button and then click the writing system you want to use.

    - Type or paste a character in *every one* of the empty boxes that are below the numbers 0-9.

The **OK** button is unavailable if some boxes have characters but other boxes are empty.

6.  Click **OK**.

> [!IMPORTANT]
>
> - In the current version, you *cannot* choose different [headword number styles](../../Format/Styles/About_Headword_Number_styles.md) (homograph or sense-reference). You can modify them.
>
> <!-- -->
>
> - **(if significant)** means that there is a homograph or sense number.
>
> - If you added characters other than 0-9 and your lexicon has 10 or more identically-spelled words, the tenth instance will be marked by the contents from the **1** box and the **0** box.
>
> - The controls in this dialog box are reset to "factory defaults" when you reset (![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/ResetViewButton.png)) the corresponding layout in the **Manage Dictionary Layouts** or **Manage Reversal Index Layouts** dialog boxes.

## Related topics
[Styles dialog box](../../Format/Styles/Styles_overview.md)
