# A7 – FEA on Bracket

For this assignment the part previously designed in project A6 will be refined and optimized to cut unnecessary material using a "2x 3x" method. The material I chose for my bracket is Titanium (Ti-6Al-4V). The workflow for this project will consist of two parts. The first is an inner loop where the mesh will be changed up to three times(atleast two times), from coarser to finer until a 7% convergence appears validating the loop. The outer loop is where the actual geometry of the shape will be changed, removing material that is unnecessary and adding material where it could come in handy. The ultimate goal is to make the part be stronger, stiffer, and more lightweight than the prior iterations.

Below is an image of my initial part from A6:

![the intro thingie](7.png)

**<u>Part 1: First FEA Design run</u>**

One of the goals I have for this project is to make it bend less. I think adding material will help, so I will try that first. I chose 508lbf for the A5, so I will continue using that for this which translates to ~2260N. This force will be consistently applied face load no more force and no less. The vertical bracket holders will be the fixtures.



## __PART 1:__ <u>First FEA Design</u>

Things changed: made the baseplate and cylinder wall 4x thicker going from 0.0422 -> 0.1688in for both of them. Elements: tetrahedrons in the coarse to fine mesh

Coarse Run 
Elements	4,521 Mass:	0.13 lb

Max stress	1190 MPa at the top of the web where it meets the plate
Max deflection	2.387 mm (0.094 in), at the free end of the cylinder
Safety factor	0.695 (yield 827 MPa ÷ 1190 MPa), same location as max stress

Fine Run
Elements:	14,499 Mass:	0.13 lb

Max stress	1376 MPa at the top of the web where it meets the plate, the stress corner.
Max deflection	2.419 mm (0.095 in), at the free end of the cylinder
Safety factor	0.601 (yield 827 MPa ÷ 1376 MPa), same location as max stress 

Finest Run
Elements:	63,817 Mass:	0.13 lb

Max stress	1683 MPa at the top of the web where it meets the plate, the stress corner.
Max deflection	2.433 mm (0.096 in), at the free end of the cylinder
Safety factor	0.491 (yield 827 MPa ÷ 1683 MPa), same location as max stress 


Images:


## __PART 2:__ <u>Second FEA Design</u>

Things changed: made the corners where stress was located fillet'ed and horizontal bracket bar 1/2 as thick 0.356 -> 0.178in for both of them reducing weight. Elements: tetrahedrons in the coarse to fine mesh

Coarse Run 
Elements	2,483 Mass:	0.11 lb

Max stress	1398 MPa at the two edges of the fillet where it meets the plate
Max deflection	2.27 mm (0.089 in), at the free end of the cylinder
Safety factor	0.591 (yield 827 MPa ÷ 1398 MPa), same location as max stress

Fine Run
Elements:	11,347 Mass:	0.11 lb

Max stress	1466 MPa at the two edges of the fillet where it meets the plate
Max deflection	2.300 mm (0.090 in), at the free end of the cylinder
Safety factor	0.564 (yield 827 MPa ÷ 1466 MPa), same location as max stress

Finest Run
Elements:	62,719 Mass:	0.11 lb

Max stress	1464 MPa at the two edges of the fillet where it meets the plate
Max deflection	2.310 mm (0.091 in), at the free end of the cylinder
Safety factor	0.565 (yield 827 MPa ÷ 1464 MPa), same location as max stress

FINAL DATA on convergence. Was it below 7%?



## __PART 3:__ <u>Third FEA Design</u>


Things changed: I cut some rectangular spaces out from the areas of the bracket that were not under much stress. I also carved out a cylindrical hole in the cylinder and widened the cylinder wall to 0.2532 and halved the horizontal bracket bar again to ~0.09

# Coarse Run 
# Elements	2,406 Mass:	0.10 lb

Max stress	831 MPa 
Max deflection	1.458 mm (0.057 in), 
Safety factor	0.995 (yield 827 MPa ÷ 831 MPa), 

# Fine Run
# Elements:	8,514 Mass:	0.10 lb

Max stress	904 MPa 
Max deflection	1.495 mm (0.059 in), 
Safety factor	0.914 (yield 827 MPa ÷ 904 MPa), 

# Finest Run
# Elements:	52,224 Mass:	0.10 lb

Max stress	1082 MPa 
Max deflection	1.506 mm (0.059 in), 
Safety factor	0.764 (yield 827 MPa ÷ 1082 MPa), 

FINAL DATA on convergence. Was it below 7%?
Show calc and say No

**<u>Thought Process</u>**
Give my thoughts on the previous section here

HERE ARE THE PARAMETERS:
Image of parameters here if needed)





## __PART 3:__ <u>Reflections</u>
 Reflection Statement


## Lessons Learned

Give lessons learned


## FILES

Parts: [the part ](Part6.SLDDRW)
Drawing: [the drawing](Part6.SLDPRT)

