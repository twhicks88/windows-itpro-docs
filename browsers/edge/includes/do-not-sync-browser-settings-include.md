<!-- ## Do not sync browser settings  --> 
>*Supported versions: Microsoft Edge on Windows 10, next major update to Windows*<br> 
>*Default setting:  Disabled or not configured (Allowed/turned on)*

[!INCLUDE [do-not-sync-browser-settings-shortdesc](../shortdesc/do-not-sync-browser-settings-shortdesc.md)]

### Supported values

|Group Policy  |MDM |Registry |Description |
|---|:---:|:---:|---|
|Disabled or not configured<br>**(default)** |0 |0 |Allowed/turned on. The “browser” group syncs automatically between user’s devices and lets users to make changes. |
|Enabled |2 |2 |Prevented/turned off.  The “browser” group does not use the Sync your Settings option. |
---

### Configuration options

For more details about configuring the browser syncing options, see [Sync browser settings options](../group-policies/sync-browser-settings-gp.md).




### ADMX info and settings
#### ADMX info
- **GP English name:** Do not sync browser settings
- **GP name:** DoNotSyncBrowserSetting
- **GP path:** Windows Components/Sync your settings
- **GP ADMX file name:** SettingSync.admx

#### MDM settings
- **MDM name:** [Experience/DoNotSyncBrowserSetting](../available-policies.md#do-not-sync-browser-settings)
- **Supported devices:** Desktop
- **URI full path:** ./Vendor/MSFT/Policy/Config/Experience/DoNotSyncBrowserSetting
- **Data type:** Integer

#### Registry settings
- **Path:** HLKM\\Software\Policies\Microsoft\Windows\SettingSync
- **Value name:** DisableWebBrowserSettingSyncUserOverride
- **Value type:** REG_DWORD


### Related policies

[Prevent users from turning on browser syncing](../new-policies.md#prevent-users-from-turning-on-browser-syncing): [!INCLUDE [prevent-users-to-turn-on-browser-syncing-shortdesc](../shortdesc/prevent-users-to-turn-on-browser-syncing-shortdesc.md)]



### Related topics

[About sync setting on Microsoft Edge on Windows 10 devices](http://windows.microsoft.com/windows-10/about-sync-settings-on-windows-10-devices)
<p><p>
<hr>