---
layout: post
title: SowBot – Autonomous Reforestation Robot
description:   SowBot is a reforestation robot developed to assist park rangers and conservation
  teams in planting seeds across difficult, off-road terrain. Our goal was to reduce the
  physical labor and time required for ecosystem restoration using a modular, robust robot
  capable of automated digging and seed deposition.
skills: 
  - Embedded Systems
  - CAD & 3D Modeling
  - Rapid Prototyping
  - Mechatronics Integration
  - C/C++ (ESP32)
  - Team Collaboration & Teamwork
  - Debugging & Testing
main-image: /mainone.png

---
## Hopper Sub-System
<br>
I led the design and fabrication of the hopper system, using Onshape for CAD modeling and rapid prototyping techniques to bring it to life. The process began with brainstorming different hopper concepts. Our design was guided by two key constraints: the motor needed enough torque to rotate a consistent number of seeds, and the mechanism had to ensure reliable seed delivery of 3-5 seeds. Drawing inspiration from a carousel, we developed a system in which a wheel is mounted on a drive shaft, connected to a motor via a coupling. By using a stepper motor to rotate the wheel in 1/3 increments, we could accurately prime the hopper for seed deployment. The wheel driving the separation of seeds was subjected to iteration, making the number of seeds per deployment more reliable. 

{% include image-gallery.html images="hopper.png" height="400" class="center-image" %}

---
## Integration 

{% include image-gallery.html images="sowbot.png" height="400" class="center-image" %}

<br>
In addition to designing the hopper system, I contributed to other subsystems to support overall integration. I developed the control code for the hopper, including a shimmying action before seed deployment to reduce jamming. I also assisted in debugging and refining the codebase, which included tuning PID controllers to enhance system performance. A key part of my role involved integrating the control system using the ESP32 microcontroller to coordinate motor drivers and subsystem timing. Throughout the project, I collaborated closely with teammates to fine-tune components and ensure smooth, cohesive operation.

{% include youtube-video.html id="0Jb2fv8mrp4" autoplay= "false"%}

{% include youtube-video.html id="fNidWjG556g" autoplay= "false"%}

---
## Challenges/Lessons
<br>
 One of our biggest challenges was ensuring that each subsystem functioned reliably when 
integrated, particularly synchronizing the auger motion with the seed release timing. Through 
frequent prototyping and testing, we quickly realized the importance of clearly defining 
interfaces early in the design process and coordinating realistic timelines across subteams. 
A key difficulty was managing team collaboration—assigning responsibilities, planning meetings,
and maintaining alignment. Early in the project, we learned that consistent and open communication 
between subteams is essential to achieve seamless integration of all components into a cohesive system.



