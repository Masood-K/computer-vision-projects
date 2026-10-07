# Computer Vision Architecture Replications

Implementations and study of computer vision architectures, progressing from CNNs to efficient models, attention and Vision Transformers. This is part of my broader **Robotics & AI** learning direction, with vision supporting robotic perception.

**Status:** Ongoing implementations and study. This repository combines architecture implementations with pretrained-model experiments and transfer learning; not every model is implemented from scratch.

## Notebook guide

| Area | Work represented in this repository |
| --- | --- |
| AlexNet | Architecture implementation and pretrained PyTorch experiments for flower classification |
| VGG | TensorFlow/Keras architecture implementation and pretrained PyTorch/TensorFlow experiments |
| GoogLeNet, ResNet and DenseNet | Pretrained-model experiments |
| MobileNet | PyTorch architecture implementation and pretrained-model experiments |
| EfficientNet and NASNet | Pretrained-model experiments |
| SqueezeNet | Architecture implementations, modified variants and pretrained-model experiments |
| Attention | Self-attention study and implementation |
| Vision Transformer | ViT architecture implementation using PyTorch and MNIST |
| Transfer learning | Fine-tuning, differential learning rates and learning-rate scheduling |
| Neural network foundations | Linear models, activation functions and overfitting experiments |

The descriptions above identify notebook scope, not benchmark claims or proof that every experiment has been fully validated.

## Explore the work

- [CNN foundations: AlexNet](Alexnet/)
- [VGG](VGGNet/) · [GoogLeNet](GoogLeNet/) · [ResNet](ResNet/) · [DenseNet](DenseNet/)
- [MobileNet](MobileNet/) · [EfficientNet](EfficientNet/) · [SqueezeNet](SqueezeNet/) · [NASNet](NASNet/)
- [Self-attention notebook](Attention%20Mechanism/Self_Attention.ipynb)
- [Vision Transformer notebook](ViT/Coding_ViT_architecture_using_pytorch_MNIST.ipynb)
- [Transfer learning experiments](Transfer%20Learning/)

## Working with the notebooks

Open the relevant notebook in Jupyter and review its imports, dataset paths and training configuration before running it. Flower-classification experiments use the `flower_images/` directory; the ViT notebook targets MNIST. Dataset paths may need adjustment for your environment.

Pretrained-model experiments may require downloading model weights. Hardware, package versions and training settings affect reproducibility. No shared, version-pinned environment or common benchmark is specified in this README.

## Tools

Python · PyTorch/torchvision · TensorFlow/Keras · Jupyter Notebook

## Related work

[Portfolio](https://masood-patan.vercel.app) · [Ground Heat PINNs research](https://github.com/Masood-K/Ground_heat_pinns) · [Profile](https://github.com/Masood-K)
