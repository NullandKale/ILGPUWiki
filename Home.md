# This is a transitional period.

We are currently in the process of creating new documentation. This should be an awesome update that will hopefully 
be beginner friendly while still short enough that GPGPU experts will not get bored.

During this transitional period all old documentation will be available still. You can find it [here](Old-Home.md).

The following is the table of contents for the new tutorial:

# ILGPUView Tutorials

## Primers (How a GPU works)

This series introduces how a GPU works. If you have programmed with CUDA or OpenCL before you can probably skip this.

01 [A GPU is not a CPU](Primer_01.md)
> This page will provide a quick rundown the basics of how kernels (think GPU programs) run.

02 [Memory and bandwidth and threads. Oh my!](Primer_02.md) 
> This will hopefully give you a better understanding of how memory works in hardware and the performance
> implications.

## Beginner (How ILGPU works)

This series is meant to be a brief overview of ILGPU and how to use it. It assumes you have at least a little knowledge of how Cuda or OpenCL work. 
If you need a primer look to something like [this for Cuda](https://developer.nvidia.com/about-cuda) or [this for OpenCL](https://www.khronos.org/opencl/)

01 [Context and Accelerators](Tutorial_01.md) (0.10.1)
> This tutorial covers the creating the Context and Accelerator objects which setup ILGPU for use. 
> It's mostly boiler plate and does no computation but it does print info about your GPU if you have one.
> There is some advice about ILGPU in here that makes it worth the quick read.

02 [MemoryBuffers and ArrayViews](Tutorial_02.md) (0.10.1)
> This tutorial covers the basics for Host / Device memory management.

03 [Kernels and Simple Programs](Tutorial_03.md) (0.10.1)
> This is where it all comes together. This covers actual code, on the actual GPU (or the CPU if you are testing / dont have a GPU). 

04 Structs

05 Algorithms 1 Math

## Beginner II (Something more interesting)

Well at least I think. This is where I will put ILGPUView bitmap shader things I (or other people if they want to) eventually write. Below are the few I have planned / think would be easy.

1. Ray Tracing in One Weekend based raytracer
2. Cloud Simulation
2. 2D Physics Simulation
3. Other things I see on shadertoy