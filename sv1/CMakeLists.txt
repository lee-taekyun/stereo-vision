cmake_minimum_required(VERSION 2.8)
project(calib)
find_package(OpenCV REQUIRED)
include_directories(${OpenCV_INCLUDE_DIRS})
add_executable(calib calib.cpp)
target_link_libraries(calib ${OpenCV_LIBS})
