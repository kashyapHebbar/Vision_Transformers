
---
# Interpreting Vision Transformers: A Deep Learning Approach

This project is a comprehensive study of Vision Transformer (ViT) models, aiming to interpret the inner workings of these powerful architectures. It features an array of ViT models, including their DeiT variants, and implements techniques like Attention Maps and Attention Rollout to understand how these models process visual data.

## Project Overview

Transformers have revolutionized the field of Natural Language Processing and have recently made a promising entry into the field of Computer Vision. This project dives deep into Vision Transformers, utilizing pretrained models to interpret their predictions and attention mechanisms.

The process involves loading pretrained ViT models, calculating their attention maps, computing score matrices, and visualizing self-attention maps. We further implement the Attention Rollout technique to provide interpretability for the Transformer models' decisions.

## Key Features

* Loading and processing of data
* Utilizing various ViT models:
  - Vanilla ViT models such as vit_base_patch16_224, vit_base_patch32_224, vit_large_patch16_224
  - ViT DeiT models like deit_tiny_patch16_224
* Computing and visualizing attention maps
* Implementing Attention Rollout technique

## Tools and Libraries Used

* Python 3.x
* PyTorch - for implementing and loading the ViT models
* Matplotlib - for visualization

## Installation & Usage

Instructions on how to install and run your code. For example:

```sh
git clone https://github.com/kashyapHebbar/vision_Transformers.git
```

## How It Works

The project starts by loading the pretrained ViT models and input images. It then calculates attention maps and computes a score matrix for each image. The score matrix is visualized as self-attention maps which highlight areas the model focuses on when making predictions. Furthermore, it implements the Attention Rollout technique to provide insights into how the attention mechanism of the Transformer models works.

## Future Plans

We aim to continue exploring and implementing novel interpretability techniques for Transformer models and further extend this work to more advanced Transformer variants.

## Acknowledgements

This project is a result of a deep exploration into the world of Transformer models, leveraging the powerful capabilities provided by PyTorch.

---
