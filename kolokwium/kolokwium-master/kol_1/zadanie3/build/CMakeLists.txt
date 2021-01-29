cmake_minimum_required(VERSION 3.10)
project(myProgram)
file(GLOB SOURCES "../myProgram/*.cpp")
add_executable(main ${SOURCES})

