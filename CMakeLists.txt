cmake_minimum_required(VERSION 3.16)
project(LABO5 C)

set(CMAKE_C_STANDARD 11)

add_executable(LABO5 main.c Bateau.h Bateau.c Port.c Port.h)
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall -Wconversion -Wextra -Wsign-conversion -pedantic")