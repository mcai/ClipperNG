cmake_minimum_required(VERSION 3.17)
project(ClipperNG)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(ClipperNG
        clipper.cpp
        clipper.hpp
        clipper_console_demo.cpp)
