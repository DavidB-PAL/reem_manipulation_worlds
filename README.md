### ROS Node: reem_manipulation_worlds
Copyright (c) 2013, David Butterworth, PAL Robotics S.L.
<br>
<br>
A collection of Gazebo simulation worlds and objects, used for testing manipulation with the REEM robot.

Tested with ROS Fuerte. The Gazebo Fuerte "grasping hack" must be used, and is enabled in reem_description.

ToDo: Gazebo Fuerte has bugs which prevent display of some object textures, and if the floor plane is enabled it destabilizes the robot.

Based on manipulation_worlds for PR2, and reem_robocup_worlds.


**Required ROS packages:** <br>
reem_simulation

**Usage:** <br>
Launch one of the examples below. See the 'Documentation' directory for photos of each world.
<br>
<br>
**REEM in front of high white table (1.02m), with small box for grasping by left arm, & other objects** <br>
$ roslaunch reem_manipulation_worlds reem_high_white_table_manipulation.launch

**REEM, high wooden table (1.02m) with red legs, coke can** <br>
$ roslaunch reem_manipulation_worlds reem_high_wooden_table_with_coke.launch

**REEM, high white table (1.02m), 4 coke cans, for testing max dimensions of Kinect** <br>
$ roslaunch reem_manipulation_worlds reem_high_white_table_with_many_cokes.launch

**REEM, low wooden table (0.765m), 5 objects** <br>
$ roslaunch reem_manipulation_worlds reem_wooden_table_withobjects.launch


