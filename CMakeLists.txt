cmake_minimum_required(VERSION 3.16)
project(DemoProject)

include_directories(include/)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_executable(main src/main.cc)
