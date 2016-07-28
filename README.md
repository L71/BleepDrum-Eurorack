Bleep Drum Eurorack
===================

This is the Bleep Drum by Bleep Labs (www.bleeplabs.com) converted to a Eurorack module.

It is a pretty basic adaptation with trigger and CV inputs added to make external control possible where the original only had the pad buttons and pitch knobs.

* Similar output circuitry as original, directly from DAC, 5V P-P (which is a bit lower than common in Eurorack)
* Trigger inputs are eurorack voltage safe (positive edge trig, >1V)
* Input CVs are averaged together with knob values (0-5V internally)  
* Power switch so it can be rebooted into noise mode independently of rack 
* The PCB layout for the RGB LED I used is wrong so the colors don't line up with the Bleep drum manual, but I don't care :) Also, this has little impact when it is just used as sound module.
* additional blinkenlights =) 

The original files from Bleep Labs can be found here: https://github.com/BleepLabs/Bleep-Drum 

This module is working with the Bleep Drum MIDI firmware v12. Original Bleep Drum programmed chips should also work (but has not been tested).  

The internal drum sequencing in the module seems a bit glitchy. I'm not sure if this is because of some weird hardware issue or something else. I also still can't get it to record or play back anything at all when the circuit sits on a breadboard (which is also the reason why a clock output is missing...). It works fine as a sound source which was the main reason I did this anyway so I'll leave it like this. (Also, the C&K switches used for the drum pads turn out to be pretty bad for playing anyway...)

Panel notes: I ordered the panel from Ponoko, laser cut and engraved on 1.5mm acrylic, black surface on white core. This gives a quite nice panel, black with engraved white text on it. Not exactly bullet proof but solid enought when the PCB is attached with all jacks and additional support screws. The used jacks will put the panel 10mm above the PCB so use matching 10mm spacer bolts. 
If a thicker panel (> 2-2.5mm) is used you may want to adjust how you mount the push buttons accordingly. 

The module has a standard 10pin Eurorack +/- 12V power connector but it only uses the +12V and should run just fine on any DC power source that provides at least 7-8 volts if used standalone.  


Please note
===========
...that this module was developed entirely without any involvement from Bleep Labs. Whatever may be wrong with it is entirely my doing. Bleep Labs cannot be expected to answer questions about this module or anything related to it. 


The schematics, the PCB and the panel are all licensed cc-by-sa (Creative Commons Attribution-ShareAlike) 4.0. 


