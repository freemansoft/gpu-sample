# gpu-sample
Playground for doing some AI Workbench Jupyter Notebook.
Currently looking at Advent of Code 2024 Day 17 brute force

## References
* [CUDA C++ programming Guide](https://docs.nvidia.com/cuda/cuda-c-programming-guide/) useful for understanding kernels, SMs, blocks, threads, etc
* [CUDA core and SM counts in various cards](https://en.wikipedia.org/wiki/CUDA)

## Getting Started
Optional section to summarize important steps and how to use the project & apps in the project

## Advent of Code Day 17
Using parallel python and GPU to solve Day 17 part 2.  It turns out GPUs were the wrong approach but parallel CPU using njit worked fine for brute force.