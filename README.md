# Vulkan Learning Project

A simple Vulkan application using GLFW and GLM.

## Prerequisites

All dependencies have been installed via Homebrew:
- GLFW (windowing)
- GLM (mathematics library)
- Vulkan headers
- MoltenVK (Vulkan for macOS)

## Building

```bash
mkdir build
cd build
cmake ..
make
```

## Running

```bash
./build/VulkanLearning
```

## VS Code Setup

The `.vscode/c_cpp_properties.json` file has been configured with the correct include paths. 

**Important:** Reload VS Code window to apply the C++ configuration:
- Press `Cmd+Shift+P`
- Type "Reload Window" and select it

This will fix the include path errors.
# vulkan-learning
