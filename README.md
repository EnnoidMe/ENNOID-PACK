Related ENNOID projects:
  - [Onboard Battery Charger](https://github.com/EnnoidMe/ENNOID-Charger)
  - [BMS](https://github.com/EnnoidMe/ENNOID-BMS)
  - [Scalable Battery Pack](https://github.com/EnnoidMe/ENNOID-PACK)
  - [Motor Drive](https://github.com/EnnoidMe/VESC-controller)
  - [Dual Isolated Gate driver](https://github.com/EnnoidMe/ENNOID-Dual-Gate-Driver)

# ENNOID-PACK

This project aims to create a scalable & modular lithium-ion battery packs based on cylindrical cell format.

For small production & prototyping, PCB cost 4.90$ for 10pcs when smaller than 100mm x 100mm. Until the design prove itself functionnal, it is cheaper to use small 100 x 100mm PCBs connected together instead of ordering one huge & expensive PCB. For this reason, the design is now based on a modular approach.

## Features:

**18650 cells board**
- Vertically mounted cells, 10P3S modular block 
- All battery connection/fuses are done from the top side
- Integrated thermistor, cell voltages & temperature monitoring connectors for BMS are soldered onto the PCB
- Cells electrodes are spotwelded directly onto the PCB
- Cells voltage levels are separated by a serpentine ribbon
- Plastic case stackable & modular for high voltage packs

 

## Concept images:

The 100mm x 100mm (cell node) has 3 series x 10 parrallel (3S10P) 18650 cells. 

The cells are spotwelded by a fuse wire through the dedicated holes.


## Cells board:
![alt text](PIC/Node.png)

The 100mm x 100mm boards can be stacked to obtain the desired series & parallels number of cells.

The example below shows 3 series x 2 parallel boards which in total makes 9 series x 20 parallels(9S20P).

