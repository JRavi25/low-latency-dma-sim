cmake_minimum_required(VERSION 3.20)
project(main)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_POSITION_INDEPENDENT_CODE)

#Debug flags
set(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -g -O0")
set(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -g -O0")

# Testing
#enable_testing() 
#include_directories(${CMAKE_SOURCE_DIR}/googletest/include)
#include_directories(${CMAKE_SOURCE_DIR}/googlemock/include)
#link_directories(${CMAKE_SOURCE_DIR}/build)

add_executable(${PROJECT_NAME} main.cpp)
