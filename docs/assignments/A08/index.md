# A8 – Gears

For this assignment a gearbox is created with pre-existing gears and pins. Bearings and the gearbox case are to be discovered. The size and material of the bearings must be decided along with the gearbox case design that the gears will be held in. I ended up choosing porous bronze SAE 841. Forces from the gears will be used to dictate these variables. Using Solidworks the gearbox will be constructed with the assembly selection.

 
Below are images of the gears that will be used for the project in solidworks.

![the intro thingie](smallgear.png)
![the intro thingie](biggear.png)

**<u>Part 1: Shaft Stress Analysis</u>**

One of the goals I have for this project is to make it bend less. I think adding material will help, so I will try that first. I chose 508lbf for the A5, so I will continue using that for this which translates to ~2260N. This force will be consistently applied at face load to the outer cylinder face normal to the baseplate pointing down. The vertical bracket holders/hooks will be the fixtures.

![the intro thingie](pg1.png)

![the intro thingie](pg2.png)


**<u>Part 2: Journal Bearing Design</u>**

![the intro thingie](pg2.png)
on the page below, I wasn't able to find a good source on porous bronze's properties until I actually picked my bearing. Luckily the values were close enough that the bearing material and sizes still worked as intended. It was close enough when re-calculating the final answers, with the lowest Factor of Safety being 3.8(typically 3). The input bearing is on the bottom right, and the output bearing is on the next page.

![the intro thingie](pg3.png)

![the intro thingie](pg4.png)

## __PART 3:__ <u>Gearbox Sketch</u>

Here is a close representation of what i plan on making my gearbox look like internally and externally with the input shaft exposed below and the output shaft exposed above the gearbox.
![the intro thingie](pg5.png)



## __PART 4:__ <u>CAD Modelling</u>

During this stage I jumped right in working on the gearbox. I started off making the pins 0.125x1.00 and 0.25x1.00


**<u>Thought Process</u>** The max stress appeared on the two vertical bracket bars on the edges. A fillet could fix it but this is my last design. Max deflection	focused primarily at the free end of the cylinder again. Stress is lower and safety factor is higher, but all small problems become bigger once the large problem is out of the way(cylinder wall). The weight loss is small but exists.

FINAL DATA on convergence. Was it below 7%? Not close. I changed a lot of areas on the part, including gutting the plate and cylinder. Fillets may have helped a little with this, but I hadn't thought about it for this last one since i thought it was going to be very stable based on the first run. If I could go back I would make the vertical bars thicker as well, or make the fillets huge. 

# IMAGE OF GEN 3 PART:

 ![the first](finalpart.png)

HERE ARE THE PARAMETERS AND TABLE IF NEEDED:
![Parameters](things.png)
![Table](table.png)



## __PART 4:__ <u>Reflections</u>

This assignment was fun because it allowed me to feel the satisfaction of getting the rhythm down for simulation. I understand how to apply forces and fixtures and set parameters without needing to search a tutorial online. In terms of my designs, I realized 1 and 3 didn’t converge on stress because of sharp corners. Design 2 converged because its corners were filleted and reducing that big stress point contributed to its success. Deflection converged in every design which I thought was interesting. The improvement from Design 1 to Design 3 was fun to calculate. Stress down 36%, deflection down 38% and mass down 20%. It amazes me that computers can solve this stuff in seconds. Though the finer meshes did take a bit longer. My laptop fans didn't even turn on once. Overall it took me ~5 hours to complete this assignment. 


## Problems Faced and Lessons Learned

It was a learning process the entire way. I was scared my bracket wasn't built right as when I first tried to simulate the original A6 bracket (0.04 in plate), it failed to solve at full load with “equilibrium not achieved.” I found it was later due to the part not being able to support such a high force, as turning it down to 226N worked fine. Thats the biggest reason my first move in this project was thickening the baseplate and cylinder wall. I had trouble applying the force for the simulation properly, but I was able to watch a tutorial to properly set it up. In between design 2 and 3, I did a small test run to see whether my design would hold up despite being quite a bit lighter, and it did horribly with ~3.06mm deflection. The safety factor is the one thing I want to change. It is still below 1 and I feel like I could refine this bracket if I invested more time into it. Thickening the vertical walls and using fillet on the upright corners would probably ease the focused stress on that edge. I learned how stress likes to focus on edges and a lot of engineering choices i see in the real world make sense to me now.

![Table](stressorpoint2.png)


## FILES

Parts: 
[Design 1](Part6design1.SLDPRT)

[Design 2](Part6design2.SLDPRT)

[Design 3](Part6design3FINAL.SLDPRT)
