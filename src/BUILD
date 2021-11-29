load("@rules_cc//cc:defs.bzl", "cc_binary")

cc_binary(
    name = "main",
    srcs = glob(["*.cpp"]),
    deps = [
        "//third_party/glfw",
        "//third_party/glm",
        "//third_party/vulkan",
    ],
)
