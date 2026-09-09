---
title: "Choose components for Show Subentry under field"
source_title: "Choose components for Show Subentry under field"
breadcrumb:
  - "Using Tools"
  - "Lexicon tools"
  - "Lexicon Edit"
  - "Choose components for Show Subentry under"
source: "Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_components_for_Show_Subentry_Under.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Using_Tools/Lexicon_tools/Lexicon_Edit/Choose_components_for_Show_Subentry_Under.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Choose (See also: Select or Specify):Components for Show Subentry under (Lexicon)"
related:
  - "Configure Dictionary dialog box -> ../../../User_Interface/Menus/Tools/Configure_Dictionary/Configure_Dictionary.md"
  - "Lexicon Edit fields overview -> ../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Lexicon_Edit_fields_overview.md"
  - "Lexicon Edit overview -> lexicon_edit_overview.md"
  - "Specify that a form is complex -> Specify_that_Form_is_Complex.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:adca3bf3298c1b3f"
---

# Choose components for Show Subentry under field

*Using Tools › Lexicon tools › Lexicon Edit*

In a complex form entry, each [component](Choose_components_for_Components_field.md) entry that is displayed in the [Show Subentry under](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Publication_Settings_flds/Show_Subentry_under.md) field will include the complex form as an indented subentry in [root-based](../../../User_Interface/Menus/Tools/Configure_Dictionary/Dictionary_views.md) dictionary layouts, *if* it is [configured](../../../User_Interface/Menus/Tools/Configure_Dictionary/Using_the_Configure_Dictionary_dialog_box.md) for display in **Dictionary**.

The **Show Subentry under** field *automatically* shows the *first* component (entry or sense) [chosen](Choose_components_for_Components_field.md) in the **Components** field. To *manually* choose other component entries, do the following:

1.  In the **Navigation** **Pane**, click **Lexicon**, and then click **Lexicon Edit**.

2.  In the **Entries** pane, click the desired entry that is a complex form (has components).

3.  In the **Entry** pane, do *one* of the following:

    - In the [Components](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Components_field.md) field, right-click a component that is *not already in* the **Show Subentry** field, and then click **Show Subentry under this Component**.

    - Below the **Publication Settings** field, click the [Show Subentry under](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Publication_Settings_flds/Show_Subentry_under.md) field, and then click the ellipsis button ![](../../../assets/images/Ellipsis_button.PNG).

      The **Choose where to show subentry** dialog box appears.

      Do the following:

      - Select (![](../../../assets/images/CheckedBox.PNG)) each component entry below which you want to display this complex form as an indented subentry.

      - Clear (![](../../../assets/images/User_Interface/Menus/Tools/UncheckedBox.PNG)) a component entry if you do *not* want this complex form displayed below it as an intended subentry.

      - If necessary, click **Add a Component** to open the **Choose Lexical Entry or Sense** dialog box so you can [choose another component entry](Choose_components_for_Components_field.md) or [create](Create_a_lexical_entry.md) a new component entry.

      - Click **OK**.

> [!IMPORTANT]
>
> - When the components listed in this [Show Subentry under](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Publication_Settings_flds/Show_Subentry_under.md) field and in the [Components](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Entry_level_fields/Components_field.md) field are an exact match (components *and* order), then the "see under" references is not displayed in **Dictionary** for the current entry.

## Related topics
[Configure Dictionary dialog box](../../../User_Interface/Menus/Tools/Configure_Dictionary/Configure_Dictionary.md)

[Lexicon Edit fields overview](../../../User_Interface/Field_Descriptions/Lexicon/Lexicon_Edit_fields/Lexicon_Edit_fields_overview.md)

[Lexicon Edit overview](lexicon_edit_overview.md)

[Specify that a form is complex](Specify_that_Form_is_Complex.md)
