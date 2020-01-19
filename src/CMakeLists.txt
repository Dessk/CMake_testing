cmake_minimum_required(VERSION 3.8)


add_executable(myProgram main.cpp)
target_link_libraries(myProgram PUBLIC myLib)