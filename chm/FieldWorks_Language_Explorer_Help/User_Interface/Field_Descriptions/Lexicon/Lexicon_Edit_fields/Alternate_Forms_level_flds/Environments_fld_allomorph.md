---
title: "Environments field"
source_title: "Environments field"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Lexicon"
  - "Lexicon Edit fields"
  - "Allomorphs level fields"
  - "Environments field"
source: "User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Environments_fld_allomorph.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Environments_fld_allomorph.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Environment:Environments field (Allomorph)"
  - "Environment:Logic of"
  - "Logic of Environments"
related:
  - "Allomorphs-level fields overview -> Alt_Forms_lev_flds_ov.md"
  - "Lexicon Edit overview -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:baed31e7ddc40028"
---

# Environments field

*User Interface › Field Descriptions › Lexicon › Lexicon Edit fields › Allomorphs level fields*

**Full name:** **Environments**

**Abbreviation:** **in**

**Location:**

In the **Entry** pane (**Lexicon Edit**).

This field is at the [Allomorphs level](Alt_Forms_lev_flds_ov.md) for each allomorph.

(A separate **Environments** field is between the **Lexeme Form** [field](../Entry_level_fields/Lexeme_Form_field.md) and the **Sense 1** [field](../Sense_level_fields/Sense_field.md). It refers to the lexeme form, not the entire entry.)

**Description:**

This field references and displays [environments](../../../../../Using_Tools/Grammar_tools/Environments/Environments_overview.md) (phonological constraints) that are specific to the stem allomorph or affix allomorph associated with the particular **Environments** field.

[Parsers](../../../../Menus/Parser/Parsing_words_overview.md) use environments.

A given allomorph may have *more* than one environment, in which case the various environments are logically *OR*ed with each other. That is, if any one of the environments for the allomorph are found, then the allomorph is considered to be valid (as far as its environments are concerned). For example, if a given allomorph can appear either before a consonant or word finally, then you can list both an environment for “before a consonant” and one for “before a word boundary.” A light gray vertical bar separates the *OR*ed environments in this field.

**Tasks:**

- [Choose environments](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_environments.md) (**Lexicon Edit**)

  - [Insert an environment](../../../../../Using_Tools/Grammar_tools/Environments/Insert_an_environment.md) (**Grammar**)

  - Type or construct an environment in **Lexicon Edit** (see below)

- [View problems with environments](../../../../../Using_Tools/Grammar_tools/Problems/View_Problems_with_Environments.md)

- You can [configure the dictionary](../../../../Menus/Tools/Configure_Dictionary/Configure_Dictionary.md) to include the allomorph environments when you configure [Allomorphs](../../../../Menus/Tools/Configure_Dictionary/alternate_forms.md).

**Field type:** [List reference field](../../../Field_Types/List_reference_field.md). However, you may type in this field to enter an existing environment or to create a new environment.

**Writing systems:**

One or more [analysis](../../../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md) *or* vernacular.

When you click an **Environments** field, FieldWorks selects the default vernacular writing system. If the font used with your *default* *vernacular* writing system supports `/`, `_`, `[` and `]` (and other characters needed for proper syntax), you can enter environments using that vernacular writing system. If not, you can mix writing systems using, for example, the default analysis for all but the phoneme.

**Examples:**

- The environment `/_[V]` (where there is a natural class of vowels with the abbreviation of `V`) may only use the default *analysis* writing system.

- The environment `/_m` (where `m` is a discrete phoneme) may use either the *analysis* or *vernacular* writing system for the `m` phoneme, and the *analysis* for `/_`.

  You can use the **Format** [menu](../../../../Menus/Format/select_a_writing_system.md) or [toolbar](../../../../Toolbars/Format_toolbar.md) to specify the writing system for individual components in an environment.

If you use writing systems *other than* the *default* analysis or *default* vernacular, environments may appear correctly and facilitate correct parsing, but may *not* appear correctly in the grammar sketch.

**Type or Construct an Environment:**

You can type the components of the environment directly in the field *or* do the following steps to construct it using menu commands (recommended for non-roman writing systems, *especially* right-to-left writing systems):

1.  Click the **Environment** field, and then click the menu button ![](../../../../../assets/images/User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Menu_Button_pic.GIF) to display the menu.

2.  On the menu, click the **Insert** **\<component\>** command for the component you need, such as the **Insert Environment slash**.

3.  Repeat steps 1 and 2 for each component until the environment is complete.

4.  [Edit the environment](../../../../../Using_Tools/Grammar_tools/Environments/Edit_an_Environment.md) to add a name and description.

**Tip:**

- If the environment in this field has a red wavy underline, the environment has a [problem](../../../../../Using_Tools/Grammar_tools/Problems/View_Problems_with_Environments.md) and *cannot* be used by the [parsers](../../../../Menus/Parser/Parsing_words_overview.md).

- When you [insert an allomorph](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Insert_an_alternate_form.md), these fields appear: [Affix Allomorph](Affix_allomorph_fld.md) or [Stem Allomorph](Stem_Allomorph_fld.md), [Is Abstract Form](Is_Abstract_Form_fld_Allomorph.md), [Morph Type](Morph_type_fld_allomorph.md) and **Environments**. For stem allomorphs, the [Stem Allomorph Label](Stem_Allomorph_Label_fld_Allomorph.md) field also appears.

- For more information, on the [Help](../../../../Menus/Help/Help_overview.md) menu point to **Resources**, and then click **Introduction to Parsing**.

## Related topics
[Allomorphs-level fields overview](Alt_Forms_lev_flds_ov.md)

[Lexicon Edit overview](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md)
