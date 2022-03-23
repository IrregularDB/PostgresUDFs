cmake_minimum_required(VERSION 3.21)
project(Postgresqludf C)

set(CMAKE_C_STANDARD 99)

add_library(Postgresqludf SHARED library.c)

include_directories(/usr/include/postgresql/12/server)