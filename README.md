# Android Auto / Automotive (AAOS) repositories

This project consolidates all the SDK update sites that offer Android Auto / Android Automotive OS system images.

## AAOS

The following sites and car models are integrated here:
- [Google](https://dl.google.com/android/repository/sys-img/android-automotive/sys-img2-3.xml)
  - Android Automotive with Play Store - Android API 28 (x86)
  - Android Automotive with Play Store - Android API 29 (x86)
  - Android Automotive with Play Store - Android API 30 (x86_64)
  - Android Automotive with Play Store - Android API 32 (x86_64)
  - Android Automotive with Play Store - Android API 32 (arm64_v8a)

- [Polestar](https://developer.polestar.com/sdk/polestar_emulator.xml)
  - Polestar 2 - Android API 28 (x86_64)
  - Polestar 2 - Android API 29 (x86_64)
- [Volvo](https://developer.volvocars.com/sdk/volvo-sys-img.xml)
  - Volvo XC40 - Android API 29 (x86_64)
- [GM](https://developer.gm.com/docs/gm-emu-downloads)
  - [MY23 GMC Yukon](https://developer.gm.com/downloads/final_37_03042022_emulator.xml) - Android API 29 (x86_64)
  - [MY23 GMC Hummer EV SUV](https://developer.gm.com/downloads/final_38_03042022_emulator.xml) - Android API 29 (x86_64)
  - [MY24 CADILLAC Lyriq Freeform SUV](https://developer.gm.com/downloads/final_ff_05302022_emulator.xml) - Android API 30 (x86_64)
  - [MY24 GM SUV](https://developer.gm.com/downloads/final_31XX_06272022_emulator.xml) - Android API 30 (x86_64)

## Android Auto
- [Google](https://dl.google.com/android/repository/sys-img/android-automotive/sys-img2-3.xml)
  - Android Auto Desktop Head Unit - 2.0
  - Android Auto Desktop Head Unit - 2.1

## Usage

In Android Studio, open the SDK manager. Then go to the tab "SDK Update Sites" and create a new entry using the + icon.

Add the following information in the dialog that pops up:

- AAOS
  - Name: droidhood (AAOS)
  - URL: https://raw.githubusercontent.com/droidhood/aaos-sys-img/main/sys-img2-3.xml

- Android Auto
  - Name: droidhood (AA)
  - URL: https://raw.githubusercontent.com/droidhood/aaos-sys-img/main/repository2-3.xml


Click OK and then apply.

If you go back to the "SDK Platforms" tab and mark the box "Show Package Details" you should be able to see the AAOS system images under the respective Android version.
Android Auto simulators will be available in the "SDK Tools" tab.