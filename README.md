# Dual-Arm-Robot-Force-Controlled-Object-Manipulation
This Repository is the complete workspace of a project that realizes force-controlled object manipulation with a dual-arm-robot (UR5 and UR10). You can watch a demonstration video of the system by following this link: https://www.youtube.com/watch?v=O0-cC2ST5L8


# Package overview:
dual_arm_robot_applications: This package contains all important Files to execute using rosrun and roslaunch and start the demonstration.

dual_arm_robot_description: This package contains the description files of the robot and the environment including the table and the side walls.

dual_arm_robot_driver: This package contains configuration files for the controller.

dual_arm_robot_moveit_config: This is the package generated by the MoveIt! Setup Assistant. It’s configured to function with ROS Control.

joint_trajectory_admittance_controller: This package contains the source code of the controller that is used for the force-controlled grasp. It's based on the 


# Run demonstration:
1. roslaunch dual_arm_robot_ros_control_rviz.launch
2. rosrun dual_arm_robot_demonstration


# Documentation:
For German speakers my master's thesis provides more detailed information. For everyone else I hope some of the diagrams are useful!
