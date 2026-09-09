---
title: "About Ad hoc Groups"
source_title: "About Ad hoc Groups"
breadcrumb:
  - "Using Tools"
  - "Grammar tools"
  - "Ad hoc Rules"
  - "About Ad hoc Groups"
source: "Using_Tools/Grammar_tools/Ad_hoc_Rules/About_Ad_hoc_Groups.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Grammar_tools/Ad_hoc_Rules/About_Ad_hoc_Groups.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Ad hoc Rules"
  - "About:Ad hoc Groups"
  - "Group"
  - "Ad hoc rules"
related:
  - "Ad hoc Rules field content sources -> Ad_hoc_Rules_field_content_sources.md"
  - "Ad hoc Rules overview -> Ad_hoc_Rules_overview.md"
  - "Insert an Ad hoc Group -> insert_an_ad_hoc_group.md"
  - "Grammar overview -> ../grammar_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:4b26bf719f7a9a7e"
---

# About Ad hoc Groups

*Using Tools › Grammar tools › Ad hoc Rules*

Suppose there is a very common allomorph, say, ‘*a*’ like in many varieties of Nahuatl where ‘*atl*’ means 'water' and the ‘*tl*’ at the end is a suffix. This means the root is only ‘*a*.’ Nahuatl allows root compounding so every time a word has an ‘*a’* in it, it could potentially be this 'water' root. Further, Nahuatl words can be quite long and complex. Numerous other morphemes have allomorphs with an ‘*a*’ in them and a sequence of letters with an ‘*a*’ in it can often be broken down into several different morphemes.

So it is quite possible that a user will want to constrain when such an ‘*a*’ is the water morpheme and when it is not. The user might write some *allomorph ad hoc co-occurrence prevention rule* to deal with *prefixes* that have an ‘*a*’ in them (because of the prefix-root boundary), some that deal with *roots*, and some that deal with *suffixes* (again because of the root-suffix boundary). Thus, they could have a group that is for ‘*atl*’ ('water') and within this group, three groups: one for *prefixes*, one for *roots*, and one for *suffixes*.

Such a group gives the user a way to organize a potentially large set of ad hoc co-occurrence constraints. It also might eventually help the user (or a consultant) figure out a better way to deal with the problem.

> [!IMPORTANT]
>
> - Ad hoc co-occurrence prevention rules are used by the [parsers](../../../User_Interface/Menus/Parser/Parsing_words_overview.md).

## Related topics
[Ad hoc Rules field content sources](Ad_hoc_Rules_field_content_sources.md)

[Ad hoc Rules overview](Ad_hoc_Rules_overview.md)

[Insert an Ad hoc Group](insert_an_ad_hoc_group.md)

[Grammar overview](../grammar_overview.md)
