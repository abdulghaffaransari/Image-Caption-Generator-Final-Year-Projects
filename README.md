# Project Description

Welcome to my Final Year Project! This repository showcases my work in the field of image captioning. I employed state-of-the-art technology, using the Visual Transformer (ViT) as the encoder and the BERT Transformer as the decoder. Our goal was to generate high-quality image captions.

# Readme

Image Captioning with Vision Transformer and BERT

This project utilizes a Vision Transformer (ViT) along with BERT for image captioning tasks. It leverages the COCO dataset for training and evaluation.

Prerequisites:

## Make sure you have the following dependencies installed:

- Python 3.x
- PyTorch
- Transformers
- PIL
- Matplotlib
- NumPy
- Pandas
- NLTK
- COCO API
- Hugging Face Datasets
- Rouge Score

You can install the necessary dependencies using the provided requirements.txt file:

pip install -r requirements.txt

Usage:

1. Clone this repository:

git clone https://github.com/your_username/image-captioning.git

2. Navigate to the project directory:

cd image-captioning

3. Install dependencies:

pip install -r requirements.txt

4. Run the Jupyter notebook final-notebook-with-coco.ipynb:

jupyter notebook final-notebook-with-coco.ipynb

5. Follow the instructions provided in the notebook for training, evaluation, and inference.

## Model:

The model architecture consists of a Vision Encoder-Decoder model. The encoder utilizes a Vision Transformer (ViT), while the decoder is based on BERT.

## Training:

The model is trained using the COCO dataset, which contains images and corresponding captions. Training hyperparameters and configurations can be adjusted in the config class within the notebook.

## Evaluation:

Evaluation is performed using Rouge scores, which measure the quality of generated captions compared to ground truth captions.

## Inference:

You can make inferences on both images from the COCO dataset and external images. The model generates captions for input images using the trained model.

## Credits:

- The work of various researchers in the field of image captioning inspires this project.
- The COCO Consortium provides the COCO dataset.

---
