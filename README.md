# imu-controller
This repository contains all the files developed for controlling a 6 axis robot arm with an IMU strip for the Hardware II Seminar at IAAC 2019/2020, Barcelona. 

Content: 

A. CONCEPT

B. OVERVIEW

C. HARDWARE
- process
- final set-up 

D. SOFTWARE
- process
- IMU strip visualisation 
   
E. APPLICATION 
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
- interfaced through Arduino-Processing / Arduino-Firefly-Grasshopper 

# HARDWARE

- ITEM LIST

![](_readMe(assets)/H_00.PNG)

- PROCESS

/ simple circuit 

![](_readMe(assets)/Circuit_01_nm.PNG)

/ first iteration of chained IMU strip

![](_readMe(assets)/E01_A.PNG)
![](_readMe(assets)/E01_B.PNG)

/ initial Arduino serial monitor data visualisation 
(single line stream for all 5 sensors)

![](_readMe(assets)/E02_A.gif)


/ interfacing with the 6-axis 120 Robot

![](_readMe(assets)/C_00.PNG)

# SOFTWARE 

/ simple circuit [1 IMU- interfacing between Ardunio & Processing]
- Accel & Gyro Outputs used

![](_readMe(assets)/E00_A.gif)

# APPLICATION 
![](_readMe(assets)/F_00.mp4)
<video src=(_readMe(assets)/F_00.mp4) width="320" height="200" controls preload></video>
