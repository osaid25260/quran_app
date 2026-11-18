Al-Quran Al-Kareem - Offline Audio Player (Sheikh Sudais)

A lightweight, 100% offline Android audio player application for listening to the complete 30 chapters (Paras/Juz) of the Holy Quran recited by Sheikh Abdur-Rahman As-Sudais.

 Key Features

Ultra-Lightweight APK (~1 MB): Built using a Shell/Wrapper architecture. The heavy audio files (1.13 GB) are NOT bundled inside the APK, preventing installation errors and saving app data.

100% Offline Playback: Reads M4A audio files directly from the Android device's local internal storage without requiring an internet connection.

Modern Dark UI: Clean, mobile-first dark slate interface with dynamic track highlighting, active playback status, and intuitive controls (Play/Pause, Previous, Next).

Single-File Architecture: Entire interface and logic contained within a standalone index.html file.

 Required Directory Structure (Important!)

For the app to locate and play the audio files offline, you must place the 30 M4A files in the exact folder path below on your Android device's Internal Storage:

/storage/emulated/0/QURAN/Quran/


File Naming Convention

Ensure the audio files inside /QURAN/Quran/ follow this exact naming pattern (from Chapter 01 to Chapter 30):

Full Quran Recitation By Sheikh Sudais _ Chapter 01_128k.m4a

Full Quran Recitation By Sheikh Sudais _ Chapter 02_128k.m4a

...

Full Quran Recitation By Sheikh Sudais _ Chapter 30_128k.m4a

 Setup & Installation Guide (For New Users)

Method 1: Using the Pre-built APK (Recommended)

Create Folders: Open your Android File Manager, go to Internal Storage, create a folder named QURAN, and inside it create another folder named Quran.

Transfer Audio: Copy all 30 .m4a recitation files into /storage/emulated/0/QURAN/Quran/.

Install App: Transfer app-release.apk to your phone and install it.

Grant Permissions: Open the app and Allow Storage/Media file access if prompted. Enjoy offline recitation!
