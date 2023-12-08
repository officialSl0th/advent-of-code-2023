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
        "day 4/day4.cpp"
        "day 4/day4.h"
        "day 5/day5.cpp"
        "day 5/day5.h"
        "day 6/day6.cpp"
        "day 6/day6.h"
        "day 7/day7.cpp"
        "day 7/day7.h"
        "day 8/day8.cpp"
        "day 8/day8.h"
)
