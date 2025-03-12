cmake_minimum_required(VERSION 3.24)
project(CS210PA2)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(CS210PA2
        GameDecisionTree.h
        main.cpp
        Node.h
        Story.h
        story.txt)
