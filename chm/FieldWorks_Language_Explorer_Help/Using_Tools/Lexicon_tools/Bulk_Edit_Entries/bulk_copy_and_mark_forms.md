---
title: "Bulk copy and mark lexeme forms"
source_title: "Bulk copy and mark lexeme forms"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Bulk Edit Entries"
  - "Bulk copy and mark lexeme forms"
source: "Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_copy_and_mark_forms.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_copy_and_mark_forms.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Bulk Edit Entries:Bulk copy and mark lexeme forms"
related:
  - "Add a processor -> add_a_processor.md"
  - "Bulk Edit Entries overview -> Bulk_Edit_Entries_overview.md"
  - "Bulk Edit overview -> bulk_edit_overview.md"
  - "Using regular expressions assistance -> ../../../Basic_Tasks/Filtering_data/Using_regular_expressions_assistance.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:38384ac1fe850ce3"
---

# Bulk copy and mark lexeme forms

*Using Tools › Lexicon tools › Bulk Edit Entries*

Here is one possible way of many to copy lexeme forms into the **Citation Forms** field and to mark those copied citation forms, to distinguish them from existing citation forms. Use this topic as an example.

1.  In the **Navigation** **Pane**, click **Lexicon**, and then click **Bulk Edit Entries**.

2.  Click the **Process** tab.

3.  Do one or more of the following to display and then select the entries you will change:

    - [Use](../../../Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.md) the **Configure Columns** dialog box to hide/show/move columns and specify writing systems, if permitted.

    - [Filter](../../../Basic_Tasks/Filtering_data/filtering_data_overview.md) or [sort](../../../Basic_Tasks/Sorting_data/Sorting_data_overview.md) the data to display only applicable entries. In this case, you will likely want to filter the **Citation Form** field for **Blanks**.

    - In the left column, [select the rows](select_rows.md) you want to change.

4.  In the **Bulk Edit Operation** pane, do the following:

    - In the **Source Field** box, select **Lexeme Form**.

    - In the **Target Field** box, select **Citation Form**.

    - In the **If the Target field is not empty** pane, make an appropriate selection or leave **Do nothing** selected. (If the **Blanks** filter is set in the **Citation Form** field, then any selection is appropriate.)

    - Click **Setup**, and then in the **Setup Processor** dialog box, click **Add**.

    - Type a name, such as **Copy and Mark**, in the **Converter Name** box.

    - Select **Regular Expression (ICU)** in the **Converter Type** box.

    - In the **Find-\> Replace** box, type: `(.+)-> $1 Marked`

<table style="margin-left: 15px;" width="75.196%">
<tbody>
<tr>
<th><p>Component</p></th>
<th width="540"><p>Function</p></th>
</tr>
&#10;<tr>
<td><p><code>.+</code></p></td>
<td width="540"><p>Match as many characters as possible but at least one.</p></td>
</tr>
<tr>
<td><p><code>( )</code></p></td>
<td width="540"><p>Capture whatever is matched and call it $1</p></td>
</tr>
<tr>
<td><p><code>-</code><code>&gt;</code></p></td>
<td width="540"><p>Replace this with</p></td>
</tr>
<tr>
<td><p><code>$1</code></p></td>
<td width="540"><p>Whatever was matched</p></td>
</tr>
<tr>
<td><p><code>Marked</code></p></td>
<td width="540"><p>This is just the word <em>Marked</em> preceded with a space.</p>
<p>You can change this to whatever marker you wish, though you will need to take care with any characters that are meaningful in regular expressions.</p></td>
</tr>
</tbody>
</table>

5.  Click **Close**.

    The new converter appears in the **Process** box.

6.  Click **Preview**, and then review the pending changes in the **Citation Form** column.

    The column shows an arrow ![](../../../assets/images/Using_Tools/Lexicon_tools/Bulk_Edit_Entries/Blue_Arrow.GIF) that points to the new content.

7.  If you decide not to change an individual entry after you preview the changes, clear the check box at the left end of the row for that entry. To clear the preview so you can start again, click **Clear**.

8.  When you are satisfied with the changes as indicated by the preview, click **Apply**.

    The entries with a check mark change, as shown in the preview.

## Related topics
[Add a processor](add_a_processor.md)

[Bulk Edit Entries overview](Bulk_Edit_Entries_overview.md)

[Bulk Edit overview](bulk_edit_overview.md)

[Using regular expressions assistance](../../../Basic_Tasks/Filtering_data/Using_regular_expressions_assistance.md)
