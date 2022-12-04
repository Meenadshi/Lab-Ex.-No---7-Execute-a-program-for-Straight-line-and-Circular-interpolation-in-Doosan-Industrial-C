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
## Program:

![k7 1](https://user-images.githubusercontent.com/88670187/205499826-5f4dbcdc-8e0d-499d-81d7-fa3e88b59254.png)
![k7 2](https://user-images.githubusercontent.com/88670187/205499829-bc94c6bd-ed41-469d-9ac7-4895dfd777c3.png)

![k7 3](https://user-images.githubusercontent.com/88670187/205499836-92b74117-2280-4d54-8188-663bc27a6a58.png)
![k7 4](https://user-images.githubusercontent.com/88670187/205499846-2c7234fe-695f-4ba5-9bb4-d64e895adb2a.png)

![k7 5](https://user-images.githubusercontent.com/88670187/205499853-06914b6f-20af-4bb5-8525-7b6e451e705d.png)


Linear Interpolation

![k7 6](https://user-images.githubusercontent.com/88670187/205499858-1fbcc1b2-487b-44bf-a46b-8afd2d89063e.png)


Circular Interpolation
![k7 7](https://user-images.githubusercontent.com/88670187/205499872-4f1d391b-f76d-44cb-8c62-1a79873b0c82.png)

### output
Linear Interpolation

![k7 8](https://user-images.githubusercontent.com/88670187/205499884-93c52b3b-65a4-4a1d-a384-d6cb83435193.png)
Circulat Interpolation
![k7 9](https://user-images.githubusercontent.com/88670187/205499899-2ba0670b-3e90-4b2f-863e-29ec735a6eda.png)



### Results 

A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully.

 
