# Set minimum required CMake version
cmake_minimum_required(VERSION 3.2)

# Define the my_lib library and specify source files
add_library(my_lib SHARED src/my_lib.cpp)

# Include directories for header files
target_include_directories(my_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)

# Set C++ standard
set_target_properties(my_lib PROPERTIES CXX_STANDARD 11 CXX_STANDARD_REQUIRED ON)
