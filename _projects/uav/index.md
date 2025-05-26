---
layout: post
title: Dynamics and Control of Autonomous Flight
description: This course explores the modeling, dynamics, and control of unmanned aerial vehicles (UAVs), with a focus on quadcopters. Through a combination of lectures and hands-on labs, students analyze aerodynamic forces, develop kinematic and dynamic models in 3D, and apply control strategies to stabilize and maneuver UAVs. A major component involves programming a microcontroller to execute a model-based controller on a flying platform.
skills: 
  - MATLAB
  - Eclipse
  - C/C++
  - Embedded Systems
  - UAV Dynamics
  - Sensor Modeling

main-image: /main.png
---

## Objective
The objective of this course was to equip students with the theoretical and practical skills necessary to analyze, model, and control unmanned aerial vehicles (UAVs). By combining lecture-based instruction with hands-on laboratory experience, the course aimed to develop a deep understanding of flight dynamics, sensor integration, control theory, integrating mechanical modeling, and embedded programming. Students applied these concepts by designing and implementing model-based controllers on microcontroller-driven UAV platforms. The overall goal is to use what we learn and complete a simple obstacle course at the end of the semester. 

{% include image-gallery.html images="uav1.png" height="400" %} 

---

## Process
This semester-long project involved close collaboration with a team of three other members, where each of us contributed equally to programming, data analysis, plotting, and documentation. We began by modifying the firmware to spin the quadcopter’s motors and collect data from the inertial measurement unit (IMU) to characterize sensor behavior across different flight states. We then conducted physical testing to map PWM inputs to rotational speed and thrust values using a tachometer and a custom-built moment balance rig. Afterward, we developed 1D and 3D state estimators using gyroscope and accelerometer data, refining them through calibration and drift correction. We implemented nested PID control to regulate the pitch angle using real-time sensor feedback. As the system matured, we integrated additional sensors—including optical flow and range finders—into a unified state estimator. With all subsystems integrated and debugged, the drone achieved stable hover via closed-loop control. For our final test, we programmed the drone to autonomously complete an obstacle course involving takeoff, vertical ascent to at least one meter, forward motion, and a soft landing.

{% include image-gallery.html images="uav2.png" height="400" %}

---
## Video
{% include youtube-video.html id="CYBPboCQD0g" autoplay= "false"%}
<br>
We were the second-closest team to reach the target and were recognized for having the smoothest landing among all teams.
---

# Challenges
One major challenge our group faced was hardware-related. From the start of the semester, we dealt with faulty radios and USB cables that frequently disrupted our connection to the quadcopter, making it difficult—and sometimes impossible—to collect consistent data. Despite continued troubleshooting, the issue persisted throughout the course, forcing us to adapt by borrowing more reliable equipment to complete critical testing. In addition to hardware setbacks, we also encountered difficulties integrating all sensor data due to significant noise, especially from the IMU and optical flow sensor. This required us to implement filtering techniques and refine our estimators to achieve smoother, more reliable readings essential for closed-loop control and accurate system behavior.

