message("   构建: 天宇测试框架源代码 - 核心测试组件")

add_library(dty-test-core STATIC

    ${PROJECT_SOURCE_DIR}/dtest-core/dty-core.cpp
    ${PROJECT_SOURCE_DIR}/dtest-core/dty-test-core.cpp
)

message("   构建-完成")