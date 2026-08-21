---
title: "Valid Characters, Manual Entry tab"
source_title: "Valid Characters, Manual Entry tab"
breadcrumb:
  - "Advanced Tasks"
  - "Writing Systems"
  - "Modifying a Writing System"
  - "Valid Characters dialog box"
  - "Manual Entry tab, Valid Characters"
source: "Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Valid_Characters_dialog_box/Valid_Chars_Manual_Entry_tab.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Advanced_Tasks/Writing_Systems/Modifying_a_Writing_System/Valid_Characters_dialog_box/Valid_Chars_Manual_Entry_tab.htm"
source_hash: "sha256:902c7d7196f408addc2e76cc7f471f0bac6efcb24cb42bbd21d8abe7fd0faf05"
keywords:
  - "Valid Characters"
  - "Valid Characters:Valid Characters"
  - "Manual Entry tab"
  - "Characters"
  - "valid for writing system"
related:
  - "Valid Characters 
 dialog box -> Valid_Char_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:a477863e35734993"
---

# Valid Characters, Manual Entry tab

*Advanced Tasks › Writing Systems › Modifying a Writing System › Valid Characters dialog box*

You can manually enter a *single* valid character, a *range* of valid characters, or a character based on its hexadecimal Unicode value for the current writing system. The current writing system is identified between the title bar and the tabs. If the keyboard is set up properly, it is automatically selected when you click the boxes in this tab.

- In the **Valid Characters** dialog box, click the **Manual Entry** tab.

### Add a *single* character

1.  Select **Single Character**.

2.  Enter (type or paste) the base character plus any combining characters, such as diacritics.

3.  Click **Add**.

    The character you entered moves to the **Valid Characters** pane.

    Repeat these steps for each single character you need to add manually.

### Add a *range* of characters

1.  Select **Range** **of** **Base** **Characters**.

2.  Enter the first base character and last base character in the boxes.

3.  Click **Add**.

    The characters in that range you entered move to the **Valid Characters** pane.

    Repeat these steps for each single character you need to add manually.

### Add a character with a hexadecimal Unicode value

1.  Select **Unicode Value**.

2.  Enter the hexadecimal value, and then click **Add**.

    - If a message box appears stating that the character is not defined and cannot be added, do the following:

      Close the **Valid Characters** dialog box.

      Add the character as a custom character.

      Return to the **Manual Entry** tab, and repeat steps 1 and 2 above.

    The character associated with the hexadecimal value is added to the **Valid Characters** pane.

    Repeat these steps for each single character you need to add with a hexadecimal Unicode value.

> [!NOTE]
>
> - A range of characters is determined by the Unicode values of the characters. When you add a range of characters, the first and last character of the range must be base characters. That is, a character that does not graphically combine with preceding characters, and that is neither a control nor a format character.
>
> - On the **Keyboard** tab of the **Writing Systems Properties** dialog box, you can select a keyboard to type characters from the active writing system in the boxes in this tab
>
> - Internet sites like <a href="https://unicode.org/charts/" target="_blank" title="https://unicode.org/charts/">https://unicode.org/charts/</a> may provide hexadecimal values.

## Related topics
[Valid Characters dialog box](Valid_Char_overview.md)
