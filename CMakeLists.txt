cmake_minimum_required(VERSION 3.13)
project(gmock-global CXX)

add_library(gmock-global INTERFACE)
target_include_directories(gmock-global INTERFACE $<BUILD_INTERFACE:${PROJECT_SOURCE_DIR}/include>)
