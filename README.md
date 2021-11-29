# Vulkan Bazel setup sample

This is a sample repository that shows how to set up an environment for developing Vulkan applications built with Bazel build system.

## How to run
To build this project it is recommended to use Bazelisk, a wrapper CLI around Bazel. You can learn how to install it on your machine [here](https://github.com/bazelbuild/bazelisk#installation).

In order to run this project use the command below.

```shell
$ bazelisk run //src:main
```

It should launch an empty window named `Vulkan window`.