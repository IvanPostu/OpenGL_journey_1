cmake_minimum_required(VERSION 3.2)

add_library(my_lib SHARED src/my_lib.cpp)
target_include_directories(my_lib PUBLIC include)
