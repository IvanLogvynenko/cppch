cmake_minimum_required(VERSION 3.20)

set(TARGET_NAME "main") # If you change this, be sure to change the target in the dockerfile as well
project(${TARGET_NAME})

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(${TARGET_NAME} main.cpp)