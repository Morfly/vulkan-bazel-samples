load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

# ===== glfw =====

GLFW_VERSION = "3.3.5"

http_archive(
    name = "glfw",
    build_file = "@//third_party/glfw:glfw.BUILD",
    strip_prefix = "glfw-{}".format(GLFW_VERSION),
    urls = ["https://github.com/glfw/glfw/archive/{}.zip".format(GLFW_VERSION)],
)

# ===== glm =====

GLM_VERSION = "0.9.9.8"

http_archive(
    name = "glm",
    build_file = "@//third_party/glm:glm.BUILD",
    strip_prefix = "glm-{}".format(GLM_VERSION),
    urls = ["https://github.com/g-truc/glm/archive/{}.zip".format(GLM_VERSION)],
)

# ===== vulkan =====

VULKAN_VERSION = "1.2.198"

http_archive(
    name = "vulkan_headers",
    build_file = "@//third_party/vulkan:vulkan_headers.BUILD",
    strip_prefix = "Vulkan-Headers-{}".format(VULKAN_VERSION),
    urls = ["https://github.com/KhronosGroup/Vulkan-Headers/archive/v{}.zip".format(VULKAN_VERSION)],
)
