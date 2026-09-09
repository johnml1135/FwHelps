---
title: "About Lexical Relations"
source_title: "About Lexical Relations"
breadcrumb:
  - "Using Tools"
  - "Lists tools"
  - "About Lexical Relations"
source: "Using_Tools/Lists_tools/About_Lexical_Relations.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lists_tools/About_Lexical_Relations.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Reference Type"
  - "Lexical"
  - "Types"
  - "Types:About Lexical Reference Types"
  - "About:Lexical Relations"
  - "Relation"
  - "lexical"
  - "Antonym"
  - "insert relation"
  - "Calendar"
  - "Classifier"
  - "Compare"
  - "Part/Whole"
  - "Specific/Generic"
  - "Synonym"
related:
  - "Lists overview -> Lists_overview.md"
  - "Modify Mappings dialog box -> ../../Beginning_Tasks/Importing_Data/modify_mapping_dialog_box.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:e33bf18ff0b5ea98"
---

# About Lexical Relations

*Using Tools › Lists tools*

*Lexical relations* establish links so you can indicate lexical relationships. Depending on the [reference set type](About_reference_set_types.md), you insert them at the [entry level](../Lexicon_tools/Lexicon_Edit/About_Lex_Edit_fld_levels.md) ([Cross References](../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/cross_references_field.md) field) *or* sense level ([Lexical Relations](../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/lexical_relations_field.md) field). The different field names prevents having two heading fields with the same name.

The following lexical relations are provided with the FieldWorks Language Explorer, but you can [create](Create_new_Lexical_Relations.md) any number of additional ones.

<table>
<tbody>
<tr>
<th style="width: 25%"><p>Name (abbr) / Reverse Name (abbr)</p></th>
<th style="width: 75%"><p>Description</p></th>
</tr>
&#10;<tr>
<td style="width: 25%"><p><strong>Antonym (ant)</strong></p></td>
<td style="width: 75%"><p>Use this type for antonym relationships (for example, <em>fast</em> and <em>slow</em>). As initial defined, an antonym relationship allows only 2 senses. To allow multiple senses, change the <a href="../../User_Interface/Field_Descriptions/Lists/Lexical_Relations_fields/reference_set_type_field.md">Reference set type</a> field to <strong>Sense Collection</strong>.</p>
<ul>
<li><p>To add this relation, click the <a href="../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/lexical_relations_field.md">Lexical Relations</a> field menu button <img src="../../assets/images/Using_Tools/Lists_tools/Menu_Button_pic.GIF" />, and then choose <strong>Insert Antonym Relation</strong>. Select a specific sense.</p></li>
</ul></td>
</tr>
<tr>
<td style="width: 25%"><p><strong>Calendar (cal)</strong></p></td>
<td style="width: 75%"><p>A calendar relation is a type of scale or sequence set. Sequences include a group of senses that are related in an ordered fashion. The calendar relation is one type of sequence that you can use to store days of the week, months of the year, or similar sequences.</p>
<ul>
<li><p>To create a calendar relation for <em>days of the week</em>, go to the <em>Sunday</em> sense, click the <a href="../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/lexical_relations_field.md">Lexical Relations</a> field menu button <img src="../../assets/images/Using_Tools/Lists_tools/Menu_Button_pic.GIF" />, and then choose <strong>Insert Calendar Relation</strong>. Select the sense for <em>Monday</em>. Continue to add senses for the remaining days of the week.</p></li>
<li><ul>
<li><p><a href="../Lexicon_tools/Lexicon_Edit/move_sequence_entry.md">Move an entry in a sequence</a> if a sense is out of order.<br />
In all scale relations, the current sense shows up in the list since order is important. From any other sense that is part of the sequence, you will see the complete set of senses in exactly the same order.</p></li>
<li><p><a href="../Lexicon_tools/Lexicon_Edit/edit_reference_set_details.md">Edit reference set details</a> allows you to add identifying metadata. In the <strong>Name</strong> box you could type "Days of the week."</p></li>
</ul></li>
<li><p>To create a relation for <em>months of the year</em>, use the same process given for days of the week, but start with a sense representing a month. Then, add the remaining months.</p></li>
</ul></td>
</tr>
<tr>
<td style="width: 25%"><p><strong>Classified Noun (clf. for) / Classifier (clf)</strong></p></td>
<td style="width: 75%"><p>Use this type to create a link between a classifier and the words it classifies.</p>
<ul>
<li><p>To add this relation, go to the lexical entry for the classifier. Click the <a href="../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/lexical_relations_field.md">Lexical Relations</a> field menu button <img src="../../assets/images/Using_Tools/Lists_tools/Menu_Button_pic.GIF" />, and then choose <strong>Insert Classified Noun Relation (to this Classifier)</strong>. Select a noun appropriate for this classifier.</p></li>
<li><p>From the entry for a noun, to indicate its classifier, click the <strong>Lexical Relations</strong> field menu button, and then choose <strong>Insert Classifier Relation (to this Classified Noun)</strong>." Choose the classifier that is used for this word.</p></li>
</ul></td>
</tr>
<tr>
<td style="width: 25%"><p><strong>Compare (cf)</strong></p></td>
<td style="width: 75%"><p>Use this type for general references to other entries. However, it is normally better to use types that are more specific. <a href="Create_new_Lexical_Relations.md">Create a new type</a>, if necessary.</p>
<ul>
<li><p>To add this relation, click the <a href="../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/cross_references_field.md">Cross References</a> field menu button <img src="../../assets/images/Using_Tools/Lists_tools/Menu_Button_pic.GIF" />, and then choose <strong>Insert Compare Relation</strong>. Select an entry that you want to compare with the current entry. You can add additional entries as desired.</p></li>
<li><p>To compare relations to be associated with senses rather than entries, you can change the <a href="../../User_Interface/Field_Descriptions/Lists/Lexical_Relations_fields/reference_set_type_field.md">Reference set type</a> field to <strong>Sense Collection</strong>. It would then show up as an option when you click the <strong>Lexical Relations</strong> field menu button.</p></li>
</ul></td>
</tr>
<tr>
<td style="width: 25%"><p><strong>Part (pt) / Whole (wh)</strong></p></td>
<td style="width: 75%"><p>Use this type to establish a link between the sense for the whole (such as <em>room</em>), and senses for the parts (<em>ceiling, wall, floor</em>).</p>
<ul>
<li><p>To add this relation, start in the sense that represents the <em>whole</em>. Click the <a href="../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/lexical_relations_field.md">Lexical Relations</a> field menu button <img src="../../assets/images/Using_Tools/Lists_tools/Menu_Button_pic.GIF" />, and then choose <strong>Insert Part Relation (to this Whole)</strong>. Select a sense that represents a part of this sense.</p></li>
<li><p>To add more <em>parts</em>, click the ellipsis button <img src="../../assets/images/Ellipsis_button.PNG" /> in the <strong>Part</strong> field and then select another part. Every part selected in this way will automatically have a corresponding <strong>Whole</strong> field. Note that you can actually build a whole/part tree. For example, you could add a <strong>Part</strong> relation to <em>house</em> that includes <em>roof, room,</em> and <em>foundation</em>. The sense <em>room</em> would then show two fields, one for the parts and one for the whole.</p></li>
<li><p>To replace the <em>whole</em>, click the ellipsis button in the <strong>Whole</strong> field, and then select another entry using the <a href="../Lexicon_tools/Lexicon_Edit/Add_Reference_to_Lexical_Relation.md">Replace Reference dialog box</a>.</p></li>
</ul></td>
</tr>
<tr>
<td style="width: 25%"><p><strong>Specific (spec) / Generic (gen)</strong></p></td>
<td style="width: 75%"><p>Use this type to establish a link between the sense for the generic (such as <em>bird</em>), and senses for the specifics (<em>robin, cardinal, dove</em>).</p>
<ul>
<li><p>To add this relation, start in the sense that represents the <em>generic</em>. Click the <a href="../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/lexical_relations_field.md">Lexical Relations</a> field menu button <img src="../../assets/images/Using_Tools/Lists_tools/Menu_Button_pic.GIF" />, and then choose <strong>Insert Specific Relation (to this Generic)</strong>. Select a sense that represents a specific of this sense.</p></li>
<li><p>To add more <em>specifics</em>, click the ellipsis button <img src="../../assets/images/Ellipsis_button.PNG" /> in the <strong>Specific</strong> field, and then select another specific. Every specific selected in this way will automatically have a corresponding <strong>Generic</strong> field.<br />
 <strong>Tip:</strong> You can build a generic/specific tree. For example, you could add a <strong>Specific</strong> relation to <em>animal</em> that includes <em>mammal, bird</em>, and <em>reptile</em>. The sense <em>bird</em> would then show two fields, one for the specifics, and one for the generic.</p></li>
<li><p>To replace the <em>generic</em>, click the ellipsis button in the <strong>Generic</strong> field, and then select another entry using the <a href="../Lexicon_tools/Lexicon_Edit/Add_Reference_to_Lexical_Relation.md">Replace Reference</a> dialog box.</p></li>
</ul></td>
</tr>
<tr>
<td style="width: 25%"><p><strong>Synonyms (syn)</strong></p></td>
<td style="width: 75%"><p>Use this type to establish a link between any number of senses.</p>
<ul>
<li><p>To add this relation from <em>any</em> sense, click the <a href="../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/lexical_relations_field.md">Lexical Relations</a> field menu button <img src="../../assets/images/Using_Tools/Lists_tools/Menu_Button_pic.GIF" />, and then choose <strong>Insert Synonyms Relation</strong>. Select a synonym of the current sense.</p></li>
<li><p>To add more synonyms to the same set, click the ellipsis button <img src="../../assets/images/Ellipsis_button.PNG" /> in the <strong>Synonyms</strong> field, and choose another sense. The other senses will automatically show all of the senses that are part of this set, excluding the current sense.</p></li>
<li><p>To insert <em>another</em> synonym relationship in the same sense, click the <strong>Lexical Relations</strong> field menu button, and then select <strong>Insert Synonym Relation</strong>. This adds another synonym set with the current sense as a member of the set.</p></li>
</ul></td>
</tr>
<tr>
<td style="width: 25%"><p><strong>Sense</strong> or <strong>Entry</strong> or <strong>Entry/Sense Unidirectional</strong></p></td>
<td style="width: 75%"><p>Use one of these options to establish a <em>one-way</em> link. For example, you could have an entry point to another entry, but that second entry would not point back to the first one.</p></td>
</tr>
</tbody>
</table>

> [!TIP]
>
> - The **Date Modified** timestamp is updated when you add or remove members in a set. See [Date](../../User_Interface/Field_Descriptions/Field_Types/date_field.md) field for more information.

## Related topics
[Lists overview](Lists_overview.md)

[Modify Mappings dialog box](../../Beginning_Tasks/Importing_Data/modify_mapping_dialog_box.md)
