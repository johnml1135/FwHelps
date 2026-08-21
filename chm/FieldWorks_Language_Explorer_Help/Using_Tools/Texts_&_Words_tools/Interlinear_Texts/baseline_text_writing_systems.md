---
title: "Baseline text writing systems"
source_title: "Baseline text writing systems"
breadcrumb:
  - "Using Tools"
  - "Texts & Words tools"
  - "Interlinear Texts"
  - "Baseline text writing systems"
source: "Using_Tools/Texts_&_Words_tools/Interlinear_Texts/baseline_text_writing_systems.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/baseline_text_writing_systems.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Writing System:Baseline text writing system"
  - "Baseline text writing systems"
  - "Texts & Words:Baseline text writing systems"
  - "Analyze Texts (parse):Baseline text writing systems"
related:
  - "Interlinear Texts 
 overview -> texts_edit_overview.md"
  - "Show 
 data overview -> ../../../Basic_Tasks/Show_data/Show_data_overview.md"
  - "Text 
 preparation before analyzing -> Text_preparation_before_analyzing.md"
  - "Word-forming 
 apostrophes and glottal stops -> ../../../User_Interface/Menus/Insert/wordforming_apostophes.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:35f6b415511fef28"
---

# Baseline text writing systems

*Using Tools › Texts & Words tools › Interlinear Texts*

When you [insert](Insert_new_Text.md) a new text, you should understand this behavior:

- If the project has only one vernacular [writing system](../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md), it is the default writing system for all your texts.

- If your vernacular language has more than one writing system, the **Select Writing System** dialog box appears. You must select one of them for the new text.

However, if you have texts that use more than just the top vernacular writing system, beware that there are special techniques to make it work properly. All [wordforms](../Word_Analyses/Word_Analyses_overview.md) and all lexeme forms should have all writing systems filled in. This will allow the baseline to find the same wordforms and lexical entries for either writing system.

<a href="http://downloads.sil.org/FieldWorks/Documentation/Flex_tips.pdf" target="_blank">http://downloads.sil.org/FieldWorks/Documentation/Flex_tips.pdf</a> has more information about interlinearizing in multiple scripts in Section 13.

> [!NOTE]
>
> - When a FLEx project is created, certain Unicode characters are treated by default as word-forming or as punctuation. In the **Texts & Words** area, the segmentation of a text into words will be done based on these characteristics: any string of consecutive word-forming characters will be grouped as a word, and any punctuation character will cause a break between words. If a character that is normally interpreted as punctuation happens to be used in the orthography as part of a word, FLEx will view as two separate words what the user perceives as a single word. The **Valid Characters** dialog box allows you to [specify](../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Valid_Characters_dialog_box/Valid_Char_overview.md) what is valid punctuation for the writing system.
>
> - You can select words in a **Baseline** tab, and then use the [Format toolbar](../../../User_Interface/Toolbars/Format_toolbar.md) or [Format menu](../../../User_Interface/Menus/Format/Format_overview.md) to change their writing system. You can change the writing system to any writing system of your vernacular language and analyze those words. But again, refer to Section 13 of the FLEx tips document (above) for guidance.
>
> If you choose any other writing system, such as an analysis writing system, it will be treated as punctuation.
>
> Avoid using text in other languages as much as possible.
>
> - You may begin a language project with, for example, a *phonetic* default (top) vernacular writing system and analyze (interlinearize) the phonetic forms of words. As the project matures, you can [reorder](../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Reorder_writing_systems.md) writing systems to make the *orthographic* writing system the default (top) vernacular.
>
> Complications are possible if you are not careful as mentioned above. For example, you may see duplicated or missing words in the [word list](../Word_list_overview.md) or duplicated or missing lexical headwords.
>
> If you see blank **Word** lines for a particular writing system, you can type the word in that line in [Bulk Edit Wordforms](../Bulk_Edit_Wordforms/Bulk_Edit_Wordforms_overview.md).
>
> Some users find it helpful [change](../../../User_Interface/Menus/Format/Styles/Styles_Font_tab.md) the Normal style so that each writing system uses a different color. Then it is easy to identify words that were typed or pasted into texts or lexical entries using the wrong writing system.

## Related topics
[Interlinear Texts overview](texts_edit_overview.md)

[Show data overview](../../../Basic_Tasks/Show_data/Show_data_overview.md)

[Text preparation before analyzing](Text_preparation_before_analyzing.md)

[Word-forming apostrophes and glottal stops](../../../User_Interface/Menus/Insert/wordforming_apostophes.md)
