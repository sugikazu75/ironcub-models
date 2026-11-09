cmake_minimum_required(VERSION 3.0.2)
project(iRonCub-Mk3)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY iRonCub launch rviz
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
