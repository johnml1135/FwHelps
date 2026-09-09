---
title: "Merge entries"
source_title: "Merge entries"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Lexicon Edit"
  - "Merge entries"
source: "Using_Tools/Lexicon_tools/Lexicon_Edit/Merge_entries.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Lexicon_Edit/Merge_entries.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Entry"
  - "Merge"
  - "Merge:Lexical entries"
related:
  - "Lexicon Edit overview -> lexicon_edit_overview.md"
  - "Merge allomorphs -> Merge_allomorphs.md"
  - "Merge senses -> Merge_senses.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:c9e09fae8fad166f"
---

# Merge entries

*Using Tools › Lexicon tools › Lexicon Edit*

1.  In the **Navigation** **Pane**, click **Lexicon**, and then click **Lexicon Edit** or **Browse**.

2.  In the **Entries** pane, click the entry that you want to merge *into another entry*.

3.  Do one of the following:

    - On the **Tools** menu, click **Merge with entry**.

    - On the [Information bar](../../../User_Interface/Toolbars/information_bar_overview.md), click the menu button and then click **Merge with entry**.

    The **Merge Entry** dialog box appears.

4.  In the **Find** box, enter the form (lexeme, citation, or allomorphs) of the entry into which you want the selected entry to merge. (You may need to change the writing system in the **Writing System** box.)

    The entry you want to merge the selected entry into appears in the **Lexical Entries** area.

5.  In the **Lexical Entries** area, select the desired entry.

    The informational area at the bottom of the dialog box describes the merge process.

6.  If the informational area describes the correct entries and the intended merge direction, click **Merge**.

    After the merge operation is completed, a **Merge Report** information box appears.

7.  On the **Merge Report** information box, click **OK**.

8.  Because content is *appended* to existing content in each field, manually review and edit the content in each field. Also, additional fields can be added, and you should review them.

For example, if you merge entries that are complex forms, the entry then has two [Complex Form Type](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Complex_Form_Type_field.md) field sets. You can likely right-click one and use the **Delete Complex Form Info** command to delete it.

> [!IMPORTANT]
>
> - If the target entry has existing content in a field, any content in the equivalent field from the merged entry is *appended* into the target entry.
>
> - All senses from the merged entry are added ('appended') to the target entry. Use [Merge Senses](Merge_senses.md) to merge any duplicates.
>
> - When merging entries, if the two lexeme forms are identical, the two entries merge without changing the headword.
>
> - When merging entries, if the two lexeme forms are not identical, FieldWorks version 6.0 and earlier merged the entries and appended the two lexeme forms together. In the process any interlinearized text permanently lost the distinction in the morpheme line, which is probably not what you wanted. In version 6.0.1 instead of appending the two lexeme forms, the lexeme form from the source entry will become an allomorph of the target entry. This maintains interlinear text morpheme lines. If you really want to merge the morpheme lines in interlinear text as happened before, right-click the first line of the new allomorph and choose [Merge Allomorph into](Merge_allomorphs.md) and choose the lexeme form. This will give the same result as earlier versions (pre 6.0.1), except the lexeme form will remain unchanged instead of appending the two forms.

## Related topics
[Lexicon Edit overview](lexicon_edit_overview.md)

[Merge allomorphs](Merge_allomorphs.md)

[Merge senses](Merge_senses.md)
