cmake_minimum_required(VERSION 3.22)

include_directories(./include)

project (Cpp_associate VERSION 1.0)

set (CMAKE_CXX_COMPILER /usr/bin/clang++)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_executable(cpp_associate ./src/helloworld.cpp)