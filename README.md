# Image Classification Project

## Table of Contents
- [Introduction](#introduction)
- [Preprocessing](#preprocessing)
  - [Face and Eyes Detection](#face-and-eyes-detection)
  - [Wavelet Transform](#wavelet-transform)
- [Data](#data)
- [Model Training](#model-training)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project is focused on image classification using computer vision techniques and machine learning algorithms. It includes the following components:

## Preprocessing

### Face and Eyes Detection

In this step, the code uses Haar cascades to detect faces and eyes in input images. Images containing at least two eyes are cropped and saved for further processing.

### Wavelet Transform

Wavelet transform is used as a feature extraction technique. It helps in enhancing the edges in images, making them more suitable for training machine learning models.

## Data

The code expects a dataset of images for different classes (e.g., celebrities). The images should be organized in folders, with each folder representing a class.

## Model Training

The code trains machine learning models on the preprocessed image data. It includes support vector machines (SVM), random forests, and logistic regression models.

## Results

The image classification models were trained and evaluated on the dataset, producing the following results:

### Model Performance

The models were evaluated using cross-validation, and the best performing models and their corresponding hyperparameters are as follows:

- Support Vector Machine (SVM):
  - Best Score: 0.827536
  - Best Parameters: {'svc__C': 1, 'svc__kernel': 'linear'}

- Random Forest:
  - Best Score: 0.714493
  - Best Parameters: {'randomforestclassifier__n_estimators': 10}

- Logistic Regression:
  - Best Score: 0.844565
  - Best Parameters: {'logisticregression__C': 1}

## Usage

To use this project, follow these steps:

1. Organize your dataset as described in the Data section.
2. Run the preprocessing code to detect faces, eyes, and apply wavelet transforms.
3. Train machine learning models using the preprocessed data.
4. Evaluate the models and analyze the results.

## Contributing

Contributions to this project are welcome. If you have ideas for improvements or bug fixes, please create a pull request. Make sure to follow any contribution guidelines specified in the repository.

## License

This project is licensed under the [MIT] License - see the [MIT](LICENSE.md) file for details.

---


