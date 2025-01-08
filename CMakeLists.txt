cmake_minimum_required(VERSION 3.5.0)

project(Prismia VERSION 0.1.0 LANGUAGES C CXX)

# Automatically include any new .cpp files added to the src folder
file(GLOB_RECURSE SOURCES src/*.cpp)

add_executable(Prismia ${SOURCES})


