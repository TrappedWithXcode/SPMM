cmake_minimum_required(VERSION 3.23)
project(projectSrc)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(projectSrc
        Main.cpp
        wkImg.cpp
        wkImg.h)
