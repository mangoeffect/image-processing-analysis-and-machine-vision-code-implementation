cmake_minimum_required(VERSION 3.14)

project(image-processing-analysis-and-machine-vision-code-implementation)

find_package(OpenCV REQUIRED)
include_directories(${OpenCV_INCLUDE_DIRS})

add_subdirectory(distance-transform)