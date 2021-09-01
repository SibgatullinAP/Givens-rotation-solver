cmake_minimum_required(VERSION 3.5)

project(QR_solver LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set (CMAKE_CXX_FLAGS "-O3 -lm -mfpmath=sse -fsignaling-nans")


add_executable(QR_solver main.cpp solver.cpp)