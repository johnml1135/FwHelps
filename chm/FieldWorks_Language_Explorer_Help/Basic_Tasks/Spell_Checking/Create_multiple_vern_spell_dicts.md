---
title: "Create multiple vernacular spelling dictionaries"
source_title: "Create multiple vernacular spelling dictionaries"
breadcrumb:
  - "Basic Tasks"
  - "Spell Checking"
  - "Create multiple vernacular spelling dictionaries"
source: "Basic_Tasks/Spell_Checking/Create_multiple_vern_spell_dicts.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Basic_Tasks/Spell_Checking/Create_multiple_vern_spell_dicts.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Vernacular"
  - "Vernacular:Create multiple vernacular spelling dictionaries"
related:
  - "Basic Tasks overview -> ../Basic_Tasks_overview.md"
  - "Baseline text writing systems -> ../../Using_Tools/Texts_&_Words_tools/Interlinear_Texts/baseline_text_writing_systems.md"
  - "Change spelling overview -> ../../Using_Tools/Texts_&_Words_tools/Word_Analyses/Change_Spelling/change_spelling_overview.md"
  - "Copy spelling dictionary files -> Copy_spelling_dictionary_files.md"
  - "Spell Checking overview -> Spell_checking_overview.md"
  - "Spelling Status field -> ../../User_Interface/Field_Descriptions/Texts_&_Words/spelling_status_field.md"
  - "Writing System Properties, General tab -> ../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_General_tab.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:d4b66d040537ba1e"
---

# Create multiple vernacular spelling dictionaries

*Basic Tasks › Spell Checking*

The first time you select **Show Vernacular Spelling Errors** on the [Tools](../../User_Interface/Menus/Tools/Tools_overview.md) menu, FieldWorks creates a vernacular spelling dictionary for the *default* vernacular writing system. If you have multiple vernacular writing systems and you want to enable spell checking for each of them, you can do either of the two options below. It is recommended that you [back up the language project](../../User_Interface/Menus/File/Backup_and_Restore/Back_up_this_Project.md) before you do either option.

## Temporarily swap vernacular writing systems

1.  In the **FieldWorks Project Properties** dialog box **Writing Systems** tab, change the order of the vernacular writing systems so that a vernacular writing system without spelling dictionaries is the *default* (top-most) vernacular writing system. Click **OK** to close the dialog box.

2.  On the **Tools** menu, point to **Spelling** and then click **Show Vernacular Spelling Errors**.

Another set of [dictionary files](dictionary_files.md) is created in the **hunspell** folder for the current default vernacular writing system.

This new spelling dictionary is automatically selected in the **Spelling dictionary** box of the **Writing System Properties** dialog box **General** tab.

3.  Return to the **Writing Systems** tab and change to order of the vernacular writing systems again so they appear in the desired order.

## Copy files

1.  In your computer's Windows<sup>®</sup> explorer, manually duplicate (with copy and paste) the existing vernacular spelling dictionary [files](dictionary_files.md) and rename each duplicate file with an appropriate name.

2.  In the **Spelling dictionary** box of the **Writing System Properties** dialog box **General** tab, [select](../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_General_tab.md) a vernacular spelling dictionary for each vernacular writing system that does not have one

## Related topics
[Basic Tasks overview](../Basic_Tasks_overview.md)

[Baseline text writing systems](../../Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/baseline_text_writing_systems.md)

[Change spelling overview](../../Using_Tools/Texts_&_Words_tools/Word_Analyses/Change_Spelling/change_spelling_overview.md)

[Copy spelling dictionary files](Copy_spelling_dictionary_files.md)

[Spell Checking overview](Spell_checking_overview.md)

[Spelling Status field](../../User_Interface/Field_Descriptions/Texts_&_Words/spelling_status_field.md)

[Writing System Properties, General tab](../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_General_tab.md)
