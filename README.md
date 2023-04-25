# Multiplayer TicTacToe Game

###  Team members name 

   1. Vishal Nannore
   2. Srushti Khatri
   3. Palak Kakani
   
A completely Responsive Multiplayer TicTacToe Game- Works on Android, iOS, Web & Desktop! 
<p align="center">
  <img width="600" src="https://github.com/vishalnannore/multiplayer-tic-tac-toe/blob/main/screenshot.png" alt="Youtube Tutorial Image">
</p>

## Features
- Create/Join Room
- Play Realtime
- Display Points
- Round & Game Winner
- Responsive Glow Themed UI
- Cross Platform Game

## Getting Started

For help getting started with Flutter, view our online
[documentation](https://flutter.io/).

To clone this project,

open your terminal or cmd

```
git clone https://github.com/vishalnannore/multiplayer-tic-tac-toe.git
```

Then 
locate the project on your system and open with android studio


## Prerequisites

What things you need to install the software and how to install them

```
* Android Studio
* Java JDK 8+
* Android SDK
* Flutter SDK
```

## To set up an emulator
* Select Run > Run 'app'
* Click 'Create New Emulator'
* Select the device you would like to emulate (Recommended: pixel xl2)
* Select the API level you would like to run - click 'Download' if not available (Recommended: Marshmallow - ABI: x86)
* Select configuration settings for emulator
* Click 'Finish' and allow Emulator to run

## To Run on an Android OS Device
* Connect the device to the computer through its USB port
* Make sure USB debugging is enabled (this may pop up in a window when you connect the device or it may need to be checked in the phone's settings)
* Select Run > Run 'app'
* Select the device (If it does not show, USB debugging is probably not enabled)
* Click 'OK'


## Installation
After cloning this repository, migrate to ```multiplayer-tic-tac-toe``` folder.

Install dependencies (Client Side)
```bash
flutter pub get
```

Install dependencies (Server Side)

```bash
cd server && npm install
```

Start the server

```bash
npm run dev
```

Configure for MacOS:
Head to macos/Runner and make sure the following keys are present in DebugProfile.entitlements and Release.entitlements
```bash
<key>com.apple.security.network.server</key>
<true/>
<key>com.apple.security.network.client</key>
<true/>
```

Run App
```bash
flutter run // After selecting the device you want to test on
```

## Tech Used
**Server**: Node.js, Express, Socket.io, Mongoose, MongoDB

**Client**: Flutter, Provider
    
## Built With

* [Android Studio](https://developer.android.com/studio/install) - How to install Android Studio
* [Flutter](https://flutter.io/get-started/install/) - Getting started with Flutter


