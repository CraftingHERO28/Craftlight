## Overview

I designed and built a compact, cost-effective 3-level light indicator (bar graph) powered by an LM339 quad comparator. The core of the circuit relies on an LDR sensor combined with a precise voltage divider ladder to monitor ambient light levels and trigger three discrete LEDs accordingly. 

I deliberately chose an open-board THT (Through-Hole Technology) design without a 3D-printed or plastic enclosure. This decision keeps manufacturing costs low, prevents unwanted shadows or light reflections from distorting the LDR readings, gives me instant physical access to the trimmer potentiometer and coin cell battery holder, and showcases the clean, hand-soldered components and copper traces.

## Challenges Faced

* **Sensor Placement:** Finding the optimal layout geometry was tricky. I had to place the LDR far enough away from the output LEDs to prevent optical feedback, ensuring the LEDs wouldn't accidentally blind the sensor and cause erratic switching behavior.
* **Routing & DRC Clearance:** Managing the traces on a single-sided-friendly layout in KiCad required some patience. I had to carefully resolve a few initial Design Rule Checker (DRC) warnings regarding trace clearance and pad spacing before exporting the final Gerber files for JLCPCB production.
* **Component Footprint Selection:** Balancing aesthetic choices with practical assembly meant sorting out proper THT footprints, such as selecting horizontal axial resistors so the board stays flat, neat, and visually balanced.

*Translated with Google Translator*