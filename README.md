# learning_ros
This is a course project that contains the main program that makes the baxter robot grab the coke can from the side and put it down.

To run this file, we need to first enter the following commands:

1:$ roslaunch gazebo_ros empty_world.launch

2:$ roslaunch baxter_variations baxter_on_pedestal_w_kinect.launch

3:$ roslaunch coordinator coord_vision_manip.launch

4:$ rosrun coordinator grab_coke_can_client

5:$ rosrun coordinator dropoff_coke_can_client

The first three instructions are necessary to run the program and are essential. They carry the environment in which the program runs and prepare the baxter robot for subsequent work.

The fourth command is a grasp command for the baxter robot. Run this command and you will see the baxter robot grabbing the coke can from the side.

The last command is the dropoff command. Run this command and you will see the baxter robot place the coke can in its hand on the table.
