cmake_minimum_required(VERSION 3.9)
project(cmilan)

set(CMAKE_CXX_STANDARD 14)

add_executable( cmilan
        src/codegen.cpp
        src/codegen.h
        src/main.cpp
        src/parser.cpp
        src/parser.h
        src/scanner.cpp
        src/scanner.h)

# 1 3 4