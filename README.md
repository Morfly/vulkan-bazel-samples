# Vulkan Bazel Samples

This is a sample repository that shows the basics of environment setup for applications that use Vulkan graphics API and built with Bazel build system.

## Vulkan SDK
It is required to have a Vulkan SDK installed on the machine. Instructions could be found [here](https://vulkan-tutorial.com/Development_environment#page_Vulkan-SDK-2) (only *Vulkan SDK* paragraph for each platform is required).

## Projects
### Environment setup
A simple project that demonstrates a bare minumum for configuring Vulkan projects with Bazel.

In order to run this project use the command below.

```shell
$ bazel run //env_setup
```

It should launch an empty window named `Vulkan window`.

### Drawing a triangle
A project that draws a triangle using Vulkan.
In order to run this project use the command below.

```shell
$ bazel run //triangle
```
