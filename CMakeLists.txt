cmake_minimum_required(VERSION 3.5)
project(ur5_robotiq2f140_gripper_description)

find_package(ament_cmake REQUIRED)

install(
  DIRECTORY config launch rviz urdf 
  DESTINATION share/${PROJECT_NAME}
)

ament_export_dependencies(${THIS_PACKAGE_INCLUDE_DEPENDS})

ament_package()
