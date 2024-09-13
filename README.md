# c3addon-ide-plus

## This is a list of features not documentation.

## Support system
> [!WARNING]  
> - Windows 10 | 11 (86_64)
> - Mac OS X 10.9 or later
> - Linux


> [!IMPORTANT] 
> - Although this tool is offline, 
> - But in this beta release some dependencies such as icons still use CDN, 
> - [font-awesome ](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css)
> - [boxicons ](https://unpkg.com/boxicons@2.1.1/css/boxicons.min.css)
> - So it requires a connection and a little time to load.


# Construct 3 SDK V2:
Reference layout, function and condition, 
made based on https://github.com/armandoalonso/c3IDE


> [!IMPORTANT]  
> - Currently only supporting [singleGlobalPlugin ](https://github.com/Scirra/Construct-Addon-SDK/tree/main/plugin-sdk/v2/singleGlobalPlugin)
## Create New c3addon 
> [!WARNING]  
> When Create New Addon (JS/TS) script type: typescript the ts file content is automatically converted to js.
> - example tool logic 
> - `const ts = require('typescript'); // dependency`
> - `editor path/instance.ts auto convert path/instance.js`
> - `editor path/actions.ts auto convert path/actions.js`




> [!IMPORTANT]
> # Tool 1 (Construct 3 SDK V2)
- Drag & Drop c3addon files here SDK V2
- Drag & Drop c3addon SDK V1 PORTING TO ADDON SDK V2 (only Plugin singleGlobalPlugin or DOM plugin)
- Editor auto suggestions API c3addon SDK: [Request ](https://github.com/EMI-INDO/c3addon-ide-plus/blob/main/suggestions)
- Editor auto this._triger(auto_addonId.auto.cnds.id) (shift + alt + s)
> [!IMPORTANT]  
> (Auto Backup: aces.json, lang.json) 
> - Auto Backup Remove Addon
> - Auto Backup Remove ACE
> - Auto Backup Remove ACE Params


## Pannel c3addon Lab test:

**C3addon build Group**
- Update addon version
- Build Addon

**Server Group**
- Custom Port (8000 - 8999)
- Update port
- Start All server: Server list localhost:randomPort/addonName/addon.json
- Stop All server

**GitHub Group**
- Repositories c3addon Name Readonly
- Url c3addon Repositories
- Create c3addon GitHub Repository
- Add c3addon Project to Repository
- Push c3addon to Repository


## GitHub Pannel API:
**GitHub API Settings**
- github-user-name
- Personal access tokens: ghp_xxxxxxxxx

## NPM Pannel:
- Login 
- Add
- Update
- Clone

## Open AI API Pannel:
**OpenAi API Settings**
- API Key: sk-proj-xxxxxxxxxxxxxxxxxxxx
- Model: dropdown
- Max Tokens
- Temperature

- ## Gemini AI Pannel: hide
-



> [!WARNING]
> - # Tool 2 (Cordova Build Management)
> - ### Dependencies (Cordova Build Management), 
> - If your Cordova project can be built using the Cordova CLI you can use this function directly.
> - Otherwise you must confirm the dependency below.

> - [Cordova CLI ](https://cordova.apache.org/docs/en/12.x/guide/cli/installation.html)
> - [Node.js ](https://nodejs.org/en/download/prebuilt-installer)
> - [Android Studio (manual install)](https://developer.android.com/studio)
> - [Android SDK Only bundle (Just set the path, then you can use it) ](https://onedrive.live.com/?redeem=aHR0cHM6Ly8xZHJ2Lm1zL3UvYy9iNGNjNGQxYWU1NzY3MGQwL0VkQndkdVVhVGN3Z2dMVGdBQUFBQUFBQlg2NG1JeXBuMWc3ZVhSUi1oRVdBVnc&cid=B4CC4D1AE57670D0&id=B4CC4D1AE57670D0%21224&parId=B4CC4D1AE57670D0%21223&o=OneUp)
> - [Java JDK 17+ ](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
> - [Gradle 8.7 ](https://gradle.org/releases/)


> [!IMPORTANT]
> ## In the stable version
> Users who are not familiar with the Cordova CLI will have no trouble because
> all separate dependencies are no longer needed,
> everything is handled by this tool,
> Because this tool already has its own dependency Management Pannel.
- Cordova Management (Environment Variables Automatic)
- SDK Android Management (Environment Variables Automatic)
- JAVA JDK Management (Environment Variables Automatic)
- Gradle Management (Environment Variables Automatic)

> [!IMPORTANT]
> ## Features
- Android Debug Apk/Aab Builds (unlimited)
- Android Release APK Builds (unlimited)
- Android Release AAB Builds (unlimited)
- Run Android Emulator (Stable release)
- NPM Plugins (unlimited)
- GitHub Plugins (unlimited)
- Custom Plugins (unlimited)
- Builds/Day. (unlimited)
- Maximum Size (unlimited)

- IOS Run Simulator Builds (unlimited)
- IOS Debug Builds (unlimited)
- IOS Release Builds (unlimited)
- Open/edit pod file
- pod install
- Open project with xcode

## Project Management:

- Plugin Management
- Platforms Management
- Search for Cordova plugin
- Cordova plugin add | remove
- Cordova Platform add | remove
- Terminal/CMD
- Cordova Project list (unlimited)
- Drag and Drop Cordova project zip
- log output

> [!IMPORTANT]
> # Tool 3 (Editor Cordova Project)
> Double-click the file to be edited.  
- Editor Cordova Project list (unlimited)
- Pannel editor on the right
- Add File
- Add Folder
- View Project
- Save
- Move folder/file (drag and drop)
- Delete project/file
- Language: Editor All


 > [!IMPORTANT]
> # Tool 4 (Create New Cordova Plugin) 
> Double-click the file to be edited.
- Pannel editor on the right
- Add File
- Add Folder
- Save
- Move folder/file (drag and drop)
- Delete project/file
> __Language: Editor__
 - java
 - koltin
 - objctive-c
 - swift
 - js 
 - ts
 - json
 - html
 - css

> [!IMPORTANT]
> # Tool 4 (Android KeyStore Pannel)
- Create New Android Keystore
- Generate SHA Key
> [!IMPORTANT]  
> Hash Algorithm
- SHA-1
- SHA-256




