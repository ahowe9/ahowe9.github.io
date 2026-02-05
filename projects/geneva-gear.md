# Geneva Gear Customizer

For the dispensing robot project later on in the portfolio, my team initially thought of using a Geneva gear to dispense one item per revolution. The issue with this is that creating Geneva gears can take considerable time due to the complexity of the geometry and defining the joints to ensure proper motion. Due to this, iterating on the Geneva gears took a considerable amount of time, and I wanted a way to rapidly generate these gears.

When creating the script, I wanted it to have these capabilities:
- Be parametric, so the user has the freedom to customize their gears for rapid prototyping
- Encode the kinematic relationships so the user does not have to add joints
- Create constraints and use geometry to ensure a valid set of input produces a pair of gears

[![Customizer In Action](docs/assets/images/Screenshot 2026-02-04 234254.png)](docs/assets/Untitled design (4).mp4)

By completing this project, I was able to learn about how to construct complex geometry with the Fusion 360 API along with creating kinmatic relationships between components. This project lets the user iterate on a design on a much smaller time scale when compared to creating this design from scratch. In future iterations of this project, I want to add some checks to ensure that the user input is valid and make a nicer UI for the parameters.
