cmake_minimum_required(VERSION 3.17)

project(upkggen)

set(CMAKE_CXX_STANDARD 20)

file(GLOB_RECURSE SRC "Generator/*.hpp" "Generator/*.cpp")

add_executable(upkggen ${SRC} main.cpp)

set_target_properties(upkggen PROPERTIES LINKER_LANGUAGE CXX)
target_link_libraries(upkggen )