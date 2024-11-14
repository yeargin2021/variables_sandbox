cmake_minimum_required(VERSION 3.28)
project(variables_sandbox)

set(CMAKE_CXX_STANDARD 17)

add_executable(variables_sandbox main.cpp
        my_variables.h
        my_functions.h)
