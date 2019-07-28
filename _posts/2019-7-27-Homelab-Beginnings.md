---
layout: post
title: Homelab Beginnings
---

# The Idea

Everybody needs a homelab. 

At least that's what everyone kept telling me when I mentioned I might be building a computer to mess around with. I had never built a computer from parts before, outside of installing some RAM in various family members' computers, so I was looking forward to the prospect of knowing how each piece fit together. 

I wanted to build something that would allow me to host at least 20 virtual machines at a time, and maybe do some other stuff if there is anything left over. I fell down a rabbit hole of homelab content, thinking of all the different things I could host and all the technologies I could learn, but I am getting ahead of myself. 

Here is the hardware (with links to products):
- [AMD Ryzen Threadripper 1920x](https://www.amazon.com/AMD-Threadripper-24-thread-Processor-YD192XA8AEWOF/dp/B074CBJHCT)
  - This was chosen due to cost effectiveness for the number of cores. I knew I wanted to run a fair amount of virtual machines, so I would need a strong CPU to handle that load.
- [NZXT H500i](https://www.amazon.com/gp/product/B07C3STSDB/ref=ppx_yo_dt_b_asin_title_o06_s02?ie=UTF8&psc=1)
  - Having never built a computer from scratch, I liked the idea of being able to see all the insides
- [WD Black 4TB SATA](https://www.amazon.com/gp/product/B07TM7QZDS/ref=ppx_yo_dt_b_asin_title_o06_s03?ie=UTF8&th=1)
  - I wanted a large drive to store all the VMs on
- [Samsung 1TB 970 EVO NVMe M2](https://www.amazon.com/gp/product/B07CGJNLBB/ref=ppx_yo_dt_b_asin_title_o06_s00?ie=UTF8&psc=1)
  - I currently have an SSD in my laptop used for the OS and the speed it offers is spectacular
- ~~[Corsair Hydro Series H115i Pro](https://www.amazon.com/gp/product/B077G3C6HH/ref=ppx_yo_dt_b_asin_title_o06_s04?ie=UTF8&psc=1)~~
  - I had never used liquid cooling and wanted to see what all the fuss was about
  - This particular cooler was a mistake
- [NZXT Kraken X62](https://www.amazon.com/gp/product/B06XX8Q1CL/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1)
- [ASRock X399 Taichi Motherboard](https://www.amazon.com/ASRock-X399-Taichi-sTR4-Motherboard/dp/B074J5R36W)
  - Reviews said this one was good with the Threadripper
  - Has several PCIe slots for future expansion there
- [Corsair RMX Series RM850x PSU](https://www.amazon.com/gp/product/B079H5WNXN/ref=ppx_yo_dt_b_asin_title_o06_s00?ie=UTF8&psc=1)
  - I used an online calculator to determine the approximate power useage
  - I wanted to be able to leave the server running for longer periods of time so I picked what seemed best for that purpose
- [GIGABYTE GeForce GTX 1050 Ti](https://www.amazon.com/Gigabyte-Geforce-GDDR5-Graphic-GV-N105TD5-4GD/dp/B01M4KGTNI)
  - The Threadripper does not have integrated graphics
  - I knew I would not be doing anything super heavy graphics wise to start, so I chose a cheaper and older card just to have some graphic options
  - If I decide I want to do any testing with stronger GPU components later, this can be upgraded
- [G.SKILL Ripjaws V Series 16GB (2 x 8GB)](https://www.newegg.com/g-skill-16gb-288-pin-ddr4-sdram/p/N82E16820231941)
  - This is the only place that could have used improvement
  - 16 GB is fine for now, but I am sure I will be upgrading to more ram soon

## A Case of Improper Cooling

So originally, I had purchased the Corsair H115i Pro cooling system. Reviews said that it would work with Threadripper, and Corsair was a recommended company for cooling systems. However, as I began assembling my system, it was quickly apparent that I was missing something. There was no way for the cooler to fit on the CPU out of the box. I did some research and discovered that there was apparently a special adapter that was needed for this cooler to fit the TR4 socket. This additional part was approximately $20 including shipping, so not a big deal. The adapter arrives and I am excited to finally be able to turn on my build. What a fool I was. This adapter, while appearing to be perfectly designed for the TR4 socket, still does not allow the H115i Pro to fit. This was ridiculous, as that was literally what this part was designed for. I am still not sure what the issue is, other than it seems that the screws just are not long enough to extend and secure the cooler. It may be a motherboard compatibility issue, but at this point I just wanted to have a working computer. 

The result was to purchase a new cooling system, one which I did even more research to determine whether it would work with the Threadripper out of the box. The NZXT Kraken X62 was my answer, and now my case and cooler would match, which I thought would be cute. 

Now I am left with an extra liquid cooling system laying around. Perhaps that will be the basis for the next build...

That's all I have to say about the hardware for now. The next challenges include installing an operating system, and hoping that actually turning on the system doesn't start a fire. 