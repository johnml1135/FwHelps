---
title: "Delete a custom field"
source_title: "Delete a custom field"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Tools"
  - "Custom Fields"
  - "Delete a Custom field"
source: "User_Interface/Menus/Tools/Custom_Fields/Delete_a_custom_field.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Tools/Custom_Fields/Delete_a_custom_field.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Delete:Custom field"
  - "Custom Fields:Delete a custom field"
related:
  - "Custom Fields overview -> Custom_Fields_overview.md"
  - "Tools overview -> ../Tools_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:eb2f624c5609f157"
---

# Delete a custom field

*User Interface › Menus › Tools › Custom Fields*

### Prerequisites

- You *cannot* use **Undo** (`Ctrl+Z`) to restore a deleted custom field. Any data in the custom field is *lost* when it is deleted. It is recommended that you [back up](../../File/Backup_and_Restore/Back_up_this_Project.md) the language project before you continue.

Do the following steps:

1.  In the **Navigation** **Pane**, click the [area](../../../Toolbars/Navigation/Navigation_Pane_overview.md) that has the custom field that you want to delete.

2.  On the **Tools** menu, point to **Configure**, and then click **Custom Fields**.

    The **Custom Fields** dialog box appears.

3.  In the **Custom Fields** pane, click the custom field you want to delete, and then click **Delete**.

    If the custom field was never used, it is deleted and the dialog box closes.

    If one or more occurrences of the custom field contain data, the **Really delete field and contents?** warning box appears. It gives you information about field usage.

    In this case, do the following steps.

    - If you are sure that you want to delete the selected custom field, click **OK**.

      The custom field is removed from the list of custom fields in this dialog box. *However*, it *remains* in the language project while the **Custom Fields** dialog box is displayed.

      As a result, you *cannot immediately* add another custom field with the *same* name as the deleted one. You need to complete the deletion process (below) before you can [add that new custom field](add_a_custom_field.md). If the name is *different*, you can add a new field now.

    - Do one of the following:

      Click **Cancel** to close the **Custom Fields** dialog box and *keep* the custom field.

      Click **OK** to close the **Custom Fields** dialog box and *delete* the custom field from the project.

## Related topics
[Custom Fields overview](Custom_Fields_overview.md)

[Tools overview](../Tools_overview.md)
