---
layout: archive
title: " "
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

(download [pdf here](http://qiao-tw.github.io/files/cv_20180730.pdf))

Work Experience
======
* 2016.03 - Present  
  __Specialist (Algorithm Developer)__, Taipei, Taiwan  
  _AsusTek, Intelligent Robot Business Unit, Artificial Intelligence Div., Computer Vision Dept._
  * In charge of designing and implementing localization system of Zenbo
    * Designed Java API as Android Service for other app development teams
    * Designed and implemented computational-expensive robotic algorithms (mainly SLAM/localization) for low-cost, severely limited sensors and embedded platform of Zenbo
  * Developed software tools to collect and analyze sensor data in real world based on Android, ROS, OpenCV and PCL
  * Worked in team to build SLAM system of Zenbo
* 2015.04 - 2016.02  
  __Advanced Engineer__, Taipei, Taiwan  
  _AsusTek, New Product Business Planning Dept._
  * Placed in charge of SLAM and localization of new robot product, Zenbo
  * Worked in team of 30+ people; attended all meetings to ensure team members understood how SLAM and localization worked
  * Prototype launched at Computex Taipei 2016
* 2014.05 - 2014.12  
  __Engineer__, Taipei, Taiwan  
  _Midas Optronics Corporation (a startup IC design house)_
  * Prototyped IC which implemented a new algorithm to achieve multi-touch capability on surface-capacitive touchscreen,which previously could only achieve single touch capability
  * Emulated analog and digital parts of IC from scratch
    * Emulated digital circuit with FPGA development kit; verified behavior and algorithm by simulation with ModelSim;conducted experiments with programmable-data-generator and logic-analyzer
    * Emulated analog circuit with PCB and breadboard; drew and sent schematics to PCB layout and manufacture firms;conducted experiments with function-generator and oscilloscope
  * Designed software on microprocessor and PC to interpret digital signal from IC to x-y coordinate of touch panel  
* 2011.10 - 2014.04  
  __Advanced Engineer__, Nantou, Taiwan  
  _Universal Scientific Industrial Co., Ltd._  
  _Smart Handheld Devices Division, Software Development Department_
  * Android system-level development
    * Cooperated with _Motorola Solutions_ (now _Zebra Technology_) on embedded devices, led five-person team
    * Responsible for bringing up new hardware platform, including porting Linux kernel driver and Android HAL/framework to new devices
    * Tested phone performance based on CDD/CTS, monkey, stress tests
  * Software tools for mass-production-lines
    * Developed hardware diagnostic program based on bootloader (das U-Boot) to verify conditions of devices without booting into operating system; enhanced efficiency of testing procedure in production lines
    * Developed Android-specific multiple-device flash tool for mass-production in factories; this tool still widely used by _Zebra Technology_’s Android SHD production lines (originally _Motorola Solutions_)

Education
======
* 2008.09 - 2010.06  
  __MSc in Engineering__, Taipei, Taiwan  
  _National Taiwan University_
  * Average 87.39/100
  * Master thesis: Sound Source Localization and Speech Interaction System for Intelligent Mobile Robots; advisor: Professor Ren C. Luo
  * First Prize, Intelligent Security Robot Competition
    * National competition hosted by Shin Kong Security; attended by university students from around Taiwan
    * Objective was to design robot which could navigate rooms of standard residential home autonomously
    * Implemented navigation system based on Monte-Carlo localization and “A-Star” path-planning algorithm
  * “Development of Intelligent Education Entertainment Companion Robot” – “Sound-source Localization Research Project”
    * “Development of Intelligent Education Entertainment Companion Robot” project funded by National Science Council
    * Implemented sound-source-detection system to identify user’s location by sound from scratch
  * “Development of Intelligent Education Entertainment Companion Robot” – “Voice Dialog System Research Project”
    * Frontend: used Microsoft Speech API to build human-robot-interface to enable robot to recognize pre-defined voice commands
    * Backend: designed primitive ROS-like middleware which provided protocols for different software modules to communicate with each other
* 2004.09 - 2008.06  
  __BSc in Engineering__, Taipei, Taiwan  
  _National Taiwan University_  
  * Last-two-years average 81.27/100  

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Extra Curricular Activities
======
* 2004.08 - 2010.10  
__President__, Taipei, Taiwan  
_Zhongshan-ChienKuo Alumni Chinese Orchestra (CKSCO)_  
  * Established society’s standard operating procedure including designating tasks and responsibilities to committee members and setting up guidelines  
  * Oversaw restructuring of society’s finances and revamping society by setting budget, writing proposal, recruiting new members, and organizing concerts  
  * Successfully transformed society into well-known alumni Chinese orchestra in Taiwan by 2008; other societies emulated CKSCO’s model  
  * Hosted large-scale concerts in prestigious concert halls to promote public’s awareness of CKSCO; by 2011, CKSCO concerts were usually sold out

Teaching
======
* 04/2013 - 04/2014  
__New Employees Training Coach__, Nantou, Taiwan  
_Universal Scientific Industrial Co., Ltd._
  * Offered training in how Android HAL/framework, and Linux kernel work and system booting procedure  

* 09/2009 - 02/2010  
__Teaching Assistant__, Taipei, Taiwan  
_National Taiwan University_  
  * Course title: Robot Sensing and Control  
  * Offered undergraduates advice on preparing for Intelligent Security Robot Competition

* 09/2004 - 09/2007  
__Private Tutor__, Taipei, Taiwan  
  * Provided one-to-one tutoring in Physics, Mathematics, and Chemistry from elementary school level to high school level
  * Offered one-to-one tutoring in middle school level English and History
  * Coached students in Chinese Flute

* 09/2004 - 06/2005  
__Teaching Assistant__, Taipei, Taiwan  
_A-Tai’s Physics Center_  
  * Answered students’ inquiries on high school Physics

  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
