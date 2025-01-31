<font size="5">Handwritten Digit Classification</font><br>
<font size="3">📌 Introduction</font><br>
<p>Handwritten digit classification is a deep learning task that involves recognizing numerical digits from images. This project utilizes a Convolutional Neural Network (CNN) to classify digits from the MNIST dataset.</p>
<font size="3">📂 Dataset</font><br>
The MNIST dataset consists of:

60,000 training images

10,000 testing images

Grayscale images (28x28 pixels) labeled from 0 to 9
<font size="3">🏗 Model Architecture</font><br>
The model is built using TensorFlow/Keras and consists of:

Convolutional Layers: Extract spatial features

Fully Connected Layers: Perform final classification

Activation Functions: ReLU & Softmax
<font size="5">📊 Training and Evaluation</font><br>
Loss Function: Categorical Cross-Entropy

Optimizer: Adam

Metrics: Accuracy

Batch Size: 32

Epochs: 10
<font size="3">📉 Results and Insights</font><br>
The CNN model achieved high accuracy on both training and test datasets.

Overfitting was minimized using dropout and data augmentation.

The model successfully classifies most digits but struggles with ambiguous handwriting styles.
<font size="3">🛠 Tech Stack</font><br>
Programming Language: Python

Libraries: TensorFlow, Keras, NumPy, Matplotlib
<font size="3">📌 Conclusion</font><br>
<p>This project demonstrates how deep learning can be used for digit recognition. The CNN-based approach provides high accuracy and serves as a strong foundation for real-world handwriting recognition applications.

</p>
