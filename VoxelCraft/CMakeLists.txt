cmake_minimum_required(VERSION 3.8)

add_executable(VoxelCraft "main.C" "main.h")

target_link_libraries(
    "VoxelCraft"
    "glfw"
    "glad"
)
