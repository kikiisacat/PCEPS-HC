---
title: "Pedestrian/Cyclist Environment Preception System"
github: "https://github.com/kikiisacat/PCEPS-HC"
description: "I've been interested in Tesla's new Full Self Driving system for a while. I want to do this project to learn more about how cars such as Teslas and Waymos use object detection or use LiDAR and the benefits and drawbacks of both and how they train their models to detect the road and people, as well as weird edge cases they might face.\n\nInstead of remaking this on a car, I want to design some type of wearable for humans that can essentially be the same thing, just not on the road. Additionally, I will get to learn more advanced skills like CNN training and PCB design. However, its going to need some small footprint microcontrollers strong enough to run CVs, many breakout boards, and probably a custom PCB as the finished product, as well as batteries and its own enclosure."
created_at: "2026-10-15"
total_time: "2h 30m"
---

# October 15, 2026: Found parts needed for project, and made basic plan
<!-- fabricate:entry 496 -->

I settled on having this project's enclosure be glasses, and made a planning sheet, as well as finding out the parts I need to build this with.
The current one will use a ESP32-S3 as the main microcontroller. A ESP32-P4 works as well. I chose these over something such as a Raspberry Pi Zero because these drain the battery less, while sharing most of the features. The OV5640 will help make the picture quality better compared to a OV2640. A 520 mAh battery will provide enough power while being light for glasses.

![](https://fabricate.hackclub-assets.com/6471591244e35728a76b176b6c85aca84119dba5cd5d8910d5cee9c7cf3b4522/image-png/Screenshot%202026-10-15%20at%205.06.42%E2%80%AFPM.png)

- [BOM.txt](https://fabricate.hackclub-assets.com/77894cc662352bb7f8a83f039184cbe40fca6a07cd1f3ffb5421fc233e811afc/application-octet-stream/BOM.txt)
- [Planning.txt](https://fabricate.hackclub-assets.com/2e8997ab3acedfdfd7ddcd24f26969e79e49fa014c50f453bc219282e12f1e6a/application-octet-stream/Planning.txt)

**Total time spent: 2h 30m**

