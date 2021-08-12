# An Even Easier Introduction to CUDA - Accompanying Notebook

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NVDLI/notebooks/blob/even-easier-cuda/even-easier-cuda/An_Even_Easier_Introduction_to_CUDA.ipynb)

This notebook accompanies Mark Harris's popular blog post [_An Even Easier Introductrion to CUDA_](https://developer.nvidia.com/blog/even-easier-introduction-cuda/) and can be run directly in [Google Colaboratory](https://colab.research.google.com/github/NVDLI/notebooks/blob/even-easier-cuda/even-easier-cuda/An_Even_Easier_Introduction_to_CUDA.ipynb).

## Learning Objectives

In this notebook you will learn the basics of writing massively parallel CUDA kernels to run on NVIDIA GPUs. By the time you complete it you will be able to:

- Launch massively parallel CUDA Kernels on an NVIDIA GPU
- Organize parallel thread execution for massive dataset sizes
- Manage memory between the CPU and GPU
- Profile your CUDA code to observe performance gains

## Prerequisites

This notebook does not require you to write novel code, but to best understand its details, you should already have familiarity with:

- Writing, compiling and running C or C++ code

## Followup Materials

If you enjoyed this notebook and want to learn more, the [NVIDIA DLI](https://nvidia.com/dli) offers several in depth CUDA Programming courses.

For those of you just starting out, please consider [_Fundamentals of Accelerated Computing with CUDA C/C++_](https://courses.nvidia.com/courses/course-v1:DLI+C-AC-01+V1/about) which provides dedicated GPU resources, a more sophisticated programming environment, use of the [NVIDIA Nsight Systems™](https://developer.nvidia.com/nsight-systems) visual profiler, dozens of interactive exercises, detailed presentations, over 8 hours of material, and the ability to earn a DLI Certificate of Competency.

Similarly, for Python programmers, please consider [_Fundamenals of Accelerated Computing with CUDA Python_](https://courses.nvidia.com/courses/course-v1:DLI+C-AC-02+V1/about).

For more intermediate and advance CUDA programming materials, please check out the _Accelerated Computing_ section of the NVIDIA DLI [self-paced catalog](https://www.nvidia.com/en-us/training/online/).
