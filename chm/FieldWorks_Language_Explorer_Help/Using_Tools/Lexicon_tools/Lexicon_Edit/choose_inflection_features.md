---
title: "Choose inflection features"
source_title: "Choose inflection features"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Lexicon Edit"
  - "Choose inflection features"
source: "Using_Tools/Lexicon_tools/Lexicon_Edit/choose_inflection_features.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Lexicon_Edit/choose_inflection_features.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Choose (See also: Select or Specify):Inflection features (Lexicon)"
  - "Inflection Features"
  - "Inflection Features:Choose inflection features"
  - "Features"
  - "Inflection"
  - "Add:Inflection Features"
related:
  - "About Inflection Features and Feature Types -> ../../Grammar_tools/Inflection_Features/About_Infl_Features_and_Types.md"
  - "Inflection Features overview -> ../../Grammar_tools/Inflection_Features/Inflection_Features_overview.md"
  - "Grammatical Info Details fields overview -> ../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Grammatical_Info_Details_fields/Gram_Info_Detls_fields_ovw.md"
  - "Lexicon Edit overview -> lexicon_edit_overview.md"
  - "Lexicon Edit fields overview -> ../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Lexicon_Edit_fields_overview.md"
  - "Parsing words overview -> ../../../User_Interface/Menus/Parser/Parsing_words_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:fa1998fbae8067b7"
---

# Choose inflection features

*Using Tools › Lexicon tools › Lexicon Edit*

- A [Required Features](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/required_features_lex.md) field appears at the [entry level](About_Lex_Edit_fld_levels.md) for an affix entry.

- A different [Required Features](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/required_features.md) field appears below the **Allomorphs** field for affix allomorphs.

- Below **Grammatical Info Details**, different variations of the **Inflection Features** [fields](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Grammatical_Info_Details_fields/Gram_Info_Detls_fields_ovw.md) can appear. For example, a derivational affix may use **From** **Inflection** **Features** and **To** **Inflection** **Features** fields, but a stem may use only one **Inflection Features** field.

- For a Feature Set in a Stem Allomorph Labels, see [Choose Inflection Features for Stem Allomorph Labels](../../Grammar_tools/Category_Edit/Choose_Inflection_features.md).

- If you will change infection features in **Bulk Edit Entries** [view](../Bulk_Edit_Entries/Bulk_Edit_Entries_overview.md), see: [Bulk change Inflection Features](../Bulk_Edit_Entries/Bulk_change_inflect_features.md).

To choose inflection features in **Lexicon Edit**, do these steps:

1.  In the **Navigation** **Pane**, click **Lexicon**, and then click **Lexicon Edit**. thweIn the **Entries** pane, click the desired entry.

2.  In the **Entry** pane, if you cannot see the desired field, [show hidden fields](../../../Basic_Tasks/Showing_and_hiding_fields/Show_Hidden_Fields.md).

3.  Click the field, and then click the ellipsis button ![](../../../assets/images/Ellipsis_button.PNG) that appears.

    The **Choose Inflection Features** dialog box appears.

4.  Do *one* of the following:

    - Select (![](../../../assets/images/SelectedRadioButton.png)) what you want to use. (Cleared (![](../../../assets/images/ClearedRadioButton.png)) items are not used.) Click **OK**.

    - Select (![](../../../assets/images/SelectedRadioButton.png)) **None of the above** to clear any selection for an inflection feature, and remove it from the field, if it is already used. Click **OK**.

    - Click the link "**The inflection feature I need is not shown here. Add inflection features to** **\<**category**\>.**"

This link changes the view to [Category Edit](../../Grammar_tools/Category_Edit/Category_Edit_overview.md) so you can [choose](../../Grammar_tools/Category_Edit/Choose_inflectable_features.md) previously defined inflection features (for the **Inflectable Features** field) or to [insert a new feature or complex feature](../../Grammar_tools/Inflection_Features/Insert_a_Feature_or_Complex_Feature.md) for the category.

The link is *unavailable* if the **Grammatical Info** field has no category.

6.  If the lexical entry has another field, such as a **To** **Inflection** **Feature** field paired with a **From** **Inflection Features** field, repeat the above steps for that field.

> [!IMPORTANT]
>
> - If you choose an inflection feature to condition an affix allomorph, the lexeme form and all other allomorphs without a similar required feature are automatically conditioned to *not* occur when that feature is present. So, in some cases you may be able to leave the lexeme form without any "required features."
>
> - - For a more complete discussion about the **Required Features** fields, point to **Resources** on the [Help](../../../User_Interface/Menus/Help/Help_overview.md) menu, and then click **Introduction to Parsing**. Section 3.8 discusses affix allomorphs conditioned by features.
>
> - It is *strongly recommended* that you [contact](../../../Overview/Technical_support.md) a FLEx consultant before you overtly add or edit features or feature types. If these are not handled correctly, the parser may not correctly analyze many of your word forms.

## Related topics
[About Inflection Features and Feature Types](../../Grammar_tools/Inflection_Features/About_Infl_Features_and_Types.md)

[Inflection Features overview](../../Grammar_tools/Inflection_Features/Inflection_Features_overview.md)

[Grammatical Info Details fields overview](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Grammatical_Info_Details_fields/Gram_Info_Detls_fields_ovw.md)

[Lexicon Edit overview](lexicon_edit_overview.md)

[Lexicon Edit fields overview](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Lexicon_Edit_fields_overview.md)

[Parsing words overview](../../../User_Interface/Menus/Parser/Parsing_words_overview.md)
