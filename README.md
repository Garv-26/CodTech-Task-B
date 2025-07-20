# Media Player App
This is a simple Android Media Player application developed as part of **CODTECH Internship – Task 2**.  
The app plays `.mp3` audio files from the device’s local storage and provides basic playback controls.

## Features
- Play local audio files (`.mp3`)
- Pause current playback
- Skip to next or previous song
- Display currently playing song name

## File Access
The app automatically scans the **Music** folder of the device and lists all `.mp3` files. It allows smooth playback with navigation through the available songs.

## Tech Stack
- Platform: Android
- Language: Java
- Minimum SDK: 21 (Android 5.0)
- Media Handling: Android `MediaPlayer` API

## Permissions
The app requires the following permission to access audio files:

```xml
<uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE"/>
