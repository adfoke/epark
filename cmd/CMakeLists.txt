# 生成可执行文件
add_executable(epark_main main.cpp)

# 链接 hello 库
target_link_libraries(epark_main PRIVATE hello_lib)