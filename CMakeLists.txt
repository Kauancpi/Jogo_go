cmake_minimum_required(VERSION 3.0...3.25)
project(
    Jogo GO # name of the project, which will also be the name of the visual studio solution if you use it
    VERSION 0.1.0 # any version number
    LANGUAGES C++ C # programming languages used by the project
)

add_executable(App main.cpp)