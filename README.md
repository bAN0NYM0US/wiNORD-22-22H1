# Nordic Windows 11 21H2 Pro 22000.593

# Known Issues
Due to the known issue with the clock being cut off when the taskbar size is set to small, it is broken by design in this project as it is intended to be replaced with Start 11. This will fix the clock issue as well as providing the ability to remove "Recommended" section from the Start Menu, as well as additional transparancy settings.

# Changelog

## [v0.1] - Windows 10 LTSC IoT 19044.1620
	### Added
		- Brave Browser
		- VLC Media Player
		- C:/NORD Directory
			- AutoDarkMode
			- Font
				- Source Code Pro Fonts
				- Registry file to enable font as system default
			- Cursor
				- Nord/CakeOS
			- SecureUX Patcher
		- Embedded Nord Light/Dark Theme to C:\Windows\Resources\Themes
		- Added more nordic wallpapers
    - Stock Windows 11 wallpaper with Nord colour pallet to C:\Windows\Web\Wallpaper\Windows
    - Blured stock Windows 11 wallpaper with Nord colour pallet to C:\Windows\Web\Screen

	### Changed
		- Setup boots directly to Drive Selection (details under ### Removed/Setup)
		- OOBE boots directly to Local Account setup (details under ### Removed/Setup)
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
