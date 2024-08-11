# Minimum CMake version we use
cmake_minimum_required(VERSION 3.10)

# Projects name
project(tcp_protocol VERSION 0.1.0 LANGUAGES C CXX)

# C++ standard setting
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Adding directory with header files
# include_directories(data_structures/inc)

# Setting source files
# set(SOURCES
#     main.cc
#     data_structures/src/linked_list.cc
# )

# Creating executable file
add_executable(tcp_protocol main.cpp)

include(CTest)
enable_testing()