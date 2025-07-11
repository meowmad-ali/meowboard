# MeowBoard

okay so this is MeowBoard  
a full-size ortholinear keyboard with some serious personality  
it’s got a funky diode wave pattern up top, a ton of keys, and space for encoders  
we basically went from zero to full PCB mayhem because a regular keyboard just wasn’t hitting anymore  

MeowBoard is made for the kind of people who actually enjoy soldering till 3am and tweaking layouts for fun  
you want knobs, clean matrix routing, and a cat logo for no reason? we got it  
this board isn’t trying to be minimal  
it’s just trying to be cool

![image](https://github.com/user-attachments/assets/7c30c675-99b5-4631-a9e3-62eb49bd32fc)

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
# MeowBoard Bill of Materials (BOM)

| Component            | Description                              | Qty | Unit Price (USD) | Total Price (USD) |
|----------------------|------------------------------------------|-----|------------------|-------------------|
| Pro Micro            | Main microcontroller (ATmega32u4)        | 1   | 8.00             | 8.00              |
| MX Switches          | Mechanical switches (any MX-style)       | 40  | 0.25             | 10.00             |
| Keycaps              | Custom keycaps for 40 keys               | 1   | 15.00            | 15.00             |
| Diodes               | 1N4148 diodes for matrix                 | 40  | 0.03             | 1.20              |
| Resistors            | For pullups or encoder                   | 10  | 0.02             | 0.20              |
| Rotary Encoder       | Vertical rotary encoder with push        | 1   | 2.50             | 2.50              |
| OLED Screen          | Optional small 128x32 display            | 1   | 4.00             | 4.00              |
| PCB                  | Custom PCB for MeowBoard                 | 1   | 15.00            | 15.00             |
| Acrylic Case         | Laser-cut top and bottom                 | 1   | 12.00            | 12.00             |
| TRRS Jack            | Used for split connections (optional)    | 1   | 1.00             | 1.00              |
| Screws & Standoffs   | Mounting hardware                        | 1   | 2.00             | 2.00              |
| Soldering Materials  | Wire, flux, solder (consumables)         | 1   | 5.00             | 5.00              |
| Miscellaneous        | Labels, packaging, foam, extras          | 1   | 6.10             | 6.10              |

**Total Estimated Cost:** ~$97.00

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
| <img width="803" alt="meowboardpcb" src="https://github.com/user-attachments/assets/d2f3d493-be2e-4af8-a04c-fd0f8338b3a4" /> | PCB view in KiCad with the diode wave and encoder spots up top |

| Image | Description |
|-------|-------------|
| <img width="415" alt="schematic" src="https://github.com/user-attachments/assets/de958ae8-edd7-4e46-b8e3-3fec8c321b89" />  | full matrix wiring with all rows and cols labeled, everything flows nice and tidy |

| Image | Description |
|-------|-------------|
| ![image](https://github.com/user-attachments/assets/53f8f981-f2e7-4d86-a190-e681d76d6a4d) | this is from the KiCad 3D viewer, it looks clean with switches in place |

---

## wanna build one ?

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
