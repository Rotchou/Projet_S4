cmake_minimum_required(VERSION 3.6)
project(ProjetS4)

set(CMAKE_CXX_STANDARD 14)

set(SOURCE_FILES src/main.cpp src/test.cpp src/test.h src/Connexion.cpp src/Connexion.h)
add_executable(ProjetS4 ${SOURCE_FILES})