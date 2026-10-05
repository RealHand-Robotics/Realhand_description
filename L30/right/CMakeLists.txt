cmake_minimum_required(VERSION 3.0.2)
project(realhand_l30_right)

find_package(catkin REQUIRED)
catkin_package()

install(DIRECTORY config launch meshes urdf
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
install(FILES realhand_l30_right.urdf
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})