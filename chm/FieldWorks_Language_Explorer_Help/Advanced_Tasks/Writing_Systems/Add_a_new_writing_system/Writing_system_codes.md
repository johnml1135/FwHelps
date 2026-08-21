---
title: "Writing system codes"
source_title: "Writing system codes"
breadcrumb:
  - "Advanced Tasks"
  - "Writing Systems"
  - "Add a new writing system"
  - "Writing system codes"
source: "Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/Writing_system_codes.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/Writing_system_codes.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Delete:Internal Code"
  - "Writing System:Codes"
  - "Ethnologue code"
  - "change"
  - "change:Writing system codes"
  - "Codes"
  - "writing system"
related:
  - "Add a new writing system overview -> Add_a_new_writing_system_overview.md"
  - "Private-Use codes -> Privatel_Use_codes.md"
  - "Select Language overview -> Select_Language_overview.md"
  - "Using the Writing System Properties dialog box -> ../Modifying_a_Writing_System/Using_the_Writing_System_Properties_dialog_box.md"
  - "Writing Systems overview -> ../Writing_Systems_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:c9a56fe9a86f25c7"
---

# Writing system codes

*Advanced Tasks › Writing Systems › Add a new writing system*

In the **Writing Systems Properties** dialog box, the **Writing Systems** pane lists writing systems. If you click one to highlight it, the *top-right* pane contains information about the *language* that the writing system is for.

In the **General** [tab](../Modifying_a_Writing_System/Writing_System_Properties_General_tab.md), **Code** means the *writing system code*. It is based on a [language code](Language_codes.md) and identifies a particular writing system for a language. The writing system [writing system file](Writing_System_files.md) name is based on the writing system code.

Here are some examples:

|           |      |          |                       |                            |
|-----------|------|----------|-----------------------|----------------------------|
| Language  | Code | Variant  | Code                  | File name                  |
| French    | fra  |          | fr                    | `fr.ldml`                  |
| Sena      | seh  |          | seh                   | `seh.ldml`                 |
| Sena      | seh  | Audio    | seh-Zxxx-x-audio      | seh-Zxxx-x-audio.ldml      |
| Sena      | seh  | IPA      | seh-fonipa            | seh-fonipa.ldml            |
| Sena      | seh  | Phonemic | seh-fonipa-x-emic     | `seh-fonipa-x-emic.ldml`   |
| Lela-Teli |      |          | qaa-x-lel             | `qaa-x-lel.ldml`           |
| Lela-Teli |      | Phonetic | qaa-fonipa-x-lel-etic | qaa-fonipa-x-lel-etic.ldml |

> [!IMPORTANT]
>
> - Additional script/region/variant codes should only be used if *essential* for distinguishing between writing systems in that project.
>
> Try to keep the code as short as possible. For example, try to use en instead of en-Latn-US.
>
> - FieldWorks version 9.0.x do not allow for en and en-Latn as two different writing systems since the default script for en is Latin. Each language has a default script. The **Script** box shows the default script, which is not included in the Code.
>
> - If you [can't find your language](Select_Language_dialog_box.md) the code starts with **qaa**. The Lela-Teli examples show this.
>
> In this case, the **Ethnologue entry for** link does not refer to a particular entry.

## Related topics
[Add a new writing system overview](Add_a_new_writing_system_overview.md)

[Private-Use codes](Privatel_Use_codes.md)

[Select Language overview](Select_Language_overview.md)

[Using the Writing System Properties dialog box](../Modifying_a_Writing_System/Using_the_Writing_System_Properties_dialog_box.md)

[Writing Systems overview](../Writing_Systems_overview.md)

## Related links
<a href="https://www.rfc-editor.org/rfc/bcp/bcp47.txt" target="_blank" title="https://www.rfc-editor.org/rfc/bcp/bcp47.txt">https://www.rfc-editor.org/rfc/bcp/bcp47.txt</a>

<a href="https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry" target="_blank" title="https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry">https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry</a>
