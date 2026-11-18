## Overview

I designed and built a compact, cost-effective 3-level light indicator (bar graph) powered by an LM339 quad comparator. The core of the circuit relies on an LDR sensor combined with a precise voltage divider ladder to monitor ambient light levels and trigger three discrete LEDs accordingly. 

I deliberately chose an open-board THT (Through-Hole Technology) design without a 3D-printed or plastic enclosure. This decision keeps manufacturing costs low, prevents unwanted shadows or light reflections from distorting the LDR readings, gives me instant physical access to the trimmer potentiometer and coin cell battery holder, and showcases the clean, hand-soldered components and copper traces.

## Challenges Faced

* **Sensor Placement:** Finding the optimal layout geometry was tricky. I had to place the LDR far enough away from the output LEDs to prevent optical feedback, ensuring the LEDs wouldn't accidentally blind the sensor and cause erratic switching behavior.
* **Routing & DRC Clearance:** Managing the traces on a single-sided-friendly layout in KiCad required some patience. I had to carefully resolve a few initial Design Rule Checker (DRC) warnings regarding trace clearance and pad spacing before exporting the final Gerber files for JLCPCB production.
* **Component Footprint Selection:** Balancing aesthetic choices with practical assembly meant sorting out proper THT footprints, such as selecting horizontal axial resistors so the board stays flat, neat, and visually balanced.

*Translated with Google Translator*

<img width="905" height="886" alt="Craftlight end (1)" src="https://github.com/user-attachments/assets/fe7d225d-7787-42a3-bd19-7098b499e84b" />
<img width="784" height="488" alt="Craftlight (3)" src="https://github.com/user-attachments/assets/7c479025-9119-42bb-a516-a50d608e54a6" />
<img width="1310" height="817" alt="Craftlight (4)" src="https://github.com/user-attachments/assets/d70dd258-28cf-4008-8912-c61e8ee55941" />
<img width="814" height="761" alt="Craftlight (1)" src="https://github.com/user-attachments/assets/be221663-47e1-4160-b476-4a97ca79db85" />
<img width="1269" height="642" alt="Craftlight (2)" src="https://github.com/user-attachments/assets/e76071bc-b02c-47f9-93c5-1ec2ca7f40b5" />
<img width="1312" height="407" alt="Craftlight end (5)" src="https://github.com/user-attachments/assets/2d0733e3-3fcc-4da4-a379-464d3603fad9" />
