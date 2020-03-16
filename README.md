# DG-Board
Blank Data General Nova/Eclipse line board project for KiCad.

This project has a library with a DG-Bus symbol and footprint.
The symbol is already placed in the schematic view and connected via the netlist to the footprint in the PCB layout.
In the PCB layout all major dimensions/holes/keepouts are laid out according to the [Nova Interface Design](http://bitsavers.trailing-edge.com/pdf/dg/015-000031-05_Nova_InterfaceDesign_May78.pdf).

For descriptions of the keepouts (which are just drawn on the F.SilkS layer for simplicity) check page 73 of the [Nova Interface Design](http://bitsavers.trailing-edge.com/pdf/dg/015-000031-05_Nova_InterfaceDesign_May78.pdf).

NOTE: Data General specifies 0.054-0.058" (1.3716-1.4732mm) finger thickness... Which is just above 1.2mm and just below 1.6mm which are two common PCB thicknesses available from manufactures.
I think erroring on the side of 1.6mm is the best option due to the connectors probably being designed for 1.6mm thickness PCBs DG probably just decided to go for this odd thickness for ease of insertion.
