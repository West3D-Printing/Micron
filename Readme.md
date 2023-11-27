# Printed parts, manual, CAD
- Your main source of information is Hartk's GitHub repo: https://github.com/PrintersForAnts/Micron. Please read through this document before you start printing your parts, as there are some modifications we recommend.
- When printing parts be sure to use the 180 files.
- We found it useful to have an extra PCB DIN clip to use for securing wires (more on that later).
- These modified Z belt covers work well and give a little more clearance for the A/B motors: https://github.com/PrintersForAnts/Micron/tree/main/Mods/Kayos%20Maker/Flat%20Z%20Belt%20Covers/STLs
- A modified bowden tube entry that adds an ECAS fitting can be found in this repository
- If you plan on moving the printer often this spool holder is convenient: https://www.printables.com/model/542953-voron-v02-foldable-spool-holder
# Toolhead
The default toolhead for our kit is the Dragonburner with an Orbiter extruder. You can get the files at https://github.com/chirpy2605/voron/tree/main/V0/Dragon_Burner. You need to use the STL files in the v0.2 directory. There's even a cowl with the Micron logo!

- If you're using the Pancake toolhead board and harness you can get the toolhead board mount at https://github.com/christophmuellerorg/voron_0_pancake_board
- If you're using the EBB36 CAN board we recommend the mount by KayosMaker at https://github.com/KayosMaker/CANboard_Mounts/tree/main/STLs/BTT_EBB36_1.0_Mounts

# Toolhead mount & probe
- We recommend using Boop as the toolhead mount and Z probe/endstop. You can get the files at https://github.com/PrintersForAnts/Boop/tree/main
- The DragonBurner toolhead requires a modified Boop front: https://github.com/chirpy2605/voron/blob/main/general/Experimental/Boop/boop_front.stl

# Screen
We recommend the BTT TFT43 screen if you're using a Raspberry Pi. If you're using a BTT Pi we recommend you either don't use a screen or source a different option; the BTT TFT35 SPI screen doesn't meet our usability requirements. You will need:
- The mount in the BTT_TFT43 folder in this repository
- The front skirt, accent, and bezel files from https://github.com/PrintersForAnts/Micron/tree/main/Mods/hartk1213/180/Waveshare4.3

# Electronics bay layout
Our kit uses a slightly different electronics layout for convenience. Looking at the electronics bay (note that your kit may have different motors):
![image](images/image_001.jpg)
- The first DIN rail mounts the PSU and a DIN mount for 3x three port Wagos.
- The second DIN rail mounts the controller board and SSR for the bed.
<br>This lets us keep the AC wiring short and contained to the right side (in this view) of the elctronics bay. The toolhead wiring and most of the DC wiring is the run on the left side of the bay. We found it helpful to install a DIN rail mount next to the left side of the controller board to tie off wires.