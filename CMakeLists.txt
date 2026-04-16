cmake_minimum_required(VERSION 3.10)

# Project Name and Version
project(Dain-DR VERSION 1.0)

# Set C++ Standard
set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add executable targets for all 11 cells
add_executable(cell1 src/cell1.cpp)
add_executable(cell2 src/cell2.cpp)
add_executable(cell3 src/cell3.cpp)
add_executable(cell4 src/cell4.cpp)
add_executable(cell5 src/cell5.cpp)
add_executable(cell6 src/cell6.cpp)
add_executable(cell7 src/cell7.cpp)
add_executable(cell8 src/cell8.cpp)
add_executable(cell9 src/cell9.cpp)
add_executable(cell10 src/cell10.cpp)
add_executable(cell11 src/cell11.cpp)

# Include directories
include_directories(include)

# Optional: Add other compilation flags or libraries here
