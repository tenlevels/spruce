![sprucetreelogo](https://github.com/tenlevels/spruce/assets/139886575/f248b441-835c-4f2e-b849-cec145b3ffcf)

# spruce: *SD Card Overhaul for Miyoo A30*

## DOWNLOAD LATEST VERSION BELOW

  - LINK https://github.com/tenlevels/spruce/releases

## CHECK OUT THE NEW WIKI
  
  - LINK https://github.com/tenlevels/spruce/wiki 

## WHAT WAS DONE:

 - All emulators and cores configured and performance considered..

 - Auto Save and Shutdown Feature added thanks to Decojon!

 - Bootlogo App added thanks to ShaunInman!

 - Performance and overclock adjustments set. No need to change cpu in settings (keep on default).

 - Remove RApp (RetroArch/Expert) from Main Menu.

 - Visual changes to default theme to match stock Miyoo.

 - In-game menu matches that of the theme loaded.

 - Imgs folder for box art now located inside rom folder.

 - BIOS folder created in root of SD card.

 - Auto save state and load enabled.

 - Remap files to have stick function on all systems.

 - Configuration of RetroArch and almost no notifications or hotkeys. Feel free to enable and configure how you like.

 - LED disabled.

## INSTALL

  - The short version is to format your SD card to FAT32 and extract the zip file onto your card.
  - See the new Wiki! https://github.com/tenlevels/spruce/wiki/Installation-Instructions

### BIOS

  - Place your BIOS files in the BIOS folder on root of SD card.

## UPDATE

To update:

- Download the latest release and extract the contents
- Delete everything on your SD card except for `BIOS` `Roms` `Saves` folders
- Place the entire contents of the latest spruce zip folder onto your SD card.

This will retain all your games, saves, and emulator bios files.

## CONTROLS

  *GLOBAL*

  - BRIGHTNESS - START + L1 (lower) START + R1 (higher)
    VOLUME - SELECT + L1 (lower) START + R1 (higher)

  *WHILE IN GAME*

  - Quit Game - Hold Select for 2 seconds and then:
    Press B to quit game or Start to Save and Shutdown.

  - SAVE/LOAD STATE RETROARCH - Home button
    EXIT GAME - Select + Start (PSP home button and exit through menu) Pico-8 press start from gamelist and home from splore
    FAST FORWARD - R2 (not for PSX)

  *WHILE IN MENU*

  - REFRESH ROMS/ SEARCH - Home button
    SEARCH - Select
    SHUTDOWN - Hold power until Power Off pop up display (A to confirm)

  *STICK DRIFT ISSUES*

  - Calibrate your stick through the settings tab in the main menu.

## SUPPORTED GAME SYSTEMS

*Amiga / Amstrad CPC / Arcade (FBNEO & Mame 2003+) / Atari 2600 / Atari 5200 / Atari 7800 / Atari Lynx / Bandai Sufami Turbo / Bandai WonderSwan & Color WS / Capcom Play System 1 / Capcom Play System 2 / Capcom Play System 3 / ColecoVision / Commodore 64 / Commodore VIC-20 / DOOM (PrBoom) / Fairchild Channel F / Famicom Disk System / FFPlay, Video & Music Player / Game & Watch / GCE Vectrex / Magnavox Odyssey 2 / Mattel Intellivision / Mega Duck / MS-DOS / MSX - MSX2 / NEC SuperGrafx / NE / TurboGrafx CD / NEC TurboGrafx-16 / Nintendo DS / Nintendo Entertainment System / Nintendo Game Boy / Nintendo Game Boy Advance / Nintendo Game Boy Color / Nintendo Pokemini / Nintendo Satellaview / Nintendo Super Game Boy / Nintendo Super Nintendo / Nintendo Virtual Boy / Nintendo64 / PICO-8 / Quake (Tyrquake) / ScummVM / Sega 32X / Sega CD / Sega Dreamcast / Sega Game Gear / Sega Genesis / Sega Genesis MSU / Sega Master System / Sega SG-1000 / Sharp X68000 / Sinclair ZX Spectrum / SNES MSU1 / SNK Neo Geo / SNK Neo Geo CD / SNK NeoGeo Pocket & Color NGP / Sony Playstation / Sony  PSP / TIC-80 / VideoPac / Watara Supervision / Wolfenstein3D (ECWolf)*

  N64/DC/PSP:

  - Consider these "BONUS". If any games play and you enjoy it, GREAT! Do not expect these systems to run smooth. Again... Bonus!
 
 ARCADE GAMES:

  - Arcade is set to use FBNEO to allow save states to function. MAME 2003 Plus is also included in the .ADD ONS folder. Save state is not supported in MAME.

 PICO-8 GAMES:

   - We strongly encourage you to buy and support Pico-8. https://www.lexaloffle.com/pico-8.php?#getpico8 You will need to purchase the Raspberry Pi version to obtain the dat and dyn files.

   - PICO-8 games will launch native from the roms folder. Place your games in the CARTS folder. You need to provide your own dat and dyn files and place them in the bin folder located in sdcard/App/PICO/bin. You can also use splore with Wi-Fi to browse and play games by launching it from the App. There are so many wonderful games and they seem to just keep getting better. Pico-8 is a great way for indie game makers to create and share with the world. We cannot say enough good things about Pico-8. Enjoy!

  - Fake08 is also included.

    Unfortunately MainUI is causing issues to launch Pico-8 games using the png extension with Fake08.
  
  - Change the game to p8 extension by deleting .png from your cart file. 
  A tool like ReNamer is very helpful and will bulk perform the task for you. https://www.den4b.com/products/renamer

      Example:
        Tomb of G'Nir.p8.png
        to
        Tomb of G'Nir.p8

## RETROARCH

  - Do not adjust settings in retroarch unless you are familiar with it.
  Removing or changing settings may cause games or controls to not work correctly. "Default" settings are from Miyoo and will remove all the custom configuration that has been done for spruce.

## THEMES

  - Included are 4 themes located in Settings. I plan on adding more icons and themes in the future.
  You can add themes from your Miyoo Mini or MMP. NOTE that there will be missing assets as the a30 has additional ones.

## Credits/Thanks

  - Huge thank you to Decojon for the Auto Save/Quick Shutdown + Resume feature!
  - Help, support and Bootlogo function (and lots of other stuff!) from Shauninman.
  - Miyoo stock OS
  - Retroarch removal from MainUI by Jim Gray
  - Onion team for the heavy lifting on finding the best cores to use with Miyoo and overall inspiration
  - DinguxCommander update by BTN/Paradise
  - Drastic by Steward
  - Pico-8 wrapper by Ninoh-FOX and Steward
  - Overlays from Onion & Darkhorse
  - Testing and encouragement by Hoo
  - Install guide, wiki, testing and support by sundowndersport
  - Photos, testing and support by supermodio64
  - Aemiii91 for being my mentor and friend
  - Russ from RGC - His YouTube channel started it all for me


THANK YOU TO THE AMAZING MIYOO COMMUNITY!!
