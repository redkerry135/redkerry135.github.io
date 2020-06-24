In this tutorial, you will be guided on how to move a save file from a cart game to a digital version of the cart game.
Credit to `redkerry135#1055` on discord for literally everything


## **What you need:**

1. A 3DS modded with Luma3DS CFW.
2. Checkpoint (If you do not have Checkpoint, a  direct link to the .cia download is [here](https://github.com/FlagBrew/Checkpoint/releases/download/v3.7.4/Checkpoint.cia).)
3. A 3DS Cartridge with a save in it.
4. A digital version of the 3DS Cartridge, either obtained through [Cartinstall](https://github.com/knight-ryu12/godmode9-layeredfs-usage/wiki/CartInstall-guide) or a legal cartridge dump. There must be a save file in this version. If there isn't a save file, make one in-game.
5. An SD Card adapter (ftp with ftpd works if necessary)

### Basic Checkpoint controls

(this section is directed to those whose SELECT button(s) are broken)

- Use the DPad or Circle Pad to navigate around the app.
- Press A to select a game.
- After selecting a game, you can press L to backup the save, or R to restore the save.
- You can also enable cheats for the selected game. Usage guide [here](https://3ds.eiphax.tech/cpcheats.html).
- You can switch to extdata saves by pressing X.
- You can backup every title at once by holding Y, then press L.
- You can also delete certain backups by selecting a game, selecting a backed up save, and then pressing X.
- Hold B to refresh the app.


### Section 1: Making a backup of both saves

1. On your 3DS, open Checkpoint and make a backup of both the cart and digital game.
2. Name the cart's save `Cart` and name the digital's save `digital`
3. Close Checkpoint and turn off your 3DS.



### Section 2: Moving the save files

1. Eject the SD Card from your 3DS and insert it in your computer.
2. In your SD Card, go to the folder named `3ds`. In this folder, there should be another folder named `Checkpoint`.
3. In the Checkpoint folder, open another folder named `saves`.
4. Inside the saves folder, look for the folders consisting of your cart and digital game's name.
5. Copy the file(s) from the game's `cart` folder into the `digital` folder. Replace the files.
6. Eject the SD Card and put it back in your 3DS.



### Section 3: Restoring the save

1. Power on your 3DS and open Checkpoint.
2. Wait for the apps to load. If the digital game does not appear, hold B to refresh.
3. Select the digital game and press R to restore the save.
4. You're done! You can now continue playing where you left off.


### Troubleshooting

Q: My game doesn't appear in checkpoint!                                                                              
A: Hold B to refresh, if you still don't see it, double check if there is a save for the game.

Q: My old save is still in the digital copy of the game!                                                              
A: Make sure you replaced the files from the backup, and didn't accidentally press Skip or Cancel while copying.
 
more troubleshooting questions coming soon when i have the motivation to think of some questions