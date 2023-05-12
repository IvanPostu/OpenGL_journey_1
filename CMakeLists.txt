cmake_minimum_required(VERSION 3.2)



project(my_project)

set(CMAKE_CXX_COMPILER "/usr/bin/g++")

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/lib)
set(CMAKE_ARCHIVE_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/lib)

# Add subdirectories for my_lib and main
add_subdirectory(my_lib)
add_subdirectory(main)