cmake_minimum_required(VERSION 3.8)

project("VoxelCraft")

add_subdirectory("glfw")
add_subdirectory("glad")
add_subdirectory("VoxelCraft")

target_include_directories("VoxelCraft" PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/glfw/include)

