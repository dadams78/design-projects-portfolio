# A2 – Truss Stress Analysis

## Goal:
There is a required truss design needed which has four points of contact. It must be created to support a predetermined amount of weight without breaking. The four points of contact are as follows in this image:

![MEGR 2156-7 original image](Truss.png)

The force P is between 20-30kN, the length of a. is 0.4m, and the height of b. is 0.3m. The beams will be made of A500 structural steel and the pins will be made of hardened tool steel with a yield shear strength of 170 ksi and a density of 0.278 lb/in^3. Point A is a pin and point B is a roller.

In order to begin the project, I drew out a rough sketch of the diagram given on a scrap piece of paper. There were many options for design, but only some were realistic for the scenario at hand. One of the potential designs was a hexagonal shape, mimicking nature had its positives and negatives during actual testing in this scenario. I went through a few designs and decided to go with one which has a singular beam running across from point A to point C. I chose this because it was unique, and could pose a challenge to me during the final design.
![Drawing Board](TrussIdea.jpg)

After the decision was made, I got to work on the free body diagram. The unique roller design for point B which slides horizontally rather than vertically in the position that it is in messed with some of my calculations initially. Using the moment force calculation from point A, I found By = -8.33kN. That value was used to derive that Ay = 8.33kN. Once the external forces were done, using Pythagorean theorem gave me the length of beam AC. 
![Calculations FBD](TrussFBD1.jpg)

This section calculated forces from each pin using method of joints, I included symbolic and numeric equations in order to stay as neat and clean as possible without mistakes. Of the entire structure only three of the pins needed to be calculated, of which I chose B, C, and D, starting off initially with B and D considering they had the least amount of members. From there using the values gained from Pins B and D, the final internal force AC was calculated. 
![Calculations FBD](TrussPins.jpg)

Going back we get the calculation for the total length of all of the beams of the truss. Finding the lengths will be useful for me later because it will go into calculating the estimated weight of the entire truss at minimum. 
![Calculations FBD](TrussLength.jpg)

The values that the pins revealed during the method of sections allows for the next formulas to calculate stress properly. I organize the pin forces and the highest one is selected which was AC at ~47kN. In combination with the safety factor, yield strength of A500 steel, the A(min) is accessible to calculate weight. The mass of structural steel, gravity, total length from earlier, and A(min) are all multiplied to form the final weight of the truss structure. 
![Calculations FBD](Trussweights.jpg)

## Analyze
Utilizing a Free Body Diagram, the forces put on each individual point(A,B,C,D) become available to use when calculating the final design of the truss.

## Decide
To finalize the geometry of the truss, a double triangle was an effective yet simple design choice. The double triangle require less beams while holding the same weight, which makes it a smart choice for a truss.

