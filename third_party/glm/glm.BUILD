load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(
    name = "glm",
    hdrs = glob([
        "glm/**/*.hpp",
        "glm/**/*.h",
    ]),
    includes = ["."],
    textual_hdrs = glob(["glm/**/*.inl"]),
    visibility = ["//visibility:public"],
)
