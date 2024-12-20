# Devanagari Character Recognition Model

This repository provides a robust deep learning model for recognizing handwritten Devanagari characters and digits. The model is capable of predicting individual characters with high accuracy, making it a useful tool for OCR (Optical Character Recognition) tasks involving Devanagari script.

## Model Overview

The model is a Convolutional Neural Network (CNN) trained on a dataset of grayscale images of Devanagari characters and digits. It takes in an input image (32x32) and outputs the recognized character or digit.

## Model Performance

### Validation Metrics
- **Validation Loss**: `0.0777`
- **Validation Accuracy**: `98.1%`

### Detailed Classification Report:

| **Character**   | **Precision** | **Recall** | **F1-Score** | **Support** |
|------------------|--------------|------------|--------------|-------------|
| क               | 0.99         | 0.98       | 0.99         | 380         |
| ख               | 1.00         | 0.98       | 0.99         | 404         |
| ग               | 0.98         | 1.00       | 0.99         | 371         |
| घ               | 0.97         | 0.98       | 0.97         | 404         |
| ङ               | 0.98         | 0.98       | 0.98         | 423         |
| च               | 0.99         | 0.98       | 0.98         | 394         |
| छ               | 1.00         | 0.93       | 0.97         | 395         |
| ज               | 0.99         | 0.98       | 0.99         | 384         |
| झ               | 0.99         | 0.98       | 0.99         | 401         |
| ञ               | 0.99         | 0.97       | 0.98         | 388         |
| ट               | 0.98         | 0.98       | 0.98         | 426         |
| ठ               | 0.98         | 0.98       | 0.98         | 382         |
| ड               | 0.98         | 0.98       | 0.98         | 421         |
| ढ               | 0.98         | 0.97       | 0.98         | 371         |
| ण               | 0.99         | 0.99       | 0.99         | 384         |
| त               | 0.96         | 1.00       | 0.98         | 407         |
| थ               | 0.97         | 0.94       | 0.95         | 414         |
| द               | 0.96         | 0.97       | 0.96         | 419         |
| ध               | 0.97         | 0.95       | 0.96         | 394         |
| न               | 0.98         | 0.98       | 0.98         | 406         |
| प               | 0.97         | 1.00       | 0.98         | 416         |
| फ               | 0.99         | 0.99       | 0.99         | 412         |
| ब               | 0.98         | 0.94       | 0.96         | 404         |
| भ               | 0.97         | 0.98       | 0.98         | 393         |
| म               | 0.98         | 0.98       | 0.98         | 402         |
| य               | 0.93         | 0.99       | 0.96         | 390         |
| र               | 0.97         | 0.99       | 0.98         | 401         |
| ल               | 0.99         | 0.99       | 0.99         | 388         |
| व               | 0.95         | 0.95       | 0.95         | 391         |
| श               | 0.99         | 1.00       | 0.99         | 410         |
| ष               | 0.99         | 0.99       | 0.99         | 385         |
| स               | 0.98         | 0.98       | 0.98         | 402         |
| ह               | 0.98         | 0.98       | 0.98         | 429         |
| क्ष             | 0.99         | 0.97       | 0.98         | 404         |
| त्र             | 0.99         | 0.98       | 0.99         | 436         |
| ज्ञ             | 1.00         | 0.99       | 0.99         | 411         |
| ०               | 1.00         | 1.00       | 1.00         | 421         |
| १               | 0.97         | 1.00       | 0.98         | 393         |
| २               | 0.99         | 0.98       | 0.99         | 382         |
| ३               | 0.99         | 0.99       | 0.99         | 387         |
| ४               | 1.00         | 0.99       | 1.00         | 403         |
| ५               | 0.99         | 1.00       | 1.00         | 370         |
| ६               | 0.97         | 1.00       | 0.98         | 406         |
| ७               | 1.00         | 0.99       | 0.99         | 383         |
| ८               | 0.97         | 0.99       | 0.98         | 415         |
| ९               | 0.99         | 0.99       | 0.99         | 398         |

- **Overall Accuracy**: `98.1%`
- **Macro Average**: `Precision: 0.98`, `Recall: 0.98`, `F1-Score: 0.98`
- **Weighted Average**: `Precision: 0.98`, `Recall: 0.98`, `F1-Score: 0.98`

---

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

