cmake_minimum_required(VERSION 3.2)

project(HELLO)

add_executable(proga main.cpp)

add_library(lib summ.h summ.cpp)

target_link_libraries(proga PUBLIC lib)