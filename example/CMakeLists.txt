cmake_minimum_required(VERSION 3.10)

project(example)

add_executable(example example.cpp)

target_include_directories(example PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../include)
