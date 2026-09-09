---
title: "Insert an environment"
source_title: "Insert an environment"
breadcrumb:
  - "Using Tools"
  - "Grammar tools"
  - "Environments"
  - "Insert an Environment"
source: "Using_Tools/Grammar_tools/Environments/Insert_an_environment.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Grammar_tools/Environments/Insert_an_environment.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Insert:Environment"
  - "Environment"
related:
  - "Edit an environment -> Edit_an_Environment.md"
  - "Environment overview -> Environments_overview.md"
  - "Non-base characters as graphemes -> ../Phonemes/Non_Base_Characters_as_Graphemes.md"
  - "View problems with environments -> ../Problems/View_Problems_with_Environments.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:03bc8459a9d110dc"
---

# Insert an environment

*Using Tools › Grammar tools › Environments*

You can type or construct an environment directly in an **Environment** field in [Lexicon Edit](../../Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md). It is added to the language project as if you inserted it **Environments**. However in this case, you *should* then return and [Edit the environment](Edit_an_Environment.md), such as to add a name and description.

To insert an environment in **Environments** ([Grammar](../grammar_overview.md)), do the following steps.

1.  In the **Navigation Pane**, click **Grammar**, and then click **Environments**.

2.  Do one of the following:

    - On the [Insert](../../../User_Interface/Toolbars/Insert_toolbar.md) toolbar, click ![](../../../assets/images/Using_Tools/Grammar_tools/Environments/Create_Environment_Grammar.GIF).

    - On the **Insert** menu, click **Environment**.

    - Press the [shortcut key](../../../User_Interface/Shortcuts/shortcut_keys_Grammar_tools.md) `Ctrl+I`.

    A new environment is added. In the **String Representation** field, **/\_** appears for left-to-right writing system or **\_/** appears for right-to-left writing systems.

3.  Enter a name and description for the environment.

4.  Click the **String Representation** field, and then do *one* of the following:

    - Recommended for non-roman writing systems, especially those which are right-to-left:\
      Click the menu button ![](../../../assets/images/Using_Tools/Lexicon_tools/Lexicon_Edit/Menu_Button_pic.GIF) that appears, and then click a command, such as **Insert Natural Class**, to insert a component of an environment. Repeat this step for each component. If you select **Insert Natural Class**, select a natural class from the dialog box, and then click **OK**. Otherwise, type a phoneme or other component as needed to complete the environment.

    - Enter the string representation by simply typing it with your keyboard.

5.  Leave the **String Representation** field by clicking another field, such as the **Name** field.

    If a red underline appears below the environment in the **String Representation** field, there is a problem with that environment. To determine the problem, right-click the environment and the select **Describe Error in Environment**. (Alternatively, go to [Problems](../Problems/Problems_overview.md).) Then correct the problem.

    Environments with a problem are *not* available for use, such as in the **Choose Environments** dialog box.

> [!IMPORTANT]
>
> - “`/`” (forward slash) must begin each environment.
>
> - “`_`” (underscore character) represents the location of the form (lexeme *or* allomorph) itself.
>
> - An environment may use a [natural class](../Natural_Classes/Natural_classes_overview.md) or it may use any grapheme of any [phoneme](../Phonemes/Phonemes_overview.md).
>
>   “`[ ]`” (square brackets) are *required* in environments that use a natural class, but are *not* used in environments that use a grapheme of a phoneme. Examples:
>
>   - `/_[V]` *must* have a *natural class* with the [abbreviation](../../../User_Interface/Field_Descriptions/Grammar/Natural_Classes_fields/Abbreviation_field_Natural_Classes.md) “`V`”.
>
>   - `/m_` uses the `m` [grapheme](../../../User_Interface/Field_Descriptions/Grammar/Phonemes_fields/representation_field_phonemes.md) of some *phoneme*.
>
> - “`( )`” (parenthesis) indicate *optional* phonemes or natural classes.
>
> - “`#`” (pound sign) is a predefined word boundary marker.
>
> - If the font associated with your vernacular writing system does *not* include the syntactic elements you need for the environment, specifically `/`, `_`, `[`, `]`, `(`, `)`, and `#`, they may appear as square boxes.
>
>   In this case, you can select each character that does not appear correctly and [change the writing system](../../../User_Interface/Toolbars/Format_toolbar.md) to an analysis writing system that includes that syntactic element. [Parsers](../../../User_Interface/Menus/Parser/Parsing_words_overview.md) accept environments with multiple writing systems.
>
> - Language Explorer does *not* allow the use of the “`~`” (tilde). Therefore, you *cannot* negate an environment, such as “`/~_ [V]`” (intended to mean “not before a vowel”).

> [!TIP]
>
> - Refer to [Environment String Representations](Environment_String_Rep_examples.md) for string representation syntax examples.
>
>   In addition, you can point to **Resources** on the [Help](../../../User_Interface/Menus/Help/Help_overview.md) menu, and then click **Introduction to Parsing** for more information. See **Allomorph Environments**.

## Related topics
[Edit an environment](Edit_an_Environment.md)

[Environment overview](Environments_overview.md)

[Non-base characters as graphemes](../Phonemes/Non_Base_Characters_as_Graphemes.md)

[View problems with environments](../Problems/View_Problems_with_Environments.md)
