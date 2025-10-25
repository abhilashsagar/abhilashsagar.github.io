# Kaage Pi — A ₹2 K Linux SBC built from scratch
Booting Linux on a hand-soldered Allwinner V3s board.

![Kaage Pi booting Linux](kaagepi_boot.png)

---

## Why I Built It
I wanted to see if a usable Linux single-board computer could be built in India for under ₹2 K using open components and simple tools.  
The Allwinner V3s SoC (ARM Cortex-A7 + 64 MB DDR2 RAM) made it possible, a single chip capable of running Debian Linux without external RAM.


This page documents the journey — from loose components on my desk to a working Debian shell prompt.

---

## Future Work
- Bring-up the LCD (Parallel RGB)  
- Enable Ethernet PHY and ping from Linux  
- Port LVGL on framebuffer   
- Work on SPI NOR flash 

---

## Resources & Tutorials That Helped

I learned a lot from open-source communities and amazing YouTube creators while building Kaage Pi.  
Here are a few that guided me through PCB design, power circuits, and Linux bring-up:

### Embedded Linux & SBC Design
- [Simon Richards – Allwinner V3S SBC](https://simonrichards.com/v3s/) – Detailed build of an SBC with Allwinner V3s, great reference.  
- [wtarreau – BreadBee: Build Your Own Single Board](http://wtarreau.blogspot.com/2020/09/breadbee-build-your-own-single-board.html) – Blog post covering the full hardware/software build of an open SBC.  
- [Popovicu – Making My First Embedded Linux System](https://popovicu.com/posts/making-my-first-embedded-linux-system/) – A beginner-friendly walk-through of embedding Linux on bare hardware.  
- [GitHub – balmerdx/AllwinnerV3S_KiCad](https://github.com/balmerdx/AllwinnerV3S_KiCad) – Open KiCad project for V3s boards, used as a layout reference and inspiration.

[![Phil’s Lab KiCad PCB Design Full Tutorial](https://www.youtube.com/watch?v=aVUqaB0IMh4&t=3288s)  

## License
All schematics, layout files, and documentation © 2025 Abhilash Sagar  
Released under the [CERN OHL-S license](https://ohwr.org/project/cernohl/wikis/Documents/CERN-OHL-version-2).

---

### Follow my work
- [LinkedIn](https://www.linkedin.com/in/abhilashsagar/)  
- [GitHub @abhilashsagar](https://github.com/abhilashsagar)




