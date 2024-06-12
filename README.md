# Handwritten Digit Recognition using Neural Networks

![Python](https://img.shields.io/badge/Python-3.8-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.4-orange.svg)
![NumPy](https://img.shields.io/badge/NumPy-1.19.5-green.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.1.5-red.svg)

## Overview

This repository contains a Jupyter Notebook that demonstrates the implementation of a neural network for recognizing handwritten digits. The model achieves an accuracy of over 92% on the test set. The project uses TensorFlow for building and training the neural network, with data manipulation performed using NumPy and Pandas.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Requirements](#requirements)
- [Installation](#installation)
- [Results](#results)
- [Contributions](#contributions)
- [Acknowledgments](#Acknowledgments)

## Introduction

Handwritten digit recognition is a classic problem in the field of machine learning. This project utilizes a neural network to recognize digits from a dataset available on kaggle and also included in this repository for use.

## Dataset

The dataset used in this project is a kaggle dataset which I have included in the given repository.

## Model Architecture

The neural network model is built using TensorFlow and consists of the following layers:
- Input layer: Flattening the input images (28x28 pixels)
- Hidden layers: Two dense layers with ReLU activation
- Output layer: A dense layer with softmax activation for digit classification

## Requirements

- Python 3.8 or higher
- Jupyter Notebook
- TensorFlow 2.4 or higher
- NumPy 1.19.5 or higher
- Pandas 1.1.5 or higher

## Installation

To get started with the project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/MRIDUL2206/Handwritten-Digit-Recognition.git
```

## Results
The model achieves an accuracy of over 92% on the test set, demonstrating its effectiveness in recognizing handwritten digits.

## Contributions
All kinds of progressive contributions are welcome.Please open an issue or submit a pull request if you have any improvements or bug fixes.

## Acknowledgments
- The MNIST database of handwritten digits
- TensorFlow and the wider machine learning community


