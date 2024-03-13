# PCI Voltage Blaster
 PCI +3.3V version of the Voltage Blaster project. This is meant to power PCI cards keyed for +5V slots that still require +3.3V. Like the "new" Chinese made ATI Rage XL PCI cards found all over eBay.

 This mini version is good for about 500mA. It's not meant for high-powered PCI devices.

 NOTE: Most +5V only PCI motherboards don't route the +3.3V pins between slots. You will have to add bodge wires on the back of your motherboard between the slot with the Voltage Blaster and the slot that needs +3.3V.

![Finished Voltage Blaster](https://github.com/chadr/PCI-Voltage-Blaster/blob/main/img/PCI%20Blaster.jpg?raw=true)

## Getting Boards Made
Either JLCPCB or PCBWay do a decent job. Your choice for HASL or ENIG. Doesn't really matter here. Choose 1.6mm board thickness.

**Bill of Materials**
**Item**|**Qty**|**MFG Part Num**
:-----:|:-----:|:-----:
+3.3V LDO|1|AMS1117-3.3 (DPAK)
10uF 16V Axial Electrolytic Capacitor|2|Nichicon VX Series
5mm LED Diffused|1|Any Generic Red or Green 5mm LED
120R 1/8 Watt Metal Film Resistor 1%|1|Any
Schottky Diode 40 Volt 1.0 Amp|1|SB140-E3/73
