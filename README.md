# Vulkan Bazel setup sample

This is a sample repository that shows how to set up an environment for developing Vulkan applications built with Bazel build system.

## Vulkan SDK
It is required to have a Vulkan SDK installed on the machine. Instructions could be found [here](https://vulkan-tutorial.com/Development_environment#page_Vulkan-SDK-2) (only *Vulkan SDK* paragraph for each platform is required).

## How to run

In order to run this project use the command below.

```shell
$ bazel run //src:main
```

It should launch an empty window named `Vulkan window`.
