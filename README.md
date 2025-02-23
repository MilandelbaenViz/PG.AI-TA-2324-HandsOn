# Postgraduate: AI Technical Architect 2023-2024

## Contents

1. **Frameworks & libraries**
   - Data Exploration & Model Training
     - *Classical Machine Learning*
     - *Deep Learning*
   - Visualizations
   - Prototyping & Robotics
2. **The tools we are going to use for the hands-on**
3. **Hands-on**
   - 01: First steps
     - First Neural Network with Keras
     - Credit Card Fraud
   - 02: Optimizations via MNIST
   - 03: CNNs & Transfer Learning
     - Object detection, identification and transfer learning with YOLO
     - CNN classifier
   - 04: Deployment & MNIST Solution
   - 05: NLP & LLMs


## Development environments
* TensorFlow: https://github.com/PXLAIRobotics/PXL_ML_Docker_v2.0_TensorFlow
* PyTorch: https://github.com/PXLAIRobotics/PXL_ML_Docker_v2.0_PyTorch


## Exercises
**01. First steps**
* [01. First Neural Network with Keras](01.%20First%20Steps/01.%20First%20Neural%20Network%20with%20Keras.ipynb)  
* [02. Credit_card_fraud](01.%20First%20Steps/02.%20Credit_card_fraud.ipynb)

**02. Optimizations via MNIST**
* [01. simple_mnist_classifier_exercise](02.%20Optimization/01.%20simple_mnist_classifier_exercise.ipynb)

**03. CNNs & Transfer Learning**
* [Traffic Signs Exercise](03.%20CNNs%20_%20Transfer%20Learning/Traffic%20Signs%20Exercise.md)

**05. NLP**
* [IMDb Sentiment Classification](05_NLP/03.%20basic_imdb_classifier_exercise.ipynb)

## Demo notebooks
**03. CNNs & Transfer Learning**
* [01. YOLO](03.%20CNNs%20_%20Transfer%20Learning/01.%20YOLO.ipynb)
* [02. CNN Classifier](03.%20CNNs%20_%20Transfer%20Learning/02.%20demo_cnn_classifier.ipynb)
* [05. LLM Intro](05_NLP/01.%20Practical_example_with_LLMs.ipynb)
* [05. LangChain](05_NLP/02.%20LangChain_Example.ipynb)

## FAQ

### Google Drive
You can mount your Google Drive in Google Colab in the following way:

```
from google.colab import drive
drive.mount('/content/drive')
```

And then access your folders like this:

```
folder = "/content/drive/MyDrive/.../"
```

### Loss functions
#### Classification
**Binary classification**
* Number of neurons in the output layer: `1`
* Activation function in the output layer: `sigmoid`
* Loss function: `binary_crossentropy` (log loss)

**Multiclass classification**
* Number of neurons in the output layer: `<num_classes>`
* Activation function in the output layer: `softmax`
* Loss function: `categorical_crossentropy` (n log loss)

#### Regression
* Number of neurons in the output layer: `1`
* Activation function in the output layer: `linear`
* Loss function: `mse` or `mae`

#### Complex outputs (i.e. YOLO)
* Number of neurons in the output layer: `<to_define>`
* Activation function in the output layer: `<to_define>`
* Activation function in the output layer: `<to_define>`
