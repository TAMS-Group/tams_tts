cmake_minimum_required(VERSION 3.0.2)
project(tams_tts)
find_package(catkin REQUIRED)

catkin_package()

catkin_install_python(PROGRAMS
  scripts/tts_node
  DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
)
