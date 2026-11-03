# A8 – Gears

For this assignment a gearbox is created with pre-existing gears and pins. Bearings and the gearbox case are to be discovered. The size and material of the bearings must be decided along with the gearbox case design that the gears will be held in. I ended up choosing porous bronze SAE 841. Forces from the gears will be used to dictate these variables. Using Solidworks the gearbox will be constructed with the assembly selection.

 
Below are images of the gears that will be used for the project in solidworks.

![the intro thingie](smallgear.png)
![the intro thingie](biggear.png)

**<u>Part 1: Shaft Stress Analysis</u>**

I begin calculating the stresses located in the pins from the 1.25in-lbf force. the 24:9 ratio was interesting to have because from statics and solids aside from levers we havent had other torque multipliers like this.

![image](pg1.jpg)
Part of this second page is related to journal bearings so it will be placed in shaft stress as well as JB design. I did not have much trouble calculating these values.
![image](pg2.jpg)


**<u>Part 2: Journal Bearing Design</u>**

![the intro thingie](pg2.jpg)
on the page below, I wasn't able to find a good source on porous bronze's properties until I actually picked my bearing. Luckily the values were close enough that the bearing material and sizes still worked as intended. It was close enough when re-calculating the final answers, with the lowest Factor of Safety being 3.8(typically 3). The input bearing is on the bottom right, and the output bearing is on the next page.

![image](pg3.jpg)

![image](pg4.jpg)

Input: McMaster-Carr 6391K326, Oil-Embedded 841 Bronze Sleeve Bearing, 1/8 in shaft diameter, 3/16 in housing ID, 5/32 in long
Output: McMaster-Carr 6391K126, Oil-Embedded 841 Bronze Sleeve Bearing, 1/4 in shaft diameter, 5/16 in housing ID, 1/4 in long

## __PART 3:__ <u>Gearbox Sketch</u>

Here is a close representation of what i plan on making my gearbox look like internally and externally with the input shaft exposed below and the output shaft exposed above the gearbox. After this I placed three #4-40 hex bolt holes in a triangle pattern to hold the box together. I chose this over a snap fit because for a gearbox I would prefer a stronger clamping force that the bolts can give. 
![image](pg5.jpg)



## __PART 4:__ <u>CAD Modelling</u>

During this stage I jumped right in working on the gearbox. I started off making the shafts 0.125x1.00 and 0.25x1.00, then downloaded the gears and bearings from the website for use with the final assembly and reference images. This helped me gauge what types of features I will need to design for in the gearbox.
![image](bearing.png)

Based on the previous image of the gears, I figured a large but not excessive gearbox size would be 2.2"x1.4". I kept this consistent across the entire project to keep it simple. 0.6 inches extruded(previously 0.5 from miscalculations).
![image](basesize.png)

I carved out a segment of the half-gearbox to make room for the gears. Bearings will need space cut out as well, though since they are interference fits the holes were designed a bit smaller. 
![image](basecut.png)
![image](impropergap.png)
![image](basepins.png)

Once I got the basics out of the way, I mirrored the bottom half-gearbox and copied it as to quickly make a top half-gearbox to fit. At this point I began putting the assembly together for the first time. Unfortunately I ran into a gear interference issue which came down to a mis-reading of the gap. I used 0.65" instead of ~0.68" I quickly fixed it and returned to the building.
![image](gearfit.png)


Getting these bearings to fit into their interference holes was troublesome. I watched a youtube video and figured out pressing ALT would focus where the individual parts tracked to. 
![image](bearingfit.png)

Finally, I felt like I had finished the gearbox, but I realized there are no holes to access either the input or output shafts. It was just kind of a screwed together little box with gifts inside at this point.
![image](gearboxdone.png)
![image](gearboxclosed.png)

Once done placing the holes I re-observed the gearbox and it turned out just how i was hoping. It was a little bit entertaining to open and close the box with its mated axes. 
![image](finalbox.png)
![image](finalboxopen.png)


**<u>Thought Process</u>** 


HERE ARE THE PARAMETERS:
![Parameters](parametrics.png)


## __PART 5:__ Problems Faced and Lessons Learned
I liked this assignment more than I thought I was going to. I was initially thinking we were going to be actually designing the gears and seeing it was just the gearbox was a bit of a relief. It was similar to designing the A6 bracket. The biggest hurdle was small items like one dimension being off by 0.03" as well as navigating assembly for the first time in solidworks. I am sure that without these small bumps I could have cut my time down by an hour or two. This can be seen with my gear interference earlier and how I later realized I hadn't made holes for the shafts to poke out of for controlling and powering. My biggest lesson was learning that you can mirror stuff. I was going to get started on the bottom half and then try to manually copy the top half's layout. Solidworks is built for just that. My smallest lesson was to always remember to smart dimension everything no matter how arbitrary it may seem. This assignment took 8 hours for me and wasn't too bad.



## FILES

Parts and Assemblies: 


[Parametrics/Parameters](Parametrics.SLDPRT)

[Gearbox ZIP File](Devin-Gearbox.zip)
