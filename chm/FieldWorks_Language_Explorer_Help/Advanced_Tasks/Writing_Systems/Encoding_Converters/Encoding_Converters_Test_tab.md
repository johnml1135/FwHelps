---
title: "Encoding Converters, Test tab"
source_title: "Encoding Converters, Test tab"
breadcrumb:
  - "Advanced Tasks"
  - "Writing Systems"
  - "Encoding Converters"
  - "Encoding Converters, Test tab"
source: "Advanced_Tasks/Writing_Systems/Encoding_Converters/Encoding_Converters_Test_tab.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Advanced_Tasks/Writing_Systems/Encoding_Converters/Encoding_Converters_Test_tab.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Encoding Converters"
  - "Test tab for Encoding Converters"
related:
  - "Encoding Converters overview -> Encoding_Converters_overview.md"
  - "Writing System Properties, Converters tab -> ../Modifying_a_Writing_System/Writing_System_Properties_Converters_tab.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:68d739ca87480b69"
---

# Encoding Converters, Test tab

*Advanced Tasks › Writing Systems › Encoding Converters*

Encoding converters *input* text in one character encoding and *output* the text in another character encoding. Before you use an encoding converter to import from Standard Format, you can test it to make sure that it outputs text in the *correct encoding* for the writing system in FieldWorks.

1.  In the **Available Converters** list, select an encoding converter.

2.  Click **Select Input File**.

    The **Open** dialog box appears.

    - Navigate to the appropriate folder, click the file that contains the input text, and then click **Open**.

3.  In the **Output font** list, select an appropriate font to display the output text in the **Converted** box.

4.  To convert the input text using the selected encoding converter, click **Convert**.

    The output text appears in the **Converted** box.

5.  If want to save the output text in the **Converted** box, click **Save to File**.

    The **Save As** dialog box appears. (Navigate to the appropriate folder in the **Save in** list, enter the **File name**, and then click **Save**.)

> [!NOTE]
>
> - The input file is not changed, unless you save the output text to it.
>
> - If the output data type of the encoding converter is Unicode, the output text is saved to a file with UTF-8 encoding.
>
> - You cannot copy text from the **Converted** box.

## Related topics
[Encoding Converters overview](Encoding_Converters_overview.md)

[Writing System Properties, Converters tab](../Modifying_a_Writing_System/Writing_System_Properties_Converters_tab.md)
