---
title: "Delete a lexical relation"
source_title: "Delete a lexical relation"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Lexicon Edit"
  - "Delete a lexical relation"
source: "Using_Tools/Lexicon_tools/Lexicon_Edit/Delete_a_lexical_relation.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Lexicon_Edit/Delete_a_lexical_relation.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Delete:Lexical relation"
  - "Delete:Cross reference lexical relation"
  - "Cross Reference"
  - "Cross Reference:Delete a lexical relation"
  - "Lexical Relation"
  - "Remove:Cross Reference or Lexical Relation"
related:
  - "Lexicon Edit fields overview -> ../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Lexicon_Edit_fields_overview.md"
  - "Lexicon Edit overview -> lexicon_edit_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:e0fe1881a8b3f5e0"
---

# Delete a lexical relation

*Using Tools › Lexicon tools › Lexicon Edit*

To delete a lexical relation (the *reference* entry and maybe the *field* it is in) from a lexical entry, do the steps in this topic.

(To delete a lexical relation from the **Lists** area, where the lexical relations are [created](../../Lists_tools/Create_new_Lexical_Relations.md) and stored, see [Delete a list item](../../Lists_tools/Delete_a_list_item.md).)

## Delete a reference but retain the field

1.  In the **Navigation** **Pane**, click **Lexicon**, and then click **Lexicon Edit**.

2.  In the **Entries** pane, click the entry from which you will remove a reference.

3.  In the **Entry** pane, if you cannot see the field that has the reference you want to delete below the **Cross References** (entry level) or **Lexical Relations** (sense level) field, click [Show Hidden Fields](../../../Basic_Tasks/Showing_and_hiding_fields/Show_Hidden_Fields.md).

4.  Depending on the [reference set type](../../Lists_tools/About_reference_set_types.md) of the lexical relation, you are able to do *one* of the following:

    - For *some* types (such as *collections*), select a reference, and then press `Delete` on the keyboard. The selected reference is deleted, but the field is *not* deleted.

      For some (such as a *sequence/scale*, when you try to select and delete the *last* reference), the **Delete Lexical Relation** warning box appears after you press **Delete**. In this case, click **Delete** in the warning box to delete the reference and the field.

    - For *other* types (such a *pairs*), *or* if the selected relation is the parent entry (such as the *generic* of a set of *specifics*), you *cannot* select and delete a reference. In these cases, click the menu button ![](../../../assets/images/Using_Tools/Lexicon_tools/Lexicon_Edit/Menu_Button_pic.GIF) and then click **Replace** **Reference**. This allows you to [select a replacement reference](Add_Reference_dialog_box_graphic.md).

    If neither of the options above are appropriate for you, do the steps below.

## Remove the field and its references

1.  In the **Navigation** **Pane**, click **Lexicon**, and then click **Lexicon Edit**.

2.  In the **Entries** pane, click the entry from which you will remove a lexical relation (reference(s) and the field).

3.  In the **Entry** pane, if you cannot see the lexical relation you want to delete below the **Cross References** (entry level) or **Lexical Relations** (sense level) field, click [Show Hidden Fields](../../../Basic_Tasks/Showing_and_hiding_fields/Show_Hidden_Fields.md).

4.  Click the reference in the lexical relation you will delete.

    A menu button ![](../../../assets/images/Using_Tools/Lexicon_tools/Lexicon_Edit/Menu_Button_pic.GIF) appears.

5.  Click the menu button, and then click **Delete Relation**.

    The **Delete Lex****ical** **Relation** warning box appears.

6.  If you are sure you want to delete the lexical relation specified in the warning box, click **Delete**.

    The lexical *reference*(s) (that is, the lexical entry or entries) and the *relation* (that is, the field) are removed from the current entry. Depending on the [reference set type](../../Lists_tools/About_reference_set_types.md) lexical references and relations may or may not continue to exist in other entries that use that lexical relation.

    For example, if the reference set type was a *pair*, deleting either of the relations deletes the entire relationship. However, for a *collection*, deleting one relation may not affect all the other relations in the collection.

## Related topics
[Lexicon Edit fields overview](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Lexicon_Edit_fields_overview.md)

[Lexicon Edit overview](lexicon_edit_overview.md)
