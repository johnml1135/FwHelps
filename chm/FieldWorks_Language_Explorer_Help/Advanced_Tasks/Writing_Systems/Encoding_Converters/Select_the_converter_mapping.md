---
title: "Select the converter mapping"
source_title: "Select the converter mapping"
breadcrumb:
  - "Advanced Tasks"
  - "Writing Systems"
  - "Encoding Converters"
  - "Select the converter mapping"
source: "Advanced_Tasks/Writing_Systems/Encoding_Converters/Select_the_converter_mapping.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Advanced_Tasks/Writing_Systems/Encoding_Converters/Select_the_converter_mapping.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Converters"
  - "Select (See also: Specify or Choose):Converter mapping"
  - "select a"
  - "TECkit"
  - "CC (Consistent Changes)"
related:
  - "Encoding Converters, Properties tab -> Encoding_Converters_Properties_tab.md"
  - "Writing System Properties, Converters tab -> ../Modifying_a_Writing_System/Writing_System_Properties_Converters_tab.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:41609dc4f9ff6988"
---

# Select the converter mapping

*Advanced Tasks › Writing Systems › Encoding Converters*

On the **Properties** tab of the **Encoding Converters** dialog box, the [converter type](Select_the_converter_type.md) determines the options for the converter mapping.

|  |  |
|----|----|
| Converter Type | To select the converter mapping |
| CC | In the **Converter Mapping File** box, enter the path to a Consistent Change table file that converts from a non-standard (custom) encoding to UTF-8. |
| ICU legacy converter | In the **Mapping Name** list, select an industry standard character set. |
| ICU Unicode to Unicode transducer | In the **Mapping Name** list, select a transformation *from Unicode to Unicode* (for example, a transliteration from one script to another). |
| TECkit (compiled TEC file) | In the **Converter Mapping File** box, enter the path to a Text Encoding Conversion toolkit *compiled* file. |
| TECkit (source MAP file) | In the **Converter Mapping File** box, enter the path to a Text Encoding Conversion toolkit *source* file. |
| Windows Code Page | In the **Code Page** list, select a code page (that is, a character set that is defined by Microsoft Windows<sup>®</sup>). |

> [!TIP]
>
> - To navigate to an external conversion file, you can click the ellipsis button ![](../../../assets/images/Ellipsis_button.PNG) to the right of the **Converter Mapping File** box.
>
> - If you select a TECkit *source* file, changes to the file will affect the next conversion. If you select a *compiled* file, make sure to recompile after you edit the source file.

## Related topics
[Encoding Converters, Properties tab](Encoding_Converters_Properties_tab.md)

[Writing System Properties, Converters tab](../Modifying_a_Writing_System/Writing_System_Properties_Converters_tab.md)
