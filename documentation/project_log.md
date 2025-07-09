# Project Log

## Restarting project (2025/05/12)

The "Crabsy" project has been elevated from a small experiment of @SamuelNoesslboeck to a Team project to improve the quality of software and especially AI. As a first step, the repo has been moved an split up, with this repo containing only the construction and electronics from now on (everything concerning the hardware).

![Old construction state](captures/1_old_cad.PNG)

## Road towards first build (2025/05/26)

### Body and baseplate upgrades

For the new AI controlled version, a first build is currently in the making, with focus on basic controls for first tests. For that a new body was constructed, using a more enhanced baseplate, that correctly embeds all components.

<p align="center">
    <img src="captures/2_core_rework.PNG" width="48%" />
    <img src="captures/3_core_rework_further.PNG" width="48%" />
</p>

![](captures/4_crabsy_2025_05.PNG)

### New design of leg segments

As it is common with hexapods, the last segments of the legs are rotated 90° downwards, resulting in the robot standing when all angles are set to their neutral position. Similar to crabs, the segments have been designed to resemble shells.

![](captures/5_crabsy_new_legs.PNG)

## Creating first build (2025/05/27)

First all leg segments and the baseplate have been printed out and assembled accordingly. 

<p align="center">
    <img src="pictures/1_first_legs.jpg" width="48%" />
    <img src="pictures/3_hexapod_done_2.jpg" width="48%" />
</p>

Afterwards, the baseplate has been equipped with it's electronic components, which are:

- The two PCA9685 16 channel servo controllers on top of the baseplate
- The battery module strapped to the bottom

Additionally, the next layer of the base has been attached to the passing screws, using 

- An ESP32 (NodeMCU32S) and
- A buck converter to 5V

as it's electronics. The finished build looked as follows:

<p align="center">
    <img src="pictures/5_next_layer_1.jpg" width="60%" />
</p>

The design of the lower hull part worked pretty well too by being attached to the bottom base layer with screws driving into nuts that have been slotted into fitting cut-outs as it is usual for 3D-printed parts.

### Issues and solution ideas for next design (2025/06/18)