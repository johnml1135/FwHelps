---
title: "Prepare MDF data for import"
source_title: "Prepare MDF data for import"
breadcrumb:
  - "Beginning Tasks"
  - "Importing Data"
  - "Prepare MDF data for import"
source: "Beginning_Tasks/Importing_Data/Prepare_MDF_data.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Beginning_Tasks/Importing_Data/Prepare_MDF_data.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Prepare MDF data"
  - "CC (Consistent Changes)"
related:
  - "Import Standard Format lexical data -> Import_Standard_Format_lexical_data.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:0e7443371d374eed"
---

# Prepare MDF data for import

*Beginning Tasks › Importing Data*

This topic contains input from *one* user regarding his process of preparing Toolbox/MDF data for importing into FLEx. It is *not* exhaustive. It is offered here to provide you with considerations and practices that may help you as you prepare your MDF data for import.

1.  Make a list of all the SFMs used. In Toolbox, go to **Database-Properties** and make a list of all the fields that are in bold type.

2.  Use the **Browse** view to systematically sort on each field. Use the **First Record** and **Last Record** buttons to find the beginning and end of each column of data.

    Problems tend to “float to the top” or “sink to the bottom” so this is an easy way to find problems. It is usually good to sort each field left-to-right, look at the beginning and end. Then, sort right-to-left and look at the beginning and end *again*. Fix any problems you find.

3.  Scan through fields, such as **\ps (part of speech/grammatical category)**, and fix any typos or other inconsistencies. Try to scan through *each* field, unless the database is too large.

4.  Make sure that each field is being used for the *purpose* for which it was designed.

    Occasionally, some fields are used for purposes other than what MDF intended, causing that data to go into the wrong FLEx field, unless you notice it and redirect it. This is especially a problem if the field is used for more than one kind of data.

5.  When you import the data into FLEx, it gives [error messages](Examine_import_preview_results_errors.md) when the MDF hierarchy is violated. Fix these problems. If necessary, restore the empty backup copy of the database in FLEx, and then import the data again.

    If the problem is systematic, consider using a CC table to fix it. Otherwise, for just a few records, fix them by hand.

> [!TIP]
>
> - For more information, on the [Help](../../User_Interface/Menus/Help/Help_overview.md) menu point to **Resources**, and then click **Technical Notes on** **SFM Database** **Import**.
>
> - It may be worth importing your data into FLEx even if you do not intend to use that program. FLEx constrains data quite rigorously, so the import process can help you find and eliminate errors in your database.

## Related topics
[Import Standard Format lexical data](Import_Standard_Format_lexical_data.md)
