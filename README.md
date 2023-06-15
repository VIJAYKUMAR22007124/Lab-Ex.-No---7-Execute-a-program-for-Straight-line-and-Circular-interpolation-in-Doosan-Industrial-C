# Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-cobot
## Aim : To Execute a program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio.

## Components Required:

*Doosan Industrial Collaborative Robot

*DRL (Doosan Robotics Language) Studio Software

### Theory 
INTERPOLATION

Interpolation, which is necessary for any type of programming, consists of generating data points between given coordinate axis positions. Within the Machine Control Unit (MCU), a device called an interpolator causes the drives to move simultaneously from the start to the end of the command. The interpolator is either an electronic hardware device for a NC system, or a software program for a CNC system. An interpolator provides two functions:

It calculates individual axis velocities to drive the tool along the programmed path at the given feed rate.

It generates thousands of intermediate coordinate points along the programmed path between the start point and the end point of the cut.

During positioning, all programmed axes move simultaneously at the specified feed rates until each axis has reached its destination. All drives start together, but without an interpolator individual destinations are reached successively according to the path traveled. However, an interpolator coordinates these axis motions in such a way that the programmed path is constantly maintained from the beginning to the end of the movement.

Linear and circular interpolation are most commonly used in CNC programming applications:

Linear interpolation is used for straight-line machining between two points.

Circular interpolation is used for circles and arcs.

Helical interpolation, used for threads and helical forms, is available on many CNC machines.

Parabolic and cubic interpolation are used by industries that manufacture parts having complex shape such as aerospace parts, and...

## Procedure:

Manipulate the end effector as per the given configuration. Movement Should Initiate in P1 and progress till the end point. Travel path should be in sequence as stated below.

![image](https://github.com/VIJAYKUMAR22007124/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119657657/e39d7ff5-1b81-4172-a607-d528200c73cf)

![image](https://github.com/VIJAYKUMAR22007124/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119657657/4c9af064-5e47-4755-9a2b-1d9fae866cb5)

![image](https://github.com/VIJAYKUMAR22007124/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119657657/5d00d76c-c91b-4735-9987-9dd92504cf03)

![image](https://github.com/VIJAYKUMAR22007124/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119657657/8839f787-0c59-46eb-a7b8-e5e148eb3ce4)

![image](https://github.com/VIJAYKUMAR22007124/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119657657/fbb5ead8-caae-4081-89d4-4fac0e7fc532)


Linear Interpolation


![image](https://github.com/VIJAYKUMAR22007124/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119657657/8c13bf21-8387-4829-ac98-c82bb3dd0aba)


Circular Interpolation


![image](https://github.com/VIJAYKUMAR22007124/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119657657/9ebfa767-947e-45f3-b1c8-7e2550fc91ac)


### Output
Linear Interpolation:

![image](https://github.com/VIJAYKUMAR22007124/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119657657/14d56628-4e07-4e4d-9d22-c37369bc8e5d)


Circular Interpolation

![image](https://github.com/VIJAYKUMAR22007124/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119657657/7fe9a45c-9d73-4faa-8894-ed664ff0b339)

### Results 
A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully.


 
