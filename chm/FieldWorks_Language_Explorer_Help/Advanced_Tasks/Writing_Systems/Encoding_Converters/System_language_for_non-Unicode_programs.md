---
title: "System language for non-Unicode programs"
source_title: "System language for non-Unicode programs"
breadcrumb:
  - "Advanced Tasks"
  - "Writing Systems"
  - "Encoding Converters"
  - "System language for non-Unicode programs"
source: "Advanced_Tasks/Writing_Systems/Encoding_Converters/System_language_for_non-Unicode_programs.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Advanced_Tasks/Writing_Systems/Encoding_Converters/System_language_for_non-Unicode_programs.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Language"
  - "Non-Unicode programs"
  - "System language for non-Unicode programs"
related:
  - "Encoding Converters overview -> Encoding_Converters_overview.md"
  - "Writing System Properties, Converters tab -> ../Modifying_a_Writing_System/Writing_System_Properties_Converters_tab.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:7c0906ccccdc9976"
---

# System language for non-Unicode programs

*Advanced Tasks › Writing Systems › Encoding Converters*

FieldWorks uses Unicode character encoding. The *Unicode Standard* is the universal character encoding scheme for written characters and text.

When you import Standard Format files from non-Unicode programs, FieldWorks automatically converts characters from the code page (that is, the set of character codes) of the system language (also known as the system locale).

*Most FieldWorks users will require [technical assistance](../../../Overview/Technical_support.md) with the system language.*

## Determine the system language

1.  Click **Start**, point to **Settings**, and then click **Control Panel**.

2.  Double-click **Regional and Language Options** *or* **Region**.

3.  In the **Region and Language** *or* **Region** dialog box, click the **Administrative** tab.

The language is stated below **Current Language for non-Unicode programs**.

4.  Click **Cancel**.

> [!IMPORTANT]
>
> - To select the system language, you must be logged on as an administrator or a member of the Administrators group. If your computer is connected to a network, network policy settings might prevent you from selecting the language.
>
> - This option enables non-Unicode programs to display menus and dialog boxes in their native language by installing the necessary code pages and fonts. However, programs designed for other languages might not display text correctly.
>
> - This option only affects non-Unicode programs. It does not affect the menus and dialog boxes in Windows<sup>®</sup> or other Unicode programs (for example, FieldWorks).

## Related topics
[Encoding Converters overview](Encoding_Converters_overview.md)

[Writing System Properties, Converters tab](../Modifying_a_Writing_System/Writing_System_Properties_Converters_tab.md)
