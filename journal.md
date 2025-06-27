---
title: "mhmhub"
author: "Daamin Ashai"
description: "a cool looking & compact usb hub"
created_at: "2025-06-20"
---

# mhmhub - a custom usb-c hub

### 20th June (day 1): brainstorming & schematic

lesgetthisstarted
i decided on using 3x usb-c ports, and 1x usb-a port. and another usb-c to plug it in. ill also maybe try to make my own cable? i wont do PD or usb3.0
i got done with the schematic pretty quickly, i took a look at the hackclub jam to figure out the placement of decoupling capacitors. i asked for a review of my schematic, and it was good to go!!! ill begin with my pcb tomorrow since its already 1am :sob:

<image src="assets/schem.png" width="400">

**Time Spent:** 3 hours

### 21st June (day 2): start and finish PCB

i did some digging on LCSC to find the correct parts, and then spent an hour downloading all the right footprints and 3d models. and i was ready to route! this was my first time routing SMD components and it was way harder. im not too proud of my result, since i ended up using a lot of vias, although the PCB was pretty compact. I used around 50 vias for such a small pcb. and i was done :yay:. i did not do the silkscreen yet. i might keep the case transparent, so i NEED some cool silkscreen.

<image src="assets/pcb.png" width="400">
<image src="assets/3dmodel.png" width="400">

**Time Spent:** 3 hours

### 26th June (day 3): top + bottom case done

i started with the bottom and top of the case today. the bottom is just a flat base with a little clearance for the components. the top has cutouts for the usb ports, and i measured the spacing to match the pcb. i didn't do the fastener holes yet. the screws are m2, so ill need to make the cutouts according to the pcb
and then ill be DONE! yay
only issue is I wanna add some cool engraving to the top, but that wont make it printable without supports :/

<image src="assets/topbottom.png" width="400">
Time Spent: 4 hours

### 27th June (day 4): finish CAD, add fastener holes and prepare repo

finished the case!! i added the fastener holes along the pcb. i also cleaned up the chamfers + fillets, i asked in the slack as to whether my fillets were printable, and they were not :sob:
but i changed them with some chamfers and BOOM, done!
then i worked on the BOM and did some basic cleanup of the project files. moved stuff into folders, renamed things, and wrote a short readme. and YAY im done!!

<image src="assets/holes.png" width="400">
Time Spent: 4 hours
