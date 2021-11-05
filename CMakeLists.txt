cmake_minimum_required(VERSION 3.17)
project(dhredis)

set(CMAKE_CXX_STANDARD 20)

add_executable(dhredis-client src/client/main.cpp)
add_executable(dhredis-server src/server/main.cpp)