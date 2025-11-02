cmake_minimum_required(VERSION 3.10)
project(VulkanLearning)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Find packages
find_package(glfw3 3.3 REQUIRED)
find_package(Vulkan REQUIRED)

# Add executable
add_executable(VulkanLearning main.cc)

# Link libraries
target_link_libraries(VulkanLearning 
    glfw
    Vulkan::Vulkan
)

# Include directories
target_include_directories(VulkanLearning PRIVATE
    /opt/homebrew/include
)
