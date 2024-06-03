# cheap_conveyor_belt

This repository contains files to build a cheap conveyor belt of any length and width. The picture is a belt of size 30cm * 2m and has a price of ~50$. This could work well together with a robot arm such as AlexanderKoch's [Low cost robot](https://github.com/AlexanderKoch-Koch/low_cost_robot).

[Picture]

## Contents:
In this repo:
- First a complete tutorial for building a 30cm * 2m as seen in the picture.
- Then a description of how you can modify the 3d-parts to fit other sizes. This is also useful if you are not able to get the exact copy of the materials (which is most likely the case).

In this repo:
- README.md
- 3d-parts: 3d-parts in .stl format for you to either edit or modify to your needs.
- budget.md: Table of how the money could be spent of this project.

## Making a 30cm * 2m conveyor belt
### What you need to buy:
- Some rollers:     More rollers = higher weight threshold for items and less bending in the belt, but is more expensive and requires more motor power to run. I usually go with 1 belt pr. 50 cm.
- The frame:        
- A motor:          There is a few options here. A N20 driver is a cheap options. The RPM determines the speed of the conveyor by approximately this equation. :
```math
speed_of_conveyor = 2 * rpm
```


- Timing belt:      
- T-screws + knots: 
- Machine Screws:   
- Kuglelejer:       
- A conveyor belt:  This is a bit difficult. You have some options, but not all of them are great. I decided to go with simple _____, which works rather fine. Using tape you can close the belt and even extend it sideways if necessary.

### What you need to print:
- 2 x number of rollers:    RollerEndings
- 1:                        RollerEndingWithMotor
- 1:                        MotorDriver

### Options
- You can either buy 90 degree cornors for the frame or print them yourself (2 x frame_cornors.stl & 2 x frame_cornors_mirrir.stl)
- You need a DriverExtension for your RollerEndingWithMotor. Depending on what speed you want, you can either print DriverExtensionSlowSpeed or DriverExtensionHighSpeed. You can of course also edit the files yourself to adjust the number of teeth on the DriverExtension.

### How to build
By now you should have everything as specified on this picture below:
[Picture]
Now it's time for the assembly:
1. Prep you rollers

2. Craft the frame

3. Add the rollers

4. And the timing belts and conveyor belt

5. Add the motor

6. Watch the magic happen

## Modifying the original 3d-parts