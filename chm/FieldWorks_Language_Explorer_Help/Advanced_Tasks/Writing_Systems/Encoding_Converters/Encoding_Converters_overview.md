---
title: "Encoding Converters overview"
source_title: "Encoding Converters overview"
breadcrumb:
  - "Advanced Tasks"
  - "Writing Systems"
  - "Encoding Converters"
  - "Encoding Converters overview"
source: "Advanced_Tasks/Writing_Systems/Encoding_Converters/Encoding_Converters_overview.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Advanced_Tasks/Writing_Systems/Encoding_Converters/Encoding_Converters_overview.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Writing System:Encoding Converters overview"
  - "Encoding Converters"
  - "Encoding Converters:Encoding Converters overview"
  - "Converters"
  - "Converters:Encoding Converters overview"
  - "Unicode"
  - "Advanced tasks:Encoding Converters overview"
  - "Python or Perl:Encoding Converters overview"
  - "Perl or Python:Encoding Converters overview"
related:
  - "Python and Perl overview -> Python_Perl_overview.md"
  - "Technical Support -> ../../../Overview/Technical_support.md"
  - "Writing Systems overview -> ../Writing_Systems_overview.md"
  - "Writing System Properties, Converters tab -> ../Modifying_a_Writing_System/Writing_System_Properties_Converters_tab.md"
fw_help_version: "9.3"
type: "index"
content_hash: "sha256:f2fa8a54e6320aee"
---

# Encoding Converters overview

*Advanced Tasks › Writing Systems › Encoding Converters*

FieldWorks uses Unicode character encoding. The *Unicode Standard* is the universal character encoding scheme for written characters and text.

Select an [encoding converter](../../../Beginning_Tasks/Importing_Data/About_encoding_converters.md) for a writing system *only* to [import](../../../Beginning_Tasks/Importing_Data/Import_overview.md) standard format files in which *some of the imported text does* *not* *meet either* of the following requirements:

- It is encoded in Unicode (for example, in UTF-8, which is a variable length encoding of the Unicode Standard that uses 8-bit sequences).

- Its encoding is compatible with the [system language for non-Unicode programs](System_language_for_non-Unicode_programs.md).

*Most FieldWorks users will require technical assistance with encoding converters.*

1.  If you need to add, copy, modify, or remove a converter, on the [Converters](../Modifying_a_Writing_System/Writing_System_Properties_Converters_tab.md) tab of the **Writing System Properties** dialog box, click **More**.

    The **Encoding Converters** dialog box appears.

2.  Do any of the following:

    - To [add, modify or remove](Encoding_Converters_Properties_tab.md) a converter, click the **Properties** tab.

    - To [convert sample text](Encoding_Converters_Test_tab.md), click the **Test** tab.

    - To [see the property values](Encoding_Converters_Advanced_tab.md) of a converter, click the **Advanced** tab.

3.  Click **Close**.

> [!IMPORTANT]
>
> - Be aware that the selection in the **Encoding converter for importing** \<language\> (**Converters** tab) *also changes if you select a different encoding converter* in the **Available Converters** list.

## Related topics
[Python and Perl overview](Python_Perl_overview.md)

[Technical Support](../../../Overview/Technical_support.md)

[Writing Systems overview](../Writing_Systems_overview.md)

[Writing System Properties, Converters tab](../Modifying_a_Writing_System/Writing_System_Properties_Converters_tab.md)

### Related Internet sites

<a href="https://software.sil.org/silconverters/" target="_blank" title="https://software.sil.org/silconverters/">https://software.sil.org/silconverters/</a>

<a href="https://software.sil.org/fieldworks/support/technical-documents/" target="_blank" title="https://software.sil.org/fieldworks/support/technical-documents/">https://software.sil.org/fieldworks/support/technical-documents/</a>
