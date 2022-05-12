## Wind Vane

<img src="https://github.com/holligram/mySQMplus_3DPrints/blob/main/images/windvane_cross_section.png" width="800">

### Features

* A key feature of this design is that it does not use any metal fasteners to assemble. There are four 3d printed threads that are integral to the design and make for a secure assembly. As these are functional prints, they all should be printed with a maximum layer height of 0.2mm, 4 walls in and out, as well as 4 top and bottom layers.
* The sensor used is the AS5600 magnetic angle sensor. The bottom of base has four pinch pins that secure the sensor in place. Once assembled, the sensor will be at the correct height just below the magnet.


### Bill of Materials
- <img src="https://github.com/holligram/mySQMplus_3DPrints/blob/main/images/GX12-4pin.png" width="200"> 4 pin Aviation type (GX12) connectors 
- <img src="https://github.com/holligram/mySQMplus_3DPrints/blob/main/images/AS5600.png" width="200">AS5600 magnetic angle sensor with magnet.
- <img src="https://github.com/holligram/mySQMplus_3DPrints/blob/main/images/6004_bearing.png" width="200">6004 bearing 20x42x12mm 


### Notes
- The common 6x3mm project magnet is too strong for this sensor and may overpower it causing unreliable data. I recommend using the smaller magnet provided with the sensor.
- Be sure the magnet is securely held in the provided cavity of the cap. Should it drop out and fall on the sensor below it, it may cause the magic smoke to escape the ESP32. Ask me how I know this!
- The pointer and tail are a tight fit in the hub which are then held fast by the cap. There may need some gentle filing to get them to fit correctly into the hub depending on how accurate your 3D printer is and how much over extrusion you have.
- The 3D printed threads may need to touched up with a file depending on how well your printer reproduces these. 
