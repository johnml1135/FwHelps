---
title: "Writing System Properties, Sorting tab"
source_title: "Writing System Properties, Sorting tab"
breadcrumb:
  - "Advanced Tasks"
  - "Writing Systems"
  - "Modifying a Writing System"
  - "Writing System Properties, Sorting tab"
source: "Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_Sorting_tab.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Writing_System_Properties_Sorting_tab.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Collation"
  - "Digraphs"
  - "Multigraphs"
  - "Order (see also Move)"
  - "Sorting:Sorting"
  - "Sorting:Sorting tab"
  - "Writing System Properties"
  - "Writing System Properties dialog box:Sorting tab"
  - "XHTML export"
  - "sorting"
  - "sorting:Sorting tab"
related:
  - "Modifying a writing system overview -> Modifying_a_writing_system_overview.md"
  - "Collation in FieldWorks -> Collation_in_FieldWorks.md"
  - "Pathway multigraphs -> ../../../User_Interface/Menus/File/Pathway_Configuration_Tool/Pathway_multigraphs.md"
  - "Export Through Pathway -> ../../../User_Interface/Menus/File/Pathway_Configuration_Tool/Export_Through_Pathway.md"
  - "Sort - Custom ICU rules -> Sort_Custom_ICU.md"
  - "Sort - Custom Simple rules -> Sort_Custom_Simple_rules.md"
  - "Shoebox-style sort order -> Shoebox_Toobox_style_sort_order.md"
  - "Sort - Same as another language -> Sort_Same_as_another_language.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:303bc6296feb1e05"
---

# Writing System Properties, Sorting tab

*Advanced Tasks › Writing Systems › Modifying a Writing System*

Use this tab to set the sort order for your writing system.

1.  [Open](Open_Writing_System_Properties_dlgbox.md) the **Writing System Properties** dialog box if it is not already open.

2.  In the **Writing Systems** pane, click the *name* of the writing system you will change.

3.  Click the **Sorting** tab.

4.  Click the **Sort** down arrow (![](../../../assets/images/Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/SortDownArrow.png)), and then click *one* of these options:

    - **Default Ordering** to use the default sort order specified by the Unicode Standard.

    - **Custom Simple (Toolbox style) rules** and then [enter](Sort_Custom_Simple_rules.md) them.

    - **Custom ICU rules** and then [enter](Sort_Custom_ICU.md) them.

    - **Same as another language** and then [choose](Sort_Same_as_another_language.md) it.

5.  Test the sort order:

    - Type words in the **Text to Sort** box that are not in the correct order, but that you think would be good to help test your sort rules.

    - Click the **Test Sort** button, and then examine the order of the words listed in the **Sort Results** box.

If necessary, type additional words in the **Text to Sort** box. Then click **Test Sort** again.

1.  - If you are not satisfied with the results, change your rules and test the sort until you are satisfied with the results.

<!-- -->

6.  Click **OK**.

> [!NOTE]
>
> - **Custom Simple (Shoebox style) rules** do *not* control alphabetized headers in [XHTML export](../../../User_Interface/Menus/File/Export/Export_overview.md) files.
>
> Use **Custom ICU rules** to control them.

## Related topics
<a href="Modifying_a_writing_system_overview.md" style="font-weight: normal;">Modifying a writing system overview</a>

[Collation in FieldWorks](Collation_in_FieldWorks.md)

[Pathway multigraphs](../../../User_Interface/Menus/File/Pathway_Configuration_Tool/Pathway_multigraphs.md) / [Export Through Pathway](../../../User_Interface/Menus/File/Pathway_Configuration_Tool/Export_Through_Pathway.md)

[Sort - Custom ICU rules](Sort_Custom_ICU.md)

[Sort - Custom Simple rules](Sort_Custom_Simple_rules.md) / [Shoebox-style sort order](Shoebox_Toobox_style_sort_order.md)

[Sort - Same as another language](Sort_Same_as_another_language.md)

## Related links
<a href="https://www.unicode.org/reports/tr10/" target="_blank" title="https://www.unicode.org/reports/tr10/">https://www.unicode.org/reports/tr10/</a>
