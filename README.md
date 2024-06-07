# Echobase-delay-pedal

VERY IMPORTANT: In the current altium pcb design, a critical mistake was made! The positive side of C23 and C24 should be connected, if not, the PT2399 doesn't get Vcc(5V) ! Please correct this and generate new gerber files before ordering!!!
=> The schematic should be corrected (but please check it yourself if it is) but the pcb design is not corrected yet!
Others notes are found below the picture.

The Echobase. A delay pedal that can be used with instruments or other audio signals. The schematics (not designed by me, credits to the spanish designer who's name is unknown), pcb altium design, gerber files, case prototype in Fusion360 and a bill of a material for this project are available in this repository.

![Echobase_pcb_and_case](https://github.com/FRniels/Echobase-delay-pedal/assets/115066333/c8cbb3cf-b5be-430b-8383-2834a33182ea)

Notes:
  - The speed control doesn't work. I yet have to figure out if this is a mistake on my side or it is a schematic error.
  - I would like to have the oscillation caused by the feedback potentiometer to be less responsive. At this moment is goes into self oscillation way to fast, leaving most of the potentiometer range unused.
    I think this could be fixed by replacing R19 = 20K with 39K when glancing over other existing circuits.
