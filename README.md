# Efficient-ML

### Papers on Efficient Training and Inference of LLMs and Other Deep Neural Networks

| **Title** | **Summary** |
|:--|:----:|
| [![Star](https://img.shields.io/github/stars/ruikangliu/FlatQuant.svg?style=social&label=Star)](https://github.com/ruikangliu/FlatQuant)<br>[FLATQUANT: Flatness Matters for LLM Quantization](https://huggingface.co/papers/2410.09426)</br>Published: 12/10/24</br>Accessed: 22/10/24<br>Conference: NA<br>Group: NA|<img width="1200" alt="image" src="figures/flat_quant.png"> </br> <p align="left"> 1. Flattens weight and activation distributions for better quantization. </br> 2. Optimizes affine transformations per linear layer.</br> 3. Uses lightweight, block-wise training on calibration data.</br>4. Uses Kronecker decomposition to reduce memory/compute overhead.</br>
| [![Star](https://img.shields.io/github/stars/haiquanlu/AlphaPruning.svg?style=social&label=Star)](https://github.com/haiquanlu/AlphaPruning)<br>[AlphaPruning](https://arxiv.org/pdf/2410.10912)</br>Published: 02/10/24</br>Accessed: 24/10/24<br>Conference: Neurips<br>Group: NA|<img width="800" alt="image" src="figures/alpha_pruning.png"> </br> <p align="left"> 1. Suggests a layerwise purning of LLMs for faster infernence </br> 2. Uses HT-SR(Heavytailed Self-regularization) theory and ESDs(Empirical Spectral Density) of matrices to decide layerwise pruning ratios  .</br> 3. Shape metrics outperform scale metrics for computing importance of each layer for pruning.</br></p>
