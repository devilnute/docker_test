cmake_minimum_required(3.13 FATAL_ERROR)

set(PROJECT_NAME DOCKER_TEST)

set(CMAKE_CXX_STANDARD 17)

project(${PROJECT_NAME})

add_executable(${PROJECT_NAME} src/main.cpp)
