# MCEE

This repo will contain Minecraft: Education Edition worlds and templates

If a world was taken from online or the MCEE library, it will be credited in the README for that specific world or template. 

Enjoy!

# Some notable worlds in the MCEE library
- AI Wildlife Reserve by Causeway Digital
- Mapping Terrain by Minecraft education

# Helpful commands and when to use them
- Detect when a block is on another block
    - use the command block, with block type: repeat, condition: undirectional, and redstone: always active
    - command input: /testforblock x y z minecraft:(block)
        - for example, to detect if a banner is on top of a block at coordinates 315 32 66, the command input is: /testforblock 315 32 66 minecraft:standing_banner
        - to take a signal out, run a capacitor from the side with a sqaure. The 2 ticks should be closest to the block