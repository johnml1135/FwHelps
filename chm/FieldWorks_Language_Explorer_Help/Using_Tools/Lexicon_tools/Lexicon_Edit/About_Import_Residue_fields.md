---
title: "About Import Residue fields"
source_title: "About Import Residue fields"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Lexicon Edit"
  - "About Import Residue fields"
source: "Using_Tools/Lexicon_tools/Lexicon_Edit/About_Import_Residue_fields.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Lexicon_Edit/About_Import_Residue_fields.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "About:Import Residue fields"
  - "Import:About Import Residue fields"
  - "Residue"
  - "import"
related:
  - "Lexicon Edit overview -> lexicon_edit_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:6341b146d58eea41"
---

# About Import Residue fields

*Using Tools › Lexicon tools › Lexicon Edit*

The **Lexicon Edit** tool has **Import Residue** fields. There is one at the *entry* level, *subentry* level, and *sense* level.

These are associated with data mapping, which you do when you [import standard format lexical data](../../../Beginning_Tasks/Importing_Data/Import_Standard_Format_lexical_data.md).

- If data associated with a particular standard format marker is *not* mapped to a field, that data is put in the appropriate **Import Residue** field during import.

- You may deliberately choose to map ([Modify Mapping](../../../Beginning_Tasks/Importing_Data/modify_mapping_dialog_box.md)) some data to an **Import Residue** field.

After importing, if there is a significant amount of data in **Import Residue** fields, restore the language project from a backup file, modify mappings, and then import the data [again](../../../Beginning_Tasks/Importing_Data/step_1_of_8_overview_and_backup.md). This is an *iterative approach* to importing.

If there is a small amount of data in these fields, manually move it to an applicable field in **Lexicon Edit**, using normal [cut and paste](../../../User_Interface/Menus/Edit/Cut_copy_and_paste.md) or [Bulk Edit](../Bulk_Edit_Entries/bulk_edit_overview.md) (bulk copy and then bulk delete).

## Related topics
[Lexicon Edit overview](lexicon_edit_overview.md)
