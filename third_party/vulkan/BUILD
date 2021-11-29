load("@rules_cc//cc:defs.bzl", "cc_library")

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "vulkan",
    srcs = [
        "libvulkan.1.2.198.dylib",
        "libvulkan.1.dylib",
    ],
    deps = ["@vulkan_headers"],
)
