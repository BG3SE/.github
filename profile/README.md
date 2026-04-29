# **Baldur’s Gate 3 Save Editor**

A modern tool for managing and editing *Baldur’s Gate 3* save files  
© 2024–2025 — All Rights Reserved

---

## **Overview**

The **Baldur’s Gate 3 Save Editor** is a simple yet powerful tool for Windows, aimed at helping players view, modify, and organize their save files for *Baldur’s Gate 3*.  
This editor allows safe and structured modifications to various character data, flags, and game progression values while ensuring that save integrity is maintained and corruption risks are minimized.

### - 🔗 ***Download the Latest Version:***

- [💾 Releases Page](https://github.com/BG3SE/.github/releases/) = `*Get the most recent version here*`

---

## **Key Features**

- **Automatic Baldur’s Gate 3 save file detection**
- **Effortless one-click save loading and exporting**
- **Customizable character attributes and progression**
- **Control over party composition and companion flags**
- **Inspect and modify quests and world state**
- **Real-time error checking and validation**
- **Automatic backup before any modifications**
- **Sleek, dark-themed interface ideal for long editing sessions**

---

## **System Requirements**

- Windows 10 or 11  
- A copy of *Baldur’s Gate 3* installed  
- Minimum 2 GB of free disk space  
- .NET Framework 4.8 or newer

---

## **Usage Instructions**

1. Download **BG3-Save-Editor.exe** from the Releases page  
2. Run the application (no installation needed)  
3. Select your *Baldur’s Gate 3* save directory  
4. Choose the save file you want to modify  
5. Edit the necessary values  
6. Click **Save Changes**

---

## ⚠️ **Important Notes for All Users**

### **Save Integrity Warning**

Improper modifications could lead to:

- Broken or unfinished quests
- Companion desynchronization
- Game freezes or crashes
- Permanent save file corruption

**Always use the automatic backup system before making any changes.**

---

## **Backup System**

The editor will automatically create backups before each edit:

- A full duplicate of the original save
- A timestamped restore point for easy recovery

Backups are saved in:

- The same directory as the original save file, inside a folder named `Backups`
- Each backup is named with the format `SaveName_yyyyMMdd_HHmmss.bak`, with the date and time of the backup for easy identification
- Older backups are automatically pruned to avoid clutter, with only the last 5 backups retained for each save file

This ensures that you always have a safe point to return to if something goes wrong during the editing process.
