cmake_minimum_required(VERSION 3.5)
project(Project3)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp CommandProcessor.cpp Menu.cpp TreeNode.h GeneralTree.h AVLTree.h tinyxml.cpp tinyxmlparser.cpp tinyxmlerror.cpp Heap.h)
add_executable(Project3 ${SOURCE_FILES})