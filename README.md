# 6-DoF-Manipulator-Simulation

This project focuses on simulating a 6 Degree-of-Freedom (DoF) robotic arm manipulator using ROS. The simulation involves creating a URDF file, path planning, and controlling the robotic manipulator.

---

## Milestone 1: Create URDF and GUI to Change Robot Angles

### Steps:

1. Run `vis.launch`.
2. Load the robot model in `rviz`.
3. Change the fixed frame to `base link`.

### Output:

![Milestone 1 Output](https://github.com/MostafaELFEEL/6-DoF-Manipulator-Simulation/assets/106331831/8c8e17c6-66cf-40d8-b6cf-232256babda4)

### After Interacting with the GUI:

![Milestone 1 After GUI](https://github.com/MostafaELFEEL/6-DoF-Manipulator-Simulation/assets/106331831/05911fbd-54e3-4707-b0c3-6863b883cf7f)

---

## Milestone 2: Use MoveIt Tool with KDL Planner and Generate Collision Matrix

### Steps:

1. Plan using the KDL planner in MoveIt.
2. Generate the collision matrix.
3. Verify the motion by running `demo.launch`.

### Output:

![Milestone 2 Output](https://github.com/MostafaELFEEL/6-DoF-Manipulator-Simulation/assets/106331831/45132640-5431-4269-9b9c-eb1dfc13f589)

---

## Milestone 3: Implement PID Control for the Robot

### Steps:

1. Add mass and inertia properties to the robot links.
2. Utilize the MoveIt tool with the control section included.
3. Adjust the PID control gains from `ros_controller.yaml` and simulation speed from `joint_limits.yaml`.
4. Execute `demo_gazebo.launch` to observe the control action.
5. Publish coordinates in space for the robot to navigate by running `moveit.py` (coordinates specified in lines 50, 51, 52).

### Output:

![Milestone 3 Output](https://github.com/MostafaELFEEL/6-DoF-Manipulator-Simulation/assets/106331831/a2f6fba9-5908-4ce5-a69a-a727be793a1a)

### After Running `moveit.py`:

![Milestone 3 After moveit.py](https://github.com/MostafaELFEEL/6-DoF-Manipulator-Simulation/assets/106331831/fe27d941-e393-49e0-9a6e-2c3e54722d95)
