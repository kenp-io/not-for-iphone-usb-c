# The Not-for-iPhone X USB-C Mod

Folder *f94_flex* contains the KiCad project if you want to order the PCB yourself. Please note that for the moment only the schematic and symbols have been released. The rest will be pushed [when the auction of the first iPhone ends](https://kenp.io/auction). This will give me time to clean up the layout of the PCB. You can star the repo if you want to be updated on this :)

Files *CNC-Hold-1.stl* and *CNC-Hold-2.stl* are the files you can 3D print to hold your phone in a CNC vise if you want to enlarge the hole for the connector. I printed it on a Prusa MK3s with PETG material. Layer height 0.3mm and infill 15%.

File *Connector_Holder.stl* is the part that you can screw in the iPhone that will give some mechanical support for the USB-C connector. I printed it on a Prusa MK3s with PETG material. Layer height 0.07mm and infill 100%.

File *cnc.f3d* is a Fusion 360 file that shows how I centred the bigger connector hole in respect to the original hole. You can use that to program a CNC.

File *cncInstructions.png* is a drawing to show how to center the new hole (outer one) with respect
to the existing hole (inner one) that was suitable for the Lightning connector. Dimensions are in mm.

File *sourcing.png* is a hint to find the source for the chips. I don't want to post those links. If you're smart enough to replicate this project, you're smart enough to find what you're looking for with this ;)


## Improvements for the future:

- Add some CC logic to switch the CC signal depending on the orientation of the cable. This would make fast-charging fully working.
- Look into finding a new connector that has a waterproof rating but is still small enough
- Make a connector holder that is a little stronger. Maybe look into micro spot welding for this.
- Look into USB-C accessories
