# coppeliasim_mapping_from_line_follower_robot

This project is a small demonstration of SLAM - Simultaneous Localization and Mapping. 

SLAM plays an important role in the autonomous navigation of a mobile robot.

ROS (Robot Operating System) has many in-built algorithms for mapping, but mapping in Coppeliasim is quite different. We use, LUA script and some mapping related functions to get the map of the coppeliasim environment.

## Steps to implement this project:
  1. Download the latest version of Coppeliasim from the given link. Select the EDU version for no usage restrictions.
     
         https://www.coppeliarobotics.com/downloads
       
     
  2. Copy the map_file from the map_files folder in the main directory where the coppeliasim is installed.
  3. The map file is specified specifically for the type of OS being used. i.e., Windows, Linux or Mac OS
  4. Open CoppeliaSim Edu application and the open the uploaded scene.
  5. Click on Start simulation in the menu bar to run the simulation
  6. If everything goes well, you will get the entire map of the environment as the robot finishes one complete cycle. 


# Mobile Robot

The Robot Model is shown below for reference
![alt text](https://github.com/vishal-kasyap/coppeliasim_mapping_from_line_follower_robot/blob/main/coppeliasim_mapping_from_line_follower_robot/robot_in_coppeliasim_world.png "Robot Model")

# Map Created

By executing the above code, the map of the environment obtained is shown below

![alt text](https://github.com/vishal-kasyap/coppeliasim_mapping_from_line_follower_robot/blob/main/coppeliasim_mapping_from_line_follower_robot/map_of_environment.png "Map Obtained")

## NOTE:
The Mobile robot used for this demonstration is designed using Fusion 360 and later converted to URDF File using this Github [link](https://github.com/vishal-kasyap/cad_to_urdf_conversion)

    https://github.com/vishal-kasyap/cad_to_urdf_conversion
It is then imported into CoppeliaSim environment.
