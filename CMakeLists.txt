cmake_minimum_required(VERSION 3.16)
project(ca_hw4)

set(CMAKE_CXX_STANDARD 11)

add_executable(ca_hw4 main.c core_api.h core_api.cpp sim_api.h sim_api.c)