# ecse373_f22_jxx439_navvis_description
 
including a robot model,name: navvis

lab2.xacro, lab2.urdf, urdf_from_xacro.urdf, lab2.launch, config.rviz

gazebo_plugins package from (sudo apt-get install ros-noetic-gazebo-plugins) 

velodyne_description package from (sudo apt-get install ros-noetic-velodyne-description)

## joint_state_publisher_gui  :  
### by using the URDF 
                   roslaunch navvis_description lab2.launch
### by using the XACRO 
                   roslaunch navvis_description lab2.launch use_xacro:=true

## joint_state_publisher (without GUI)  :  
### by using the URDF 
                   roslaunch navvis_description lab2.launch use_gui:=false
### by using the XACRO 
                   roslaunch navvis_description lab2.launch use_xacro:=true use_gui:=false
