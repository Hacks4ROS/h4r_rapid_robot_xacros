cmake_minimum_required(VERSION 2.8.3)
project(h4r_rapid_robot_xacros)
find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY 
   launch def
   DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
 )
