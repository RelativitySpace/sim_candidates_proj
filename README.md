## Relativity Space - Simulation engineering candidates' project
This readme contains a project that candidates can work on as a take-home project

### Instructions:
1. Solve the problems from this repo
    * You can use any simulation tool you want but ANSYS is recommended. If you don't have access to simulation software we can provide a machine that has Ansys and you can Remote Desktop into it from web browser. Ask your interviewer for access. The machine will be available to you for two days.
    * Depending on your time and level of enthusiasm about the problem you can choose to do only parts of the problem
2. Once done, email the results requested back to your interviewer.

Open an issue on this repo if you have any questions about the problems.

Adding clarification and description as powerpoint, pdf, or readme file is welcomed if needed.

### Project : Simulating FDM process
The goal of project is to simulate FDM process using laser as energy source. If you are not familiar with the FDM process read [its Wikipedia page](https://en.wikipedia.org/wiki/Fused_deposition_modeling). The process involves a laser as energy source, a wire feed and build platform which is the same material as wire.

![Directed Energy Deposition with laser](/images/ded1.png)

The deposition and the build platform moves under the laser and wire feed, as wire is pushed out and laser melts the wire and forms the part layer by layer. Alternatively laser and wire feed can move instead of the build plate.

![Directed Energy Deposition with laser](/images/ded2.png)

Check out the [video](https://github.com/RelativitySpace/sim_candidates_proj/raw/master/videos/print.mp4) of the described process.

The goal is to simulate around three inches of straight deposition and capture maximum depth of molten material throughout the deposition.

#### Assumptions
1. Diameter of the wire is 0.03 inches
2. Wire feed rate is 150 inches per minute
4. Speed of movement of the build plate with respect to laser and wire feed is 100 inches per minute
5. Laser spot size is circular with 0.1 inches in diameter
6. Total laser power absorbed is 3KW
7. Feel free to make reasonable assumptions about other details that are not mentioned here. Please include your assumptions when submitting the results
8. You can use aluminum for material
10. The run will be a transient simulation running for 2 seconds

#### Deliverables
1. Capture and report maxim depth of molten material through out the simulation for every time step.
2. Animation that shows liquid fraction of the cross section in the middle of the deposited material. For example see below:

![Liquid fraction of the cross section](/images/liquid_fraction_xsection.png)

