---
title: "Attaches to Categories field"
source_title: "Attaches to Categories field"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Lexicon"
  - "Lexicon Edit fields"
  - "Grammatical Info Details fields"
  - "Attaches to Category field"
source: "User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Grammatical_Info_Details_fields/attaches_to_categories_field.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Grammatical_Info_Details_fields/attaches_to_categories_field.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Enclitic/Proclitic"
  - "attach to"
  - "Attaches to Category field"
  - "Clitics"
  - "Proclitic/Enclitic"
  - "attach to:Attaches to Categories field"
related:
  - "Grammatical Info Details fields overview -> Gram_Info_Detls_fields_ovw.md"
  - "Grammar overview -> ../../../../../Using_Tools/Grammar_tools/grammar_overview.md"
  - "Lexicon Edit overview -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md"
  - "Lexicon Edit fields overview -> ../Lexicon_Edit_fields_overview.md"
  - "Show Hidden Fields -> ../../../../../Basic_Tasks/Showing_and_hiding_fields/Show_Hidden_Fields.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:09b339659e6b47c3"
---

# Attaches to Categories field

*User Interface › Field Descriptions › Lexicon › Lexicon Edit fields › Grammatical Info Details fields*

**Full name:** **Attaches to** **Categories**

**Location:**

In the **Entry** pane (**Lexicon Edit**).

This field is at the [Grammatical Info Details level](Gram_Info_Detls_fields_ovw.md).

It appears in lexical entries set to **enclitic** or **proclitic** in the **Morph Type** [field](../Entry_level_fields/Morph_Type_Field.md) at the entry level *or* in the **Morph Type** [field](../Alternate_Forms_level_flds/Morph_type_fld_allomorph.md) for one or more of its allomorphs.

**Description:**

In this field, you choose one or more categories (or parts of speech) to which the enclitic or proclitic described in the lexical entry may attach, if it attaches to a form (host).

The form, gloss, grammatical category of the lexical entry and the **Attaches to Categories** field content appear in the [Grammar Sketch](../../../../../Using_Tools/Grammar_tools/Grammar_Sketch/Grammar_Sketch_overview.md) under **Clitics**.

Categories stored in this field are used by the [parsers](../../../../Menus/Parser/Parsing_words_overview.md).

**Tasks:**

- [Choose categories](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_categories.md)

**Field type:** [List reference field](../../../Field_Types/List_reference_field.md)

**Writing systems:** Best [analysis](../../../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md)

**Example:**

`The queen of England`’`s hat was` `enormous``.`

`The guy who lost’s expression was` `so` `funny``.`

`That man over there’s brother bought my car.`

The possessive **’s** enclitic indicates ownership by the 1) **queen of** **England**, so you would choose *proper noun* (or maybe just *noun*), 2) **guy who lost**, so you could choose *verb*, and 3) **that man over there****’s brother**, so you would choose *adverb*.

**:**

Consider these sentences:

\[\[The queen of England\]'s hat\] was enormous. (proper noun)

\[\[The guy who lost\]'s expression\] was so funny. (verb)

\[\[That man over there\]'s brother\] bought my car. (adverb)

\[\[The book\]'s cover\] was red. (noun)

\[\[The guy who ran so slowly\]'s shoes\] looked like lead weights. (adverb)

\[\[The last one to turn in\]'s duty\] was to turn off the light. (preposition)

\[\[The guy who shot him\]'s weapon\] was on the doorstep. (pronoun)

So, while there are other categories that could be selected besides the three used in **Example** above, you would *not* want to choose *every* category. For example, the possessive enclitic would *not* go on an article or conjunction. “The’s book cover is blue.” and “The blue and’s green book was good.” are *not* correct.

**Tip:** For more information, on the [Help](../../../../Menus/Help/Help_overview.md) menu point to **Resources**, and then click **Introduction to Parsing**.

## Related topics
[Grammatical Info Details fields overview](Gram_Info_Detls_fields_ovw.md)

[Grammar overview](../../../../../Using_Tools/Grammar_tools/grammar_overview.md)

[Lexicon Edit overview](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md)

[Lexicon Edit fields overview](../Lexicon_Edit_fields_overview.md)

[Show Hidden Fields](../../../../../Basic_Tasks/Showing_and_hiding_fields/Show_Hidden_Fields.md)
