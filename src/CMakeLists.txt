cmake_minimum_required(VERSION 3.8)

include_directories("lib")

add_executable(myProgram test.cpp)
target_link_libraries(myProgram myLib)