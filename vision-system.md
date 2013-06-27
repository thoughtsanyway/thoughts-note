视觉识别系统的设计与实现
============================

Introduction
----------------------------

###### The definition of Vision Recognition System (VRS)

An image recognition system which is composed of a image-capturing device, a computational platform, and a recognition algorithm.

### 视觉系统的分类

##### 从应用角度分类

###### 机器视觉 - 工业视觉检测系统

+ 位置
+ 形状
+ 色彩
+ 纹理

###### 人体生物特征识别系统

+ 人脸
+ 指纹
+ 虹膜
+ 掌纹
+ 步态

##### 从成像维度分类

###### 面阵视觉系统
最常见的视觉系统。使用面阵传感器或相机采集图像或视频。

###### 线阵视觉系统
使用线阵传感器或者线阵相机采集图像。

###### 3D视觉系统

+ 激光
+ 双目
+ 相位调制
+ TOF深度相机

### 机器视觉系统的组成
Three parts

+ An image capturing device
+ A computation platform
+ A recognition algorithm

#### Image Capturing Device

+ light
+ lens
+ camera/sensor chip
+ frame grabber/A/D converter+interfaces
+ Micro-controller

#### Computation Platform

##### Architecture
+ x86
+ Arm
+ DSP
+ 51
+ FPGA

##### Operating System
+ Win XP/7/8 32/64 bit
+ Linux
+ Android
+ Mac
+ Other Embedded System: VxWorks, RTOS...

#### Recognition Algorithm

##### Functions
A biometric system should provide enroll, verification, and identification functions.
A machine vision system should provide measurement, localization, object tracking, object recognition, texture analysis etc.

##### Fields
+ Image Processing
  + Image Preprocessing/Normalization
  + ROI extraction
+ Pattern Recognition
  + Feature Extraction
  + Classification
+ Machine Learning

A simple face recognition system
-----------------------------

To demonstrate the structure of a vision system, a face recognition system is proposed as a first simple example.

The structure is like this.

1. The image capturing device is a USB camera  .
2. The computation platform is a laptop computer as .
3. The development environment should be based on Qt and OpenCV libraries 