# 🧥 TinyVGG on FashionMNIST using PyTorch

This project implements a convolutional neural network using a simplified VGG-style architecture (TinyVGG) in PyTorch to classify images from the FashionMNIST dataset. It also visualizes the intermediate feature maps to better understand what the network learns.

---

## 🔍 Techniques of Interest

- Custom [TinyVGG architecture](https://arxiv.org/abs/1409.1556) in PyTorch
- Two-block convolutional network with ReLU activations and MaxPooling
- Use of [CrossEntropyLoss](https://pytorch.org/docs/stable/generated/torch.nn.CrossEntropyLoss.html) for multi-class classification
- Training using [Stochastic Gradient Descent (SGD)](https://pytorch.org/docs/stable/optim.html#torch.optim.SGD)
- Feature map visualization for interpretability using `matplotlib`

---

## 🧰 Libraries and Tools

- [PyTorch](https://pytorch.org/) – Deep learning framework
- [Torchvision](https://pytorch.org/vision/stable/index.html) – Preloaded FashionMNIST dataset
- [Matplotlib](https://matplotlib.org/) – Visualizing feature maps

---

## 📁 Project Structure
- **`TinyVGG_FashionMNIST.py`**: Contains the full code for model training, evaluation, and visualization.

---

## 📌 Notes

This project is ideal for understanding how small CNNs learn visual features. It’s also a great entry point to experiment with model depth, visualization techniques, and performance tuning on real-world-like datasets.

---
