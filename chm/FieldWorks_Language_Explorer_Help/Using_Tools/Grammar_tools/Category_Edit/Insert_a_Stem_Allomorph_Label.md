---
title: "Insert a Stem Allomorph Label"
source_title: "Insert a Stem Allomorph Label"
breadcrumb:
  - "Using Tools"
  - "Grammar tools"
  - "Category Edit"
  - "Insert a Stem Allomorph Label"
source: "Using_Tools/Grammar_tools/Category_Edit/Insert_a_Stem_Allomorph_Label.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Grammar_tools/Category_Edit/Insert_a_Stem_Allomorph_Label.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Feature Sets"
  - "Insert Stem Allomorph Label"
  - "Insert:Stem Allomorph Label"
related:
  - "Category Edit overview -> Category_Edit_overview.md"
  - "Choose a Stem Allomorph Label -> ../../Lexicon_tools/Lexicon_Edit/Choose_Stem_Allomorph_Label.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:d5150a4e7927c98d"
---

# Insert a Stem Allomorph Label

*Using Tools › Grammar tools › Category Edit*

Stem Allomorph Labels control stem allomorphy that is dependent not on phonological issues, but on the presence of certain inflection features. Make sure the necessary [inflection features](../Inflection_Features/Inflection_Features_overview.md) are available before you do the steps in this topic.

1.  In the **Navigation Pane**, click **Grammar** and then click **Category Edit**.

2.  In the center column, select the category.

Subcategories will inherit any Stem Allomorph Labels which their parent categories have, so you will probably want to insert the Stem Allomorph Label at the *highest* level category.

3.  In the **Category (or Part of Speech)** pane, click the [Stem Allomorph Labels](../../../User_Interface/Field_Descriptions/Grammar/Category_Edit_fields/Stem_Allomorph_Labels_field.md) field label, and then do one of the following:

    - Click the **Insert Stem Allomorph Label** link that appears.

    - Click the menu button ![](../../../assets/images/Using_Tools/Grammar_tools/Category_Edit/Menu_Button_pic.GIF) that appears, and then select **Insert Stem Allomorph Label**.

      [Stem Allomorph Label](../../../User_Interface/Field_Descriptions/Grammar/Category_Edit_fields/Stem_Allomorph_Label_field.md), [Abbreviation](../../../User_Interface/Field_Descriptions/Grammar/Category_Edit_fields/Abbreviation_field_stem_Allomorph_Label.md), [Description](../../../User_Interface/Field_Descriptions/Grammar/Category_Edit_fields/Description_field_Stem_Allomorph_Label.md) and [Feature Set](../../../User_Interface/Field_Descriptions/Grammar/Category_Edit_fields/Feature_Set_field_Category_Edit.md) fields appear.

4.  Enter a name, abbreviation and description for the Stem Allomorph Label.

5.  In the **Feature Set** field, [choose](Choose_Inflection_features.md) a set of inflection features that are relevant to this Stem Allomorph Label.

6.  If you need more than one Feature Set for this Stem Allomorph Label, [insert a Feature Set](Insert_a_Feature_Set.md) for each one.

> [!IMPORTANT]
>
> - Stem Allomorph Labels may only be used for stem allomorphs, not for affix allomorphs.
>
> - When a particular allomorph of a stem is tagged as belonging to a Stem Allomorph Label, that allomorph is only valid when the word it is in contains certain inflectional features. The main way that the word can have those certain features is if one or more inflectional affixes have those features. (It is also possible for one or more derivational affixes in the word to add inflectional features to the word.)
>
>   A "matching" process happens: when a particular Stem Allomorph Label is used with a given stem allomorph, it means that this allomorph is good only when there are one or more inflectional affixes in the word with at least those inflectional features. (Some or all of the required features can also be from the **To Inflection Features** field of a derivational affix.) Therefore, for *each* feature in *each* Feature Set, make sure there is *at least one* inflectional affix entry with that feature in its **Inflection Features** field (**Lexicon Edit**) *or at least one* derivational affix entry with that feature in its **To Inflectional Features** field. [Choose inflection features](../../Lexicon_tools/Lexicon_Edit/choose_inflection_features.md) as necessary.
>
> - If a computational [parser](../../../User_Interface/Menus/Parser/Parsing_words_overview.md) gives invalid analyses, do the following:
>
> - - Review your affix template tables. Make sure that you have at least one [inflectional template](Insert_an_affix_template.md) defined for each category that uses Stem Allomorph Labels.
>
>   - Review your inflectional features used with Stem Allomorph Labels. Be aware that you need to do three things for valid parses:
>
>   - - [Insert feature sets](Insert_a_Feature_Set.md) for Stem Allomorph Labels.
>
>     - [Choose Stem Allomorph Label](../../Lexicon_tools/Lexicon_Edit/Choose_Stem_Allomorph_Label.md) for stem allomorphs.
>
>     - [Choose inflection features](../../Lexicon_tools/Lexicon_Edit/choose_inflection_features.md) for inflectional affixes.
>
> - **Category Edit overview** has a discussion about category hierarchy.
>
> - For more information and examples, point to **Resources** on the [Help](../../../User_Interface/Menus/Help/Help_overview.md) menu, and then click **Introduction to Parsing**.

## Related topics
[Category Edit overview](Category_Edit_overview.md)

[Choose a Stem Allomorph Label](../../Lexicon_tools/Lexicon_Edit/Choose_Stem_Allomorph_Label.md) (**Lexicon**)
