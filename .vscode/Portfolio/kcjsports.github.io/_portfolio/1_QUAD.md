---
title: TURTLE Quadruped Project (QUAD)
excerpt: A series of quadrupedal robots developed with TURTLE Robotics at Texas A&M University<br/><img src='/images/QUAD/QUAD_V2.png'/>
collection: portfolio
---

| ![QUAD V2](/images/QUAD/QUAD_V2.png) | ![Mini QUAD V1](/images/QUAD/Mini_QUAD_V1.png) |
| :----------------------------------: | :--------------------------------------------: |
|        *QUAD V2 (Fall 2025)*         |           *Mini QUAD V1 (Fall 2024)*           |

Posters: [Fall 2025](/files/QUAD/QUAD_Poster_Fall_2025.pdf), [Spring 2025](/files/QUAD/QUAD_Poster_Spring_2025.pdf), [Fall 2024](/files/QUAD/QUAD_Poster_Fall_2024.pdf)  
Code: [QUAD V2](https://github.com/turtle-robotics/quad-v2), [QUAD V1](https://github.com/turtle-robotics/quad)  

QUAD was a project for [TURTLE Robotics](https://turtlerobotics.org), an undergraduate robotics student organization at Texas A&M, with the aim of developing a series of quadrupedal robots and exploring the capabilities of legged robotics. I joined the project during the redesign of the third revision \[Mini Quad V1\] of the QUAD robotic dog, where I was responsible for designing the robot legs. Upon completion of Mini Quad, I assumed the role of mechanical lead for QUAD V2 and oversaw the year long design process from pitch to full system testing. 

## QUAD V2: February 2025 – December 2025

QUAD V2 is a modular 3D printed robotic dog, weighing 15 kilograms with an individual joint torque of 30 newton-meters using a 19:1 custom cycloidal gear reduction on each motor. This robot was designed and produced in around a year, and completed in Fall of 2025. In the production of this robot, I practiced mechanical design, including holding two design reviews for the leg and chassis subsystems. My work included system design, system integration, and electronic specification. QUAD V2 was designed to be a successor for the previous QUAD robots, improving the controllability of the robot with motor drivers, high joint torque limits, and looser power constraints.

This revision was designed around the mjbots electronic architecture. All 12 motors are high-torque mj5208 brushless motors driven by moteus-r4.11 and moteus-c1 motor controllers communicating through CAN. I also used the mjbots power distribution system and Raspberry Pi 4 for processing. To remain within TURTLE's manufacturing capabilities, most parts were designed and made through FDM additive manufacturing including: PETG for the chassis, carbon fiber infused PETG for the legs and gearboxes, and polycarbonate for the motor shafts. Due to budget constraints, the chassis frame was adapted to use PVC pipes rather than the planned carbon fiber rods. The chassis panels are detachable, held together with magnets.

Responsibilities as Mechanical Lead:
- Coordinating the system design of the robot including the chassis and testbeds
- Ensurance of organized and fully defined CAD w/configurations
- Hands on design of of the robotic leg

Individual Contributions:
- Serviceability -> modular subsystems and replaceable actuators
- Two gearbox configurations used for the three actuators
- Grease trap to allow cycloidal lubrication without entering motor
- Knee ROM of 115.2° with bend of 35° and 150.2° extension
- Reusable silicon foot molds with embedded sensor
- Leg electronics: 3 moteus-c1, 3 mj5208 brushless motor, Foot sensor

| ![V1 Leg](/images/QUAD/V1_Leg.png)         | ![V2 Leg](/images/QUAD/V2_Leg.png)      | ![Silicon Foot Molds](/images/QUAD/Foot_Molds.png) | ![V2 Leg with Final Components](/images/QUAD/Parts.png)   |
| :----------------------------------------: | :-------------------------------------: | :------------------------------------------------: | :-------------------------------------------------------: |
|        *V1 Leg*                            |           *V2 Leg*                      |           *Silicon Foot Molds*                     |        *V2 Leg with Final Components*                     |

## Mini QUAD V1: January 2025 - May 2025

Mini QUAD V1 is a small and light 3D printed quadruped. It was created as a platform to develop software algorithms for QUAD V1. The motivation for creating a smaller robot was to allow for quicker design iterations with smaller, low cost, and low maintenance parts.

Mini QUAD V1 runs on a Raspberry Pi Zero 2 W and shares software with QUAD V1. It has a 7 volt servo driver for the MG92B micro servos on each leg. The lower legs are tendon-driven like Boston Dynamics’ Spot and Unitree’s Go.

Responsibilities as sub-team lead:
- Allocated component goals, bounding boxes and mounting geometry
- Hands on design of all upper leg components 

Individual Contributions:
- Linear leg control mechanism
- 180° Hip range of motion
- Knee bend of 37.46° with 130.72° extension
- 6701-2RS 12x18x4mm ball bearing for reduced servo load
- Femur width of 22.85mm
- Electronics: 12 MG92B micro servos, RPi Zero 2W, RPI camera module 3, RPi Servo Bonnet, and 9-DOF IMU



| ![QUAD V2 at TURTLE Showcase](/images/QUAD/QUAD_V2_Showcase.jpg)  | ![Mini QUAD V1](/images/QUAD/Mini_QUAD_V1.jpg)|
| :---------------------------------------------------------------: | :-------------------------------------------: |
|       *QUAD V2 on display at 2025 TURTLE Project Showcase*        |                 *Mini QUAD V1*                |