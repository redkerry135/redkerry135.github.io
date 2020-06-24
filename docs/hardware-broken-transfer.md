# This is a complicated process. Please make sure to **_read the steps carefully_** to prevent a possible brick.



## What you need:

1. Two 3DS consoles, both modded with Luma3DS CFW.

 2.`essential.exefs`, which should have been backed up after completing Plailect's [finalizing setup](https://3ds.hacks.guide/finalizing-setup).

3. [Faketik.3dsx](https://github.com/ihaveamac/faketik/releases/download/v1.1.1/faketik.3dsx)




## Instructions:



### Section 1: Setting up the new console

1. Install Luma3DS CFW from this [guide](https://3ds.hacks.guide/get-started) if it is not already installed. **Do not install the cias or make a NAND Backup on Finalizing Setup**
2. Put `faketik.3dsx` inside your broken console's `3ds` folder, but do not run it.




## Extracting the movable file from essential.exefs

1. Insert your SD Card to your computer and retrieve the `essential.exefs` from when you made a NAND Backup on your previous broken console.
2. Put the `essential.exefs` anywhere on the SD Card (for now, just put it on the SD Card's root)
3. Eject your SD Card and insert it into your new 3DS console.
4. Boot GodMode9 by holding Start, then press Power.
5. Press A on `[0:] SDCARD`
6. Select your `essential.exefs`, and press A on `Mount as EXEFS image`.
7. Look for a file named `movable` inside the `essential.exefs` image mount.
8. Copy the `movable` file to the root of your SD Card.
9. There are two possible ways to do this step:
   
  i. Go back to GM9's main menu, press R + START to power off, and eject the SD Card and insert it in your computer.
   
  ii. Press R + X to rename the file.
  Rename the `movable` file to `movable.sed`.

## Replacing the movable.sed 
10. (if you did part i, eject the SD Card and insert it into  your 3DS, and boot GM9.)
    Navigate to `[1:] SYSNAND CTRNAND` > `private` and delete the `movable.sed` file that is found in there.
11. Press B until you are back at GM9's main menu.
12. Locate your renamed `movable.sed` in `[0:] SDCARD` and copy it to `[1:] SYSNAND CTRNAND` > `private`
13. Press B until you're back at GM9's main menu, then press R and A simultaneously and select Fix CMACs for drive. 
14. Press B until you are back at GM9's main menu, then press Start to reboot.
15. Your console will act like it has just been formatted, this is meant to happen. Proceed through initial setup.



## Getting your apps back

1. If you have some basic CFW knowledge, you would know that CFW persists after a system format.
2. Use the Download Play method to get to the homebrew launcher (go to the download play app, press L + Down(dpad) + Select > scroll down to miscellaneous options > Switch the hb. title to the current app, then relaunch download play)
3. Run faketik.3dsx
4. When faketik has done its amazing magic, you can close download play. Your apps will appear as gifts on the home menu. Do not worry, your saves are inside.
5. Congratulations, you just performed a complex procedure.



## Troubleshooting

Q: GM9 doesn't load when I hold start on boot!                                                                              
A: Ensure `GodMode9.firm` is inside `luma`/`payloads`. Check for any mistakes in the spelling for the folder names.                   

more troubleshooting questions will come when i don't suck at markdown