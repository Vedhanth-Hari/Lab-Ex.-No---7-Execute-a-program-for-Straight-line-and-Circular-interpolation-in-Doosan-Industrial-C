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

![Screenshot 2025-05-15 155336](https://github.com/user-attachments/assets/2ee1a361-17fb-4be6-9f99-c22fd8d1ca12)

![Screenshot 2025-05-15 155349](https://github.com/user-attachments/assets/50226766-5927-4111-b423-5b10f809538b)

![Screenshot 2025-05-15 155400](https://github.com/user-attachments/assets/0ccad08a-f4fd-4905-b589-b47951bac2f1)

![Screenshot 2025-05-15 155411](https://github.com/user-attachments/assets/7b78c8eb-f261-4b2d-b3b5-4df9e0c5e208)

![Screenshot 2025-05-15 155420](https://github.com/user-attachments/assets/cdc05c6b-6046-40ac-9469-5d6814835bb1)


## Linear Interpolation:

![Screenshot 2025-05-15 155621](https://github.com/user-attachments/assets/0a7c9319-3c11-4c90-8c73-ef695786a679)


### Circular Interpolation:

![Screenshot 2025-05-15 155645](https://github.com/user-attachments/assets/f55113a2-4820-4ea0-ba70-4f2763083e70)


### Result:

A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully.



 
