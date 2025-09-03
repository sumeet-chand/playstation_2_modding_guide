
# PLAYSTATION MODDING GUIDE

* By: Sumeet Chand
* Created: October 2024
* Version: 1.0 (October 2024)
* Description: How to mod a Playstation 2 to play your legally dumped games digitally for preservation purposes. This method allows playing games on
authentic hardware with full compatability whereas software emulators often fail e.g, flashlights don't work well in many software emulators on a computer.

# TABLE OF CONTENTS
- [1. Terminologies](#terminologies)
- [2. Models](#models)
- [3. Modding](#modding)

# TERMINOLOGIES

PS2 = Playstation 2
OPL = Open playstation loader, a software used for reading attached storage mediums on your PS2 e.g, Harddrive (HDD), through ethernet port or through
USB or Memory Card
Free Mcboot = A set of files copied onto a memory card that allows soft modding a PS2, you can then copy other software in .EFL files such as OPL onto the
memory card to then soft mod and play games digitally you own.

# MODELS

Read this good social media post: https://www.reddit.com/r/ps2/comments/a4iolm/what_ps2_is_the_best/ 

# MODDING

To play dumped ROMS of your PS2 games on actual hardware you can follow the steps below. They do not apply to any SCPH-9xxxx latest models
as they have inbuilt firmware to prevent hacking the device.

Watch this video to learn how, note the MX4SIO part can be skipped if you just want to use a USB.: https://www.youtube.com/watch?app=desktop&v=O8sP1Xm5MfI

The latest version of Open Playstation loader 1.2+ supports exfat attached USB's. In the authors experience there is no issue with speeds in SCPH-7xxxx+ 
slim models, but possibly there is for earlier models. Note all Playstations have use 1.1 standards and speeds which is significantly theoretically slower
then the DVD or Internal Harddrive (HDD) or even compared with running games through the Ethernet port connected to a router with a USB running Samba like sharing.

## ADD COVER ART

To add art cover thumbnails for games similar to Retroarch first you need to create a folder named 'Art' along sider your 'DVD' folder on the USB. The images needs to be named as the games catalouge number and put into the Art folder. Example for ICO PAL version the image needs to be named SCES_507.60_COV.jpg. You can download the whole git here and rename the /default folder to "Art" then move to the USB
https://github.com/xlenore/ps2-covers Then plug the USB back into the PS2 start OPL manager go settings - Display settings - enable art - set to yes - then restart and test



## TROUBLESHOOTING

### USB GAMES NOT APPEARING
Occurs in exfat USB storage mediums. Put your roms in the USB in either a /CD or /DVD folder then plug into PS2 and start OPL, if the games dont intiially
appear under BDM/USB Games, then press the SELECT button to refresh then after press X button then press right to go to another list e.g, HDD Games, then go back 
to BDM/USB Games to see the list appear. If not then from Start - Quit OPL - start OPL again - repeat the before and restart and try again as a final attempt.
Follow this video up until the MX4SIO part and just follow the USB part - https://www.youtube.com/watch?app=desktop&v=O8sP1Xm5MfI

### GAMES WRONG COLOR
If you play a game from an incorrect region e.g, US or JAP game on a PAL console you will see incorrect colours. This is because the game sends NTSC encoding to a PAL
TV which is incorrect. To fix either use the correct region game for your console and for international region games use a a region converter for your cable e.g, for Component cables for NTSC/Japanese games in PAL console use a "ntsc to pal converter"

### SHAKY SCREEN

If you find the screen is a bit shaky then most likely you are on PAL 50hz console, which is software outputting at 60hz. Set to the correct Hz e.g, 50hz.
