-----------------------------------------------------
-----------------------------------------------------
UPDATE 1.0

For General
- Beta Release (Not posted on Github)

-----------------------------------------------------
-----------------------------------------------------
UPDATE 1.1

For General
- Initial Github Release

For ANIM
- Cleaned up Main Menu
- Adjusted Options 1, 2, 3, and 4 to make created tiles span across the duration of the video, if 
  possible
- Added 'Reduced' Champion Icon support
- Adjusted Option 1 and 2 to automatically create standard Champion Icon sprite sheet
  and Reduced Champion sprite sheet at the same time
- Adjusted Options 1, 2, 3, and 4 to append some attributes to output folder/file names. For example:
   "_Champ" (if the output files/folders are for Champ Icons)
   "_Reduced" (if the output files/folders are for Reduced Champ Icons)
   "_Spray" (if the output files/folders are for Reduced Champ Icons)
   "_Bars" (if the output files/folders are Black Bar versions)
   "_Stretch" (if the output files/folders are Stretched versions)

- These attributes can stack too, i.e. "Aespa_Champ_Bars_Reduced"   
- Created Option 101: This option allows splitting of vanilla sprite sheets into tiles
- This supports:
  a. Animated Spray Sprite Sheets (4x4 tiles, 2048x2048px)
  b. Regular Champion Icons Sprite Sheets (6x10 tiles, 3588x3980px)
  b. Redeuced Champion Icons Sprite Sheets (5x8 tiles, 2000x2136px)
  
-----------------------------------------------------
-----------------------------------------------------
UPDATE 1.1.1

For General
- Changed 'D-Your-New-SPLIT-Sheets-Are-Here' to 'Z-Your-New-SPLIT-Sheets-Are-Here'
  
For ANIM
- Adjusted Main Menu (to be more inline with soundKits Main Menu)
- Adjusted Options 3 and 4 to create 'Item' (lower resolution) sprite sheets alongside normal rez sheets.
- Normal rez versions will have "_Show" appended, and lower rez versions will have "_Item" appended
- Added Info Options (WIP) for each Option. Type an "i" + the number of the Option, and press Enter
  EXAMPLE: To get info about Option 2, type "i2" and hit enter.

NOTE: This is NOT heavily tested!

-----------------------------------------------------
-----------------------------------------------------
UPDATE 1.1.2

For General

For ANIM
- Upgraded Option 101 to allow turning sprite sheets into gifs or mp4s

NOTE: This is NOT heavily tested! 

-----------------------------------------------------
-----------------------------------------------------
UPDATE 1.1.3

For General
- Added .bat and Instructions txt back

For ANIM
- In Option 1, 2, and 101, added support for 3800x4000 champion sprite sheets (Gambit has these dimensions, for example)
  This new sheet will now be automatically created for Options 1 and 2
  Dimensions for Champ sheets are now appended onto their output file names
- Reworked Option 101 to only use a single input folder now.
  Sprays, Full Champ, and Reduced Champ sheets will now all be placed into 'A-Put-Your-Sprite-Sheets-Here'
- Renamed Option 101 output folder to 'B-Your-New-SPLIT-Sheets-Are-Here'
- Added support for .webm to Option 101
  NOTE: Webm supports transparency. Quality is BALANCED (Not perfect)
- Improved .gif and .mp4 quality for Option 101
  NOTE: GIF supports transparency. Quality is BALANCED (Not perfect)
- Menus and some Info Options adjusted accordingly/cleaned up
- Main Menu options no longer need double confirmation.
  Processing will begin on the first press of "Enter" on a valid option.  

NOTE: This is NOT heavily tested! 

-----------------------------------------------------
-----------------------------------------------------
UPDATE 1.2.0 (NOT RELEASED YET, 'BUG TESTING')

For General
- Added Updater .bat file. Double clicking this will download the latest release .zip of SoundKit_MR

For ANIM
- Added Support for animated emojis
- Changed Easy Config rubric to no longer require TileHeight and TileWidth input
  These are now automatically calculated given the sprite sheet dimensions and row/column count

NOTE: This is NOT heavily tested! 

-----------------------------------------------------
-----------------------------------------------------
UPDATE X.X.X (NOT RELEASED YET, 'BUG TESTING')

For General

For ANIM

NOTE: This is NOT heavily tested!  
