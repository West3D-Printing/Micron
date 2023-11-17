# Printed parts, manual, CAD
- Your main source of information is Hartk's GitHub repo: https://github.com/PrintersForAnts/Micron. Please read through this document before you start printing your parts, as there are some modifications we recommend.
- When printing parts be sure to use the 180 files.
- We found it useful to have an extra PCB DIN clip to use for securing wires (more on that later).
- These modified Z belt covers work well and give a little more clearance for the A/B motors: https://github.com/PrintersForAnts/Micron/tree/main/Mods/Kayos%20Maker/Flat%20Z%20Belt%20Covers/STLs
- A modified bowden tube entry that adds an ECAS fitting can be found in this repository
# Toolhead
The default toolhead for our kit is the Dragonburner with an Orbiter extruder. You can get the files at https://github.com/chirpy2605/voron/tree/main/V0/Dragon_Burner

- If using the Pancake toolhead board and harness you can get the toolhead board mount at https://github.com/christophmuellerorg/voron_0_pancake_board
- If using an EBB36 CAN board we recommend the mount by KayosMaker at https://github.com/KayosMaker/CANboard_Mounts/tree/main/STLs/BTT_EBB36_1.0_Mounts

# Toolhead mount & probe
- We recommend using Boop as the toolhead mount and Z probe/endstop. You can get the files at https://github.com/PrintersForAnts/Boop/tree/main
- The DragonBurner toolhead requires a modified Boop front: https://github.com/chirpy2605/voron/blob/main/general/Experimental/Boop/boop_front.stl

# Screen
We recommend the BTT TFT43 screen if you're using a Raspberry Pi (not the BTT Pi). You will need:
- The files in the BTT_TFT43 folder in this repository
- The front skirt and accent files from https://github.com/PrintersForAnts/Micron/tree/main/Mods/hartk1213/180/Waveshare4.3