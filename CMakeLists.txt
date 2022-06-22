# CMakeList.txt : CMake project for X8080, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("X8080")

# Add source to this project's executable.
add_executable (X8080 "X8080.cpp" "X8080.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET X8080 PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
