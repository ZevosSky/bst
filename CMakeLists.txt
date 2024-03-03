cmake_minimum_required(VERSION 3.22)
project(bst)

set(CMAKE_CXX_STANDARD 17)

add_executable(bst driver.cpp 
              bst-map.h
              bst-map.cpp)
