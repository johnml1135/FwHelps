---
title: "Ad hoc Co-occurrence Prevention Rules field content sources"
source_title: "Ad hoc Co-occurrence Prevention Rules field content sources"
breadcrumb:
  - "Using Tools"
  - "Grammar tools"
  - "Ad hoc Rules"
  - "Ad hoc Co-occurrence Prevention Rules field content sources"
source: "Using_Tools/Grammar_tools/Ad_hoc_Rules/Ad_hoc_Rules_field_content_sources.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Grammar_tools/Ad_hoc_Rules/Ad_hoc_Rules_field_content_sources.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Ad hoc Rules"
related:
  - "Ad hoc Rules overview -> Ad_hoc_Rules_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:c827fb1751d45e40"
---

# Ad hoc Co-occurrence Prevention Rules field content sources

*Using Tools › Grammar tools › Ad hoc Rules*

When you insert an *ad hoc co-occurrence prevention rule* ([allomorph](insert_an_allomorph_ad_hoc_rule.md), [morpheme](Insert_a_morpheme_ad_hoc_rule.md), or [group](insert_an_ad_hoc_group.md)), you populate its fields by selecting items from dialog boxes. The content in these dialog boxes comes from the [Lexicon](../../Lexicon_tools/Lexicon_overview.md) as described in the examples below.

### Example – Allomorph Ad hoc Co-occurrence Rule

(It may appear in either the [Key Allomorph](../../../User_Interface/Field_Descriptions/Grammar/Ad_hoc_Rules_fields/Key_Allomorph_field_Ad_hoc_Rules.md) field or the [Other Allomorph(s)](../../../User_Interface/Field_Descriptions/Grammar/Ad_hoc_Rules_fields/other_allomorphs_field_ad_hoc_rules.md) field.)

`tair (throw): taira`

The components come from the following fields:

- `tair` is the *allomorph* from a) **Citation Form**, if used, otherwise **Lexeme Form**, *or* b) **Allomorph**, depending on your selection in the dialog box.

- `(throw)` from the **Gloss** field of the first **Sense**.

- `taira` is the *form* from **Citation Form**, if used, otherwise **Lexeme Form**.

### Example – Morpheme Ad hoc Co-occurrence Rule

(It may appear in either [Key Morpheme](../../../User_Interface/Field_Descriptions/Grammar/Ad_hoc_Rules_fields/Key_Morpheme_field_Ad_hoc_Rules.md) field or the [Other Morpheme(s)](../../../User_Interface/Field_Descriptions/Grammar/Ad_hoc_Rules_fields/other_morphemes_field_ad_hoc_rules.md) field.)

`tair: throw stem/root: verb`

The components come from the following fields:

- `tair` is the *morpheme* from **Citation Form**, if used, otherwise **Lexeme Form**.

- `throw` from the **Gloss** field of the first **Sense**.

- `stem/root` is a ‘type’ of morpheme types.

  For non-stem/root morpheme types (such as affixes), you will see the [token](../../Lists_tools/Change_the_tokens_for_morpheme_types.md), if any are used.

- `verb` from the **Grammatical Info**.

> [!NOTE]
>
> - The list of items in the **Cannot Occur** field is not editable.

## Related topics
[Ad hoc Rules overview](Ad_hoc_Rules_overview.md)
