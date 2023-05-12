cmake_minimum_required(VERSION 3.2)

add_executable(my_exe src/main.cpp)
target_link_libraries(my_exe my_lib)
target_include_directories(my_exe PRIVATE include)
