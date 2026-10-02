## Day 4 – GPU, VRAM & Model Memory

### Topics Learned
- CPU vs GPU
- GPU Cores
- Types of GPU
- VRAM
- Context Window
- Context Length
- AI Model Parameters
- Quantization
- Q4 and Q4_K_M
- Basic VRAM Estimation

### Practical
Created `vram_estimate.py` to understand and estimate AI model memory requirements.

### Example
For a 1.5B parameter model with Q4 quantization:

1.5B × 4 / 8 ≈ 0.75 GB

With quantization overhead, the model weight memory is approximately 0.8 GB.

### Key Learning
GPU is useful for parallel AI computations, while VRAM stores the model weights and other data required during AI inference.

Context length represents the amount of token-based information a model can handle at one time. Longer context generally requires more memory.
