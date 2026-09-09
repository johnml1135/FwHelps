---
title: "Publish Sense In"
source_title: "Publish Sense In"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Lexicon"
  - "Lexicon Edit fields"
  - "Sense level fields"
  - "Publish Sense In field"
source: "User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Publish_In_(Sense).htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Publish_In_%28Sense%29.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Exclude:Exclude a sense from Dictionary"
  - "Publish In fields:Publish Sense In"
related:
  - "Create a new publication -> ../../../../../Using_Tools/Lists_tools/Create_new_publication.md"
  - "Sense-level fields overview -> Sense_level_fields_overview.md"
  - "Show Data overview -> ../../../../../Basic_Tasks/Show_data/Show_data_overview.md"
  - "Show Subentry under -> ../Publication_Settings_flds/Show_Subentry_under.md"
  - "Specify publishable lexical data -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_publishable_lexical_data.md"
  - "What is a publication? -> ../../../Lists/Publications/What_is_a_Publication.md"
fw_help_version: "9.3"
page_heading: "Publish Sense In field"
type: "topic"
content_hash: "sha256:b010adad3f395d4a"
---

# Publish Sense In

*User Interface › Field Descriptions › Lexicon › Lexicon Edit fields › Sense level fields*

**Full name:** **Publish Sense In** or **Publish Subsense In**

**Location:**

In the **Entry** pane (**Lexicon Edit**).

This **Publish Sense In** field appears in each [sense](Sense_level_fields_overview.md) and subsense.

**Description:**

This field can be empty or it can contain one or more publications from the **Publications** [list](../../../../../Using_Tools/Lists_tools/List_item_usage_table.md).\
It works like a filter.

- If this field, in a particular sense or subsense, contains a publication then lexical data in that sense or subsense, and any of their subsenses are *available* for display and for publishing. You will need to [select](../../../../../Using_Tools/Lexicon_tools/Dictionary/Select_a_publication.md) the publication and configure the view.

- If this field does *not* contain a publication in a *sense,* then for that publication, the *sense and any of its subsenses* are *unavailable* (in the lexical entry and in references from elsewhere) for display or for publishing.

  - If this field does *not* contain a publication in a *sub*sense, then for that publication, the *subsense and any of its subsenses* are *unavailable* (in the lexical entry and in references from elsewhere) for display or for publishing.

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

**Tip:**

[Usages](Usages_field.md) field content can help identify data you do *not* want to publish, such as offensive data. Here is one possible example scenario:

- [Choose](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_Usages.md) **offensive** in the **Usages** fields for offensive data.

- [Filter](../../../../../Basic_Tasks/Filtering_data/filter_lexical_entries.md) for senses marked as 'offensive'.

- [Remove](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_Publish_In_publications.md) the publication from the **Publish Sense In** fields for those senses.

- [Select](../../../../../Using_Tools/Lexicon_tools/Dictionary/Select_a_publication.md) that publication. Offensive data is not displayed.

### **Related Topics**

[Create a new publication](../../../../../Using_Tools/Lists_tools/Create_new_publication.md)

[Sense-level fields overview](Sense_level_fields_overview.md)

[Show Data overview](../../../../../Basic_Tasks/Show_data/Show_data_overview.md)

[Show Subentry under](../Publication_Settings_flds/Show_Subentry_under.md)

[Specify publishable lexical data](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_publishable_lexical_data.md)

[What is a publication?](../../../Lists/Publications/What_is_a_Publication.md)
