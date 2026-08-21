---
title: "Set Type example – Entry or Sense Tree"
source_title: "Set Type example – Entry or Sense Tree"
breadcrumb:
  - "Using Tools"
  - "Lists tools"
  - "Reference set type example – Entry or Sense Tree"
source: "Using_Tools/Lists_tools/Set_Type_example_entry_or_sense_tree.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lists_tools/Set_Type_example_entry_or_sense_tree.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Reference set types"
  - "Set Type"
related:
  - "Lists overview -> Lists_overview.md"
  - "About Lexical Relations -> About_Lexical_Relations.md"
  - "Add reference to lexical relation -> ../Lexicon_tools/Lexicon_Edit/Add_Reference_to_Lexical_Relation.md"
  - "Add reference to cross reference lexical relation -> ../Lexicon_tools/Lexicon_Edit/Add_Reference_to_CR_lexical_relation.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:7fe713413ee2f383"
---

# Set Type example – Entry or Sense Tree

*Using Tools › Lists tools*

In this example, the lexical relation is as follows:

- **Name** is "`Test`" and its **Abbreviation** is "`tst`"

- **Reverse Name** is "`Result`" and its **Reverse Abbreviation** is "`rslt`"

**Three variations** of this [reference set type](../../User_Interface/Field_Descriptions/Lists/Lexical_Relations_fields/reference_set_type_field.md) are included below. Notice how the dictionary entry changes depending upon if the relation was established at the entry level, or the sense level, and if an entry or sense was selected in the dialog box.

<table width="100%">
<tbody>
<tr>
<td style="width: 16%"><h3 id="variation-1">Variation 1</h3></td>
<td style="width: 84%"><h3 id="sample-entries">Sample entries:</h3></td>
</tr>
<tr>
<td style="width: 16%"></td>
<td style="width: 84%"><p><strong>ResultEntry</strong> <em>tst:</em> <strong>TestEntry</strong> <em>N.</em> ResultEntry definition.</p></td>
</tr>
<tr>
<td style="width: 16%"></td>
<td style="width: 84%"><p><strong>TestEntry</strong> <em>rslt:</em> <strong>ResultEntry</strong> <em>N.</em> TestEntry definition.</p></td>
</tr>
</tbody>
</table>

> [!NOTE]
>
> - In **Variation 1**, the lexical relation was added to the **Cross References** field (*entry* level).
>
> - In **Step 2** of the **Identify Test entry** dialog box (note that "Test" in dialog box name came from the name of the lexical reference type—see above), **Choose the selected lexical entry** was selected.
>
> <table width="100%">
> <tbody>
> <tr>
> <td style="width: 18%"><h3 id="variation-2">Variation 2</h3></td>
> <td style="width: 82%"><h3 id="sample-entries-1">Sample entries:</h3></td>
> </tr>
> <tr>
> <td style="width: 18%"></td>
> <td style="width: 82%"><p><strong>ResultEntry</strong> <em>N.</em> ResultEntry definition. <em>tst:</em> <strong>TestEntry</strong></p></td>
> </tr>
> <tr>
> <td style="width: 18%"></td>
> <td style="width: 82%"><p><strong>TestEntry</strong> <em>N.</em> TestEntry definition. <em>rslt:</em> <strong>ResultEntry</strong></p></td>
> </tr>
> </tbody>
> </table>

> [!NOTE]
>
> - In the **Variation 2**, the lexical relation was added to the **Lexical References** field (*sense* level).
>
> - In **Step 2** of the **Identify Test entry** dialog box, **Choose a sense of the entry** was selected.
>
> <table width="100%">
> <tbody>
> <tr>
> <td style="width: 16%"><h3 id="variation-3">Variation 3</h3></td>
> <td style="width: 84%"><h3 id="sample-entries-2">Sample entries:</h3></td>
> </tr>
> <tr>
> <td style="width: 16%"></td>
> <td style="width: 84%"><p><strong>ResultEntry</strong> <em>N.</em> ResultEntry definition. <em>tst:</em> <strong>TestEntry</strong></p></td>
> </tr>
> <tr>
> <td style="width: 16%"></td>
> <td style="width: 84%"><p><strong>TestEntry</strong> <em>rslt:</em> <strong>ResultEntry</strong> <em>N.</em> TestEntry definition.</p></td>
> </tr>
> </tbody>
> </table>

> [!NOTE]
>
> - In the **Variation 3**, the lexical relation was added to the **Lexical References** field (*sense* level).
>
> - In **Step 2** of the **Identify Test entry** dialog box **Choose the selected lexical entry** was selected.

> [!IMPORTANT]
>
> - Each **Entry or Sense Tree** uses *two* names: **Name** and **Reverse Name**
>
> - To ensure the proper relational *direction* for reference set types with two names begin in the root entry (here a "Result") and add to it the leaves (here "Test").
>
>   In particular, in an *entry* when you right-click the **Cross References** label (or in the *sense* you right-click the **Lexical Relations** label) to add the relation, the text in the menu command reflects the available lexical relations. For each of the samples above, the right-click menu reads, "**Insert Test Relation (to this Result)**."
>
>   You can swap the **Name** and **Abbreviation** with the **Reverse Name** and **Reverse Abbreviation** in [Lists area](Lists_overview.md) to reverse the root/leaves relationship.

## Related topics
[Lists overview](Lists_overview.md)

[About Lexical Relations](About_Lexical_Relations.md)

[Add reference to lexical relation](../Lexicon_tools/Lexicon_Edit/Add_Reference_to_Lexical_Relation.md)

[Add reference to cross reference lexical relation](../Lexicon_tools/Lexicon_Edit/Add_Reference_to_CR_lexical_relation.md)
