# ros-amcl-localization
Localization of a turtlebot using Adaptive Monte Carlo Localization ROS package. 'Where Am I?' project done as a part of the Udacity Robotics Software Engineering Nanodegree.


This application creates a 2D map of a custom Gazebo world and localizes a turtlebot within it as the robot drives around. 

To launch the Gazebo world with the robot:

`roslaunch my_robot world.launch`

To launch the amcl algorithm:

`roslaunch my_robot amcl.launch`

Move the robot around with your keyboard using turtlebot's teleop package:

`rosrun teleop_twist_keyboard teleop_twist_keyboard.py`


---

You will see the robot being localized in RVIZ. RVIZ is already configured to show the robot within the map and the particles as a they are resampled by the amcl algorithm. 
Rviz launches automatically when the Gazebo world is launched.

---

Output Screenshots:

![Screenshot (141)](https://user-images.githubusercontent.com/60242931/179150707-f963cfc6-a38b-461e-9f3a-7915c6869f35.png)

![Screenshot (142)](https://user-images.githubusercontent.com/60242931/179150724-13917b47-ee0f-4011-be4c-0633e57cde2a.png)

![Screenshot (143)](https://user-images.githubusercontent.com/60242931/179150739-a0e02b88-3d85-4fcc-95f9-b22753d34952.png)

![Screenshot (144)](https://user-images.githubusercontent.com/60242931/179150752-03fbe3d4-ce2f-48db-b643-7c94d6505d9b.png)

![Screenshot (145)](https://user-images.githubusercontent.com/60242931/179150772-c2f01ceb-d0e8-4056-ba59-60cbb4da4dd7.png)

![Screenshot (146)](https://user-images.githubusercontent.com/60242931/179150789-fd05ebe5-a7c4-48e7-9154-7554157264f8.png)

