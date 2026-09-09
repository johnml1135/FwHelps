---
title: "Import SFM data examples"
source_title: "Import SFM data examples"
breadcrumb:
  - "Beginning Tasks"
  - "Importing Data"
  - "Import SFM data examples"
source: "Beginning_Tasks/Importing_Data/Import_SFM_data_examples.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Beginning_Tasks/Importing_Data/Import_SFM_data_examples.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Import:SFM data examples"
related:
  - "Import overview -> Import_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:32e2bc0ee66a5793"
---

# Import SFM data examples

*Beginning Tasks › Importing Data*

If your lexical SFM data file has instances of multiple items in one field separated by a delimiter, the topic [Import Standard Format lexical data](Import_Standard_Format_lexical_data.md) asks you to consider which to split into multiple fields.

However, FLEx does not allow multiple fields to exist in the SFM file for *some* fields. For each destination field in FLEx, the information displayed when you click **Show Info** in the [Modify Mapping](modify_mapping_dialog_box.md) dialog box includes whether the field *allows* or *does not allow* multiple SFM fields in the SFM file, and in some cases, the action taken by the import process. It is also important to know if the field is selected as a [key marker](Step_5_of_8_Key_markers.md) as these begin a group of related fields.

The examples that follow should help you understand the potential results.

### Examples

<table width="100%">
<tbody>
<tr>
<th style="width: 33%"><p>Field</p></th>
<th style="width: 20%"><p>Allows multiple SFM fields?</p></th>
<th style="width: 46%"><p>Result</p></th>
</tr>
&#10;<tr>
<td style="width: 33%"><p><strong>Category (Part Of Speech)</strong></p></td>
<td style="width: 20%"><p><strong>No</strong></p></td>
<td style="width: 46%"><p>A field <code>\ps n;v</code> would appear as <code>n:v</code> in the FLEx <strong>Grammatical Info</strong> field.</p>
<p>If split (<code>\ps n</code> and <code>\ps v</code>), the result is two senses in FLEx; one a noun and the second a verb.</p></td>
</tr>
<tr>
<td style="width: 33%"><p><strong>Definition</strong></p></td>
<td style="width: 20%"><p><strong>Yes</strong></p></td>
<td style="width: 46%"><p>Field contents are appended into a single definition.</p>
<p>If this is not the desired results, you need to separate them with a key marker, such as a part of speech, to force the definitions into separate senses.</p></td>
</tr>
<tr>
<td style="width: 33%"><p><strong>Homonym number</strong></p></td>
<td style="width: 20%"><p><strong>No</strong></p></td>
<td style="width: 46%"><p>The <strong>Import Preview Results</strong> report includes multiple homonym number fields as an “error” you need to fix.</p>
<p>If ignored, you could see incorrect homonym numbers.</p></td>
</tr>
<tr>
<td style="width: 33%"><p><strong>Status</strong></p></td>
<td style="width: 20%"><p><strong>No</strong></p></td>
<td style="width: 46%"><p>The <strong>Import Preview Results</strong> report will include this as a “problem to review. “</p>
<p>If ignored, the import process will discard content from all but the last field</p></td>
</tr>
</tbody>
</table>

> [!TIP]
>
> - For more information about importing, point to **Resources** on the [Help](../../User_Interface/Menus/Help/Help_overview.md) menu, and then click **Technical Notes on SFM Database Import**.

## Related topics
[Import overview](Import_overview.md)
