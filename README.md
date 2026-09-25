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

### Bill of Materials/Build Instructions - 
https://docs.google.com/document/d/1SkERPSoR8iWG40bx3YqEnEg6MCOHkP-ulHTMdxtHGsY/edit?usp=sharing

Prices may fluctuate from initial values as time passes. It also does not consider taxes and shipping due to the variance.
Bill of Materials assumes you own a 3d printer already because why are you building a CNC if you don't already own a 3d printer

To note, the aluminum parts at the end for for a set of custom milled UPGRADES AND not a required part.

| Part | Cost | Link	| Quantity | Reference Num |
| ---- | ---- | ----  | -------- | ------------- |
| PLA/ABS Filament (either work fine) |	16.99 |	https://www.amazon.com/ELEGOO-Filament-Resistant-Toughness-Resistance/dp/B0F37VY5VZ/ref=sr_1_12 | 1 |	1 |
| M6 Coupling Nuts | 25.16 |	https://www.amazon.com/uxcell-10pcs-M6x10x15mm-Coupling-Nuts/dp/B0F6N7XLS5/ref=sr_1_12 | 4 | 2 |
| Zinc-Plated Steel Coupling Nut Low Strength, 3/8"-16 Thread Size, 1-1/8" Long |	16.5 |	https://www.mcmaster.com/90264A113/	| 25 | 3 |
| M4 10mm Coupling Nuts | 6.89 |	https://www.amazon.com/MECCANIXITY-Coupling-M4x0-7mm-Connector-Hardware/dp/B0DK9B5V27/ref=sr_1_6 |	1 |	4 |
| Assortment of Screws : Mcmaster - M6 50mm socket head cap M6 30mm socket head cap M6 20mm socket head cap Aliexpress - M5 30mm socket head cap M5 20mm socket head cap M5 10mm socket head cap M4 15mm socket head cap M3 20mm socket head cap M3 15mm socket head cap M3 10mm socket head cap M3 8mm socket head cap m5 30mm roundhead aliexpress |	75.87 |	https://www.aliexpress.us/item/3256809207500690.html https://www.aliexpress.us/item/3256806812715286.html https://www.mcmaster.com/91290A326/ https://www.mcmaster.com/91290A205/ https://www.mcmaster.com/91290A332/	| 1 of each |	5 |
| M3 T Nuts |	4.99 | https://www.amazon.com/HELIFOUNER-Pieces-2020-Aluminum-Profile/dp/B0B1LTNX7F/ref=sr_1_3 | 1 | 6 |
| Threaded rods 400mm | 14.93 |	https://www.homedepot.com/p/Everbilt-3-8-in-x-6-ft-Zinc-Plated-Steel-Coarse-Threaded-Rod-23031/332734180 | 1 2ft 1 6ft | 7 |
| Limit Switches | 10.99 | https://www.amazon.com/REIFENG-Mechanical-Endstop-Horizontal-Ramps1-4/dp/B07PCN6T6F/ref=sr_1_4 | 1 |	8 |
| Nema17 Stepper Motor KIT + CNC Shield V3 Engraving Machine + A4988 Driver + 42 Stepper Motor Nema17 17Hs4401S With Wire |	53.51 |	https://www.aliexpress.us/item/3256804512478212.html | 1 | 9 |
| 24V DC power supply |	6.07 | https://www.amazon.com/Power-Supply-Adapter-Wall-Converter/dp/B0CNLR8ZYB/ref=sr_1_3 | 1 |	10 |
| G-penny 800W 110V spindle + VFD + pump + clamp | 288.00 |	https://gpennymachine.com/products/g-penny-0-8kw-er11-d65-220v-400hz-24000rpm-water-cooled-spinle-motor-with-inverter-bracket-water-pump-kit | 1 | 11 |
|Random bag of quick set concrete | 6.27 | https://www.lowes.com/pd/Sakrete-50-lb-Fast-Setting-Concrete-Mix/3338802?store_code=1921 | 1 | 12 |
|MGN12H rail and carriage 500mm 400mm	| 132.58 |	https://www.aliexpress.us/item/3256809265975522.html |	2 of each	 | 13 |
|SFU 1204 ball screw 500mm 400mm | 131.06	| https://www.amazon.com/dp/B0B7RM9ZNH/ref=twister_B0CN99BC2K?_encoding=UTF8&th=1 https://www.amazon.com/dp/B09BR414X7/ref=twister_B0CN99BC2K?_encoding=UTF8&th=1 |	2 500mm 1 400mm |	14 |
|SFU 1204 ball screw w/ HGR 20CA rail and carriage 200mm | 54.99 | https://www.amazon.com/dp/B0CW9CVH1V/ref=twister_B0CW8Y79VN?_encoding=UTF8&th=1 |	1 |	15 |
|2020 Extruded Aluminum: 400mm 500mm 560mm |	105.28	| https://www.aliexpress.us/item/3256807923095651.html |1 400mm 2 500mm 2 560mm | 16 |
|Frame rails and y axis brace | 242.2 | https://jlccnc.com/ | 2 frame rails 1 axis brace | 17 |
|Random wood board from basement 👍 | 0 |    |   1	| 18 |
|Aluminum parts (POTENTIAL UPGRADES IS NOT CONSIDERED IN TOTAL) |	242.2 (FOR FUTURE NOT MADE YET) |	https://www.midweststeelsupply.com/store/6061aluminumplate | 3 of 15x5.5 2 of 12.5x4 |	19 | 

|Total | 1192.08 |
|----- | ------- |

### Future - 
This github repo will be updated later with full build instructions and improvements to it, once the build is actually built and parts are ordered. 
Due to tariffs and other financial circumstances, the build model may change to cope.

Build Instructions are due to be added once parts are ordered and the build is built.

Submitted on Stardance for funding.

