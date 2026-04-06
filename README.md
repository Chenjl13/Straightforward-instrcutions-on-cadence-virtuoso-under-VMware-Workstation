# Straightforward-instrcutions-on-cadence-virtuoso-under-VMware-Workstation
This project gives out a very simple instruction on how to use cadence virtuoso for circuit design and layout drawing

## Project buiding phase
First, we need to make a folder on our desktop, and enter Virtuoso, using the command as follow:
<img src="images/1.png">

Then, choose "File->New->Library" to create a new library. Take "inv" as example, we input the library name and chooose "Attach to an existing technology library", and we choose "smic18mmrf" as example.
<img src="images/2.png">

## Schematic phase
We now create a schematic for "inv", and finish the schematic drawing.
<img src="images/3.png">
<img src="images/4.png">

We use "Check->Current Cellview" to check if there is a connection error in our schematic.

## Symbol phase
If there is no errors in our schematic, using "Create->Cellview->From Cellview..." to create a symbol.
<img src="images/5.png">

## CDL and netlist generation phase
Go back to the Virtuoso page, using "File->Export->CDL..." to generate CDL. Choosing inv_schematic and replacing "Output CDL Netlist File" as inv.cdl
<img src="images/6.png">

If the analysis job succeeded, we will go to the next phase.
<img src="images/7.png">

## Layout phase



















