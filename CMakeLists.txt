cmake_minimum_required(VERSION 3.26)
project(SQL_DBMS C)

set(CMAKE_C_STANDARD 11)

add_executable(SQL_DBMS main.c
        models.c)
