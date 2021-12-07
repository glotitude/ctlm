cmake_minimum_required(VERSION 3.19)
project(ctlm C)

set(CMAKE_C_STANDARD 99)

add_executable(ctlm main.c common.h chunk.h chunk.c memory.h memory.c)