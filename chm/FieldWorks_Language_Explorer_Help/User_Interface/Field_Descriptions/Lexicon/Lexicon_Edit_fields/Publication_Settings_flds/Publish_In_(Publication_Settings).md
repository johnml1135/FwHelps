---
title: "Publish Publication Settings In"
source_title: "Publish Publication Settings In"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Lexicon"
  - "Lexicon Edit fields"
  - "Publication Settings level fields"
  - "Publish Entry In field"
source: "User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Publication_Settings_flds/Publish_In_(Publication_Settings).htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Publication_Settings_flds/Publish_In_%28Publication_Settings%29.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Exclude:Exclude an entry from Dictionary"
  - "Publish In fields:Publish Entry In"
related:
  - "Create a new publication -> ../../../../../Using_Tools/Lists_tools/Create_new_publication.md"
  - "Dictionary overview -> ../../../../../Using_Tools/Lexicon_tools/Dictionary/Dictionary_overview.md"
  - "Publication Settings-level fields overview -> Publ_Set_level_fields_overview.md"
  - "Show Data overview -> ../../../../../Basic_Tasks/Show_data/Show_data_overview.md"
  - "Show Subentry under field -> Show_Subentry_under.md"
  - "Specify publishable lexical data -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_publishable_lexical_data.md"
  - "What is a publication? -> ../../../Lists/Publications/What_is_a_Publication.md"
fw_help_version: "9.3"
page_heading: "Publish Entry In field"
type: "topic"
content_hash: "sha256:73ff03b38bf78f54"
---

# Publish Publication Settings In

*User Interface › Field Descriptions › Lexicon › Lexicon Edit fields › Publication Settings level fields*

**Full name:** **Publish Entry In**

**Location:**

In the **Entry** pane (**Lexicon Edit**).

This field is at the [Publication Settings level](Publ_Set_level_fields_overview.md).

**Description:**

This field can be empty or it can contain one or more publications from the **Publications** [list](../../../../../Using_Tools/Lists_tools/List_item_usage_table.md). You use this field towards [specifying publishable lexical data](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_publishable_lexical_data.md).

It works like a filter:

- If this field contains a publication, then the lexical data in this entry is available for display and for publishing. You will need to [select](../../../../../Using_Tools/Lexicon_tools/Dictionary/Select_a_publication.md) that publication and configure the layout.

- If this field does not contain a particular publication, then, for that publication, the entry becomes *totally* *unavailable* for display in **Dictionary** *and* **Classified Dictionary**, and publishing (as a headword, all senses, examples, and any references to this entry from elsewhere, and so on).

Homograph numbers are automatically updated if you exclude an entry that has a homograph number.

**Tasks:**

- [Choose Publish In field publications](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_Publish_In_publications.md)

<!-- -->

- Right-click the field label, or click the menu button (![](../../../../../assets/images/Menu_Button_pic.GIF)), and then click [Field Visibility](../../../../../Basic_Tasks/Showing_and_hiding_fields/change_the_visibility_of_fields.md).

If the set of publications is other than *all of the publications*, then it counts as if there is something in the field.

If the set of publications is *all of the publications*, then it is as if it is empty.

Thus, when **Normally hidden unless non-empty** is selected (![](../../../../../assets/images/CheckedBoxBLACK.png)), the field should appear if you changed anything, but not appear if you have not changed anything.

- Right-click a publication in the field, and then click **Show in Publications list**.

**Field type:** Non-editable

**Writing systems:** Default [analysis](../../../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md)

## Related topics
[Create a new publication](../../../../../Using_Tools/Lists_tools/Create_new_publication.md)

[Dictionary overview](../../../../../Using_Tools/Lexicon_tools/Dictionary/Dictionary_overview.md)

[Publication Settings-level fields overview](Publ_Set_level_fields_overview.md)

[Show Data overview](../../../../../Basic_Tasks/Show_data/Show_data_overview.md)

[Show Subentry under field](Show_Subentry_under.md)

[Specify publishable lexical data](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_publishable_lexical_data.md)

[What is a publication?](../../../Lists/Publications/What_is_a_Publication.md)
