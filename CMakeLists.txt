cmake_minimum_required(VERSION 3.27)
project(advent_of_code_2023)

set(CMAKE_CXX_STANDARD 20)

add_executable(advent_of_code_2023 main.cpp
        "day 1/day1.cpp"
        "day 1/day1.h"
        includes.h
        "day 2/day2.cpp"
        "day 2/day2.h"
        "day 3/day3.cpp"
        "day 3/day3.h"
)
