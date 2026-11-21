# 6-DoF ROV Simulation in Simulink

Spatial Robotics coursework: a Simulink model of a six-degree-of-freedom underwater vehicle (ROV) using a nonlinear quaternion-based model, with position and orientation displays and a 3D virtual-reality view.

## What's in it

- `Assignment_2_Spatial_Robotics.slx`: the Simulink model. It includes the nonlinear 6-DoF ROV subsystem, initial position and orientation inputs, roll/pitch/yaw displays and a VR Sink for 3D visualisation.

## Running it

Requires MATLAB and Simulink (with the Simulink 3D Animation toolbox for the VR view). The 3D scene (VRML file and textures) and helper functions come from the course materials and are not included in this repository, so the model will open and simulate but the 3D view needs those assets.
