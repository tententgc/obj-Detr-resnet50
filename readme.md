# DETR (DEtection TRansformer) with ResNet-50

This repository contains code to train the [DETR](https://arxiv.org/abs/2005.12872) model with a ResNet-50 backbone for object detection.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Dataset Preparation](#dataset-preparation)
- [Training](#training)
- [Evaluation](#evaluation)
- [Acknowledgments](#acknowledgments)

## Introduction
DETR (DEtection TRansformer) is a transformer-based architecture that directly predicts the final set of detections, with the transformer mechanism handling the modeling of interactions between objects in an image. In this repo, we provide instructions to train DETR with a ResNet-50 backbone.

## Installation
To install the required dependencies, run the following:

```bash
# Clone the repository
git clone https://github.com/your-username/detr-resnet50-training.git
cd detr-resnet50-training

# Create and activate a virtual environment (optional but recommended)
python3 -m venv env
source env/bin/activate  # On Windows, use `env\Scripts\activate`

# Install dependencies
pip install -r requirements.txt
