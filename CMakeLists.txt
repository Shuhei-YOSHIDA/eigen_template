cmake_minimum_required(VERSION 3.1)
project(main)
set(CMAKE_CXX_STANDARD, 11)

find_package(Eigen3 REQUIRED)

include_directories(${EIGEN3_INCLUDE_DIR})
add_executable(main main.cpp)

