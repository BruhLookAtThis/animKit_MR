# animKit_MR
Animated Icon/Spray modding kit for Marvel Rivals

--------------------------------------------------------------
OVERVIEW
--------------------------------------------------------------

(GRAB AN FMODEL DOWNLOAD FROM HERE: https://fmodel.app/download)

AnimKit (Animated Image Making Kit) is for:
   
   a. Converting videos/gifs/images into tiles
   
   b. Converting those tiles into sprite sheets for use with Animated UI
   
   c. Converting sprite sheets into tiles/gifs/videos

--------------------------------------------------------------
USAGE INSTRUCTIONS
--------------------------------------------------------------

1. Download the tool, and unzip it
2. Right click the `z1_RunMeInPowershell_ANIM_MR.ps1` file and choose `Run with Powershell`
   - 2b. A Blue window should pop up. If it does not stay open, try double-clicking `z2_DoubleClickMe_ANIM_MR.bat`
   - 2c. A black window should pop up. If it doesn't, Google `how to change powershell execution policy`
   - 2d. Set your policy to `Unrestricted`, and then try step 2 or step 2b again
3. Place the video/gif you want made into a sprite sheet directly into `1-PLACE-VIDEO-HERE`
   - 3b. For Title Logo mods, you need to place your files in `1-PLACE-VIDEO-HERE\1-PUT-TITLE-START-FILE-HERE\` (this will play through ONE time, for a short period) and `1-PLACE-VIDEO-HERE\1-PUT-TITLE-LOOP-FILE-HERE\` (this will indefinitely loop until you leave the title screen)
4. Input a number for the asset you want to create (Champion Icon, Animated Spray, etc) i.e `1` for Champ Icon, then press Enter
5. In this next menu, choose if you want to use transparent padding to keep your input video/gif/img's aspect ratio, or if you want it to stretch to file out any (potential) empty space (people usually use the transparent padding option)
6. Once finished, it will have individuals tiles used to create your sprite sheet inside of folders named after your input video/gif/img in `2-TILE-IMAGES-ARE-HERE` (these are largely irrelevant to you)
7. It will also have sprite sheets inside of folders named after your input video/gif/img in `3-FINAL-IMAGE-HERE` folder (THIS is what you want)
   - 7b. If you chose to make a Champion Icon sprite sheet, you will have two output folders
   - 7c. One of the folders for Champ Icons is `YOURFILENAME_Champ_Pad`, which contains a `3588x3980px` version of your sheet AND a `3600x4000px` version. There are two outputs here because some character's file uses the first size, others use the other size, so I just force the script to make both.
   - 7d. The other folder for Champ Icons is `YOURFILENAME_Champ_Pad_Reduced`, which contains a lower-pixel version of your sprite sheet. This is used by Rivals in certain areas, and must be added to your mod so that your custom imagery always shows up in the game no matter where you look at it
   - 7e. If you chose to make an Animated Spray sprite sheet, you will have one output folder
   - 7f. The folder will be named `YOURFILENAME_Spray_Pad`, which contains a `YOURFILENAME_Spray_Pad_Item.png` file (`Item` images are a spray's thumbnail) and a `YOURFILENAME_Spray_Pad_Show.png` file (`Show` images are what show when you actually spray the image onto the ground ingame)
   - 7g. If you chose to make an Animated Emoji sprite sheet, you will have three output folders
   - 7h. These folders will be named `YOURFILENAME_Emoji_Pad_80`, `YOURFILENAME_Emoji_Pad_328`, & `YOURFILENAME_Emoji_Pad_1024`, and will contain a multitude of image sizes (again, thats just me forcing the script to account for "every" sizing scenario. You likely only need one size image from here)
8. Next you need to select which image(s) you need from your output + figure out what to name your files, as these new sprite sheets have to be the same name as the vanilla files. 
   - 8b. To see what's required for your mod, open FModel and look for your character's vanilla sprite sheet(s). Locations are listed below:

## Champion Sprite Sheets can be found here (Size may vary by character so pay attention):
- `Marvel/Content/Marvel/UI/Textures/Mastery/Common/CharaID#/FILE(S)`
- `Marvel/Content/Marvel/UI/Textures/Mastery/Reduce/CharaID#/FILE(S)`
- `Marvel/Content/Marvel_LQ/UI/Textures/Mastery/Common/CharaID#/FILE(S)`
- `Marvel/Content/Marvel_LQ/UI/Textures/Mastery/Reduce/CharaID#/FILE(S)`

## Sprays Sprite Sheets can be found here (These are pretty much always the same size):
- `Marvel/Content/Marvel/UI/Textures/Item/Spray/FILES(S)`
- `Marvel/Content/Marvel/UI/Textures/Show/Spray/FILE(S)`
- `Marvel/Content/Marvel_LQ/UI/Textures/Item/Spray/FILES(S)`
- `Marvel/Content/Marvel_LQ/UI/Textures/Show/Spray/FILE(S)`

## Emoji Sprite Sheets can be found here (Size may vary by character so pay attention):
- `Marvel/Content/Marvel/UI/Textures/Chat/Bubble/80x80/VX/FILE(S)`
- `Marvel/Content/Marvel/UI/Textures/Chat/Bubble/328x328/VX/FILE(S)`
- `Marvel/Content/Marvel/UI/Textures/Chat/Bubble/1024x1024/VX/FILE(S)`
- `Marvel/Content/Marvel_LQ/UI/Textures/Chat/Bubble/80x80/VX/FILE(S)`
- `Marvel/Content/Marvel_LQ/UI/Textures/Chat/Bubble/328x328/VX/FILE(S)`
- `Marvel/Content/Marvel_LQ/UI/Textures/Chat/Bubble/1024x1024/VX/FILE(S)`

## Emoji Thumbnail can be found here:
- `Marvel/Content/Marvel_LQ/UI/Textures/Chat/Bubble/328x328/FILE(S)`

## Title Logo can be found here (You don't actually need to check anything here, the sprite sheets are already named and sized correctly):
- `Marvel/Content/Marvel/UI/Textures/Login_V3/EN/FILE(S)`


9. Once you find what you need, left click the file one time so it's highlighted, then right click it


MAKE SURE YOU READ THE INSTRUCTIONS IN EACH FOLDER (If theyre outdated, they will be labeled as so)

--------------------------------------------------------------
CREDITS:

BruhLookAtThis / ❕토 Tobi 비❕ (Spare Change?: https://linktr.ee/BruhLookAtThis)

--------------------------------------------------------------
## Licensing

### animKit_MR
- **License**: GNU General Public License v3.0 
- **Description**: soundKit_MR is a tool kit for modding sounds in Marvel Rivals, including organizing, renaming, manipulating, and compiling audio & text files. 
- **Project homepage**: https://github.com/BruhLookAtThis/animKit_MR
- **Main developers/maintainers**: BruhLookAtThis  
- **Source code**: Available at https://github.com/BruhLookAtThis/animKit_MR/releases

## Third-Party Dependencies / Licensing

This tool includes and redistributes the following open-source components:

### FFmpeg / ffprobe
- **License**: GNU Lesser General Public License version 2.1 or later (LGPL v2.1+)
- **Description**: Multimedia framework for decoding, encoding, and processing audio/video.  
- **Project homepage**: https://ffmpeg.org  
- **Version used**: 7.1.1  
- **Source code**: https://github.com/FFmpeg/FFmpeg/releases/tag/n7.1.1  
- FFmpeg is a trademark of Fabrice Bellard.

--------------------------------------------------------------
