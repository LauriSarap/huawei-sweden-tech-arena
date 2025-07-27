# AI-Enabled Robust SVD for Wireless Communication
Here is a list of topics and questions I must learn before the hackathon.

## Singular Value Decomposition (SVD) Basics

* ~~Singular values, singular vectors~~
* ~~Frobenius norm~~
* ~~Computational complexity~~
* ~~Outlier rejection~~
* ~~Missing data imputation~~

## Wireless Communication (5G/6G)

* Cellular networks
* MIMO
* Beamforming & Precoding
* Channel State Information (CSI)
* Channel diagonalization
* SVD for MIMO

## AI-Powered SVD Approximations

* Neural Decomposition: Autoencoders, differentiable SVD via unfolding (iterative algos as layers).
* Low-Rank: Truncating to top k singular values; NN compression (pruning/quantization to int8/float16) for dynamic rank.
* Complex-Valued NNs: Handle wireless signals (e.g., IQ components) with complex activations.

## Hardware-Aware Optimization

* Low-latency (<1ms), energy efficiency for IoT; model size under 100MB.
* Balancy compute (flops), memory (GB), energy (joules) for edge devices.
* Precision (float16 ok for singular values) vs. speed/energy.

## Used materials
* [Singular Value Decomposition playlist](https://www.youtube.com/playlist?list=PLMrJAkhIeNNSVjnsviglFoY2nXildDCcv)
* Data Driven Science & Engineering, book by Steven L. Brunton and J. Nathan Kutz