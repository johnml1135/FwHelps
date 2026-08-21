---
title: "Upload to Webonary"
source_title: "Upload to Webonary"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "File"
  - "Upload to Webonary"
source: "User_Interface/Menus/File/Upload_to_Webonary.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/File/Upload_to_Webonary.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Publish:Upload to Webonary"
  - "Upload to Webonary"
  - "Web:Publish to Webonary"
  - "Webonary"
  - "upload to"
  - "upload to:Webonary"
related:
  - "File menu overview -> File_overview.md"
  - "Manage Dictionary Layouts dialog box -> ../Tools/Configure_Dictionary/Manage_Dictionary_Views.md"
  - "Manage Reversal Index Layouts dialog box -> ../Tools/Configure_Reversal_Index/Manage_Views_Reversal_Index.md"
  - "Show Minor Entry field -> ../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Variants_level_fields/Show_Minor_Entry_Var_level.md"
  - "Webonary -> Export/Webonary.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:37966bffedf3d69c"
---

# Upload to Webonary

*User Interface › Menus › File*

### Prerequisites

- You need to have an account at <a href="https://www.webonary.org/" style="font-family: Verdana, sans-serif;" target="_blank" title="https://www.webonary.org/">https://www.webonary.org/</a>.

You will be given a site name. It is usually the FieldWorks project name, but could be different.

**See:** <a href="https://www.webonary.org/host-your-dictionary-at-webonary-org/" style="font-family: Verdana, sans-serif;" target="_blank" title="https://www.webonary.org/host-your-dictionary-at-webonary-org/">https://www.webonary.org/host-your-dictionary-at-webonary-org/</a>.

- Prepare the dictionary and reversal indexes. This includes (*not exhaustive*):

  - <a href="../../../Basic_Tasks/Show_data/Show_in_from_Lexicon.md" style="font-family: Verdana, sans-serif;">Sort</a> and <a href="../../../Basic_Tasks/Filtering_data/filter_lexical_entries.md" style="font-family: Verdana, sans-serif;">filter</a> the entries.

  - <a href="../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_Publish_In_publications.md" style="font-family: Verdana, sans-serif;">Choose</a> a [publication](../../Field_Descriptions/Lists/Publications/What_is_a_Publication.md) in **Publish** \<item\> **In** fields to <a href="../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_publishable_lexical_data.md" style="font-family: Verdana, sans-serif;">specify publishable lexical data</a>.

  - <a href="../Tools/Configure_Dictionary/Using_the_Configure_Dictionary_dialog_box.md" style="font-family: Verdana, sans-serif;">Configure</a> one or more dictionary [layout](../Tools/Configure_Dictionary/Dictionary_views.md). This can include [using](../Tools/Configure_Dictionary/Manage_Dictionary_Views.md) the **Manage Dictionary Layouts** dialog box.

  - [Configure](../Tools/Configure_Reversal_Index/Configuring_a_reversal_index_view.md) one or more reversal index layout.

This can include [using](../Tools/Configure_Reversal_Index/Manage_Views_Reversal_Index.md) the **Manage Reversal Index Layouts** dialog box.

- In the Navigation pane, click **Lexicon Edit**, **Browse** or **Dictionary**.

On the **File** menu, click **Upload to Webonary**. Then, do the following:

1.  In the **Site name** box, type your site name.

<!-- -->

2.  In the **Username** box, type your username.

3.  In the **Password** box, type your Webonary password.

4.  Click the **Publication** control down arrow and then click the publication.

5.  Click the **Layout** down arrow and then click the desired layout.

The layouts you can click are only those that are available to the publication you chose in the previous step. Available layouts were set in the **Manage Dictionary Layouts** or **Manage Reversal Index Layouts** dialog boxes.

6.  In the **Reversals** box, select (![](../../../assets/images/CheckedBox.PNG)) any of the reversal indexes that you want to include with the vernacular dictionary.

7.  Click **Submit** to upload the dictionary and any reversal indexes.

8.  Click **View Report** to open the **Webonary Log** dialog box.

- You can click **Full Log** to see the entire upload history.

- Click **Rejected Files** or **Errors & Warning** to only rows that show a problem.

You might want to [get more help](../../../Overview/Technical_support.md) if you see problems.

- Click **Save Log** to save a copy of the log to your computer.

> [!NOTE]
>
> - Any \*.wav files in your FLEx data are converted to \*.mp3 when uploaded to Webonary.\
>   You may notice an increased upload time if you have many \*.wav files.
>
> - FieldWorks does not support \*.tif. You need to convert them.
>
> Supported file formats for Webonary exports include:\
> \*.wav, \*.jpg, \*.jpeg, \*.gif, \*.png, \*.mp3, \*.mp4, and \*.3gp.
>
> These are supported by most web browsers, including the embedded Firefox browser that FLEx uses to display entries in **Dictionary**.

## Related topics
<a href="File_overview.md" style="font-family: Verdana, sans-serif;">File menu overview</a>

[Manage Dictionary Layouts dialog box](../Tools/Configure_Dictionary/Manage_Dictionary_Views.md)

[Manage Reversal Index Layouts dialog box](../Tools/Configure_Reversal_Index/Manage_Views_Reversal_Index.md)

[Show Minor Entry field](../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Variants_level_fields/Show_Minor_Entry_Var_level.md)

[Webonary](Export/Webonary.md)
