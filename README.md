# AI-Enabled Robust SVD for Wireless Communication
Here is a list of topics and questions I must learn before the hackathon.

## Singular Value Decomposition (SVD) Basics

**Key concepts**
* ~~Singular values, singular vectors~~
* ~~Frobenius norm~~
* ~~Computational complexity~~

1) ~~How is SVD performed mathematically?~~
2) ~~What are the limitations of classical SVD in noisy/incomplete data?~~

**SVD Optimizations**
* ~~Outlier rejection~~
* ~~Missing data imputation~~

1) ~~What specific robust SVD algorithms exist?~~
2) ~~How do they handle noise/outliers compared to classical SVD?~~

## Wireless Communication (5G/6G)

**Key Concepts**
* ~~Wireless communication fundamentals~~
* MIMO and Beamforming
* Channel State Information (CSI)
* Precoding, Channel diagonalization
* Low-latency, High-speed, Energy efficiency

## SVD in Wireless Context

**Key Concepts**
* MIMO: Multiple antennas, SVD diagonalizes for parallel streams.
* Beamforming/Precoding: Beam steering, maximizing SNR.
* Robustness: Regularization, outlier rejection. Dealing with noise.

1) How does SVD enable channel diagonalization in MIMO?
2) What are limitations in noisy CSI estimation?

## AI-Powered SVD Approximations

**Key Concepts**
* Neural Decomposition: Autoencoders, differentiable SVD via unfolding (iterative algos as layers).
* Low-Rank: Truncating to top k singular values; NN compression (pruning/quantization to int8/float16) for dynamic rank.
* Complex-Valued NNs: Handle wireless signals (e.g., IQ components) with complex activations.

1) How can NNs approximate low-rank H for beamforming?
2) What loss functions suit training (e.g., Frobenius + orthogonality penalty)?

## Hardware-Aware Optimization

**Key Concepts**
* Constraints: Low-latency (<1ms), energy efficiency for IoT; model size under 100MB.
* Balancing: Compute (flops), memory (GB), energy (joules) for edge devices.
* Trade-offs: Precision (float16 ok for singular values) vs. speed/energy.

## Used materials
* [Singular Value Decomposition playlist](https://www.youtube.com/playlist?list=PLMrJAkhIeNNSVjnsviglFoY2nXildDCcv)
* Data Driven Science & Engineering, book by Steven L. Brunton and J. Nathan Kutz