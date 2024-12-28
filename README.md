# Classifying CIFAR-10 Dataset

This repository contains a Jupyter Notebook for classifying the CIFAR-10 dataset using machine learning techniques. The CIFAR-10 dataset is a well-known dataset consisting of 60,000 32x32 color images in 10 different classes, with 6,000 images per class. This project provides a foundation for experimenting with and improving image classification algorithms.

## Features

- Data loading and preprocessing
- Model design and training
- Evaluation of model performance
- Visualization of training results and predictions

## Prerequisites

Before running the notebook, ensure you have the following installed:

- Python 3.8 or higher
- Jupyter Notebook or Jupyter Lab

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Hariharan-Durairaj/Classifying-cifar-10-dataset-using-CNN.git
   cd Classifying-cifar-10-dataset-using-CNN
   ```

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook Classifying-cifar-10-dataset.ipynb
   ```

2. Follow the instructions in the notebook to load the CIFAR-10 dataset, train the model, and evaluate its performance.

## Dependencies

The `requirements.txt` file contains all the dependencies needed for this project:

```
numpy==1.25.2
pandas==1.5.3
matplotlib==3.4.3
seaborn==0.13.2
scikit-learn==1.3.0
pytorch==2.0.1
torchvision==0.15.2
jupyter
```

## Results

After training, the notebook evaluates the model's performance using metrics like accuracy and loss, and visualizes the results with charts.

## License

This project is licensed under the MIT License. Feel free to use and modify the code as needed.
