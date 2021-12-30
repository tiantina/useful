cmake_minimum_required(VERSION 3.14)
project(show)

set(CMAKE_CXX_STANDARD 17)

add_library(${PROJECT_NAME} INTERFACE)

target_include_directories(show INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})
