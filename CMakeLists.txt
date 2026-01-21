cmake_minimum_required(VERSION 4.2 FATAL_ERROR)

project(RxCpp)

if(PROJECT_IS_TOP_LEVEL)
option(BUILD_EXAMPLES "Build RxCpp examples" ON)
option(BUILD_TESTS "Build RxCpp tests" ON)
option(BUILD_DOXYGEN "Build RxCpp Doxygen examples" OFF)
endif(PROJECT_IS_TOP_LEVEL)

# define some folders

add_subdirectory(projects/CMake build)
