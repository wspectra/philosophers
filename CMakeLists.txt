cmake_minimum_required(VERSION 3.19)
project(04_philosophers C)

set(CMAKE_C_STANDARD 99)

add_executable(04_philosophers
        src/main.c
        src/utils.c
        src/parsing.c
        src/init.c
        src/print.c)