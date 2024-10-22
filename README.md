# Efficient-ML

### Papers on Efficient Training and Inference of LLMs and Other Deep Neural Networks

| **Title** | **Introduction** | **Summary** |
|:--|:----:|:---:|
| [FLATQUANT: Flatness Matters for LLM Quantization](https://huggingface.co/papers/2410.09426) | <img width="1500" alt="image" src="figures/image.png"> | The authors propose a method that focuses on achieving a flatter distribution of weights and activations to enhance the effectiveness of quantization. Their approach, named FLATQUANT, identifies the optimal affine transformation for each linear layer using a lightweight, block-wise training strategy over calibration data. To reduce inference overhead, they leverage Kronecker decomposition, which helps in minimizing both memory and computational demands.
