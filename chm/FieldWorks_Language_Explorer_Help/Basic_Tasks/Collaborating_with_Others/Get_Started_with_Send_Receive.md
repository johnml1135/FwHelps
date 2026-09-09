---
title: "Get Started with Send/Receive"
source_title: "Get Started with Send/Receive"
breadcrumb:
  - "Basic Tasks"
  - "Collaborating with Others"
  - "Get Started with Send/Receive"
source: "Basic_Tasks/Collaborating_with_Others/Get_Started_with_Send_Receive.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Basic_Tasks/Collaborating_with_Others/Get_Started_with_Send_Receive.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Send/Receive:Get Started with Send/Receive"
  - "Get:Get Started with Send/Receive"
  - "Chorus"
  - "Send/Receive"
  - "Receive (Get)"
  - "Receive (Get):Get Started with Send/Receive"
  - "Get"
related:
  - "Open a FieldWorks language project -> ../../User_Interface/Menus/File/Open_a_language_project.md"
  - "Send/Receive overview -> Send_Receive_overview.md"
  - "Spelling Checking vernacular words -> ../Spell_Checking/vernacular_spell_checking.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:cf4de76dcf566458"
---

# Get Started with Send/Receive

*Basic Tasks › Collaborating with Others*

To get started correctly, you must use the correct [Send/Receive menu](../../User_Interface/Menus/Send_Receive/Send_Receive_menu.md) command. *Some* commands "get" (![](../../assets/images/Basic_Tasks/Collaborating_with_Others/GET_Icon.png)) a full project or lexical data (LIFT). *Other* commands "send" (![](../../assets/images/Basic_Tasks/Collaborating_with_Others/Send_Icon.png)) data, or do *both* send and receive (![](../../assets/images/Basic_Tasks/Collaborating_with_Others/Send_Receive_Icon.png)).

**For the repository** - If the *shared* [repository](../../Glossary_of_Terms.md#R) will be on

- an *Internet* server, set up the account with the instructions provided by the server administrator. For example, see <a href="https://lexbox.org/login" target="_blank" title="https://lexbox.org/login">Lexbox.org</a> (formerly *Language Depot*).

**See Also:** [Collection of Locale Data](../../Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Collection_of_Locale_data.md).

- a *networked computer*, designate a computer to function as the "server," and then [start Chorus Hub](Chorus_Hub_overview.md) on that computer. It could be one of the computers on which FLEx or WeSay is running or a dedicated computer.

- a *USB Flash Drive* or other remote device, have it ready for use.

### For FLEx-to-FLEx collaboration

1.  Choose *one copy* of the language project.

    - Make sure it contains *the most recent and complete* data because this copy will be used to create the *shared* repository.

2.  The person with that copy of the language project:

    - Make sure that the Internet server is ready or that Chorus Hub is running, or insert the USB Flash Drive.

    - On the **Send/Receive** menu, click ![](../../assets/images/User_Interface/Menus/Send_Receive/Send_Icon.png) **Send this Project for the first time**.

    - In the **Send/Receive** dialog box, click **OK (I have the master project)**.

    - In the **Send/Receive Project** dialog box, click a button (**USB Flash Drive**, **Internet** or **Chorus Hub**).

    - When done, click **Close** in the **Send/Receive Project** dialog box.

<!-- -->

3.  Each *other* person:

    - [Delete](../../User_Interface/Menus/File/Delete_Fieldworks_project.md) or [rename](../../User_Interface/Menus/File/Backup_and_Restore/Rename_a_FieldWorks_project.md) any copy of the language project that is on your computer.

    - [Get the project](../../User_Interface/Menus/Send_Receive/Get_a_project.md) from the *shared* repository project.

4.  Review the information in ![](../../assets/images/Important_Icon.gif) **Important** below.

### For FLEx-to-LIFT collaboration

1.  Do the following to *create* the shared repository from FLEx:

    - Make sure that the Internet server is ready or that Chorus Hub is running, or insert the USB Flash Drive.

    - On the **Send/Receive** menu, click ![](../../assets/images/User_Interface/Menus/Send_Receive/Send_Icon.png) **Send this Lexicon (WeSay) for the first time**.

    - In the **Send/Receive** dialog box, click **OK (I have the master project)**.

    - In the **Send/Receive Project** dialog box, click a button (**USB Flash Drive**, **Internet** or **Chorus Hub**).

    - When done, click **Close** in the **Send/Receive Project** dialog box.

<!-- -->

2.  In the Chorus-enabled program, such as WeSay, use Send/Receive to get that project.

3.  Review the information in ![](../../assets/images/Important_Icon.gif) **Important** below.

### For LIFT-to-FLEx collaboration

1.  Do the following to *create* the shared repository from the Chorus-enabled program (such as WeSay):

    - Use **Send/Receive** in that program to *create* a lexical (LIFT) repository at an agreed-upon location (**USB Flash Drive**, **Internet** or **Chorus Hub**).

2.  FLEx user:

    - [Get the lexicon](../../User_Interface/Menus/Send_Receive/Get_a_lexicon.md).

Get that shared repository and merge its data into the open project.

3.  Review the information in ![](../../assets/images/Important_Icon.gif) **Important** below.

> [!IMPORTANT]
>
> - As a general rule, data are included when you use the send/receive feature; Personal settings, such as views, are *not* included. You need to install fonts and keyboards on each computer or device separately.\
>   For more details, see <a href="https://software.sil.org/fieldworks/support/using-sendreceive/" target="_blank" title="https://software.sil.org/fieldworks/support/using-sendreceive/">https://software.sil.org/fieldworks/support/using-sendreceive/</a>.
>
> <!-- -->
>
> - After you do the steps above, each copy of the project will have a "common ancestor" (the shared repository).
>
> *This is required for subsequent send/receive collaboration.*
>
> When each person works with the project in FLEx, changes are stored in their *personal* repository on their local computer until the next use of send/receive. Specifically, you each use the **Send/Receive-Project** (FLEx-to-FLEx) *or* **Send/Receive-Lexicon** (LIFT-to-FLEx) to merge other people's changes into your *personal* repository and then update the *shared* repository.
>
> These processes could actually be described as "receive/send."
>
> - If multiple FLEx users will collaborate with one or more WeSay users, it is recommended that only one of the FLEx users use **Send/Receive Lexicon** with the WeSay users, and then use **Send/Receive Project** to keep the other FLEx user(s) updated.
>
> **Send/Receive Lexicon** *cannot and will not sufficiently synchronize the two FLEx users. Non-lexical data loss is likely.*
>
> - [Send/Receive considerations](Send_Receive_considerations.md) and [Writing system collaborating issues](Writing_system_collaboration_issues.md) have information about which you need to be aware.

> [!NOTE]
>
> 1.  - **Technical Notes on FieldWorks Send-Receive** is available under **Resources** on the [Help](../../User_Interface/Menus/Help/Help_overview.md) menu.
>
>     - **Help** on the [Send/Receive menu](../../User_Interface/Menus/Send_Receive/Send_Receive_menu.md) opens **Chorus Help** with additional information.

## Related topics
[Open a FieldWorks language project](../../User_Interface/Menus/File/Open_a_language_project.md)

[Send/Receive overview](Send_Receive_overview.md)

[Spelling Checking vernacular words](../Spell_Checking/vernacular_spell_checking.md)
