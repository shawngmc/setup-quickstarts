

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
### Install
- Install UniGetUI
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

## O&O Shut Up
### Current User

#### Privacy
- Disable and reset Advertising ID and info -> On
- Disable transmission of typing information -> On
- Disable suggestions in the timeline -> On
- Disable suggestions in Start Disable tips, tricks, and suggestions when using Windows -> On
- Disable showing suggested content in the Settings app -> On
- Disable the possibility of suggesting to finish the setup of the device -> On
#### Activity History and Clipboard
- Disable Storage of Clipboard History -> On
#### App Privacy
- Disable App Access to user account information -> On
- Disable Windows Tracking of app starts -> On
- Disable App Access to diagnostic information -> On
#### Microsoft Edge (new version based on Chromium)
- Disable tracking in the web -> On
- Disable check for saved payment methods by sites -> On
- Disable personalizing advertising, search, news and other services -> On
- Disable automatic completion of web addresses in address bar -> On
- Disable user feedback in toolbar Disable storing and autocompleting of credit card data on websites -> On
- Disable form suggestions Disable suggestions from local providers -> On
- Disable search and website suggestions -> On
- Disable shopping assistant in Microsoft Edge -> On
- Disable Edge bar -> On
- Disable Sidebar in Microsoft Edge -> On
- Disable Enhanced Spell Checking -> On
- Hide first run experience and splash screen -> On
- Disable spotlight experiences and recommendations -> On
- Disable automatic sign-in from web to browser -> On
- Disable Bing Chat on new tab page -> On
- Disable content on new tab page -> On
- Disable Al-generated themes -> On
- Disable built-in Al APIs for websites -> On
- Disable inline Compose feature -> On
- Disable Copilot access to page context -> On
- Disable prompts to make Edge the default browser -> On
- Disable default browser campaigns -> On
- Disable diagnostic data collection -> On
- Disable shopping assistant -> On
- Hide Microsoft 365 Copilot chat icon -> On
- Hide Microsoft Rewards -> On
- Disable recommendations in settings -> On
- Disable cloud-based tab services -> On
- Disable text prediction in forms -> On
- Disable visual search -> On
- Disable Al-powered history search -> On
- Disable Edge Secure Network (built-in VPN) -> On
- Allow user control of local Al features -> On
- Disable use of web service to resolve navigation errors -> On
- Hide default top sites on new tab page -> On
- Hide Adobe Acrobat subscription button -> On
#### Microsoft Edge (legacy version)
- Disable tracking in the web -> On
- Disable Page Prediction -> On
- Disable Search and Website Suggestions -> On
- Disable Cortana in Microsoft Edge -> On
- Disable Showing Search History -> On
#### Synchronization of Windows Settings 
- Disable synchronization of all settings -> On
- Disable synchronization of design settings -> On
- Disable synchronization of browser settings -> On
- Disable synchronization of credentials (passwords) -> On
- Disable synchronization of language settings -> On
- Disable synchronization of accessibility settings -> On
- Disable synchronization of advanced Windows settings-> On
#### Cortana (Personal Assistant) 
- Disable and reset Cortana -> On
- Disable Input Personalization -> On
#### Copilot & Windows AI
- Disable the Windows Copilot -> On
- Disable the Copilot button from the taskbar -> On
- Disable Bing Chat eligibility in Windows Copilot -> On
- Disable Windows Copilot+ Recall -> On
#### User Behavior 
- Disable diagnostic data from customizing user experiences -> On
#### Windows Explorer 
- Disable occassionally showing app suggestions in Start menu -> On
- Do not show recently opened items in Jump Lists on "Start" or the taskbar -> On
- Disable ads in Windows Explorer/OneDrive -> On
#### Lock Screen 
- Disable Windows Spotlight -> On
- Disable fun facts, tips, tricks, and more on your lock screen -> On
- Disable notifications on lock screen -> On
#### Mobile Devices 
- Disable access to mobile devices -> On
- Disable Phone Link app -> On
- Disable showing suggestions for using mobile devices with Windows -> On
#### Search
- Disable search with Al in search box -> On
- Disable extension of Windows search with Bing -> On
#### Taskbar
- Disable search box in task bar -> On
- Disable People icon in the taskbar -> On
- Disable "Meet now" in the task bar -> On
#### Miscellaneous
- Disable feedback reminders -> On
- Disable automatic installation of recommended Windows Store Apps -> On
- Disable tips, tricks, and suggestions while using Windows -> On
- Disable Windows Media Player Diagnostics -> On
- Disable the desktop icon for information on "Windows Spotlight" -> On

### Local Machine
#### Privacy
- Disable sharing of handwriting data -> On
- Disable sharing of handwriting error reports -> On
- Disable Inventory Collector -> On
- Disable camera in logon screen -> On
- Disable and reset Advertising ID and info -> On
- Disable advertisements via Bluetooth -> On
- Disable the Windows Customer Experience Improvement Program -> On
- Disable backup of text messages into the cloud -> On
- Disable Windows Error Reporting -> On
- Disable biometrical features -> On
#### Activity History and Clipboard
- Disable recordings of user activity -> On
- Disable storing users' activity history -> On
- Disable the submission of user activities to Microsoft -> On
- Disable storage of clipboard history -> On
- Disable the transfer of the clipboard to other devices via the cloud -> On
#### App Privacy
- Disable app access to user account information -> On
- Disable app access to diagnostics information -> On
- Disable app access to device location -> On
#### Security
- Disable password reveal button -> On
- Disable user steps recorder -> On
- Disable telemetry -> On
#### Microsoft Edge (new version based on Chromium)
- Disable tracking in the web -> On
- Disable check for saved payment methods by sites -> On
- Disable personalizing advertising, search, news and other services -> On
- Disable automatic completion of web addresses in address bar -> On
- Disable user feedback in toolbar -> On
- Disable storing and autocompleting of credit card data on websites -> On
- Disable form suggestions -> On
- Disable suggestions from local providers -> On
- Disable search and website suggestions -> On
- Disable shopping assistant in Microsoft Edge -> On
- Disable Edge bar -> On
- Disable Sidebar in Microsoft Edge -> On
- Disable Enhanced Spell Checking -> On
- Hide first run experience and splash screen -> On
- Disable spotlight experiences and recommendations -> On
- Disable automatic sign-in from web to browser -> On
- Disable Bing Chat on new tab page -> On
- Disable content on new tab page -> On
- Disable Al-generated themes -> On
- Disable built-in Al APIs for websites -> On
- Disable inline Compose feature -> On
- Disable Copilot access to page context -> On
- Disable prompts to make Edge the default browser -> On
- Disable default browser campaigns -> On
- Disable diagnostic data collection -> On
- Disable shopping assistant -> On
- Hide Microsoft 365 Copilot chat icon -> On
- Hide Microsoft Rewards -> On
- Disable recommendations in settings -> On
- Disable cloud-based tab services -> On
- Disable text prediction in forms -> On
- Disable visual search -> On
- Disable Al-powered history search -> On
- Disable Edge Secure Network (built-in VPN) -> On
- Allow user control of local Al features -> On
- Disable use of web service to resolve navigation errors -> On
- Disable suggestion of similar sites when website cannot be found -> On
- Hide default top sites on new tab page -> On
- Hide Adobe Acrobat subscription button -> On
#### Microsoft Edge (legacy version)
- Disable automatic completion of web addresses -> On
#### Cortana (Personal Assistant)
- Disable online speech recognition -> On
- Cortana and search are disallowed to use location -> On
- Disable web search from Windows Desktop Search -> On
- Disable display web results in Search -> On
- Disable download and updates of speech recognition and speech synthesis models -> On
- Disable cloud search -> On
- Disable Cortana above lock screen -> On
- Disable the search highlights in the taskbar -> On
#### Copilot & Windows Al
- Disable the Windows Copilot -> On
- Disable the provision of recall functionality to all users -> On
- Disable the Image Creator in Microsoft Paint -> On
- Disable Windows Copilot+ Recall -> On
- Disable Cocreator in Microsoft Paint -> On
- Disable Al-powered image fill in Microsoft Paint -> On
#### Location Services
- Disable functionality to locate the system -> On
- Disable scripting functionality to locate the system -> On
- Disable sensors for locating the system and its orientation -> On
- Disable Windows Geolocation Service -> On
#### User Behavior
- Disable application telemetry -> On
- Disable diagnostic data from customizing user experiences -> On
- Disable diagnostic log collection -> On
- Disable downloading of OneSettings configuration settings -> On
#### Windows Update
- Disable Windows Update via peer-to-peer -> On
- Disable updates to the speech recognition and speech synthesis modules -> On
#### Windows Explorer
- Disable OneDrive access to network before login -> On
- Disable Microsoft OneDrive -> On
#### Mobile Devices
- Disable connection to PC to mobile devices -> On
#### Taskbar
- Disable People icon in the taskbar -> On
- Disable "Meet now" in the task bar -> On
#### Miscellaneous
- Disable feedback reminders -> On
- Disable remote assistant connections to this computer -> On
- Disable remote conenctions to this computer -> On
#### Gaming
- Disable Xbox Game Bar and DVR -> On

### AI
- The copilot functionality is activated and data can be recorded.

## Apps via UniGetUI
### Basic Set For All Machines
```
Clear-Host
Write-Host ""
Write-Host "========================================================"
Write-Host ""
Write-Host "        __  __      _ ______     __  __  ______" -ForegroundColor Cyan
Write-Host "       / / / /___  (_) ____/__  / _// / / /  _/" -ForegroundColor Cyan
Write-Host "      / / / / __ \/ / / __/ _ \/ __/ / / // /" -ForegroundColor Cyan
Write-Host "     / /_/ / / / / / /_/ /  __/ /_/ /_/ // /" -ForegroundColor Cyan
Write-Host "     \____/_/ /_/_/\____/\___/\__/\____/___/" -ForegroundColor Cyan
Write-Host "          UniGetUI Package Installer Script"
Write-Host "        Created with UniGetUI Version 2026.2.2"
Write-Host ""
Write-Host "========================================================"
Write-Host ""
Write-Host "NOTES:" -ForegroundColor Yellow
Write-Host "  - The install process will not be as reliable as importing a bundle with UniGetUI. Expect issues and errors." -ForegroundColor Yellow
Write-Host "  - Packages will be installed with the install options specified at the time of creation of this script." -ForegroundColor Yellow
Write-Host "  - Error/Success detection may not be 100% accurate." -ForegroundColor Yellow
Write-Host "  - Some of the packages may require elevation. Some of them may ask for permission, but others may fail. Consider running this script elevated." -ForegroundColor Yellow
Write-Host "  - You can skip confirmation prompts by running this script with the parameter `/DisablePausePrompts` " -ForegroundColor Yellow
Write-Host ""
Write-Host ""
if ($args[0] -ne "/DisablePausePrompts") { pause }
Write-Host ""
Write-Host "This script will attempt to install the following packages:"
Write-Host "  - Google Chrome from WinGet"
Write-Host "  - 7-Zip from WinGet"
Write-Host "  - Mozilla Firefox (en-US) from WinGet"
Write-Host "  - Microsoft Visual Studio Code from WinGet"
Write-Host "  - Tabby from WinGet"
Write-Host "  - MPV (Official CI build, MSVC) from WinGet"
Write-Host "  - ungoogled-chromium from WinGet"
Write-Host "  - Bitwarden from WinGet"
Write-Host ""
if ($args[0] -ne "/DisablePausePrompts") { pause }
Clear-Host

$success_count=0
$failure_count=0
$commands_run=0
$results=""

$commands= @(
    'winget.exe install --id "Google.Chrome" --exact --source winget --accept-source-agreements --disable-interactivity --silent --accept-package-agreements --force',
    'winget.exe install --id "7zip.7zip" --exact --source winget --accept-source-agreements --disable-interactivity --silent --accept-package-agreements --force',
    'winget.exe install --id "Mozilla.Firefox" --exact --source winget --accept-source-agreements --disable-interactivity --silent --accept-package-agreements --force',
    'winget.exe install --id "Microsoft.VisualStudioCode" --exact --source winget --accept-source-agreements --disable-interactivity --silent --accept-package-agreements --force',
    'winget.exe install --id "Eugeny.Tabby" --exact --source winget --accept-source-agreements --disable-interactivity --silent --accept-package-agreements --force',
    'winget.exe install --id "mpv-player.mpv-CI.MSVC" --exact --source winget --accept-source-agreements --disable-interactivity --silent --accept-package-agreements --force',
    'winget.exe install --id "eloston.ungoogled-chromium" --exact --source winget --accept-source-agreements --disable-interactivity --silent --accept-package-agreements --force',
    'winget.exe install --id "Bitwarden.Bitwarden" --exact --source winget --accept-source-agreements --disable-interactivity --silent --accept-package-agreements --force'
)

foreach ($command in $commands) {
    Write-Host "Running: $command" -ForegroundColor Yellow
    cmd.exe /C $command
    if ($LASTEXITCODE -eq 0) {
        Write-Host "[  OK  ] $command" -ForegroundColor Green
        $success_count++
        $results += "$([char]0x1b)[32m[  OK  ] $command`n"
    }
    else {
        Write-Host "[ FAIL ] $command" -ForegroundColor Red
        $failure_count++
        $results += "$([char]0x1b)[31m[ FAIL ] $command`n"
    }
    $commands_run++
    Write-Host ""
}

Write-Host "========================================================"
Write-Host "                  OPERATION SUMMARY"
Write-Host "========================================================"
Write-Host "Total commands run: $commands_run"
Write-Host "Successful: $success_count"
Write-Host "Failed: $failure_count"
Write-Host ""
Write-Host "Details:"
Write-Host "$results$([char]0x1b)[37m"
Write-Host "========================================================"

if ($failure_count -gt 0) {
    Write-Host "Some commands failed. Please check the log above." -ForegroundColor Yellow
}
else {
    Write-Host "All commands executed successfully!" -ForegroundColor Green
}
Write-Host ""
if ($args[0] -ne "/DisablePausePrompts") { pause }
exit $failure_count
```


## VM Specific
### Common
1. Disable Windows Hello (Settings > Accounts > Sign-in Options > "For improved security, only allow Windows Hello sign-in for Microsoft accounts on this device (Recommended)." -> Off
### UTM
### Hyper-V



## TODO: Additional Windows 11 Performance Tweaks - need evaluated

### Services (services.msc)
- [ ] Disable/set to Manual: SysMain (Superfetch) — test on SSD
- [ ] Disable/set to Manual: DiagTrack (Connected User Experiences and Telemetry)
- [ ] Disable/set to Manual: Windows Search (if unused, esp. on VM disks)
- [ ] Disable/set to Manual: Print Spooler (if no printer)
- [ ] Disable/set to Manual: Fax
- [ ] Disable/set to Manual: Downloaded Maps Manager
- [ ] Disable/set to Manual: Remote Registry

### Startup Apps
- [ ] Review Task Manager > Startup apps tab (separate from Settings > Apps > Startup)

### Power Plan
- [ ] Set Ultimate/High Performance plan, or Settings > System > Power > "Best Performance"
- [ ] Disable USB selective suspend (if peripheral issues)

### Fast Startup / Hibernation
- [ ] Run `powercfg /h off` to disable hibernation + Fast Startup

### Storage
- [ ] Enable Storage Sense (Settings > Storage)

### Windows Optional Features to Remove
- [ ] Internet Explorer mode
- [ ] Media Features
- [ ] XPS Viewer
- [ ] Windows Fax and Scan
- [ ] Steps Recorder
- [ ] Work Folders Client

### Search Indexing
- [ ] Control Panel > Indexing Options — exclude unused drives/folders (esp. VM virtual disks)

### Background Apps
- [ ] Settings > Apps > Installed apps — review per-app "let this app run in background"

### Windows Defender
- [ ] Schedule scans for idle hours
- [ ] (Optional, security tradeoff) Add exclusions for dev/build folders

### GPU / Game Bar
- [ ] Enable Hardware-Accelerated GPU Scheduling (Settings > Display > Graphics)
- [ ] Fully disable Game Bar/Game DVR (not just controller-launch)

### VM Specific (fill out empty sections in main doc)
- [ ] Disable Windows Update auto-restart scheduling in VMs
- [ ] Use fixed-size VHD/VHDX instead of dynamically-expanding
- [ ] Enable Hyper-V enhanced session mode
- [ ] Install/verify VirtIO or UTM guest tools for disk + network throughput
- [ ] Right-size vCPU/RAM to actual host headroom (avoid over-provisioning)