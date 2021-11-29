load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

# ===== glfw =====

GLFW_VERSION = "3.3.5"

http_archive(
    name = "glfw",
    build_file = "@//third_party/glfw:glfw.BUILD",
    sha256 = "a89bb6074bc12bc12fcd322dcf848af81b679ccdc695f70b29ca8a9aa066684b",
    strip_prefix = "glfw-{}".format(GLFW_VERSION),
    urls = ["https://github.com/glfw/glfw/archive/{}.zip".format(GLFW_VERSION)],
)

# ===== glm =====

GLM_VERSION = "0.9.9.8"

http_archive(
    name = "glm",
    build_file = "@//third_party/glm:glm.BUILD",
    sha256 = "4605259c22feadf35388c027f07b345ad3aa3b12631a5a316347f7566c6f1839",
    strip_prefix = "glm-{}".format(GLM_VERSION),
    urls = ["https://github.com/g-truc/glm/archive/{}.zip".format(GLM_VERSION)],
)

# ===== vulkan =====

VULKAN_VERSION = "1.2.198"

http_archive(
    name = "vulkan_headers",
    build_file = "@//third_party/vulkan:vulkan_headers.BUILD",
    sha256 = "0d0c54a6f96a0a1decdbb7270baf003a71b48c68b3516fed55882d9401e626c2",
    strip_prefix = "Vulkan-Headers-{}".format(VULKAN_VERSION),
    urls = ["https://github.com/KhronosGroup/Vulkan-Headers/archive/v{}.zip".format(VULKAN_VERSION)],
)
