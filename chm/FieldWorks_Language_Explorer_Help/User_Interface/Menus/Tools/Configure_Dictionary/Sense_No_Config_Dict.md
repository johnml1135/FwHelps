---
title: "Sense/Subsense Number Configuration - Dictionary"
source_title: "Sense Number Configuration"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Tools"
  - "Configure Dictionary"
  - "Sense Number Configuration"
source: "User_Interface/Menus/Tools/Configure_Dictionary/Sense_No_Config_Dict.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Tools/Configure_Dictionary/Sense_No_Config_Dict.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Sense:Configuring Senses"
  - "Dictionary view"
  - "Subsense"
  - "Senses:Sense Number Configuration"
  - "Show:Show parent sense number"
  - "Sense Number Configuration"
  - "Dictionary Entry"
  - "Separated by dot"
  - "subsense configuration"
  - "Joined"
related:
  - "Configure Dictionary dialog box -> Configure_Dictionary.md"
  - "Paragraph Style to display sense on new line -> Display_each_sense_in_a_paragraph.md"
  - "Use right-click to help configure Dictionary -> ../../../../Using_Tools/Lexicon_tools/Dictionary/Use_right-click_to_help_configure_Dictionary_view.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:a1f2d2037687a269"
---

# Sense/Subsense Number Configuration - Dictionary

*User Interface › Menus › Tools › Configure Dictionary*

In the [left pane](About_the_left_pane.md), if you click **Senses** or **Subsenses** ([Senses / Subsenses](Senses_Subsenses.md)) you can use **Sense Number Configuration** or **Subsense Number Configuration** controls.

You can configure the display of sense numbers independently for main entries, minor entries, subsenses and so on. When you configure the sense numbers that appear in both a "parent" entry and a "child" entry (component and component references, variants or variant references, and so on), you can configure the parent entry and the same sense number configuration will appear in the "child" entry.

1.  In the *left* pane of the **Configure** area, click the appropriate **Senses** or **Subsenses** node to *highlight* it (![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/Sense_Num_Config.PNG) or ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/Subsenses.png)).

    **Sense Number Configuration** or **Subsense Number Configuration** appears with other controls in the *right* pane.

2.  Do *one* of the following:

    - In the **Numbering Style** box, select **(none)**.

      **(none)** removes the sense number from dictionary entries the **Entries** pane, and also *disables* the other features in the **Sense Number Configuration** area.

      - If **Display each sense in a paragraph** is selected (![](../../../../assets/images/CheckedBox.PNG)), use the **Paragraph Style for Content** control (*bottom* of right pane) to choose styles. For example, **Bulleted List** adds bullets to the senses or subsenses.

    - In the **Numbering Style** box, select a number style, then do *any* of the following:

      - Choose a **Character Style**.

      - Use the **Style** button to make changes to styles.

      - **Show parent sense number** (for *sub*senses):\
        Choose **(none)**, **Joined** or **Separated by dot**. See **Tip** below.

      - **Before** box: enter any character or symbol you want to display *before* the sense numbers.

      - **Between** box: enter any character or symbol you want to display *between* the sense numbers for entries with more than one sense.

      - **After** box: enter any character or symbol you want to display *after* the sense numbers.

      - Select (![](../../../../assets/images/CheckedBox.PNG)) **Number even a single sense** if you want to display sense numbers even if there is only one. Otherwise, sense numbers will only appear in entries with multiple senses.

> [!TIP]
>
> - Examples of **Show parent sense number** options with **Numbering Style** set to **A B C** and `)` in **After** box:
>
> - - **(none)** - A) \[the parent sense number, 1, is not displayed\]
>
>   - **Joined** - 1A)
>
>   - **Separated by dot** - 1.A)
>
> Select (![](../../../../assets/images/CheckedBox.PNG)) or clear (![](../../../../assets/images/User_Interface/Menus/Tools/UncheckedBox.PNG)) the **Number even a single sub**sense check box to show or not show subsense numbers on lone subsenses.
>
> - [Grammatical Info](Grammatical_Info.md) discusses the **If all senses share the grammatical information, show it first** check box.
>
> - **See Also:** [Display each sense in a paragraph](Display_each_sense_in_a_paragraph.md) and [Configure Headword Numbers](../Configure_Headword_Numbers/Config_Hdwrd_Numbers_dialog_box.md) dialog box.

## Related topics
**<a href="Configure_Dictionary.md" style="font-weight: normal;">Configure Dictionary dialog box</a>**

[Paragraph Style to display sense on new line](Display_each_sense_in_a_paragraph.md)

[Use right-click to help configure Dictionary](../../../../Using_Tools/Lexicon_tools/Dictionary/Use_right-click_to_help_configure_Dictionary_view.md)
