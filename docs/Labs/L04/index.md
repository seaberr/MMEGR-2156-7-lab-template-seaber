![MEGR 2156-7 Title](MEES_Logo_Standard.png)
# Lab4 – Benchmark a Parameter
Instructions
Design an artifact in which benchmarks a parameter for the Prusa 3D printer.
Documentation and Grading:
Example HERE
### Parameter (5%)
For my Benchmark I used two test. One test was the overhang test and the other one was the tolerance test. I chose these Because I have been thinking of Ideas for things to make later on in the semester and the Tolerence Is very important to me if I want things to fit together correctly. I also Chose the overhang test because I hate when my 3d prints overhang does not look good so I wanted to find the real limit for my projects to come.

### Document Design (35%)
## I heavily documented my process using Creo to design a system where I Extruded
Detail the steps and reasons/decisions from start to finish. There were a few main step I took whie designing. FIrst I opened a new part and extruded rectangular block. Then I chose a side and I started drawing fro a extrude cut for an overhang. I extruded 5 of these overhangs at different degrees. Next, I selected the top Plane and Drew a circle with a measured diameter and extruded this to a reasonable height. I repeated this process five more times and made the cylinders smaller each time so that there would be a perfect range for my tolerence test.
![IMG 5919](IMG_5919.JPEG)

![IMG 5920](IMG_5920.JPEG)

![IMG 5922](IMG_5922.JPEG)

![IMG 5926](IMG_5926.JPEG)

![IMG 5927](IMG_5927.JPEG)

![IMG 5928](IMG_5928.JPEG)

![IMG 5930](IMG_5930.JPEG)

![IMG 5932](IMG_5932.JPEG)

![IMG 5933](IMG_5933.JPEG)

![IMG 5979](IMG_5979.JPEG)

![IMG 5980](IMG_5980.JPEG)

![IMG 5982](IMG_5982.JPEG)

![IMG 5984](IMG_5984.JPEG)

![IMG 5985](IMG_5985.JPEG)

![IMG 6017](IMG_6017.JPEG)

Detail what parameters you are trying to characterize.

Document the design process which includes many pictures with an overview of images.
### Preprocessor (30%)

Detail the reasons why you choose the build parameters in the pre-processor. Note the slice information on Prusaslicer. Some, not all questions, to answer are outlined below to guide your documentation.
#### Why choose the infill? 
I chose 15% infil of PETG because It was quick and cheap.
#### Why choose the build orientation?
I chose the build orientation when I designed the model in creo becasue it was specifically made so that the overhangs would go above 45 degrees to test the limits of the 3d printer. If I did not do that the 3d printing test would have been a waste.
#### Did you use supports if so, how did you do add supports in the software. 
I did not use and supports
#### Did you need to scale, if so why and how?
Yes I scaled it by 1/2 so that It would print quickly. This also allowed me to easily calculate the new dimentions of my tollerence gauge studs because I would just multiply by 0.5.
#### Detail any mistakes throughout the process.
I made the mistake of not Documenting every step, so I took a step back and redid my work in Creo to get you all the photos you could ever want.
### Print Artifact (10%)
![IMG 5987](IMG_5987.JPEG)

![IMG 5992](IMG_5992.JPEG)

![IMG 6002](IMG_6002.JPEG)

![IMG 6003](IMG_6003.JPEG)
Post a picture of the first layer calibration.
Print artifact and describe what the artifact tested.
Embed Video of the artifact build.
Was the outcome different than what you originally thought?
## Video
-----------------------------------------------------------
https://youtu.be/Wwpaoy1UOgA
[![Watch the demonstration video](https://img.youtube.com/vi/Wwpaoy1UOgA/maxresdefault.jpg)](https://youtu.be/Wwpaoy1UOgA)
### Lessons Learn (15%)
So the outcomes generally were pretty accurate to what the manufacturer stated the Prusa Core One was capable of. I am surprised that the Slicers quality wasn't also a factor that made the printer fail a little more than it did. I did notice that the printer did fail once which I probably would blame on the slicer rebuilding my Creo model in a low-quality manner this was for the first tolerance test at 12.5mm. 
## Tolerance test results
**Tolerance specification:** ±0.3% of the intended dimension, with a minimum tolerance of ±0.3 mm. 

| Intended Value (mm) | Measured Value (mm) | Absolute Error (mm) | Percent Error | Allowed Tolerance (mm) | Pass/Fail |
|---:|---:|---:|---:|---:|:---:|
| 12.50 | 11.938 | 0.562 | 4.50% | ±0.300 | **Fail** |
| 10.00 | 9.800 | 0.200 | 2.00% | ±0.300 | **Pass** |
| 6.00 | 6.020 | 0.020 | 0.33% | ±0.300 | **Pass** |
| 5.00 | 4.720 | 0.280 | 5.60% | ±0.300 | **Pass** |
| 2.00 | 2.133 | 0.133 | 6.65% | ±0.300 | **Pass** |
| 1.25 | 1.190 | 0.060 | 4.80% | ±0.300 | **Pass** |
## ![IMG 6018](IMG_6018.JPEG)
## Agle Test results
Rated up to 45 degrees
| Angle (Degrees) | Pass/Fail |
|---:|:---:|
| 44° | **Pass** |
| 45° | **Pass** |
| 46° | **Fail** |
| 47° | **Fail** |
| 48° | **Fail** |
## ![IMG 6025](IMG_6025.JPEG)

### (5%) Resources
I used Proto Labs Manufacturing Accelerated, Design Rules for 3d Printing and The Prusa Core One Manufacturer DATA sheet

