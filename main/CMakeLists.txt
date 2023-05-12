# Set minimum required CMake version
cmake_minimum_required(VERSION 3.2)

# Define the my_exe executable and specify source files
add_executable(my_exe src/main.cpp)

# Include directories for header files
target_include_directories(my_exe PRIVATE ${CMAKE_CURRENT_SOURCE_DIR}/include)

# Link my_lib library to my_exe executable
target_link_libraries(my_exe PRIVATE my_lib)

# Set C++ standard
set_target_properties(my_exe PROPERTIES CXX_STANDARD 11 CXX_STANDARD_REQUIRED ON)