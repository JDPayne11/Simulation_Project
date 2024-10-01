cmake_minimum_required(VERSION 3.10)  # Minimum required version
project(MyCMakeProject)                 # Project name

set(CMAKE_CXX_STANDARD 11)              # Set C++ standard

add_executable(MyProgram src/main.cpp)  # Create an executable from source
