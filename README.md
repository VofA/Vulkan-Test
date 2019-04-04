Vulkan-Test

VulkanSDk
https://vulkan.lunarg.com/

brew install glfw3 --HEAD
brew install glm

touch ~/.profile

export VULKAN_SDK=/Users/danil/Documents/SDK/vulkansdk-macos-1.1.101.0/macOS/

export VK_ICD_FILENAMES=$VULKAN_SDK/etc/vulkan/icd.d/MoltenVK_icd.json
export VK_LAYER_PATH=$VULKAN_SDK/etc/vulkan/explicit_layer.d