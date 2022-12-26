cmake_minimum_required(VERSION 3.21.0)
project(fixed_size_function)

set(CMAKE_CXX_FLAGS " ${CMAKE_CXX_FLAGS} -std=c++0x")
set(SOURCE_FILES test/tests.cpp)
add_executable(test_fixed_size_function ${SOURCE_FILES})
target_include_directories(test_fixed_size_function PUBLIC include)