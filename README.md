![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.6+-3776AB?style=flat-square&logo=python&logoColor=white)
[![GitHub Release](https://img.shields.io/github/v/release/Madnes-Madlaki/FolderVanish?style=flat-square&logo=github)](https://github.com/Madnes-Madlaki/FolderVanish/releases)

# FolderVanish
**Hide folders completely with the option of encyrpting them with a password using `attrib +s +h`, it provides a UI to the windows default CLI command and protects history using cryptography library**
## /!\ Folders are now considered as system files but they can still be seen with the correct methodology.
Encryption has been added, there is chance to lose the original folder in case of crash / power loss
since the program deletes the original folder and then creates the .enc file.
In case of crash, the folder has been already deleted but the encryption has not ended.

## Purpose
Hide folders so they don't appear even when "Show hidden files" is ON.
Unhide with one click, keeps track of hidden folders with an encrypted history list.
Works without password for hide/unhide, history requires unlock.
Standalone Windows executable available.

## How to use
1. Browse or type a folder path.
2. Click **Hide** –> folder disappears from Explorer.
3. Click **Unhide** –> folder reappears.
4. **Unlock History** –> enter/create password to see list of hidden folders.

<img width="937" height="848" alt="image" src="https://github.com/user-attachments/assets/426b6e0b-23ca-4731-8a68-db2dd4623a56" />


## Dependencies 
python 3.6+
cryptography library

## Run from source.
```bash
pip install cryptography
python program.py
