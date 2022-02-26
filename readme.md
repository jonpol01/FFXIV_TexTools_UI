# FFXIV TexTools

TexTools is a FFXIV Modding Framework for both mod creation and use/installation. It was originally created by Liinko in 2016, but has since been greatly updated and extended by the TexTools Github Group.

You can download TexTool Installer from the [Releases Page](https://github.com/TexTools/FFXIV_TexTools_UI/releases).

Bugs can reported on our Github [Issues Page](https://github.com/TexTools/FFXIV_TexTools_UI/issues).


## System Requirements

- Windows 7 SP1, Windows 8.1 and Windows 10 19h1 (18362) or higher (32 or 64 bit)
- All users require [Visual C++ 2019+ x64 and x86 as well as Visual Studio 2012 Update 4 Redistributables](https://docs.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170)
- Windows 7 SP1 and 8.1 users need to have [.Net Framework 4.8](https://dotnet.microsoft.com/download/dotnet-framework/net48) installed.
  - Windows 10 19h1 has this included, users on early versions of Windows 10 are advised to update instead of installing the 4.8 installable. 
- Windows 7 SP1 requires the [Platform Update for Windows 7 (KB2670838)](https://www.microsoft.com/en-au/download/details.aspx?id=36805)
  - Some users will need to uninstall this KB patch and reinstall it due to known/resolved cases where some of the subdependencies were blocked due to outdated/broken display drivers.

### Technical Notes

- Most mods are intended for the DX11 client, requiring a 64bit Windows install.
- There are possible issues with Rivatune Statistics Server 7.2.2 and older following a Windows update that has changed Windows D3D runtime files. 
  - Update to latest MSIAB or standalone RTSS release.
- Nahimic OSD is known to cause GUI corruption, this is a flaw in Nahimic itself and affects all WPF applications to some degree or other.
  - Nahimic v3 1.8.6 and later is reported to resolve the issue, this will be obtainable from your Mainboard, or audio device vendor in their respective sound software.
