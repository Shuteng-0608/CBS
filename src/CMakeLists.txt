cmake_minimum_required(VERSION 3.16)
INCLUDE_DIRECTORIES(/usr/include/cbs)

ADD_EXECUTABLE(main main.cpp)
TARGET_LINK_LIBRARIES(main HighLevelSolver LowLevelSolver TreeNode)


