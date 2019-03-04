This repository is part of the open-source project: EVGE - Electric Vehicle Global Equipment:

- EVCE - Electric Vehicle Charge Equipment
  - Onboard Battery Charger
  - Charging station
- EVBE - Electric Vehicle Battery Equipment 
  - BMS (https://github.com/EnnoidMe/ENNOID-BMS)
  - **Scalable Battery Pack (This repository)**
- EVPE - Electric Vehicle Powertrain Equipment
  - Motor Driver (https://github.com/EnnoidMe/VESC-controller)
  - Gate driver (https://github.com/EnnoidMe/ENNOID-Dual-Gate-Driver)
  - Scalable Three-Phase Electric Motor

# ENNOID-PACK

This project aims to create a scalable & modular lithium-ion battery packs based on cylindrical cell format.

For small production & prototyping, PCB cost 4.90$ for 10pcs when smaller than 100mm x 100mm. Until the design prove itself functionnal, it is cheaper to use small 100 x 100mm PCBs connected together instead of ordering one huge & expensive PCB. For this reason, the design is now based on a modular approach.

## Features:

**18650 cells board**
- Vertically mounted cells
- All battery connection/fuses are done from the top side
- Integrated temperature probes & cell monitoring connectors for BMS
- Electrodes can be spotwelded directly onto the PCB
- Cells voltage levels are separated by a hollow serpentine ribbon

 

## Concept images:

The 100mm x 100mm (cell node) has 3 series x 10 parrallel (3S10P) 18650 cells. 

The cells are spotwelded by a fuse wire through the dedicated holes.


## Cells board:
![alt text](PIC/Node.png)

The 100mm x 100mm boards can be stacked to obtain the desired series & parallels number of cells.

The example below shows 3 series x 2 parallel boards which in total makes 9 series x 20 parallels(9S20P).


## Stacking cells board (With PCB)
![alt text](PIC/With_PCB.png)

## Stacking cell boards (PCB removed to show concept)

![alt text](PIC/No_PCB.png)
