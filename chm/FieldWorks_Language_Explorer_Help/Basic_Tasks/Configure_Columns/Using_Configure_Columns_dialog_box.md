---
title: "Using Configure Columns dialog box"
source_title: "Using Configure Columns dialog box"
breadcrumb:
  - "Basic Tasks"
  - "Configure Columns"
  - "Using Configure Columns dialog box"
source: "Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Basic_Tasks/Configure_Columns/Using_Configure_Columns_dialog_box.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Date Created/Modified"
  - "Best Analysis writing system"
  - "Use or Using:Using Configure Columns dialog box"
related:
  - "Configure Columns overview -> Configure_Columns_overview.md"
  - "Filtering data overview -> ../Filtering_data/filtering_data_overview.md"
  - "Number of Text Analyses -> Number_of_Text_Analyses.md"
  - "Single-line text field -> ../../User_Interface/Field_Descriptions/Field_Types/Single_line_text_field.md"
  - "Sorting data overview -> ../Sorting_data/Sorting_data_overview.md"
  - "Word list columns -> ../../Using_Tools/Texts_&_Words_tools/Word_list_columns.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:304209df3509c5f6"
---

# Using Configure Columns dialog box

*Basic Tasks › Configure Columns*

1.  To open the **Configure Columns** dialog box, do either of the following:

    - At the right end of the column headings, and in some dialog boxes, click the ![](../../assets/images/Basic_Tasks/Configure_Columns/Conf_Columns_Button.GIF) ([button](configure_column_button_graphic.md)), and then click **More Column Choices**.

    - On the **Tools** menu, point to **Configure**, and then click **Columns**.

      The **Configure Columns** dialog box appears.

2.  Do any of the following:

    - To *remove* a column from view, in the **Current Columns** pane, click the column you want to remove, and then click **Remove**.

      The selected column moves out of the **Current Columns** pane.

    - To *show* a hidden column or to *add* another column with the same heading/content, in the **Column Options** pane, click the column you want to show/add, and then click **Add**.

      The selected column is added to the list of columns in the **Current** **Columns** pane.

    - To *change the order* of the columns, in the **Current Columns** pane, click a column, and then click the up-arrow button or the down-arrow button to move it. Repeat this to achieve the desired order.

      The top-to-bottom order of the columns in the dialog box determines the left-to-right order of the columns in the **Browse** view.

    - To specify column content *based on the writing system*, click that field (column) in the **Current Columns** pane. Then, if the **Writing Systems** box is available, select a writing system or another option (**Default Vernacular**, **Best Analysis**, **Best Analysis or Vernacular**, and so on. Different contexts permit different options.)

      (**Best Analysis** attempts first to use any content from an associated single line text field entered using the default writing system. If none is found, then content entered using the next analysis writing system is used.)

3.  Click **OK**.

> [!IMPORTANT]
>
> - Configure columns in **Collect Words** to specify which **Lexicon Edit** fields receive the data (**Citation Form**, **Lexeme Form**, **Gloss**, or **Definition**) and the writing system used by each column. See [Collect Words](../../Using_Tools/Lexicon_tools/Collect_Words/Collect_Words_overview.md) and [Collect Words with Dialect Labels](../../Using_Tools/Lexicon_tools/Collect_Words/Collect_Words_with_Dialect_Labels.md).

> [!TIP]
>
> - Suppose a project's lexical data has glosses in three different languages. In **Lexicon Edit**, these glosses appear in [separate lines](../../User_Interface/Field_Descriptions/Field_Types/Single_line_text_field_example_graphic.md), distinguished by their writing system. In **Browse**, each column shows only *one* writing system. Therefore, to display all of the glosses, use **Add** to put *three* **Glosses** columns in the **Current Columns** area, and use the **Writing System** list to select *one* of the three writing systems for *each* column.
>
> - To hide/show a column, *without* using the dialog box, click the **Configure Columns** button, to display the list. Click the desired column in that list. Columns with check marks are displayed in the tool; columns without check marks are hidden.
>
> - The **Date Modified** and **Date Created** columns use the date and time formats that are set in your computer's operating system. You control these in the **Regional and Language Options** dialog box that you can access by way of your **Control Panel**. You can restrict the displayed data based on dates (or numerical values) using the [Restrict to items](../Filtering_data/Using_Restrict_dialog_box.md) dialog box.
>
> - [Bulk Edit overview](../../Using_Tools/Lexicon_tools/Bulk_Edit_Entries/bulk_edit_overview.md) describes features in this dialog box when used in a bulk edit tool.
>
> - [Filter Notebook records](../Filtering_data/Filter_Notebook_records.md) and [Sort Notebook records](../Sorting_data/Sort_Notebook_records.md) describe columns you likely want to display when you filter and sort in **Notebook**.

## Related topics
[Configure Columns overview](Configure_Columns_overview.md)

[Filtering data overview](../Filtering_data/filtering_data_overview.md)

[Number of Text Analyses](Number_of_Text_Analyses.md)

[Single-line text field](../../User_Interface/Field_Descriptions/Field_Types/Single_line_text_field.md)

[Sorting data overview](../Sorting_data/Sorting_data_overview.md)

[Word list columns](../../Using_Tools/Texts_&_Words_tools/Word_list_columns.md)
