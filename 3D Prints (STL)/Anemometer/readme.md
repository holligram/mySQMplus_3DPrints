## Anemometer

<img src="https://github.com/holligram/mySQMplus_3DPrints/blob/main/images/anemometer_cross_section.png" width="800">


### Features

* A key feature of this design is that it does not use any metal fasteners to assemble. There are four 3d printed threads that are integral to the design and make for a secure assembly. As these are functional prints, they all should be printed with a maximum layer height of 0.2mm, 4 walls in and out, as well as 4 top and bottom layers.

* The Anemometer design has an arm length of 100mm from the center of the hub to the middle of the cup. The mySQM+ mydefines.h will need to be adjusted:

`#define ARM_LENGTH                  (0.100)`

* The sensor used is either the KY-024 or the KY-003. The base has a pocket to accommodate the sensor and which places the magnet hall sensor at the correct height to interact with the magnets, which are housed in the hub nut. There are two versions of the base stl's provided. Select the one that matches the sensor you plan to use.
* There is an optional board retainer ring which will keep the board securely held in the pocket.  
* The 3D printed nut doubles as the magnet carrier and can contain either 1, 2, 3, or 6 magnets. Two magnets are recommended. The number of pulses generated per revolution is based on 1 pulse per magnet. The mySQM+ mydefines.h will need to be adjusted based on the number of magnets you use:

`#define PULSES_PER_REVOLUTION       2`

### Bill of Materials
- <img src="https://github.com/holligram/mySQMplus_3DPrints/blob/main/images/GX12-3pin.png" width="200"> 3 pin Aviation type (GX12) connectors 
- <img src="https://github.com/holligram/mySQMplus_3DPrints/blob/main/images/KY-024.png" width="200">KY-024 module <b>&nbsp;&nbsp;&nbsp;OR&nbsp;&nbsp;&nbsp;</b> <img src="https://github.com/holligram/mySQMplus_3DPrints/blob/main/images/KY-003.png" width="200">KY-003 module
- <img src="https://github.com/holligram/mySQMplus_3DPrints/blob/main/images/6x3magnets.png" width="200">6mmx3mm magnets
- <img src="https://github.com/holligram/mySQMplus_3DPrints/blob/main/images/6004_bearing.png" width="200">6004 bearing 20x42x12mm 


### Notes
- I've tried both the KY-024 and the KY-003 module and was not able to get the KY-024 to work correctly.
- The KY-003 module works perfectly without the D2 or R3 components present in the circuit. Refer the mySQM+ documentation for more detail on this.
- The arms are a tight fit in the hub which are then held fast by the cap. The ends of the arms may need some filing to get them to fit into the hub depending on how accurate your 3D printer is and how much over extrusion you have.
- The 3D printed threads may need to touched up with a file depending on how well your printer reproduces these.

