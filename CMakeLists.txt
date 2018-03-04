cmake_minimum_required(VERSION 3.9)
project(4_Optimize_Histogram_Filter_Cpp)

set(CMAKE_CXX_STANDARD 11)

add_executable(4_Optimize_Histogram_Filter_Cpp
        headers/blur.h
        headers/initialize_beliefs.h
        headers/move.h
        headers/normalize.h
        headers/print.h
        headers/sense.h
        headers/zeros.h
        blur.cpp
        initialize_beliefs.cpp
        main.cpp
        move.cpp
        normalize.cpp
        print.cpp
        sense.cpp
        zeros.cpp)
