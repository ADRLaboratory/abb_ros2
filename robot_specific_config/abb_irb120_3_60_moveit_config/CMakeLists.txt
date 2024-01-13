cmake_minimum_required(VERSION 3.22)
project(abb_irb120_3_60_moveit_config)

find_package(ament_cmake REQUIRED)

ament_package()


install(DIRECTORY config rviz DESTINATION share/${PROJECT_NAME})
install(FILES .setup_assistant DESTINATION share/${PROJECT_NAME})
