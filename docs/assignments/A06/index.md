# A6 – Bracket Drawing (part 1)

For this assignment we are parametrically designing the bracket that was dimensioned in the previous assignment to meet a maximum deflection of 0.005 inches per component. This was done by calculating the given stress and strength needed at various areas to give a thickness that is satisfactory to meet the requirement. Ultimately Stress was the limiting factor, so the dimensions given in the stress equations are what the current design will be using. Below are the given instructions on what the bracket was supposed to be designed around, which was a rigid T beam. For the design process, I chose Titanium (Ti-6Al-4V) to be the material of the bracket and will use the stress dimensions from the previous assignment for this one.

**<u>The T Bracket Base</u>**

![the intro thingie](intro.png)


## __PART 1:__ <u>Parametric Design</u>


**<u>Getting Started</u>**

Designing in SolidWorks is new to me, while this is a documentation of building the bracket to fit onto the T Bracket Base, it is also a documentation of the failures and mistakes I made while creating this part. I started off creating the cylinder wall since it is lowest to the ground.


To begin, I started building the cylinder wall and realized when extending the length to the parametric definitions I had saved, it would not equally lengthen both sides of the rectangle sketch. Later I figured out I had to use centerlines with midpoint lines to accurately center the base of the bracket.
![the beginning stages](1.png)

Here is the centered base. Later I had to extend it to include my vertical walls for the bracket, and I did not realize until much later on in this process.
![the intro thingie](4.png)

After finishing the base and cylinder wall, I started on the cylinder. After perfectly attributing its diameter parametrically, when I went to extrude I realized it was attached to the plane behind the part.
![the intro thingie](2.png)

A bit of research led me to "Edit Sketch Plane" which allowed me to easily pin the sketch to the wall. 
![the intro thingie](3.png)

After getting the cylinder pinned down, and fixing the base dimensions, I worked on the vertical walls. These gave me trouble due to the 
![the intro thingie](5.png)
![the intro thingie](6.png)
![the intro thingie](7.png)

![part1-1](Part1-1.jpg)
**<u>Thought Process</u>**
All of the thicknesses of each plate are very small decimal numbers. During this point of the project I was not concerned about the bracket being too big like with the ABS project, but too small. 
![part1-1](Part1-2.jpg)

## __PART 2:__ <u>Drawing</u>

For this part of the assignment, it was a bit easier to go through each of the features as I had gotten the hang of drawing the FBDs and formulas. After seeing the first radius for the cylinder, I was thinking the rest of these values would be very small, which I was mostly correct.
![part1-1](Part2-1.jpg)
On the final Feature, the thickness of the metal actually exceeds the prior highest set by the Stress Analysis. it was very close, near hundredth of an inch, but could be enough of a difference in some scenarios that could cause it to fail if it was too thin.
![part1-1](Part2-2.jpg)



## __PART 3:__ <u>Reflections</u>



## Lessons Learned
-------------------------------------FILLL IN HERE

An error I faced was mixing up the base and height values quite a bit when calculating final thicknesses. I didn't get far before realizing but it was very annoying having to re-do it. 

One assumption I made was

It took ~6 hours to complete this project

