# MuSHR Racecar Build Instructions
____
 *[Link](https://github.com/planc509/mushr_docs/blob/master/v3_1_bill_of_materials.pdf) to Bill of Materials*


---

*This Wiki provides instructions for building the MuSHR Racecar. For each section, we recommend reading through each of the section's steps before attempting it.*

**Steps**

[TOC]

___
## VESC Preparation 
---
*In this section, we will prepare the VESC's connectors for installation. Note that one end of the VESC connects to the BLDC motor, while the other end connects to the 5000 mAH NiMH battery. We assume that the VESC is already outfitted with 4mm bullet connectors for interfacing with the BLDC motor. However, a connector for interfacing with the battery must be added to the VESC. The addition of this connector will be detailed in the following steps.*

**Required Materials and Tools**

* VESC
* 1/4" Heat Shrink
* 2x Solderless Wire Connectors (Heat Shrink Butt Connector)
* Battery Connector 4mm 
* USB Mini Cable 1 ft
* Wire Stripper/Cutter
* Scissors
* Crimping Tool 
* Heat Gun

**Steps**

1. If the VESC's battery wires are already tinned with solder, use the wire cutter to remove the tinned segments such that the individual wire strands are not soldered together.

2. Use the wire stripper to remove 1 cm of insulation from each of the VESC's battery wires and each of the battery connector's wires.

3. Use the scissors to cut two pieces of black 1/4" heat shrink. The length of each piece should be approximately 1 cm longer than the length of the solderless wire connector. 

4. Slip a piece of cut heatshrink (from the previous step) onto each of the VESC's battery wires. Slide them down along the wires, towards the VESC's circuitry. They will be heat shrunk in a later step. (Fig. 1.1)

    ![Screen Shot 2019-07-22 at 11.32.01 AM.png](https://bitbucket.org/repo/ooxLxBK/images/1325747650-Screen%20Shot%202019-07-22%20at%2011.32.01%20AM.png)

    *Fig. 1.1*

5. For each stripped wire, twist the wire strands into a tight bunch such that they can fit inside of the solderless wire connectors. (Fig. 1.2)

    ![IMG_8545.jpg](https://bitbucket.org/repo/ooxLxBK/images/113685279-IMG_8545.jpg)

    *Fig 1.2*

6. Insert the stripped end of one of the battery connector's wires into the solderless wire connector. The exposed copper should be inside of the metallic cylinder of the solderless wire connector. Ensure that no exposed copper is sticking out of the solderless wire connector. (Fig. 1.3)

    ![Screen Shot 2019-07-22 at 11.15.14 AM.png](https://bitbucket.org/repo/ooxLxBK/images/3725489763-Screen%20Shot%202019-07-22%20at%2011.15.14%20AM.png)

    *Fig 1.3*

7. Use the crimping tool to crimp the solderless wire connector onto the battery connector's exposed copper. Ensure that the crimp is tight and complete by holding onto the solderless wire connector and tugging on the crimped wire. If tugging causes the connection to slip or disconnect, go back to step 5. (Fig 1.4)

    ![Screen Shot 2019-07-22 at 11.17.33 AM.png](https://bitbucket.org/repo/ooxLxBK/images/2214143648-Screen%20Shot%202019-07-22%20at%2011.17.33%20AM.png)

    *Fig 1.4*

8. Insert the stripped end of the VESC's corresponding battery wire (i.e. the one that has the same color as the battery connector from the previous step) into the uncrimped end of the solderless wire connector. Repeat step 4 as necessary. Again, ensure that the exposed copper is inside of the solderless battery connector's metallic cylinder, but that no exposed copper is sticking out of the solderless wire connector. 

9. Repeat the process described in step 7 for the VESC's inserted battery wire (instead of the battery connector wire). 

10. Perform a final check of the strength of the connection by stiffly tugging on both of the crimped wires. 
 
11. Use the heat gun to uniformly heat the solderless wire connector until it has completely shrunk. Be careful not to apply excessive heat.
 
12. Once the solderless wire connector has  cooled down, adjust the 1/4" heat shrink so that it completely covers the solderless wire connector.(Fig. 1.5)

    ![Screen Shot 2019-07-22 at 11.20.32 AM.png](https://bitbucket.org/repo/ooxLxBK/images/3355594909-Screen%20Shot%202019-07-22%20at%2011.20.32%20AM.png)

    *Fig. 1.5*

13. Use the heat gun to uniformly heat the heat shrink until it has completely shrunk. (Fig. 1.6)

    ![Screen Shot 2019-07-22 at 11.22.13 AM.png](https://bitbucket.org/repo/ooxLxBK/images/2695730662-Screen%20Shot%202019-07-22%20at%2011.22.13%20AM.png)

    *Fig. 1.6*

14. This completes the connection of one of the battery wires. Repeat steps 6 through 13 for the other wire. (Fig. 1.7)

    ![Screen Shot 2019-07-22 at 11.27.38 AM.png](https://bitbucket.org/repo/ooxLxBK/images/328913345-Screen%20Shot%202019-07-22%20at%2011.27.38%20AM.png)

    *Fig. 1.7*

15. Plug the USB mini cable into the VESC.

---
## Servo Motor Removal
---
*In this section, we will describe the steps necessary to remove the stock servo motor from the chassis. In a later section, we will install a more powerful servo motor.*

**Required Materials and Tools**

* Hex Keys 
* Racecar Chasis
* Philips Screwdriver 
* Pliers


**Steps**

1. Flip the car over and remove the five screws that are holding the motor in place. (Fig. 2.1)

    ![Screen Shot 2019-07-22 at 10.40.43 AM.png](https://bitbucket.org/repo/ooxLxBK/images/1506880554-Screen%20Shot%202019-07-22%20at%2010.40.43%20AM.png)
    *Fig 2.1*

2. Flip the chassis back over and take out the servo motor mount. It is still connected to the brushed motor, which will be removed in the next section. 

3. A linkage connects the servo arm to the chassis. Use pliers to disconnect this linkage from the chassis. (Fig. 2.2)

    ![Screen Shot 2019-07-22 at 10.38.19 AM.png](https://bitbucket.org/repo/ooxLxBK/images/3839140568-Screen%20Shot%202019-07-22%20at%2010.38.19%20AM.png)

    *Fig 2.2*

4. Unscrew the servo motor arm from the servo motor. Remove the linkage from the servo arm. (Fig. 2.3)

    ![Screen Shot 2019-07-22 at 10.39.11 AM.png](https://bitbucket.org/repo/ooxLxBK/images/4151573928-Screen%20Shot%202019-07-22%20at%2010.39.11%20AM.png)

    *Fig 2.3*


5. Keep the metal linkage, as it will be used later when we install a more powerful servo motor.  

___
## Brushed Motor Removal
---

*In this section, we will remove the brushed motor that comes with the chassis. Removing the brushed motor and replacing it with a BLDC motor (as detailed in the following section) requires a significant amount of time and effort. An alternative is to instead buy the Pro Version of the Redcat Blackout racecar chassis. This will lead to a slightly more expensive build, but that chassis already has a BLDC motor installed.*

**Required Materials and Tools**

* Racecar Chasis
* Hex Keys
* Philips Screwdriver 
* Pliers 

**Steps**

1. Use the screw driver to remove the front and back cover mounts. (Fig. 3.1)

    ![Screen Shot 2019-07-23 at 4.17.43 PM.png](https://bitbucket.org/repo/ooxLxBK/images/1722792277-Screen%20Shot%202019-07-23%20at%204.17.43%20PM.png)

    *Fig. 3.1*

2. A metal bar holds the upper suspension between the chassis and right rear wheel in place. This metal bar is in turn held in place by a screw. This screw is highlighted in Fig 3.2 below, remove it.

    ![Screen Shot 2019-07-23 at 4.18.50 PM.png](https://bitbucket.org/repo/ooxLxBK/images/859059689-Screen%20Shot%202019-07-23%20at%204.18.50%20PM.png)

    *Fig. 3.2*

3. Remove the metal bar that is holding the upper suspension in place by wiggling the upper suspension back and forth. Apply downwards pressure onto the upper suspension while wiggling it back and forth. This method is a bit tricky, and requires a little bit of patience. Alternatively, the metal bar can be pushed out by inserting a small object into the front of the bar's cavity. Once a few millimeters of the metal bar has been wiggled/pushed out, use pliers to fully pull it out while continuing to wiggle the upper suspension as necessary. (Fig. 3.3)

    ![Screen Shot 2019-07-23 at 4.20.02 PM.png](https://bitbucket.org/repo/ooxLxBK/images/3292279853-Screen%20Shot%202019-07-23%20at%204.20.02%20PM.png)

    *Fig 3.3*

4. Store the metal bar and screw, they will be re-installed later.

5. Two linkages connect the motor gear cover to the rear wheel mounts. Pry both of these linkages off of the motor gear cover with a screw driver or pliers. (Fig. 3.4)

    ![Screen Shot 2019-07-23 at 4.22.00 PM.png](https://bitbucket.org/repo/ooxLxBK/images/2875907100-Screen%20Shot%202019-07-23%20at%204.22.00%20PM.png)

    *Fig. 3.4*

6. Rotate the rear right wheel away from the chassis to release the wheel shaft. Store this shaft for later re-installation.

7. Flip the car over and remove the nine screws that attach the rear suspension, motor mount, and the motor gear cover to the chassis of the car. (Fig 3.5)

    ![Screen Shot 2019-07-23 at 4.22.31 PM.png](https://bitbucket.org/repo/ooxLxBK/images/2322109430-Screen%20Shot%202019-07-23%20at%204.22.31%20PM.png)
  
    *Fig 3.5*

8. Flip the car back over and remove the four screws on top of the motor gear cover. (Fig 3.6) 

    ![Screen Shot 2019-07-23 at 4.23.36 PM.png](https://bitbucket.org/repo/ooxLxBK/images/1389571407-Screen%20Shot%202019-07-23%20at%204.23.36%20PM.png)

    *Fig. 3.6*

9. Remove the motor gear cover.

10. Remove the two screws that secure the motor to its mount. (Fig. 3.7, Fig. 3.8) Be sure to orient the screwdriver as perpendicularly as possible with the face of the screw to avoid stripping the screw. 

    ![Screen Shot 2019-07-23 at 4.24.39 PM.png](https://bitbucket.org/repo/ooxLxBK/images/3696769893-Screen%20Shot%202019-07-23%20at%204.24.39%20PM.png)

    *Fig. 3.7*

    ![Screen Shot 2019-07-23 at 4.25.00 PM.png](https://bitbucket.org/repo/ooxLxBK/images/3637718447-Screen%20Shot%202019-07-23%20at%204.25.00%20PM.png)

    *Fig. 3.8*

11. To finally release the motor, we must remove the motor gear pinion. First, rotate the motor gear pinion so that the screw is facing towards the right side of the chassis such that it is aligned with the indent in the plastic motor mount. This indent allows for extra space when inserting a hex key. Insert the hex key and remove the motor gear pinion screw. (Fig. 3.9) 

    **Take extra caution in this step because the motor gear pinion screw is extremely tight and can easily be stripped, leaving the motor stuck. Make sure to check that the hex key tightly fits inside of the screw hole, and push the hex key into the screw hole with a large amount of pressure WHILE UNSCREWING to ensure that it does not slip out. If you feel the hex key starting to slip or strip, stop unscrewing and re-insert the hex key before trying again.**


    ![Screen Shot 2019-07-23 at 4.26.37 PM.png](https://bitbucket.org/repo/ooxLxBK/images/2088817300-Screen%20Shot%202019-07-23%20at%204.26.37%20PM.png) 

    *Fig. 3.9*

12. With the motor gear pinion screw removed, slip the motor gear pinion off of the motor shaft and remove the brushed motor from the motor mount. The motor gear pinion and its screw will be reused when installing the BLDC motor. 

---
## Brushless Motor Installation
---

*In this section, we will install the BLDC motor.*

**Required Materials and Tools:**

* BLDC Motor
* Racecar Chasis
* Hex Keys 
* Philips Screwdriver 
* Pliers 

**Steps**

1. Orient the motor so that the wires are above the motor casing.

2. Mount the motor to the chassis by inserting screws into the lower hole of the upper right pair and the upper hole of the lower left pair (Fig. 4.1). Use the same screws that previously held the brushed motor in place. 

    ![motorshaft.png](https://bitbucket.org/repo/ooxLxBK/images/1070933003-motorshaft.png)

3. Re-insert the drive shaft if it is no longer in position. (Fig. 4.2)

    ![drive_shaft.png](https://bitbucket.org/repo/ooxLxBK/images/3712263872-drive_shaft.png)
    *Fig. 4.2*

4. Flip the car onto its side and re-insert the three screws that fasten the motor mount to the chasis. This ensures that the drive shaft will stay in place.

5. Note that the motor shaft is not entirely round, there is a flat edge. Locate that flat edge, and use pliers to rotate the shaft so that the flat edge is facing towards the right side of the chassis. 

6. Re-install the motor gear pinion so that the screw hole of the motor gear pinion is aligned with the flat side of the motor shaft. Thus, once the screw is reinserted (don't do it yet), the end of the screw will be in contact with the flat edge of the motor shaft, preventing the motor gear pinion from slipping. Also, ensure that the motor gear pinion is pushed as far back onto the shaft as possible while at the same time being able to be screwed in from the right side. (Fig 4.3) 

    ![fig4.3.png](https://bitbucket.org/repo/ooxLxBK/images/84971499-fig4.3.png)

    *Fig. 4.3*

7. Insert the motor gear pinion screw. Tighten the screw as much as possible, but be careful not to strip it.

8. Lift the car and spin the drive shaft gear to test that the drive shaft and motor gears have properly mated. The motor gear should turn as you spin the drive shaft gear without much resistance. 

9. Re-insert the right rear wheel shaft and rotate the rear wheel towards the chassis to hold it in place.

10. Place the upper suspension back to its original position, and secure it in place by re-inserting the metal rod. Use pliers to re-insert the rod if necessary.

11. Re-install the screw that originally held the metal rod in place. (Fig. 4.4)

    ![fig4.4.png](https://bitbucket.org/repo/ooxLxBK/images/3639560755-fig4.4.png)
    
    *Fig. 4.4*

12. Re-install the plastic motor gear cover into its original position. 

13. Re-attach the two rear linkages to the motor gear cover by pushing their unconnected ends back down onto the metal balls. Use pliers if necessary.

14. Flip the car over and re-insert all of the screws that attach the rear suspension to the car chassis. (Fig. 4.5) 

    ![fig4.5.png](https://bitbucket.org/repo/ooxLxBK/images/3210418081-fig4.5.png)

    *Fig. 4.5*
    
15. Flip the car back over, place it on the floor, and lightly push it forward. The car should freely move forward at least a few feet before coasting to a stop. Then repeat, except push it backwards. If the car doesn't freely move forward/backward, the motor gear pinion is most likely not pushed in far enough and is rubbing against the motor gear cover. Go back to step 6 if this is the case. 

16. Insert the four top screws into the motor gear cover to secure it. (Fig. 4.6)

    ![fig4.6.png](https://bitbucket.org/repo/ooxLxBK/images/1573204346-fig4.6.png)
    
    *Fig. 4.6*

17. Again verify that the car moves freely when pushed (as described in step 15). If it does, the brushless motor has been successfully installed. 

---
## Servo Motor Installation 
---

*In this section, we will install a servo motor into the racecar chassis. Compared to the stock servo motor, the replacement servo motor is much more powerful. This allows the racecar to effectively steer, despite the additional weight that will be mounted to the chassis in later sections.*

**Required Materials and Tools**

* Racecar Chasis
* 3D Printed Parts
    * Servo Cage
* 6x M2.5 Hex Nuts
* 2x M2.5 Flat Head Screws
* 4x M2.5 Pan Head Screws
* 20 KG servo motor
* Threadlocker
* Hex Keys
* Philips Screwdriver 
* Pliers 

**Steps**

1. Insert six hex nuts into the inlets below each of the servo cage's screw holes. (Fig. 5.1)

    ![fig5.1.png](https://bitbucket.org/repo/ooxLxBK/images/2877450989-fig5.1.png)

    *Fig 5.1*

2. Take out the servo motor, but do not attach the metal arm yet. Orient the servo motor into the servo cage such that the motor gear is on the same side as the four screw holes, and the motor wire is oriented towards the knotch in the back of the servo cage.  The servo motor should prevent the six hex nuts from falling out of their holes. (Fig. 5.2) 

    ![fig5.2.png](https://bitbucket.org/repo/ooxLxBK/images/1624850657-fig5.2.png)

    *Fig. 5.2*

3. Insert four M2.5 pan head screws to mount the servo motor to the servo cage. 

4. Attach the metal servo arm onto the servo motor so that it points directly upwards. (Fig. 5.3)

    ![fig5.3.png](https://bitbucket.org/repo/ooxLxBK/images/2894778595-fig5.3.png)

    *Fig. 5.3*

5. Use the screw that came with the servo motor to secure the servo arm to the servo motor. 

6. Position the servo motor cage on the chassis. Orient it so that the servo arm is facing towards the right side of the race car and the wires run towards the back of the car. The two stubs on the servo motor cage should protrude through the corresponding holes of the chassis. (Fig. 5.4)

    [fig5.4.png](https://bitbucket.org/repo/ooxLxBK/images/3841750503-fig5.4.png)

    *Fig. 5.4!*

7. Flip the car over and attach the servo cage to the chassis with two M2.5 flat head screws. 

8. Note the metal ball screwed into the **old/stock** servo arm. Unscrew it with the pliers.  

9. Apply threadlocker to the threads of the metal ball. Then screw the ball into the lower hole of the **new** servo arm. Tighten it by screwing it with the pliers. 

10. Re-attach the servo linkage that was removed from the old servo motor. First re-attach it to the chassis by pushing it down onto the chassis' metal ball. 

11. Line up the linkage with the servo arm's metal ball by turning the wheels and/or the servo arm, and then attach it with pliers. (Fig. 5.5)

    ![fig5.5.png](https://bitbucket.org/repo/ooxLxBK/images/311690660-fig5.5.png)

    *Fig. 5.5*

12. Test that manually panning the wheels causes the servo arm to move forwards and backwards. If it does, the servo motor has been installed successfully. 

---
## Lower Platform Installation
---

*In this section, we will install the car's lower platform, which will serve as a foundation for mounting additional electronics. This involves attaching the VESC to the bottom of the foundation, mounting the foundation onto the racecar chassis, and affixing the buck converter to the top of the foundation.*

**Required Materials and Tools**

* 3D Printed Parts:
    * Back Foundation
    * Front Foundation
    * Lower Left Foundation Support
    * Lower Right Foundation Support
    * Upper Left Foundation Support
    * Crossbar Upper Support
    * Crossbar Buttom Support
* Racecar Chasis
* VESC
* Buck Converter
* 3 Pin Through Hole Male Header
* Electrical Tape
* 4 x M3 Flathead Screws (40mm)
* 27x M2.5 Hex nuts
* 10x M2.5 Flat Head Screws
* 4x M2.5 Pan Head Screws
* 4x Nylon Spacers
* Zip Ties
* 3000 mAH NiMH Battery (7.2 V)
* Super Glue
* Hex Keys
* Philips Screwdriver  

**Steps**

1. Put the 3000 mAH NiMH battery into the battery compartment on the left side of the racecar chassis. Orient the battery such that the wires run towards the front of the racecar chassis. 

2. Use two M2.5 flat head screws and nuts to attach the two tabs extending out the back of the front foundation to the corresponding holes near the front of the back foundation.

3. Note the two holes in the middle of the metal crossbar that came with the racecar chassis. Align them with the two holes in the middle of the now unified foundation (the metal crossbar should be below the foundation), and then attach the metal crossbar to the foundation with two M2.5 flathead screws and nuts. (Fig. 6.1)

    ![fig6.1.png](https://bitbucket.org/repo/ooxLxBK/images/773659141-fig6.1.png)

    *Fig 6.1*

4. Turn the foundation over so that the metal crossbar is on top. If using the **DZS Elec LM2596** buck converter, insert four M2.5 hex nuts into the holes outlined in blue in Fig. 6.2. If using the **DROK 180051US** buck converter, insert four M2.5 hex nuts into the holes outlined in red in Fig. 6.2. Add super glue into the spaces between the edge of the hole and the hex nuts in order to keep the hex nuts in place. Be careful not to get super glue into the threads of the hex nuts. Allow the super glue to dry before continuing. 

    ![fig6.2.png](https://bitbucket.org/repo/ooxLxBK/images/1965841006-fig6.2.png)

    *Fig. 6.2*

5. Insert two M2.5 hex nuts into the inlets below the screw holes of the lower right foundation support. Align the lower right foundation support with the corresponding screw holes on the foundation, and then use two M2.5 flat head screws to secure it to the foundation.

    ![fig6.3.png](https://bitbucket.org/repo/ooxLxBK/images/2079021998-fig6.3.png)

    *Fig 6.3*

6. Repeat step 5 for the lower left foundation support. (Fig 6.4)

    ![fig6.4.png](https://bitbucket.org/repo/ooxLxBK/images/3845554176-fig6.4.png)

    *Fig 6.4*
    
7. Repeat step 5 for the upper left foundation support. (Fig 6.5)

    ![fig6.5.png](https://bitbucket.org/repo/ooxLxBK/images/2931106247-fig6.5.png)

    *Fig 6.5*

8. Align the 3D printed lower crossbar support with the holes in the back of the metal crossbar, and insert two M3 40mm Flat Head screws down through the foundation. Repeat this for the 3D printed upper crossbar support and the front holes of the metal crossbar.

9. Now we will mount the VESC to the bottom of the foundation. Place it between the lower right foundation support and metal crossbar, such that it will be above the BLDC motor once the foundation has been mounted to chassis. Orient it such that the three BLDC motor connector wires run towards the back of the foundation, and the USB mini port faces towards the metal crossbar. (Fig. 6.6)

    ![fig6.6.png](https://bitbucket.org/repo/ooxLxBK/images/3407837904-fig6.6.png)

    *Fig 6.6*

10. Use zip ties slipped through the gaps in the foundation to mount the VESC to the foundation as shown in Fig. 6.7. Chain zip ties together if extra length is necessary. Make sure that the zip ties do not significantly protrude out from the top of the foundation.

    ![fig6.7.png](https://bitbucket.org/repo/ooxLxBK/images/3354383496-fig6.7.png)

    *Fig 6.7*

11. Use zip ties to secure the VESC battery wires and USB mini cable to the bottom of the foundation. (Fig. 6.8)

    ![fig6.8.png](https://bitbucket.org/repo/ooxLxBK/images/3214699224-fig6.8.png)

    *Fig 6.8*

12. Use pliers to remove the individual pins from the 3 pin male header. Use these pins to connect the three pin female header of the VESC to the three pin female header of the servo motor. Connect them such that corresponding colors are connected together (e.g. Red connects to red, black connects to black/brown).

13. Wrap electrical tape around the connection between the VESC and servo motor.

14. Organize the servo motor wire into a neat bundle with a zip tie.

15. Orient the foundation right-side-up and align it with the chassis. Connect the VESC's motor wires to the BLDC motor. Assuming the VESC is positioned above the BLDC motor and oriented as described in step 9, each VESC wire should be connected to the BLDC motor in the corresponding position. That is, the furthest left VESC motor wire should be connected to the furthest left BLDC motor wire, the middle VESC wire should be connected to the middle BLDC motor wire, and the furthest right VESC wire should be connected to the furthest right BLDC motor wire. (Fig 6.9)

    ![Screen Shot 2019-07-28 at 8.33.27 PM.png](https://bitbucket.org/repo/ooxLxBK/images/4118519116-Screen%20Shot%202019-07-28%20at%208.33.27%20PM.png)

    *Fig 6.9*

16. Mount the foundation to the chassis by screwing in the four M3 40mm flathead screws that go through the crossbar supports to the race car chassis. This may be a tight fit due to the VESC, so push down on the foundation if necessary. Make sure that none of the supports get caught on the wall of the chassis and that none of the VESC's wires get caught between the foundation and the servo cage. (Fig 6.10)

    ![fig6.9.png](https://bitbucket.org/repo/ooxLxBK/images/113651169-fig6.9.png)

    *Fig 6.10*
    
17. Insert nine M2.5 hex nuts into the hex shaped holes along the inner surface of the foundation walls. Apply super glue in between the edges of each nut and the plastic, but be careful not to get super glue into the threads of the hex nuts.

18. Slip four M2.5 pan head screws through the mounting holes of the buck converter. Then slip a nylon spacer onto each of the screw shafts. Then screw a M2.5 hex nut onto each of the screw shafts until it loosely holds the nylon spacer against the bottom surface of the buck converter. (Fig. 6.11)

    ![fig6.10.png](https://bitbucket.org/repo/ooxLxBK/images/4091367934-fig6.10.png)

    *Fig 6.11*
    
19. Insert the buck converter's mounting screws into the corresponding mounting holes of the foundation. (Fig. 6.12)

    ![fig6.11.png](https://bitbucket.org/repo/ooxLxBK/images/2518368462-fig6.11.png)

    *Fig 6.12*

---
## Buck Converter Configuration
--- 

*In this section, we will configure the buck converter. The buck converter steps down the battery voltage (~7-8 V) to the voltage required by the Jetson Nano (5.0 V). Thus, we must perpare two connections: one between the battery and buck converter, and one between the buck converter and Jetson Nano. We will also adjust the buck converter's potentionmeter to achieve the correct output voltage.*

**Required Materials and Tools**

* Barrel Connector 5.5x2.1 mm
* 2x Solderless Wire Connectors (Heat Shrink Butt Connector)
* 1/4" Heat Shrink
* Battery Connector
* 5000 mAH NiMH Battery
* Hot Glue Gun 
* Heat Gun
* Crimping Tool 
* Wire Stripper/Cutter
* Flathead Screwdriver

**Steps**

**Buck Converter to Jetson Nano Connection**

1. Cut the barrel connector's wires to a length of approximately 30 cm. Keep the extra wire as we will reuse it later. 

2. Strip approximately 7.5 mm of insulation off of the ends of the wires.

3. Use a flathead screwdriver to unscrew the output terminals of the buck converter. This allows the exposed ends of the barrel connector's wire to be slipped into the output terminals. **The red wire should go into the terminal marked OUT+, and the black wire should go into the terminal marked OUT-.** Push them in far enough such that no exposed copper hangs out of the output terminals (use wire cutters to shorten the exposed ends if necessary). 

    ![fig7.1.png](https://bitbucket.org/repo/ooxLxBK/images/3609895744-fig7.1.png)

    *Fig 7.1*

4. While holding the wires in place, tighten the output terminal screws to secure the wires in place. Gently tug on the wires to check that they will not slip out of the output terminals. **Again check that no exposed copper hangs out of the output terminal, and that there are no shorts between the two wires.** (Fig. 7.2)

    ![fig7.2.png](https://bitbucket.org/repo/ooxLxBK/images/3622309256-fig7.2.png)

    *Fig. 7.2*

5. Cover the wire insertion point and surrounding area in hot glue. This strengthens the connection and will further prevent short circuits between the two wires. (Fig. 7.3)

    ![fig7.3.png](https://bitbucket.org/repo/ooxLxBK/images/28183303-fig7.3.png)  

    *Fig. 7.3*

**Battery to Buck Converter Connection.**

6. Cut a length of wire of approximately 22 cm. Create this length of wire from the extra wire that was cut off of the barrel connector in step 1. 

7. Using two solderless wire connectors and heat shrink, connect the 22cm length of wire to the battery connector. Use the exact same process that was detailed in the *VESC Preparation* section, particularly steps 2-13.

8. Install the other end of the 22 cm length of wire into the **input** terminals of the buck converter. The process is exactly the same as steps 2-5 in the previous subsection, except that **the red wire should go into the terminal marked IN+, and the black wire should go into the terminal marked IN-**.

9. The connections for the input and output of the buck converter are now complete, as shown in Fig 7.4.

    ![fig7.4,7.57.6.png](https://bitbucket.org/repo/ooxLxBK/images/838253025-fig7.4,7.57.6.png)

    *Fig 7.4*
    
**Buck Converter Voltage Adjustment**

*The following instructions detail voltage adjustment for the **DZS Elec LM2596** buck converter. If you are using a different buck converter, follow the manufacturer's instructions to set the output voltage to 5V.*

10. Before continuing, **make sure that the barrel connector is NOT plugged into the Jetson Nano.** 

11. Place the 5000 mAH battery in the lower foundation's right battery compartment, and plug it into the buck converter. The buck converter's LED screen should light up and display numbers.

12. Press the button labeled **OUT** on the buck converter.

13. Use a flat head screw driver to adjust the potentiometer until the LED screen displays *5.0*, which indicates that the buck converter is outputting 5V.

14. Unplug the battery from the buck converter.

15. Place hot glue over the potentiometer to prevent any inadvertant adjustment of the potentiometer in the future. (Fig. 7.5)

    ![fig7.4,7.57.6 copy.png](https://bitbucket.org/repo/ooxLxBK/images/2579584104-fig7.4,7.57.6%20copy.png)

    *Fig 7.5*

16. Expose the adhesive backing of the heat sink that came with the buck converter and attach it to the IC shown in Fig. 7.6.

    ![fig7.4,7.57.6 copy 2.png](https://bitbucket.org/repo/ooxLxBK/images/370635846-fig7.4,7.57.6%20copy%202.png)

    *Fig 7.6*

---
## Push Button Installation
---

*In this section, we will mount the push button to the chassis' front bumper.*

**Required Materials and Tools**

* Racecar Chassis
* Push Button
* 4x Female to Female Jumper Cable
* 1K Ohm Resistor
* 1/8” Heat Shrink
* 2x 20mm M2.5 Pan Head Screws
* 2x M2.5 Hex Nuts
* 4x Nylon Spacers
* Electrical Tape
* Screw Driver
* Heat Gun
* Wire Cutters/Strippers

1. Slip a nylon spacer onto each of the two 20mm M2.5 Pan Head Screws, and then insert the screws through the mounting slots of the push button.

2. Align the mounting slots of the push button with the slots on the front bumper. (Fig. 8.1)

    ![1.png](https://bitbucket.org/repo/ooxLxBK/images/2891707108-1.png)
 
    *Fig. 8.1*

3. Slip another nylon spacer onto each of the screw shafts so that they are pressed up against the back surface of the front bumper.

4. Secure the push button onto the front bumper by installing nuts onto the screw shafts. (Fig. 8.2)

    ![2.png](https://bitbucket.org/repo/ooxLxBK/images/440394051-2.png)

    *Fig. 8.2*

5. Slip the push button's wires underneath the chassis' lower suspension, and then up through one of the holes in the front foundation. (Fig. 8.3)

    ![3.png](https://bitbucket.org/repo/ooxLxBK/images/394427460-3.png)
    
    *Fig. 8.3*

6. Use the wire cutters to remove one of the female housings three of the jumper cables. Strip approximately one centimeter of insulation off of each of the cut ends. We will assign a letter to each jumper cable, so we have jumper cable A, jumper cable B, and jumper cable C. We will refer to the remaining, uncut jumper cable as jumper cable D.

7. Trim both of the resistor's legs to be approximately 1cm long.

8. Take jumper cables A and B and tightly twist their exposed copper around one of the legs of the resistor. (Fig. 8.4)

    ![4.png](https://bitbucket.org/repo/ooxLxBK/images/3350641686-4.png)

    *Fig. 8.4*

9. Cut an approximately 5cm piece of 1/8" heat shrink and slip it onto jumper cable C.

10. Tightly twist the exposed copper of jumper cable C around the unconnected leg of the resistor. (Fig. 8.5)

    ![5.png](https://bitbucket.org/repo/ooxLxBK/images/3285403884-5.png)
   
    *Fig. 8.5*
    
11. Slip the heat shrink over the resistor so that it covers all exposed metal. Use a heat gun to uniformaly shrink the heat shrink. (Fig. 8.6)

    ![6.png](https://bitbucket.org/repo/ooxLxBK/images/1654066569-6.png)

    *Fig. 8.6*

12. Connect jumper cable A to the push button's white wire, and jumper cable D to the push button's black wire. Wrap electrical tape around the connection. In a later section, we will finish connecting the push button to the Jetson Nano.

---
## YDLIDAR Installation
---

*In this section, we will mount the YDLIDAR to the top of the racecar's back cover.*

**Required Materials and Tools**

* 3D Printed Parts
    * Back Cover Top
* YDLIDAR
* USB Micro Splitter
* 4x M2.5 Pan Head Screws
* 8x M2.5 Hex Nuts
* 4x Nylon Spacers
* Hex Keys
* Philips Screw Driver

**Steps**

1. Orient the 3D printed back cover top (BCT) so that the side with exactly eight round holes faces upwards. 

2. A separate printed circuit board (PCB) comes with the YDLIDAR. Insert four M2.5 pan head screws through its mounting holes. Then slip a nylon spacer onto each of the screw shafts. Then slip a M2.5 hex nut onto each shaft. The nut should loosely hold the nylon spacer against the bottom surface of the PCB.

3. Align the PCB's mounting screws with the set of four holes on the BCT that are closest together. Orient the board so that the USB ports are facing towards the rectangular hole. Secure the screws in place with four M2.5 nuts inserted through the bottom of the BCT. (Fig. 9.1, 9.2)

    ![fig8.1.png](https://bitbucket.org/repo/ooxLxBK/images/2631203721-fig8.1.png)

    *Fig 9.1*

    ![fig8.1.2.png](https://bitbucket.org/repo/ooxLxBK/images/34050691-fig8.1.2.png)

    *Fig 9.1*

4. Insert the legs of the YDLIDAR into the holes on top of the BCT. Secure them in place by inserting the four screws into the corresponding holes of the bottom of the BCT. Use the fours screws that came with the YDLIDAR.

5. Connect the YDLIDAR to the PCB with the provided set of wires. Also, plug the USB micro splitter into the PCB. Note the red plastic around one of the USB micro splits. This corresponds to power, which should be plugged into the USB connector labeled **PWR** on the PCB. Put the other USB micro split into the other USB connector of the PCB. Guide the USB Type A end through the rectangular hole of the BST.

6. The YDLIDAR is now successfully mounted, as shown in Fig. 9.3.

    ![fig8.2.png](https://bitbucket.org/repo/ooxLxBK/images/2828026749-fig8.2.png)

    *Fig 9.3*

---
## Jetson Nano Wi-Fi Card Installation
---

*In this section, we will install a Wi-Fi card and antennas into the Jetson Nano.*

**Required Materials and Tools**

* Jetson Nano 
* Wi-Fi Card 
* 2x Wi-Fi Antenna
* Philips Screw Driver 

**Steps**

1. Connect the Wi-Fi antennae to the Wi-Fi card. To do this, first place the card on a flat surface. To connect an antenna, align the neck of its connector to be perpendicular to the back edge of the card. Tilt the antenna connector so that only the back part is making contact with the connector on the card as shown in Fig 10.1. Place your thumb on top, and then apply firm pressure as you roll your thumb forward along the antenna connector. It should snap into place. It is a tight fit and can be difficult to make the connection, but do not force it as the connectors can break.

    ![fig9.1.png](https://bitbucket.org/repo/ooxLxBK/images/3072838218-fig9.1.png)

    *Fig 10.1*

3. Take out the two screws that secure the Jetson module to the carrier board. (Fig. 10.2) 

    ![fig9.2.png](https://bitbucket.org/repo/ooxLxBK/images/4042565311-fig9.2.png)

    *Fig 10.2*

4. Release the side latches that are on both sides of the module. These latches hold the module in place, and once released the module will pop up. Gently pull on the Jetson module to remove it. (Fig. 10.3)

    ![fig9.3.png](https://bitbucket.org/repo/ooxLxBK/images/1517097560-fig9.3.png)

    *Fig 10.3*

5. Remove the #2 screw located in the center of the board.

6. Position the Wi-Fi card at a slight angle and insert it into the M.2 connector. 

7. Re-insert the #2 screw to secure the Wi-Fi card in place. 

8. Route the antennae wires such that they lay between the two Jetson module screw mounts. (Fig. 10.4)

    ![fig9.4.png](https://bitbucket.org/repo/ooxLxBK/images/3338508918-fig9.4.png)

    *Fig 10.4*

9. Position the Jetson Nano module at a slight angle before re-inserting it into the carrier board socket. Push it back down so that it is retained by the latches.

10. Re-insert the screws to secure the Jetson module. 

11. The Wi-Fi card is now successfully installed into the Jetson Nano.

---
## SD Card Setup
---

*In this section, we will write a system image with pre-installed MuSHR software to an SD card, and then insert that SD card into the Jetson Nano.*

**Required Materials and Tools**

* Jetson Nano 
* SD Card - (64GB or larger) 
* Computer with
    * Internet Connection 
    * Ability to Read and Write SD Cards (*[SD Card USB Adapter](https://www.amazon.com/Reader-Laptop-Windows-Chrome-RS-MMC/dp/B07MK99R14)*)

**Steps**

1. Download and decompress the MuSHR system image from *[here](https://drive.google.com/open?id=1KgW5MtAw83IgkHb4FP6z9KN8QxQ0kwkb)*.

2. Flash the MuSHR image onto the SD card following the instructions *[here](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit#write)*.

3. Insert the SD card into the Jetson Nano's SD card slot.

---
## Back Cover Installation
---

In this section, we will assemble the back cover, mount the Jetson Nano, and attach the back cover to the foundation.

**Required Materials and Tools**

* Jetson Nano 
* 3D Printed Parts:
    * Back Cover Top (w/ LIDAR mounted)
    * Back Cover Left Side
    * Back Cover Right Side
* Racecar Chasis
* 12x M2.5 Hex Nuts
* 8x M2.5 Pan Head Screws
* 4x M2.5 Flat Head Screws
* 12x Spacers
* Pin Jumper
* Hex Keys
* Tweezers  
* Pliers
* Philips Screwdriver 

**Steps**

1. Before continuing, **the LIDAR should already be mounted to the 3D printed back cover top (BCT).** 

2. Insert a M2.5 pan head screw into each of the Jetson Nano's mounting holes. Then place two spacers on each screw shaft, followed by a M2.5 hex nut. Screw the nut onto the shaft such that it loosely holds the upper spacer against the bottom surface of the Jetson Nano.

3. Insert a M2.5 hex nut into each of the four hex inlets on the sides of the BCT. (Fig. 12.1)

    ![fig11.1.png](https://bitbucket.org/repo/ooxLxBK/images/572490577-fig11.1.png)
    
    *Fig 12.1*

4. Align the 3D printed back cover right side with the two holes on the right side of the BCT that are above the inlets from the previous step. Before inserting a M2.5 pan head screw into each of these holes, slip one nylon spacer onto the screw shaft.

5. Repeat the previous step with the 3D printed back cover left side in order to attach it to the BCT.

6. Observe the bottom surface of the BCT (i.e. the side opposite to the one the LIDAR is mounted on). Note the four mostly hexagonal holes near where the BCT connects to the back cover left side and back cover right side. Insert a M2.5 hex nut into each of these holes, and align their thread hole with the round portion of the hole. (Fig. 12.2)

    ![fig11.2.png](https://bitbucket.org/repo/ooxLxBK/images/884939768-fig11.2.png)

    *Fig 12.2*

7. Tilt the back cover so that the hex nuts from the previous step stay in place. Simultaneously align the Jetson Nano with these hex nuts, and secure its mounting screws to the BCT. (Fig. 12.3)

    ![fig11.3.png](https://bitbucket.org/repo/ooxLxBK/images/4210668053-fig11.3.png)

    *Fig 12.3*

8. Now that the Jetson Nano has been mounted, put a pin jumper on the J48 header, as shown in Fig 12.4, so that the Jetson Nano draws power from the DC barrel jack.

    ![fig11.4.png](https://bitbucket.org/repo/ooxLxBK/images/170809248-fig11.4.png)

    *Fig. 12.4*

9. Next, we will connect the push button to the Jetson Nano's breakout pins. Note that in the following description, all pins refer to pins found on the Jetson Nano's J41 header, and that we will refer to specific jumper cables as defined in the push button installation section. Connect jumper cable B to Pin 33, which serves as an input GPIO pin. Connect jumper cable C to Pin 1, which connects the pull-up resistor to 3.3V. Finally, connect jumper cable D to Pin 39, which serves as a ground connection when the button is pressed.

10. Optionally, apply hot glue to ensure that jumper cables B,C, and D do not become disconnected from their respective pins on the J41 header. 

11. Expose the adhesive on the back of each of the antennas, and attach them to the side walls of the back cover.

12. Use four M2.5 flat head screws to mount the back cover to the foundation. (Fig. 12.5)

    ![Screen Shot 2019-07-28 at 9.10.04 PM.png](https://bitbucket.org/repo/ooxLxBK/images/2972127422-Screen%20Shot%202019-07-28%20at%209.10.04%20PM.png)

    *Fig. 12.5*

    
---
## Front Cover Installation
---

In this section, we will mount the D435i Realsense camera to the front cover of the car, and attach the front cover to the foundation.

**Required Materials and Tools**

* Intel D435i Camera 
* USB 3.0 1ft Cable
* 3D Printed Parts:
    * Racecar Front Cover Whole
* Racecar Chasis
* 5x Flat Head Screws
* 2x 6mm M3 Pan Head Screws
* Pliers 
* Hex Keys 
* Philips Screwdriver 

**Steps**

1. Plug the 1ft USB 3.0 cable into the D435i camera. Note that we are not using the USB cable that comes with the camera because it is excessively long.

2. Guide the USB cable from the outside of the front cover to the inside through the gap near the mounting holes. (Fig. 13.1)

    ![fig12.1.png](https://bitbucket.org/repo/ooxLxBK/images/3808359714-fig12.1.png)

    *Fig 13.1*

3. Use two 6mm M3 screws to mount the D435i camera to the front cover.(Fig. 13.2)

    ![fig12.2.png](https://bitbucket.org/repo/ooxLxBK/images/151068752-fig12.2.png)

    *Fig 13.2*

4. Use five M2.5 flat head screws to mount the front cover to the race car. (Fig. 13.3)

    ![fig12.3.png](https://bitbucket.org/repo/ooxLxBK/images/1636758027-fig12.3.png)

    *Fig 13.3*
    
---
## Final Assembly
---

In this section, we will finish assembling the racecar.

**Required Materials and Tools**

* Wireless Controller
* Racecar Chassis
* 3D Printed Parts:
    * 2x Racecar Cover Image
    * Racecar Cover Number
* Zip Ties
* Super Glue

1. Plug the wireless controller's dongle into the included range extender. Note that you could skip steps 1-5 of this section and just directly plug the dongle into the Jeton Nano's USB. However, we have observed that the range extender improves the controller's wireless connection.

2. Remove the two screws that mount the back bumper to chassis. Place the range extender's wire inbetween the two screw holes before re-inserting the screws. (Fig. 14.1)

    ![1.png](https://bitbucket.org/repo/ooxLxBK/images/1150745629-1.png)

    *Fig. 14.1*

3. Mount the range extender to the back bumper with two daisy chained zip ties. (Fig. 14.2)

    ![2.png](https://bitbucket.org/repo/ooxLxBK/images/1286161650-2.png)

    *Fig. 14.2*

4. Plug the range extender into one of the Jetson Nano's USB ports. 

5. Tightly bundle the range extender's wire and attach it below the back bumper with a zip tie. (Fig. 14.3)

    ![3.png](https://bitbucket.org/repo/ooxLxBK/images/1726164376-3.png)

    *Fig. 14.3*
    
6. Route the VESC's USB cable up through the hole in the foundation near the left battery compartment. Plug it into one of the Jetson Nano's USB ports.

7. Plug the YDLIDAR's USB cable into one of the Jetson Nano's USB ports.

8. Plug Realsense D435i's USB cable into one of the Jetson Nano's USB ports.

9. Make sure that the 5000 mAH battery is not plugged into the buck converter. Then plug the barrel connector into the Jetson Nano.

10. Apply super glue to one of the insets on the outside of the back cover. Insert one of the 3D printed cover images into the inset.

11. Repeat step 10 for the cover image on the other side of the back cover, and for the cover number in the center of the front cover.

12. Congratulations, you have finished building the MuSHR Racecar! (Fig 14.4)

    *Fig. 14.4*
