# Captum Interpretability Demonstrations

This repository contains a collection of Python scripts that demonstrate the use of the Captum library for model interpretability. Captum provides a suite of tools to help understand and interpret the predictions of deep learning models, particularly in computer vision tasks.

## Overview

The project focuses on applying various interpretability techniques to a ResNet18 model fine-tuned on the CIFAR-10 dataset. These techniques help in visualizing and understanding how different parts of an input image contribute to the model's prediction, making it easier to trust and debug the model's behavior.

## Key Features

- **Grad-CAM Visualization**: Generates visual explanations for decisions made by the model by highlighting important regions of the image that most strongly influence the output.
- **Integrated Gradients**: Attributes the prediction of the model to its input features by integrating gradients along a straight path from a baseline to the input.
- **Gradient SHAP**: Combines the ideas from SHAP values and Integrated Gradients to attribute the output prediction to input features by computing weighted averages of gradients.

Each technique provides a different perspective on model interpretability, helping to dissect and understand the inner workings of neural networks.
