---
title: "Components field"
source_title: "Components field"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Lexicon"
  - "Lexicon Edit fields"
  - "Entry level fields"
  - "Components field"
source: "User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Components_field.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Components_field.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Components"
  - "Components:Components field"
related:
  - "About Complex Form Types -> ../../../../../Using_Tools/Lists_tools/About_complex_forms.md"
  - "Complex Form Type field -> Complex_Form_Type_field.md"
  - "Entry-level fields overview -> Entry_level_fields_overview.md"
  - "Lexicon Edit overview -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md"
  - "Referenced Complex Forms field -> ../Publication_Settings_flds/Referenced_Complex_Forms_Publication_Settings.md"
  - "Show Data overview -> ../../../../../Basic_Tasks/Show_data/Show_data_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:41b06985985a51f1"
---

# Components field

*User Interface › Field Descriptions › Lexicon › Lexicon Edit fields › Entry level fields*

**Full name:** **Components**

**Location:**

In the **Entry** pane (**Lexicon Edit**).

This field is between the **Lexeme Form** [field](Lexeme_Form_field.md) and the **Sense 1** [field](../Sense_level_fields/Sense_field.md), at the [entry-level](Entry_level_fields_overview.md).

**Description:**

For lexeme forms that are *complex* (have components), this field references and displays its components.

Homograph numbers appear, if the components have them. Sense numbers appear, if senses are selected.

The *first* component you choose also appears in the [Show Subentry under](../Publication_Settings_flds/Show_Subentry_under.md) field.

Entries in the **Show Subentry under** field also appear in the [Complex Forms](Complex_Forms_entry.md) field for those entries.

**Note:**

You typically select a [complex form type](../../../../../Using_Tools/Lists_tools/About_complex_forms.md) in the [New Entry](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Create_a_lexical_entry.md) dialog box when you create a complex entry. Then the [Complex Form Type](Complex_Form_Type_field.md), **Components**, [Show Subentry under](../Publication_Settings_flds/Show_Subentry_under.md) and [Show Minor Entry](../Publication_Settings_flds/Show_Minor_Entry_Pub_Set_level.md) fields appear in the **Entry** pane.

If you did *not* select a complex form type in the **New Entry** dialog box, then these fields appear in the **Entry** pane after you either choose components in *this* field or you click **Lexeme Form as components** on the [Information bar](../../../../Toolbars/information_bar_overview.md) menu button.

If you do not [choose components](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_components_for_Components_field.md), then the **Complex Form Type** and **Components** field set are deleted when you leave the entry.

**Tasks:**

- [Add a lexical subentry](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Add_a_lexical_subentry.md) ([Specify that a form is complex](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_that_Form_is_Complex.md))

- [Choose components for Components field](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_components_for_Components_field.md)

- [Delete Complex Form Info](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/change_the_entry_type.md)

- Right-click an entry in this field, and then click any of the following:

  - **Show Entry in Lexicon**

  - **Show Entry in Concordance**

  - **Show Sense in Concordance**

  - **Show Subentry under this Component**:\
    Click to select (![](../../../../../assets/images/CheckMark%20in%20RightClick%20Menu.png)) and add the entry to the [Subentries](../Publication_Settings_flds/Subentries_(Publication_Settings).md) field in the component entry; click to clear (![](../../../../../assets/images/Cleared%20RightClick%20Menu.png)) and remove the entry from that **Subentries** field.

  - **Move Left** or **Move Right** to reorder the component entries.

- In the **Configure Dictionary** [dialog box](../../../../Menus/Tools/Configure_Dictionary/Configure_Dictionary.md), you configure components under [Component References](../../../../Menus/Tools/Configure_Dictionary/Component_References.md), [Components](../../../../Menus/Tools/Configure_Dictionary/Components.md), and so on.

**Field type:** [List reference](../../../Field_Types/List_reference_field.md)

**Writing systems:** Best [analysis](../../../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md)

**Tip:**

- If you [swap the lexeme form with an allomorph](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Swap_LexForm_with_Allomorph.md), the content in this field changes.

- If you use **Move Left** or **Move Right** to reorder the component entries, the [Show Subentry under](../Publication_Settings_flds/Show_Subentry_under.md) field does *not* change, you should review that field.

- When the components listed in this [Components](Components_field.md) field and the [Show Subentry under](../Publication_Settings_flds/Show_Subentry_under.md) field are an exact match (components *and* order), then the "see under" references is not displayed in **Dictionary** for the current entry. You can use **Move Left** or **More Right** to experiment with this feature.

## Related topics
[About Complex Form Types](../../../../../Using_Tools/Lists_tools/About_complex_forms.md)

[Complex Form Type field](Complex_Form_Type_field.md)

[Entry-level fields overview](Entry_level_fields_overview.md)

[Lexicon Edit overview](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md)

[Referenced Complex Forms field](../Publication_Settings_flds/Referenced_Complex_Forms_Publication_Settings.md)

[Show Data overview](../../../../../Basic_Tasks/Show_data/Show_data_overview.md)
