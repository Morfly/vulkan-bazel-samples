load("@rules_cc//cc:defs.bzl", "cc_library")

DARWIN_SRCS = [
    "libvulkan.1.2.198.dylib",
    "libvulkan.1.dylib",
]

WIN32_SRCS = [
    "vulkan-1.dll"
]

cc_library(
    name = "vulkan",
    srcs = select({
        "@bazel_tools//src/conditions:darwin": DARWIN_SRCS,
        "@bazel_tools//src/conditions:windows": WIN32_SRCS,
        # "@bazel_tools//src/conditions:linux_x86_64"
        "//conditions:default": [],
    }),
    visibility = ["//visibility:public"],
    deps = ["@vulkan_headers"],
)
