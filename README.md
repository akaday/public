# Public Directory

## Description
This directory contains system-related files and scripts for various tasks.

## Contents
- **autorun.inf**: Autoplay configuration file.
- **bootmgr**: Boot manager for Windows.
- **bootmgr.efi**: UEFI boot manager for Windows.
- **setup.exe**: Installer executable.
- **__chunk_data**: Chunk data file.

## Usage
- **autorun.inf**: Place in the root directory of a USB to enable autoplay.
- **setup.exe**: Double-click to run the installer.

## Scripts
1. **Cleanup.bat**:
   ```sh
   @echo off
   del /q /f C:\Windows\Temp\*
   echo Temporary files deleted.
