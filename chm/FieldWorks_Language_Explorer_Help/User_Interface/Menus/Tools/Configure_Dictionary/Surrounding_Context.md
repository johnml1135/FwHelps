---
title: "Surrounding Context"
source_title: "Surrounding Context"
breadcrumb:
  - "User Interface"
  - "Menus"
  - "Tools"
  - "Configure Dictionary"
  - "Surrounding Context (Before, Between, After)"
source: "User_Interface/Menus/Tools/Configure_Dictionary/Surrounding_Context.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=User_Interface/Menus/Tools/Configure_Dictionary/Surrounding_Context.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "About:Before/Between/After boxes"
  - "ZWSP"
  - "ZWSP:Surrounding Context"
  - "Before"
  - "Between"
  - "After context boxes"
  - "After context boxes:Surrounding Context"
  - "Surrounding context (Before"
  - "After"
  - "ZWNJ"
  - "ZWJ"
  - "LRM"
  - "RLM"
  - "Line break"
  - "insert"
  - "Break a line"
  - "Force a new line"
  - "LRI (formatting):Surrounding Context)"
related:
  - "Configuring a Classified Dictionary layout -> ../Configure_Classified_Dictionary/Configuring_a_Classified_Dictionary_view.md"
  - "Configuring a Reversal Index layout -> ../Configure_Reversal_Index/Configuring_a_reversal_index_view.md"
  - "Using the Configure Dictionary dialog box -> Using_the_Configure_Dictionary_dialog_box.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:2b9e0f87f4307379"
---

# Surrounding Context

*User Interface › Menus › Tools › Configure Dictionary*

When you configure a **Dictionary** layout, **Reversal Index**, **Classified Dictionary** layout or **Document** layout you often see "surrounding context" boxes labelled **Before**, **Between** and **After**.

You can type characters, spaces or symbols in them. What you type is usually visible and uses the [Dictionary-Context style](../../Format/Styles/About_the_Dictionary-Context_style.md).

Additionally, you can also type a Unicode hexadecimal value and then press the shortcut keys **Alt+X** to convert the value to the corresponding Unicode character or symbol (not available in the **Configure Classified Dictionary Layout** or **Configure Document Layout** dialog boxes).

Here are some examples (*not* exhaustive):

|  |  |  |
|----|----|----|
| **Type** | **Alt+X result** | Note |
| 0009 | ![](../../../../assets/images/User_Interface/Menus/Tools/Configure_Dictionary/Tabarrow.png) | (tab) |
| 0020 | • | (dot, for a space) |
| 061C | \[ALM\] | Arabic Letter Mark |
| 202A | \[LRE\] | Left-to-Right Embedding |
| 202D | \[LRO\] | Left-to-Right Override |
| 202B | \[RLE\] | Right-to-Left Embedding |
| 202E | \[RLO\] | Right-to-Left Override |
| 202C | \[PDF\] | Pop Directional Formatting |
| 2066 | \[LRI\] | Left-to-Right Isolate |
| 2067 | \[RLI\] | Right-to-Left Isolate |
| 2068 | \[FSI\] | First Strong Isolate |
| 2069 | \[PDI\] | Pop Directional Isolate |
| 200B | \[ZWSP\] | Zero-Width Space |
| 200C | \[ZWNJ\] | Zero-Width Non-Joiner |
| 200D | \[ZWJ\] | Zero-Width Joiner |
| FEFF | \[ZWNBSP\] | Zero Width No-Break Space |
| 200E | \[LRM\] | Left-to-Right Mark |
| 200F | \[RLM\] | Right-to-Left Mark |
| 00A0 | \[NBSP\] | No-Break Space |
| 202F | \[NNBSP\] | Narrow No-break Space |

|  |  |  |
|----|----|----|
| **Type** | **To** | Note |
| \0A | force a new line | You can do this in any **Before**, **Between** or **After** box. |

> [!TIP]
>
> - Consider the following for some *right-to-left* situations:
>
> 1.  Typically, you can simply type a space to separate parts of a dictionary entry. However, if the space could appear between two pieces of *left-to-right* text that should be ordered with the first one on the right, you need to enter a three-letter sequence: RLMspaceRLM, where RLM is the Unicode character U+200F, the **Right-to-left mark**.
>
>     This sequence acts as a space and it indicates to FieldWorks that the space must be treated as *right-to-left.* It separates the two chunks of *left-to-right* text (such as a gloss or a part of speech) so that they follow the paragraph order separately.
>
> 2.  For two spaces, use RLMspacespaceRLM.
>
> 3.  You can use [ZEdit](../../../../Basic_Tasks/ZEdit.md) to construct a sequence. For example, set ZEdit to UTF8 document, and use the "Insert Characters" command to insert 200F, 0020, 200F. Then, select and copy it to the clipboard, and paste into FLEx.
>
> - You can break strings over several lines for aesthetic or other reasons.\
>   <a href="https://mathiasbynens.be/notes/css-escapes" target="_blank" title="https://mathiasbynens.be/notes/css-escapes">https://mathiasbynens.be/notes/css-escapes</a> has more information.
>
> - Some advanced users can work with [custom css override files](../../../../Advanced_Tasks/Custom_CSS_Override_Files/Custom_CSS_Override_Files_overview.md).
>
> - For additional information, on the [Help](../../Help/Help_overview.md) menu, point to **Resources** and click **Technical Notes on Writing Systems**.

## Related topics
[Configuring a Classified Dictionary layout](../Configure_Classified_Dictionary/Configuring_a_Classified_Dictionary_view.md)

[Configuring a Reversal Index layout](../Configure_Reversal_Index/Configuring_a_reversal_index_view.md)

[Using the Configure Dictionary dialog box](Using_the_Configure_Dictionary_dialog_box.md)

## Related links
<a href="https://unicode-table.com/en/000A/" target="_blank" title="https://unicode-table.com/en/000A/">https://unicode-table.com/en/000A/</a>

<a href="https://en.wikipedia.org/wiki/Zero-width_space" target="_blank" title="https://en.wikipedia.org/wiki/Zero-width_space">https://en.wikipedia.org/wiki/Zero-width_space</a>

<a href="https://en.wikipedia.org/wiki/Zero-width_non-joiner" target="_blank" title="https://en.wikipedia.org/wiki/Zero-width_non-joiner">https://en.wikipedia.org/wiki/Zero-width_non-joiner</a>

<a href="https://en.wikipedia.org/wiki/Zero-width_joiner" target="_blank" title="https://en.wikipedia.org/wiki/Zero-width_joiner">https://en.wikipedia.org/wiki/Zero-width_joiner</a>

<a href="https://en.wikipedia.org/wiki/Left-to-right_mark" target="_blank" title="https://en.wikipedia.org/wiki/Left-to-right_mark">https://en.wikipedia.org/wiki/Left-to-right_mark</a>

<a href="https://en.wikipedia.org/wiki/Right-to-left_mark" target="_blank" title="https://en.wikipedia.org/wiki/Right-to-left_mark">https://en.wikipedia.org/wiki/Right-to-left_mark</a>

<a href="https://en.wikipedia.org/wiki/List_of_Unicode_characters" target="_blank" title="https://en.wikipedia.org/wiki/List_of_Unicode_characters">https://en.wikipedia.org/wiki/List_of_Unicode_characters</a>
