---
layout: post
title: Edge Computing-Based Visual Guidance System
author: Enze Luo
tags:
- Edge Computing
- Visual
date: 2024-10-01 13:56 +0800
---
## Abstract
This post describes the development of a visual guidance system for a flying vehicle, leveraging edge computing for real-time target detection and attitude control.
<!--more-->

## i. System Design
Designed a system comprising a launcher and a flying vehicle. The flying vehicle is capable of recognizing and precisely striking ground targets. It relies on initial velocity for flight, adjusts its attitude via a tail wing, and achieves target accuracy through <mark>visual guidance</mark>. The launcher provides initial velocity, controls thrust using a tension sensor, and adjusts the vehicle’s yaw angle during launch with a motor.

## ii.	Control Methodology
Leveraged edge computing for real-time target detection and vehicle <mark>attitude control</mark>. The visual guidance system integrates precise target recognition with adaptive attitude adjustment to ensure high-accuracy strikes.

## iii.	Hardware Implementation
- Integrated an embedded <mark>NPU (K230)</mark> for real-time inference of the target detection model.
Used an embedded CPU (K230) to control servo motors that adjust the vehicle’s tail wing for attitude regulation.
- Incorporated an <mark>IMU</mark> to acquire real-time attitude data of the flying vehicle.
- Implemented an embedded <mark>Free-RTOS</mark> system to manage the launcher’s thrust control and yaw angle adjustment during operation.

## iv.	Software Development
Developed and trained the <mark>target detection model</mark>, optimized it for deployment on the embedded NPU, and implemented robust control algorithms for vehicle attitude and launcher operations.

## v.	Experimental Validation
Conducted comprehensive tests to validate the system’s performance under various conditions, ensuring its ability to recognize targets, adjust flight dynamics, and achieve precise strikes.

## Pictures
- i.  
![dart-single.png](/pictures/dart-single.png)
- ii.  
![dart-single-2.png](/pictures/dart-single-2.png)
- iii.  
![dart_sum.png](/pictures/dart-sum.png)

For more information about this theme, you can search the [repository](https://github.com/ZLLCmosasaurus/RMUC-2025/tree/M58-Dart).
