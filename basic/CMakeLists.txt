cmake_minimum_required(VERSION 3.22)
project(Threading)

set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)

#
add_executable(basic_threading basic_threading.cpp)
add_executable(compute_sum compute_sum.cpp)
