---
title: "About the Advanced writing system controls"
source_title: "About the Advanced writing system controls"
breadcrumb:
  - "Advanced Tasks"
  - "Writing Systems"
  - "Modifying a Writing System"
  - "About the advanced writing system controls"
source: "Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/About_the_Advanced_ws_controls.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/About_the_Advanced_ws_controls.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Writing System:Advanced check box"
  - "General tab"
  - "About:Advanced check box"
  - "About:Advanced writing system controls"
  - "Modify a writing system:About the advanced writing system controls"
related:
  - "Use the Advanced writing system controls -> Use_the_advanced_writing_system_controls.md"
  - "Writing Systems overview -> ../Writing_Systems_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:fda22cfa487e92e6"
---

# About the Advanced writing system controls

*Advanced Tasks › Writing Systems › Modifying a Writing System*

In the **General** [tab](Writing_System_Properties_General_tab.md) of the **Writing Systems Properties** dialog box, an **Advanced** check box can appear. If you select (![](../../../assets/images/CheckedBox.PNG)) it, you will see additional controls for script, region and variant information.

Before you [use](Use_the_advanced_writing_system_controls.md) these controls, review the information below.

- **BCP-47 Code** box

  - This box automatically updates to show the codes for your script and region, or your variant information. That is, it shows your *writing system tags*.

  - It is *not* recommended for most users, but you can manually type the entire code in this box if you know its syntax. In this case, the **Script**, **Region** or **Variant** boxes automatically update.

You can validate the syntax on the Internet here: <a href="https://schneegans.de/lv?tags=en-x-3ab&amp;format=text" target="_blank" title="https://schneegans.de/lv?tags=en-x-3ab&amp;format=text">https://schneegans.de/lv/?tags=en-x-3ab&amp;format=text</a>.

- A red background color in a box means you have not typed the correct number of letters or digits (numbers), or there is some other syntax problem.

  - The `Code` box for a script must have 4 letters. Typically, the first letter is capitalized.

  - The `Code` box for a region must have 2 letters or 3 digits.

  - The **Other Variants** box must begin with an IANA variant or **x-**, and must not end with a dash (-).

Anything after or between dashes is called a *subtag*. Subtags are limited to 8 letters or digits.

- **None** — Because all writing systems need a script, if you click **None** in the **Script** box drop-down list, the *default* script for the language (not **None**) appears. The default script does not appear in the code.\
  **None** can appear in the **Region** or **Standard Variant** boxes.

- **(Copy)** — If you see this in the `Writing System` list, you have writing systems that are the same.

Before you leave the writing system, make at least one change to distinguish this writing system from others.

- **![](../../../assets/images/Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/WarningIcon.png) Clear Advanced** warning box — It appears if you clear (![](../../../assets/images/User_Interface/Menus/Tools/UncheckedBox.PNG)) the **Advanced** check box any of the **General** tab. If you click **Yes**, all your advanced choices are discarded and the standard view appears with default selections for your language.

However, if you select (![](../../../assets/images/CheckedBox.PNG)) and use the **Advanced** check box, but all your script, region and variant information can appear completely in the standard view, the next time you open this dialog box, it will open with the **Advanced** check box cleared.

> [!NOTE]
>
> - In the FLEx user interface and in these Helps, *writing system* tags is typically used for what the most internet sites refer to as *language* tags. Examples:
>
> <a href="https://www.w3.org/International/questions/qa-choosing-language-tags" target="_blank">https://www.w3.org/International/questions/qa-choosing-language-tags</a>
>
> <a href="https://en.wikipedia.org/wiki/IETF_language_tag" target="_blank" title="https://en.wikipedia.org/wiki/IETF_language_tag">https://en.wikipedia.org/wiki/IETF_language_tag</a>
>
> - **(Copy)** — Here is an example:
>
> One writing system has **Special** set to **None**; and another one has **Special** set to **Script/Region/Variant** and **Script** set to the *default* script, but the other controls are set to **None**.
>
> - In the **General** tab, in either the standard view or when **Advanced** is selected, the **Script** control can show the *default* script for a language. However, the default script is not included in the **Code** that you see at the top of the **General** tab.

## Related topics
[Use the Advanced writing system controls](Use_the_advanced_writing_system_controls.md)

[Writing Systems overview](../Writing_Systems_overview.md)
