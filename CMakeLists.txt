cmake_minimum_required(VERSION 3.16)
project(arboria)

set(CMAKE_CXX_STANDARD 14)

add_executable(arboria cmake-build-debug/src/main.cpp cmake-build-debug/src/world/chunk/chunk.cpp cmake-build-debug/src/world/chunk/chunk.h)