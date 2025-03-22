---
layout: post
title: Series-Wheeled Legged Control System Design and Implementation
date: 2023-06-29 23:18 +0800
last_modified_at: 2023-10-01 01:08:25 +0800
tags: [LQR Control,PID Wheeled Legged]
toc:  true
---
## Abstract
This post describes the design and implementation of a 3-DOF wheeled-leg robot chassis, integrating wheeled and legged movement for enhanced mobility.
<!--more-->

## i System Design    
  - Designed a <mark> 3-DOF wheeled-leg </mark> robot chassis, integrating wheeled locomotion with legged movement to enhance mobility and adaptability across diverse terrains. 
    
## ii Control Algorithm  
  - Implemented a high-stability control algorithm leveraging a <mark>Kalman</mark> fusion observer for real-time state estimation and sensor data integration.   
  - Adopted a hybrid control approach combining Linear Quadratic Regulator <mark>(LQR)</mark> for optimal trajectory control and Proportional-Integral-Derivative <mark>(PID)</mark> controllers for precise motion adjustments. 

## iii	Embedded System Development  
  - Developed an embedded system to execute the control algorithm, enabling seamless coordination between the robot’s wheels and legs.   

## iv	Experimental Validation
  - Conducted tests to validate the stability, precision, and adaptability of the control system under various operational scenarios, ensuring optimal performance across complex environments.    
    
## V Pictures
- i.   
![wheeled-legged-1.png](/pictures/wheeled-legged-1.png)
- i.   
![wheeled-legged-2.png](/pictures/wheeled-legged-2.png)


For more information about this theme, you can search the [repository](https://github.com/sos-xiaobai/ch32v307-Whell-Leg).




[^fn-sample_footnote]: Handy! Now click the return link to go back.
