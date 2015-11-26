# _pHRIWARE_ #
pHRIWARE (pron. 'freeware') provides tools to analyse, research and evaluate physical human-robot interactions. Many of these tools also requires the Robotics Toolbox for MATLAB(R) (RTB), developed by Peter Corke. This may be downloaded at www.petercorke.com.

pHRIWARE is licensed under the LGPL.

The primary tools pHRIWARE provides are:

## Human Arm-like Kinematics ##
Create a kinematic model with the HAL class, a subclass of SerialLink (RTB). Key features include analytic inverse kinematics and workspace generation (converting points in Cartesian space to full co-ordinate frames), with many direct methods to handle the kinematic redundancy of the swivel angle

## Collision Checking ##
Conduct efficient point-primitive collision checking - test if points are within 3D geometric primitives. Combine multiple primitives to create more complex CollisionModels (requires Symbolic Toolbox). Models of the human head and torso and right arm are included, and others. Direct functionality with version 9.9+ of RTB, which uses STL point data from SerialLink objects.

## RTB Patches and Add-ons ##
Includes faster, more accurate general inverse kinematics (requires Optimisation Toolbox). Resolve redundant robots by avoiding joint limits (requires Optimisation Toolbox). Quickly calculate joint torques due to gravity without a MEX file, and determine the static payload capacity of your robot.