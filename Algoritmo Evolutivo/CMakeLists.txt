cmake_minimum_required(VERSION 3.21)
project(Algoritmo_Evolutivo C)

set(CMAKE_C_STANDARD 99)

add_executable(Algoritmo_Evolutivo
        algoritmo.c
        algoritmo.h
        funcao.c
        funcao.h
        main.c
        utils.c
        utils.h)
