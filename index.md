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

### [Download Cjam](https://github.com/cutandjoin/Cjam/releases/download/v2720/cjam_v2720.zip)

**Version**: 2.7.2.0  
**Release Date**: Sep 19, 2026  
**File Size**: 54.4 MB  
**SHA-256**: 1b8ffc96f09a86fa0bce4d9a949a9153bfe55286547c1b0e11eab175e9143158

Includes the .NET 8 runtime. No additional software is required.

If the latest version cannot be downloaded, the previous version is available [here](https://github.com/cutandjoin/Cjam/releases/download/v2700/cjam_v2700.zip).

For more information, see the <a href="https://forum.cjmapp.net/index.php">forum</a>.

## Alternative Downloads

### Framework-dependent (.NET 8)

Requires Microsoft .NET 8 Runtime.

[Download](https://github.com/cutandjoin/Cjam/releases/download/v2720/cjam_v2720_net8.zip)

**File Size**: 2.08 MB  
**SHA-256**: 64e294d27d0bf7c969ce2b73b924322f40557354acbc0cba3d5b736997e3c179

### Framework-dependent (.NET 6)

Requires Microsoft .NET 6 Runtime.

[Download](https://github.com/cutandjoin/Cjam/releases/download/v2720/cjam_v2720_net6.zip)

**File Size**: 2.08 MB  
**SHA-256**: 351369aec664cac032124d8b3bb05ff9fec5d6a48de95338c6372ece34c92de1

## Supported Devices

- Microsoft Windows 10 or later

## Supported File Formats

- MP3 (*.mp3)
- CUE (*.cue)
- M3U (*.m3u)
- CJAMC (*.cjc) - Cjam's custom format
- CJAMJ (*.cjj) - Cjam's custom format
- <a href="https://cjmapp.net/manual/manual.html#txt-cjm">CJAM</a> (*.cjm) - Cjam's custom format
- <a href="https://cjmapp.net/manual/manual.html#txt-cjt">CJAMT</a> (*.cjt) - Cjam's custom format
- TXT (*.txt)

## Installation and Execution

1. Extract the ZIP file.
2. Place the "Cjam" folder on a drive with read/write access.
3. Run "Cjam.exe".

## Changelog

### Version 1.0.0.0 - Dec 21, 2019

### Version 2.0.0.0 - Jun 28, 2025

### Version 2.7.2.0 - Sep 19, 2026
- Added support for new section types in .cjt and .txt files (Lua definition)
- Added support for custom properties accessible from Lua
- Fixed a bug where Lua code in .cjt and .txt files was not applied under certain conditions
- Fixed a bug where comment lines in CJM sections in .cjt and .txt files were not removed
- Fixed a bug where the run order of CJMP commands was not properly prioritized


For detailed update information, see the <a href="https://forum.cjmapp.net/viewforum.php?f=3">full changelog</a>.
