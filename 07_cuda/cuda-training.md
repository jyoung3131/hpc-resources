# CUDA Training

## What's the objective of this module?
When working with HPC systems and applications, you will often need to run code that is written in [CUDA](https://en.wikipedia.org/wiki/CUDA) a C-based language that NVIDIA developed to program Graphics Processing Units (GPUs).

## What should you learn? 
* [What is a GPU and why is GPU programming important?](http://developer.download.nvidia.com/compute/developertrainingmaterials/presentations/general/Why_GPU_Computing.pptx)
* [What does a CUDA program look like?]()
* [How do you compile and run a CUDA program?]()


### Suggested Workflow
1) Get an account on an HPC system with a CUDA GPU [Link TBD], or [install CUDA on your local machine](https://docs.nvidia.com/cuda/cuda-quick-start-guide/index.html). 
2) Review the following modules at https://developer.nvidia.com/cuda-education
     * [Why GPU Computing](http://developer.download.nvidia.com/compute/developertrainingmaterials/presentations/general/Why_GPU_Computing.pptx)
     * [Introduction to the CUDA platform](http://developer.download.nvidia.com/compute/developertrainingmaterials/presentations/general/Introduction_to_CUDA_Platform.pptx)
     * [Your first CUDA program](https://developer.nvidia.com/how-to-cuda-c-cpp)
3) Work through Homework 1 in the [OLCF CUDA training series](https://github.com/olcf/cuda-training-series/tree/master/exercises/hw1)
4) Review the [module on CUDA libraries](http://developer.download.nvidia.com/compute/developertrainingmaterials/presentations/cuda_language/Introduction_to_Libraries.pptx).


### Questions for Discussion
* When are GPUs faster than CPUs?
* Why do we use CUDA to program GPUs when OpenMP and OpenACC exist?
* What libraries does CUDA provide for HPC and machine learning?

## Other Resources
* [OLCF CUDA Training Series](https://github.com/olcf/cuda-training-series) - an in-depth dive into programming with CUDA.
* [Even Easier Introduction to CUDA C++](https://developer.nvidia.com/blog/even-easier-introduction-cuda/)
* [NVIDIA notebook for the CUDA Introduction (free)](https://courses.nvidia.com/courses/course-v1:DLI+T-AC-01+V1/about) - note some of the other training here is not free.
* [CUDA Fortran Introduction](https://developer.nvidia.com/blog/easy-introduction-cuda-fortran/)
* [CSE 5991 - David Kirk and Wen-Mei Hu - Accelerated Computing - Programming GPUs ](https://tschmidt23.github.io/cse599i/) - this course covers common patterns and how to implement them on GPUs. Slightly more advanced but may be a good reference!

## Advanced Concepts for CUDA Programming
* [CUDA C Best Practices Guide](https://docs.nvidia.com/cuda/cuda-c-best-practices-guide/index.html)
* [CUDA Graphs](https://www.nersc.gov/users/training/events/cuda-graphs-october-13-2021/)
* [Introduction to Graph Analysis with cuGraph and Rapids-AI](https://medium.com/rapids-ai/introduction-to-graph-analysis-using-cugraph-a9dc2fbc3c5e)
