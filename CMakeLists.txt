cmake_minimum_required(VERSION 3.7.2)
project(Wumpus_World)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Wumpus_World
        Wumpus.cpp
        environment.hpp
        environment.h
        agent.hpp
        agent.h)
