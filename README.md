# The [TMF-1](https://github.com/TudorSupica/TMF)

The TMF-1 is a Modular Footswitch board (hence the MF in the name) which aims to simplify the process of pedal making by integrating the footswitch, power and effect LEDs and the voltage divider into a single board.

The purpose of the TMF is to be modular, so that I can attach it to any effect pedal I might design in the future, without mutch trouble.

# [The Schematic](https://github.com/TudorSupica/TMF/blob/main/schematic/TMF.pdf)

![TMF_Schematic](https://github.com/user-attachments/assets/e463a493-cecf-4a01-919c-8c5612154258)

The schematic is rather simple.

It consists of only a few parts: the footswitch, four resistors (R1 and R2 form a voltage divider while R3 and R4 are curent limitting resistors for the LEDs), two LEDs (no, color does not matter), two JST connectors, and finally two filtering capacitor (C1 and C2).

I removed the "anti-stupid" protection diode since the power for the board is supplied via a 4-pin JST connector that can't be plugged backwards, thus no need for the diode.

# [The PCB](https://github.com/TudorSupica/TMF/tree/main/PCB)
![3D-isometric](https://github.com/user-attachments/assets/f4155b56-73d0-42c7-9d3d-c72b8ad6e72f)

The PCB design was done such that when i order from JLC-PCB I can get as many boards as cheap as possible (turbo capitalism type shi).

I added four screw mounting pads connected to the ground plane for each board so that when i add the enclosure, the whole module gets shielded from EMF.

I also added vias for better connection and reduced capacitance between the ground planes.
