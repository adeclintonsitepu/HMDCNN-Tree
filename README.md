# Optimized Visual Recognition through a Deep Convolutional Neural Network with Hierarchical Modular Organization
This repository contains the code (in PyTorch) for "Optimized Visual Recognition through a Deep Convolutional Neural Network with Hierarchical Modular Organization" article by Ade Clinton Sitepu and Chuan-Ming Liu

## Introduction
<hr/>
Artificial Intelligence (AI) tasks such as natural language processing, visual recognition, and autonomous decision-making require substantial computational power beside its superior performance. The need for AI, especially Deep Convolution Neural Networks (DCNNs), in image processing is substantial and has rapidly grown in today's era. Convolutional Neural Networks (CNNs) have demonstrated remarkable capabilities in visual recognition and understanding, making them indispensable in a wide range of applications. DCNNs techniques have brought about an advance impact in the field of artificial intelligence (AI) and show remarkable success in visual recognition (computer vision) domains. In computer vision, DCNNs trained on large-scale image datasets have achieved high accuracy. However, the exceptional performance of DCNNs comes with the considerable cost of computational complexity.

The article provides the following contributions:
<ul>
  <li>Introducing the HMDCNN-tree, a hierarchical tree structure composed of interconnected nodes, where nodes with children are termed super-clusters. Each node, except leaf nodes, contains a module trained to classify inputs into its children, preventing unnecessary activations and enhancing visual recognition efficiency.</li>
  <li>Utilizing the concept of fuzzy sets and sigmoid membership function (sgmf), the creation of modules in the HMDCNN-tree is based on visual similarities between new and old classes, allowing for dynamic adaptation without relying on fixed optimal thresholds.</li>
  <li>The trade-off between accuracy and DCNN architecture size is addressed by using the metric change in efficiency gain and fixed optimal threshold values, enabling the selection of optimal configurations for each module and significantly reducing DCNN size without losing its performance across popular image datasets.</li>
</ul>
