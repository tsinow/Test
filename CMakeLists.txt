cmake_minimum_required(VERSION 3.16)
project(1000)

set(CMAKE_CXX_STANDARD 14)

include_directories(1000jiechen)
include_directories(1000jiechen/Debug)

add_executable(1000
        1000jiechen/Debug/jiechen.pch
        1000jiechen/jiechen.cpp
        1000jiechen/StdAfx.cpp
        1000jiechen/StdAfx.h)
