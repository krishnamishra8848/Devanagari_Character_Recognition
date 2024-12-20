# Devanagari Character Recognition Model

This repository provides a robust deep learning model for recognizing handwritten Devanagari characters and digits. The model is capable of predicting individual characters with high accuracy, making it a useful tool for OCR (Optical Character Recognition) tasks involving Devanagari script.

## Model Overview

The model is a Convolutional Neural Network (CNN) trained on a dataset of grayscale images of Devanagari characters and digits. It takes in an input image (32x32) and outputs the recognized character or digit.

### Strengths:
- **High Accuracy**: The model achieves a validation accuracy of **98.1%** with a low validation loss.
- **Lightweight**: The model is efficient and runs seamlessly on both CPU and GPU environments.
- **Simple to Use**: The model is available as a pre-trained `.keras` file and can be integrated into applications with minimal setup.

### Weaknesses:
- The model recognizes only the following Devanagari characters and digits:
    - **Consonants**: क, ख, ग, घ, ङ, च, छ, ज, झ, ञ, ट, ठ, ड, ढ, ण, त, थ, द, ध, न, प, फ, ब, भ, म, य, र, ल, व, श, ष, स, ह, क्ष, त्र, ज्ञ
    - **Digits**: ०, १, २, ३, ४, ५, ६, ७, ८, ९
- **No Contextual Understanding**: The model predicts each character individually and does not consider the context of adjacent characters.
- **Preprocessed Input**: The model expects a fixed input size of 32x32 grayscale images. Additional preprocessing is required for larger or colored images.

## Usage

### Access the Model
You can use the model interactively via the following Hugging Face Space:
[Devanagari Character Recognition App](https://huggingface.co/spaces/krishnamishra8848/devanagari_character_recognition)

### Download the Model and Source Code
To download the model or source code, visit the Hugging Face repository:
[Model and Source Code Repository](https://huggingface.co/krishnamishra8848/Devanagari_Character_Recognition)

## Model Features
- **Character Set**: Recognizes 36 Devanagari consonants and 10 digits (०-९).
- **Input Requirements**:
  - Input images must be in grayscale format.
  - Input size should be 32x32 pixels.
- **Output**: A single predicted character or digit.

