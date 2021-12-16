Reusable Synth Sim Lib
====================

Setup
---
1. Preferences > Configure Paths > add "ANALOG_SYNTH_SIM_LIB" to repo path
2. Preferences > Manage Symbol Libraries > Global Libraries > add "${ANALOG_SYNTH_SIM_LIB}/AnalogSynthSimLib.kicad_sym"


Parts
---
* Opamps: 
  * TL072
  * TL074
* OTA Opamps
  * LM13700
* Diodes
  * 1N4004
* Transistors
  * 2N3906
  * 2N3904

Things Fixed vs. KiCad Defaults
-----------------------------
* Diodes have proper pin order, for sim & footprint
* 


Thonkiconn jacks:
```
       _________
      |         |
   o  | o     o |
      |_________|

   S    TN     T
```

