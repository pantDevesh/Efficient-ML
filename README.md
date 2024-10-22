# Efficient-ML

### Papers on Efficient Training and Inference of LLMs and Other Deep Neural Networks

| **Title** | **Main Figure** | **Summary** |
|:--|:----:|:---:|
| [FLATQUANT: Flatness Matters for LLM Quantization](https://huggingface.co/papers/2410.09426) | <img width="1200" alt="image" src="figures/image.png"> | <div style="text-align: justify;"> - Flattens weight and activation distributions for better quantization.</br> - Optimizes affine transformations per linear layer.</br> - Uses lightweight, block-wise training on calibration data.</br> - Leverages Kronecker decomposition to reduce memory and computational overhead.</div> |
