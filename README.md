<h1>Handwritten Digit Classification<h1><br>
<h3>📌 Introduction</h3><br>
<p>Handwritten digit classification is a deep learning task that involves recognizing numerical digits from images. This project utilizes a Convolutional Neural Network (CNN) to classify digits from the MNIST dataset.</p>
<h3>📂 Dataset</h3><br>
The MNIST dataset consists of:

60,000 training images

10,000 testing images

Grayscale images (28x28 pixels) labeled from 0 to 9
<h3>🏗 Model Architecture</h3><br>
The model is built using TensorFlow/Keras and consists of:

Convolutional Layers: Extract spatial features

Fully Connected Layers: Perform final classification

Activation Functions: ReLU & Softmax
<h3>📊 Training and Evaluation</h3><br>
Loss Function: Categorical Cross-Entropy

Optimizer: Adam

Metrics: Accuracy

Batch Size: 32

Epochs: 10
<h3>📉 Results and Insights</h3><br>
The CNN model achieved high accuracy on both training and test datasets.

Overfitting was minimized using dropout and data augmentation.

The model successfully classifies most digits but struggles with ambiguous handwriting styles.
<h3>🛠 Tech Stack</h3><br>
Programming Language: Python

Libraries: TensorFlow, Keras, NumPy, Matplotlib
<h3>📌 Conclusion</h3><br>
<p>This project demonstrates how deep learning can be used for digit recognition. The CNN-based approach provides high accuracy and serves as a strong foundation for real-world handwriting recognition applications.

</p>
