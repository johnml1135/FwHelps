---
title: "About writing systems"
source_title: "About writing systems"
breadcrumb:
  - "Advanced Tasks"
  - "Writing Systems"
  - "Add a new writing system"
  - "About Writing Systems"
source: "Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Writing System"
  - "Writing System:Default writing system"
  - "Writing System:About Writing Systems"
  - "Writing System:Analysis writing system"
  - "Project:Writing system"
  - "Hide"
  - "Project Properties overview:Project Properties_ Writing Systems tab"
  - "About:Writing Systems"
  - "Default:Default analysis writing system"
  - "Default:Default vernacular writing system"
  - "Default:Project Properties"
  - "Writing Systems tab"
  - "Analysis"
  - "Vernacular"
  - "Vernacular:Vernacular words"
  - "Vernacular:Vernacular writing system"
  - "Best Analysis writing system"
  - "Analysis writing system"
  - "Analysis writing system:About Writing Systems"
  - "Set up writing systems"
  - "Setup Writing Systems"
  - "Modify a writing system:About Writing Systems"
  - "IPA:About Writing Systems"
  - "WritingSystemStore"
  - "WritingSystemRepository"
  - "FieldWorks Project Properties dialog box:FW Project Properties - Writing Systems tab"
  - "Vernacular writing system"
  - "Vernacular writing system:About Writing Systems"
related:
  - "Add 
 a new writing system overview -> Add_a_new_writing_system_overview.md"
  - "Format 
 menu overview -> ../../../User_Interface/Menus/Format/Format_overview.md"
  - "Showing 
 writing systems overview -> ../../../Basic_Tasks/Showing_Writing_Systems/Show_WSs_overview.md"
  - "Using 
 the Writing System Properties dialog box -> ../Modifying_a_Writing_System/Using_the_Writing_System_Properties_dialog_box.md"
  - "Writing Systems 
 overview -> ../Writing_Systems_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:fe47da3f886c29ca"
---

# About writing systems

*Advanced Tasks › Writing Systems › Add a new writing system*

A language can be written in more than one script, such as *orthographically* and *phonetically* (IPA). Accordingly, *writing system* refers to the combination of a specific *language* and a *script*.

The most fundamental piece of information in a writing system is the language it is for. When you [create](../../../User_Interface/Menus/File/Create_a_new_Fieldworks_project.md) a project and choose a writing system, you first [look up](Select_Language_overview.md) the [language code](Language_codes.md). Later, you [use](../Modifying_a_Writing_System/Using_the_Writing_System_Properties_dialog_box.md) the **Writing System Properties** dialog box to define it, set the font, keyboard and sort and so on.

Each *writing system* has a [code](Writing_system_codes.md) and a [file](Writing_System_files.md).

There are two versions of **Writing System Properties** dialog box: one for the *vernacular* language and one for *analysis* languages.

- **Vernacular** — it is the language that you will study.

Lexical headwords, text content, example sentences and similar use it.

A project should have *one* vernacular language with multiple writing systems.

**See Also:** [About vernacular writing systems](About_vernacular_writing_systems.md).

- **Analysis** — it is typically a language-of-wider-communication.

Text analysis, notes, descriptions, and similar use it.

**Best analysis** writing system is a program feature. It attempts to *first* use content from the associated field that was entered in the *default* (top) writing system. If none is found, then content that was entered in the *next* analysis writing system is used.

### Do you *need* different writing systems for the same language?

Yes, typically. For example, you could represent your data orthographically and phonetically, such as for pronunciations. You could also use an audio writing system so people can hear the headwords pronounced.

In some cases, such as a mono-lingual dictionary, the same language can be used for vernacular and analysis writing systems.

###  Notes

- You can [configure](../../../Basic_Tasks/Showing_Writing_Systems/configure_field_WSs.md) which writing systems are displayed in many fields.

When necessary, FLEx automatically changes the writing system and keyboard when you move the insertion point.

**See Also:** [Select a writing system](../../../User_Interface/Menus/Format/select_a_writing_system.md).

- For writing systems provided by ICU (International Components for Unicode), you cannot change the "similar writing system" selected for [collation](../Modifying_a_Writing_System/Collation_in_FieldWorks.md) or [modify](../Modifying_a_Writing_System/Writing_System_Properties_Sorting_tab.md) the collation rules.

- For more information, on the [Help](../../../User_Interface/Menus/Help/Help_overview.md) menu, point to **Resources**, and then click **Technical Notes on Writing Systems**.

## Related topics
[Add a new writing system overview](Add_a_new_writing_system_overview.md)

[Format menu overview](../../../User_Interface/Menus/Format/Format_overview.md)

[Showing writing systems overview](../../../Basic_Tasks/Showing_Writing_Systems/Show_WSs_overview.md)

[Using the Writing System Properties dialog box](../Modifying_a_Writing_System/Using_the_Writing_System_Properties_dialog_box.md)

[Writing Systems overview](../Writing_Systems_overview.md)
