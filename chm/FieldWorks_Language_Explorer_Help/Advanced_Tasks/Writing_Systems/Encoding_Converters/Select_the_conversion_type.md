---
title: "Select the conversion type"
source_title: "Select the conversion type"
breadcrumb:
  - "Advanced Tasks"
  - "Writing Systems"
  - "Encoding Converters"
  - "Select the conversion type"
source: "Advanced_Tasks/Writing_Systems/Encoding_Converters/Select_the_conversion_type.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Advanced_Tasks/Writing_Systems/Encoding_Converters/Select_the_conversion_type.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Converters"
  - "Conversion type"
  - "Select (See also: Specify or Choose):Conversion type"
  - "select a"
  - "Unicode"
  - "TECkit"
  - "CC (Consistent Changes)"
related:
  - "Encoding Converters, Properties tab -> Encoding_Converters_Properties_tab.md"
  - "Writing System Properties, Converters tab -> ../Modifying_a_Writing_System/Writing_System_Properties_Converters_tab.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:f0ca9bc1fe531f70"
---

# Select the conversion type

*Advanced Tasks › Writing Systems › Encoding Converters*

On the **Properties** tab of the **Encoding Converters** dialog box, the [converter type](Select_the_converter_type.md) determines the *most likely* conversion type to *import* Standard Format files.

FieldWorks uses the Unicode character encoding. The *Unicode Standard* is the universal character encoding scheme for written characters and text.

A *legacy encoding* is any non-Unicode encoding, including earlier international, national, and industry standards, as well as non-standard (custom) encodings.

<table width="100%">
<tbody>
<tr>
<th style="width: 50%"><p>Converter Type</p></th>
<th style="width: 50%"><p>Conversion Type</p></th>
</tr>
&#10;<tr>
<td style="width: 50%"><p>CC</p></td>
<td style="width: 50%"><p>Legacy to Unicode</p></td>
</tr>
<tr>
<td style="width: 50%"><p>ICU legacy converter</p></td>
<td style="width: 50%"><p>Legacy to Unicode*</p></td>
</tr>
<tr>
<td style="width: 50%"><p>ICU Unicode to Unicode transducer</p></td>
<td style="width: 50%"><p>Unicode to Unicode**</p></td>
</tr>
<tr>
<td style="width: 50%"><p>TECkit</p></td>
<td style="width: 50%"><p>Legacy to Unicode<br />
Legacy to and from Unicode<br />
to and from Legacy</p></td>
</tr>
<tr>
<td style="width: 50%"><p>Windows Code Page</p></td>
<td style="width: 50%"><p>Legacy to Unicode*</p></td>
</tr>
</tbody>
</table>

\*If you use the encoding converter for other purposes than importing Standard Format files, you might select **Legacy to and from Unicode** or **Unicode to and from Legacy**.

\*\*If you use the encoding converter for other purposes than importing Standard Format files, you might select **Unicode to and from Unicode**.

> [!IMPORTANT]
>
> - CC [mapping files](Select_the_converter_mapping.md) that convert from legacy encodings to Unicode (that is, UTF-8) must have rules for *every possible input character* to ensure that the output is valid.

## Related topics
[Encoding Converters, Properties tab](Encoding_Converters_Properties_tab.md)

[Writing System Properties, Converters tab](../Modifying_a_Writing_System/Writing_System_Properties_Converters_tab.md)
