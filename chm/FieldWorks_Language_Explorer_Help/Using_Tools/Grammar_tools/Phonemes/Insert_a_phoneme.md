---
title: "Insert a phoneme"
source_title: "Insert a phoneme"
breadcrumb:
  - "Using Tools"
  - "Grammar tools"
  - "Phonemes"
  - "Insert a phoneme"
source: "Using_Tools/Grammar_tools/Phonemes/Insert_a_phoneme.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Grammar_tools/Phonemes/Insert_a_phoneme.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Insert:Phoneme"
  - "Phoneme"
  - "Grapheme:Insert a phoneme"
  - "Digraphs"
  - "Multigraphs"
related:
  - "Phonemes fields overview -> ../../../User_Interface/Field_Descriptions/Grammar/Phonemes_fields/Phonemes_fields_overview.md"
  - "Phonemes overview -> Phonemes_overview.md"
  - "Phonological Features field (Phonemes) -> ../../../User_Interface/Field_Descriptions/Grammar/Phonemes_fields/Phonological_Features_field.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:0d1fcbaa0c10918c"
---

# Insert a phoneme

*Using Tools › Grammar tools › Phonemes*

*First*, make sure necessary phonological features and values are available in the [Phonological Features tool](../Phonological_Features/Phonological_Features_overview.md) (if you use phonological features).

Reason: When you enter the IPA symbol in the **IPA Symbol** field, Language Explorer adds phonological features and values to the **Phonological Features** field, if it is empty. If the **Description** field is empty, Language Explorer also adds a description. Fields with existing content are *not* changed.

1.  In the **Navigation** **Pane**, click **Grammar**, and then click **Phonemes**.

2.  Do one of the following:

    - On the [Insert](../../../User_Interface/Toolbars/Insert_toolbar.md) toolbar, click ![](../../../assets/images/Using_Tools/Grammar_tools/Phonemes/Create_Phoneme_Grammar.GIF).

    - On the **Insert** menu, click **Phoneme**.

    - Press the [shortcut keys](../../../User_Interface/Shortcuts/shortcut_keys_Grammar_tools.md) `Ctrl+I`.

    A new phoneme is inserted.

3.  In the [Refer to as](../../../User_Interface/Field_Descriptions/Grammar/Phonemes_fields/name_field_phonemes.md) field, type one or more characters that represent the way the phoneme is commonly represented in the vernacular writing system.

4.  In the [IPA Symbol](../../../User_Interface/Field_Descriptions/Grammar/Phonemes_fields/Basic_IPA_Symbol_fld_(Phms).md) field, type the IPA symbol for the phoneme.

5.  If necessary, do the following:

    - In the [Description](../../../User_Interface/Field_Descriptions/Grammar/Phonemes_fields/description_field_phonemes.md) field, type or edit the description.

    - In the [Phonological Features](../../../User_Interface/Field_Descriptions/Grammar/Phonemes_fields/Phonological_Features_field.md) field, [choose](Choose_phonological_features.md) phonological features. Alternatively, you can [Bulk Edit Phoneme Features](../Bulk_Edit_Phoneme_Features/Bulk_Edit_Phoneme_Features.md).

6.  Below the **In Orthography as** label, enter all the different ways the phoneme is written in the vernacular writing system:

<!-- -->

1.  - In the default (first) [Grapheme](../../../User_Interface/Field_Descriptions/Grammar/Phonemes_fields/representation_field_phonemes.md) field, enter one or more characters that represent the way the phoneme commonly appears (is written) in the vernacular writing system (often the same as you entered in the **Refer to as** field). **See also:** [Non-base characters as graphemes](Non_Base_Characters_as_Graphemes.md).

    - [Insert](Insert_a_representation.md) additional **Grapheme** fields, if there is more than one way to write the phoneme in the orthography.

> [!TIP]
>
> - A *grapheme* is anything that functions as a distinct unit within an orthography. A grapheme may be a *single* character, a *multigraph*, or a *diacritic*, but in all cases graphemes are defined in relation to the particular orthography.
>
> - [Natural classes](../Natural_Classes/Natural_classes_overview.md) and [environments](../Environments/Environments_overview.md) can use phonemes, and these can then be used by a [parser](../../../User_Interface/Menus/Parser/Parsing_words_overview.md). They appear in the [grammar sketch](../Grammar_Sketch/Grammar_Sketch_overview.md).

## Related topics
[Phonemes fields overview](../../../User_Interface/Field_Descriptions/Grammar/Phonemes_fields/Phonemes_fields_overview.md)

[Phonemes overview](Phonemes_overview.md)

[Phonological Features field (Phonemes)](../../../User_Interface/Field_Descriptions/Grammar/Phonemes_fields/Phonological_Features_field.md)

## Related links
<a href="https://software.sil.org/fonts/guides/" target="_blank" title="https://software.sil.org/fonts/guides/">https://software.sil.org/fonts/guides/</a>
