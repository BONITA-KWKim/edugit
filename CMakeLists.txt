cmake_minimum_required (VERSION 3.5.1)
project (edugit)

add_definitions (-std=c++11)

# build entire server
add_subdirectory (${CMAKE_CURRENT_SOURCE_DIR}/src)