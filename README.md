# Open Source Traffic Monitor Enclosure 3D Printing Models

The Traffic Monitor (TM) enclosure is designed to comfortably house your Raspberry Pi -based traffic monitoring equipment.

Visit the [Traffic Monitor homepage](https://www.trafficmonitor.ai) or the [Traffic Monitor GitHub repo](https://github.com/glossyio/traffic-monitor) to learn more about the project, instructions to build your own, and links to buy it.

**What does this repo contain?**

This repository contains the `.stl` files for the Traffic Monitor 3D enclosure to print via your FDM 3D Printer.

## Features

- Outdoor, weatherproof design to prevent water and dust infiltration for your traffic monitor components.
- Designed to fit the Traffic Monitor recommended hardware: camera, radar, and AI co-processor (environmental / air quality sensors require modified enclosure).
- 1/4"-20 screw insert holes on bottom and back for compatability with a variety of camera -style mounting hardware.
- Built-in Arca-Swiss Quick Release System -compatible plate to quickly and easily clamp onto compatible tripods.
- VESA mount -compatible M4 screw insert holes at 75 and 100 mm on the back.

![Enclosure Top](static/img/tm-encl-top-mk1.png)

![Enclosure Bottom](static/img/tm-encl-bottom-mk1.png)

## Printing Notes

This is designed to be printed without supports to minimize plastic waste and post-printing work, using the 45-degree rule, but YMMV.

**Materials**
- ABS or ASA are recommended for outdoor deployment; however, these matrials are often harder to print.
- PETG is a good alternative to ASA but provides less UV protection; prime and paint the exterior prior to deployment.
- PLA may be used for indoor-only deployments or test prints.

**Settings**
- Infill may be set as low as 8% or less, as the case will still be strong and protect internal components.
- Walls should be multiple layer (4+ layers), especially when screw inserts are used for strength.
- Supports should be unnecessary, as design was made with the 45-degree rule wherever possible.

## Assembly

See Traffic Monitor Build Your Own Device documentation for assembling your TM (_coming soon_)

**Additional Components**

- Required: Window insert of polycarbonate, acrylic, or glass; recommend sealing with silicon adhesive.
- Required: Six (6) of 3mm x 45mm steel dowel pins for hinges (2), latch (2), and latch catch (2).
- Required: Four (4) of M3 * 4mm screw inserts for Enclosure Top mounting board hold down.
- Recommended: Silicon beading for waterproofness on rim inset.
- Optional: Mounting screw inserts
    - Up to two (2) of 1/4"-20 screw inserts on bottom and back
    - Up to eight (8) of M4 * 5 * 5mm screw inserts on back for VESA mount -compatible holes
- Optional: Mounting hardware (dependent on mounting conditions)
- Recommended: Tether with small caribiner clip for mounting failsafe
