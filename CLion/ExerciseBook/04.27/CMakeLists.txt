# 包含公共库
include_directories(${CMAKE_SOURCE_DIR}/Status)

# 生成可执行文件
add_executable(04.27 SString.h SString.c 04.27.c)
# 链接公共库
target_link_libraries(04.27 Scanf_lib)