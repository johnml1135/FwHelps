---
title: "Set Type example – Sense Tree"
source_title: "Set Type example – Sense Tree"
breadcrumb:
  - "Using Tools"
  - "Lists tools"
  - "Reference set type example – Sense Tree"
source: "Using_Tools/Lists_tools/Set_Type_example_sense_tree.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lists_tools/Set_Type_example_sense_tree.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
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
content_hash: "sha256:5e4329fba5297908"
---

# Set Type example – Sense Tree

*Using Tools › Lists tools*

In this example, the lexical relation is as follows:

- **Name** is "`Parts`" and its **Abbreviation** is "`pt`"

- **Reverse Name** is "`Whole`" and its **Reverse Abbreviation** is "`wh`"

<table width="100%">
<tbody>
<tr>
<td style="width: 100%"><h3 id="sample-entries"><strong>Sample entries:</strong></h3></td>
</tr>
<tr>
<td style="width: 100%"><p><strong>ceiling</strong> <em>N.</em> The overhead upper surface of a room. <em>wh:</em> <strong>room</strong></p></td>
</tr>
<tr>
<td style="width: 100%"><p><strong>floor</strong> <em>N.</em> The inside lower horizontal surface of a room. <em>wh:</em> <strong>room</strong></p></td>
</tr>
<tr>
<td style="width: 100%"><p><strong>room</strong> <em>N.</em> An area in a building enclosed by walls, a floor and a ceiling. <em>pt</em>: <strong>floor</strong>, <strong>ceiling</strong>, <strong>wall</strong></p></td>
</tr>
<tr>
<td style="width: 100%"><p><strong>wall</strong> <em>N.</em> The partition between rooms in a building or the outside. <em>wh:</em> <strong>room</strong>; pt: <strong>window</strong></p></td>
</tr>
<tr>
<td style="width: 100%"><p><strong>window</strong> <em>N.</em> A glass pane built into a wall to admit light into a room. <em>wh:</em> <strong>wall</strong></p></td>
</tr>
</tbody>
</table>

> [!IMPORTANT]
>
> - Each **Sense Tree** uses two names: **Name** and **Reversal Name**.
>
> - To ensure the proper relational *direction* for reference set types with two names begin in the root entry (here "Whole") and add to it the leaves (here "Parts").
>
>   In particular, when you right-click the **Lexical Relations** label in a sense to add the relation, the text in the menu command reflects the available lexical relations. In this example, the right-click menu reads, "**Insert Part Relation (to this Whole)**" so you begin in the "room" entry.
>
>   You can swap the **Name** and **Abbreviation** with the **Reverse Name** and **Reverse Abbreviation** in [Lists area](Lists_overview.md) to reverse the root/leaves relationship.
>
> - Notice that in the sample entries above the entry "**wall**" *is* a part of a whole (*wh:* **room**) and also *has* a part (*pt:* **window**). The entry "**wall**" was treated as both a root and a leaf.

## Related topics
[Lists overview](Lists_overview.md)

[About Lexical Relations](About_Lexical_Relations.md)

[Add reference to lexical relation](../Lexicon_tools/Lexicon_Edit/Add_Reference_to_Lexical_Relation.md)

[Add reference to cross reference lexical relation](../Lexicon_tools/Lexicon_Edit/Add_Reference_to_CR_lexical_relation.md)
