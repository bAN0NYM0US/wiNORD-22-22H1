# Nordic Windows 11 Pro 22000.593

![alt text](https://i.imgur.com/dwgVPXF.png?raw=true)

# Known Issues
Due to the known issue with the clock being cut off when the taskbar size is set to small, it is broken by design in this project as it is intended to be replaced with Start 11. This will fix the clock issue as well as providing the ability to remove "Recommended" section from the Start Menu, as well as additional transparancy settings.

# Manual Procedure
Font:

Navigate to C:\NORD and manually install the Source Code Pro font (select all, right-click, install). Once complete, run the .reg file to set it as the system font (reboot is required).

Theme:

Navigate to C:\NORD and Right-click ThemeTool.exe, open as administrator, Click "Yes". Click the "Install" Button and reboot. Repeat steps for opening ThemeTool.exe and now select the Nord Dark Theme and click "Patch & Apply".

Additional Info:

You will need to run the font .reg file, and Applying the Nord theme with ThemeTool.exe after every major Windows Update.

# Changelog

## [v0.1] - Windows 11 Pro 21H2 22000.593
	### Added
		- Brave Browser
		- VLC Media Player
		- C:/NORD Directory
			- Font
				- Source Code Pro Fonts
				- Registry file to enable font as system default
			- Cursor
				- Nord/CakeOS
			- SecureUX Patcher
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
		- Taskbar set to Small (taskbar clock issue is know, with no fix)
		- This PC as Default for File Explorer
		- Windows 10 context menu

	### Fixed
		- Embedded TPM 2.0 Bypass
    
	### Removed
		- Setup:
			- Language Select
			- EULA
			- Product Key Input/Version Select
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
