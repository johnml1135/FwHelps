---
title: "Examine Import Preview Results errors"
source_title: "Examine Import Preview Results errors"
breadcrumb:
  - "Beginning Tasks"
  - "Importing Data"
  - "Examine Import Preview Results errors"
source: "Beginning_Tasks/Importing_Data/Examine_import_preview_results_errors.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Beginning_Tasks/Importing_Data/Examine_import_preview_results_errors.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Problems:Examine import preview results errors"
  - "Examine Import Preview Results errors"
  - "Import:Import Preview Results errors"
  - "ZEdit"
  - "program"
  - "CC (Consistent Changes)"
related:
  - "Import overview -> Import_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:ad2d7d7342d22be3"
---

# Examine Import Preview Results errors

*Beginning Tasks › Importing Data*

The **Import Preview Results** **for** *\<name of import file\>* opens in your Internet Explorer. This preview contains **Errors** and **Warnings**, if any, and **Statistics for standard format markers**.

Each *error* indicates a particular line in the import data that has a problem and is presented as a hyperlinked text. The hyperlink opens the actual import data in [ZEdit](../../Basic_Tasks/ZEdit.md) where you can see and edit the problematic line.

These hyperlinks are initially blocked by the explorer. To use these hyperlinks, do the following:

1.  In the open Internet Explorer (IE), click the Information bar that is located below the address bar, and then select **Allow Blocked Content**.

    A **Security Warning** information box appears.

2.  In the **Security Warning** box, click **Yes**.

    The Information bar disappears and the blocks on the error are removed.

3.  Click an error.

    An **Internet Explorer** question box appears and asks if you want to allow the page to open.

4.  Click **Yes**.

    The import data is displayed with the line indicated in the error you clicked automatically selected.

5.  If your computer does not allow you to complete these steps, or if after you do them you still cannot open the error links ("disallowed by user"), you may need to [modify the security settings](Modify_security_settings_for_error_links.md).

> [!TIP]
>
> - If the **Import Preview Results** report opens in a browser *other than* Internet Explorer (IE) and you cannot figure out how to allow the pop-ups to appear in that browser, do the following:
>
> - - Open IE. Copy the URL from the browser in which the report opened to IE.
>
>   - View the report in IE, and follow the instructions above regarding unblocking the pop-ups.
>
> - It is recommended that you start your error-correction efforts at the bottom of the file, with the *highest* line number. Then, if you insert a line the *lower* line numbers are not affected, maintaining the integrity of the hyperlinks.
>
> - Typically errors result from out-of-order fields. For example, a gloss (**\ge**) is part of a sense, usually following part of speech **(\ps**). If the **\ge** field occurs before the **\ps**, this will cause an error because FieldWorks will think that **\ge** is part of an entry, but this is not allowed. The two options are to reorder the fields in the input file, or to add **\ge** as another begin marker in Step 6 of 8. A disadvantage of making it a beginning marker is it disallows having multiple **\ge** fields in one sense. Normally if **\ge** is not a begin marker, if you have more than one **\ge** field in a sense, FieldWorks will append the two fields together separated by a semicolon to form a single gloss. If it is a begin marker, however, it means the second **\ge** will create a new sense.
>
> - In badly ordered data, it may be faster to use CC (*Consistent Changes* tables) or some other means of reordering fields throughout the dictionary rather than manually editing each failed case.
>
> - Import data that as a dash (**-**) before the citation form (for example, `\lx` **–iyaka**) are assigned a **Morph Type** of **–suffix**. If you used the dash to for any other reason than to indicate a suffix, consider changing these in your import data *before* you begin the import process.

## Related topics
[Import overview](Import_overview.md)
