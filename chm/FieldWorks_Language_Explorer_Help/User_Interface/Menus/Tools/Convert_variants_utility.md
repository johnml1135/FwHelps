---
title: "Convert variants utility"
source_title: "Convert variants utility"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Tools"
  - "Utilities"
  - "Convert variants utility"
source: "User_Interface/Menus/Tools/Convert_variants_utility.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Tools/Convert_variants_utility.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Irregularly Inflected Form (variants):Convert variants utility"
  - "Variant Forms:Convert variants utility"
  - "Convert:Convert variants utility"
related:
  - "About Variant Types -> ../../../Using_Tools/Lists_tools/About_Variants.md"
  - "Tools overview -> Tools_overview.md"
fw_help_version: "9.3"
page_heading: "Convert variants utilities"
type: "topic"
content_hash: "sha256:c9c021405848e0de"
---

# Convert variants utility

*User Interface › Menus › Tools › Utilities*

Here are two of the utilities in the **FieldWorks Project Utility** dialog box:

- **Convert variants to irregularly inflected form variants**

This utility allows you to select one or more variant types and convert them to be *irregularly* inflected form variants.

This *adds* [Append to Gloss](../../Field_Descriptions/Lists/Variant_Types_flds/Append_to_Gloss.md), [Inflection Features](../../Field_Descriptions/Lists/Variant_Types_flds/Inflection_Features.md), and [Slots](../../Field_Descriptions/Lists/Variant_Types_flds/Slots.md) fields to the **Variant Type** pane (**Variant Types** [list](../../Field_Descriptions/Lists/Variant_Types_flds/variant_types_flds_overview.md)) for the converted variant types.

- **Convert irregularly inflected form variants to variants**

This utility allows you to select one or more *irregularly* inflected form variant types and convert them to be 'regular' variants types.

> [!IMPORTANT]
>
> - You *cannot* use `Undo` to reverse the changes made by these [utilities](Language_Project_Utilities_overview.md).\
>   **See:** [FieldWorks Project Utilities overview](Language_Project_Utilities_overview.md).
>
> Do the following:
>
> 1.  Click the utility you will run, and then carefully read all the information and cautions in the **Description** pane.
>
> 2.  Select (![](../../../assets/images/CheckedBox.PNG)) the utility you will run, and then click **Run Check Utilities Now**.
>
> The **Choose Variant Type** dialog box opens.
>
> 3.  Select (![](../../../assets/images/CheckedBox.PNG)) the variant types that you want to convert. Click **OK** to close the dialog box and start the utility.
>
> 4.  Click **Close** to close the **FieldWorks Project Utility** dialog box.
>
> 5.  If [Append to Gloss](../../Field_Descriptions/Lists/Variant_Types_flds/Append_to_Gloss.md), [Inflection Features](../../Field_Descriptions/Lists/Variant_Types_flds/Inflection_Features.md), and [Slots](../../Field_Descriptions/Lists/Variant_Types_flds/Slots.md) fields were added for the converted variant types, type or select data in them.

> [!TIP]
>
> - If you are collaborating with others using [Send/Receive](../../../Basic_Tasks/Collaborating_with_Others/Send_Receive_considerations.md), you need to coordinate the use of this utility. You may want to [get more help](../../../Overview/Technical_support.md) before you use this utility.
>
> - If you are not collaborating, and do not want to keep the results of the conversion (e.g., you converted too many variant types), [restore](../File/Backup_and_Restore/Restore_a_project.md) the project. Then, do the above steps again.
>
> - On the [Help](../Help/Help_overview.md) menu, point to **Resources**, and then click **Introduction to Parsing** for additional information, such as how the parsers handle irregularly inflected forms.

## Related topics
[About Variant Types](../../../Using_Tools/Lists_tools/About_Variants.md)

[Tools overview](Tools_overview.md)
