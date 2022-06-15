# Bastard OS
`A Custom Version of Onion OS for the Miyoo Mini`

**Do you have a spare SD card?** 

**Do you like the stock Miyoo Mini firmware but don't like how it runs?** 

**Do you love Onion and Mini UI for their own unique reasons?** 

Bastard OS is a amalgamation of the stock OS and Onion OS taking what I like from both and smashin em together.

# Features:

* The EMUs of stock but baked into Onion OS for faster boot times, better performance and battery percentage.

* Keeps original in-game menu button action including the save/load menu.

* Quick save via power button enabled. Press power button in game (except PS1*) and the system will quicksave and shutdown. *Power back on and select your game in recent to resume!* *For PS1 quicksave functions use the Retroarch shortcut for PS1 and use the button combo `MENU + POWER` to quicksave and powerdown!

* Faster then stock with cores picked by my personal experience

* Custom Keymon fully working by `Eggs` <3 RTC and Screenshot built in! (check shortcuts)

* Onion OS v3.11.1 SDL audio fix + latency reduction baked in so less audio pops *between* games.

* includes `Eggs` full miyoo mini optimized retroarch to run systems not included.

* **No** background music on the homescreen

* Includes File Explorer 

# Installation:

You need the 0419 firmware update, upgrade info below

<details open=""><summary>Show upgrade guide from the Trifoce Miyoo Mini Wiki</summary><br>
<a href="https://github.com/TriForceX/MiyooCFW/wiki/Miyoo-Mini#firmware-update-guide" rel="nofollow">Source with picture guide</a>
  
  
<p>Download latest update direct from Miyoo from official <a href="https://lemiyoo.cn/upgrade" rel="nofollow">website</a> or from our <a href="https://drive.google.com/drive/folders/192KkgJ6rTy5gpYRyPIK4D0_apm8bwVlm?usp=sharing" rel="nofollow">backups</a></p>
<p><em><strong>NOTE PLEASE READ FIRST</strong></em></p>
<ol>
<li>use a trustworthy SD card(sandisk, toshiba, etc.)</li>
<li>Make sure miyoo283_fw.img was downloaded correctly (file size: 15,134,744 CRC32:814ED165)&amp; MD5 (miyoo283_fw.img) = 32ce41b44cf9d35f4ee9ceae0ba7827d</li>
</ol>
<p>Additional Tips: Please use a power plug that is not more than 5V, do not upgrade through the computers usb charging,
copy the firmware files to TF card immediately after upgrading the machine do not flash after playing games, otherwise its easy to lose data AND END UP WITH A brick!:)</p>
<p><em><strong>Note: VERY IMPORTANT Remove the battery first then proceed with the upgrade!</strong></em>
Step 1 Download Miyoo283_fw. Img firmware &amp; the A wild card zip.
Step 2 Copying TF cards connect to a computer through a card reader then copy the downloaded Miyoo283_Fw. img firmware directly to the root directory of the TF card.
Step 3 Upgrading Do not power off during upgrade! You can't press the power button! It turns into bricks!</p>
<ol>
<li>Power off remove the battery</li>
<li>Install the TF card back</li>
<li>Power on through Type C plug the data cable and enter charging state</li>
<li>Do not press the power button. It will enter the firmware upgrade state automatically.</li>
<li>The upgrade takes about 2 minutes after the update it will enter a charging state only then remove the cable very important as its still writing to internal NAND.</li>
</ol>
<p>Step 4 Please delete the Miyoo283_fw. Img firmware copied from the TF card after the upgrade!
Step 5 Copy (first backup your card,you will loose your saved data)Copy APP, Emu, RApp, RetroArch from the wild card folder that you downloaded to the TF card and directly overwrite any files is ask to.```</p>
<p>Additional Tips: Please use a power plug that is not more than 5V, do not upgrade through the computers usb charging,
copy the firmware files to TF card immediately after upgrading the machine do not start playing games, otherwise its easy to lose data AND END UP WITH A brick! :)</p>
</details>

ALWAYS BACKUP YOUR GAMES AND SAVES/STATES. RECCOMENDED USING THIS ON AN EXTRA CARD AS ITS MAINLY FOR PERSONAL USE.

1. `Delete all partitions of your SD card and format to Fat32`
2. `Copy the contents of "Bastard OS SD Files" to your fresh SD` 
3. `Instert SD to Miyoo Mini and turn on`
4. `Go through the installer. All EMUs will install AUTOMATICALLY`
5. `If you want to install any Retroarch shortcuts then select them in the installer`
3. `The mini will shutdown and you are all done!`

**Copy over roms and saves as needed and enjoy!**

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

# Thanks:

* The Onion OS team: `Sichroteph, jimgraygit, PixelShift-gb, asiansteev, Codeudan and squallstar`

* `eggs` the maker of the custom keymon and miyoo wizard
* `shauninman` maker of Mini UI and custom cores
* `Saí`
* `Jeltron`


If we can turn this into a community project making it OUR bastard OS by tweaking it and making it better and better then I would be happy with that. Thanks to all the dev community including the Retro Game Handhelds discord for being amazing
