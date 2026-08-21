---
title: "Configuring Document Layout styles"
source_title: "Configuring Document Layout styles"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Tools"
  - "Configure Document"
  - "Configuring Document Layout styles"
source: "User_Interface/Menus/Tools/Configure_Document/Configuring_Document_view_styles.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Tools/Configure_Document/Configuring_Document_view_styles.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
related:
  - "Classifications -> Classifications.md"
  - "Configure Document layout dialog box -> Configure_Document_View_dialog_box.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:5ee0c4af5c558312"
---

# Configuring Document Layout styles

*User Interface › Menus › Tools › Configure Document*

While you [configure](Configuring_a_Document_view.md) the **Document** layout with the **Configure Document Layout** dialog box, various boxes can appear that help you choose styles. The styles you specify here do *not* affect the fields as displayed in **Record Edit** or **Browse**. *However*, some styles you [apply](../../Format/apply_a_style_to_text.md) to particular content in individual fields can override the style set in the **Configure Document Layout** dialog box.

1.  Click a field label to *highlight* it (such as ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Document/HighlightedTimeOfEvent.PNG)), and then do the following in the *right* pane under **Record:** **\<field name\>**:

    - If a **Styles** button is shown, click it to open the [Styles](../../Format/Styles/Styles_overview.md) dialog box so you can add or modify a style (optional).

    - Then, use any of the available boxes:

<table style="left: 0px; top: 207px;">
<tbody>
<tr>
<th><p>Box</p></th>
<th><p>Use to select the</p></th>
</tr>
&#10;<tr>
<td><p><strong>Character Style for Before string</strong></p></td>
<td><p><em>character</em> style for the <strong>Before</strong> box content.<br />
You cannot apply a style to the <strong>Between</strong> or <strong>After</strong> box contents.</p></td>
</tr>
<tr>
<td><p><strong>Character Style for Content</strong></p></td>
<td><p><em>character</em> style for the contents in the current field (for <em>all</em> writing systems).</p></td>
</tr>
<tr>
<td><p><strong>Paragraph Style for Before header</strong></p></td>
<td><p><em>paragraph</em> style for the <strong>Before</strong> box content.<br />
This box typically appears for field labels, such as <strong>Description</strong>, which appear as headers in this layout.</p></td>
</tr>
<tr>
<td><p><strong>Paragraph Style for Content</strong></p></td>
<td><p><em>paragraph</em> style for the contents in the current field (for <em>all</em> writing systems).</p></td>
</tr>
</tbody>
</table>

2.  Finish the [Configuring the Document layout](Configuring_a_Document_view.md) topic.

> [!NOTE]
>
> - To apply a different style to *individual* writing system for a field, [duplicate the field](../Configure_Dictionary/Duplicate_Dict_field.md). Then, [select one writing system](Configuring_a_Document_view.md) for each copy, and configure each writing system separately.
>
> - If any of the boxes listed above are empty, the **Normal** style is used.

## Related topics
[Classifications](Classifications.md)

[Configure Document layout dialog box](Configure_Document_View_dialog_box.md)
