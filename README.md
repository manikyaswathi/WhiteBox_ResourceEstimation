# WhiteBox_ResourceEstimation

# **Advancing AI with AI4HPC: From Black-Box to White-Box Approaches in DNN Resource Estimation**

Artificial intelligence (AI) technologies are transforming research and industry, and their growing reliance on computing is driving unprecedented demand for high-performance computing (HPC). For decades, HPC has been central to breakthroughs in scientific research, but the increasing complexity of AI workflows has amplified the need for computational resources. By 2030, the energy consumption of U.S. data centers is projected to triple, primarily due to AI's rising requirements. For perspective, training early versions of ChatGPT (v3.0) required 25,000 P100 GPUs running for three months—consuming energy equivalent to the annual electricity usage of 5,000 U.S. households. Compare this to the modest ~350 GPUs available in a typical academic supercomputing center.

## **Training deep neural networks (DNNs) presents significant challenges, including:**

- Precise estimation of computational, memory, and storage needs
- Optimization of runtime for efficient resource allocation

To address these challenges, our research focuses on developing HPC application resoource estimators for DNN workloads. We explore two complementary approaches to estimating training times: black-box and white-box models.

1. _Black-box Approach:_ Each DNN training session is treated as an independent application, represented as a single feature for estimation. This method emphasizes simplicity and adaptability across diverse workloads.

2. _White-box Approach:_ Inspired by Google’s TPU Performance Model, this method integrates high-level optimization graphs from TensorFlow compilers with hardware-specific features. It enables scalable and precise estimations for neural networks within the same architecture family.

Our evaluations demonstrate the effectiveness of these approaches using Convolutional Neural Networks (CNNs), highlighting their accuracy, usability, and flexibility across different stages of the machine learning lifecycle.

This research aims to bridge the gap between resource-intensive AI workflows and the limited computational resources available in academic and small-scale research environments. By improving resource estimation, we can make AI research more sustainable, accessible, and efficient.
