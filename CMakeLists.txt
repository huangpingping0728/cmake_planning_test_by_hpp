cmake_minimum_required(VERSION 3.20.0)
project(planning_hpp)
set(CMAKE_CXX_STANDARD 17)


set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)
aux_source_directory(. SRC_LIST)
add_executable(planning_main ${SRC_LIST})