# lookpilot-downloads
Installer downloads for the LookPilot app.

latest version: 1.0.14

Changelog:
## 1.0.14
- fixes to auto upgrading
- released for auto upgrade test
## 1.0.15
- bug fixes in auto upgrading
- mandatory updating dialog for windows
- optional update link for linux
- remove run now from uninstaller
## 1.0.16
- use wau for lookpilot auto updates instead of updating from within the app
## 1.1.0
- added 'auto' protocol to linux (now being the default protocol)
- updated status indicator GUI
- moved fps info to status indicator
## 1.1.1
- added start guide
## 1.1.2
- added start guide translations
## 1.1.11
- add early access notice on linux builds
- fix visualization cube not showing on linux
- remove manual bash script launch depenendency for auto protocol 
- speed up auto protocol on steam build
- fix auto protocol json decode error issue
- fix app crashing on resize on linux
- add free trial to standalone version
- add logout tab to standalone version
## 1.2.0
- improve auto protocol compatibility
- replace game process with game's wine prefix in auto protocol
- rename freetrack (Proton) to freetrack (Wine)
- improve compatibility of other launcher in freetrack (Wine) 
- change tool path to wine executable in other launcher in freetrack (Wine)
- sending a bug report now sends more comprehensive logs
## 1.2.6
- added max input & output customization
- added proton launch detection
## 1.2.10
- Fix quick start guide dialog scaling bug
- Detect more processes via auto
- Make position axes affected by deadzone
- Use steam runtime env when in standalone
- Get rid of pyopengl dependency
- Fix vdf error
- Add wider linux cross-distro compatibility (compiled on older system)
- Detect Steam launch dynamically
