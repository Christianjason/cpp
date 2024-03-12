cmake_minimum_required(VERSION 3.24)
project(cpp_git)

set(CMAKE_CXX_STANDARD 14)

include_directories(base/0312)

add_executable(cpp_git
        base/0312/main.cpp
        base/0312/main.h)
