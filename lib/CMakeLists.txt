add_library(myLib src/testing.cpp src/testing.h)

message(STATUS "${CMAKE_CURRENT_SOURCE_DIR}")

target_link_directories(myLib PUBLIC "${CMAKE_CURRENT_SOURCE_DIR}")