# Welcome to TULIP 2.0

>"Everything will be alright as long as you have your -ing potato." - Mr. Tulip, to Mr. Pin, _The Truth_, by Terry Pratchett

>"See a pin and pick it up, and all day long you’ll have a pin!" - Stanley Howler, _Going Postal_, by Terry Pratchett

## A full pin mod for the AB motor mounts, XY gantry joints and front idler tensioners for the Voron v0.2
 - AB motors are mounted solidly to the frame, meaning no more shunting them back and forth with a bulky tensioning nut
 - AB motor shafts are held in double shear with an extra bearing, lowering radial force on the motor bearings
 - Tension is now applied through an M3 screw in the front idlers, and ALL bearing stacks run on pins rather than screws
 - Both MGN7H (stock) and MGN9C X rails are supported, WITH NO TRAVEL LOSS
 - Standard 3mm off-the-shelf pins, for those unable to cut their own
 - LazyCam support
 - Fysetc X light gantry compatibility (use standard XY joints)
 - Mamabot.io X light gantry support
 - Nema 17 AB Motor Mount Beta 
 - Nema 14 - 35mm Shaft Motor Mount Beta
 - Live Idler XY joints + Tension Idlers

## Installation
Go to the [Releases Page](https://github.com/SnoWFLakE0s/tulip/releases) and download the .zip file from the latest release.

## Renders

![](/documentation/images/V0.2R1%20Tulip%20Mod%20master%20v121.png)

![](/documentation/images/V0.2R1%20Tulip%20Mod%20XY%20Joints.png)

| Idlers | XY Joints |
| :---: | :---: |
| ![](/documentation/images/V0.2R1%20Tulip%20Mod%20idler%20tensioner.png) | ![](/documentation/images/V0.2R1%20Tulip%20Mod%20XY%20Joint.png) |
| ![](/documentation/images/V0.2R1%20Tulip%20Mod%20idler%20tensioner%20cut.png) | ![](/documentation/images/V0.2R1%20Tulip%20Mod%20Live%20XY%20Joints.png) |

![](/documentation/images/V0.2R1%20Tulip%20Mod%20Live%20Idler%20Exploded.png)

----

> **Note - for LazyCam idlers you will require some extra printed parts to complete found [here](https://www.printables.com/model/533483-voron-02-lazycams-tool-free-locking-idlers-models)**

Parts required are; 

- LazyCams_C-A CamArm_v1.stl
- LazyCams_C-A CamLock_v1.stl

- LazyCams_C-B CamArm_v1.stl
- LazyCams_C-B CamLock_v1.stl

---

## Bill of Materials (BOM)

### Idler / Tensioner BOM

| **Part** | **Quantity** | **Notes / Links** | 
| :--- | :--- | :--- |
| Pin M3x18mm | 2 | [KB-3D](https://kb-3d.com/store/hardware/143-3mm-bearing-steel-shafts-various-lengths-1642291225169.html) / [AliExpress](https://www.aliexpress.us/item/3256804639701799.html?spm=a2g0o.order_list.order_list_main.10.681a1802dQtwCu&gatewayAdapt=glo2usa) | 
| M2x10 Self Tapper | 4 |  | 
| M3 Hexnut | 4 |  | 
| M3x0.5mm Washer / Shim | 4 |  | 
| M3x10 BHCS | 4 |  | 
| M3x12 BHCS | 2 |  | 
| M3x35 BHCS | 2 |  | 
| F623 Bearing | 4 |  | 

---

### AB Motor Mount BOM

| **Part** | **Quantity** | **Notes / Links** | 
| :--- | :--- | :--- |
| 625-ZZ/2RS Bearing | 2 |  | 
| GT2 20T 6mm Pulley | 2 |  | 
| M3 Hexnut | 6 |  | 
| M3 Threaded Insert | 4 |  | 
| M3x0.5mm Washer / Shim | 20 |  | 
| M3x8 BHCS | 2 |  | 
| M3x10 BHCS | 4 |  | 
| M3x12 BHCS | 4 |  | 
| M3x30 BHCS | 6 |  | 
| Pins M3x30mm | 4 | [KB-3D](https://kb-3d.com/store/hardware/143-3mm-bearing-steel-shafts-various-lengths-1642291225169.html) / [AliExpress](https://www.aliexpress.us/item/3256804639701799.html?spm=a2g0o.order_list.order_list_main.10.681a1802dQtwCu&gatewayAdapt=glo2usa) | 
| F623 Bearing | 12 |  | 

---

### XY Joint BOM

| **Part** | **Quantity** | **Notes / Links** | 
| :--- | :--- | :--- |
| M3x6 BHCS | 2 |  | 
| M2x6 FHCS | 8 |  | 
| M3x8 BHCS | 4 |  | 
| Pins M3x30mm | 4 | [KB-3D](https://kb-3d.com/store/hardware/143-3mm-bearing-steel-shafts-various-lengths-1642291225169.html) / [AliExpress](https://www.aliexpress.us/item/3256804639701799.html?spm=a2g0o.order_list.order_list_main.10.681a1802dQtwCu&gatewayAdapt=glo2usa) | 
| M3x0.5mm Washer / Shim | 16 |  | 
| F623 Bearing | 8 |  | 

---

### Live Idler XY Joint BOM

| **Part** | **Quantity** | **Notes / Links** | 
| :--- | :--- | :--- |
| M3x6 BHCS | 2 |  | 
| M2x6 FHCS | 8 |  | 
| M3x8 BHCS | 4 |  | 
| XY Pins M3x30 | 4 | [KB-3D](https://kb-3d.com/store/hardware/143-3mm-bearing-steel-shafts-various-lengths-1642291225169.html), [AliExpress](https://www.aliexpress.us/item/3256804639701799.html?spm=a2g0o.order_list.order_list_main.10.681a1802dQtwCu&gatewayAdapt=glo2usa) | 
| M3x0.5 Washer / Shim | 12 |  | 
| F623 Bearing | 8 |  | 
| 16T Solid Idler | 2 | [Alchemy3d](https://alchemy3d.de/products/active-idlers-5mm-id-16t-for-6mm-belt), [Filastruder](https://www.filastruder.com/collections/gates/products/gates-2gt-pulley-custom-no-grub-set-screw?variant=41243545174087), [3dkatten](http://3dkatten.eu/products/custom-16t-2gt-3mm-id-live-shaft-idler) | 

----

NEW Pin Hole Sizing for Tulip should mean NO MORE REAMING! but if you still have trouble fitting your pins then refer to this guide

> **Note - For PIN FITTING GUIDE you can find it [here](https://github.com/Amekyras/tulip/tree/main/PIN%20GUIDE)**

----

**Links to original source material**

https://github.com/VoronDesign/Voron-0

https://vorondesign.com

https://github.com/akinferno/Voron0/tree/main/LazyCams

https://github.com/ruiqimao/VoronUsers/tree/v0.2-mgn9c/printer_mods/ruiqimao/V0.2_MGN9C_X

**GNU Terry Pratchett**

----

**special thanx for all thoes who have helped with feedback and improvement ideas to get Tulip as good as it is!**
