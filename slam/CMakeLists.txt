cmake_minimum_required(VERSION 2.6)
project(slam)

add_executable(slam main.cpp)

install(TARGETS slam RUNTIME DESTINATION bin)
