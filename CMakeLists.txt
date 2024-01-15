cmake_minimum_required(VERSION 3.5)
project(msg_pkg)

find_package(ament_cmake REQUIRED)
find_package(rosidl_default_generators REQUIRED)

rosidl_generate_interfaces(${PROJECT_NAME}
  "msg/RuneCorner.msg"
)

ament_package()
