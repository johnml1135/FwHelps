---
title: "Import Character Mapping dialog box (Import Character Mapping)"
source_title: "Import Character Mapping dialog box"
breadcrumb:
  - "Beginning Tasks"
  - "Importing Data"
  - "Import Notebook Data"
  - "Import Character Mapping dialog box"
source: "Beginning_Tasks/Importing_Data/Import_Notebook_Data/Import_Character_Mapping.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Beginning_Tasks/Importing_Data/Import_Notebook_Data/Import_Character_Mapping.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Import:Standard Format anthropology data"
related:
  - "Step 6 of 7: Character Mapping -> Step_6_of_7_Character_mapping.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:ffa1105dbe61c286"
---

# Import Character Mapping dialog box (Import Character Mapping)

*Beginning Tasks › Importing Data › Import Notebook Data*

A pair of beginning and ending *inline markers* identify a text element within a field in a Standard Format file.

1.  In the **Beginning marker** box, type or edit the beginning marker used in the import data.

2.  In the **Ending marker** box, type or edit the ending marker used in the import data, if any.

    - Leave the **Ending marker** box empty if the beginning marker does *not* have a corresponding ending marker.

3.  Select one of the following to specify when a beginning marker should end in the case where ending markers are not used or inadvertently missing in the data:

    - **Stop at End of Word**

    - **Stop at End of Field**

4.  In the **Notebook Destination** area, do one of the following:

    - Select a writing system from the list. It the one you need is not listed, click **Add**, point to **Vernacular Writing System** or **Analysis Writing System**, and then click an existing writing system or **Define New** to [add](../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/Add_a_new_writing_system.md) a new writing system.

    - Select a character style, or click Styles (Not implemented).

    - Select **Ignore** if you want to ignore the *markers* but import the text.

5.  Click **OK**.

> [!NOTE]
>
> - Here is an example of a Standard Format field that contains a character mapping from beginning marker **\|fv{** and ending marker **}** to the Lela-Teli writing system:
>
>   **\desc** A description in English that contains **\|fv{Lela-Teli words}**.
>
> - When you export as Standard Format, inline markers identify text in any writing system other than the default *analysis* writing system. The beginning marker includes the [writing system code](../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/Writing_system_codes.md), for example:
>
>   **\desc** Default analysis writing system and **\|xlel{Lela-Teli writing system}**.

## Related topics
[Step 6 of 7: Character Mapping](Step_6_of_7_Character_mapping.md)
