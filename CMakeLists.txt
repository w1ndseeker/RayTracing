cmake_minimum_required(VERSION 3.10)

project(raytracing)

set(CMAKE_BUILD_TYPE Release)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_FLAGS "-O3")

add_subdirectory(Walnut)
add_subdirectory(RayTracing)