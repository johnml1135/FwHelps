---
title: "Use the advanced writing system controls"
source_title: "Use the advanced writing system controls"
breadcrumb:
  - "Advanced Tasks"
  - "Writing Systems"
  - "Modifying a Writing System"
  - "Use the Advanced writing system controls"
source: "Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Use_the_advanced_writing_system_controls.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Use_the_advanced_writing_system_controls.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Writing System:Advanced check box"
  - "General tab"
  - "Advanced check box"
  - "Advanced tasks:Advanced check box"
  - "Use or Using:Use the advanced writing system controls"
related:
  - "Modifying \n a writing system overview -> Modifying_a_writing_system_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:b0299bfdcefbee75"
---

# Use the advanced writing system controls

*Advanced Tasks › Writing Systems › Modifying a Writing System*

- Review [About the Advanced writing system controls](About_the_Advanced_ws_controls.md).

If you need to work with script, regional and variant information beyond what you can do in the standard view of the **General** [tab](Writing_System_Properties_General_tab.md), do these steps:

1.  [Open](Open_Writing_System_Properties_dlgbox.md) the **Writing System Properties** dialog box if it is not already open.

2.  Click the **General** tab.

If **Special** shows **Script/Region/Variant**, and you have made at least one change, then the **Advanced** check box appears.

3.  Select (![](../../../assets/images/CheckedBox.PNG)) **Advanced**.

4.  Do any of these steps in the displayed boxes:

    - **Script** — Click the down arrow and then click an option or **None**.

The **Name** and **Code** boxes are automatically updated. You cannot edit them.

Click **Private Use Script (Qaaa)** to set a *private-use* script. In this case you can edit the contents in the **Name** and **Code** boxes to make the writing system unique. See ![](../../../assets/images/Important_Icon.gif) **Important** below.

3.  - **Region** — Click the down arrow and then click an option or **None**.

The **Name** and **Code** boxes are automatically updated. You cannot edit them.

Click **Private Use Region (QM)** to set a *private-use* region. In this case, you can edit the contents in the **Name** and **Code** boxes to make the writing system unique.

3.  - **Standard Variant** — Click the down arrow and then click an option or **None**.

<!-- -->

3.  - **Other Variants** — Click the box and type additional information to define the variant.

The **BCP-47 Code** box automatically updates to show the standard variant you chose.

> [!IMPORTANT]
>
> - **Qaaa** is used by SIL for and as a private use convention. Therefore, when you use **Qaaa** in SIL software we can store a custom script name in our project data, and a custom script code in the private use area of the language code.
>
> If you think you need to use another private use script, please [get technical support](../../../Overview/Technical_support.md) to avoid problems.

## Related topics
[Modifying a writing system overview](Modifying_a_writing_system_overview.md)
