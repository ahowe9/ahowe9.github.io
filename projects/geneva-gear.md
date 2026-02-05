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

**Demo:** [![Customizer In Action](/docs/assets/images/GenevaGearThumbnail.png)](/docs/assets/videos/GenevaGearDemo.mp4)

## Technical Highlights
By completing this project, I was able to learn about how to construct complex geometry with the Fusion 360 API, along with creating kinematic relationships between components. 

## Future Versions
In future iterations of this project, I want to add input validation to prevent certain sets of user inputs that would not create a valid topology. Additionally, I want to create a cleaner UI instead of the five different on-screen prompts.
