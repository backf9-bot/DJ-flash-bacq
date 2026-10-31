# PK DJ PRO — Android offline starter

This is the first Android Studio project for PK DJ PRO. It provides two independent local-audio decks, persistent Android document-picker access, play/pause/stop, seek bars, per-deck volume, a centered/resettable crossfader, and an offline search field that filters the tracks currently loaded in either deck. It does not need a network connection while mixing.

## Build the APK
1. Install Android Studio on a computer.
2. Choose **Open** and select this extracted `PK_DJ_PRO_Android` folder.
3. Allow Gradle to sync and install the Android SDK 35 if prompted.
4. Connect an Android phone with USB debugging enabled, or use an emulator.
5. Press **Run** to install the app. To create an APK, choose **Build > Build APK(s)**.

## Current scope
This is a starter build, not a complete Serato replacement. Advanced waveform rendering, full-device music-library indexing/search, beat-grid/BPM detection, beat sync, hot cues, looping, EQ/DSP effects, sampler, microphone input, recording, Bluetooth latency tuning and headphone cue routing still need implementation and device testing. Android audio focus and device-specific latency also need hardening before a public release.

## Offline and music rights
The app selects audio files stored on the device. It does not stream or download music. Only mix audio you own or are licensed to use.
