# Nordic Minimalist Windows 11 Pro 22000.593

![alt text](https://i.imgur.com/dwgVPXF.png?raw=true)

# Known Issues
- Due to the known issue with the clock being cut off when the taskbar size is set to small, it is broken by design in this project, as it is intended to be replaced with Start 11. This will fix the clock issue as well as providing the ability to remove "Recommended" section from the Start Menu, and additional transparancy settings.

- Nord Theme Light Mode does not work.

- Maximizing a Window does not work correctly. You need to Maximize, Minimise to Taskbar, and Click it again for it to go full screen.
	This is an issue with SecureUX Patcher, nothing can be done until the programme is updated for Windows 11.

# Install Procedure
ISO will boot directly to the Drive Selection screen. Pick a drive/partition and install. Once install is complete, OOBE will load. If you don't have direct internet access, you will be asked to connect to wifi first. If you have direct access, OOBE will load directly to Local Account. Enter a username and password. Everything will finish up and you will be at the Desktop. (slower computer may see the Post-Setup screen still going, but this is normally done in the backgorund before the desktop loads on faster machines). Don't be alarmed, this is just removing Edge, installing Brave and VLC.

# Manual Procedure
Post-install instructions can be found in C:\NORD\Install Guide.txt

Additional Info:

You will need to run the font .reg file, and reapply the Nord theme with ThemeTool.exe after every major Windows Update.

# Downloads
## [wiNORD 22000.593](http://usheethe.com/ksw2)
This is NOT activated. You will need to activate this with a Pro Product Key or, for EDUCATIONAL PURPOSE use [EzHWID](https://github.com/ExeCsrss/EzHWID)

[Nord Colour Stock Wallpapers](http://usheethe.com/ksxJ)

# Changelog

## Windows 11 Pro 21H2 22000.593
	### Added
		- Brave Browser
		- VLC Media Player
		- C:/NORD Directory
			- Font
				- Source Code Pro
				- Registry file to enable font as system default
			- Cursor
				- Nord/Oreo/CakeOS
			- SecureUxTheme
		- Embedded Nord Dark Theme to C:\Windows\Resources\Themes
		- Added more nordic wallpapers
   		- Alternative Windows 11 wallpaper with Nord colour pallet to C:\Windows\Web\Wallpaper\Windows
 		- Blured alternative Windows 11 wallpaper with Nord colour pallet to C:\Windows\Web\Screen

	### Changed
		- Setup boots directly to Drive Selection (details under ### Removed/Setup)
		- OOBE boots directly to Local Account setup (details under ### Removed/OOBE)
		- Default UI to Full Dark Mode
		- EST Time Zone as Default
		- US English as Default
		- Taskbar set to Small (taskbar clock issue is know, start11 is the fix)
		- This PC as Default for File Explorer
		- Windows 10 context menu

	### Fixed
		- Embedded TPM 2.0 Bypass
    
	### Removed
		- Setup:
			- Language Select
			- EULA
			- Version Select
		- OOBE:
			- Language/Region
			- Keyboard Select
			- Online Account
			- Telemetry Switches
		- Microsoft Edge
		- Microsoft Telemetry
		- Recommended Apps & Settings
		- Quick Access from File Explorer
		- Language Packs
		- Windows Media Player
		- Taskbar:
			- Task View
			- Teams/Chat
			- Notification Centre
			- Search
			- People

# Contributions
	- Nord Theme by niivu
		https://www.deviantart.com/niivu/art/Nord-Windows-10-Theme-837266272
	- CakeOS Cursor by niivu
		https://www.deviantart.com/niivu/art/cakeOS-Cursors-760664795
	- Nord Cursor by Abod1960
		https://www.deviantart.com/abod1960/art/Nord-Cursor-887885140
	- Nord Oreo by Abod1960
		https://www.deviantart.com/abod1960/art/Oreo-Nord-875312546
	- Wallpapers in Nord Theme by Anonymous
		http://4chan.org/wg
	- Source Code Pro Font by Paul D. Hunt
		https://github.com/adobe-fonts/source-code-pro
	- Windows 11 by Microsoft
		https://www.microsoft.com/en-ca/software-download/windows11
	- Start 11 by Stardock
		https://www.stardock.com/products/start11/
	- SecureUxTheme by namazso
		https://github.com/namazso/SecureUxTheme
