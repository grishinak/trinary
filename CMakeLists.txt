cmake_minimum_required(VERSION 3.8)

project(MyProjectTrinary)

set(CMAKE_CXX_STANDARD 11) 

FILE(GLOB_RECURSE headers "src/*.h")
FILE(GLOB_RECURSE sources "src/*.cpp")

add_executable(Proj ${sources} ${headers})