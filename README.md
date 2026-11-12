# tinycraft

The world's smallest Minecraft server, on a tiny PCB.

## What this is

tinycraft is a 25×30 mm board that runs [bareiron](https://github.com/p2r3/bareiron), a size-optimized C implementation of the Minecraft server, on an ESP32-S3. I made it as small as I could, with rounded corners, to see how far I could push the size of a working PCB.

## Features

- Runs a Minecraft server from a board smaller than a postage stamp
- Built around the ESP32-S3, so it connects over Wi-Fi
- Serves on your local network, so you can join from any device on the same LAN
- Designed in KiCad, with fabrication outputs included in the repo

## Getting started

1. Get a board from this project, or fabricate one using the files in this repo.
2. Check the pin definitions. If you're using this board, change them to the ones for this layout. If you're not sure, try the defaults first, since they may work as-is.
3. Configure your Wi-Fi network credentials so the ESP32-S3 can connect.
4. Power the board. It should open the server on your LAN.
5. Find the board's address on your network, join it from Minecraft, and enjoy.

## Repository contents

- `tinycraft.kicad_pro`, `tinycraft.kicad_sch`, `tinycraft.kicad_pcb`: KiCad project, schematic, and board layout
- `tinycraft.svg`: board graphic
- `pcb.step`: 3D model of the finished board
- `bom.csv`: bill of materials
- `fabrication-toolkit-options.json`: fabrication settings
- `production/`: manufacturing outputs

## Pictures

### Completed PCB

<img width="724" height="764" alt="Screenshot 2026-10-30 112206" src="https://github.com/user-attachments/assets/2a0bdfe0-b8c7-413f-afbb-8f2ad2e0841f" />

### Front of board

<img width="1520" height="1520" alt="pcb_2026-Nov-12_02-12-07AM-000_CustomizedView5941216004" src="https://github.com/user-attachments/assets/d861aed2-dd04-42c3-86fa-cb2e5c0bc829" />

### Back of board

<img width="1520" height="1520" alt="f4051bfa-f3ec-4756-a9c6-7e3e15bd4561" src="https://github.com/user-attachments/assets/b376e7e8-fd76-4fb9-92ef-acda84664402" />

### Schematic

<img width="3175" height="2245" alt="tinycraft" src="https://github.com/user-attachments/assets/f1089243-7627-4591-b4f5-afe3d032dc70" />

## Why I made it

I've been interested in pushing the limits of how small I can make my PCBs. tinycraft is one project in that series, and I hope more come later.
