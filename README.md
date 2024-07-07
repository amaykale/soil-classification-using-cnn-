# soil-classification-using-cnn-
Soil Classification using Convolutional Neural Networks (CNN)

Overview
This project employs Convolutional Neural Networks (CNNs) to classify soil types based on images. The CNN model is trained using a dataset containing images of four main soil classes: Red Soil, Black Soil, Alluvial Soil, and an unspecified class. Soil classification is crucial for various applications in agriculture and environmental science, aiding in soil management and analysis.

Key Features
Dataset Organization: The dataset is structured into training and testing sets, each with subdirectories for different soil classes.

Data Augmentation: Training data is augmented using techniques such as rotation, shifting, shearing, and flipping to enhance model generalization.

Model Architecture: The CNN model consists of convolutional layers followed by max-pooling layers, flattening layers, and dense layers with ReLU and softmax activations for classification.

Training and Evaluation: The model is trained using the Adam optimizer and categorical cross-entropy loss function. Evaluation metrics such as accuracy, F1 score, confusion matrix, and classification report are computed on the test set.

Model Persistence: The trained model is saved both in TensorFlow SavedModel format and native Keras format for future use and deployment.
