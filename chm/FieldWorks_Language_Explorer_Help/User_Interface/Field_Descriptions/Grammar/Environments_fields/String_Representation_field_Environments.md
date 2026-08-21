---
title: "String Representation field (Environments)"
source_title: "String Representation field (Environments)"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Grammar"
  - "Environments fields"
  - "String Representation field (Environments)"
source: "User_Interface/Field_Descriptions/Grammar/Environments_fields/String_Representation_field_Environments.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Grammar/Environments_fields/String_Representation_field_Environments.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Grapheme"
related:
  - "Environments fields overview -> Environments_fields_overview.md"
  - "Environment String Representation examples -> ../../../../Using_Tools/Grammar_tools/Environments/Environment_String_Rep_examples.md"
  - "Grammar Sketch -> ../../../../Using_Tools/Grammar_tools/Grammar_Sketch/Grammar_Sketch_overview.md"
  - "Problems -> ../../../../Using_Tools/Grammar_tools/Problems/Problems_overview.md"
fw_help_version: "9.3"
page_heading: "String Representation field"
type: "topic"
content_hash: "sha256:b47d2b711a9625d4"
---

# String Representation field (Environments)

*User Interface › Field Descriptions › Grammar › Environments fields*

**Full name:** **String Representation**

**Location:** The **String Representation** field is in the **Environment** pane of **Environments** ([Grammar](../../../../Using_Tools/Grammar_tools/grammar_overview.md))

**Description:**

This field stores the actual environment, which may include the [abbreviation](../Natural_Classes_fields/Abbreviation_field_Natural_Classes.md) from a [natural class](../../../../Using_Tools/Grammar_tools/Natural_Classes/Natural_classes_overview.md), or a discrete [phoneme](../Phonemes_fields/Phonemes_fields_overview.md).

It appears in various dialog boxes and fields, such as the [Environments field](../../Lexicon/Lexicon_Edit_fields/Entry_level_fields/Environments_field.md) (**Lexicon Edit**). [Parsers](../../../Menus/Parser/Parsing_words_overview.md) use these environment string representations.

**Tasks:**

- [Delete an environment](../../../../Using_Tools/Grammar_tools/Environments/Delete_an_Environment.md)

- [Edit an environment](../../../../Using_Tools/Grammar_tools/Environments/Edit_an_Environment.md)

- [Insert an environment](../../../../Using_Tools/Grammar_tools/Environments/Insert_an_environment.md)

- [View problems with environments](../../../../Using_Tools/Grammar_tools/Problems/View_Problems_with_Environments.md)

  - If the environment in this field has a red underline (such as ![](../../../../assets/images/User_Interface/Field_Descriptions/Grammar/Environments_fields/RedUnderlinedEnv.GIF)), the environment has a [problem](../../../../Using_Tools/Grammar_tools/Problems/View_Problems_with_Environments.md) (has ill-formed syntax). Right-click the problematic environment, and then select **Describe Error in Environment** to see a brief description of the problem.

- **See** **also****:** [Environments overview](../../../../Using_Tools/Grammar_tools/Environments/Environments_overview.md)

**Field type:** Text field

**Writing systems:**

One or more [analysis](../../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md) *or* vernacular.

When you click an **Environments** field, FieldWorks selects the default vernacular writing system. If the font used with your *default* *vernacular* writing system supports `/`, `_`, `[` and `]` (and other characters needed for proper syntax), you can enter environments using that vernacular writing system. If not, you can mix writing systems using, for example, the default analysis for all but the phoneme.

**Examples:**

- The environment `/_[V]` (where there is a natural class of vowels with the abbreviation of `V`) may only use the default *analysis* writing system.

- The environment `/_m` (where `m` is a discrete phoneme) may use either the *analysis* or *vernacular* writing system for the `m` phoneme, and the *analysis* for `/_`.

  You can use the **Format** [menu](../../../Menus/Format/select_a_writing_system.md) or [toolbar](../../../Toolbars/Format_toolbar.md) to specify the writing system for individual components in an environment.

If you use writing systems *other than* the *default* analysis or *default* vernacular, environments may appear correctly and facilitate correct parsing, but may *not* appear correctly in the grammar sketch.

**Type or Construct an Environment:**

You can type the components of the environment directly in the field *or* do the following steps to construct it using menu commands (recommended for non-roman writing systems, *especially* right-to-left writing systems):

1.  Click the **Environment** field, and then click the menu button ![](../../../../assets/images/User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Menu_Button_pic.GIF) to display the menu.

2.  On the menu, click the **Insert** **\<component\>** command for the component you need, such as the **Insert Environment slash**.

3.  Repeat steps 1 and 2 for each component until the environment is complete.

4.  [Edit the environment](../../../../Using_Tools/Grammar_tools/Environments/Edit_an_Environment.md) to add a name and description.

**Grammar Sketch:** Under **Allomorphy**

**Tip:** For additional information about environments, point to **Resources** on the [Help](../../../Menus/Help/Help_overview.md) menu, and then click **Introduction to Parsing**.

## Related topics
[Environments fields overview](Environments_fields_overview.md)

[Environment String Representation examples](../../../../Using_Tools/Grammar_tools/Environments/Environment_String_Rep_examples.md)

[Grammar Sketch](../../../../Using_Tools/Grammar_tools/Grammar_Sketch/Grammar_Sketch_overview.md)

[Problems](../../../../Using_Tools/Grammar_tools/Problems/Problems_overview.md)
