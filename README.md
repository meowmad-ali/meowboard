# MeowBoard

MeowBoard is a full-sized custom mechanical keyboard designed for those who believe functionality and personality should go hand-in-hand. It's unapologetically bold, unreasonably aesthetic, and entirely open-source. With a sleek ortholinear grid layout and a cat-ear-style diode wave cresting the top, this board isn’t just about typing it’s about making a statement.

Built for the hands of devs, designers, tinkerers, and keyboard freaks who refuse to settle for boring boards, MeowBoard invites you to build, break, and rebuild it your way. Whether you're soldering your first switch or modding your 40th layout, this board is here for the chaos.

---

## The Vision

This board wasn’t born from a tutorial. It was born out of that deep, late-night urge to make something weird and cool that just *works*. It started with the idea of "What if a keyboard looked like it had cat ears and was still ergonomic?" and evolved into a full-featured, encoder-ready, QMK-compatible monster of a project. The name "MeowBoard" came later it kinda named itself.

We wanted to build something that felt like it belonged on the desk of a digital wizard  a board that could run macros, control volume, do RGB flexing, and still slap in a gaming sesh or hackathon.

---

## What Makes It Cool

Instead of throwing a basic layout at you, MeowBoard brings some real sauce:

This PCB was routed with both aesthetic and practicality in mind. The top row has a repeating wave-like array of diode pads that adds a unique vibe to your builds and lets you flex that PCB even when it's not in a case. It's designed to support MX-compatible switches, per-key LED mods, and has enough encoder footprints to run volume, scroll, and even macro layers without breaking a sweat.

Oh, and if you're tired of the default spacebar? Go split. Wanna add OLED? Do it. Want to slap in a knob that controls Spotify? Yes chef.

---

## Features

MeowBoard is not just a keyboard, it’s a canvas for experimentation. Here's the highlight reel:

The board supports a full ortholinear layout with a satisfying uniform grid feel. It's got footprints for three rotary encoders up top, ready for scroll-wheel energy, volume control, or creative macros. The MCU section is built around Elite-C or Pro Micro, so USB-C is fully supported if you’re going for a modern build. The PCB has full QMK support, and we’re adding VIA support soon.

Each switch is individually routed and has through-holes for easy troubleshooting. Routing was done with both symmetry and signal integrity in mind, which means you get both aesthetic PCB porn and actual reliability.

No underglow here   we're keeping it clean, focused, and ready for a case of your choosing.

---

## Gallery and PCB Preview

| Image | Description |
|-------|-------------|
| <img width="803" alt="meowboardpcb" src="https://github.com/user-attachments/assets/73dd79f8-0eee-4a8e-9af0-0c7ebd444028" /> | Top-view of the PCB layout showcasing the unique diode wave, matrix structure, and encoder spots |

| Image | Description |
|-------|-------------|
| <img width="415" alt="schematic" src="https://github.com/user-attachments/assets/9abca0f4-de7f-4c87-92ef-ef1d851db39f" />  | Schematic view showing key switch matrix and controller pin mapping |

| Image | Description |
|-------|-------------|
| _Insert KiCad 3D render here_ | 3D render of the board from KiCad   for a vibe check before manufacturing |

---

## How To Build

You’ll need:

- A soldering iron that doesn’t suck  
- A decent batch of switches (any MX-compatible ones will do)  
- Diodes, preferably pre-bent unless you like pain  
- Your choice of controller RP2040 
- A rotary encoder or three if you're feeling fancy  
- PCB ordered from JLC or similar  
- Patience and snacks

Flash the firmware using QMK Toolbox, test using VIA, and build your layout layer-by-layer until it feels right.

---

## Licensing

MeowBoard is open-source and lives under the MIT License. Build it, remix it, clone it, but please don’t try to make a drop-shipping business out of it. That’s cringe. Give credit, and tag if you post your build   we love to see it.

---

built with caffeine, chaos, and cats
