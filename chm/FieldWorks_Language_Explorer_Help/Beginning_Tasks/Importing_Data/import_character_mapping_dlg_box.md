---
title: "Import Character Mapping dialog box (import character mapping dlg box)"
source_title: "Import Character Mapping dialog box"
breadcrumb:
  - "Beginning Tasks"
  - "Importing Data"
  - "Import Character Mapping dialog box"
source: "Beginning_Tasks/Importing_Data/import_character_mapping_dlg_box.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Beginning_Tasks/Importing_Data/import_character_mapping_dlg_box.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Mapping"
  - "Mapping:Import Character Mapping"
  - "Markers"
  - "Character mapping"
  - "import"
related:
  - "Import Standard Format Lexical data -> Import_Standard_Format_lexical_data.md"
  - "Sample screen shot -> Import_Character_Mapping_Sample.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:809426cb23e84916"
---

# Import Character Mapping dialog box (import character mapping dlg box)

*Beginning Tasks › Importing Data*

The **Import Character Mapping** dialog box appears if you click **Add** or **Modify** in the **Import Standard Format lexical data** wizard [Step 6 of 8 Character Mapping](Step_6_of_8_Character_mapping.md). In this dialog box, you specify the beginning markers and end markers (if any), and how FieldWorks should interpret them.

1.  In the **Beginning marker** box, enter or edit the *beginning* marker used in the import data.

2.  In the **Ending marker** box, enter or edit the *ending* marker used in the import data, if any.

3.  If the beginning marker does *not* have a corresponding ending markers in your import data, leave the **Ending marker** box empty. Then in the **End At** row, select **End of Word** or **End of Field** to indicate the end of the marked text.

4.  In the **Lang Descriptor** box, do one of the following:

    - Leave or set the selection to **\<No Change\>**.

    - Select an *existing* language descriptor (specified in [Step 3 of 8](Step_3_of_8_Language_mapping.md), **Language mapping**).

    - For markers with which you will specify a character style, such as **\|b \|r**, this limits the character style change to *only* the selected language descriptor.

      For others, such as **\|fr{ }**, this specifies which language descriptor is applies to the marked text.

    - Click **Add** to [add a language mapping](Step_3_of_8_Language_mapping.md).

5.  In the **Character style** box, do one of the following:

    - Leave or set the selection to **\<****No Change****\>**.

    - Use the down arrow to select an *existing* character style.

    - Click **Styles** to open the **Styles** dialog box so you can add or modify [styles](../../User_Interface/Menus/Format/Styles/Styles_overview.md).

6.  Click **OK**.

    The **OK** button is *not* available if the markers and settings are identical to another mapping in the **Character mapping** list. In this case, you need to change something or click **Cancel** to close the dialog box.

> [!IMPORTANT]
>
> - To '*ignore'* a marker, specifically to *remove* the beginning and ending marker from the imported data without any changes, set *both* **Lang Descriptor** and **Character Style** to **\<No Change\>**.
>
> - Some fields *do not allow* embedded writing systems or embedded styles, such as [Gloss](../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Gloss_field_Sense.md) and [Grammatical Info](../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Grammatical_Info_field.md) fields. For these fields, the markers will remain in the field after they are imported, unless 'ignored' as stated above. This allows you to filter for them and do whatever you want with these markers. However, there are three exceptions where the markers will *always* be deleted (**Lexeme Form**, **Citation Form**, and **Allomorph**).
>
> - Any markers that are not listed in the [Character Mapping](Step_6_of_8_Character_mapping.md) list will be treated as normal word-forming characters and will appear in the imported fields.

### Examples of commonly used markers:

- **fv:** to indicate a single word in the vernacular writing system, as in "Use **fv:**Usted to show respect.", if a vernacular writing system is selected in the **Lang Descriptor** box ([Sample screen shot](Import_Character_Mapping_Sample.md)).

  - If you use a marker that does *not* have a corresponding ending marker to indicate, for example, that a multi-word phrase uses a different writing system than the text preceding and following that phrase, you need to mark *each* of the words in the phrase, as in "**fv:**word1 **fv:**word2 **fv:**word3". However, if the phrase stands alone, you may be able to select **End of Field**.

    This differs from **\|fr{ }**, as in "**\|fr{**word1 word2 word3**}**", which has an ending marker.

- **\|fr{ }** to indicate a French writing system, as in "This is **\|fr{**Français**}**.", if French is selected in the **Lang Descriptor** box.

- **\|b \|r** to indicate bold, as in "This is **\|b**bold**\|r**.", if a bold character style is selected in the **Character style** box.

## Related topics
[Import Standard Format Lexical data](Import_Standard_Format_lexical_data.md)

[Sample screen shot](Import_Character_Mapping_Sample.md)
