---
title: "Modify security settings for error links"
source_title: "Modify security settings for error links"
breadcrumb:
  - "Beginning Tasks"
  - "Importing Data"
  - "Modify security settings for error links"
source: "Beginning_Tasks/Importing_Data/Modify_security_settings_for_error_links.htm"
source_url: "https://downloads.languagetechnology.org/fieldworks/Documentation/en/index.htm#t=Beginning_Tasks/Importing_Data/Modify_security_settings_for_error_links.htm"
source_hash: "sha256:18f8b3364a5650ff4235ca9d73b9ba1a90362b3f54612977ddd38ccd417084b2"
keywords:
  - "Security settings"
  - "modify"
related:
  - "Import overview -> Import_overview.md"
fw_help_version: "9.3"
type: "topic"
content_hash: "sha256:ddf1eb0ed1c92d53"
---

# Modify security settings for error links

*Beginning Tasks › Importing Data*

> [!CAUTION]
>
> - This is an advanced procedure and it is *strongly recommended* that you *do not attempt this* if you are not experienced in managing or changing the **Registry Editor**. If you incorrectly change items in the registry, you may cause problems in numerous programs or to your security settings.
>
> If you cannot open the error links as you [examine the import preview results](Examine_import_preview_results_errors.md), you may need to add the **My Computer** security zone for your Internet Explorer in the **Internet Options**\\**Security** tab, and then configure it.
>
> 1.  Run **regedit** to open the **Registry Editor** window, and then do the following:
>
>     - Navigate to: **HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Internet Settings\Zones\0**.
>
>     - Click **FLAGS** to open the **Edit DWORD Value** dialog box
>
>     - In the **Value** **data** box, change the value for "dword" to `47`, and then click **OK**.
>
>     - Close the **Registry Editor** window.
>
>     You should now have a **My Computer** security zone in your **Internet Options**\\**Security** tab.
>
> 2.  Launch Internet Explorer, and then to the following:
>
>     - On the **Tools** menu, click **Internet Options**.
>
>     - Click the **Security** tab.
>
> 3.  In the **Security** tab, click the **My Computer** security zone, and then do the following:
>
>     - Click **Custom Level**.
>
>     - Below **ActiveX controls and plug-ins**, change **Download signed ActiveX controls** to **Enable**.
>
>     - Change **Download unsigned ActiveX controls** to **Enable**.
>
>     - Change **Initialize and script ActiveX controls not marked as safe** to **Enable**.
>
>     - Change **Run ActiveX controls and plug-ins** to **Enable**.
>
>     - Change **Script ActiveX controls marked safe for scripting** to **Enable**.
>
>     - Click **OK**.
>
>     - Click **Apply**.
>
>     - Click **OK**.

> [!IMPORTANT]
>
> - If you are running any antivirus program, such as Norton AntiVirus ("NAV"), you may see a **Malicious script detected** alert, because antivirus software, such as NAV, flags such files as a possible virus. You will receive this warning for every shortcut you set up. If you are running NAV, you can select **Authorize this script** from the drop down box, and then select **OK**. You will not be flagged again for this link.

## Related topics
[Import overview](Import_overview.md)
