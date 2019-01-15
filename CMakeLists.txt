cmake_minimum_required(VERSION 3.13)
project(neatPathFinder)
#set(EXECUTABLE_OUTPUT_PATH neatPathFinder/)

#The includes
include_directories(include/)

file(GLOB SOURCES src/*.cpp)

#remove from glob
#list(REMOVE_ITEM SOURCES nnxor/badcode.cpp)

add_executable(neatPathFinder ${SOURCES})