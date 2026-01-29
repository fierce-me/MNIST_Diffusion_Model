# MNIST_Diffusion_Model
This project implements a denoising diffusion probabilistic model (DDPM) from scratch to generate handwritten digits from the MNIST dataset. The model learns to reverse a gradual noising process, starting from random noise and producing realistic 28×28 grayscale digits through iterative denoising steps.

### Features
- **Full DDPM training pipeline** with custom U-Net architecture
- **Forward & reverse diffusion processes** with linear noise scheduling
- **Conditional generation** (optional class-guided sampling)
- **Lightweight implementation** using PyTorch
- **Visualization tools** for sampling progress and loss curves

### Results
The model generates diverse MNIST-style digits after training, showcasing the capability of diffusion models for image synthesis on small-scale datasets.
