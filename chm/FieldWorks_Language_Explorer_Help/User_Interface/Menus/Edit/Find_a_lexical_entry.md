---
title: "Find a lexical entry"
source_title: "Find a lexical entry"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Edit"
  - "Find a lexical entry"
source: "User_Interface/Menus/Edit/Find_a_lexical_entry.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Edit/Find_a_lexical_entry.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Find:Find a lexical entry"
  - "Search"
  - "Go To"
related:
  - "Basic Tasks overview -> ../../../Basic_Tasks/Basic_Tasks_overview.md"
  - "Edit menu overview -> Edit_overview.md"
  - "Find in Dictionary overview -> ../Tools/Find_in_Dictionary_overview.md"
  - "Find a reversal entry -> Find_a_reversal_entry.md"
  - "Find wordform -> Find_wordform.md"
  - "Lexicon Edit overview -> ../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:65f737ee9eb6ab94"
---

# Find a lexical entry

*User Interface › Menus › Edit*

This ![](../../../assets/images/FindEntry.GIF) **Find lexical entry** feature and the ![](../../../assets/images/Find_Replace_Text.GIF) [Find in Lexicon](Find_and_Replace_Lexicon.md) are different.

To find an entry, you can search for a *form* (lexeme form, citation form or allomorph), *gloss* or *definition*. In some cases, you use it to *go to* the entry. In other cases, you use it to *select* an entry you want to add to a field, such as in the **Complex Forms** field.

1.  In applicable **Lexicon** views, do one of the following to open the **Find Lexical Entry** dialog box:

    - On the [Insert](../../Toolbars/Insert_toolbar.md) toolbar, click ![](../../../assets/images/FindEntry.GIF).

    - On the **Edit** menu, click ![](../../../assets/images/FindEntry.GIF) **Find lexical entry**.

    - Press the [shortcut keys](../../Shortcuts/shortcut_keys_Lexicon_tools.md) `Ctrl+F`.

    - In [fields](../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Lexicon_Edit_fields_overview.md) that display other entries, click the ellipsis button ![](../../../assets/images/Ellipsis_button.PNG) to open a chooser dialog box. In *some* of those fields such as **Referenced Complex Form** field, click the "**Add a ...**" link in the chooser.

    The **Find Lexical Entry** dialog box appears.

2.  In the **Writing System** box, select the writing system of the *form* or *gloss*.

3.  In the **Find** box, type the *form* or *gloss*.

4.  If the entry does *not appear* (**Lexical Entries** pane), do any of the following:

    - Change the spelling in the **Find** box.

    - Select a different writing system.

    - Click **Create** to open the **New** **Entry** dialog box so you can [create a new lexical entry](../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Create_a_lexical_entry.md).

      ![](../../../assets/images/Warning_Icon.gif) **Warning:** If you create a new entry with an *analysis* writing system selected, *it will not have a headword* because lexeme and citation forms use a vernacular writing system.

    - Consider if the current [publication](../Tools/Configure_Dictionary/Manage_Dictionary_Views.md) should display it.

    - Click **Cancel** to close the dialog box.

5.  If the entry *appears* (**Lexical Entries** pane), click it. Click **Go To** or **Select**.

In **Dictionary**, if the entry is not [published](../../../Using_Tools/Lexicon_tools/Lexicon_Edit/Specify_publishable_lexical_data.md), then an **Entry not published** warning box appears. In this case, close the warning box, and then [select](../../../Using_Tools/Lexicon_tools/Dictionary/Select_a_publication.md) **All Entries** on the [information bar](../../Toolbars/information_bar_overview.md). Alternatively, you can select the publication in the [Publish Entry In](../../Field_Descriptions/Lexicon/Lexicon_Edit_fields/Publication_Settings_flds/Publish_In_(Publication_Settings).md) field.

> [!NOTE]
>
> - [Configuring](../../../Basic_Tasks/Configure_Columns/Configure_Columns_overview.md) (![](../../../assets/images/Conf_Columns_Button.png)) the columns in the **Lexical Entries** pane does *not* affect the search:
>
> - - Suppose the **Glosses** column displays a particular analysis writing system, but a *different* analysis writing system is selected in the **Writing System** box. The search will find entries with the gloss you type in the **Find** box even if the gloss is not visible.
>
>   - Displaying **Grammatical Info** or **Morph Type** columns will *not* enable a search for content in those fields.
>
> - You can use the `Up Arrow` and `Down Arrow` keys to select an entry (when multiple entries appear in the **Lexical Entries** area) *without* moving the insertion point from the **Find** box.
>
> - A **Target not found** information box appears if a [filter](../../../Basic_Tasks/Filtering_data/filtering_data_overview.md) was turned on that filtered-out the desired entry. Click **Yes** to turn off the filter. If you click **No**, you will not see the desired entry.

## Related topics
[Basic Tasks overview](../../../Basic_Tasks/Basic_Tasks_overview.md)

[Edit menu overview](Edit_overview.md)

[Find in Dictionary overview](../Tools/Find_in_Dictionary_overview.md)

[Find a reversal entry](Find_a_reversal_entry.md)

[Find wordform](Find_wordform.md)

[Lexicon Edit overview](../../../Using_Tools/Lexicon_tools/Lexicon_Edit/lexicon_edit_overview.md)
