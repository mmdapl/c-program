cmake_minimum_required(VERSION 3.21)
project(c_program)

set(CMAKE_CXX_STANDARD 14)

include_directories(algorithm)
include_directories(base-learn)

add_executable(c_program
        algorithm/test.c)
