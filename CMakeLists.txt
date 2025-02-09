cmake_minimum_required(VERSION 3.10)
project(epark)

# 设置 C++ 标准
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# 包含子目录
add_subdirectory(cmd)
add_subdirectory(pkg)