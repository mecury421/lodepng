cmake_minimum_required(VERSION 3.0 FATAL_ERROR)
project(lodepng CXX)

set (LODEPNG_SRC
    lodepng.cpp
    lodepng.h
)

add_library(lodepng ${LODEPNG_SRC})
target_include_directories(lodepng PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
