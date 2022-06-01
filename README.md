# Bastard-OS
A Custom Version of Onion OS for the Miyoo Mini

*This will be used as a main hub for updates and links for* ***BASTARD OS***

UPDATE 05/29. I HAVE FIXED THE CRASH SO NOW BASTARD OS IS IN FULL WORKING ORDER AND REQUIRES LESS STEPS TO INSTALL V2.0 WILL BE OUT IN A WEEK OR SO. LINK HAS BEEN PULLED TILL NEW ZIP IS MADE. STAY TUNED. 


# BASTARD OS VERSION 1.5

**NEW UPDATE AT** `05/25/2022`, IF YOU ARE USING A PREVIOUS VERSION BACKUP EVERYTHING AND COMPLETELY WIPE. A NEW FRAMEWORK IS INPLACE AS WELL AS `NEW SAVE AND STATE LOCATIONS`! DONT FORGET TO READ BELOW FOR ALL NEW INFORMATION!

Do you have a spare SD card? Do you like the stock Miyoo Mini firmware but don't like how it runs? Do you love Onion and Mini UI for their own unique reasons? Bastard OS is a amalgamation of the stock OS and Onion OS taking what I like from both and smashin em together.

\-Onion OS base with Stock baked in includes faster boot times and battery percentage.

\-Keeps original menu button action and save/load menu but themed

\-Onion launcher Quick save power button feature backed in. Press power button in game (except PSX) and the system will quicksave and shutdown. *Power back on and select your game in recent to resume!*

\-Faster then stock with cores picked by my personal experience

\-Custom Keymon fully working by `Eggs` <3 RTC and Screenshot built in! (check shortcuts)

\-onionOs v3.10.5 SDL audio fix + latency reduction baked in so NO AUDIO POP *between* games (MAKE SURE AUDIO FIX IS SET ON IN THE SETTINGS)

\-includes `Eggs` full miyoo mini optimized retroarch to run systems not included

\-**No** background music on the homescreen

\-Includes File Explorer & Retroarch

\-*Added a template for how to sort games by creating new EMU folders. Check out the included SMWHACKS as an example and its included readme*

If we can turn this into a community project making it OUR bastard OS by tweaking it and making it better and better then I would be happy with that. Thanks to all the dev community including the Retro Game Handhelds discord for being amazing

* `eggs,`
* `shauninman,`
* `jimgray and`
* `Saí`
* `Pixelshift`
* `Jeltron`

Installation:

ALWAYS BACKUP YOUR GAMES AND SAVES/STATES. RECCOMENDED USING THIS ON AN EXTRA CARD AS ITS MAINLY FOR PERSONAL USE.

1. `Delete all partitions of your SD card and format to Fat32`
2. `Copy the contents of "Bastard OS SD Files" to your fresh SD 3. Instert SD to Miyoo Mini and turn on`
3. `Go into the App Menu and run "Bastard OS Installer + Themes"`
4. `Select "Bastard OS Fix" and press "Install"`
5. `Back in the App menu run "Bastard OS Refresh"`

**Done!** Copy over roms and saves as needed and enjoy!

# Shortcuts:

*Menu button:* Opens stock menu that can save state, load state and change EMU

Shortcuts via `Eggs`:

*START button:* Adjust the brightness by pressing L2/R2 while holding down.

*SELECT button:* Adjust the internal digital volume by pressing L2/R2 while holding down. (-30dB \~ +30dB, 3dB step) Pressing SELECT + L2 + R2 to reset to 0dB. - Digital volume setting value is not saved and will be restored if the application initializes - Because of the analog wheel, this feature is not likely to be used very often, but it may be useful if sound is too loud or too quiet.

*During suspend - MENU button:* Take a screenshot. a png file will be saved in /Screenshots in SD. (Same function as scrshot app)

*During suspend - START button:* Adjust internal clock. (Same function as clock daemon) Clock setting is saved as currentTime.txt in the same directory as keymon. - Note that some applications may have problems if the time is changed during execution.

*During suspend - SELECT button:* Adjust LCD parameters. (Luma / Hue / Saturation / Contrast) - No need to reboot after adjustment.

*Power button ingame (EXCEPT PSX):* Pressing in all emus BUT PSX will auto-save and shutdown. When powering on you can open the save state by going into recents or finding game file

**-if battery falls below about 4% the device will AutoSave & Exit**

# Locations:

Roms: SD:\\Roms

Game save location: `SD:\Emu\(game system)\config\saves\(game system)\(core)`

Game states location: `SD:\Roms\(game system)\(core)`

Game auto state location: 'SD:\Emu\(game system)\config\states\(game system)\(core)'

Bios: `SD:\Emu\(game system)`

\*PS1 has its states and memcards self contained here:

`SD:\Emu\PS\.pcsx`



# UPDATE LOG

v1.5

* ^(Changed save and state locations to make known issue crash be less problematic)
* ^(changed ra32.ss structure to all use the same (Thanks) `Eggs`)
* ^(System files have been further cleaned up to take up less space)
