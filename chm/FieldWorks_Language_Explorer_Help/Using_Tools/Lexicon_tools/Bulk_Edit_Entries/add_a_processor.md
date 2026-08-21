---
title: "Add a processor"
source_title: "Add a processor"
breadcrumb:
  - "Using Tools"
  - "Texts & Words tools"
  - "Bulk Edit Wordforms"
  - "Add a processor"
source: "Using_Tools/Lexicon_tools/Bulk_Edit_Entries/add_a_processor.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Bulk_Edit_Entries/add_a_processor.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Bulk Edit Entries:Add a processor"
  - "Encoding Converters:Python or Perl for processor setup"
  - "Processor"
  - "Processor:Using Perl or Python for processor"
  - "Setup Processor"
  - "Add:Processor"
  - "Bulk Edit Wordforms (See: Texts & Words overview):Add a processor"
  - "Bulk Edit Reversal Entries:Add a processor"
related:
  - "Bulk Edit Entries overview -> Bulk_Edit_Entries_overview.md"
  - "Bulk Edit overview -> bulk_edit_overview.md"
  - "Copy a processor -> copy_a_processor.md"
  - "Technical Support -> ../../../Overview/Technical_support.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:a272b29c35dc3ab0"
---

# Add a processor

*Using Tools › Texts & Words tools › Bulk Edit Wordforms*

1.  In a **Bulk Edit** tool (**Entries**, **Reversal Entries** or **Wordforms**), click the **Process** tab, and then click **Setup**.

    The **Setup Processor** dialog box appears.

2.  Click **Add**.

    The boxes in the **Properties** tab become either empty or available for change, and a **More** button appears.

3.  In the **Converter Name** box, type a descriptive name (that is, the name that appears in the list of encoding converters). Example: SIL Galatia\<\>UNICODE

4.  Select the converter type.

    - If the converter type you need is *not* in the list, click **More**. See **Note** below.

    For additional information, see [Select the converter type](../../../Advanced_Tasks/Writing_Systems/Encoding_Converters/Select_the_converter_type.md).

5.  Select the converter mapping file.

    |  |  |
    |----|----|
    | Converter Type | To select the converter mapping |
    | CC | In the **Converter Mapping File** box, enter the path to a Consistent Change table file that converts from a non-standard (custom) encoding to UTF-8. The ellipsis button ![](../../../assets/images/Ellipsis_button.PNG) allows you to browse for the file. |
    | ICU Unicode to Unicode transducer | In the **Mapping Name** list, select a transformation (for example, a transliteration from one script to another). |
    | TECkit (compiled TEC file) | In the **Converter Mapping File** box, enter the path to a Text Encoding Conversion toolkit *compiled* file. The ellipsis button allows you to browse for the file. |
    | TECkit (source MAP file) | In the **Converter Mapping File** box, enter the path to a Text Encoding Conversion toolkit *source* file. The ellipsis button allows you to browse for the file. |
    | Regular Expression (ICU) | In the **Find-\>Replace** box, type or paste a [regular expression](../../../Basic_Tasks/Filtering_data/About_Regular_Expressions.md). |

6.  Select the *conversion type*, either **Unicode to and from Unicode** or **Unicode to Unicode** (discussed in [Setup Processor dialog box](Using_Setup_Processor_dialog_box.md)).

7.  Click **Close**.

> [!NOTE]
>
> - **More** opens a dialog box with more types. Make a selection, and then click **Add**. Another dialog box will appear. Instructions for that dialog box are in its **About** tab.
>
>   The new processor will appear in the **Available** **Processors** pane. If the selected processor was added with the **More** button, the boxes in the **Properties** tab are *not* available for change. In this case, a **Modify** button appears so you can change processors added with the **More** button.

## Related topics
[Bulk Edit Entries overview](Bulk_Edit_Entries_overview.md)

[Bulk Edit overview](bulk_edit_overview.md)

[Copy a processor](copy_a_processor.md)

[Technical Support](../../../Overview/Technical_support.md)
