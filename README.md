# Welcome to TULIP 2.0

>"Everything will be alright as long as you have your -ing potato." - Mr. Tulip, to Mr. Pin, _The Truth_, by Terry Pratchett

>"See a pin and pick it up, and all day long you’ll have a pin!" - Stanley Howler, _Going Postal_, by Terry Pratchett

A full pin mod for the AB motor mounts, XY gantry joints and front idler tensioners for the Voron v0.2

 - AB motors mounted solidly to the frame, meaning no more shunting them back and forth with a bulky tensioning nut.
 - Tension is now applied through an M3 screw in the front idlers, and ALL bearing stacks run on pins rather than screws.
 - Both MGN7H (stock) and MGN9C X rails are supported, WITH NO TRAVEL LOSS.
 - Pins are standard 3mm off-the-shelf sizing, for those unable to cut their own
 - LazyCam Support
 - Nema 17 AB Motor Mount Beta
 - Fysetc X light gantry compatibility (use standard XY joints)
 - Mamabot.io X light gantry support
 - Nema 14 - 35mm Shaft Motor Mount Beta
 - Live Idler XY joints + Tension Idlers


We now have a gorgeous manual in development by danya on the Voron discord, check it out if you need a helping hand!

<img width="2560" height="1233" alt="V0 2R1 Tulip Mod 2 0" src="https://github.com/user-attachments/assets/bbab425a-e143-43da-9606-4c9e4cf16088" />

<img width="2560" height="1233" alt="V0 2R1 Tulip Mod AB mounts" src="https://github.com/user-attachments/assets/694f5b5e-4fc6-4d11-9b11-c4687ed4c3a5" />

<img width="2560" height="1233" alt="V0 2R1 Tulip Mod XY Joints" src="https://github.com/user-attachments/assets/ba5ac1bb-6a4c-46ed-9dff-875838d53e57" />

<img width="2560" height="1233" alt="V0 2R1 Tulip Mod Live Idler" src="https://github.com/user-attachments/assets/bc292e69-279f-4b5f-8eae-878d514f82da" />

![V0 2R1 Idler Tensioners Cut](https://github.com/user-attachments/assets/495141d5-1f36-4f96-8263-19239bde98af)

<img width="2560" height="1233" alt="V0 2R1 Tulip Mod Live XY Joints" src="https://github.com/user-attachments/assets/978dd8bb-09df-4dce-9a4b-b6a3c0b4e281" />

![V0 2R1 XY Live Idler Cut](https://github.com/user-attachments/assets/34739536-31f3-4f1c-aaeb-e7359cc94028)

<img width="1960" height="1100" alt="Live Idler Stack" src="https://github.com/user-attachments/assets/d18074a9-c851-4898-90b5-930feaa2f203" />


> **Note - for LazyCam idlers you will require Some extra printed parts to complete**

these can be found here https://www.printables.com/model/533483-voron-02-lazycams-tool-free-locking-idlers-models

- LazyCams_C-A CamArm_v1.stl
- LazyCams_C-A CamLock_v1.stl

- LazyCams_C-B CamArm_v1.stl
- LazyCams_C-B CamLock_v1.stl

----
NEW Pin Hole Sizing for tulip should mean NO MORE REAMING! but if you still have trouble fitting your pins then reffer to this guide

> **Note - For PIN FITTING GUIDE you can find it here**

[https://github.com/Amekyras/tulip/blob/main/PIN%20GUIDE/PIN%20FITTING%20GUIDE.md](https://github.com/Amekyras/tulip/tree/main/PIN%20GUIDE)

----

> **CHANGE LOG**


----

31/07/25

CAD V36 Release

- Welcome to Tulip 2.0 !!!

AB mounts have been heavily Revised
- NEW universal design means it will work with any rail combo
- NEW (more) open frame design also helps with belting and visuals of motion system for easier diagnostics
- NEW branding Logo's

XY Joints
- NEW M3x25 + Threaded Insert fixing method, this now gives a much improved and stronger joint between the lower and upper parts
- NEW joining method also alows bearings to be serviced without removal of the whole gantry - simply unscrew and remove the tops for access
- some geometry has been revised on all versions
- Live Idler XY joint sports some NEW Features to add strength and stiffness
- Live Idlers moved from Beta to Mainstream
- MGN9H rail is no longer being supported

Idler Tensioners
- NEW crown tops added to all versions
- tension marks added to all version
- Logo has been moved to the front on all versions

Spacer
- Live idler spacer has now been adopted throught Tulip

PicoBilical
- added Picobilical STL's
- removed bowden tube holder from "Cable_Tie_Point" due to potential belt rubbing issue

S35 AB Mounts
- these will be updated in the comming months

----

04/02/25

CAD V35 release

QOL additions to
- Tension Idlers
- AB motor Mounts
- Live Idler XY Spacers

Tension Idlers
- added tension marks to the side for visual aid
- Reduced overhngs to Lower_Tensioner
- Increased Radious to front overhang to Lower_Tensioner to reduce curling
- reduced material used on Upper_Tensioner
- added in corner releif for upper extrusion

AB Motor Mounts
- Added additional location points to Mid_Mounts.
- This is to give a more possitive engagement / alignment between Mid and Top parts helping the double shear alignment.
- Chamfers removed from Top_Motor_Mounts - QOL for printing
- Motor Screw Holes resized from 3.4mm to 3.2mm for more secure location of the motor location on Mid_Mount
- added in corner relief for upper extrusion

Live Idler XY Joints
- Changed profile of Spacer top (bearing side)
- Old style was too easy to get upside down - this newer design will combat this while keeping the same overall look
- Lower_XY_Joints have had chamfer amendments for better first layer printability

----

11/12/24

CAD V34 release

update for a missed pin hole re-size ( parts affected - XY left upper joint & XY left upper MMU joint )

AB Mounts for MGN7H have been removed in favour of having MGN9C as the new standard - reason, MGN9C will work for MGN7H and gives and easy path to upgrade to MGN9C with no changes to be made to printed parts - also reduces part veriance for a more cohesive mod.

STL's for parts affected by the pin hole error have been updated

STL's for MGN7H AB Mounts have been removed

----

01/12/24

CAD V33 release

updated the pin cutting tool to give 18mm pins (as this is now the standard)

STL's have been updated

28/11/24

CAD v32 release

small amendments to supporting drawing

removal of 16mm pin tension idlers - in favour of better 18mm pin version (also to simplify and cause less confusion)

NEW addition of Nema 14 - 35mm shaft CAD and STL's

NEW addition of LIVE IDLER CAD for XY joints to have solid toothed idler and live pins
STL's have been added

----

10/11/24

CAD v31 release

Added umbilical Cover Plates (with + without Bowden Hole) and MMU versions

Added Picobilical Strain Relief Beta (MMU)

----

04/11/24

CAD v29 release

House keeping in CAD - Created componants for all bodies, Some name corrections, Reduced Materials

18mm Pin version of the front Idler Tensioners have been added for those who are struggling to find 16mm Pins, These also have LazyCam support
these are also recomended to those wishing to use GT3 belts

X Light Gantry (MamaBot.io) Beta is now included
> **Note - This is NOT compatible with the Fysetc X Light Gantry, instead use standard XY Joints**

Nema 17 AB Motor Mount Beta added for testing

ReadMe's added for some folders - please make sure you read them

STL's added

BOM amended + PDF format added

ALL STL's updated to latest CAD version

ALL Pin Holes have a new size (this should work for a better fit withoit the reeming)

----

16/09/24

CAD v28 release

Both Standard and LazyCAM static bodies have has the access hole size changed (for the front fixing into the extrusion) so that longer screws can be used and dropped in from the top.

A NEW motor "Pully Tool" has been made to measure from the motor tops rather than from the top of the shaft

BOM has been updated to show "Washers / Shims" for the bearing stacks

XY_Upper_Joint Fixings changed from M3x6mm to M3x8mm on CAD

PIN GUIDE has been added to help users get the best from TULIP

MGN9H BETA (yes H) has been added for those wanting to use this type of rail setup. All printed parts needed are in the STL's frolder MGN9H.
> **Note - A 160mm Rail is required for full travel**

----

04/09/24

CAD v27 release

Amended Pin hole depth on parts

- Top_Mount_A_MGN9C_x1
- Top_Mount_B_MGN9C_x1

Motor "Pully Tool" has now been added to help get them in the right place

Picture of the tool has been added to the PICS folder

STL's have been updated for the latest change for the parts affected

----

24/08/24

CAD v26 release

CAD names have been updated to be consistant with the STL names and the [a] for accent colour marking has also been added. Corrected a mistake where the Voron Logo was mirrored on Mid_Mount_A_x1.

STL's Updated to latest Names denoting the [a] for accent colours. corrected Mid_Mount_A_x1 STL

----

08/08/24

CAD v25 release

Idler tensioners static body had printability update to make B side easier to print (less chance to warp off the bed)

tensioner upers had changes to work with new static bodies

Tensioner lowers captive nut minor geometry changes - better pre-engagement with tension screw - reduced hole size after captive nut to act as tension screw "nylock"

LazyCam static bodies added for those wishing to use the LazyCam system (type C)

----

10/07/24

CAD v24 release

Idler tensioners static body is now one piece and printed on its side

Idler tensioners lock screw is now static with slot in tensioner parts

XY joints had some holes resized and some minor corrections

Spacers - new fillet chamfer design (fillamfer)

AB Motor mounts plates and mid parts have locating tabs to secure each other together for more secure umbilical plate attachment

Tools added - Bearing insert tool & Drill jig for access to tensioner locking screw

----

**Links to original source material**

https://github.com/VoronDesign/Voron-0

https://vorondesign.com

https://github.com/akinferno/Voron0/tree/main/LazyCams

https://github.com/ruiqimao/VoronUsers/tree/v0.2-mgn9c/printer_mods/ruiqimao/V0.2_MGN9C_X

**GNU Terry Pratchett**

----

**special thanx for all thoes who have helped with feedback and improvement ideas to get Tulip as good as it is!**



