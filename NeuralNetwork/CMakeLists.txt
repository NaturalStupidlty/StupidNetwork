cmake_minimum_required(VERSION 3.20)
project(NeuralNetwork)

set(CMAKE_CXX_STANDARD 14)

add_executable(NeuralNetwork main.cpp NeuralNetwork.cpp NeuralNetwork.h Files.cpp Files.h)
