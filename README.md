# DropperCracker
A small applet to crack the static java.util.Random object present in Minecraft's Dropper and Dispenser classes given only output from an in game redstone device.

To use the applet, first build and launch the application and then open the Minecraft 1.15.2 world file found in Dropper Cracker.zip. Press the birch button found in this world, wait approximately 30 seconds, and then check the boxes corresponding to the lamps which have lit up. The program outputs the current internal seed of the Dropper/Dispenser Random object. Since the Random object is static, this will be the internal seed for any dropper in any world until Minecraft is closed or a Dropper/Dispenser fires.
