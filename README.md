# Learning Note

## Contents
- [Papers](#papers)

## <span id = "papers">Papers</span>
> Paper list for deep learning

| Paper | Publication | Year | Contribution | Code |
| :- | :-: | :-: | :- | :-: |
| ***Augmentation*** |
| [Data augmentation using learned transforms for one-shot medical image segmentation](https://arxiv.org/pdf/1902.09383) | CVPR | 2019 | Present an automated data augmentation method for synthesizing labeled medical images by a spatial deformation field and an intensity change. | [Official](https://github.com/xamyzhao/brainstorm) |
| [TorchIO: a Python library for efficient loading, preprocessing, augmentation and patch-based sampling of medical images in deep learning](https://arxiv.org/pdf/2003.04696) | arXiv | 2020 | TorchIO is a Python package containing intensity and spatial transforms for data augmentation and preprocessing. | [Official](https://github.com/fepegar/torchio) |
| ***Network Architecture*** |
| [RepVGG: Making VGG-style ConvNets Great Again](https://arxiv.org/pdf/2101.03697) | CVPR | 2021 | Decouple the training-time and inference-time architecture of VGG | [Official](https://github.com/megvii-model/RepVGG) [PyTorch](https://github.com/DingXiaoH/RepVGG) |
| ***Representation Learning*** |
| [Exploring Simple Siamese Representation Learning](https://arxiv.org/pdf/2011.10566) | CVPR | 2021 | Propose that simple Siamese (SimSiam) networks can learn meaningful representations with a stop-gradient operation, and without (i) negative sample pairs, (ii) largebatches, (iii) momentum encoders | [PyTorch](https://github.com/PatrickHua/SimSiam) |
| ***Vision Transformer (ViT)*** |
| [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](https://arxiv.org/pdf/2010.11929) | arXiv | 2020 | Apply transformer in CV | [Official](https://github.com/google-research/vision_transformer) [PyTorch](https://github.com/lucidrains/vit-pytorch) |
| [Tokens-to-Token ViT: Training Vision Transformers from Scratch on ImageNet](https://arxiv.org/pdf/2101.11986) | arXiv | 2021 | Structurize image by Tokens-To-Token | [PyTorch](https://github.com/lucidrains/vit-pytorch) |
| [TransGAN: Two Transformers Can Make One Strong GAN](https://arxiv.org/pdf/2102.07074) | arXiv | 2021 | Apply ViT in GAN | [Official](https://github.com/VITA-Group/TransGAN)
| [Pyramid Vision Transformer: A Versatile Backbone for Dense Prediction without Convolutions](https://arxiv.org/pdf/2102.12122) | arXiv | 2021 | Apply pyramid in ViT | [Official](https://github.com/whai362/PVT) |
| [Pre-Trained Image Processing Transformer](https://arxiv.org/pdf/2012.00364) | CVPR | 2021 | Develop a pre-trained model for low-level CV task | |
| [Transformer in Transformer](https://arxiv.org/pdf/2103.00112) | arXiv | 2021 | Propose a novel Transformer-iN-Transformer (TNT) model for modeling both patch-level and pixel-level representation | [Official](https://github.com/huawei-noah/noah-research/tree/master/TNT) [PyTorch](https://github.com/lucidrains/transformer-in-transformer) |
| ***Reinforcement Learning*** |
| [Learning to Paint With Model-based Deep Reinforcement Learning](https://arxiv.org/pdf/1903.04411) | ICCV | 2019 | Teach machines to paint like human painters | [Official](https://github.com/megvii-research/ICCV2019-LearningToPaint) |