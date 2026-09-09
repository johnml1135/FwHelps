---
title: "Delete Grammatical Info"
source_title: "Delete Grammatical Info"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Lexicon Edit"
  - "Delete Grammatical Info"
source: "Using_Tools/Lexicon_tools/Lexicon_Edit/Delete_grammatical_info.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Lexicon_Edit/Delete_grammatical_info.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Delete:Grammatical Info."
  - "Delete Grammatical Info"
  - "Grammatical Information:Delete Grammatical Info"
related:
  - "Affix Slots field -> ../../../User_Interface/Field_Descriptions/Grammar/Category_Edit_fields/Affix_Slots_field_Category_Edit.md"
  - "Grammatical Info Details fields overview -> ../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Grammatical_Info_Details_fields/Gram_Info_Detls_fields_ovw.md"
  - "Lexicon Edit overview -> lexicon_edit_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:97a5805e905dcbe0"
---

# Delete Grammatical Info

*Using Tools › Lexicon tools › Lexicon Edit*

Typically, you *cannot* manually delete grammatical information from some fields below the **Grammatical Info Details** field. Unused grammatical information is *automatically* removed.

For example, grammatical information is removed from the **Category Info** field when you [delete a sense or subsense](delete_a_sense_or_subsense.md), if that grammatical information is *not* used

- by another sense or subsense, *or*

- in any [interlinearized text](../../Texts_&_Words_tools/Interlinear_Texts/Analyze_Text_overview.md).

However, if you see grammatical information that you think is unused and should be deleted, try the following:

1.  [Insert a sense](Insert_a_sense_or_subsense_in_an_entry.md) (new, temporary) and [choose](change_the_grammatical_info.md) the grammatical information you want to delete.

2.  Delete this newly created sense.

If the information you wanted to delete is still there, then it is still being used somewhere.

Here are possible places it is being used:

- Some *sense* in the entry refers to it.

- Some *analysis* of at least one word refers to it.\
  This could be from either you manually interlinearizing a text where your analysis included this item, *or* maybe you ran a computational [parser](../../../User_Interface/Menus/Parser/Parsing_words_overview.md) on the word(s) and the parser suggested this item as part of the analysis.

  - If it might be the former, try this: Right-click the [Sense](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Sense_field.md) field associated with the grammatical information and choose **Show Sense in Concordance**. In [Concordance](../../Texts_%26_Words_tools/Concordance/Concordance_overview.md), examine the results in the **Analyze** tab.

  - If it might be the latter, try this: On the **Tools** menu, click **Utilities**. Then, run **Remove Parser approved analyses**.

- A *morpheme-oriented ad hoc rule* refers to this information. Delete that ad hoc rule if it is not needed.

- Some *inflection template slot* refers to it. Review the associated template table.

After you think all references to the item you want to delete are gone, do the first two steps above again.

The ![](../../../assets/images/Important_Icon.gif) **Important** section of [Category Info](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Grammatical_Info_Details_fields/Category_Info_field.md) field has more information about how fields work together.

## Related topics
[Affix Slots field](../../../User_Interface/Field_Descriptions/Grammar/Category_Edit_fields/Affix_Slots_field_Category_Edit.md)

[Grammatical Info Details fields overview](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Grammatical_Info_Details_fields/Gram_Info_Detls_fields_ovw.md)

[Lexicon Edit overview](lexicon_edit_overview.md)
