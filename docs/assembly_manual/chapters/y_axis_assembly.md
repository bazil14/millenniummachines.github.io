# Y Axis Assembly

![Y Axis Assembly](../resources/y_axis_assembly/y_axis_assembly.png)

---

## XY plate orientation

![XY plate](../resources/y_axis_assembly/y_axis_step_0.png)

The XY gantry plate is not an exact mirrored part, and therefore needs to be oriented in the right direction for correct installation..

To make sure that the plate is installed the right way round, rotate the plate until counterbores "a" are facing upwards.

With the counterbores the right way round, locate hole "b" and make sure it is on the right side of the plate.

After this has been done, face "c" will now be oriented towards you. When installed, this face will be towards Y minimum (or towards the operator).

---

> M3x5mm SHCS

![screw the bottom carriages using M3x5mm SHCS](../resources/y_axis_assembly/y_axis_step_1.png)

> M3x10mm SHCS

![screw the top carriages using M3x10mm SHCS](../resources/y_axis_assembly/y_axis_step_2.png)

### BE SAFE, LOCK IT!

These machines vibrate an immense amount when in use, and fasteners are bound to back out. Don't be afraid to add a little bit of medium-strength thread-lock to all your screws to avoid this problem.

### Protect your rail carriages

![dummy rail](../resources/hardware/dummy_rail.png)

Rail carriages should always have a rail or dummy rail installed in them to avoid getting them damaged. If your rails didn't come with dummy rails, then print the ones we provided for you in the print list.

---

> M3 Heat Insert

![insert the M3 heat inserts in the XY dragchain transition](../resources/y_axis_assembly/y_axis_step_3.png)

---

> M3 washer
> M3x20mm SHCS

![fasten the XY dragchain transition to the XY plate using M3x20mm SHCS stacked with one M3 washer](../resources/y_axis_assembly/y_axis_step_4.png)

---

> M5 Heat Insert
> M3 Heat Insert

![insert the M3 and M5 heat inserts in the Y Axis Anti Backlash Nut](../resources/y_axis_assembly/y_axis_step_5.png)

> M3x8mm SHCS
> Brass leadscrew nut

![fasten the Brass leadscrew nuts on either side of the Y Axis Anti Backlash Nut using M3x8mm SHCS](../resources/y_axis_assembly/y_axis_step_6.png)

---

> M3 Heat Insert
> M5 Heat Insert

![insert the M3 and M5 heat inserts in the X Axis Anti Backlash Nut](../resources/y_axis_assembly/y_axis_step_7.png)

> M3x8mm SHCS
> Brass leadscrew nut

![fasten the Brass leadscrew nuts on either side of the X Axis Anti Backlash Nut using M3x8mm SHCS](../resources/y_axis_assembly/y_axis_step_8.png)

---

> M5x16mm BHCS

![fasten the Y Axis Anti Backlash Nut to the bottom of the XY plate using M5x16mm BHCS](../resources/y_axis_assembly/y_axis_step_9.png)

---

> M5x16mm BHCS

![fasten the X Axis Anti Backlash Nut to the top of the XY plate using M5x16mm BHCS](../resources/y_axis_assembly/y_axis_step_9.png)

---

## ANTI-BACKLASH PRELOAD TUNING

Each axis uses anti-backlash* blocks in order to compensate for changes in screw direction during operation. They do this by driving 2 brass TR8x8 lead screw nuts towards each other to engage both sides of the lead screw threads.

In order for this to work the preload required to drive each nut needs to be tuned by hand. To tune the preload make sure the screws are greased appropriately, then loosely install the 2 brass TR8x8 lead screw nuts within the anti backlash block without tightening the bolts too much.
Then install a spare lead screw temporarily in the block and begin to tighten each brass nut equally.
The ideal preload will allow for the leadscrew to still spin by hand but should have a moderate amount of resistance to it.
Once complete make sure each bolt has thread-lock applied, and uninstall the leadscrew - your preload is now set. To avoid any headaches, do this before final installation.

\*Yes technically it's a "zero backlash" nut and not an "anti-backlash nut", but the common term for it is anti-backlash and that's what most people know it as.

---

> M5 Heat Insert

![insert the M5 heat inserts in the Y Axis Motor Mount](../resources/y_axis_assembly/y_axis_step_12.png)

> M2.5 Heat Insert

![insert the M2.5 heat inserts in the Y Axis Bearing Block](../resources/y_axis_assembly/y_axis_step_12_1.png)

---

> F608ZZ bearing
> 608ZZ Bearing

![insert a bearing stack (composed of 1 F608ZZ bearing and 2 608ZZ Bearing) on either side of the Y axis bearing block](../resources/y_axis_assembly/y_axis_step_12_2.png)

---

> C-Beam 470mm
> M5x12mm BHCS

![fasten the Y axis motor mount to the 470mm C-Beam aluminium profile using M5x12mm BHCS](../resources/y_axis_assembly/y_axis_step_13.png)

## Temporarily install the Y bearing block

The Y bearing block is used as a stop to install the Y rails, it will then be removed later so there is no need to thread-lock it at this point.

> M5x12mm BHCS

![fasten the Y axis bearing block to the other end of the 470mm C-Beam aluminium profile using M5x12mm BHCS](../resources/y_axis_assembly/y_axis_step_14.png)

---

## T-Nut installation

Spring T-Nuts are used here to mount the rails but are not shown, install these prior to screwing the bolts in.

> M3x10mm SHCS
> MGN15 350mm Rails

![fasten the MGN15 350mm Rails to the 470mm extrusion screwing M3x10mm SHCS into the spring t-nuts inside the profil](../resources/y_axis_assembly/y_axis_step_15.png)

## Rail centering guide

![amongus](../resources/hardware/rail_alignment_tool.png)

Use the MGN15 guides to position the rail in the center of the extrusion prior to fastening the screws.

---

## Uninstall the Y bearing block

The Y bearing block needs to be uninstalled before being able to install the XY carriage.

![the Y axis bearing block is nowhere to be found in this picture](../resources/y_axis_assembly/y_axis_step_16.png)

---

## Take care when installing carriages onto rails

Improper handling of carriages can damage them - the best way is to install a dummy rail in the carriages and then transfer onto the steel rails.

![carefully slide the XY plate assembly on the Y rails](../resources/y_axis_assembly/y_axis_step_17.png)

---

## Install the Y bearing block for the final time

This will be the final installation of the Y bearing block. Be sure to use thread-lock.

> M5x12mm BHCS

![fasten the Y axis bearing block to the other end of the 470mm C-Beam aluminium profile using M5x12mm BHCS](../resources/y_axis_assembly/y_axis_step_18.png)

---

> 550mm leadscrew
> 8 to 6.35mm rigid coupler

![couple the nema23 motor to the 550mm leadscrew using a 8 to 6.35mm rigid coupler](../resources/y_axis_assembly/y_axis_step_11.png)

---

## Install the Y screw, coupler and motor

From the back of the Y axis, insert the Y screw assembly. Be sure to thread through the Y anti-backlash nut, but do not insert it through the bearing block yet.

![](../resources/y_axis_assembly/y_axis_step_19.png)

---

## Install Locking collar on leadscrew

Before pushing the leadscrew through the bearing block, don't forget to add a locking collar to the inside bearing face. Leave this loose.

![](../resources/y_axis_assembly/y_axis_step_20.1.png)

![](../resources/y_axis_assembly/y_axis_step_20.2.png)

---

> M5x30 SHCS

![fasten the nema23 motor to the Y axis motor mount using M5x30 SHCS](../resources/y_axis_assembly/y_axis_step_21.png)

---

## Install Locking collar on leadscrew

Add the last locking collar on the operator side of the bearing block. Do not tighten the set screw yet.

![](../resources/y_axis_assembly/y_axis_step_22.png)

---

## Locking collar preload

Using your fingers, press each locking collar towards each other - driving them into the face of each bearing with moderate to high pressure. Tighten the operator side collar first before tightening the internal side collar. This will ensure that the screw remains in the same position during use.

_NOTE_: add some medium-strength thread-lock to the set screw.

![](../resources/y_axis_assembly/y_axis_step_23.png)

---

## Y Endstop installation process

To avoid the endstop getting damaged during the rest of the assembly, its a good idea not to install it at this point, but rather install it later with the rest of the wiring.

![](../resources/y_axis_assembly/y_axis_step_23.1.png)

---

> M3 Heat Insert

![insert the M3 heat inserts in the Y dragchain mount](../resources/y_axis_assembly/y_axis_step_24.png)

> M5x12mm BHCS

![fasten the Y dragchain mount to the 470mm profile using a M5x12mm BHCS and a spring t-nut](../resources/y_axis_assembly/y_axis_step_25.png)

---

## Drag chain orientation

Drag chains have 2 different sides - a fixed side and a free side. For this setup, the free side is connected to the rear drag chain mount shown on the last image. The fixed side attaches itself under the XY transition piece.

> M3x6mm FHCS

![fasten one end link of the dragchain to the Y axis dragchain mount using 3 M3x6mm FHCS](../resources/y_axis_assembly/y_axis_step_26_1.png)
![fasten the other end link of the dragchain to the XY axis dragchain transition using 2 M3x6mm FHCS](../resources/y_axis_assembly/y_axis_step_26_1.png)

---

<!-- TODO do a composite image to replicate the zoom in done in the original manual -->

## Cable tie points

It's a good time to mention that the little cutouts that you may have noticed scattered around the build are for your zip ties. Use these to secure your cables where necessary.

## Cable chain optional installation point

You may wish to install the rest of the cable chain now to complete the Y axis, however it is often easier to thread your X axis motor and X endstop cables through the loose chain before installing it as it can become quite a tight space to work in later.
_NOTE_: Remember this chain is for X axis cables despite being mentioned now during Y axis assembly.

![](../resources/y_axis_assembly/y_axis_step_26_3.png)

---

[Next Chapter: X Axis Assembly](./x_axis_assembly.md)