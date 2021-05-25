# learning_ros
This is a course project that contains the main program that makes the baxter robot grab the coke can from the side and put it down.

To run this file, we need to first enter the following commands:

1:$ roslaunch gazebo_ros empty_world.launch
2:$ roslaunch baxter_variations baxter_on_pedestal_w_kinect.launch
3:$ roslaunch coordinator coord_vision_manip.launch
4:$ rosrun coordinator grab_coke_can_client
5:$ rosrun coordinator dropoff_coke_can_client



