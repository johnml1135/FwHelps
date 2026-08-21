---
title: "Export Semantic Domain Worksheets"
source_title: "Export Semantic Domain Worksheets"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "File"
  - "Export"
  - "Export Semantic Domain Worksheets"
source: "User_Interface/Menus/File/Export/Export_Semantic_Domain_Worksheets.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/File/Export/Export_Semantic_Domain_Worksheets.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Semantic Domain"
  - "Semantic Domain:Export Semantic Domain Worksheets"
  - "Print:Semantic Domain Worksheets"
  - "export/print"
  - "Rapid Words"
  - "Rapid Words:Export Semantic Domain Worksheets"
  - "Export:Semantic Domain Worksheets"
  - "Collect Words:Export Semantic Domain Worksheets"
  - "Worksheet"
  - "Semantic Domain export"
  - "Questionnaires"
related:
  - "Export overview -> Export_overview.md"
  - "Semantic Domains fields overview -> ../../../Field_Descriptions/Lists/Semantic_Domains_fields/Semantic_Domains_fields_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:d8d608d963ad095d"
---

# Export Semantic Domain Worksheets

*User Interface › Menus › File › Export*

You can export and print semantic domain worksheets (questionnaires), and then use them to collect words, such as in a *Rapid Word Collection* workshop.

The exported file opens by default in Microsoft Word® (Word). In Word, modify styles to hide or show the example words, questions and descriptions.

1.  If you will export and print the questionnaire in a writing system other than English, you need to have the Semantic Domains list available in FLEx in that writing system. **See:** [User Interface language for Lists](../../Tools/Options/User_interface_languages_for_lists.md).

2.  On the **File** menu, click **Export**.

The **Export** dialog box appears.

3.  Click **Semantic Domain Worksheets**, and then click **Export**.

The **Export Semantic Domains** dialog box appears.

4.  Do the following:

<!-- -->

3.  - Select the writing system for the semantic domain questionnaire.

The **Include English (in red) if translation is missing** check box becomes available if you selected a writing system other than English.

1.  - Select (![](../../../../assets/images/CheckedBox.PNG)) the check box if you want data that is *not* [translated](../../Tools/Options/User_interface_languages_for_lists.md) into the selected writing system to be displayed in English, with a red font color.

If the check box is cleared (![](../../../../assets/images/UncheckedBox.PNG)), untranslated data is *omitted*. Be aware that the export process exports content from these [fields](../../../Field_Descriptions/Lists/Semantic_Domains_fields/Semantic_Domains_fields_overview.md): **Name**, **Abbreviation**, **Example Words**, **Question** and **Descriptions**.

1.  - Click **Export**.

The **Export to DOC** dialog box appears.

3.  - Choose a folder for the export file, type a name in the **File name** box, and then click **Save**.

The folder opens with the file selected.

5.  Open the file in Word. Then do *any* of the following:

    - [Example words](../../../Field_Descriptions/Lists/Semantic_Domains_fields/Example_Words_field_Semantic_Domains.md) are hidden by default. To display them, clear (![](../../../../assets/images/UncheckedBox.PNG)) the **Hidden** check box for the **words** style.

**Tip:** In Word, this check box typically appears in the **Font** dialog box (below **Effects**) when you modify styles. You may be able to use the shortcut keys `Ctrl+Shift+S` to open a dialog box that lists the styles and displays the **Modify** button.

4.  - [Questions](../../../Field_Descriptions/Lists/Semantic_Domains_fields/Question_field_Semantic_Domains.md) use either the **quest** or **quest1** style. The difference between these two styles is in the default line and page-break settings. You can modify these styles or apply them differently as desired.

    - [Descriptions](../../../Field_Descriptions/Lists/Semantic_Domains_fields/description_field_semantic_domains.md) use the **descr** style. Modify this style as desired.

    - English substitutions for untranslated data use the **english** style, set to use a red font by default. Modify this style as desired.

    - To control pagination, modify the **Heading1** or **Heading2** styles.

The file **folderStart** lists the numbers of the semantic domains that use the **Heading1** style, which by default means each one starts on a new page. The rest use **Heading2**.

**folderStart** is installed at: C:\Program Files\SIL\FieldWorks 9\Language Explorer\Export Templates

**Tip:** Use the **Print Layout** view to see the page breaks.

6.  When the data you want is displayed and paginated as desired, print a *limited range* of pages.

Be aware that more than 1800 pages are required if you print the entire set of semantic domains with a page break before the beginning of EACH domain.

> [!NOTE]
>
> - Refer to Word help to learn how to modify styles in the version of Word you use. Or see sites like: <a href="https://www.shaunakelly.com/word/styles/modifyastyle.html" target="_blank" title="https://www.shaunakelly.com/word/styles/modifyastyle.html">https://www.shaunakelly.com/word/styles/modifyastyle.html</a>
>
> - The output is an HTML file but with a .doc filename extension so that it opens in Microsoft Word<sup>®</sup> by default. If you want to open it in an internet browser or use it in some other way, you can change the filename extension from .doc back to .htm (or .html).

## Related topics
[Export overview](Export_overview.md)

[Semantic Domains fields overview](../../../Field_Descriptions/Lists/Semantic_Domains_fields/Semantic_Domains_fields_overview.md)

## Related links
<a href="https://rapidwords.net/" target="_blank" title="https://rapidwords.net/">https://rapidwords.net/</a>
