cmake_minimum_required(VERSION 3.27)
project(otus_cpp_basic_hw2)

set(CMAKE_CXX_STANDARD 20)

add_executable(otus_cpp_basic_hw2
        hello_world.cpp
        example.cpp example.h
        move_me_out.cpp move_me_out.h
)
