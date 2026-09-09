---
title: "Select the parent style"
source_title: "Select the parent style"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Format"
  - "Styles"
  - "Select the parent style"
source: "User_Interface/Menus/Format/Styles/Select_the_parent_style.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Format/Styles/Select_the_parent_style.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Parent"
  - "Select (See also: Specify or Choose):Parent style"
  - "select a"
related:
  - "Styles overview -> Styles_overview.md"
  - "Inheriting unspecified attributes -> Inheriting_unspecified_attributes.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:4ebd2ee1b83548db"
---

# Select the parent style

*User Interface › Menus › Format › Styles*

A style inherits unspecified attributes from the *parent style*. The parent style appears in the **Based on** box on the [General](Styles_General_tab.md) tab of the **Styles** dialog box.

Attributes that are not modified in the new style will retain the default settings (in gray color) from the parent style. Modify only the attributes that need to be different from the parent style.

New *character* styles are initially based on **Default Paragraph Characters**. If you [apply a style](../apply_a_style_to_text.md) that is based on **Default Paragraph Characters** to characters in a paragraph, the paragraph style determines the unspecified attributes.

New *paragraph* styles are initially based on **Normal**. The **Normal** style initially uses the **\<default font\>** (which is selected on the [Font](../../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_Fonts_tab.md) tab of the **Writing System Properties** dialog box). The colors for the font and background are set by Microsoft Windows<sup>®</sup>.

> [!NOTE]
>
> - Modifying attributes in new paragraph or character styles *do not change* the attributes in the parent style.
>
> - If you copy a style, the *specified* attributes of the copied style are transferred to the new style. The *unspecified* attributes of the copied style are *inherited* from its parent style.

## Related topics
[Styles overview](Styles_overview.md)

[Inheriting unspecified attributes](Inheriting_unspecified_attributes.md)
