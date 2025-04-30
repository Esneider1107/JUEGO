cmake_minimum_required(VERSION 3.30)
project(JUEGO)

set(CMAKE_CXX_STANDARD 20)

add_executable(JUEGO main.cpp
        hormigas.cpp
        hormigas.h
        reyhongo.cpp
        reyhongo.h
        personaje.cpp
        personaje.h
        ray.cpp
        ray.h
        borrador.cpp
        juego.cpp
        juego.h
        puntaje.h)
