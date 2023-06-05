---
title: "Open-Source Plotter"
description: "This is the short description."
date: 2023-06-05
draft: false
tldr: "This is the tl;dr" # (optional)
tags: ["plotter", "raspberry_pi"] # [tag names] (optional)
---
## THE OPEN-SOURCE OPTION

This post describes the “new” navigation system onboard our 1976 Hallberg-Rassy Rasmus 35. The quotation marks are there because the “new” system is actually a bunch of old hardware, connected through a [Raspberry Pi]({{< ref  "what_is_a_raspberry_pi" >}}) single-board Linux computer running OpenPlotter. This open-source, DIY approach allowed us to modernize our system at a fraction of the price of a commercially available package. Hopefully this post can help provide some inspiration and resources for anyone wanting to undertake a similar project.

We needed a new system because we were going long-distance cruising. Our plotter, while fully functional, had outdated maps. Updated ones were no longer being produced for it. We also could not add a modern AIS unit to our system, since it relied on now-obsolete wiring and communication protocols. These are common problems, as producers of marine electronics tend to reinvent the wheel with new map formats, wire standards and communication protocols every few years. The new wheel unfortunately tends to be incompatible with any previously produced wheels. So if you have a flat, it is probably best to [replace the whole car...](https://www.youtube.com/watch?v=DHXBacEH0qo)

So what are the advantages of an open-source system? The most obvious is cost. You can reuse many things you already have, get “obsolete” marine hardware second-hand for peanuts and then connect it to an inexpensive [Raspberry Pi or similar]({{< ref  "what_is_a_raspberry_pi" >}}). A less obvious but equally important advantage is repairability. Most of the components in our system can be sourced cheaply at electronic stores anywhere. Because they are so cheap, we carry spares for almost everything. Finally, the open-source boating community has a wealth of forums, Wikis and YouTube channels. I can say from experience that the open source solution has technical support on a whole different level than its more commercial counterpart.

## THE HARDWARE, THE SOFTWARE

{{< figure src="/images/courage_plotter.jpg" link="/images/courage-plotter.jpg" caption="Click to see a larger version">}}

## THE FUTURE