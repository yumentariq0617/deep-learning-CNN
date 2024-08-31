# deep-learning-CNN
<p>I implemented a Convolutional Neural Network (CNN) to classify images in the CIFAR-10 dataset, which comprises 60,000 32x32 color images across 10 distinct classes, including objects such as airplanes, automobiles, and animals.

The CNN architecture was carefully designed to extract hierarchical features from the input images. It consists of multiple convolutional layers, each equipped with a set of filters that learn to detect essential features like edges, textures, and more complex patterns as depth increases. These layers are followed by activation functions (ReLU) to introduce non-linearity, allowing the network to model complex relationships within the data.

To reduce spatial dimensions and control overfitting, pooling layers are incorporated, which downsample the feature maps while retaining the most significant information. The feature maps are then flattened and passed through fully connected layers, which integrate the learned features to form a final decision.

The model was trained using a cross-entropy loss function, optimized with the Adam optimizer to ensure efficient convergence. This setup allowed the CNN to achieve high classification accuracy on the CIFAR-10 dataset, demonstrating its ability to generalize well across different image classes.

</p>
