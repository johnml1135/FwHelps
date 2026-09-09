---
title: "Choose environments"
source_title: "Choose environments"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Lexicon Edit"
  - "Choose environments"
source: "Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_environments.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_environments.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Environment"
  - "Environment:Logic of"
  - "Environments"
  - "Choose (See also: Select or Specify):Environments (Lexicon)"
  - "Logic of Environments"
related:
  - "Lexicon Edit fields overview -> ../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Lexicon_Edit_fields_overview.md"
  - "Lexicon Edit overview -> lexicon_edit_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:6b1eee2cb607c9a6"
---

# Choose environments

*Using Tools › Lexicon tools › Lexicon Edit*

You can choose existing environments or type a new environment directly in an **Environment** field. *Alternatively*, you can choose individual environment components from the menu button (![](../../../assets/images/Using_Tools/Lexicon_tools/Lexicon_Edit/Menu_Button_pic.GIF)) list to construct a new environment directly in an **Environments** field.

1.  In the **Navigation** **Pane**, click **Lexicon**, and then click **Lexicon Edit**.

2.  In the **Entries** column, click the desired entry.

3.  In the **Entry** pane, if you cannot see the **Environments** field, [show hidden fields](../../../Basic_Tasks/Showing_and_hiding_fields/Show_Hidden_Fields.md).

4.  Click one of these fields, and then continue:

    - [Environments](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Environments_field.md), which is located below the **Lexeme Form** field ([entry level](About_Lex_Edit_fld_levels.md))

    - [Environments](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Environments_fld_allomorph.md), for the applicable stem or affix allomorph below the **Allomorphs** field

    A menu button (![](../../../assets/images/Using_Tools/Lexicon_tools/Lexicon_Edit/Menu_Button_pic.GIF)) and an ellipsis button ![](../../../assets/images/Ellipsis_button.PNG) appear at the ends of the field.

5.  Do one of the following:

    - Click the ellipsis button to open the **Choose Environments** dialog box. Select one or more environments, and then click **OK**.

      If the desired environment is not listed, click the **Edit the Environments** link so you can [insert an environment](../../Grammar_tools/Environments/Insert_an_environment.md).

    - Type a new environment directly in the **Environments** field.

    - Click the menu button that appears (recommended for non-roman right-to-left writing systems). Click a component of an environment, such as an environment slash **/** or environment bar **\_**. Repeat this step for each component or type a phoneme or other item as needed to complete the environment.

6.  Click any other field to "leave" the **Environments field**. If a red wavy underline appears below the environment, the environment has a problem. If you cannot determine and solve the problem, refer to the [Problems](../../Grammar_tools/Problems/View_Problems_with_Environments.md) area.

> [!IMPORTANT]
>
> - [Parsers](../../../User_Interface/Menus/Parser/Parsing_words_overview.md) use environments, however, problematic environments cannot be used.
>
> - You can have more than one environment in an **Environments** field. In this case, an "*OR*" logic is used (if any one of the environments for the lexeme are found, then the lexeme is considered to be valid, as far as its environments are concerned). A light gray vertical bar separates them. If you will choose a second or subsequent environment, move the insertion point to the right of the gray vertical bar. You can click there or use the `Right Arrow` key. Then, repeat the applicable steps above.

> [!TIP]
>
> - Refer to [Environment String Representations](../../Grammar_tools/Environments/Environment_String_Rep_examples.md) for string representation syntax examples.
>
> - In addition, you can point to **Resources** on the [Help](../../../User_Interface/Menus/Help/Help_overview.md) menu, and then click **Introduction to Parsing** for more information.
>
> - If you type or construct a *new* environment, you will need to add its name and description in the [Grammar](../../Grammar_tools/Environments/Environments_overview.md) area.

## Related topics
[Lexicon Edit fields overview](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Lexicon_Edit_fields_overview.md)

[Lexicon Edit overview](lexicon_edit_overview.md)
