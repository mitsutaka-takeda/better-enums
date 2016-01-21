cmake_minimum_required(VERSION 3.1.0 FATAL_ERROR)

project("Better Enums" CXX)

# Better Enums is a header-only library
add_library(better_enums INTERFACE)
target_include_directories(
  better_enums INTERFACE
  ${CMAKE_CURRENT_SOURCE_DIR}
  )
