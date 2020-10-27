# Dokter's Prescription
A script suite to make life easier for Windows and **Ableton Live** users.


##	Default "Dokter’s Prescription" shortcuts

- The "Dokter’s Prescription.EXE" script enables several shortcuts for Windows, Ableton Live, and other specific programs:

  - **Ableton Live** - 47 custom shortcuts
  - **Spotify** - 7 custom shortcuts
  - **Google Chrome** - 5 custom shortcuts
  - **Brave Browser** - 5 custom shortcuts
  - **Windows** - 15 custom shortcuts
  
*Program-specific shortcuts are only enabled while the corresponding program window is active.*
  
**Reference the `Dok's Rx Guide.xls` spreadsheet for the complete list of keyboard shortcuts included in `Dokter's Prescription.EXE`**

- **Suspend/Resume Script** - **`[CTRL+ALT+SHIFT+PAUSE]`**.

- **Exit Script** - **`[CTRL+ALT+SHIFT+END]`**

_*See the **"Customizing Scripts"** section below, for instructions on customizing all default shortcuts included in this script._


## Optional* "Dokter’s Prescription" shortcuts

_*See the **"Customizing Scripts"** section below, for instructions on activating the following optional shortcuts:_

- **A-Z Launch/Toggle Programs** - These shortcuts are __disabled by default__ but can be customized to your prefernce by editing the **`Dok's Rx (Raw).AHK`** script. These shortcuts will launch a specified program if it is not currently running, **OR** toggle the program window if the program is currently running, using the following hotkeys:
  - **`[WIN+SHIFT+** *letter key* **]`**
    - i.e. **`[WIN+SHIFT+A]`**; **`[WIN+SHIFT+B]`**; **`[WIN+SHIFT+C]`**; etc.

- **0-9 Launch/Toggle Programs** - These shortcuts are __disabled by default__ but can be customized to your personal prefernce by editing the **`Dok's Rx (Raw).AHK`** script. These shortcuts will launch a specified program if it is not currently running, **OR** toggle the program window if the program is currently running, using the following hotkeys:
  - **`[WIN+** *number key* **]`**
    - i.e. **`[WIN+1]`**; **`[WIN+2]`**; **`[WIN+3]`**; etc.



#	The "Dok’s Rx Cabinet" folder
The `Dok's Rx Cabinet` folder contains sub-folders for associated scripts/files referenced by the `Dokter's Prescription.EXE` and `Dok's Rx (Raw).AHK` scripts.

The following additional scripts are stored within the`Dok's Rx Cabinet` folders:

- **Ableton Takeover**
- **Power & Sleep Hotkeys**
- **Research Chemicals**

These additional packaged scripts can of course be launched manually from `Dok's Rx Cabinet` without hotkeys and used independently without the "Dokter's Prescription" script running.

*If the “Dok’s Rx Cabinet” folder is not kept within the same location that you are running the `Dokter’s Prescription.EXE` script from, the script may run into an error if a hotkey is pressed and the script is unable to locate the associated file within the `Dok’s Rx Cabinet` folder. In regard to this, if the `Dok's Rx Cabinet` folder gets moved or deleted, you can simply recreate it by launching the “Dokter’s Prescription.EXE” file again. Re-launching the `Dokter's Prescription.EXE` script will not overwrite any existing packaged files in `Dok's Rx Cabinet`. In other words, any changes that you have made to files within `Dok's Rx Cabinet` will not be lost by re-launching `Dokter's Prescription.EXE`*



#	The "Dok’s Rx" folder
The `Dok’s Rx` folder contains the following items referenced by the  **`Dokter's Prescription.EXE`** and **`Dok's Rx (Raw).AHK`** scripts:

- **The "Dok’s Rx Guide.xls" spreadsheet**
  - Includes full index of script functions and additional workbook tabs to reference some native hotkeys for additional programs.

- **The "App Launch Shortcuts" folder**
  - Used for storing created program shortcut files for launching/toggling apps that were installed by Microsoft Store.
  
*The `App Launch Shortcuts` sub-folder within `Dok’s Rx Cabinet\Dok’s Rx` is a location to keep program shortcuts for the "program launch/toggle" optional template code within the **Dokter's Prescription** script.*

*For example, programs that are downloaded from the Microsoft Store are not located in the standard program location. These programs are usually nested within `C:\Program Files\WindowsApps`. Typically, if you attempt the run the programs directly from their native file location, they will not launch properly. For these instances, you can create a program shortcut for these applications and move it into the `App Launch Shortcuts` folder.*

*i.e. Using the filepath:*

`"%A_WorkingDir%\Dok's Rx\App Launch Shortcuts\Microsoft To Do"`

*instead of:* 

`"C:\Program Files\WindowsApps\Microsoft.Todos_2.28.32802.0_x64__8wekyb3d8bbwe\ToDo.exe"`

- **The "Dok's Rx (Raw).AHK" script:**
  - This can be used for customizing the **Dokter's Prescription** script to meet your desired preferences.
  - See the "**Customizing Scripts**" section below for more info about this.

- **Icon files referenced by the the "Dok's Rx (Raw).AHK" script.**



#	The "Over The Counter" folder
The `Over The Counter` folder contains additional scripts referenced by **`Dokter's Prescription.EXE`** and **`Dok's Rx (Raw).AHK`**. These scripts can also be launched and used independently without the **`Dokter's Prescription.EXE`** or **`Dok's Rx (Raw).AHK`** running. This folder contains:

## The "Ableton Takeover.EXE" script:
 - Suspends program processes of specified programs while the Ableton Live window is active and resumes the program processes once the Ableton Live window is not active.
 - **Launch Script** while running **Dokter's Prescription** - **`[CTRL+ALT+SHIFT+A]`**
 - **Exit Script** - **`[CTRL+ALT+SHIFT+DEL]`**

Reference the `Ableton Takeover README.txt` for more info and the complete list of default program processes included in the .EXE version of this script.

An .AHK version of this script is included within `Dok's Rx Cabinet\Over The Counter\Ableton Takeover` for optional customizing. Although the .EXE version of **Ableton Takeover** includes a *decent* list of *common* programs, you can edit this script to include the program processes that are typically running while you are using Ableton Live. (See "Customizing Scripts" section below.)

Reference the `Ableton Takeover README.txt` file for more info and the complete list of default program processes included in the .EXE version of this script.
 
## The "Power & Sleep Hotkeys.EXE" script:
 - Enables hotkeys to sleep, hibernate, restart, or shutdown your PC. 
 - **Sleep PC** - **`[CTRL+ALT+SHIFT+ESC]`**
 - **Resart PC** - **`[CTRL+ALT+SHIFT+F5]`**
 - **Hibernate PC** - **`[CTRL+ALT+SHIFT+F9]`**
 - **Shutdown PC** - **`[CTRL+ALT+SHIFT+F12]`**
 - **Launch Script** while running **Dokter's Prescription** - **`[CTRL+ALT+SHIFT+P]`**
 - **Exit Script** this script by pressing **`[CTRL+ALT+SHIFT+HOME]`**

An .AHK version of this script is included within `Dok's Rx Cabinet\Over The Counter\Power & Sleep` for optional customizing. Although the .EXE version of **Power & Sleep Hotkeys** includes the hotkeys shown above, you can edit this script to adjust the hotkeys for your preference. (See the "**Customizing Scripts**" section below.)



# The "Research Chemicals" folder
The `Research Chemicals` folder contains the `Research Chemicals.AHK` script and associated tray icons.

## The "Research Chemicals.AHK" script:
 - An Autohotkey “testing script” for Autohotkey script development. You can edit this script with functions that you would like to test but do not want to incorporate into your main script.
 - **Display test message - `[CTRL+ALT+SHIFT+T]`**
 - **Identify mouse cursor coordinates - `[CTRL+ALT+SHIFT+C]`**
 - **Launch Script** while running **Dokter's Prescription** - `**[CTRL+ALT+SHIFT+R]**`
 - **Exit Script - `[CTRL+ALT+SHIFT+DEL]`**
 - **Save and Reload Script - `[CTRL+S]`**

*The Autohotkey software will need to be installed on your computer to run this script, as there is no compiled .EXE version included due to the nature of it's intended usage.*



#	Customizing Scripts

## Customizing the **Dokter's Prescription** script

1. Ensure that the Autohotkey software is installed on your computer - https://autohotkey.com/
2. Open the **`Dok's Rx (Raw).AHK`** file in the `Dok's Rx Cabinet\Dok's Rx`folder with any text editor such as `Notepad`; or a script editor such as `SciTE4Autohotkey`.
3. Edit the script text for each shortcut feature as desired, following the instruction comments embedded within the script.
4. Save your customized changes to the .AHK script file.
5. Use your customized script by simply launching your saved .AHK file or alternatively, you can compile it into an .EXE file by right-clicking the saved .AHK file and selecting **"Compile Script"**.
    - *This will create an .EXE version of the script that will be able to run on computers that do not have the Autohotkey software installed.*
6. Move your new custom .EXE or .AHK script file into the same folder as the original `Dokter's Prescription.EXE` script file location.

- Customizing the **Launch/Toggle Programss** shortcuts within `Dok's Rx (Raw).AHK`:

**NOTE:** By default, the **Launch/Toggle Programs** shortcuts in **`Dok's Rx (Raw),AHK`** are deactivated to keep this portion of the script in a clean, "template code" format. There are detailed instruction comments within the **`Dok's Rx (Raw).AHK`** file to guide you through customizing the script for your personal needs.

  - These deactivated blocks of code can be activated by removing the `/*`and `*/` brackets for each hotkey shortcut. Once these blocks of code are activated, they allow you to Launch/Toggle Programs windows using `WIN+(number key)` and/or `WIN+SHIFT+(letter key)` as described previosuly above.

  - In addition to removing the comment brackets, you will need to replace portions of the "template code" with the **program name** and **file path** for each desired program. There are detailed instructions on how to customizing these features located in the actual script file via comments labled under: "PLEASE READ - ADJUST FOR YOUR OWN PROGRAMS:""

*Make sure that your customized version of **`Dok's Rx (Raw).AHK`** script is moved into the same folder location of the original `Dokter's Prescription.EXE` script to ensure that it will be able to reference the associated files in the `Dok's Rx Cabinet` folder appropriately.*

**NOTE:** *The `Dok’s Rx (Raw).AHK` copy of the script does not include the sections of code that install the `Dok's Rx Cabinet` folder. You can always launch the original `Dokter's Prescription.EXE` file to re-install  the `Dok's Rx Cabinet` folder if needed. If you need to re-install a single file or folder to `Dok's Rx Cabinet`, re-installing the `Dok's Rx Cabinet` folder will never overwrite any existing files within `Dok's Rx Cabinet` and should never harm any files that have saved changes.*

## Customizing the **Ableton Takeover** script

1. Ensure that the Autohotkey software is installed on your computer - https://autohotkey.com/
2. Open the **`Ableton Takeover.AHK`** file in the `Dok's Rx Cabinet\Over The Counter\Ableton Takeover`folder with any text editor such as `Notepad`; or a script editor such as `SciTE4Autohotkey`.
3. Edit the script text to include/exclude any specific program process names, following the instructions within the `Ableton Takeover README.txt` file.
4. Save your customized changes to the .AHK script file.
5. Use your customized script by simply launching your saved .AHK file or alternatively, you can compile it into an .EXE file by right-clicking the saved .AHK file and selecting **"Compile Script"**.
  - *This will create an .EXE version of the script that will be able to run on computers that do not have the Autohotkey software installed.*
6. Move your new custom .EXE or .AHK script file into the same folder as the original `Ableton Takeover.EXE` script file location.

## Customizing the **Power & Sleep Hotkeys** script

1. Ensure that the Autohotkey software is installed on your computer - https://autohotkey.com/
2. Open the **`Power & Sleep Hotkeys.AHK`** file in the `Dok's Rx Cabinet\Over The Counter\Power & Sleep` folder with any text editor such as `Notepad`; or a script editor such as `SciTE4Autohotkey`.
3. Edit the script text to adjust the hotkey commands to meet your desired preferences, following the instructions within the `Power & Sleep Hotkeys README.txt` file.
4. Save your customized changes to the .AHK script file.
5. Use your customized script by simply launching your saved .AHK file or alternatively, you can compile it into an .EXE file by right-clicking the saved .AHK file and selecting **"Compile Script"**.
  - *This will create an .EXE version of the script that will be able to run on computers that do not have the Autohotkey software installed.*
6. Move your new custom .EXE or .AHK script file into the same folder as the original `Power & Sleep Hotkeys.EXE` script file location.

## Customizing the **Research Chemicals** script

1. Ensure that the Autohotkey software is installed on your computer - https://autohotkey.com/
2. Open the **`Research Chemicals.AHK`** file in the `Dok's Rx Cabinet\Research Chemicals` folder with any text editor such as `Notepad`; or a script editor such as `SciTE4Autohotkey`.
3. Edit the script text to include any Autohotkey functions that you would like to test.
4. Save your customized changes to the original `Research Chemicals.AHK` script file.
5. You're done. :)

# Donate

This script is **100% free** to use, manipulate, distribute, or incinerate but I've included a link for **donations** below.

If you find that **Dokter's Prescription** is useful for you, consider making a small donation. (or just enjoy it for free!)

**https://paypal.me/DokRyConn**

# 

Peace,

**Dokter RyConn**
