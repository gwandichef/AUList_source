cmake_minimum_required(VERSION 4.0)
project(AUList_source)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(AUList_source
        AUList.cpp
        AUList.h
        main.cpp)
