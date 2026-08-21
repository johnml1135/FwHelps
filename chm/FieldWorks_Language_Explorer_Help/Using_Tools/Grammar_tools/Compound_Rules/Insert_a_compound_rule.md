---
title: "Insert a compound rule"
source_title: "Insert a compound rule"
breadcrumb:
  - "Using Tools"
  - "Grammar tools"
  - "Compound Rules"
  - "Insert a compound rule"
source: "Using_Tools/Grammar_tools/Compound_Rules/Insert_a_compound_rule.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Grammar_tools/Compound_Rules/Insert_a_compound_rule.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Insert:Compound rule"
  - "Compound Rule"
  - "Category"
related:
  - "Compound Rules overview -> Compound_Rules_overview.md"
  - "Insert a category -> ../Category_Edit/Insert_a_Category.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:47df2ab669cfe076"
---

# Insert a compound rule

*Using Tools › Grammar tools › Compound Rules*

> [!WARNING]
>
> - Once you define your *first* compound rule, the [parser](../../../User_Interface/Menus/Parser/Parsing_words_overview.md) will then *only* allow compounds for which there are rules. In particular, this means that you may have a number of word forms that will suddenly fail to analyze once you write your first compound rule. To get them to analyze, you will need to define appropriate compound rules for them. You can still break the words with compounds by hand in the [Gloss](../../Texts_%26_Words_tools/Interlinear_Texts/specify_the_word_gloss.md) or [Analyze](../../Texts_&_Words_tools/Interlinear_Texts/Analyze_Text_overview.md) tabs.
>
> - **See Also:** [Active field](../../../User_Interface/Field_Descriptions/Grammar/Compound_Rules_fields/Active_field_Compound_Rules.md).
>
> If you need to define a compound rule, do the following steps:
>
> 1.  In the **Navigation** **Pane**, click **Grammar**, and then click **Compound Rules**.
>
> 2.  Do one of the following:
>
>     - On the [Insert](../../../User_Interface/Toolbars/Insert_toolbar.md) toolbar, click ![](../../../assets/images/Using_Tools/Grammar_tools/Compound_Rules/Create_HeadedCompoundRule_Grammar.GIF) (*headed compound*) or ![](../../../assets/images/Using_Tools/Grammar_tools/Compound_Rules/Create_Non_HeadedCompoundRule_Grammar.GIF) (*non-headed compound*).
>
>     - On the **Insert** menu, click **Headed Compound**, or click **Non-headed Compound**.
>
>     A new compound rule is inserted, with empty fields.
>
> 3.  Enter a name and description for the new compound rule.
>
> 4.  In the **Left Member** **Category** field, select a category. If the needed category is not available, click **More** to open the [Add from Catalog](../../Lexicon_tools/Lexicon_Edit/Using_Add_from_Catalog_dialog_box.md) dialog box.
>
> 5.  Repeat step 4 for the **Right Member Category** field.
>
> 6.  For *non-headed* compound rules, do the following:
>
>     - In the **Result Category** field, select a category. If the needed category is not available, click **More** to open the **Add from Catalog** dialog box.
>
>     - If your language uses inflection classes, click the **Inflection Class** field, and then click the ellipsis button ![](../../../assets/images/Ellipsis_button.PNG) that appears to open the **Choose Inflection Class** dialog box. Choose an inflection class, and then click **OK**.
>
>       If the needed inflection class is *not* listed, click **Edit the Inflection Classes** link so you can [insert an inflection class](../Category_Edit/Insert_an_Inflection_Class.md). Then, click the **Back** button on the [Standard](../../../User_Interface/Toolbars/Standard_toolbar.md) toolbar to return to the new compound rule and choose the inflection class.
>
> 7.  For *headed* compound rules, do one of the following:
>
>     - If the rule is *right* headed, select the **Right Headed** check box.
>
>     - If the rule is *left* headed, clear the **Right Headed** check box.
>
> 8.  For *headed* compound rules, repeat step 4 for the **Override Head with: Category** field, if necessary.
>
>     For more information, point to **Resources** on the [Help](../../../User_Interface/Menus/Help/Help_overview.md) menu, and then click **Introduction to Parsing**. See the sections **Incorporation as a Headed Compound with Override** and **Other Considerations**.

## Related topics
[Compound Rules overview](Compound_Rules_overview.md)

[Insert a category](../Category_Edit/Insert_a_Category.md)
