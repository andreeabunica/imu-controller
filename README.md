# imu-controller
This repository contains all the files developed for controlling a 6 axis robot arm with an IMU strip for the Hardware II Seminar at IAAC 2019/2020, Barcelona. 

# Content: 

A. CONCEPT

B. OVERVIEW

C. HARDWARE & SOFTWARE
- process
- final set-up 

D. APPLICATION 
- live 6-axis control 

# CONCEPT

![](_readMe(assets)/06.jpg)


/initial idea: 
- actuated strip/ small scale robot
- haptic sensing
- object recognition (features, properties)

# OVERVIEW 

!add gh animation here 

/ project definition: 
- flexible strip (position in space & real time movement feedback)

- chained IMUs
- interfaced through Arduino-Processing / Arduino-Firefly-Grasshopper-Machina
- connects to ABB 120 + sends real time position data based on controller strip movement

# HARDWARE & SOFTWARE

ITEM LIST

![](_readMe(assets)/H_00.PNG)

PROCESS

- circuit A 
test

![](_readMe(assets)/Circuit_01_nm.PNG)

/ simple circuit [1 IMU- interfacing between Ardunio & Processing]
(Accel & Gyro Outputs used)

![](_readMe(assets)/E00_A.gif)

- circuit B

![](_readMe(assets)/Circuit_2_nm.PNG)

/ first iteration of chained IMU strip

![](_readMe(assets)/E01_A.PNG)
![](_readMe(assets)/E01_B.PNG)

- initial Arduino serial monitor data visualisation 
(single line stream for all 5 sensors)

![](_readMe(assets)/E02_A.gif)

- cleaned up Arduino serial monitor data (acc + gyro + gravity calculation)

** include video of the cleaned up signal!!!

- circuit C

interfacing with the 6-axis 120 Robot:

/aim: 


/communication: 

![](_readMe(assets)/C_00.PNG)

- grasshopper script: 

# APPLICATION 

/ 1 IMU used as attractor point 
[firefly-grasshopper-machina]

* add video here

![](_readMe(assets)/F_00.gif)
