# A11 – Motor Selection

This is the second portion of our group development of a tensile testing lead screw system. During this section, the development of the motorized drive and structural integration for the 2 kN tensile tester is the primary focus. To achieve that a motor will be selected that aligns with our goals, and an analysis of the frame and clamp design/stability will be conducted to ensure it's safety factors are within specification. It will ensure that the crosshead moves accordingly under controlled torque and speed all while maintaining a precise load alignment. 

![image](fig1.png)

## **<u>Part 1: Motor Selection and Attachments (Jacob)</u>**

For the first part of this portion, utilizing the speed and torque requirements from the previous assignment we chose a motor to use, which ended up being a stepper type motor.  For the thickness on the first section of this part, the calculated number was rounded up to 1/4 inch. Math was then done to validate the safety factors of the couplers along with the frame mounting holes for the motor mount.
![image](01.png)
![image](02.png)
![image](03.png)
![image](04.png)
![image](05.png)
![image](06.png)
![image](07.png)

After this choice we created a motor mounting bracket for the motor to attach to, which is pictured below. It maintains its alignment with the rest of the system and stays within its clearances and tolerances regarding deflection.

Here is the start of the motor mount, ~2.36in size.

![image](m1.png)
![image](m2.png)

Cutting these sections out took a bit of work but it was eventually done. 

![image](m3.png)
![image](m4.png)
![image](m5.png)
![image](m6.png)

Getting these holes lined up was tedious, but the final part works. 

![image](m7.png)
![image](mount.png)

## **<u>Part 2: Analyze and design a Frame (Ryan)</u>**

Utilizing FEA for this second part of this, experimentation is done to see how the motors will affect the system and account for it. Using connectors, leadscrews and slight modifications(different frame type compared to the one selected before, specifically 80x40mm -> 40x40mm. The top of the frame will need to be able to support the loads of the lead screw and torque. Afterwards, verification of the vertical component and frame will be conducted with proper constraints and forces put in place. For the vertical frame we noticed a large safety factor. Once that was noted, we continued on with the simulations starting with the frame. The first one had a max element size 4mm and min 0.5mm, with the second one going down to 2.5mm and 0.35mm. For the vertical frame we started with 4mm  and 1.5mm, then dropped down to 2.5mm and 1mm for the second test.

![image](mm1.jpeg)
![image](mm2.jpeg)
![image](mm3.jpeg)
![image](mm11.png)
![image](mm22.png)
![image](mm33.png)
![image](mm44.png)
![image](mm55.png)
![image](mm66.png)


## **<u>Part 3: Design Floating Bearing Mount (Devin)</u>**

The last part of this system design requires modelling a floating mounting bearing that lets the end part of the lead screw to rotate. It is fitted to the bottom of the frame. We chose 0.5in for the center lead screw diameter with a +0.0007 tolerance as an RC3 for the 1/2 in leadscrew, along with four M8 sized bolt holes evenly spaced 1.575in apart. It is 0.75 in thick to give a decent amount of material for strength purposes if ever needed. The part itself is 2.5in x 2.5in to give clearance from the frame to its side. The original idea of 3 inches would be too large so we reduced it down.

Originally on this part it had to be completely remade to account for the smaller size of 3in down to 2.5in.

![image](p1.png)
![image](p2.png)

Figuring out how to get these screws lined up was a throwback to one of the previous projects, it was satisfying seeing them all line up properly and size themselves in sync.

![image](p3.png)
![image](p4.png)
![image](p5.png)

Here is the finished bearing.

![image](p6.png)

## **<u>Final System</u>**

This is the final assembly of the system!

![image](FinAsem.png)

## __Bill of Materials and Labor Costs (Devin)__


| Item Number | Quantity | Name | Cost/Item | Cost | Purchase Link |
|:-----------:|:--------:|:-----|----------:|-----:|:-------------:|
| 98980A370 | 1 | 304 Stainless Steel Precision Acme Lead Screw, 1/2"-10, 6 ft | $127.10 | $127.10 | [McMaster-Carr](https://www.mcmaster.com/98980A370/) |
| 97790A110 | 2 | Precision Acme Flange Nut, 1/2"-10, 932 Bronze | $178.60 | $357.2 | [McMaster-Carr](https://www.mcmaster.com/97790A110/) |
| 804T48 | 1 | Frame: Rectangle, 40 Series, Smooth, Double, 3 m, 40 mm x 40 mm | $115.67 | $115.67 | [Grainger](https://www.grainger.com/product/80-20-T-Slot-Framing-System-Square-804TA8) |
|  6627T591  | 1 | Stepper Motor with Square Body | $152.00 | $152.00 | [McMaster-Carr](https://www.mcmaster.com/6627T591/) |
|  6208K565  | 1 | Clamping Precision Flexible Shaft Coupling | $102.50 | $102.50 | [McMaster-Carr]([https://www.mcmaster.com/6208K565/]) |
| | | | **Total Cost** | **$854.47** | |


| Person | Hours Worked | Cost/Hour | Cost |
|:-----------:|:--------:|:-----:|:----------:|
| Devin | 7.5 | 35 | 105 |
| Jacob | 6.5 | 35 | 140 |
| Ryan | 7.5 | 35 | 105 |
| | | **Total Cost** | **$752.50** |


| Final Cost: |
|:----:|
| $1,606.97 |

## __Lessons Learned__ Ryan/Devin/Jacob

There was a lot of things we learned on this portion of the project. it took ~7 hours individually for each of us and 21.5 hours combined for us to complete this. A big thing was learning how to properly adjust the lengths of the downloaded solidworks parts from Grainger and McMaster. They had signatures on them and in order to not receive an error the files had to be converted to .STEP files. It took a second but we also had to relearn how to properly align the holes in a square shape to allow for an even mounting surface. 


**<u>Files & Parametrics</u>**

[Motor Mount](A11MotorMount2.SLDPRT)

[Floating Bearing Mount](FloatingBearing2.SLDPRT)

[Frame Motor Assembly](FMA.SLDASM)

[motor Frame 30x40](30x40f.SLDPRT)

[Motor Frame](Motor-Frame.SLDPRT)

[Motor Frame Assembly](MotorFrameAssemblyPart2.SLDASM)

[Crosshead](crosshead.SLDPRT)

[Lead Screw](LeadScrew.SLDPRT)

[Flange Nut](FlangeNut.SLDPRT)
