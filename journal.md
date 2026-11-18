---
title: "Craftlight"
github: "https://github.com/CraftingHERO28/Craftlight"
description: "A simple 3-step LED light indicator built on an open PCB using an LM339 comparator and an LDR light sensor. It runs on a small coin cell battery and shows ambient light levels in real-time."
created_at: "2026-11-18"
total_time: "2h 48m"
---

# November 18, 2026: I selected the parts and connected them to each other.

Using AI, I identified all the components I needed and connected them correctly so that everything should work; I did this using KiCad. It was particularly challenging to determine the correct outputs for the LM339 and to first grasp the fact that there are five distinct sections, even though I only need four of them. Finally, I added the 'Hutprinz' component, ensuring that every part is a THT  component so that it isn't too difficult to solder.

![](https://fabricate.hackclub-assets.com/ad4200bb500bb2d6a959ea38d24011b95059f129529dbc7cf19a3b395cc09859/image-png/Craftlight%20%281%29.png)
![](https://fabricate.hackclub-assets.com/ae33962dc43b912d2e62d766cf4af5e71e997c0b3424ac2f3a70426eaa5748bc/image-png/Craftlight%20%282%29.png)
![](https://fabricate.hackclub-assets.com/eac4fa347b26a350453d557cc18a5cd29f7f72fda3eadb9d52216ea19892815a/image-png/image.png)

**Total time spent: 1h 12m**

# November 18, 2026: I rooted the PCB

I routed the PCB in KiCad. First, I placed the LDR light sensor far away from the LEDs so they wouldn't interfere with the light readings, while keeping the potentiometer and battery holder easy to reach. After routing the copper traces, I ran the Design Rule Checker (DRC) and fixed a few minor spacing issues until everything passed without errors. Finally, I decided to skip a plastic case—it saves money and material, prevents shadows from distorting the sensor, gives me direct access to the trimmer and battery, and leaves the clean THT components and traces visible.

![](https://fabricate.hackclub-assets.com/b3d0f22a8d6f6c49159f1d0b5561c8f4d41e0316f7cc3b5c91d0df57084004b5/image-png/Craftlight%20%284%29.png)
![](https://fabricate.hackclub-assets.com/a80fe33427159a81bafd8de2b0749d5882dc1e2eb86ee754e1e7c0ff56ed63c1/image-png/Craftlight%20%285%29.png)
![](https://fabricate.hackclub-assets.com/1dd8cc839f8fc8073cc4d16adb7c479990ef6312e8e9dcb37a93fe8a9f7ba60c/image-png/Craftlight%20%283%29.png)

**Total time spent: 48m**

# November 18, 2026: Items added to cart, BOM.csv, README

Once I had completed all the work on the printed circuit board, I still needed to source the components. After some research, I found that Reichelt offered the best prices. Furthermore, as it is a German supplier, there are no additional EU taxes or fees to consider. I then created a bill of materials (BOM) in CSV format, which included all the components required for the shopping cart. In addition, I submitted the board design to JLCPCB to determine the costs there; this information is also included in the BOM. Finally, I wrote a README file in German and had it translated using Google Translate.

![](https://fabricate.hackclub-assets.com/3e7838091c4286aff31d7e2cc002e5e4021e9d91708e391e4faf2f5b962cdfaa/image-png/Crafthub%20end%20%281%29.png)
![](https://fabricate.hackclub-assets.com/391f885a7eb883dd2d5c4b65c1fbe0c6169bf4b4ec73bd634ba935e4d17637b6/image-png/Crafthub%20end%20%282%29.png)
![](https://fabricate.hackclub-assets.com/bbb29676ff014647953560ff7b6789eda996e70b4baf02dcd12e719924370a07/image-png/Crafthub%20end%20%283%29.png)
![](https://fabricate.hackclub-assets.com/64b575aa5c00bf59e002f3396f56d37291c087df6044831212ab825087f28186/image-png/Crafthub%20end%20%284%29.png)
![](https://fabricate.hackclub-assets.com/7ff9884d0fc64719ab27ca37b9bb01db6402224f3b4b786f40270e15b619049c/image-png/Crafthub%20end%20%285%29.png)
![](https://fabricate.hackclub-assets.com/68ce719df6e018c08fbc19a2361ceb986cead209bd902f5ad80256d03b096af6/image-png/Crafthub%20end%20%286%29.png)

**Total time spent: 48m**
