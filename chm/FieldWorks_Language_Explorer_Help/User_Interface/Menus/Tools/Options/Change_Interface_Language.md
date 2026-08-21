---
title: "Change User interface language"
source_title: "Change User interface language"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Tools"
  - "Options"
  - "Change User interface language"
source: "User_Interface/Menus/Tools/Options/Change_Interface_Language.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Tools/Options/Change_Interface_Language.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Change:User interface language"
  - "Get:Get a Language Pack"
  - "Interface language"
  - "Language Packs:Change User interface language"
  - "Language Packs:Install a UI language pack"
  - "Localization:Change User interface language"
  - "Options dialog box:Change User interface language"
  - "UI language"
  - "User Interface languages"
  - "change:Install UI Language pack"
related:
  - "Delete \n FieldWorks project -> ../../File/Delete_Fieldworks_project.md"
  - "Tools overview -> ../Tools_overview.md"
  - "Options overview -> Options_overview.md"
  - "User \n Interface language for Lists -> User_interface_languages_for_lists.md"
fw_help_version: "9.3"
page_heading: "Change the User Interface language"
type: "topic"
content_hash: "sha256:3b212339ad651385"
---

# Change User interface language

*User Interface › Menus › Tools › Options*

In the **Options** dialog box, the **User interface language** list allows you to select a different language for menus, dialog boxes, [field](../../../Field_Descriptions/field_descriptions_overview.md) labels, and so on. The user interface (UI) language is also important for lists *and* list content ([more](User_interface_languages_for_lists.md)).

## Select an installed UI language

1.  On the **Tools** menu, click **Options**.

    The **Options** dialog box appears.

2.  Click the **General** tab.

3.  Select a user interface language.

4.  Click **OK**.

## Install an additional or most-recently updated UI language pack

1.  Close all FieldWorks programs.

2.  Run the **SIL FieldWorks Installer** again, such as from <a href="https://software.sil.org/fieldworks/download/" target="_blank" title="https://software.sil.org/fieldworks/download/">https://software.sil.org/fieldworks/download/</a>.

3.  In the installer, select **Modify**, and then click **Next**.

4.  Select one or more languages under **Language Packs** ([example](Language_Packs_example.md)).

    - <a href="https://software.sil.org/fieldworks/download/localizations/" target="_blank" title="https://software.sil.org/fieldworks/download/localizations/">https://software.sil.org/fieldworks/download/localizations/</a> has more language packs you can download and install. These are the *most-recently updated* language packs.

5.  Follow the remaining steps as described in the installer dialog box.

> [!IMPORTANT]
>
> - The translations into some of these UI languages are partial and preliminary.
>
> Open the *Chorus Help* system with the [Send/Receive menu](../../Send_Receive/Send_Receive_menu.md) to learn about localization of **Send/Receive** dialog boxes.
>
> - Write to `FLEx_Localization@sil.org`
>
>   - if you are interested in helping translate them, or
>
>   - if you need a language pack that is not yet in the installer or at <a href="https://software.sil.org/fieldworks/download/localizations/" target="_blank" title="https://software.sil.org/fieldworks/download/localizations/">https://software.sil.org/fieldworks/download/localizations/</a>.
>
> - After you have installed the language pack, that content will be available for any *new* project you *subsequently* [create](../../File/Create_a_new_Fieldworks_project.md).
>
>   For older projects that were created *before* you installed the language pack, do the following to see the translated list content:
>
> - [Create](../../File/Create_a_new_Fieldworks_project.md) a new temporary project with writing systems that *match* those in the older project. [Export lists](../../File/Export/Export_Translated_Lists.md) the particular lists you want from that project which have translated content.
>
> - Open the older project, and then [import the lists](../../../../Beginning_Tasks/Importing_Data/Import_Translated_List_Content.md) you just exported.\
>   This will add the translated content, but it will not change any of the list items that you have already translated.
>
> - *FieldWorks Localization* is a technical document that helps you understand the localization process. It is available at <a href="https://software.sil.org/fieldworks/support/technical-documents/" target="_blank" title="https://software.sil.org/fieldworks/support/technical-documents/">https://software.sil.org/fieldworks/support/technical-documents/</a>.
>
> - [Configure List](../Configure_List.md) discusses the use of the current user interface language for list names and descriptions.

## Related topics
[Delete FieldWorks project](../../File/Delete_Fieldworks_project.md)

[Tools overview](../Tools_overview.md)

[Options overview](Options_overview.md)

[User Interface language for Lists](User_interface_languages_for_lists.md)
