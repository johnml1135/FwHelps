---
title: "Referenced Complex Forms (sense)"
source_title: "Referenced Complex Forms (sense)"
breadcrumb:
  - "User Interface"
  - "Field Descriptions"
  - "Lexicon"
  - "Lexicon Edit fields"
  - "Sense level fields"
  - "Referenced Complex Forms field (sense)"
source: "User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Referenced_Complex_Forms_(sense).htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Sense_level_fields/Referenced_Complex_Forms_%28sense%29.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Referenced Complex Forms field:Referenced Complex Forms (Senses)"
related:
  - "Add a lexical subentry -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Add_a_lexical_subentry.md"
  - "Specify that a form is complex -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_that_Form_is_Complex.md"
  - "Lexicon Edit overview -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md"
  - "Other Referenced Complex Forms -> ../../../../Menus/Tools/Configure_Dictionary/Other_Referenced_Complex_Forms.md"
  - "Sense-level fields overview -> Sense_level_fields_overview.md"
  - "Show Data overview -> ../../../../../Basic_Tasks/Show_data/Show_data_overview.md"
  - "Specify publishable lexical data -> ../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_publishable_lexical_data.md"
fw_help_version: "9.3"
page_heading: "Referenced Complex Forms field"
type: "topic"
content_hash: "sha256:a73f3f0d4bf3fedf"
---

# Referenced Complex Forms (sense)

*User Interface › Field Descriptions › Lexicon › Lexicon Edit fields › Sense level fields*

**Full name:** **Referenced Complex Forms**

**Location:**

In the **Entry** pane (**Lexicon Edit**).

This **Referenced Complex Forms** field is in each [sense](Sense_level_fields_overview.md) and subsense.

(There is a separate [Referenced Complex Forms](../Publication_Settings_flds/Referenced_Complex_Forms_Publication_Settings.md) field below the **Publication Settings** field.)

**Description:**

This field is used for [lexeme-based](../../../../Menus/Tools/Configure_Dictionary/Dictionary_views.md) dictionary layouts.

It references and displays entries which are complex forms

- that use the current sense or subsense as a [component](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_components_for_Components_field.md),

- *and*, that you want to make available for display in **Dictionary**.

There is a corresponding **Complex Forms** field that always displays and references all complex forms that use this sense or subsense as a component. However, the **Complex Forms** field does *not* affect what is displayed in **Dictionary**. Complex forms displayed in the **Referenced Complex Forms** field are available for display in [Dictionary](../../../../../Using_Tools/Lexicon_tools/Dictionary/Dictionary_overview.md) as [publishable lexical data](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_publishable_lexical_data.md).

**Tasks:**

- [Choose referenced complex forms](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_referenced_complex_forms.md)

  - Select an entry in this field, and then press the **Delete** or **Backspace** key to remove it from the field.

- Right-click an entry form in the field, and then click **Move Left** or **Move Right** to manually reorder the entries in the field. *This affects the order in* **Dictionary***.*

- Click the menu button (![](../../../../../assets/images/Menu_Button_pic.GIF)), and then click **Alphabetical Order** to set the order of the entries to be alphabetical in the field. *This affects the order in* **Dictionary**.

- You can [configure the dictionary](../../../../Menus/Tools/Configure_Dictionary/Configure_Dictionary.md) to show content from associated fields when you configure [Referenced Complex Forms](../../../../Menus/Tools/Configure_Dictionary/Referenced_Complex_Forms.md). When you do this, the order of the **Complex Form Types** list determines the sort order by type. Then, the order of complex forms in the field is applied.

**Field type:** [List reference](../../../Field_Types/List_reference_field.md)

**Writing systems:** Default [vernacular](../../../../../Advanced_Tasks/Writing_Systems/Add_a_new_writing_system/About_Writing_Systems.md)

**Tip:**

- For [root-based](../../../../Menus/Tools/Configure_Dictionary/Dictionary_views.md) dictionary layouts, see:

  - [Subentries field](Subentries_(Sense).md)

  - **[Other Referenced Complex Forms](../../../../Menus/Tools/Configure_Dictionary/Other_Referenced_Complex_Forms.md) (These are those forms that appear in the [Referenced Complex Forms](../Publication_Settings_flds/Referenced_Complex_Forms_Publication_Settings.md) field, but which are** *not* **also in the [Subentries](../Publication_Settings_flds/Subentries_(Publication_Settings).md) field.)**

- Entries that are complex forms (have components) can also be components of other complex forms. So, even entries that are complex forms have **Referenced Complex Forms** fields.

## Related topics
[Add a lexical subentry](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Add_a_lexical_subentry.md) ([Specify that a form is complex](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_that_Form_is_Complex.md))

[Lexicon Edit overview](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md)

**[Other Referenced Complex Forms](../../../../Menus/Tools/Configure_Dictionary/Other_Referenced_Complex_Forms.md)**

[Sense-level fields overview](Sense_level_fields_overview.md)

[Show Data overview](../../../../../Basic_Tasks/Show_data/Show_data_overview.md)

[Specify publishable lexical data](../../../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_publishable_lexical_data.md)
