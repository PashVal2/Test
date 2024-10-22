cmake_minimum_required(VERSION 3.30 FATAL_ERROR)

project (Test) 

add_executable(myExe src/main.cpp)
add_library(myLib STATIC src/lib.cpp) 
