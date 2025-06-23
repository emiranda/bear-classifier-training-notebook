# Bear Classifier – Training Notebook

Training notebook for a bear image classifier using fastai and transfer learning.

## Overview

This project demonstrates how to train an image classifier that distinguishes between grizzly bears, black bears, and teddy bears. The model was built using the fastai library and fine-tuned from a pre-trained `resnet18` model.

The resulting `.pkl` file is used in production on Hugging Face Spaces:
👉 [Live Demo](https://huggingface.co/spaces/emiranda182/bear_classifier)

## Contents

- `bear_classifier_training.ipynb` – full training notebook
- `bears.zip` – zipped dataset used for training (downloaded using DuckDuckGo)

## Setup Instructions

1. Unzip `bears.zip` into a `bears/` folder
2. Open the notebook in Jupyter or Colab
3. Run all cells to retrain the model

## Requirements

- Python 3.10+

Install requirements:

```bash
pip install fastai duckduckgo_search
