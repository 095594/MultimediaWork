Fashion MNIST Classification

Overview

This project builds a Convolutional Neural Network (CNN) to classify images from the Fashion MNIST dataset. The dataset contains grayscale images (28x28 pixels) of 10 clothing categories, such as T-shirts, shoes, and bags. The goal is to train a model to correctly identify these items.

Prerequisites

Before setting up the project, ensure you have:

A computer with Python 3.8 or later installed.

pip (Python package manager) installed.

An internet connection (to install dependencies and download the dataset).

Installation

Follow these steps to set up the project:

Clone or Download the Project
If you have Git installed, clone the repository using:

git clone https://github.com/your-repo-link.git
cd MultimediaWork

If you don't have Git, you can manually download the project as a ZIP file, extract it, and navigate to the project folder.

Create a Virtual Environment (Recommended)
A virtual environment keeps dependencies organized:

python -m venv env

On Windows, activate it using:

env\Scripts\activate

On Mac/Linux, activate it using:

source env/bin/activate

Install Dependencies
Install all required libraries using:

pip install -r requirements.txt

Running the Model

Ensure dependencies are installed (see installation steps above).

Run the Python script to train the model:

python fashionmnist.py

The model will train, and you will see accuracy metrics displayed.

Sample predictions will be visualized using Matplotlib.

Project Files

fashionmnist.py - The main script for training and evaluating the model.

requirements.txt - A list of required Python libraries.

README.md - This documentation file.

Troubleshooting

If using PyCharm and facing display issues with Matplotlib, add this to fashionmnist.py before importing matplotlib.pyplot:

import matplotlib
matplotlib.use('TkAgg')

If you get a ModuleNotFoundError, ensure you installed dependencies correctly using:

pip install -r requirements.txt

Additional Information

Fashion MNIST is an alternative to the classic MNIST dataset but with clothing categories instead of handwritten digits.

The model uses CNNs (Convolutional Neural Networks), which are effective for image classification tasks.

Author

Created by Group 4. 🚀

