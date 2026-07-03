

## Installation
### Disabling MS Login
Method 1: The 'BypassNRO' Command (Most Reliable)
This command modifies the installer to let you skip internet connectivity and log in offline.
1. Unplug your ethernet cable or disconnect from your Wi-Fi network when you reach the network setup screen.
2. Press Shift + F10 on your keyboard (on some laptops, you may need to press Fn + Shift + F10) to open the Command Prompt.
3. Type oobe\bypassnro and press Enter.
4. Your computer will restart automatically.
5. Proceed through the setup again. When you get to the "Let's connect you to a network" screen, select the "I don't have internet" option.
6. Click "Continue with limited setup" to create your local username and password.



## Settings App
### System
- Advanced > End Task (in Taskbar) -> On
- Advanced > File Explorer > Show File Extensions -> On
- Advanced > File Explorer > Show Hidden and System Files -> On
- Advanced > File Explorer > Show Full Path in Title Bar -> On
- Advanced > File Explorer > Show Option to Run As Different User in Start -> On
- Advanced > Terminal -> Windows Terminal
- Advanced > PowerShell > Change execution policy to allow local scripts -> On
- Advanced > Enable Sudo -> On
### Personalization
- Background > Personalize your background -> Solid Color (and choose one)
- Colors > Choose your mode -> Dark
- Colors > Accent Color -> Choose One
- Colors > Show Accent Color on Start and Taskbar -> On
- Colors > Show Accent Color on Title bar and window borders -> On
- Lock Screen > Personalize your lock screen -> Picture
- Lock Screen > Personalize your lock screen > Get Fun Facts... -> Off
- Lock Screen > Lock Screen Status -> None
- Lock Screen > Show Lock Screen sign-in picture on the startup screen -> Off
- Start > Show Recently Added Apps -> Off
- Start > Show Recommended Files... -> Off
- Start > Show Recommendations... -> Off
- Start > Show account-related notifications -> Off
- Start > Folders > Settings -> On
- Taskbar > Search -> Hide
- Taskbar > Task View -> Off
- Taskbar > Widgets -> Off
- Taskbar > Resume -> Off
- Taskbar > Other System Tray Icons -> REQUIRES CUSTOMIZATION
### Apps
- Actions > Microsoft 365 Copilot -> Off
- Startup > Microsoft 365 Copilot -> Off
- Startup > Microsoft OneDrive -> Off
#### Installed Apps to Remove
- Feedback Hub
- Microsoft 365 Copilot
- Microsoft ClipChamp
- Microsoft OneDrive
- Microsoft Teams
- Microsoft ToDo
- News
- Weather
- Xbox Live
### Gaming
- Game Bar > Allow Controller to Open Game Bar -> Off
### Accessibility
- Visual Effects > Transparency Effects -> Off
- Visual Effects > Animation Effects -> Off
### Privacy and Security
- Recommendations and Offers > Personalized Offers -> Off
- Recommendations and Offers > Improve Start and Search Results -> Off
- Recommendations and Offers > Show Notifications in Settings -> Off
- Recommendations and Offers > Recommendations and Offers in Settings -> Off
- Recommendations and Offers > Advertising ID -> Off
- Speech > Online -> Off
- Diagnostics and Feedback > Send Optional Diagnostic Data -> Off
- Diagnostics and Feedback > Improve Inking and Typing -> Off
- Search > Search History -> Off
- Search > Show search highlights -> Off
- Search > Search my accounts -> Off
- Location > Off

## Miscellaneous
### Start Menu
- Remove LinkedIn
- Remove WhatsApp

## CTT Winutil
```irm https://christitus.com/win | iex```
### Tweaks
- Essential Tweaks > ConsumerFeatures Disable -> On
- Essential Tweaks > Delivery Optimization Disable -> On
- Essential Tweaks > End Task with Right Click Enable -> On
- Essential Tweaks > Location Tracking Disable -> On
- Essential Tweaks > Microsoft Store Recommended Search Results Disable -> On
- Essential Tweaks > Telemetry Disable -> On
- Advanced Tweaks > Visual Effects Set to Best Performance -> On
- Advanced Tweaks > Windows AI Disable and Remove -> On
- Run Tweaks
- Customize Preferences > BSoD Verbose Mode -> On
- Customize Preferences > Logon Verbose Mode -> On


## VM Specific
### Common
1. Disable Windows Hello (Settings > Accounts > Sign-in Options > "For improved security, only allow Windows Hello sign-in for Microsoft accounts on this device (Recommended)." -> Off
### UTM
### Hyper-V
