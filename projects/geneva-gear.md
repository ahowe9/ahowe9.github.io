# Geneva Gear Customizer
Fusion 360 API | Design Automation | Mechanism Kinematics

## Problem
While developing a dispensing robot, my team explored using a Geneva mechanism to dispense one item per revolution. However, modeling Geneva gears in Fusion 360 was a time-consuming process, significantly slowing our rapid prototyping process.

## Solution
I developed a parametric Geneva gear generator using the Fusion 360 API that automates geometry creation and kinematic setup.

Design goals:
- Fully parametric, enabling rapid prototyping
- Encode the kinematic relationships, eliminating manual joint creation.
- Use analytic geometry and geometric constraints, ensuring a valid set of input produces a pair of gears

## Parameter List
- Driven Geneva gear radius
- Number of slots
- Slot radius
- Backlash
- Gear thickness

## Results
This script reduces the design iteration time from minutes to seconds, allowing rapid prototyping.

**Demo:** 
*Click the image to see a video of the perspective*
[![Customizer In Action](/docs/assets/images/GenevaGearThumbnail.png)](/docs/assets/videos/NewGenevaGearScript.mp4)

## Technical Highlights
By completing this project, I was able to learn about how to construct complex geometry with the Fusion 360 API, along with creating kinematic relationships between components. 

## Recent Changes
I recently added a GUI to the script so the user could see the updates to the gears in real time. Additionally, I included a feature using JSON to store the users parameters every time they use the add-in. There are safeguards put in place in case the JSON file is missing or the parameters have been deleted.

![GUI Picture](/docs/assets/images/GUI.png)
*Current look of the GUI*

**[Homepage](/index.md)**
