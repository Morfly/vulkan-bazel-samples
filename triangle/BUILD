load("@rules_cc//cc:defs.bzl", "cc_binary")

cc_binary(
    name = "triangle",
    srcs = glob(["*.cpp"]),
    data = [
        "//triangle/shaders:vert_shader",
        "//triangle/shaders:frag_shader",
    ],
    deps = [
        "//third_party/glfw",
        "//third_party/glm",
        "@rules_vulkan//vulkan:vulkan_cc_library"
    ],
)
