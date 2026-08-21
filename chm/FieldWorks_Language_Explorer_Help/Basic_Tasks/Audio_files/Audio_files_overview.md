---
title: "Audio files overview"
source_title: "Audio files overview"
breadcrumb:
  - "Basic Tasks"
  - "Audio files"
  - "Audio files overview"
source: "Basic_Tasks/Audio_files/Audio_files_overview.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Basic_Tasks/Audio_files/Audio_files_overview.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Sound or movie file"
  - "Link (See also: Hyperlink):Audio files"
  - "link to existing"
  - "Audio files overview"
  - "Audio files overview:Audio files overview"
related:
  - "Basic Tasks overview -> ../Basic_Tasks_overview.md"
  - "Insert a sound or movie file -> ../../Using_Tools/Lexicon_tools/Lexicon_Edit/Insert_link_to_sound_or_movie.md"
  - "Specify concordance criteria -> ../../Using_Tools/Texts_&_Words_tools/Concordance/specify_concordance_criteria.md"
fw_help_version: "9.3"
type: "index"
content_hash: "sha256:961de03037bc53e5"
---

# Audio files overview

*Basic Tasks › Audio files*

You can [add](../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/Add_a_new_writing_system.md) an **Audio** [writing system](../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md). You use it to record and play audio files (\*.wav files only). In fields that show the **Audio** writing system, the *empty* symbol (![](../../assets/images/Basic_Tasks/Audio_files/Empty%20Audio%20field.png)) appears. For a field with an audio file, the *play* button appears gray (![](../../assets/images/Basic_Tasks/Audio_files/GrayPlay.png)). When you move the mouse pointer over one of them, they change to the *record* button (![](../../assets/images/Basic_Tasks/Audio_files/Record%20Button.png)) or *play* button (![](../../assets/images/Basic_Tasks/Audio_files/Play%20Button.png)), respectively. Because these are typically very short recordings, there is neither a *pause* or *stop* button.

## Reasons for the Audio variant

- If you will [import](../../Beginning_Tasks/Importing_Data/import_lift_lex.md) LIFT lexical data, such as from WeSay, you need to add matching writing systems. This includes an **Audio** variant for writing systems with audio files.

- If you want to record and play audio files in fields other than the **Media File** field, then add an **Audio** variant to an appropriate writing system.

## Record audio

- In a field that shows the audio field as empty (![](../../assets/images/Basic_Tasks/Audio_files/Empty%20Audio%20field.png)), click and hold the left mouse button on the record button (![](../../assets/images/Basic_Tasks/Audio_files/Record%20Button.png)) while you record the audio through your microphone. The file name is as follows: \<number\>\<headword\>.wav.

## Link to an existing \*.wav file

- In a field that shows the audio field as empty (![](../../assets/images/Basic_Tasks/Audio_files/Empty%20Audio%20field.png)), press and hold the **Shift** key down while you click the record button (![](../../assets/images/Basic_Tasks/Audio_files/Record%20Button.png)). The **Open** dialog box appears. Click the audio file, and then click **Open**.

See ![](../../assets/images/Important_Icon.gif) **Important** below.

## Play audio

- Click the field that had the audio file, and then click the play button (![](../../assets/images/Basic_Tasks/Audio_files/Play%20Button.png)).

## Delete an audio file

- Click the field that has the audio file, and then click the delete button (![](../../assets/images/Basic_Tasks/Audio_files/RedDeleteX.GIF)) that appears in the field (*not* on the toolbar). The audio file is deleted from the project folder, and the empty symbol (![](../../assets/images/Basic_Tasks/Audio_files/Empty%20Audio%20field.png)) appears in the field.

The full path to the file appears if you hold your mouse pointer over the delete button (![](../../assets/images/Basic_Tasks/Audio_files/RedDeleteX.GIF)).

> [!IMPORTANT]
>
> - If you generated audio files outside of this FLEx project, we recommend that you do *not* copy those files into the **AudioVisual** [folder](../../User_Interface/Menus/File/Backup_and_Restore/Folder_Structure.md) for the current project. Instead, store them in a separate folder on your computer and link to them from there as described above.\
>   The reason is that when you link to an audio file, a copy is added to the **AudioVisual** folder. This allows you to use the same audio recording multiple times without the risk of breaking all of the links if you delete one instance.\
>   However, if you copy them into the **AudioVisual** folder and then link to them a copy is made in that folder, but a numerical value is appended to the file name and that copy is used. The original is not used. If you use the same file multiple times, there can be confusion about which copy or copies of the file are being used.
>
> - If you add an **Audio** variant for a vernacular writing system, you can add an audio file to fields that use the vernacular writing system, such as [Lexeme Form](../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Lexeme_Form_field.md), [Citation Form](../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Complex_Forms.md), and [Example](../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/example_field.md).
>
> - See [Correct sound quality problems (Windows<sup>®</sup>10)](Correct_sound_quality_problem_on_Windows_10.md) if you have poor sound quality.

## Related topics
[Basic Tasks overview](../Basic_Tasks_overview.md)

[Insert a sound or movie file](../../Using_Tools/Lexicon_tools/Lexicon_Edit/Insert_link_to_sound_or_movie.md)

[Specify concordance criteria](../../Using_Tools/Texts_&_Words_tools/Concordance/specify_concordance_criteria.md)
