cmake_minimum_required(VERSION 3.14)

project(c-as-cpp)

add_executable(test main.c)

set_source_files_properties(main.c PROPERTIES LANGUAGE CXX)
