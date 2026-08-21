---
title: "Analyzing a lexical phrase"
source_title: "Analyzing a lexical phrase"
breadcrumb:
  - "Using Tools"
  - "Texts & Words tools"
  - "Interlinear Texts"
  - "Analyzing a lexical phrase"
source: "Using_Tools/Texts_&_Words_tools/Interlinear_Texts/Analyzing_a_phrase.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Texts_%26_Words_tools/Interlinear_Texts/Analyzing_a_phrase.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Phrase"
  - "Phrase:Analyzing a lexical phrase"
  - "Idiom"
  - "Analyze Texts (parse):Analyzing a lexical phrase"
  - "Lexical Phrase"
  - "Lexical Phrase:Analyzing a lexical phrase"
related:
  - "Help -> ../../../User_Interface/Menus/Help/Help_overview.md"
  - "Interlinear Texts overview -> texts_edit_overview.md"
  - "Morpheme Break examples -> Morpheme_Break_examples.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:c19af00e24536468"
---

# Analyzing a lexical phrase

*Using Tools › Texts & Words tools › Interlinear Texts*

> [!IMPORTANT]
>
> - How you analyze your lexical phrases usually needs to be *discussed with a consultant*.
>
> For a lexical phrase ([idiom](../../../User_Interface/Field_Descriptions/Lists/Complex_Form_Types_flds/Idiom_entry_type.md), phrasal verb, saying, and so on) part of the [analysis task](Analyze_Text_overview.md) might be that you would [link all the words](Link_words_in_phrase.md) in the phrase so that they appear together in a single [word focus box](Word_Focus_Box_examples.md). Then you could select or create a lexical entry for that lexical phrase.
>
> However, many lexical phrases can appear with derivational or inflectional affixes. For example, consider the English idiom **go for broke** and an inflected form **going for broke**.
>
> What should you do with the derivational or inflectional affixes that are part of a lexical phrase?
>
> Here are some optional ways to *consider* (*not* exhaustive):
>
> - [Insert morpheme breaks](Insert_or_remove_morpheme_breaks.md) to isolate the derivational or inflectional affixes from the phrase ([Example](Insert_or_remove_morpheme_breaks.md)).
>
> - [Add the form as a variant](Add_variant_of_lexical_entry.md) in the lexical entry for the basic lexical phrase.
>
> - [Add the form as an allomorph](../../Lexicon_tools/Lexicon_Edit/Insert_an_alternate_form.md) in the lexical entry for the basic lexical phrase (specify **Phrase** in the [Morph Type field](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Alternate_Forms_level_flds/Morph_type_fld_allomorph.md)).

> [!NOTE]
>
> - Currently, computational [parsers](../../../User_Interface/Menus/Parser/Parsing_words_overview.md) are *not* able to analyze such lexical phrases.
>
>   - When you *manually* analyze words or phrases, Language Explorer does a simple lexicon lookup. Any form that matches the characters *and* that has the same morpheme type will match. These are suggested to you with a blue background [color](interlinear_views_colors.md). It does not pay attention to anything else in the lexical entry or in the grammar. When you break words by hand, Language Explorer assumes that you know what you are doing and that you can (and will) correct it if its suggestion is wrong.
>
>   - Computational parsers pay attention to all of the environments, categories, and so on. The results of the automated parser are thus what your lexicon and grammar predict the analysis of the word should be. Parses treat a phrase like a stem. That is, any derivational or inflectional affixes must attach around the phrase, not within it (unless such an affix is an infix, of course). Parsers will *not* correctly analyze phrases like **going for broke** where the tense inflection occurs as a suffix on the first word of the phrase.
>
>     In some cases, it is possible to do some work-arounds that allow a parser to show a valid **Parse result** of **Successful** for an analysis that you completed manually and approved as being correct. This is of limited value. Subsequent instances of that lexical phrase will continue to show the suggestion with a *blue* background color (a matched instance), and *not* the *tan* [color](interlinear_views_colors.md) (parser-suggested analysis).

## Related topics
*Introduction to Parsing*, which is available on the [Help](../../../User_Interface/Menus/Help/Help_overview.md) menu.

[Interlinear Texts overview](texts_edit_overview.md)

[Morpheme Break examples](Morpheme_Break_examples.md)
