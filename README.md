<p align="center">
  <img width="200" height="200" src="https://raw.githubusercontent.com/Nicklas373/M.A.O/master/M.A.O.png"><br>
</p>

<p align="center">
  <b>M.A.O</b><br>
  <b>Mido Audio Optimizer</b><br>
</p>

M.A.O is application that can control current exist audio features on kernel directly and show current audio media flinger status that running on device when play a song or not from audioserver service on android.
M.A.O work by using shell command that will dump active android mediaflinger from system and sort it by category then detect it each current state.
M.A.O should work on android 10.0 with latest Android Audio API, not sure for older Android Audio API from android below than Android 10.0.

# Project Status
![Build](https://travis-ci.org/Nicklas373/M.A.O.svg?branch=master) ![Dev](https://img.shields.io/badge/Development%20Phase-W.I.P-yellow.svg) ![Version](https://img.shields.io/badge/Latest%20Version-10th%20Phase-yellow) ![Package](https://img.shields.io/badge/Package-Android%20App-blue.svg)

M.A.O will show only exist kernel audio feature configuration on the device, so not all audio feature will show same in all ROMs. M.A.O is app for extension from [M.A.O Magisk Module](https://github.com/Nicklas373/Internal_DAC_Fixer) to optimize that module functionallity

What's features that available to control:
- Headset High Perfomance Mode (HPH v2)
- Ultra High Quality Audio Mode (UHQA Mode)
- Low Distortion AMP
- Headphone Impedance Detection
- Qualcomm Power Gating (BiQuads Filter Workaround)

What's audio status that can be show:
- Sample Rate (Variable rate from device)
- Bit Depth (Float, 16 bit , 24 bit (Digital or Analog), 32 bit)
- Audio Flags (DIRECT, DEEP BUFFER, FAST|PRIMARY, RAW)
- Audio Out (Headset, Speaker, Headphone, Line Out)
- HAL Buffer Size (Variable size from device)

NOTE : 
- this app is need root access
- minimum requirement is android 7.0 (API 24)
- Not all features on kernel will show on app, only exist features that will show
- audio state and features will get refreshed when activity is restart, it work by dump value on kernel not based on sharedpreferences.
       
Current Build :
- Build 20190503 (WIP)
- Build 20190505 (WIP 2nd Phase)
- Build 20190508 (WIP 3rd Phase)
- Build 20190509 (WIP 4th Phase)
- Build 20190513 (WIP 5th Phase)
- Build 20190515 (WIP 6th Phase)
- Build 20190516 (WIP 7th Phase)
- Build 20190630 (WIP 8th Phase)
- Build 20190725 (WIP 9th Phase)
- Build 20200317 (WIP 10th Phase)

# Contributor
[![](https://sourcerer.io/fame/Nicklas373/Nicklas373/M.A.O/images/0)](https://sourcerer.io/fame/Nicklas373/Nicklas373/M.A.O/links/0)[![](https://sourcerer.io/fame/Nicklas373/Nicklas373/M.A.O/images/1)](https://sourcerer.io/fame/Nicklas373/Nicklas373/M.A.O/links/1)[![](https://sourcerer.io/fame/Nicklas373/Nicklas373/M.A.O/images/2)](https://sourcerer.io/fame/Nicklas373/Nicklas373/M.A.O/links/2)[![](https://sourcerer.io/fame/Nicklas373/Nicklas373/M.A.O/images/3)](https://sourcerer.io/fame/Nicklas373/Nicklas373/M.A.O/links/3)[![](https://sourcerer.io/fame/Nicklas373/Nicklas373/M.A.O/images/4)](https://sourcerer.io/fame/Nicklas373/Nicklas373/M.A.O/links/4)[![](https://sourcerer.io/fame/Nicklas373/Nicklas373/M.A.O/images/5)](https://sourcerer.io/fame/Nicklas373/Nicklas373/M.A.O/links/5)[![](https://sourcerer.io/fame/Nicklas373/Nicklas373/M.A.O/images/6)](https://sourcerer.io/fame/Nicklas373/Nicklas373/M.A.O/links/6)[![](https://sourcerer.io/fame/Nicklas373/Nicklas373/M.A.O/images/7)](https://sourcerer.io/fame/Nicklas373/Nicklas373/M.A.O/links/7)
