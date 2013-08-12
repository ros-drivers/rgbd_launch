cmake_minimum_required(VERSION 2.8.3)
project(rgbd_launch)

find_package(catkin)

catkin_package()

install(DIRECTORY launch
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/
)

install(PROGRAMS scripts/hydro-upgrade-notice
  DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}/
)
