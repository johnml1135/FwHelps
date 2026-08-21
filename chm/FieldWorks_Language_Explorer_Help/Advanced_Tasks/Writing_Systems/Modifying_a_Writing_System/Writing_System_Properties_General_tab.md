---
title: "Writing System Properties, General tab"
source_title: "Writing System Properties, General tab"
breadcrumb:
  - "Advanced Tasks"
  - "Writing Systems"
  - "Modifying a Writing System"
  - "Writing System Properties, General tab"
source: "Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_General_tab.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_General_tab.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Name tab"
  - "Choose (See also: Select or Specify):Spelling dictionary"
  - "Select (See also: Specify or Choose):Spelling dictionary"
  - "select a"
  - "Script name"
  - "writing system"
  - "Direction"
  - "specify for writing system"
  - "IPA:General tab"
  - "Writing System Properties"
  - "Right-to-Left direction"
  - "Region name"
  - "Variant name"
  - "Writing System Properties dialog box:General tab"
  - "Direction:Writing System Properties"
  - "General tab"
  - "General:General tab"
related:
  - "About Dialect Labels -> ../../../Using_Tools/Lists_tools/About_Dialect_Labels.md"
  - "Audio files overview -> ../../../Basic_Tasks/Audio_files/Audio_files_overview.md"
  - "Modifying a writing system overview -> Modifying_a_writing_system_overview.md"
  - "Writing System files -> ../Add_a_new_writing_system/Writing_System_files.md"
  - "Writing Systems overview -> ../Writing_Systems_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:f098e49eda322844"
---

# Writing System Properties, General tab

*Advanced Tasks › Writing Systems › Modifying a Writing System*

[Using the Writing System Properties dialog box](Using_the_Writing_System_Properties_dialog_box.md) describes the **Writing Systems** pane and more. See Also: [Language codes](../Add_a_new_writing_system/Language_codes.md) and [Writing system codes](../Add_a_new_writing_system/Writing_system_codes.md).

Do these steps in the **General** tab:

1.  [Open](Open_Writing_System_Properties_dlgbox.md) the **Writing System Properties** dialog box.

2.  In the **Writing Systems** pane, click the [writing system](../Add_a_new_writing_system/About_Writing_Systems.md) you will change.

3.  Do *any* of these steps:

**Code** — Observe the writing system [code](../Add_a_new_writing_system/Writing_system_codes.md).

**Spelling dictionary** — Select the [spelling dictionary](../../../Basic_Tasks/Spell_Checking/Spell_checking_overview.md).

**Right-to-left** — Select (![](../../../assets/images/CheckedBox.PNG)) for a [right-to-left](../../../User_Interface/Menus/Format/Styles/Direction.md) writing system.

**Abbreviation** — Edit the abbreviation. It appears in the UI ([example](../../../User_Interface/Field_Descriptions/Field_Types/Single_line_text_field_example_graphic.md)).

**Special** — based on how the writing system was [added](../Add_a_new_writing_system/Add_a_new_writing_system.md), you see:

- **IPA Transcription** from **Add IPA for** \<language\>.

Click **Purpose**, and then click **Etic**, **Emic** or **Default**.

- **Voice** from **Audio for** \<language\>. Do not change it.

- **Script/Region/Variant** from **Add variation of** \<language\>.

**Script** — Select a script from the list *if* the writing system uses a script that is different from the language.

**Region** — Select a region from the list if the writing systems is *dialect* that if regional.

**Variant** — Type the name of the variant in this box.

5.  If necessary, select (![](../../../assets/images/CheckedBox.PNG)) **Advanced** to display and [use](Use_the_advanced_writing_system_controls.md) the [Advanced](About_the_Advanced_ws_controls.md) controls.

> [!IMPORTANT]
>
> - **Purpose** lets you distinguish multiple IPA Transcription writing systems. If you only use one IPA Transcription writing system, it is best to leave **Purpose** set to **Unspecified**.
>
> However, you could have *both* **Etic** (phonetic) and **Emic** (phonemic) writing systems for a language. Their [codes](../Add_a_new_writing_system/Writing_system_codes.md) would be different.
>
> - Each language has a default script and region. A script subtag will not be included in the writing system code unless it is used to specify a non-default script. Region subtags should not be used unless a single project needs to distinguish between regions. Likewise, variants should only be used if needed to specify differences between writing systems in a given project.
>
> - If you are [collaborating](../../../Basic_Tasks/Collaborating_with_Others/Collaborating_with_Others_overview.md) with others using [Send/Receive](../../../Basic_Tasks/Collaborating_with_Others/Send_Receive_overview.md), do not change writing systems without [discussing it](../../../Basic_Tasks/Collaborating_with_Others/Send_Receive_considerations.md) first.
>
> - [Collection of Locale Data](Collection_of_Locale_data.md) describes the **Share writing system data with SLDR** check box.

## Related topics
[About Dialect Labels](../../../Using_Tools/Lists_tools/About_Dialect_Labels.md)

[Audio files overview](../../../Basic_Tasks/Audio_files/Audio_files_overview.md)

<a href="Modifying_a_writing_system_overview.md" style="font-weight: normal;">Modifying a writing system overview</a>

[Writing System files](../Add_a_new_writing_system/Writing_System_files.md)

[Writing Systems overview](../Writing_Systems_overview.md)

## Related links
<a href="https://software.sil.org/fieldworks/support/technical-documents/" target="_blank" title="https://software.sil.org/fieldworks/support/technical-documents/">https://software.sil.org/fieldworks/support/technical-documents/</a>

<a href="https://www.unicode.org/reports/" target="_blank" title="https://www.unicode.org/reports/">https://www.unicode.org/reports/</a>

<a href="https://unicode-org.github.io/icu/" target="_blank" title="https://unicode-org.github.io/icu/">https://unicode-org.github.io/icu/</a>

<a href="https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry" target="_blank" title="https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry">https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry</a>
