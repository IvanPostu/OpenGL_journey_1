cmake_minimum_required(VERSION 3.2)

set(CMAKE_CXX_STANDARD_LIBRARIES "-lstdc++")
set(CMAKE_C_COMPILER "/usr/bin/gcc-11")
set(CMAKE_CXX_COMPILER "/usr/bin/g++-11")
set(CMAKE_CXX_STANDARD 17)

add_library(my_lib SHARED src/my_lib.cpp)
target_include_directories(my_lib PUBLIC include)
