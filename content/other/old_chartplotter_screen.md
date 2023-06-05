---
title: "Using an old Chartplotter as a Raspberry Pi screen"
# description: "This is the short description."
date: 2023-06-05
draft: false
# tldr: "This is the tl;dr" # (optional)
tags: ["opencpn", "raspberrypi"] # [tag names] (optional)
---

While building my open-source navigation system, I managed to repurpose the old [Seiwa Barramundi 11″ chartplotter](https://www.marinepanservice.com/en/prodotti/barramundi-plus-11) that came with our boat. The chartplotter had an analog video input that was originally intended for connecting a masthead camera. With a bit of experimentation and the right equipment, I managed to connect to it and transform it into a screen for my Raspberry Pi.

To begin, I purchased a small converter from the producer. This converter allowed me to connect a normal analog component video cable to the chartplotter.

In my initial attempt, I used the Raspberry Pi’s built-in analog video output to establish the connection. However, I noticed that the image quality wasn’t as crisp as I wanted. I opted for the HDMI output of the Raspberry Pi and employed a cheap [HDMI-to-Analog converter](https://www.amazon.com/CIMPLE-CO-Converter-Converts-CONVERTS/dp/B0748NHKW6). This gave a much better result.

Another important step was to properly adjust the overscan settings on the Raspberry Pi to ensure that the image fit correctly onto the screen of the chartplotter. I found an informative [video tutorial on YouTube](https://www.youtube.com/watch?v=RvZDzoDlykg) that guided me through the process of adjusting the overscan settings for my specific Raspberry Pi model.