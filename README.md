🧠 Evolution of CNNs: From LeNet-5 to ResNet
A deep dive into the history and architectural breakthroughs of Convolutional Neural Networks. This presentation traces the timeline of innovation from the foundational LeNet-5 to the deep residual learning of ResNet, analyzing how each model solved the limitations of its predecessors.

📄 Overview
This presentation was created to visualize the "Big Bang" of modern Deep Learning. It breaks down the structural evolution of CNNs, focusing on the transition from simple digit recognition to massive-scale image classification on ImageNet.

🔍 Key Architectures Covered
1. LeNet-5 (1998) - The Origin
The Foundation: Introduced the standard Convolution → Pooling hierarchy.

Focus: Handwritten digit recognition (MNIST).

Legacy: Proved that backpropagation could train convolutional layers, though limited by activation functions (Sigmoid/Tanh) and computing power.

2. AlexNet (2012) - The Breakthrough
The Spark: The architecture that kicked off the Deep Learning boom by crushing the ImageNet competition (16.4% error rate).

Innovations:

ReLU Activations: Solved vanishing gradients.

Dropout: Prevented overfitting in deep layers.

GPU Training: Enabled massive parallelization for the first time.

3. VGG-16 (2014) - Standardization
Philosophy: "Simplicity and Depth."

Architecture: Replaced large filters with stacks of small 3x3 convolutions.

Trade-off: Achieved high accuracy and modularity but at the cost of massive parameter counts (~138M) and slow training times.

4. GoogLeNet / Inception (2014) - Efficiency
The Inception Module: Addressed the computational cost of deep networks.

Innovation: used parallel filters (1x1, 3x3, 5x5) to capture features at different scales simultaneously.

1x1 Convolutions: Acted as "bottlenecks" to reduce dimensionality and computation.

5. ResNet (2015) - Deep Residuals
The Depth Revolution: Successfully trained a 152-layer network (vs. VGG's 19).

Residual Blocks: Introduced "skip connections" to allow gradients to flow through the network unimpeded, solving the degradation problem in very deep networks.

🛠 Usage
Feel free to use these slides for educational purposes, study groups, or as a quick refresher on CNN history.

