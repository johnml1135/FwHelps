---
title: "Print Dictionary or Reversal Index"
source_title: "Print Dictionary or Reversal Index"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Reversal Indexes"
  - "Print Dictionary or Reversal Index"
source: "User_Interface/Menus/File/Print_Dictionary_or_Reversal_Index.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/File/Print_Dictionary_or_Reversal_Index.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Print"
  - "Print:Print Dictionary or Reversal Index"
  - "Dictionary:Print Dictionary or Reversal Index"
  - "Reversal Indexes:Print Dictionary or Reversal Index"
  - "Dictionary view:Print Dictionary or Reversal Index"
related:
  - "Configure Dictionary dialog box -> ../Tools/Configure_Dictionary/Configure_Dictionary.md"
  - "Configure Reversal Index dialog box -> ../Tools/Configure_Reversal_Index/Configure_Reversal_Index_dialog_box.md"
  - "Configure Document Layout dialog box -> ../Tools/Configure_Document/Configure_Document_View_dialog_box.md"
  - "File overview -> File_overview.md"
  - "Page Setup -> Page_Setup.md"
  - "Print content -> Print_content.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:b73bed75de88dedd"
---

# Print Dictionary or Reversal Index

*Using Tools › Lexicon tools › Reversal Indexes*

If your dictionary or reversal index has *more than* 1000 entries after any filters are applied, do the steps in this topic.

Otherwise, see [Print](Print.md).

1.  [Sort](../../../Basic_Tasks/Sorting_data/Sorting_data_overview.md) and [filter](../../../Basic_Tasks/Filtering_data/filter_lexical_entries.md), as desired, so only the content you want to print is displayed in **Dictionary** or **Reversal Indexes**.

2.  In the **Navigation Pane** click **Lexicon** and then click **Dictionary** or **Reversal Indexes**.

Each **Dictionary** [tab](../../../Using_Tools/Lexicon_tools/Dictionary/Navigating_in_Dictionary.md) or **Reversal Index** [tab](../../../Using_Tools/Lexicon_tools/Reversal_Indexes/Navigating_in_Reversal_Indexes.md) displays a maximum of 1000 entries.

3.  If you want to print only one or more particular entries, select them.

4.  On the **File** menu click **Print**, or press the [shortcut keys](../../Shortcuts/shortcut_keys_on_the_File_menu.md) **Ctrl+P**.

The **Generate all entries before printing** question box appears.

5.  If you click **Yes** in the question box, all the entries are generated and sent to a PDF file. You can print your entries from that PDF file.

6.  If you click **No** in the question box, only the 1000 entries in the displayed tab are available for the **Print** dialog box.

Do these steps:

- In the **Print** dialog box, specify settings as necessary, and then click **OK**. If you printed to a file, instead of a printer, click the folder for that file, and then click **Save**.

- If there are more entries to print, do these steps:

  - Click the next tab in **Dictionary** or **Reversal Index** to display the next 1000 entries.

  - On the **File** menu, click **Print**, or press the shortcut keys **Ctrl+P**. Then continue as discussed above.

> [!NOTE]
>
> - By default, if you have more than 10,000 entries, the entries are automatically sent to a PDF file.
>
> Advanced users can add an environmental variable (FIELDWORKS_PRINT_LIMIT=) to their computer operating system and change that default limit to some other number of entries.
>
> If you set this variable, you will need to restart FieldWorks before it takes effect.
>
> You might need to [get more help](../../../Overview/Technical_support.md).

## Related topics
[Configure Dictionary dialog box](../Tools/Configure_Dictionary/Configure_Dictionary.md)

[Configure Reversal Index dialog box](../Tools/Configure_Reversal_Index/Configure_Reversal_Index_dialog_box.md)

[Configure Document Layout dialog box](../Tools/Configure_Document/Configure_Document_View_dialog_box.md)

[File overview](File_overview.md)

[Page Setup](Page_Setup.md)

[Print content](Print_content.md)
