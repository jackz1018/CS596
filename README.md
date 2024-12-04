# CS596

The overarching goal is to optimize GPU sharing technologies to address the inefficiencies in resource utilization, which can have significant economic and performance implications in computing environments.
What’s the “big” problem? The major issue is the underutilization of GPU resources in various computing environments, ranging from small-scale labs to large data centers. GPUs, being high-value assets, often remain idle or underused due to inefficient resource allocation and management.

![描述文本](https://docs.nvidia.com/deploy/mps/_images/image1.png)

In many computing environments, GPUs are not utilized to their fullest potential due to lack of effective sharing mechanisms. This results in wasted computational power and increased costs due to the need for more hardware to meet peak demands.

By clearly identifying the problem of GPU underutilization, the solution becomes evident: thus the ≈ paper would focus on researching how to develop or improve GPU sharing technologies. These new stack need to ensure that GPU resources can be dynamically allocated and managed to match the computational demands, thus maximizing the GPU usage efficiency, reducing costs, and increasing the performance of computing systems.

![MIG Featured Image](https://blogs.nvidia.com/wp-content/uploads/2020/05/mig-featured-image-FINAL-1280.jpg)

The approach to solving this problem involves the development of new algorithms, possibly leveraging artificial intelligence to predict workload patterns and adjust resource allocations in real-time. Implementing robust virtualization and containerization technologies could also be part of the solution, enabling better isolation, security, and flexibility in resource sharing.
Thus, addressing this problem not only optimizes resource usage but also propels forward the capabilities and sustainability of GPU or CUDA cloud computing infrastructures.
![DGX A100 Server Scaling](https://developer-blogs.nvidia.com/wp-content/uploads/2021/09/DGX-A100-server-scaling-total-throughput-1024x412.png)

