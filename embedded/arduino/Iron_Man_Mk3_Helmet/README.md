# Iron Man Mk3 Helmet Replica

A functional, 3D-printed replica of the **Iron Man Mk3 helmet**, integrating Arduino-based control for motion, lighting, and audio effects.  
This project combines mechanical design, embedded electronics, and sound synchronization to recreate the iconic faceplate operation.

---

## Overview

- **Type:** Embedded mechatronic project  
- **Controller:** Arduino Nano  
- **Power:** 3.7 V Li-ion battery with **TP4056** charging module  
- **Actuation:** Dual servo motors for faceplate movement  
- **Lighting:** White LEDs behind diffused lenses  
- **Audio:** Helmet open/close sounds and JARVIS voice lines  
- **Trigger:** Chin-mounted switch for opening/closing sequence  

---

## Features

- Smooth **servo-based** faceplate opening and closing  
- LED fade sequence mimicking the cinematic power-up effect  
- Integrated **sound playback** synchronized to motion  
- Rechargeable via **TP4056** USB module  
- Fully self-contained inside the helmet enclosure  

---

## Visuals

**Helmet Overview**

![Helmet Photo](media/iron_man_mk3_helmet.png)

**Demo Video**

https://github.com/rnelson-electronics/hardware-projects/blob/main/embedded/arduino/Iron_Man_Mk3_Helmet/iron_man_mk3_helmet_vid.mp4

*(Short demo of faceplate actuation, LED sequence, and sound effects.)*

---

## System Overview

| Subsystem | Component | Function |
|:-----------|:-----------|:----------|
| Controller | Arduino Nano | Main logic control |
| Power | 3.7 V Li-ion + TP4056 | Rechargeable battery system |
| Motion | 2× micro servos | Faceplate actuation |
| Lighting | 2× white LEDs | Eye illumination with fade-in |
| Audio | DFPlayer Mini (optional) | Sound playback of helmet effects |
| Interface | Chin toggle switch | Open/close trigger |

---

## Learning Objectives

- Apply embedded control for motion and lighting synchronization  
- Integrate multiple subsystems (mechanical, electrical, audio)  
- Design and test a self-contained battery-powered embedded system  
- Experiment with Arduino-based automation in a physical prototype  

---

## Notes

This project was designed and built as a lockdown experiment in practical embedded design and prototyping.  
All assembly and integration were done manually on perfboard.  
Not affiliated with or endorsed by Marvel or Disney.

---

**Author:** R. Nelson Electronics  
**License:** Personal / Educational Use Only
