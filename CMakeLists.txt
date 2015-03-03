cmake_minimum_required(VERSION 2.8.4)
project(diversity_toolkit)

include_directories("${Project_SOURCE_DIR}")

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES examples/planes.cpp)
add_executable(planes ${SOURCE_FILES})
