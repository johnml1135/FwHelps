---
title: "Hide or show a writing system"
source_title: "Hide or show a writing system"
breadcrumb:
  - "Advanced Tasks"
  - "Writing Systems"
  - "Modifying a Writing System"
  - "Hide or show a writing system"
source: "Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Hide_or_show_a_writing_system.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Hide_or_show_a_writing_system.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Writing System:Hide or show a writing system"
  - "Show:Hide or show a writing system"
  - "Hide:Hide or show a writing system"
related:
  - "Get more help -> ../../../Overview/Technical_support.md"
  - "Modifying a writing system overview -> Modifying_a_writing_system_overview.md"
  - "Writing systems overview -> ../Writing_Systems_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:8bf40e493a6002f0"
---

# Hide or show a writing system

*Advanced Tasks › Writing Systems › Modifying a Writing System*

[Showing Writing Systems overview](../../../Basic_Tasks/Showing_Writing_Systems/Show_WSs_overview.md) describes two ways to reduce the amount of scrolling you might need to do when you have multiple writing systems.

## Hide a writing system

When you hide a writing system, here is what happens:

- That writing system is removed from the **Writing Systems** pane. It will not be available when you [configure](../../../Basic_Tasks/Showing_Writing_Systems/configure_field_WSs.md) writing systems for fields or as a [baseline](../../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/baseline_text_writing_systems.md) writing system for texts, or other places where you can choose writing systems.

- Existing data that use it remain in the project, but are normally not shown. Reversal Indexes are hidden. Texts with a hidden baseline writing system remain in view, but cannot be glossed or analyzed.

- If you hide a *vernacular* writing system that was *never used*, it is *deleted*.\
  It will not appear in the **Hidden Writing Systems** dialog box. In this case, if you add that vernacular writing system again, the definitions you set in the various [tabs](Modifying_a_writing_system_overview.md) are remembered.

If you want to hide a writing system, do these steps:

1.  [Open](Open_Writing_System_Properties_dlgbox.md) the **Writing System Properties** dialog box.

2.  In the **Writing Systems** pane, right-click a writing system and then click **Hide**.

## Show a writing system that was hidden

You can add a hidden writing system back to the list of writing systems. In addition, you can add a writing system that was previously only a vernacular or analysis writing system so it appears in [both](../Add_a_new_writing_system/About_Writing_Systems.md) lists.

1.  [Open](Open_Writing_System_Properties_dlgbox.md) the **Writing System Properties** dialog box for the vernacular or analysis writing systems, as needed.

2.  Click the ![](../../../assets/images/Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Add_Button.png) button and then **View hidden Writing Systems**.

The **Hidden Writing System** dialog box appears with a list of writing systems.

3.  Click the writing system you want to add and then click **Add**.

4.  Click **Close**.

> [!WARNING]
>
> - **Delete** will delete all the data that use the selected writing system.
>
> [Delete a writing system](Delete_a_writing_system.md) has important information to read before you delete one.

## Related topics
[Get more help](../../../Overview/Technical_support.md)

[Modifying a writing system overview](Modifying_a_writing_system_overview.md)

[Writing systems overview](../Writing_Systems_overview.md)
