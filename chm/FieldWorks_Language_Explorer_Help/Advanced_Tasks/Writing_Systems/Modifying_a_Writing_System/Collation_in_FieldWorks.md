---
title: "Collation in FieldWorks"
source_title: "Collation in FieldWorks"
breadcrumb:
  - "Advanced Tasks"
  - "Writing Systems"
  - "Modifying a Writing System"
  - "Collation in FieldWorks"
source: "Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Collation_in_FieldWorks.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Collation_in_FieldWorks.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Collation"
  - "Digraphs"
  - "ICU"
  - "ICU:Collation in FieldWorks"
  - "ICU:ICU"
  - "Ignore"
  - "Multigraphs"
  - "Sorting:Sorting"
  - "Tertiary"
  - "Writing System:Collation in FieldWorks"
  - "sorting"
  - "via collation rules"
  - "Collation:Collation in FieldWorks"
related:
  - "Pathway multigraphs -> ../../../User_Interface/Menus/File/Pathway_Configuration_Tool/Pathway_multigraphs.md"
  - "Treat punctuation as word-forming characters -> Valid_Characters_dialog_box/treat_punctuation_as_word_forming_characters.md"
  - "Writing Systems overview -> ../Writing_Systems_overview.md"
  - "Writing System Properties, Sorting tab -> Writing_System_Properties_Sorting_tab.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:29c2c2517d0143a6"
---

# Collation in FieldWorks

*Advanced Tasks › Writing Systems › Modifying a Writing System*

ICU tailoring rules are at

<a href="https://unicode-org.github.io/icu/" target="_blank" title="https://unicode-org.github.io/icu/">https://unicode-org.github.io/icu/</a>.

ICU provides a useful web site for testing collation rules at

<a href="https://icu4c-demos.unicode.org/icu-bin/collation.html" target="_blank" title="https://icu4c-demos.unicode.org/icu-bin/collation.html">https://icu4c-demos.unicode.org/icu-bin/collation.html</a>

Each rule starts with an *ampersand* followed by an *anchor point*. The rest of the rule specifies how characters are collated compared to the anchor point. There is no need to start a new line for each rule, but that makes it more readable.

### Examples

- Here is a simple example of a rule using a primary level (*single left wedge*):

  `&c<k`

  This rule states that “`k`” comes immediately after “`c`” (e.g., `cat`, `kite`, `dog`).**\
  Note:** This does *not* handle uppercase.

  Digraphs can be handled as well:

  `&n<ng`

  This rule states that the “`ng`” digraph occurs after “`n`” (e.g., `nang`, `nung`, `ngang`).**\
  Note:** This does not handle uppercase.

  The Unicode default collation sequence ignores diacritics unless the rest of the word is identical. In that case, words are sorted based on the diacritic (e.g., `bad`, `bád`, `bàd`, `bâd`, `båd`, `bäd` `bãd`).

- *Two left wedges* are used for secondary level collation which only comes into effect if the primary levels are identical. The secondary level is typically used for diacritics. You can change the way diacritics are sorted with the following rule:

  `&a<<à<<á<<â<<å<<ä<<ã`

  This example changes the default collation of diacritics to include grave before acute (e.g., `bad, bàd`, `bád`, `bâd, båd, bäd, bãd`).

  **Note:** In addition to inserting the actual character in a rule, you can also give the code point. The following commands are identical:

  `&a<<à &\u0061<<\u00e0`

- *Three left wedges* are used for tertiary level collation which is typically used for case. Tertiary level sorting only affects strings that are identical through the secondary level.

  `&n<ng<<<Ng<<<NG &c<k<<<K`

  The first rule moves “`ng`” (regardless of case) to follow “`n`” (e.g., `nang, Nang, NANG, nung, ngang, Ngang, NGANG`). The second moves “`k`” (regardless of case) to follow “`c`” (e.g., `cat, kite, Kite, dog`).

- To sort “`á`” at a primary level after all other “`a`'s”, use this rule:

  `&a<á<<<Á`

  This sort order gives `ade, ãde, apple, Azure, áde, Áde`.

  If you need to sort a character before another one instead of after, (e.g., `āb, Āb, aa, Aa`) you can do it two ways:

  `&[before 1]a<ā<<<Ā`

  In this case the right-hand side goes before the A anchor instead of after. The digit 1 indicates this is a primary level.

  `&9<ā<<<Ā`

  The other way is to use an anchor point before the desired letter. Since `9` normally sorts before `A`, we can use the normal way to specify that `ā` immediately follows `9`, so therefore it will be before `A`.

- To sort phonetic script in “`p pʰ b ɸ β m ʍ w`” order, use either of the following identical rules:```&p<pʰ<b<ɸ<β<m<ʍ<w &p<\u0070\u02b0<b<\u0278<\u03b2<m<\u028d<w`

- **Note:** This approach can be used to turn a Shoebox sort sequence (that does not have case distinctions) into a rule. Shoebox has a list of characters, one per line in the desired order. Put an “`&`” in front of the first character and change each new line into “**\<**”.This rule can be pasted into the FieldWorks sort tab. Use only UTF-8 characters, *not* ANSI.

- To sort uppercase and lowercase in “`c C b B a A`” order, use these two rules:`&c<b<<<B &b<a<<<A`

  This can also be combined into a single rule:

  `&c<b<<<B<a<<<A`

**Note:** In an ICU rule, any non-alphanumeric ASCII character is reserved for syntax characters. If you need to control collation of any of these characters, you must enclose them in *apostrophes*. *A single apostrophe is represented as two apostrophes*. Here are some examples of alphanumeric and punctuation characters with our without the `\u` syntax.

<table width="100%">
<tbody>
<tr>
<td style="width: 33%"><p><code>a</code></p></td>
<td style="width: 33%"><p><code>letter a</code></p></td>
<td style="width: 33%"></td>
</tr>
<tr>
<td style="width: 33%"><p><code>\u0061</code></p></td>
<td style="width: 33%"><p><code>letter a</code></p></td>
<td style="width: 33%"></td>
</tr>
<tr>
<td style="width: 33%"><p><code>3</code></p></td>
<td style="width: 33%"><p><code>digit 3</code></p></td>
<td style="width: 33%"></td>
</tr>
<tr>
<td style="width: 33%"><p><code>ng</code></p></td>
<td style="width: 33%"><p><code>digraph ng</code></p></td>
<td style="width: 33%"></td>
</tr>
<tr>
<td style="width: 33%"><p><code>'ng'</code></p></td>
<td colspan="2" style="width: 66%"><p><code>digraph ng</code> (quotes are optional for alphanumeric characters)</p></td>
</tr>
<tr>
<td style="width: 33%"><p><code>\u006e\u0067</code></p></td>
<td style="width: 33%"><p><code>digraph ng</code></p></td>
<td style="width: 33%"></td>
</tr>
<tr>
<td style="width: 33%"><p><code>'-'</code></p></td>
<td style="width: 33%"><p><code>hyphen</code></p></td>
<td style="width: 33%"></td>
</tr>
<tr>
<td style="width: 33%"><p><code>' '</code></p></td>
<td style="width: 33%"><p><code>space</code></p></td>
<td style="width: 33%"></td>
</tr>
<tr>
<td style="width: 33%"><p><code>'\u0020'</code></p></td>
<td style="width: 33%"><p><code>space</code></p></td>
<td style="width: 33%"></td>
</tr>
<tr>
<td style="width: 33%"><p><code>''</code></p></td>
<td style="width: 33%"><p><code>apostrophe</code></p></td>
<td style="width: 33%"></td>
</tr>
<tr>
<td style="width: 33%"><p><code>\u0027\u0027</code></p></td>
<td style="width: 33%"><p><code>apostrophe</code></p></td>
<td style="width: 33%"></td>
</tr>
</tbody>
</table>

To control the collation of an apostrophe you would thus add two apostrophes (not a double quote). To sort `t'` after `t`, you would use the rule

`&t<t''`

The following rules would be one way to handle IPA sorting:

`&d<d͡ʒ`

`&e<ɛ<f<ɸ`

`&i<ɨ`

`&k<k''`

`&n<ŋ`

`&p<p''<r<ɾ`

`&s<ʃ<ʂ`

`&t<t''<t͡s<t͡s''<t͡ʃ<t͡ʃ''<ʈ͡ʂ<ʈ͡ʂ''`

`&z<ʒ<ʐ<ʔ`

Suppose you want to ignore an apostrophe after `m` and `n`, but you want `ng` to sort after `n`, and `ng'` to sort after `ng`. The following rules allow for this.

The `=` syntax states that the right side is identical to the left side.

`&m=m''`

`&M=M''`

`&n=n''`

`&N=N''`

`&n<ng<<<Ng<<<NG<ng''<<<Ng''<<<NG''`

Suppose you want to ignore 02BC;MODIFIER LETTER APOSTROPHE in sorting. There are two ways you could handle this. The following rule doesn’t totally ignore the apostrophe, but it treats it in a secondary level so that it is ignored unless words are identical otherwise. In this case it always comes after other diacritics.

`&\u030E<<\u02BC`

This would result in the following order: `ba, bad, bäd, baʼd, bʼad, bade, bat, bät, baʼt, bʼat, bate``.`

The second approach is to *totally ignore* 02BC.

`&[last tertiary ignorable] = \u02BC`

This would result in the following order `ba, baʼd, bad, bʼad, bäd, bade, baʼt, bat, bʼat, bät, bate`. Since `ba, baʼd`, and `bʼad` all have identical sort keys, their order is random.

If you need to ignore more than one character, use `=` to separate the list of characters. The following rule would ignore an apostrophe, a question mark, a hyphen, a space, and the `ng` digraph

`&[last tertiary ignorable] = '' = '?' = '-' = ' ' = ng`

This could also be represented as

`&[last tertiary ignorable] = \u0027\u0027 = '\u003f' = '\u002d' = '\u0020' = \u006e\u0067`

If you simply want to ignore all punctuation as well as white space, you can use the following rule

`[alternate shifted]`

> [!TIP]
>
> - Remove a parenthesis "(" that appears as [letter headings](../../../Using_Tools/Lexicon_tools/Dictionary/Dictionary_Letter_Headings_overview.md) in **Dictionary** or **Reversal Indexes** with a rule like this:
>
> `&[last tertiary ignorable] = '('`
>
> - For more information, refer to the document entitled <a href="https://downloads.languagetechnology.org/fieldworks/Documentation/FieldWorks%20Sorting%20With%20ICU%20Rules.pdf" target="_blank" title="https://downloads.languagetechnology.org/fieldworks/Documentation/FieldWorks%20Sorting%20With%20ICU%20Rules.pdf">FieldWorks Sorting With ICU rules</a> on the Internet.
>
> You can find it and other documents at <a href="https://software.sil.org/fieldworks/help/technical-documents/" target="_blank" title="https://software.sil.org/fieldworks/help/technical-documents/">https://software.sil.org/fieldworks/help/technical-documents/</a>.

## Related topics
[Pathway multigraphs](../../../User_Interface/Menus/File/Pathway_Configuration_Tool/Pathway_multigraphs.md)

[Treat punctuation as word-forming characters](Valid_Characters_dialog_box/treat_punctuation_as_word_forming_characters.md)

[Writing Systems overview](../Writing_Systems_overview.md)

[Writing System Properties, Sorting tab](Writing_System_Properties_Sorting_tab.md)
