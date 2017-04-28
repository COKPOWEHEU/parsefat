cmake_minimum_required(VERSION 3.5)
project(parsefat)

set(CMAKE_C_STANDARD 99)
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall -Wextra -Wshadow -Wpointer-arith -Wcast-align -Wconversion -pedantic")
set(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -O0")

set(SOURCE_FILES main.c)
add_executable(parsefat ${SOURCE_FILES})