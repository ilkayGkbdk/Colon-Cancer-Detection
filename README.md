# Colon Cancer Detection

## Overview

This project is a deep learning-based colon cancer detection system that utilizes histopathological images. The system preprocesses histopathological images, 
extracts relevant features using a deep convolutional neural network, and classifies the images to detect signs of cancer. 
This project was developed as part of a **Deep Learning** course in the 3rd year of university.

## Features

- Preprocessing of histopathological images (resizing, format validation)
- Dataset split into training, validation, and testing sets
- Image classification with a CNN model
- Model training with TensorFlow and Keras
- Performance evaluation and results visualization
- Model saving and loading functionality

## Technologies Used

- **Python** (version 3.x)
- **TensorFlow** (for deep learning model creation and training)
- **Keras** (high-level neural networks API)
- **OpenCV** (for image processing)
- **Matplotlib** (for visualizing training results)
- **NumPy** (for numerical computations)
- **PIL** (for image format handling)

## File Structure

```
project_root/
│-- dataset/
│   ├── colon_aca/ (1000 images of cancerous tissue)
│   ├── colon_n/ (1000 images of non-cancerous tissue)
│-- forTEST/
│   ├── colon_aca_test/ (10 test images of cancerous tissue)
│   ├── colon_n_test/ (10 test images of non-cancerous tissue)
│-- logs/
│   ├── train/ (training logs)
│   ├── validation/ (validation logs)
│-- models/
│   └── colon_model_v4.keras (saved model)
│-- main.ipynb (Jupyter notebook containing the code)
```

## Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-repo-name.git
cd your-repo-name
```

### 2. Install Dependencies

Make sure you have Python 3.8+ installed, then run:

```bash
pip install -r requirements.txt
```

### 3. Test With Your Own Dataset (Optional)

Alternatively, if you want to use your own dataset, Place your dataset (colon_aca, colon_n) in the dataset/ directory, ensuring the folder structure follows the one described above.


## Dataset Credit

This dataset was obtained from [colon-cancer-detection-dataset](https://www.kaggle.com/datasets/andrewmvd/lung-and-colon-cancer-histopathological-images). Special thanks to the original creators.

## Contribution

Feel free to contribute to this project by submitting issues or pull requests.

