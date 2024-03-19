# Leaf-Lab
Plant disease classification using CNN to identify plant diseases.

# Plant Disease Classification using CNN

This repository contains code for a Convolutional Neural Network (CNN) based plant disease classification model. The model is trained to classify various plant diseases using images from the Kaggle dataset. It achieves an accuracy of 87.14% after 5 epochs of training on a Google Colab T4 GPU.

![Screenshot 2024-03-18 202148](https://github.com/ayushtan123/Leaf-Lab/assets/121681555/24821296-efd2-4338-ba7f-3fc1fac91f5f)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/ayushtan123/Leaf-Lab.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Copy API of this Kaggle dataset from [Kaggle](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset) and place the `kaggle.json` file in the root directory of the project.

## Usage

1. Run the Streamlit app:

    ```bash
    streamlit run main.py
    ```
H5 file can be downloaded from drive link given in text file : app/trained_model_link.txt

2. Open the provided URL in your browser.

3. Upload an image of a plant leaf to classify the disease.

## Colab File
https://colab.research.google.com/drive/1CRT9Ht4qtZFrST67S6MhSvDDXsOiAfbn?usp=sharing

## Results

- **Model**: Convolutional Neural Network (CNN)
- **Framework**: TensorFlow
- **GPU**: Google Colab T4
- **Epochs**: 5
- **Accuracy**: 87.14%

![Screenshot 2024-03-18 205540](https://github.com/ayushtan123/Leaf-Lab/assets/121681555/00854162-ee63-4331-9f27-e2f12abf3718)
![Screenshot 2024-03-18 203321](https://github.com/ayushtan123/Leaf-Lab/assets/121681555/e9a8558f-f1bd-47ac-981d-0ce3b79b2af8)


