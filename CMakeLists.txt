cmake_minimum_required(VERSION 3.25)
set(CMAKE_C_COMPILER /usr/bin/clang)
set(CMAKE_C_STANDARD 17)
set(CMAKE_C_STANDARD_REQUIRED True)

set(TARGET dsinc)

project(${TARGET} VERSION 1.0)
add_executable(${TARGET} main.c)

