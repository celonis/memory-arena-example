cmake_minimum_required(VERSION 3.8)
project(parallel_memtest)

set(CMAKE_CXX_STANDARD 11)


set(SOURCE_FILES main.cpp)
add_executable(parallel_memtest ${SOURCE_FILES})
target_link_libraries(parallel_memtest pthread )