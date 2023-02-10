cmake_minimum_required(VERSION 3.24)
project(naughts_and_crosses)

set(CMAKE_CXX_STANDARD 14)

add_executable(naughts_and_crosses
        nandc.cpp nandc_functions.hpp nandc_functions.cpp)
