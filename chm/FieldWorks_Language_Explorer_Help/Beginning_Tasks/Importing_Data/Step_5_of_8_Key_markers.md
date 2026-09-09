---
title: "Step 5 of 8: Key markers"
source_title: "Step 5 of 8: Key markers"
breadcrumb:
  - "Beginning Tasks"
  - "Importing Data"
  - "Step 5 of 8: Key markers"
source: "Beginning_Tasks/Importing_Data/Step_5_of_8_Key_markers.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Beginning_Tasks/Importing_Data/Step_5_of_8_Key_markers.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Key markers"
  - "Import:Standard Format lexical data"
  - "Steps"
  - "importing data"
related:
  - "Import Standard Format Lexical data -> Import_Standard_Format_lexical_data.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:f79c7176f363df39"
---

# Step 5 of 8: Key markers

*Beginning Tasks › Importing Data*

In this step, you specify which unique standard format markers can *begin* a group of related fields. That is, you specify which marker(s) indicate a second sense, second pronunciation, second example, and so on, as a checked marker can only occur once in a given group. Incorrect selections in this step can cause a large number of errors in the [readiness check](Step_7_of_8_Readiness.md).

Do the following:

1.  For each group (**Entry**, **Pronunciation**, *Sense*, **Example**, and so on) in the **Key markers** pane, select one or more markers that can begin a group of related fields.

- Each group needs at least one checked marker. Otherwise, the group label has a colored background and the **Next** button is disabled.

2.  Click the **Next**.

[Step 6 of 8: Character Mapping](Step_6_of_8_Character_mapping.md) appears.

> [!IMPORTANT]
>
> - For a discussion about SFM data import, point to **Resources** on the [Help](../../User_Interface/Menus/Help/Help_overview.md) menu, and then click **Technical Notes on SFM Database Import**.

### Examples

- Example 1

  **\lx abako**

  **\sn 1**

  **\ps verb**

  **\ps noun**

  Assuming **\sn** and **\ps** start a sense, this example would result in two senses. The first would have **\sn \ps**. The second **\ps** would start a second sense because the first sense already contains a **\ps** field.

- Example 2

  **\lx bank**

  **\ge tip airplane**

  **\ps verb**

  **\ps noun**

  **\ge financial institution**

  **\ge side of river**

  Assuming the default setting of **\ps** starting a sense, FieldWorks knows that **\ge** and **\ps** are both parts of a sense, so it will make its best attempt at loading the data. The result would be two senses with “tip airplane” and “verb” in the first sense and ”noun” and ”financial institution; side of river” in the second sense. By selecting **\ps** and **\ge** a begin markers for a sense, this example would result in three senses. The first would have “tip airplane” and “verb”. “noun” would start a new sense since the first sense already has a **\ps**. “financial institution” would go in the second sense since that sense is still missing a **\ge**. “side of river” would start a third sense since the second sense already has a **\ge** field.

> [!TIP]
>
> - To save time, you may want to have the data open in its original program (for example *The Linguist’s Shoebox*), or in a viewer, so that you can examine the data and determine the key markers.
>
> - You can click **Save** to save any changes you have made in any of the wizard's steps.

## Related topics
[Import Standard Format Lexical data](Import_Standard_Format_lexical_data.md)
