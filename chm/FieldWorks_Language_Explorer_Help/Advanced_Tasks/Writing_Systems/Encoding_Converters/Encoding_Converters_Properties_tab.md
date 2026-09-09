---
title: "Encoding Converters, Properties tab"
source_title: "Encoding Converters, Properties tab"
breadcrumb:
  - "Advanced Tasks"
  - "Writing Systems"
  - "Encoding Converters"
  - "Encoding Converters, Properties tab"
source: "Advanced_Tasks/Writing_Systems/Encoding_Converters/Encoding_Converters_Properties_tab.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Advanced_Tasks/Writing_Systems/Encoding_Converters/Encoding_Converters_Properties_tab.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Delete:Processor"
  - "Delete:Encoding converter"
  - "Encoding Converters"
  - "Change:Properties of a processor"
  - "Properties"
related:
  - "Encoding Converters overview -> Encoding_Converters_overview.md"
  - "Writing System Properties, Converters tab -> ../Modifying_a_Writing_System/Writing_System_Properties_Converters_tab.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:9aecb3fe144e0644"
---

# Encoding Converters, Properties tab

*Advanced Tasks › Writing Systems › Encoding Converters*

On the **Properties** tab, you can add, copy, modify, and delete encoding converters. Any encoding converter change (addition, modification, and so on) you make affects all FieldWorks programs and all language projects. Further, because they are stored outside of FieldWorks, the change also affects all other programs that use encoding converters.

## Add an encoding converter

- Do the steps in [Add an encoding converter](Add_Encoding_Converter.md).

## Copy an encoding converter

You *cannot* copy an encoding converter that was [added](Add_Encoding_Converter.md) with the **More** button.

- In the **Available Converters** list, select an encoding converter, click **Copy**, and then modify the properties.

## Modify an encoding converter

- In the **Available Converters** list, select an encoding converter, and then do one of the following:

  - If the boxes and lists are available, modify the properties on the **Properties** tab.

  - If the boxes and lists are *not* available, click **Modify**.

## Delete an encoding converter

- In the **Available Converters** list, select an encoding converter, and then click **Delete**.\
  The selected encoding converter is removed from the language project, both here as an encoding converter *and* as a [processor](../../../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Delete_a_Processor.md) for bulk edit.

> [!IMPORTANT]
>
> - When you remove the information about an encoding converter/processor from FieldWorks, it *does not delete* any external mapping files.
>
> - The selection in the **Encoding converter** list for the writing system *changes if you select an encoding converter* in the **Available Converters** list.

## Related topics
[Encoding Converters overview](Encoding_Converters_overview.md)

[Writing System Properties, Converters tab](../Modifying_a_Writing_System/Writing_System_Properties_Converters_tab.md)
