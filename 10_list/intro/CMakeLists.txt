cmake_minimum_required(VERSION 3.16 FATAL_ERROR)
project(test LANGUAGES CXX)
set(CMAKE_CXX_STANDARD 20)

include(doctest.cmake)
add_executable(test test_list.cpp)
target_link_libraries(test PRIVATE doctest)
