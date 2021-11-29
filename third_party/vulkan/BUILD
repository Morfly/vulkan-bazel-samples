load("@rules_cc//cc:defs.bzl", "cc_library")

DARWIN_SRCS = [
    "libvulkan.1.2.198.dylib",
    "libvulkan.1.dylib",
]

cc_library(
    name = "vulkan",
    srcs = select({
        "@bazel_tools//src/conditions:darwin": DARWIN_SRCS,
        "//conditions:default": [],
    }),
    visibility = ["//visibility:public"],
    deps = ["@vulkan_headers"],
)
