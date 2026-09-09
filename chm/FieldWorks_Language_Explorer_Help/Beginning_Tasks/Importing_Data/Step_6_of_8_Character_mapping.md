---
title: "Step 6 of 8: Character mapping"
source_title: "Step 6 of 8: Character mapping"
breadcrumb:
  - "Beginning Tasks"
  - "Importing Data"
  - "Step 6 of 8: Character mapping"
source: "Beginning_Tasks/Importing_Data/Step_6_of_8_Character_mapping.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Beginning_Tasks/Importing_Data/Step_6_of_8_Character_mapping.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Mapping"
  - "Mapping:Step 6 of 8: Character mapping"
  - "Import:Standard Format lexical data"
  - "Steps"
  - "importing data"
  - "Character mapping"
  - "import"
related:
  - "Import Standard Format Lexical data -> Import_Standard_Format_lexical_data.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:4c35554fb1f19642"
---

# Step 6 of 8: Character mapping

*Beginning Tasks › Importing Data*

In this step, you indicate any markup you have used in your data to identify character styles, writing systems, or direct formatting. See **Examples** below.

1.  Do any of the following:

    - To *add* a markup to the list, click **Add**.

      The [Import Character Mapping](import_character_mapping_dlg_box.md) dialog box appears so you can specify the markers, descriptor and so on.

    - To *modify* a markup, click it in the **Character mapping** list, and then click **Modify**.

      The **Import Character Mapping** dialog box appears with content and settings you can change.

    - To *delete* a markup, click it in the **Character mapping** list, and then click **Delete**.

      The selected element is deleted.

2.  Click **Next**.

    [Step 7 of 8: Readiness](Step_7_of_8_Readiness.md) appears.

### Examples

- **fv:** to indicate a single word in the vernacular writing system, as in "Use **fv:**Usted to show respect.", if a vernacular writing system is selected in the **Lang Descriptor** box ([Sample screen shot](Import_Character_Mapping_Sample.md)).

  - If you use a marker that does *not* have a corresponding ending marker to indicate, for example, that a multi-word phrase uses a different writing system than the text preceding and following that phrase, you need to mark *each* of the words in the phrase, as in "**fv:**word1 **fv:**word2 **fv:**word3". However, if the phrase stands alone, you may be able to select **End of Field**.

    This differs from **\|fr{ }**, as in "**\|fr{**word1 word2 word3**}**", which has an ending marker.

- **\|fr{ }** to indicate a French writing system, as in "This is **\|fr{**Français**}**.", if French is selected in the **Lang Descriptor** box.

- **\|b \|r** to indicate bold, as in "This is **\|b**bold**\|r**.", if a bold character style is selected in the **Character style** box.

> [!TIP]
>
> - Any markups in the **Character mapping** list that have a different color, are set to be ignored in the [Import Character Mapping](import_character_mapping_dlg_box.md) dialog box.
>
> - You can click **Save** to save any changes you have made in any of the wizard's steps.

## Related topics
[Import Standard Format Lexical data](Import_Standard_Format_lexical_data.md)
