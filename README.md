# Urban_Search_and_Rescue
When a disaster occurs, the map of the area is lost as some part of it destroyed or modified, So in this Urban Search and Rescue operation, first a robot explores the area thoroughly and builds a map of the area and also searches for possible location of any victims and store the location and send it to the rescue team, which one more rescue robot. 

Here, in this project, we are simulating a simplified version of the mission. There are two turtlebots, one as "explorer" and the other as "follower". The explorer job is to explore the area, build a map and locate victims (but in this project map is already built) and store the location of the victims, go back to startng point and pass the location date to the follower. The follower will then visit all locations which was passed by explorer and save/rescue the victims.


Instructions to run the package:

Clone the repository into your catkin build workspace:
git clone https://github.com/Madhunc5229/Urban_Search_and_Rescue

Install turtlebot3 package:
sudo apt install ros-melodic-turtlebot3-*

Add ArUco markers to the Gazebo model:
export GAZEBO_MODEL_PATH=$GAZEBO_MODEL_PATH:/home/username/catkin_ws/src/package_name/models

Build the package using catkin build 
Source the bash
Type the following commands to launch the project:

roslaunch package_name multiple_robots.launch
rosrun package_name final_project_node

If you clone this repository, package name is 'Urban_Search_and_Rescue'
