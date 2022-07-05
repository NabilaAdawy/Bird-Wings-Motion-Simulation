# Bird-Wings-Motion-Simulation
Design and Implementation of a Mechanism that Simulates the Motion of a Bird Wings, using only one Motor. 
- First step, I started by calculating the kinematics of the mechanism and simulate it using Geogebra to make sure it is working. 
- Second, I Designed the mechanism using Fusion360. 
- Third, I made dynamics analysis using Ansys workbench, to find the required torque from the motor to derive the mechanism according to the desired motion. 
- Forth, I made static structural analysis for the mechanism to determine the stresses, strains, and the displacements, resulted from the forces in the structure. 
- Fifth, I 3D printed the design and assembled it.

# Kinematics
Here the goal is to find the positions (and velocities) of a mechanism that simulates the motion of a bird wing. Due to the complex motion, we can divide the mechanism into 3 separate mechanisms to simplify the calculations:
• First Mechanism is a planetary gear. 
• Second Mechanism is a 5-bar linkage. 
• Third Mechanism is a 4-bar linkage.

### Kinematic Simulation using Geogebra:
https://www.geogebra.org/calculator/ckuxrbtj

# CAD & Dynamics
Here the goal is to design a mechanism that simulates the motion of the bird wing. Then solve the dynamics of the mechanism to find the required torque from the motor to derive the mechanism according to the desired motion. The tools used are Fusion360 and Ansys workbench.

### Motion Animation of the design (Dynamics Simulation):
![motion_Animation](https://user-images.githubusercontent.com/22743949/162501330-d8abf152-c442-46c8-87cb-214890e9a928.gif)

#CAE Analysis
Here the goal is to make static structural analysis for the mechanism to determine the stresses, strains, and the displacements, resulted from the forces in the structure. I chose this type of analysis because there are no time-varying forces/loads in the mechanism. Hence, we will study how steady-state inertial forces affects on the mechanism structure. The tool used is Fusion360.
