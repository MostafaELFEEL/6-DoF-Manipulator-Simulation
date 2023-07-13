# 6-DoF-Manipulator-Simulation

The idea of the project is to use ROS to simulate a 6 DoF robotic arm manipulator. The simulation includes creating a URDF file, path planning, and controlling the robot manipulator. 
## Milestone 1: Create URDF and gui to change robot angles
### Steps:
  1- Run vis.launch.
  
  2- Load robot model on rviz.
  
  3- Change fixed frame to base link.
### Output:
![image](https://github.com/MostafaELFEEL/6-DoF-Manipulator-Simulation/assets/106331831/8c8e17c6-66cf-40d8-b6cf-232256babda4)

### After playing with the gui:

![image](https://github.com/MostafaELFEEL/6-DoF-Manipulator-Simulation/assets/106331831/05911fbd-54e3-4707-b0c3-6863b883cf7f)

## Milestone 2: Use moveit tool to plan (KDL planner) and generate collision Matrix then verify the motion by running demo.launch

### Output:
![image](https://github.com/MostafaELFEEL/6-DoF-Manipulator-Simulation/assets/106331831/45132640-5431-4269-9b9c-eb1dfc13f589)

## Milestone 3: PID control of robot

### Steps: 
  1- Add mass and inertia to robot links.
  
  2- Use moveit tool again but this time add the control section.
  
  3- Modify the pid control gains from ros_controller.yaml and adjust speed of simulation from joint_limits.yaml.
  
  4- Run demo_gazebo.launch and check the control action.
  
  5- Finally you can publish coordinates in space for the robot to move to by running moveit.py (coordinates in line 50,51,52).
  

### Output:
![image](https://github.com/MostafaELFEEL/6-DoF-Manipulator-Simulation/assets/106331831/a2f6fba9-5908-4ce5-a69a-a727be793a1a)

### After running moveit.py:

![image](https://github.com/MostafaELFEEL/6-DoF-Manipulator-Simulation/assets/106331831/fe27d941-e393-49e0-9a6e-2c3e54722d95)


