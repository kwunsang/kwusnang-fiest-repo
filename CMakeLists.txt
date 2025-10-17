cmake_minimum_required(VERSION 3.0)

project(251016_test)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g -Wall")

include_directories(./)

# file(GLOB_RECURSE SOURCES "utility/*.cpp")

add_executable(main main.cpp)