cmake_minimum_required(VERSION 3.5)
project(dlisio LANGUAGES CXX)

find_package(fmt)

add_executable(mwe mwe.cpp)
target_link_libraries(mwe PRIVATE fmt::fmt-header-only)
