cmake_minimum_required(VERSION 3.24)
project(Project)

set(CMAKE_CXX_STANDARD 17)

add_executable(Project main.cpp Admin.cpp Customer.cpp User.cpp Library.cpp Book.cpp)
