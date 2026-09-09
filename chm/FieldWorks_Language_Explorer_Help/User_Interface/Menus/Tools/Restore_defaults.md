---
title: "Restore defaults"
source_title: "Restore defaults"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Tools"
  - "Configure_Restore Defaults"
  - "Restore defaults"
source: "User_Interface/Menus/Tools/Restore_defaults.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Tools/Restore_defaults.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Restore:Restore default settings"
  - "Dictionary:Using the Configure Dictionary dialog box"
  - "Default:Restore default settings"
  - "Visibility"
  - "field"
  - "Field visibility settings"
  - "Reset:Defaults"
  - "Restore"
related:
  - "Technical Support -> ../../../Overview/Technical_support.md"
  - "Tools overview -> Tools_overview.md"
fw_help_version: "9.3"
page_heading: "Restore default settings"
type: "topic"
content_hash: "sha256:8356e9ee2c9d46cb"
---

# Restore defaults

*User Interface › Menus › Tools › Configure_Restore Defaults*

The **Restore Defaults** command on the **Tools** menu allows you to restore *some* default (factory) settings for the current language project. When you restore default settings, *most* of the files in the **ConfigurationSetting** [folder](../File/Backup_and_Restore/Folder_Structure.md) are deleted. If you want to keep these settings files, [back up the project](../File/Backup_and_Restore/Back_up_this_Project.md) before you restore defaults.

|  |  |
|----|----|
| Settings that are restored include: | Settings that are *not* restored include: |
| Dialog boxes you set to *do not display* will appear again. | [Classified Dictionary](Configure_Classified_Dictionary/Configure_Classified_Dictionary_View_dlgbox.md) |
| [Document](Configure_Document/Configure_Document_View_dialog_box.md) | [Choose Texts](../../../Basic_Tasks/Filtering_data/Choose_Texts.md) selections |
| [Field visibility settings](../../../Basic_Tasks/Showing_and_hiding_fields/change_the_visibility_of_fields.md) | Column [sorts](../../../Basic_Tasks/Sorting_data/Sorting_data_overview.md) and [filters](../../../Basic_Tasks/Filtering_data/filtering_data_overview.md) |
| Toolbars you [moved](../../Changing_toolbars_and_menus/Move_a_toolbar.md) | Custom views ([Dictionary](Configure_Dictionary/Manage_Dictionary_Views.md), [Reversal Indexes](Configure_Reversal_Index/Manage_Views_Reversal_Index.md), [Document](Configure_Document/Manage_Document_Views.md)) |
| Window and pane sizes, and locations | [Dictionary views](Configure_Dictionary/Dictionary_views.md) |
|  | **Linked Files** [folders](../File/Backup_and_Restore/Folder_Structure.md) |
|  | [Interlinear lines](Configure_interlinear_lines_dialog_box.md) |
|  | [Reversal Indexes](Configure_Reversal_Index/Configure_Reversal_Index_dialog_box.md) |
|  | [Selected spelling dictionaries](../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_General_tab.md) |
|  | [Styles](../Format/Styles/Styles_overview.md) |
|  | [Writing system](../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Using_the_Writing_System_Properties_dialog_box.md) settings (fonts, sizes, colors and so on) |

Do these steps:

1.  On the **Tools** menu, point to **Configure**, and then click **Restore Defaults**.

2.  In the **Restore Defaults** dialog box, click **Yes**.

> [!IMPORTANT]
>
> Reasons to use this feature include:
>
> - If you want to clear all the configured settings that are listed in the left column above. Custom fields are *not* removed or changed.
>
> - If FieldWorks' settings files become out of sync, you may experience a [problem](../../../Overview/information_for_bug_reports.md) with the program. Some of these problems may be resolved by restoring the default settings.
>
> - - A *more extensive* way to reset setting is to start Language Explorer with the **Shift** key held down. This resets *more* settings, such as interlinear lines, column filters and sorts, and so on. However, some settings remain, such as writing systems and styles.
>
> Similar to **Restore Defaults**, most of the files are deleted from the **ConfigurationSettings** folder when you start with **Shift** key held down. You can *also* see a significant reduction in the size of the files that remain after starting with the **Shift** key held down.

## Related topics
[Technical Support](../../../Overview/Technical_support.md)

[Tools overview](Tools_overview.md)
