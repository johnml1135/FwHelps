---
title: "Select the converter type"
source_title: "Select the converter type"
breadcrumb:
  - "Advanced Tasks"
  - "Writing Systems"
  - "Encoding Converters"
  - "Select the converter type"
source: "Advanced_Tasks/Writing_Systems/Encoding_Converters/Select_the_converter_type.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Advanced_Tasks/Writing_Systems/Encoding_Converters/Select_the_converter_type.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Converters"
  - "Select (See also: Specify or Choose):Converter type"
  - "select a"
  - "TECkit"
  - "CC (Consistent Changes)"
related:
  - "Encoding Converters, Properties tab -> Encoding_Converters_Properties_tab.md"
  - "Python and Perl overview -> Python_Perl_overview.md"
  - "Writing System Properties, Converters tab -> ../Modifying_a_Writing_System/Writing_System_Properties_Converters_tab.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:423cd01cb6f43e2c"
---

# Select the converter type

*Advanced Tasks › Writing Systems › Encoding Converters*

On the **Properties** tab of the **Encoding Converters** dialog box, the **Converter Type** list determines the options for the [converter mapping](Select_the_converter_mapping.md) and [conversion type](Select_the_conversion_type.md).

- Click the down arrow in the **Converter Type** box, and then select one of the items in the list.

  Use the descriptions below to help you choose.

## Convert from an industry standard encoding

- **Windows Code Page** is for character sets that are defined by Microsoft Windows<sup>®</sup> (for example, code page 1251 Cyrillic Windows).

- **ICU** (International Components for Unicode) also converts character sets.

## Convert from any other legacy (non-Unicode) encoding

- **CC** (Consistent Changes) can use rules in a change table to convert a set of non-standard (custom) characters to UTF-8. (UTF-8 is a variable length encoding of the Unicode Standard that uses 8-bit sequences.)

- **TECkit** (Text Encoding Conversion toolkit) can also convert characters to Unicode.

> [!TIP]
>
> - ICU can also *transliterate* from one script to another (Unicode to Unicode).
>
> - TECkit mapping files can be in either *source* or *compiled* format.
>
> - TECkit converters may be written for bidirectional operation. In FLEx, operations are normally one way. However, if you need to run a bidirectional converter in the reverse direction, it can be done in FLEx. To do this, click the **More** button next to the **Converter Type**, then add a **Compound Converter** through the dialog that comes up. If you add a bidirectional converter in the **Setup** tab, there is a **Reverse** check box that will run it in the reverse direction.
>
> - The ICU, CC, and TECkit converter *software* is installed on your computer with FieldWorks. Because CC and TECkit convert from non-standard encodings, you need to provide the *mapping file* (for example, the change table).
>
> - FieldWorks automatically converts characters from the code page of the [system language for non-Unicode programs](System_language_for_non-Unicode_programs.md) (also known as the system locale).
>
> - **Regular Expression (ICU)** allows you to enter a regular expression directly in the dialog box (**Find-\>Replace box**).

## Related topics
[Encoding Converters, Properties tab](Encoding_Converters_Properties_tab.md)

[Python and Perl overview](Python_Perl_overview.md)

[Writing System Properties, Converters tab](../Modifying_a_Writing_System/Writing_System_Properties_Converters_tab.md)
