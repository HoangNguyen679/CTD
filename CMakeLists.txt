cmake_minimum_required(VERSION 3.6)
project(Scanner)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        charcode.c
        charcode.h
        error.c
        error.h
        reader.c
        reader.h
        scanner.c
        token.c
        token.h)

add_executable(Scanner ${SOURCE_FILES})