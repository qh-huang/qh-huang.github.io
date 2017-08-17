---
layout: archive
title: " "
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Department of Electrical Engineering, National Taiwan University, 2008
* M.S. in Department of Electrical Engineering, National Taiwan University, 2010

Work Experience
======
* 2015 - 2017: Advanced Engineer
  * AsusTek
  * Participated the robot project from scratch; in charge of functions related to robot perceptions (SLAM / Localization)
  * Implemented computational-expansive robotic algorithms (mainly SLAM / Localization) on limited, low-cost embedded platforms.
  * Designed and developed debugging tools for robotic navigation.
  * Collaborated with different teams to implement robot navigation feature on Zenbo.

* 2014 - 2015: Engineer
  * An Startup focusing on IC-Design
  * Assisted in design and debug of analog circuit (Hardware / Schematics / PCB) and digital circuit (FPGA/Verilog)
  * Worked on signal experimental design and data acquisition analysis software (MCU / Qt)
  * Managed and maintained laboratory equipment and materials.

* 2011 - 2014: Software Engineer
  * Universal Scientific Industrial Co.
  * System Level Development on Android / Embedded Linux
  * Lead platform team, team scale is 5 engineers.
  * In charge of new hires training on Android / Linux kernel.
  * Devices bring up, Android 4.2 ~ 4.4 (Linux kernel 3.0 ~ 3.4) porting.
  * Customize audio framework of Android system.
  * Design method of audio latency measurement in Android framework.
  * Customize and debug general embedded system feature, such as keypad, SD card, audio, UI, power management, etc.
  * Design Android Muti-Flash tool (Win32 Application) for production line.
  * Design IC-module testing program based on bootloader (U-Boot) to replace the one relies on OS environment. This improvement significantly accelerate testing procedure of manufacturing.


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
