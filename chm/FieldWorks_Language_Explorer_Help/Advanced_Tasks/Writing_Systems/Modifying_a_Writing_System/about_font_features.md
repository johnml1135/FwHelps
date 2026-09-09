---
title: "About Font Features"
source_title: "About Font Features"
breadcrumb:
  - "Advanced Tasks"
  - "Writing Systems"
  - "Modifying a Writing System"
  - "About Font Features"
source: "Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/about_font_features.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/about_font_features.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "About:Font Features"
  - "Diacritics"
  - "split cursor"
  - "Split cursor"
  - "with diacritics"
  - "Cursor"
  - "split with diacritics"
  - "Function Keys"
  - "used in Language Explorer"
related:
  - "Using the Writing System Properties dialog box -> Using_the_Writing_System_Properties_dialog_box.md"
  - "Writing Systems overview -> ../Writing_Systems_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:25250bb211962adc"
---

# About Font Features

*Advanced Tasks › Writing Systems › Modifying a Writing System*

For Charis SIL, Doulos SIL and other graphite-enabled fonts, you can select **Enable Graphite** in the [Font](Writing_System_Properties_Fonts_tab.md) tab of the **Writing System Properties** dialog box. Then, the **Font Features** button becomes available in the **Font** tab. There is separate **Font Features** button in the [Font](../../../User_Interface/Menus/Format/Styles/Styles_Font_tab.md) tab of the **Styles** dialog box which allows you to specify font features for a particular style.

**Font Features** buttons display menus which provide optional ways to indicate variant renderings (alternately-designed glyphs) using the same font. You can select one or more options.

Also, the **Font Features** menu usually includes **Diacritic Selection**.

- Select (![](../../../assets/images/Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/CheckMark.GIF)) **Diacritic Selection** to enable the insertion point to split when you use the `Left Arrow` and **Right Arrow** keys to move it. That is, the arrow keys will move the insertion point *by* *code point* instead of *by character cluster*. (See **Tip** below.)

- Clear **Diacritic Selection** to disable the split insertion point feature. In this case, the insertion point moves over a base character and its diacritic(s) with one press of an arrow key.

> [!IMPORTANT]
>
> - The `F7` and `F8` keys move the insertion point *by code point* (left or right respectively), regardless if **Diacritic Selection** is selected or cleared.
>
> - For fonts *other than* Charis SIL or Doulos SIL that have diacritics but for which the **Font Features** button or **Diacritic Selection** is *not* available, you can set a registry key and value to enable a split insertion point (split cursor) when you use the arrow keys. To do this:
>
> - Double-click the batch file that was installed with FieldWorks:
>
> - C:\Program Files\SIL\FieldWorks 9\Arrow by character.reg
>
> This batch file sets the HKEY_CURRENT_USER\Software\SIL\FieldWorks **ArrowByCharacter** string value to True.
>
> (False disables the split insertion point when you use the arrow keys.)

> [!TIP]
>
> - The sample below shows consecutive insertion point positions and shapes as it moves left-to-right through the letters k, u and its diacritic.
>
> ![](../../../assets/images/Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Split_cursor.GIF)
>
> - This may be particularly important when you [edit morpheme breaks](../../../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/Insert_or_remove_morpheme_breaks.md).
>
> - **See Also:** *Settings files and registry.doc* at <a href="https://software.sil.org/fieldworks/support/technical-documents/" target="_blank" title="https://software.sil.org/fieldworks/support/technical-documents/">https://software.sil.org/fieldworks/support/technical-documents/</a>.
>
> - For more information, CharisSIL-features.pdf, DoulosSIL-features.pdf and possibly other similar files were installed with fonts by FieldWorks. For example: C:\Program Files\SIL\Fonts\DoulosSIL\documentation

## Related topics
[Using the Writing System Properties dialog box](Using_the_Writing_System_Properties_dialog_box.md)

[Writing Systems overview](../Writing_Systems_overview.md)
