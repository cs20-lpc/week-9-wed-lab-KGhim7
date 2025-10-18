cmake_minimum_required(VERSION 3.16)
project(week_9_wed_lab_KGhim7)
set(CMAKE_CXX_STANDARD 14)

include_directories(${CMAKE_CURRENT_SOURCE_DIR})

add_executable(week_9_wed_lab_KGhim7
        main.cpp
        ArrayQueue.hpp
        ArrayQueue.tpp
        Queue.hpp
)