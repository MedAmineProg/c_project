cmake_minimum_required(VERSION 3.10)
project(HelloJenkins)

set(CMAKE_CXX_STANDARD 11)

add_executable(hello main.cpp)

enable_testing()
add_test(NAME MyTest COMMAND hello)
