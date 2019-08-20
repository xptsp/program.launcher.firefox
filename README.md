# Kodi Launches FireFox Addon
### Addon for Kodi to launch FireFox on Windows and Linux. ###

The goal is to bring to Kodi an easy access to launch this fantastic browser.

This Addon was made for Kodi Krypton v17.x and higher since it takes advantage of new features introduced on this version.
This Addon is only available in 3 languages: English, French and Spanish. To swtich to any language, change it on the configurations of Kodi at `Settings -> Interface settings -> Regional -> Language`.

## Usage
Use this Addon on Kodi if you want to launch FireFox from it.  It works on any platform where Kodi and FireFox can be installed (Linux and Windows).

![Addon-Selected-Information.jpg](/script.kodi.launches.firefox/resources/addon-screenshots/Addon-Selected-Information.jpg)



## Installation

#### Prerequisites
First, you need to install Kodi, to download and install it go to https://kodi.tv/  
After that you need to install and configure FireFox, to download and get instructions based on your operating system, go to https://www.mozilla.org/en-US/firefox/new/ and extract the files to the correct location.

#### Steps
1. Download the Addon:   
   For now this Addon is not registered on any official or unofficial Kodi repositories yet, hopefully it would be in the future. For now the way to install this Addon is to install it from a zip file.  
   Go to this page https://github.com/xptsp/Kodi-Launches-FireFox-Addon/releases and download the latest zip file available.

2. Start Kodi and navigate to `Settings -> Add-ons -> Add-on browser -> Install from zip file`, on the file browser look for the zip file you downloaded on the previous step and select it. Installation is going to start and Kodi will show a notification when this is done.   
   **Note:** If preference is not checked, Kodi will ask you to allow installations from zip files as a security measure. Change your preferences to allow installations from zip files and continue with the installation. Also please notice that this options can be displayed on different paths depending of the Skin you are using. The path used above is a generic one that may or may not be on your Skins, but in any case it is not hard to find.

3. Once the Addon is installed, navigate to `Program Add-ons` and you will see FireFox listed there.   

   ![Addon-Selected.jpg](script.kodi.launches.firefox/resources/addon-screenshots/Addon-Selected.jpg)

4. Before running the Addon, you need to set the location of the FireFox executable, the default location for Windows is `C:\Program Files (x86)\FireFox\firefox.exe` while for Linux it is `/usr/bin/firefox`, if you installed FireFox on a different location, you can choose your own location by going to the Addon-Settings by selecting the FireFox Addon, bringing up the contextual menu by right-clicking it (or pressing the `Guide` button on a remote, pressing `C` key on a keyboard, pressing `X` button on Xbox or Steam Controllers or `Square` button on PayStation controllers) and selecting `Settings` or `Configure`.   

   ![Addon-Settings.jpg](script.kodi.launches.firefox/resources/addon-screenshots/Addon-Settings.jpg)

   The next window will show you the `FireFox executables` properties that you can select and change them by navigating on the file browser. You only need to edit the executable property of the OS you are running since the other would be ignored. The Addon during its execution checks which OS is running and will call the corresponding executable. If you provided an executable that doesn't exist anymore, the next time you try to run it the Addon will show you an error message suggesting you to go to the Addon-Settings and change it.   

   ![Addon-Settings-Edit-Executable.jpg](script.kodi.launches.firefox/resources/addon-screenshots/Addon-Settings-Edit-Executable.jpg)

5. Enjoy!


## Troubleshooting

##### FireFox not visible or starting underneath Kodi
When Python within Kodi starts a new command like the FireFox program, it doesn't provide a terminal where emulators can connect and be displayed. As for version 1.1.4 we implemented a solution for Linux users by running Xterm which calls FireFox executable and this provides a TTY for FireFox to connect to. Xterm location is set as default, but if you have it on a different path, you can change it on the Advanced tab of the Addon Configuration.

Sometimes, because Kodi is in fullscreen, FireFox will start underneath Kodi's window and not become visible. This can be worked around by exiting Kodi's fullscreen when FireFox starts and returning to Kodi's fullscreen after FireFox closes. As for version 1.1.4, this option has been added on the Advanced tab of the Addon Configuration.

##### Screen turning off or computer enters in sleep mode
On some systems, FireFox will not keep Kodi from shutting down screen or putting the computer to sleep. A workaround has also been added and a switch was added on the Advanced tab of the Addon Configuration.

##### Advanced tab of the Addon Configuration
Here you can find the Advanced tab of the Addon Configuration, set the values and switches as needed if you face one of the mentioned issues:
![Addon-Settings-Advance.jpg](script.kodi.launches.firefox/resources/addon-screenshots/Addon-Settings-Advance.jpg)

## Credits
Forked from [https://github.com/BrosMakingSoftware/Kodi-Launches-EmulationStation-Addon](https://github.com/BrosMakingSoftware/Kodi-Launches-EmulationStation-Addon "Kodi-Launches-EmulationStation-Addon by BrosMakingSoftware @ GitHub").  Language files modified to show target of addon.