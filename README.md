<img width="498" height="494" alt="pcb_layout" src="https://github.com/user-attachments/assets/1a53de0b-3ae6-4886-a077-b3138f07f6c4" />
# Voltage-Controlled Audio Preamplifier (SMD PCB)

Academic hardware project developed at the **Faculty of Electronics, Telecommunications and Information Technology (ETTI)**, POLITEHNICA Bucharest.

## Overview
A compact audio preamplifier whose amplification level is controlled by a DC voltage adjusted via a potentiometer. The circuit was designed, simulated, and physically built on a 2-layer PCB using Surface-Mount Device (SMD) components.

## Key Features
* **Power Supply:** 14 V DC (with LED indicator)
* **Input Signal:** Sinusoidal, up to 40 mV at 4 kHz
* **Gain Control:** Adjustable from 1x up to 40x using a 50 kΩ potentiometer (0 V – 4 V control voltage)
* **Technology:** 2-layer PCB with 0805 SMD components and BC817-25 NPN transistors

## Tools Used
* **OrCAD Capture CIS & PSpice:** Schematic design and circuit simulation
* **OrCAD PCB Designer:** 2-layer board routing and Gerber file generation
* **Manual SMD Assembly:** Soldering using a hot-air/soldering station (SnAgCu alloy)

## Repository Contents
* `P1_2024_434B_Mindroc_Robert_Andrei_PaCT_N4_LTSpice (2) (1).zip` *(download archive containing all project files)*:
  * `document_final.pdf` – Full technical project report, calculations, and assembly guide
  * `SCHEMATIC/` – OrCAD Capture schematics (`schematic pcb/`), PSpice simulation files (`schematic spice/`), component libraries, and Bill of Materials (`.BOM` / `.ods`)
  * `Layout/` – OrCAD PCB Designer board file (`pcb_proiect1_Mindroc_Robert_434B.brd`)
  * `Gerber si Excellon (DRILL)/` – Manufacturing Gerber files (`TOP.art`, `BOT.art`, solder mask/paste layers) and drill files (`DRILL.drl`)

 ## Circuit & PCB Preview
![Schematic](schematic.png)
![PCB Layout](pcb_layout.png)
