cmake_minimum_required(VERSION 3.5)

project(otus-cpp-basics_lesson_02)

add_executable(otus-cpp-basics_lesson_02
        hello_world.cpp
        example.cpp
        example.h
        todo_move_me_out.cpp
        todo_move_me_out.h)

set_target_properties(otus-cpp-basics_lesson_02 PROPERTIES
    CXX_STANDARD 17
    CXX_STANDARD_REQUIRED ON
)