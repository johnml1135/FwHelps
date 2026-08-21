---
title: "Custom CSS Override example"
source_title: "Custom CSS Override example"
breadcrumb:
  - "Advanced Tasks"
  - "Custom CSS Override Files"
  - "Custom CSS Override example"
source: "Advanced_Tasks/Custom_CSS_Override_Files/Custom_CSS_Override_example.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Advanced_Tasks/Custom_CSS_Override_Files/Custom_CSS_Override_example.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Custom:CSS Override example"
related:
  - "Advanced Tasks overview -> ../Advanced_Tasks_overview.md"
  - "Custom CSS Override Files overview -> Custom_CSS_Override_Files_overview.md"
  - "Surrounding Context -> ../../User_Interface/Menus/Tools/Configure_Dictionary/Surrounding_Context.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:e89c3d4d095e7af5"
---

# Custom CSS Override example

*Advanced Tasks › Custom CSS Override Files*

Overriding begin/end text to give it special styles.

Note: **Root.css** in %temp%\DictionaryPreview\\projectname\> contains information from styles. You cannot override these styles in **overrides.css**, but you can copy bits of css from this file.

To use this, look in **Preview.css** for something like this:

.entry\> .senses \> .sensecontent \> .sense\> .definitionorgloss\> span:first-child:before{

content:'Definition: (';

}

.entry\> .senses \> .sensecontent \> .sense\> .definitionorgloss\> span:last-child:after{

content:') ';

}

which corresponds to this in the fwdictconfig file:

\<ConfigurationItem name="Definition (or Gloss)" isEnabled="true" before="Definition: (" between=" " after=") " field="DefinitionOrGloss"\>...

Copy this into the **\*Overrides.css** file, then add customizations to make it do what you want, such as:

font-style:italic;

font-weight:bold;

font-family:'Charis SIL',serif;

font-size:10pt;

color:#0F0;

background-color:#F00;

text-decoration-color:#FF0;

colors are: blue \#00F, bright green \#0F0, red \#F00, yellow \#FF0, turquoise \#0FF, pink \#F0F, black \#000, white \#FFF, orange \#F60, violet \#800080

Note: You cannot change the writing system of begin/end text, but you can change the font to display correctly.

You can also override the content.

.entry\> .senses \> .sensecontent \> .sense\> .definitionorgloss\> span:first-child:before{

content:'Definition: (';

font-weight:bold;

font-family:'Times New Roman',serif;

font-size:14pt;

}

.entry\> .senses \> .sensecontent \> .sense\> .definitionorgloss\> span:last-child:after{

content:') ';

color:#0F0;

}

## Related topics
[Advanced Tasks overview](../Advanced_Tasks_overview.md)

[Custom CSS Override Files overview](Custom_CSS_Override_Files_overview.md)

[Surrounding Context](../../User_Interface/Menus/Tools/Configure_Dictionary/Surrounding_Context.md)
