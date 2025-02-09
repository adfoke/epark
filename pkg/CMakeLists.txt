# 生成库
add_library(hello_lib hello.cpp)

# 头文件目录
target_include_directories(hello_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})