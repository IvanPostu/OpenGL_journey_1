cmake_minimum_required(VERSION 3.2)

set(CMAKE_CXX_STANDARD_LIBRARIES "-lstdc++")
set(CMAKE_C_COMPILER "/usr/bin/gcc-11")
set(CMAKE_CXX_COMPILER "/usr/bin/g++-11")
set(CMAKE_CXX_STANDARD 17)

add_executable(my_exe src/main.cpp)
target_link_libraries(my_exe my_lib)
target_include_directories(my_exe PRIVATE include)
