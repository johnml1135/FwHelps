---
title: "Analysis spelling dictionary files"
source_title: "Analysis spelling dictionary files"
breadcrumb:
  - "Basic Tasks"
  - "Spell Checking"
  - "Analysis spelling dictionary files"
source: "Basic_Tasks/Spell_Checking/Analysis_spelling_dictionary_files.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Basic_Tasks/Spell_Checking/Analysis_spelling_dictionary_files.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "About:Spelling dictionary files"
  - "Spell Checking:Analysis spelling dictionary files"
related:
  - "About spelling dictionary files -> dictionary_files.md"
  - "Add to Spelling Dictionary (right-click menus) -> ../Show_data/Context_sens_menus.md"
  - "Bulk change spelling status -> ../../Using_Tools/Texts_&_Words_tools/Bulk_Edit_Wordforms/bulk_change_spelling_status.md"
  - "Folder Structure (Backup and Restore) -> ../../User_Interface/Menus/File/Backup_and_Restore/Folder_Structure.md"
  - "Spell Checking overview -> Spell_checking_overview.md"
  - "Spell Checking Vernacular Words -> vernacular_spell_checking.md"
  - "Spelling Status field -> ../../User_Interface/Field_Descriptions/Texts_&_Words/spelling_status_field.md"
  - "Using the Writing System Properties dialog box -> ../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Using_the_Writing_System_Properties_dialog_box.md"
  - "ZEdit -> ../ZEdit.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:c37894a64e0fbe07"
---

# Analysis spelling dictionary files

*Basic Tasks › Spell Checking*

[Hunspell](About_Hunspell.md) uses these [files](dictionary_files.md) for *analysis* writing systems:

### **\*.dic**

- This file stores words that are considered to be correctly spelled.

- You *cannot* add words to this file from FieldWorks (FLEx).

- In this file, the top line shows the number of words in the file. The second line is for file identification; *do not delete or edit it.*

### **\*.exc**

- *exc* means *exceptions*.

- This file stores words added with **Add to Spelling Dictionary**. These are correctly-spelled words that are *in addition to* those in the **\*.dic** file.

- The **\*.exc** file is created the first time you use **Add to Spelling Dictionary**.

- To remove words, edit this file in Notepad or ZEdit.

### **\*.aff**

- Some advanced users may be able to use this file which would permit the right-click menu to offer corrected words as valid spellings. To learn how, refer to Hunspell documentation at <a href="https://manpages.ubuntu.com/" target="_blank" title="https://manpages.ubuntu.com/">https://manpages.ubuntu.com/</a>.

### About these files

- **\*** is the file name, which tells you the particular language. Analysis writing systems are typically majority languages.

- OpenOffice/LibreOffice and other programs use hunspell. However, even if one of these programs is installed on your computer, you must [copy](Copy_spelling_dictionary_files.md) the **\*.dic** and **\*.aff** files into the **hunspell** folder so FLEx can access them.

- The **hunspell** folder location: C:\Users\\username\>\AppData\Roaming\hunspell

<!-- -->

- Select a spelling dictionary with the **Spelling dictionary** control (**General** tab of the **Writing System Properties** dialog box).

- Only the **\*.exc** file is included in the [backup file](../../User_Interface/Menus/File/Backup_and_Restore/Backup_files.md). The **\*.dic** files are typically large and readily available. You can manually copy dictionary files, and then store or share them as desired.

> [!IMPORTANT]
>
> - *Before* you click **Add to Spelling Dictionary**, look at the [Format](../../User_Interface/Toolbars/Format_toolbar.md) toolbar and make sure the *correct writing system* was used for the [flagged](Spell_checking_overview.md) word.
>
> The writing system determines which spelling dictionary receives the spelling. (If [styles](../../User_Interface/Menus/Format/Styles/Styles_overview.md) are similar, the writing system may not be obvious.)
>
> - **See Also:** <a href="https://software.sil.org/fieldworks/download/spelling-dictionaries/" target="_blank" title="https://software.sil.org/fieldworks/download/spelling-dictionaries/">https://software.sil.org/fieldworks/download/spelling-dictionaries/</a>

## Related topics
[About spelling dictionary files](dictionary_files.md)

[Add to Spelling Dictionary (right-click menus)](../Show_data/Context_sens_menus.md)

[Bulk change spelling status](../../Using_Tools/Texts_%26_Words_tools/Bulk_Edit_Wordforms/bulk_change_spelling_status.md)

[Folder Structure (Backup and Restore)](../../User_Interface/Menus/File/Backup_and_Restore/Folder_Structure.md)

[Spell Checking overview](Spell_checking_overview.md)

[Spell Checking Vernacular Words](vernacular_spell_checking.md)

[Spelling Status field](../../User_Interface/Field_Descriptions/Texts_%26_Words/spelling_status_field.md)

[Using the Writing System Properties dialog box](../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Using_the_Writing_System_Properties_dialog_box.md)

[ZEdit](../ZEdit.md)
