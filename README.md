Bleep Drum Eurorack
===================

This is the Bleep Drum by Bleep Labs converted to a Eurorack module.

It is a pretty basic adaptation with just trigger and CV inputs to make external control possible where the original only had the pad buttons and pitch knobs.

* Same output circuitry as original (5V P-P, a bit lower than common in Eurorack)
* Trigger inputs are eurorack voltage safe (positive edge trig, >1V)
* Input CVs are averaged together with knob values (0-5V internally)  
* Power switch so it can be rebooted into noise mode independently of rack 
* The PCB layout for the RGB LED I used is wrong so the colors don't line up with the Bleep drum manual, but I don't care :) Also, this has little impact when it is just used as sound module.
* additional blinkenlights =) 

Credits for the original circuitry goes to Bleep Labs (www.bleeplabs.com).

This module is working with the Bleep Drum MIDI firmware v12. Original Bleep Drum programmed chips should also work (but has not been tested).  
The internal drum sequencing seems a bit buggy. I'm not sure if this is because of hardware issues or not. I did not get it to work at all when I built this on a breadboard (which is also the reason why a clock output is missing). It works fine as a sound source which was the main reason I did this anyway so I'll leave it like this. 

Panel notes: I ordered the panel from Ponoko, laser cut and engraved on 1.5mm acrylic, black surface on white core. This gives a quite nice panel, black with engraved white text on it. Not exactly bullet proof but solid enought when the PCB is attached with all jacks and additional support screws. The used jacks will put the panel 10mm above the PCB so use matching 10mm spacer bolts. 
If a thicker panel (> 2-2.5mm thick) is used you may want to adjust how you mount the push buttons accordingly. 


Please note
===========
...that this module was developed entirely without any involvement from Bleep Labs. Whatever may be wrong with it is entirely my doing. Bleep Labs cannot be expected to answer questions about this module or anything related to it. 



The schematics, the PCB and he panel are all licensed cc-by-sa (Creative Commons Attribution-ShareAlike) 4.0. 


