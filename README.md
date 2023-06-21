# Vission-Transformer
Building ViT Model from scratch using Tensorflow 
Vision Transformer, also known as ViT, is a groundbreaking architecture that brings the power of transformers to the field of computer vision. Traditionally, convolutional neural networks (CNNs) have dominated image recognition tasks, but ViT represents a paradigm shift in visual processing.

Unlike CNNs that rely on convolutional layers, Vision Transformers utilize the transformer architecture, which has achieved remarkable success in natural language processing. By adapting transformers for computer vision, ViT has demonstrated exceptional performance in image classification, object detection, and other vision tasks.

Architecture of Vision Transformer Model
---
<img width="321" alt="Architecture" src="https://github.com/prashanth-githubuser/Vission-Transformer/assets/120344718/2e25c1d7-b0ec-4a74-82d8-e4d09c2d9050">

--- 
Key Features of Vision Transformer:

1️⃣ Self-Attention Mechanism: ViT employs self-attention to model global dependencies among image patches. This allows it to capture long-range contextual information, enabling better understanding of image semantics.

2️⃣ Patch Embeddings: Input images are divided into smaller fixed-size patches, which are then linearly transformed into embeddings. This process preserves the spatial information while enabling parallel processing across patches.

3️⃣ Positional Encoding: To incorporate spatial information, ViT incorporates positional encoding. This technique adds positional information to the patch embeddings, allowing the model to learn the spatial relationships between different parts of the image.

4️⃣ Training on Large-Scale Datasets: Vision Transformers benefit from large-scale pre-training on vast image datasets, followed by fine-tuning on specific tasks. This enables them to learn rich representations and generalize well to diverse visual tasks.


Details of Vision Transformer model variants.

| Model    | Layers | Hidden size |MLP size |Heads |Params |
| :------- | :----: | :---------: |:------: |:---: |:----: |
| ViT-Base | 12     |     768     |  3072   |  12  |  86M  |
| ViT-Large| 24     |     1024     |  4096  |  16  |  307M |
| ViT-Huge | 32     |     1280    |  5120   |  16  |  632M |
