# Z-Axis Assembly

![](../img/z_axis_assembly/z_axis_assembly.png)

---

## Identifying Extrusions

This section of the build contains a number of C-beams that are close together. To help you identify which parts are which, lay out your extrusions like the diagram shown below. The next steps will then highlight which extrusions are used for each step.

!!! info "Components Required"
    ```
    A: Openbuilds 4080x260mm C-Beam
    B: Openbuilds 4080x260mm C-Beam
    C: Openbuilds 4080x250mm C-Beam
    D: Openbuilds 4080x120mm C-Beam
    ```
![](../img/z_axis_assembly/y_axis_step_42.png){: .shadow}

---

Extrusions `A` and `B` are the main Z-column extrusions.

![](../img/z_axis_assembly/y_axis_step_43.png){: .shadow}

---
## FMJ

*[FMJ]: Full Metal Jacket

!!! tip "Full Metal Jacket Installation"
    If you have Full Metal Jacket plates instead of the 3D printed column joining plates, please refer to the [FMJ Assembly](./fmj_assembly.md) guide. Once complete, you can return to the [Lower Bearing Block](#lower-bearing-block) section and continue your Z-Axis assembly.

---

## Installing the Column Plates

!!! info annotate "Components Required"
    ```
    20 x M5x12mm BHCS
     1 x Joining Plate B        (1)
     1 x Joining Plate C        (2)
     1 x Joining Plate B Mirror (3)
     1 x Joining Plate C Mirror (4)
    ```
1. :material-printer-3d-nozzle-heat-outline: Print this part using the [recommended settings](../../printing/print_guide.md#main-column)!
2. :material-printer-3d-nozzle-heat-outline: Print this part using the [recommended settings](../../printing/print_guide.md#main-column)!
3. :material-printer-3d-nozzle-heat-outline: Print this part using the [recommended settings](../../printing/print_guide.md#main-column)!
4. :material-printer-3d-nozzle-heat-outline: Print this part using the [recommended settings](../../printing/print_guide.md#main-column)!


Place extrusions `A` and `B` facing each other, creating an internal channel. This is where the ballast box can be installed (later, calm down cowboy!).

Install Joining Plate B and Joining Plate C on one side, using M5x12 BHCS to hold the extrusions together.

![](../img/z_axis_assembly/y_axis_step_46.png){: .shadow}


---

!!! tip
    Make sure there is a `67mm` vertical spacing between the lower and upper column plates. The top of the thin part of the uppermost column plate should be flush with the top surface of the C-Beams.

![](../img/z_axis_assembly/y_axis_step_47.png){: .shadow}

---
Select extrusion `D`.

![](../img/z_axis_assembly/y_axis_step_45.png){: .shadow}

---

Place  extrusion `D` at the top of the column with the channel facing _outwards_.

![](../img/z_axis_assembly/y_axis_step_48.png){: .shadow}

---

Use M5x12 BHCS to hold the extrusion in place against the column.

![](../img/z_axis_assembly/y_axis_step_49.png){: .shadow}

---

Select extrusion `C`.

![](../img/z_axis_assembly/y_axis_step_44.png){: .shadow}

---

Place it on the front of extrusion `D`, again with the channel facing _outwards_.

![](../img/z_axis_assembly/y_axis_step_50.png){: .shadow}

!!! tip
    The lower edge of extrusion `C` should be `18mm` above the lower edge of extrusion `D`, making room for the lower bearing block.

---

![](../img/z_axis_assembly/y_axis_step_51.png){: .shadow}

---
<!-- TODO do a composite image showing the zoom in -->

Use M5x12 BHCS to hold the extrusion in place against the column.

![](../img/z_axis_assembly/y_axis_step_52.png){: .shadow}

At this point, you can install Joining Plate B Mirror and Joining Plate C Mirror on the other side of the column, taking care to align them with the plates on the other side.

---
## Lower Bearing Block

!!! info annotate "Components Required"
    ```
    4 x M5x12mm BHCS
    1 x 608ZZ bearing
    1 x Z-Axis Bearing Block (1)
    ```
1. :material-printer-3d-nozzle-heat-outline: Print this part using the [recommended settings](../../printing/print_guide.md#z-axis-assembly)!

Push the 608ZZ bearing into the bearing block until it is flush.

![](../img/z_axis_assembly/y_axis_step_53.png){: .shadow}

---

Use M5x12mm BHCS to attach the bearing block to the bottom of extrusion `C`.

![](../img/z_axis_assembly/y_axis_step_54.png){: .shadow}

---

## Ballast Box

The ballast box is designed to house a damping load such as sand or epoxy granite. It is not a requirement but is recommended.

!!! info annotate "Components Required"
    ```
    1 x Ballast Box (1)
    1 x Ballast Cap (2)
    ```
1. :material-printer-3d-nozzle-heat-outline: Print this part using the [recommended settings](../../printing/print_guide.md#main-column)!
2. :material-printer-3d-nozzle-heat-outline: Print this part using the [recommended settings](../../printing/print_guide.md#main-column)!

![](../img/z_axis_assembly/y_axis_step_56.png){: .shadow}

!!! tip
    There is a small lip in the ballast box which registers with the tongue on the ballast cap.
    This is easiest to install at an angle.

!!! warning
    Once the ballast top is installed, it can be difficult to remove.
    Be sure that no other steps need to be taken before sealing the lid.

---

![](../img/z_axis_assembly/y_axis_step_57.png){: .shadow}

---

## Z-Axis Anti-Backlash Nut

!!! info annotate "Components Required"
    ```
    4 x M3 Heat-Set Insert
    4 x M3x8mm SHCS
    2 x M5 Heat-set Insert
    2 x Brass Lead-screw Nut
    1 x Locking Collar
    1 x Z-Axis Anti-Backlash Nut (1)
    ```
1. :material-printer-3d-nozzle-heat-outline: Print this part using the [recommended settings](../../printing/print_guide.md#z-axis-assembly)!

Insert the M3 and M5 heat-set inserts in the Z Axis Anti-Backlash Nut.
<!-- This image is reused from the y axis assembly on purpose -->
![Insert the M3 and M5 heat-set inserts in the Z Axis Anti Backlash Nut](../img/y_axis_assembly/y_axis_step_5.png){: .shadow}

---

Fasten the Brass lead-screw nuts on either side of the Z Axis Anti Backlash Nut using M3x8mm SHCS. Remember to apply medium-strength threadlock here, sparingly!

<!-- This image is reused from the y axis assembly on purpose -->
![Fasten the Brass lead-screw nuts on either side of the Z Axis Anti Backlash Nut using M3x8mm SHCS](../img/y_axis_assembly/y_axis_step_6.png){: .shadow}

---

Insert the lead-screw into the anti-backlash nut and set the preload using the same technique as the X and Y nuts.

![](../img/z_axis_assembly/y_axis_step_58.png){: .shadow}

---

Place a locking collar onto the bottom of the lead-screw, and lock it in place. Remember to apply medium-strength threadlock to the grub-screws!

![](../img/z_axis_assembly/y_axis_step_59.png){: .shadow}

!!! tip
    The locking collar should sit 13mm from the bottom of the lead-screw.

---
<!-- TODO do a composite showing the zoom -->
![](../img/z_axis_assembly/y_axis_step_60.png){: .shadow}

---
## Z-Axis Rails and Lead-screw

!!! info annotate "Components Required"
    ```
    8 x M3x10mm SHCS
    2 x Brass Lead-screw Nut
    2 x MGN15 Rail 250mm
    1 x Z-Axis Lead-screw
    ```

!!! note
    If you followed the FMJ installation steps, your rails are already installed. Proceed to fitting the lead-screw!

Install the Z rails with only the lower carriages installed onto the `C` extrusion using M3x10mm SHCS. Make sure the end-most and centre-most bolt holes in each rail are used.

Use printed [rail alignment guides](https://github.com/MillenniumMachines/Milo-v1.5/tree/main/STL%20Files/Tools/Rail%20Alignment%20Guide.stl) to make sure the rails are aligned.

![](../img/z_axis_assembly/y_axis_step_60_1.png){: .shadow}

!!! tip
    You can use the rail alignment guides to stop the lower carriages from falling off the vertical rail!

---

Place the lead-screw with the locking collar at the bottom into the bearing at the bottom of the Z-axis. The curved surface of the anti-backlash nut should face upwards.

![](../img/z_axis_assembly/y_axis_step_61.png){: .shadow}

---

Install the upper rail carriages onto the Z rails, above the anti-backlash nut.

![](../img/z_axis_assembly/y_axis_step_62.png){: .shadow}

---

## Z-Axis Mounting Plate and Motor Mount

!!! info annotate "Components Required"
    ```
    16 x M3x5mm SHCS
     2 x M5x16mm BHCS
     2 x 608ZZ Bearing
     2 x M2.5 Heat-set Insert
     1 x GT2 40T Pulley
     1 x Locking Collar
     1 x Z-Axis Mounting Plate (1)
     1 x Z-Axis Motor Mount    (2)
    ```
1. For additional strength this part should be machined :material-saw-blade: but it can be printed :material-printer-3d-nozzle-heat-outline: using the [recommended settings](../../printing/print_guide.md#z-axis-assembly) if necessary.
2. :material-printer-3d-nozzle-heat-outline: Print this part using the [recommended settings](../../printing/print_guide.md#z-axis-assembly)!

Install the Z-Axis mounting plate onto the anti-backlash nut using M5x16mm BHCS.

![](../img/z_axis_assembly/y_axis_step_63.png){: .shadow}

---

Attach the Z-Axis mounting plate to the carriages using M3x5mm SHCS.

![](../img/z_axis_assembly/y_axis_step_64.png){: .shadow}

---

Insert the 608ZZ bearings into the Z-Axis motor mount, and insert M2.5 heat-set inserts for the Z endstop.

![](../img/z_axis_assembly/y_axis_step_65.png){: .shadow}

---

Place a locking collar on the lead-screw.

![](../img/z_axis_assembly/y_axis_step_66.png){: .shadow}

!!! tip
    Tighten the collar slightly so that it stays in place. If you drop it at this point, it will be a pain to fish it out from behind the -Z-axis mounting plate!

---

Install the Z-Axis motor mount onto the top of the C-beam using M5x12mm BHCS.

![](../img/z_axis_assembly/y_axis_step_67.png){: .shadow}

---

Fasten the GT2 40T Pulley onto the top of the lead-screw.

With the Pulley attached above the bearings, you can now loosen off the locking collar below the bearings. Push it upwards until it contacts the lower bearing and lock it in place.

Remember to apply medium-strength threadlock to the grub-screws!

![](../img/z_axis_assembly/y_axis_step_68.png){: .shadow}

---

## Z-Axis Motor

!!! info "Components Required"
    ```
    4 x M5x20mm BHCS
    4 x M5 Nyloc Nut
    4 x M5 Washer
    1 x NEMA23 Motor
    1 x GT2 20T Pulley
    1 x 200mm GT2 Belt
    ```

![](../img/z_axis_assembly/y_axis_step_69.png){: .shadow}

---

When installing the Z motor, attach your belt loosely around your lead-screw pulley and then slide your Z motor in at an angle.

![](../img/z_axis_assembly/y_axis_step_70.png){: .shadow}

---

Attach the motor using M5x20mm BHCS with M5 washers and Nyloc nuts on the upper surface of the Z motor mounting plate.

![](../img/z_axis_assembly/y_axis_step_71.png){: .shadow}

!!! info
    Before tightening the fasteners fully, make sure the tension is set correctly.
    To do this, pull the motor away from the column with one hand until the belt can be strummed like a guitar string and then tighten the fasteners in opposing corners first.

---
## Z-Axis Reinforcement Bracket

!!! info annotate "Components Required"
    ```
    4 x M5x12mm BHCS
    2 x Z Reinforcement Bracket (1)
    ```
1. :material-printer-3d-nozzle-heat-outline: Print this part using the [recommended settings](../../printing/print_guide.md)!

!!! note
    If you have FMJ's on your Z-axis, these reinforcements are unnecessary.

Place the Z Reinforcement Brackets under the Z motor as shown below.

![](../img/z_axis_assembly/y_axis_step_72.png){: .shadow}

---

Attach the reinforcement brackets at the bottom using M5x12mm BHCS.

![](../img/z_axis_assembly/y_axis_step_73.png){: .shadow}

---

And at the top using M5x12mm BHCS.

![](../img/z_axis_assembly/y_axis_step_74.png){: .shadow}

---
## Cable Management
!!! info annotate "Components Required"
    ```
    3 x M3 Heat-set Insert
    2 x M5x12mm BHCS
    1 x Z Drag-Chain Mount   (1)
    1 x Z Cable Redirect Hook (2)
    ```
1. :material-printer-3d-nozzle-heat-outline: Print this part using the [recommended settings](../../printing/print_guide.md#cable-chain-mounts)!
2. :material-printer-3d-nozzle-heat-outline: Print this part using the [recommended settings](../../printing/print_guide.md#cable-chain-mounts)!

Install the M3 heat-set inserts into the Z Drag-Chain Mount.

![](../img/z_axis_assembly/y_axis_step_75_1.png){: .shadow}

---

Install the Z Drag-Chain mount and Cable Redirect Hook using M5x12mm BHCS.

![](../img/z_axis_assembly/y_axis_step_75.png){: .shadow}

---
## Joining Y- and Z-Axes (Standard)

!!! note
    If you have FMJ plates, skip to [Joining Y- and Z-Axes (FMJ)](#joining-y-and-z-axes-fmj)

!!! info annotate "Components Required"
    ```
    18 x M5x12mm BHCS
     1 x Assembled Y-Axis
     1 x Assembled Z Axis
     1 x Joining Plate A        (1)
     1 x Joining Plate A Mirror (2)
    ```
1. :material-printer-3d-nozzle-heat-outline: Print this part using the [recommended settings](../../printing/print_guide.md#main-column)!
2. :material-printer-3d-nozzle-heat-outline: Print this part using the [recommended settings](../../printing/print_guide.md#main-column)!

Attach the assembled Y- and Z-Axes to each other using M5x12mm BHCS through the joining plates.

![](../img/z_axis_assembly/y_axis_step_76.png){: .shadow}

---

## Joining Y- and Z-Axes (FMJ)

!!! note
    If you do not have FMJ plates, follow [Joining Y- and Z-Axes (Standard)](#joining-y-and-z-axes-standard) above.

!!! info annotate "Components Required"
    ```
     8 x M5x12mm BHCS
     1 x Assembled Y-Axis
     1 x Assembled Z Axis with FMJ
    ```

Attach the assembled Y- and Z-Axes to each other using M5x12mm BHCS through the bottom row of holes in the FMJ.

![](../img/fmj_assembly/fmj_step_6.png){: .shadow}

---

## Y-Axis Motor Mount

Attach the Y-Axis Motor Mount to the Z-Axis using M5x12mm BHCS.

![](../img/y_axis_assembly/y_axis_step_77.png){: .shadow}


---
## Spindle Mount

!!! info annotate "Components Required"
    ```
     4 x M5x100mm BHCS
     4 x M5 Washer
     2 x M3 Heat-set Insert
     1 x Spindle Mount Part A (1)
     1 x Spindle Mount Part B (2)
    ```
1. :material-printer-3d-nozzle-heat-outline: Print this part using the [recommended settings](../../printing/print_guide.md#spindle-mount)!
2. :material-printer-3d-nozzle-heat-outline: Print this part using the [recommended settings](../../printing/print_guide.md#spindle-mount)!

Install M3 Heat-set inserts into Spindle Mount Part B.

![](../img/z_axis_assembly/y_axis_step_78.png){: .shadow}

---

Pass the M5x100mm BHCS through the M5 washers and into Spindle Mount Part A and B.

![](../img/z_axis_assembly/y_axis_step_79.png){: .shadow}

---

## Install Spindle Mount

!!! info "Components Required"
    ```
     1 x Spindle Mount
     4 x M5 Nyloc Nuts
    ```

It has come time to install your spindle mount - but do not install your spindle at this point.

Bolt the M5x100mm BHCS through the Z-Axis Mounting Plate

![](../img/z_axis_assembly/y_axis_step_80.png){: .shadow}

---

Attach M5 Nyloc nuts on the back side.

![](../img/z_axis_assembly/y_axis_step_81.png){: .shadow}

!!! warning
    Do not tighten these nuts yet!

---

## Optional: Logo insert

!!! info annotate "Components Required"
    ```
     1 x Millennium Machines Logo (1)
     1 x Glue
    ```
1. :material-printer-3d-nozzle-heat-outline: Print this part using the [recommended settings](../../printing/print_guide.md#spindle-mount)!

If you wish at this point, you can glue in your Millennium Machines Logo.

![](../img/z_axis_assembly/y_axis_step_83.png){: .shadow}

---

## Cable Management... Continued
!!! info annotate "Components Required"
    ```
     6 x M3x6 FHCS
     3 x M3 Heat-set Insert
     2 x M5x12 BHCS
     1 x Z Drag-Chain Mount B (1)
     1 x Drag Chain
    ```
1. :material-printer-3d-nozzle-heat-outline: Print this part using the [recommended settings](../../printing/print_guide.md#cable-chain-mounts)!

Install the M3 Heat-set inserts into the Z Drag-Chain Mount B.

![](../img/z_axis_assembly/y_axis_step_83_1.png){: .shadow}

---

Attach Z Drag-Chain Mount B to the Spindle Mount using M5x12mm BHCS.

![](../img/z_axis_assembly/y_axis_step_84.png){: .shadow}

---

Use M3x6 FHCS to attach the Drag Chain floating and fixed ends to the drag chain mounts.

![](../img/z_axis_assembly/y_axis_step_85.png){: .shadow}

---

Clip the drag chain body into place.

![](../img/z_axis_assembly/y_axis_step_86.png){: .shadow}

---

[Next Chapter: Table Assembly](./table_assembly.md)
