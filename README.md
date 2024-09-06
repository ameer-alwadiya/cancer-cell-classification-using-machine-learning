# Cancer Cell Classification Using Machine Learning

This project focuses on building a machine learning model for the classification of cancer cells. By utilizing various machine learning techniques, the goal is to accurately differentiate between cancerous and non-cancerous cells based on input features.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Models Used](#models-used)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

Cancer classification is a crucial problem in the medical field. This project implements machine learning algorithms to classify cancer cells based on a dataset containing features related to cell characteristics. The aim is to build an accurate model to assist in diagnosis.

## Dataset

The dataset used in this project includes various features extracted from cell nuclei of biopsy images. Each instance in the dataset is labeled as either cancerous or non-cancerous.

### Dataset Features:

- Mean radius
- Mean texture
- Mean smoothness
- Mean compactness
- Mean symmetry
- Fractal dimension
- ... and more.

### Labels:
- `1`: Malignant (cancerous)
- `0`: Benign (non-cancerous)

The dataset is available in the repository under the `data/` directory.

## Installation

To run the project, you'll need to have Python installed, along with the required libraries.

1. Clone the repository:

   ```bash
   git clone https://github.com/ameer-alwadiya/cancer-cell-classification-using-machine-learning.git
   cd cancer-cell-classification-using-machine-learning
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

Once the project is set up, you can run the following command to train the model:

```bash
python train_model.py
```

You can also test the model using the following command:

```bash
python test_model.py
```

### Jupyter Notebook

Alternatively, you can explore the data and run the training process in a Jupyter Notebook. The `CancerCellClassification.ipynb` notebook walks through the process of loading the dataset, training the model, and evaluating its performance.

## Models Used

This project explores various machine learning models, including:

- **Logistic Regression**: A simple baseline model.
- **Support Vector Machine (SVM)**: A powerful model for classification tasks.
- **Random Forest**: An ensemble method known for good accuracy in classification problems.
- **K-Nearest Neighbors (KNN)**: A distance-based algorithm that classifies based on proximity to other data points.

## Results

The model evaluation is done using common metrics, including:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

The project report and evaluation results are available in the `results/` directory.

## Contributing

If you'd like to contribute to the project, feel free to fork the repository and submit a pull request.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Submit a pull request
