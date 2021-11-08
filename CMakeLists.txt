# CMakeList.txt : CMake project for Kingdom, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("Kingdom")

# Add source to this project's executable.
add_executable (Kingdom "Kingdom.cpp" "Kingdom.h")

# Compile required libraries from antuco
add_subdirectory("${CMAKE_CURRENT_SOURCE_DIR}/engine/antuco")