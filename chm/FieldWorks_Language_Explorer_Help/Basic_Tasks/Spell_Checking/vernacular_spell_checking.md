---
title: "Spell Checking vernacular words"
source_title: "Spell Checking vernacular words"
breadcrumb:
  - "Basic Tasks"
  - "Spell Checking"
  - "Spell Checking Vernacular Words"
source: "Basic_Tasks/Spell_Checking/vernacular_spell_checking.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Basic_Tasks/Spell_Checking/vernacular_spell_checking.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Vernacular"
  - "Vernacular:Spell checking vernacular words"
  - "Spell Checking:Spell Checking Vernacular Words"
related:
  - "Basic Tasks overview -> ../Basic_Tasks_overview.md"
  - "Change spelling overview -> ../../Using_Tools/Texts_&_Words_tools/Word_Analyses/Change_Spelling/change_spelling_overview.md"
  - "Spell Checking overview -> Spell_checking_overview.md"
  - "Spelling Status field -> ../../User_Interface/Field_Descriptions/Texts_&_Words/spelling_status_field.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:c0891eeb427f093c"
---

# Spell Checking vernacular words

*Basic Tasks › Spell Checking*

This topic is for the *default* vernacular writing system. At the beginning of a new language project, you may want to wait until a reasonable number of words are known to be correctly spelled or you may see too many flagged words.

1.  On the [Tools](../../User_Interface/Menus/Tools/Tools_overview.md) menu, point to **Spelling**, and then click **Show Vernacular Spelling Errors** to select (![](../../assets/images/CheckMark%20in%20RightClick%20Menu.png)) it.

    - The *first* *time* you do this, FieldWorks [creates](Create_multiple_vern_spell_dicts.md) empty spelling dictionary [files](Vernacular_spelling_dictionary_files.md) for the *default* vernacular writing system. Each word that uses this writing system, but is not in this spelling dictionary, is [flagged](Spell_checking_overview.md).

    - Clear (![](../../assets/images/User_Interface/Menus/Tools/UnCheckMarkedSpellingCmd.PNG)) it to *hide* flags for the default vernacular writing system.

    - Select (![](../../assets/images/User_Interface/Menus/Tools/CheckMarkedSpellingCmd.PNG)) it to *show* flags under each word that uses this writing system but is not in this spelling dictionary.

2.  *Add* words to the default vernacular spelling dictionary in any of these ways:

    - Right-click a flagged vernacular word, and then select **Add to Spelling Dictionary**.

    - Correct a spelling, such as with the [Change Spelling](../../Using_Tools/Texts_&_Words_tools/Word_Analyses/Change_Spelling/change_spelling_overview.md) dialog box.

    - [Specify](../../Using_Tools/Texts_&_Words_tools/Word_Analyses/Specify_spelling_status.md) **Correct** in the **Spelling Status** field for the current word.

    - [Bulk change Spelling Status](../../Using_Tools/Texts_&_Words_tools/Bulk_Edit_Wordforms/bulk_change_spelling_status.md) in **Bulk Edit Wordforms** to set the spelling status to **Correct**.

3.  *Remove* words from a default vernacular spelling dictionary in any of these ways:

    - [Specify](../../Using_Tools/Texts_&_Words_tools/Word_Analyses/Specify_spelling_status.md) **Incorrect** (or **Undecided**) in the **Spelling Status** field for each word you want to remove.

    - [Bulk change Spelling Status](../../Using_Tools/Texts_&_Words_tools/Bulk_Edit_Wordforms/bulk_change_spelling_status.md) in **Bulk Edit Wordforms** to set the spelling status to **Incorrect** for words you want to remove.

    - Edit the `<name>.dic` [file](dictionary_files.md) with a text editor, such as [ZEdit](../ZEdit.md)*.*

> [!NOTE]
>
> - If you have [multiple vernacular writing systems](Create_multiple_vern_spell_dicts.md), those that are *not* the top (default) vernacular writing system are handled like analysis writing systems.
>
> - Any words in [Word Analyses](../../Using_Tools/Texts_&_Words_tools/Word_Analyses/Word_Analyses_overview.md) that have **Spelling Status** set to **Correct**, will be written to a vernacular .dic file in the hunspell directory whenever FLEx is started. These words will be used for spelling checks in interlinear baselines, and will show in vernacular columns when you choose **Spelling Errors** as the [filter](../Filtering_data/filter_Texts_Words.md).
>
> If your vernacular writing system matches a standard spelling dictionary [obtained](Obtaining_spelling_dictionary_files.md) <a href="Obtaining_spelling_dictionary_files.md" target="_blank" title="https://software.sil.org/fieldworks/download/spelling-dictionaries/">elsewhere</a>, FLEx will use that list instead of writing over it.

## Related topics
[Basic Tasks overview](../Basic_Tasks_overview.md)

[Change spelling overview](../../Using_Tools/Texts_&_Words_tools/Word_Analyses/Change_Spelling/change_spelling_overview.md)

[Spell Checking overview](Spell_checking_overview.md)

[Spelling Status field](../../User_Interface/Field_Descriptions/Texts_&_Words/spelling_status_field.md)
