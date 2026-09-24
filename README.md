# DIY-CNC

This design is my take on the common gantry CNC mill. 

<img width="1053" height="988" alt="image" src="https://github.com/user-attachments/assets/30792567-220d-4f82-8aaf-6d99ac522dec" />

## Goal - 
The main focus of the design was to develop a rigid and stable machine that will be able to machine aluminum quickly and harder steels, while also staying relatively cheap. Therefore, the use of 3D printed parts is common as a means to save money on outsourced aluminum machining. Although a majority of the parts are 3D printable it is recommended to later upgrade to aluminum for greater accuracy and rigidity (spindle plates). Other than the spindle, the rest of the build uses aluminum parts that are significantly too big for a standard 256 x 256 x 256 mm 3d printer causing them to have to be outsourced. The reasoning for the sizing of these part (y axis brace and gantry arms) were to cope for significant axial forces.

### CAD - 
The design is essentially complete, with minor changes that are going to be applied once greater testing occurs. 

### Part Selection - 
A few of the parts like the 800W water-cooled spindle and the use of SFU1204 ball screws may be questioned, though they were generally chosen to ensure that the parts come nearly 100% safe and simpler to use. Regarding the 800W spindle combo, when researching for a specific spindle I had to consider 3 major things: US power constraints, cooling, and noise. Companies like RATTMOTOR and etc, came up commonly, though when reading each of their reviews they were extremely mixed. Leading me to choose a Chinese company, G-Penny. They sell high quality spindles with solid ceramic bearings and wiring I don't have to tamper with, along with this it simplifies the search, since I needed a VFD that could run 110V. The SFU1204 ball screw was chosen specifically for accuracy, since I plan on making some extremely precise builds in the future and need that accuracy. The use of GRBL and the arduino system was quickly switched to mainly due to the need to reduce cost. The rail selection was based off of sizing and the availability of each on Aliexpress.

### Specifications - 

- 290 x 315 x 88 mm working area
- 800W water-cooled spindle
- SFU1204 ball screws for XYZ axis
- Nema 17 open loop steppers
- Concrete-filled base + 2020 extrusion frame

### Firmware/Software - 
GRBL - https://github.com/gnea/grbl/releases#release-v1.1h.20190825
UGS - https://github.com/winder/Universal-G-Code-Sender

### Bill of Materials - 
https://docs.google.com/document/d/1SkERPSoR8iWG40bx3YqEnEg6MCOHkP-ulHTMdxtHGsY/edit?usp=sharing

### Future - 
This github repo will be updated later with full build instructions and improvements to it, once the build is actually built and parts are ordered. 
Due to tariffs and other financial circumstances, the build model may change to cope.

Build Instructions are due to be added once parts are ordered and the build is built.

Submitted on Stardance for funding.

