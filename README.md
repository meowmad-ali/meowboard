# MeowBoard

okay so this is MeowBoard  
a full-size ortholinear keyboard with some serious personality  
it’s got a funky diode wave pattern up top, a ton of keys, and space for encoders  
we basically went from zero to full PCB mayhem because a regular keyboard just wasn’t hitting anymore  

MeowBoard is made for the kind of people who actually enjoy soldering till 3am and tweaking layouts for fun  
you want knobs, clean matrix routing, and a cat logo for no reason? we got it  
this board isn’t trying to be minimal  
it’s just trying to be cool

---

## how it started

was messing around with layout ideas and thought  
what if the keyboard had vibes  
like actual vibes  
started sketching some cat-themed stuff  
then just dumped it all into KiCad  
made a clean matrix  
threw in some encoder footprints  
and gave it a top edge that looks like it’s meowing

from there it spiraled into what you see here  
one full-size chaotic energy ortholinear board with layers for days

---

## what’s actually on this thing

this thing has enough key real estate to launch a space shuttle  
it’s using a clean 18x6 ortholinear layout  
MX switch support because yes  
supports both Pro Micro and Elite-C so you can flex with USB-C  
three encoder spots up top because one is boring  
all the rows and columns are routed cleanly, trust me it looks good in the gerbers  
and yeah, there’s a little sukhoi-style logo because why not

no underglow  
no RGB distractions  
just raw switch power

---

## pics or it didn’t happen

| Image | Description |
|-------|-------------|
| ![meowboard-pcb](https://github.com/user-attachments/assets/bfb35075-b8e0-459f-87e9-5e74d0ca21c3) | PCB view in KiCad with the diode wave and encoder spots up top |

| Image | Description |
|-------|-------------|
| _insert schematic screenshot here_ | full matrix wiring with all rows and cols labeled, everything flows nice and tidy |

| Image | Description |
|-------|-------------|
| _insert 3D view screenshot here_ | this is from the KiCad 3D viewer, it looks clean with switches in place |

---

## what’s in the repo

- meowboard.kicad_pcb – the full board file  
- meowboard.sch – schematic  
- firmware folder with QMK stuff and default layout  
- journal.md because yeah we tracked the build  
- meowboard.json for VIA  
- optional 3D printable case and DXF for the plate  

everything here is editable  
go nuts  

---

## wanna build one

you’ll need a soldering iron  
around 100 switches  
diodes  
a microcontroller  
a brain  
and probably some snacks because this takes time  

flash the firmware with QMK Toolbox  
use VIA to remap  
stare at it for a bit  
then start flexing

---

## license thingy

this project is open source  
MIT license  
do what you want but don’t gatekeep  
tag me if you make a build  
meowboard was made with chaos and caffeine so pls respect the drip
