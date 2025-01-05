cmake_minimum_required(VERSION 3.27)
project(Matrix)

set(CMAKE_CXX_STANDARD 14)

include_directories(Matrix)

add_executable(Matrix
        Matrix/App.cpp
        Matrix/ExtendedTest.cpp
        Matrix/ExtendedTest.h
        Matrix/Matrix.cpp
        Matrix/Matrix.h
        Matrix/ShortTest.cpp
        Matrix/ShortTest.h)
