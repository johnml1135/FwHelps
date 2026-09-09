---
title: "About Reference set types"
source_title: "About Reference set types"
breadcrumb:
  - "Using Tools"
  - "Lists tools"
  - "About Reference set types"
source: "Using_Tools/Lists_tools/About_reference_set_types.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lists_tools/About_reference_set_types.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Sequence"
  - "lexical relation:About reference set types"
  - "Types"
  - "Types:About Mapping Types"
  - "About:Reference set types"
  - "Synonym"
  - "Antonym"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:54da36e62c86e035"
---

# About Reference set types

*Using Tools › Lists tools*

When you [create](Create_new_Lexical_Relations.md) a [lexical relation](About_Lexical_Relations.md) you select a type in the [Reference set type](../../User_Interface/Field_Descriptions/Lists/Lexical_Relations_fields/reference_set_type_field.md) field. The available types are the following:

|  |  |  |  |
|----|----|----|----|
| Type | Relationship is among | Use in Field labeled | Example |
| Sense collection - one name | Multiple sense-level members | **Lexical Relations\*** | [Synonym](Set_Type_example_sense_collection.md) |
| Entry collection – one name | Multiple entry-level members | **Cross References\*\*** | [Compare](Set_Type_example_entry_collection.md) |
| Entry or sense collection – one name | Multiple entry- or sense-level members | **Cross References or Lexical Relations \*\*\*** | -- |
|  |  |  |  |
| Sense pair – one name | Two sense-level members | **Lexical Relations** | [Antonym](set_type_example_sense_pair.md) |
| Entry pair – one name | Two entry-level members | **Cross References** | -- |
| Entry or sense pair – one name | Two entry- or sense- level members | **Cross References or Lexical Relations** | -- |
|  |  |  |  |
| Sense pair – two names | Two sense-level members | **Lexical Relations** | [Operator/Vehicle](set_type_example_sense_pair.md) |
| Entry pair – two names | Two entry-level members | **Lexical Relations** | -- |
| Entry or sense pair – two names | Two entry- or sense-level members | **Cross References or Lexical Relations** | -- |
|  |  |  |  |
| Sense sequence/scale – one name | Multiple sense-level members, where sequence or order is emphasis | **Lexical Relations** | -- |
| Entry sequence/scale – one name | Multiple entry-level members, where sequence or order is emphasis | **Cross References** | [Days of Week](Set_Type_example_entry_sequence_scale.md) |
| Entry or sense sequence/scale – one name | Multiple entry- or sense-level members, where sequence or order is emphasis | **Cross References or Lexical Relations** | -- |
|  |  |  |  |
| Sense tree – two names | Multiple sense-level members | **Lexical Relations** | [Part/Whole](Set_Type_example_sense_tree.md) |
| Entry tree – two names | Multiple entry-level members | **Cross References** | [Specific/Generic](Set_Type_example_entry_tree.md) |
| Entry or sense tree – two names | Multiple entry- or sense-level members | **Cross References or Lexical Relations** | [Test/Result](Set_Type_example_entry_or_sense_tree.md) |
|  |  |  |  |
| Sense Unidirectional | If you want a reference to occur in a sense, but not have a reference *back to that* sense. | **Lexical Relations** |  |
| Entry Unidirectional | If you want a reference to occur in an entry, but not have a reference *back to that* entry. | **Cross References** |  |
| Entry/Sense Unidirectional | If you want a reference to occur in a sense or entry, but not have a reference *back to that* sense or entry. | **Cross References or Lexical Relations** |  |

\* [Cross Reference](../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/cross_references_field.md) fields are at the *[entry](../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Entry_level_fields_overview.md)* level (above the first *sense*).

\*\* [Lexical Relations](../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/lexical_relations_field.md) fields are in each *[sense](../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Sense_level_fields_overview.md) and subsense*.

\*\*\* If the [reference set type](../../User_Interface/Field_Descriptions/Lists/Lexical_Relations_fields/reference_set_type_field.md) includes *Entry/Sense*, then **Step 2: Select Entry or Sense** is available in the [Add Reference](../Lexicon_tools/Lexicon_Edit/Add_Reference_dialog_box_graphic.md) dialog box. This permits you to link an entry to a sense or a sense to an entry.
