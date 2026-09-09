---
title: "About encoding converters"
source_title: "About encoding converters"
breadcrumb:
  - "Beginning Tasks"
  - "Importing Data"
  - "About encoding converters"
source: "Beginning_Tasks/Importing_Data/About_encoding_converters.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Beginning_Tasks/Importing_Data/About_encoding_converters.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Encoding Converters"
  - "Encoding Converters:About encoding converters"
  - "About:Encoding converters"
related:
  - "Import Standard Format lexical data -> Import_Standard_Format_lexical_data.md"
  - "Encoding Converters overview -> ../../Advanced_Tasks/Writing_Systems/Encoding_Converters/Encoding_Converters_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:8297ba8ffe733846"
---

# About encoding converters

*Beginning Tasks › Importing Data*

The following discussion is *not* exhaustive, but is offered to help you determine the need for an [encoding converter](../../Advanced_Tasks/Writing_Systems/Encoding_Converters/Encoding_Converters_overview.md) in the context of importing SFM lexical data into FieldWorks Language Explorer (FLEx).

## Do I need an encoding converter, and if so, which one?

- If your data uses only ASCII character (a-z, A-Z, 0-9, and basic punctuation), then you do *not* need an encoding converter. You can use **Already in Unicode** or **Windows1252****\<****\>****Unicode**.

- If your data uses *any* diacritics, then you *may* or *may* *not* need an encoding converter.

  - If you are using a standard Windows<sup>®</sup> font, such as Times New Roman in **Shoebox**, then you should use the supplied **Windows1252\<\>Unicode** converter because **Shoebox** does *not* support Unicode.

  - If you are using **Toolbox**, use **Project** **&** **Language Encodings**, click each language and select **Modify**. Go to the **Options** tab and click **Advanced**. If the **Unicode (UTF-****8)** check box has a check mark, then it probably means that your data is in Unicode, so you would choose **Already in Unicode** as the converter.

- If you are using a custom (hacked) non-Unicode font supplied by your branch or someone else, then you will definitely need a custom converter to convert your data into Unicode.

- If you choose the wrong encoding converter, some of your data will look incorrect once in FLEx. In this case, you will usually need to choose a different converter.

> [!NOTE]
>
> - The **Bulk Edit Entries** features ([Lexicon](../../Using_Tools/Lexicon_tools/Lexicon_overview.md)) use [processors](../../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Using_Setup_Processor_dialog_box.md).

## Related topics
[Import Standard Format lexical data](Import_Standard_Format_lexical_data.md)

[Encoding Converters overview](../../Advanced_Tasks/Writing_Systems/Encoding_Converters/Encoding_Converters_overview.md)

### Related Internet sites

<a href="https://software.sil.org/silconverters/" target="_blank" title="https://software.sil.org/silconverters/">https://software.sil.org/silconverters/</a>

<a href="https://software.sil.org/fieldworks/support/technical-documents/" target="_blank" title="https://software.sil.org/fieldworks/support/technical-documents/">https://software.sil.org/fieldworks/support/technical-documents/</a>
