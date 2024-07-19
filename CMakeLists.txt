cmake_minimum_required(VERSION 3.20 FATAL_ERROR)

set(PROJECT_NAME DOCKER_TEST)

project(${PROJECT_NAME})

add_executable(${PROJECT_NAME} src/main.cpp)
