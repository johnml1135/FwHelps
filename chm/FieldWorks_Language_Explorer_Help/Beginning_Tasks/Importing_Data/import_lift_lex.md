---
title: "Import LIFT lexical data"
source_title: "Import LIFT lexical data"
breadcrumb:
  - "Beginning Tasks"
  - "Importing Data"
  - "Import LIFT Lexical Data"
source: "Beginning_Tasks/Importing_Data/import_lift_lex.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Beginning_Tasks/Importing_Data/import_lift_lex.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Import:LIFT Lexical Data"
  - "LIFT lexical data"
  - "Import"
  - "Import:Import LIFT lexical data"
related:
  - "Date fields -> ../../User_Interface/Field_Descriptions/Field_Types/date_field.md"
  - "Import overview -> Import_overview.md"
  - "Send/Receive overview -> ../../Basic_Tasks/Collaborating_with_Others/Send_Receive_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:910cff29dfff2df4"
---

# Import LIFT lexical data

*Beginning Tasks › Importing Data*

This import process will import (add and merge) lexical data into your language project from a LIFT file. See ![](../../assets/images/Important_Icon.gif) **Important** below for current limitations.

It is best if you import data that has the same writing system as the default vernacular. If the LIFT file has different or additional writing systems, they are added to the language project.

To import lexical data from a LIFT file, do the following:

1.  In FieldWorks Language Explorer, [stop the parser](../../User_Interface/Menus/Parser/Start_or_Stop_Parser.md), if it is running.

2.  On the **File** menu, point to **Import**, and then click **LIFT Lexicon**.

    The **Import****/Merge From LIFT File** dialog box appears.

3.  Click **Backup** (*recommended*) if you did not recently [back up](../../User_Interface/Menus/File/Backup_and_Restore/Back_up_this_Project.md) the project.

4.  Select the desired merge setting, so that FieldWorks knows what to do when data conflict (See **Tip** below).

    - Select or clear the **Skip importing entries with identical modification times** check box.

5.  In the **Select the LIFT file to import** box, click **Browse**. (Alternatively, you can type or paste a path directly in the field.)

    The **Open Lexicon Interchange FormaT File** dialog box appears.

6.  Choose a `.lift` file, and then click **Open**.

    The path to the file appears in the **Select the LIFT file to import** box.

7.  Click **OK**.

A progress indicator appears. The progress indicator and dialog box both close when the import is finished. Then, the **Import Log** opens automatically in an Internet Explorer window.

The **Import Log** file is put in the root of your **My Documents** folder (C:\Documents and Settings\\your name\>\My Documents\\file name\>-ImportLog.htm). It lists information such as the number of entries imported, which environments were added to the project, and so on.

> [!IMPORTANT]
>
> - LIFT (*Lexicon Interchange FormaT*) files contain primarily *lexical* data. If another FLEx user provided you lexical data, consider the following:
>
>   *Before* you import any LIFT files, you might want to first
>
>   - restore a [backup file](../../User_Interface/Menus/File/Backup_and_Restore/Backup_files.md) because it contains *grammar* data (slots, affix templates, features, environments and so on) and *list* data (locations and people you added and so on)
>
>   - copy to your computer [other files that are not backed up](../../User_Interface/Menus/File/Backup_and_Restore/Files_that_FieldWorks_does_not_back_up.md)
>
>   - [add](../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Using_the_Writing_System_Properties_dialog_box.md) variant writing systems for [audio files](../../Basic_Tasks/Audio_files/Audio_files_overview.md) to appropriate writing systems.
>
>   Then when you import the LIFT files, you will have a more complete language project.
>
> <!-- -->
>
> - Data *are merged* if the language projects were at one time the *same* language project. Example scenario:
>
> - - One person works with a language project in Language Explorer (FLEx). A backup copy is given to another person who restores it. Both people work in the language project in their respective copies on their own computers. To merge their data, one person exports their copy as a LIFT file. The other person imports that LIFT file (merging the data), and then makes a new backup copy which is restored on the other computer.
>
> - Data are *not* merged, currently, for language projects that were created independently. The imported data are not lost, but appear in separate entries.

> [!TIP]
>
> - With the first two options in the dialog box, the merge uses the 'ids' to identify the matching entries and senses, then tries to merge each field.
>
> - - If a field is empty in one, it receives the content of the other.
>
>   - If it is a sequence or collection, such as examples, semantic domains, and so on, then it will merge the two together—hopefully not duplicating anything that is in both.
>
>   - If the two entries or senses have a field in both objects that is different, that is when it detects that there is a merge conflict.\
>     In that case:\
>     - the *first* import option will ignore the conflicting field in the imported object, leaving that field as it is in the current project;\
>     - with the *second* import option, that field will be replaced with the contents of the imported object.
>
> - With the *third* option, the conflicting field will cause the entire merge of that object to fail and a duplicate entry or sense will be added from the imported file so that you now have two entries or senses; the original one from your project, and the other coming from the LIFT file. Any entries/senses that do not have the same ids are treated as different objects, so they will be imported separately without any attempt at merging. Also, if **Skip importing entries with identical modification times** is selected (![](../../assets/images/CheckedBox.PNG)), and the modification date on the two entries is the same, the imported entry is ignored without any attempt at merging.
>
> - **Skip importing entries with identical modification times** can speed up the import process, regardless of the merge setting:
>
> - - When *selected*, date and time metadata are compared between the current file and the import file. If the date/time stamps are identical for an entry, then no additional comparison is done.
>
>   - When *cleared*, data in *all* fields are compared.

## Related topics
[Date fields](../../User_Interface/Field_Descriptions/Field_Types/date_field.md)

[Import overview](Import_overview.md)

[Send/Receive overview](../../Basic_Tasks/Collaborating_with_Others/Send_Receive_overview.md)
