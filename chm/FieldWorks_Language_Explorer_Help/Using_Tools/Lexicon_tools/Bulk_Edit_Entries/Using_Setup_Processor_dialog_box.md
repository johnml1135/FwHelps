---
title: "Setup Processor dialog box"
source_title: "Setup Processor dialog box"
breadcrumb:
  - "Using Tools"
  - "Texts & Words tools"
  - "Bulk Edit Wordforms"
  - "Using Setup Processor dialog box"
source: "Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Using_Setup_Processor_dialog_box.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Using_Setup_Processor_dialog_box.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Bulk Edit Entries:Setup Processor dialog box"
  - "Encoding Converters:Python or Perl for processor setup"
  - "Converters:Bulk Edit Processors"
  - "Processor"
  - "Processor:Using Perl or Python for processor"
  - "Processor:Processor"
  - "Setup dialog box"
  - "Setup Processor"
  - "Setup Processor:Setup Processor dialog box"
  - "Add:Processor"
  - "Python or Perl:Setup Processor dialog box"
  - "Perl or Python:Setup Processor dialog box"
  - "TECkit"
  - "CC (Consistent Changes)"
  - "Use or Using:Setup Processor dialog box"
  - "Bulk Edit Wordforms (See: Texts & Words overview):Setup Processor dialog box"
  - "Bulk Edit Reversal Entries:Setup Processor dialog box"
related:
  - "Bulk Edit overview -> bulk_edit_overview.md"
  - "Python and Perl overview -> ../../../Advanced_Tasks/Writing_Systems/Encoding_Converters/Python_Perl_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:ee936161fb7d6edd"
---

# Setup Processor dialog box

*Using Tools › Texts & Words tools › Bulk Edit Wordforms*

The **Setup Processor** dialog box is the same as the [Encoding Converters](../../../Advanced_Tasks/Writing_Systems/Encoding_Converters/Encoding_Converters_overview.md) dialog box, but with two main exceptions:

- It does *not* have the **Test** or **Advanced** tabs.

- The **Available Processors** list includes only those processors described under ![](../../../assets/images/Important_Icon.gif) **Important** below. However, such processors/converters are available in *both* dialog boxes. So, you can use the [Test](../../../Advanced_Tasks/Writing_Systems/Encoding_Converters/Encoding_Converters_Test_tab.md) and [Advanced](../../../Advanced_Tasks/Writing_Systems/Encoding_Converters/Encoding_Converters_Advanced_tab.md) tabs for processors you added in the **Setup Processor** dialog box. Similarly, any deletion or change is reflected in both dialog boxes.

To successfully use all the processor features, you need to have files, such as CC files and TECkit MAP files, available for selection using this dialog box. You may need to work with a consultant to collect and install the necessary files on your computer.

1.  In a **Bulk Edit** tool (**Entries**, **Reversal Entries** or **Wordforms**), click the **Process** tab, and then click **Setup**.

    The **Setup Processor** dialog box appears, with the contents of the **Properties** tab displayed.

2.  Do any of the following:

    - [Add a processor](add_a_processor.md)

    - [Copy a processor](copy_a_processor.md)

    - [Delete a processor](Delete_a_Processor.md)

    - [Change the properties of a processor](change_the_properties_of_a_processor.md)

> [!IMPORTANT]
>
> - The *processors* in the **Setup Processor** dialog box are a *subset* of the *encoding converters* used with writing systems in the [Encoding Converters](../../../Advanced_Tasks/Writing_Systems/Encoding_Converters/Encoding_Converters_overview.md) dialog box. Only *Unicode to Unicode* or *Unicode to and from Unicode* encoding converters are available as bulk edit processors. Those used to convert *legacy fonts-to-Unicode* are only available for use with writing systems during import and will not appear in the **Available Processors** list.
>
> - *Unicode to and from Unicode* specifies a converter that is designed to work in the forward and reverse directions. TECkit files are often of this type. *Unicode to Unicode* means the converter is designed to work only in the forward direction. CC tables are of this type. For example, a converter that converts `9ab` to `9ea` in the *forward* direction, but one that can also convert **9ea** to **9ab** in the *reverse* direction would be a *Unicode to and from Unicode* converter. In FieldWorks **Bulk Edit** tools, we do *not* provide a way to use a converter in a reverse direction, so either one (*Unicode to and from Unicode* or *Unicode to Unicode*) can be used in bulk edit operations, but *only* in the forward direction.
>
> - - A TECkit file may contain one or more passes. Each pass begins with a header line that specifies the type of data expected in this pass.
>
> `pass(`type`)`
>
> The *type* inside the parentheses can be Byte, Unicode, Byte_Unicode, or Unicode_Byte. In FieldWorks Bulk Edit tools, *only* TECkit files with type **Unicode** will be available for use in the **Process** tab. This is because all data in FieldWorks is Unicode, so Byte converters do not make sense in this context. From the **Writing System Properties** dialog or one of the Import dialog boxes, you can use a TECkit map with Unicode, Byte, or Byte_Unicode types as long as the output data is valid Unicode since input data can be byte or Unicode. The pass type occurring in the file *overrides* the **Conversion Type** selection in the FieldWorks converter setup dialog box. To see the real type in the TECkit file, use the **Advanced** tab in the converter setup dialog, which you open from the [Converters](../../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_Converters_tab.md) tab (**Writing System Properties** dialog box); check the `Type` from there.
>
> - The **More** button allows you to add other processors, such as [Python or Perl](../../../Advanced_Tasks/Writing_Systems/Encoding_Converters/Python_Perl_overview.md) or *Compound* converters besides *TECkit*, *CC* and *ICU*.
>
> - TECkit converters may be written for bidirectional operation. In FLEx, operations are normally one way. However, if you need to run a bidirectional converter in the reverse direction, it can be done in FLEx. To do this, click the **More** button next to the **Converter Type**, then add a **Compound Converter** through the dialog that comes up. If you add a bidirectional converter in the **Setup** tab, there is a **Reverse** check box that will run it in the reverse direction.

## Related topics
[Bulk Edit overview](bulk_edit_overview.md)

[Python and Perl overview](../../../Advanced_Tasks/Writing_Systems/Encoding_Converters/Python_Perl_overview.md)

### Related Internet sites

<a href="https://software.sil.org/fieldworks/support/technical-documents/" target="_blank" title="https://software.sil.org/fieldworks/support/technical-documents/">https://software.sil.org/fieldworks/support/technical-documents/</a>

<a href="https://software.sil.org/silconverters/" target="_blank" title="https://software.sil.org/silconverters/">https://software.sil.org/silconverters/</a>

<a href="https://software.sil.org/teckit/" target="_blank" title="https://software.sil.org/teckit/">https://software.sil.org/teckit/</a>
