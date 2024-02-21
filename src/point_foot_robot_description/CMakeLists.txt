cmake_minimum_required(VERSION 3.5)
project(point_foot_robot_description)

find_package(catkin REQUIRED COMPONENTS
  roscpp
)

catkin_package()

install(DIRECTORY meshes urdf launch
    DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)