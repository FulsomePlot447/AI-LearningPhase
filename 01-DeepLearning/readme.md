# 🧠 Deep Learning & Machine Learning with PyTorch

A comprehensive collection of notebooks covering the fundamentals and practical applications of **Machine Learning**, **Deep Learning**, and **PyTorch**. This repository documents my learning journey through building, training, evaluating, and deploying deep learning models using industry-standard tools and workflows.

---

## 📂 Repository Structure

```
├── notebooks/
│   ├── 01_Custom.ipynb
│   ├── 02_Experiment_tracking.ipynb
│   ├── 03_FashionNet.ipynb
│   ├── 04_FoodModel.ipynb
│   ├── 05_Model_delpoyment.ipynb
│   ├── 06_Non_linear_data.ipynb
│   ├── 07_Paper_Replicating.ipynb
|   ├── 08_Transfer_learning.ipynb
|   ├── 09_Xor.ipynb
│
├── data.zip/
│   ├── pizza_steak_sushi
│   └── pizza_steak_sushi/
│       ├── train/
│       └── test/
│
└── README.md
```

---

# 📖 Notebook Overview

## 1. PyTorch Fundamentals

Learn the building blocks of PyTorch.

### Topics Covered

* Tensor creation and manipulation
* Tensor operations
* GPU (CUDA) support
* Tensor indexing and slicing
* Matrix multiplication
* Random tensors
* Automatic differentiation (Autograd)
* Device management (CPU/GPU)

**Skills Learned**

* Working with tensors
* Efficient tensor computations
* GPU acceleration
* PyTorch fundamentals

---

## 2. Machine Learning Basics

Introduction to the complete machine learning workflow using PyTorch.

### Topics Covered

* Data preprocessing
* Train/Test split
* Linear Regression
* Model training
* Loss functions
* Optimizers
* Model evaluation
* Saving and loading models

**Skills Learned**

* Building ML pipelines
* Model evaluation
* Regression models
* Training loops

---

## 3. FoodVision — Pizza, Steak & Sushi

A multiclass image classification project using a custom image dataset.

### Topics Covered

* Image preprocessing
* Data augmentation
* ImageFolder datasets
* CNN architecture
* Model training
* Prediction visualization
* Accuracy evaluation

Dataset Classes:

* 🍕 Pizza
* 🥩 Steak
* 🍣 Sushi

**Skills Learned**

* Computer Vision
* CNNs
* Image preprocessing
* Data loading with DataLoader

---

## 4. FashionMNIST Classification

Classification of grayscale clothing images using neural networks.

### Topics Covered

* FashionMNIST dataset
* Fully Connected Networks
* CNN implementation
* Model comparison
* Accuracy metrics
* Confusion matrix

Dataset Classes include:

* T-shirt
* Trouser
* Pullover
* Dress
* Coat
* Sandal
* Shirt
* Sneaker
* Bag
* Ankle Boot

**Skills Learned**

* Image classification
* CNN implementation
* Evaluation metrics

---

## 5. Paper Replication

Implementation and reproduction of a research paper to understand modern deep learning architectures.

### Topics Covered

* Reading research papers
* Recreating architectures
* Training from scratch
* Hyperparameter tuning
* Comparing results

**Skills Learned**

* Research implementation
* Understanding academic papers
* Model replication

---

## 6. Transfer Learning

Training powerful image classifiers using pretrained models.

### Topics Covered

* Pretrained models
* Feature extraction
* Fine-tuning
* Freezing layers
* Efficient training

Common pretrained models include:

* EfficientNet
* ResNet
* Vision Transformers (if applicable)

**Skills Learned**

* Transfer Learning
* Fine-tuning
* Reduced training time
* Improved accuracy

---

## 7. Model Deployment on Hugging Face

Deploy trained PyTorch models for public inference using Hugging Face Spaces.

### Topics Covered

* Exporting trained models
* Loading models for inference
* Building prediction interfaces
* Hugging Face deployment
* Model sharing

**Skills Learned**

* Model deployment
* Inference pipelines
* Sharing ML applications

---

## 8. Non-Linear Data Classification

Understanding neural networks on non-linear datasets.

### Topics Covered

* Synthetic datasets
* Decision boundaries
* Hidden layers
* Activation functions
* Binary classification

**Skills Learned**

* Non-linear modeling
* Neural network architecture
* Decision boundary visualization

---

## 9. Experiment Tracking with TensorBoard

Monitor and compare model performance during training.

### Topics Covered

* TensorBoard setup
* Logging metrics
* Training curves
* Validation metrics
* Hyperparameter comparison
* Model graph visualization

**Skills Learned**

* Experiment tracking
* Model debugging
* Performance comparison

---

## 8. Implementing XOR Gate using Linear Neural Networks

A basic implementation of XOR Gate

## 9. Custom Neural Network using numpy

A design of Linear layer using numpy and maths

## Topic Covered

* Numpy
* Calculas Maths
* Linear Layer

**Skills Learned**

* Numpy
* Depth and Working of Linear Layer

# 📦 Dataset

This repository includes the **Pizza, Steak, Sushi** dataset used throughout multiple notebooks.

```
data/
├── pizza_steak_sushi.zip
└── pizza_steak_sushi/
    ├── train/
    │   ├── pizza/
    │   ├── steak/
    │   └── sushi/
    │
    └── test/
        ├── pizza/
        ├── steak/
        └── sushi/
```

The dataset is organized into separate **training** and **testing** directories following the standard folder structure expected by `torchvision.datasets.ImageFolder`. This makes it straightforward to build reproducible data pipelines and train image classification models.

---

# 🛠 Technologies Used

* Python
* PyTorch
* TorchVision
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* TensorBoard
* Hugging Face
* Google Colab / Jupyter Notebook

---

# 🎯 Learning Outcomes

By working through these notebooks, you'll gain hands-on experience with:

* PyTorch fundamentals
* Machine Learning workflows
* Deep Learning
* Computer Vision
* Transfer Learning
* Research paper implementation
* Experiment tracking
* Model deployment
* Data preprocessing
* Performance evaluation
* Reproducible deep learning pipelines

---

# 🚀 Getting Started

1. Clone the repository:

```bash
git clone https://github.com/FulsomePlot447/AI-LearningPhase.git
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open any notebook and run the cells sequentially.

---

# 📌 Note

Some notebooks expect the dataset to be extracted before execution. If only the ZIP archive is present, unzip it into the `data/` directory so the `train/` and `test/` folders are available in the expected structure.

---

## ⭐ If you find this repository useful, consider giving it a star!
