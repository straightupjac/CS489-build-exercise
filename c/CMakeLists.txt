cmake_minimum_required(VERSION 2.6)

project(Jobs)

include_directories(include)

add_executable(program input.c job.c main.c include/config.h include/input.h include/job.h)
