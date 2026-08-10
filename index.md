---
layout: default
title: "Cjam"
---
# Cjam
<a href="img/ss00.png"><img src="img/ss00.png" alt="Cjam Screenshot" width="700px"></a>

## Overview
**Cjam** is non-destructive MP3 editing software designed for Windows PCs. Files are imported by dragging and dropping them onto the interface, after which they can be processed and exported according to the specified settings. Operations can be defined using text input, allowing multiple independent actions to be executed sequentially. The software enables fast editing without the need for decoding and re-encoding the audio.

## Key Features
- Cut MP3 files
- Join MP3 files
- Add fade effects to MP3 files
- Add silent intervals to MP3 files
- Play MP3 files
- Operate using text commands
- Save settings

## Download

### [Download Cjam](https://github.com/cutandjoin/Cjam/releases/download/v2600/cjam_v2600.zip)

**Version**: 2.6.0.0  
**Release Date**: Aug 10, 2026  
**File Size**: 53.8 MB  
**SHA-256**: c274614c62eae124caa5efc1f9ac13fcf75a9e496a8472702dc299940792f63c

Includes the .NET 8 runtime. No additional software is required.

If the latest version cannot be downloaded, the previous version is available [here](https://github.com/cutandjoin/Cjam/releases/download/v2510/cjam_v2510.zip).

For more information, see the <a href="https://forum.cjmapp.net/index.php">forum</a>.

## Alternative Downloads

### Framework-dependent (.NET 8)

Requires Microsoft .NET 8 Runtime.

[Download](https://github.com/cutandjoin/Cjam/releases/download/v2600/cjam_v2600_net8.zip)

**File Size**: 1.46 MB  
**SHA-256**: ee00d26c7d8f9fbffaaa0831a57b1db7332cc60ae51fc6046fde00838b3771e6

### Framework-dependent (.NET 6)

Requires Microsoft .NET 6 Runtime.

[Download](https://github.com/cutandjoin/Cjam/releases/download/v2600/cjam_v2600_net6.zip)

**File Size**: 1.46 MB  
**SHA-256**: c2296b2d84862e08335cafe2bcca2888aca05511697eacfeba530f6ec1dcde39

## Supported Devices

- Microsoft Windows 10 or later

## Supported File Formats

- MP3 (*.mp3)
- CUE (*.cue)
- M3U (*.m3u)
- CJAMC (*.cjc) - Cjam's custom format
- CJAMJ (*.cjj) - Cjam's custom format
- <a href="https://cjmapp.net/manual/manual.html#txt-cjm">CJAM</a> (*.cjm) - Cjam's custom format
- <a href="https://cjmapp.net/manual/manual.html#txt-txt">TXT</a> (*.txt)

## Installation and Execution

1. Extract the ZIP file.
2. Place the "Cjam" folder on a drive with read/write access.
3. Run "Cjam.exe".

## Changelog

### Version 1.0.0.0 - Dec 21, 2019

### Version 2.0.0.0 - Jun 28, 2025

### Version 2.6.0.0 - Aug 10, 2026
- Added support for .txt files
- Added a new command parameter (at)
- Added a new command alias (load)
- Changed the values of the command parameters (ie, ee)
- Removed the "Ctrl/Shift/Alt + Drop TXT Files" feature
- Unified paste operations in the main window under Ctrl+V and removed Ctrl+Shift+V
- Changed how command parameters (cb, ip, ar, up) are applied to paste operations in the main window
- Fixed an issue with incorrect paste positions in the main window
- Improved waveform rendering performance
- Added lang.txt entries (stf_c001-c007, stf_d001-d002)
- Updated a lang.txt entry (txt_c006)
- Removed lang.txt entries (prn_c102–prn_c105, prn_c261–prn_c264)
- Changed the author name
- Updated the distribution packages (Self-contained and Framework-dependent builds)
- Updated the system requirements (the primary download no longer requires the .NET Runtime)
- Fixed minor bugs


For detailed update information, see the <a href="https://forum.cjmapp.net/viewforum.php?f=3">full changelog</a>.
