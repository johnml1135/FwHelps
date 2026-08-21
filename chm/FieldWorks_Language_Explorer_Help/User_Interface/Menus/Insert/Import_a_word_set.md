---
title: "Import Word Set"
source_title: "Import Word Set"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Insert"
  - "Import a word set"
source: "User_Interface/Menus/Insert/Import_a_word_set.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Insert/Import_a_word_set.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Words:Word set"
  - "import a"
  - "Import:Word Set"
  - "into the word list"
  - "Import a word set"
related:
  - "Insert menu -> Insert_overview.md"
fw_help_version: "9.3"
page_heading: "Import a word set"
type: "topic"
content_hash: "sha256:90919e5c2684383e"
---

# Import Word Set

*User Interface › Menus › Insert*

You can import a set of words into the [word list](../../../Using_Tools/Texts_&_Words_tools/Word_list_overview.md) from one or more `*.txt` files, and give that set of words a name. In **Filters** ([View](../View/View_overview.md) menu), a filter with this name is added so you can filter for this set of words. You can import multiple files as a group under one name. However, consider how you may want to filter the imported word sets as you decide how many files to import under the same name.

1.  In the **Navigation** **Pane**, click **Texts & Words** and then select **Word Analyses**.

2.  On the **Insert** menu, click **Import Word Set**.

    The **Import Word Set** dialog box appears.

3.  Do the following:

    - In the **Name of New Word Set** box, enter a name.

    - Click **Choose File(s)** to display the **Open** dialog box.

    - In the **Open** dialog box navigate to and select the file that has the words you want to import, and then click **Open**. (Leave the **Files of type** box set to **Text Files (\*.txt)**).\
      You can do this step multiple times if you have words in more than one file.

    - Click **Import**.

4.  Refresh (`F5`) the screen.

    The imported words appear in the **Wordforms** pane.

> [!NOTE]
>
> - **See Also:** [Import Standard Format words and glosses](../../../Beginning_Tasks/Importing_Data/Import_SFM_words_and_glosses/Import_Standard_Format_words_and_glosses.md).
>
> - Currently, there is no way to delete the filter that is created by importing a word set.
>
> - If you do *not* enter a name for the word set, the file name and filename extension (such as *list.txt*) are used as the default name. In this case, you see that filename and extension as the filter name in the [View](../View/View_overview.md) menu.
>
> - Depending upon the writing system and use of any custom characters, you may need to have saved the `*.txt` file with a **Unicode** encoding (**Save As** dialog box, **Encoding** box) for all the characters to appear correctly.

## Related topics
[Insert menu](Insert_overview.md)
