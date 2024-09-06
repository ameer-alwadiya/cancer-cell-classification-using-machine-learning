# Cancer Cell Classification Using Machine Learning

This project aims to develop an accurate, explainable deep learning model to classify cancer cells into healthy and metastatic categories. The project also focuses on enhancing the interpretability of the model's predictions by identifying critical cellular features that influence classification decisions.

## Aim

The primary aim of this project is to:
- Develop an accurate and explainable deep learning model for classifying cells into healthy and metastatic categories.
- Enhance the interpretability of the model’s predictions by identifying key cellular features that impact classification decisions.

## Objectives

### Basic Objectives

1. **Literature Review on Cancer Cell Classification:**
   - Analyze the dataset of healthy and metastatic cells, including explanations of primary tumor types and individual cell data.
   - Conduct a comprehensive literature review on the application of machine learning and deep learning algorithms in cancer cell classification.

2. **Segmentation-Based Extraction Methods:**
   - Develop and apply segmentation techniques to extract individual cells from microscopy images.
   - Compare the extracted cells with manually extracted cell data images.

3. **Model Design and Implementation:**
   - Develop a deep learning model for classifying healthy and metastatic cells.
   - Use appropriate neural network architectures and evaluate their performance on the provided dataset.

4. **Address Class Imbalance:**
   - Investigate the impact of class imbalance on model accuracy and performance metrics.
   - Implement strategies to mitigate the effects of class imbalance and evaluate preprocessing techniques.

### Advanced Objectives

1. **Comparison with Pre-trained Models:**
   - Compare the performance of the newly developed model with two pre-trained models.
   - Analyze differences in accuracy, interpretability, and robustness across different model architectures.

2. **Model Interpretation and Explainability:**
   - Develop and apply techniques such as Grad-CAM, Guided Grad-CAM, and High-Resolution Guided Grad-CAM to describe the reasoning behind the model’s decisions.
   - Focus on identifying and visualizing key features influencing model predictions.

3. **Comparison of Extraction Methods:**
   - Evaluate the performance of the model on both manually extracted and segmentation-extracted cells.
   - Analyze the differences in explainability and accuracy between these extraction techniques, particularly in the context of imbalanced classes.

## Getting Started

**Clone the Repository:**
   ```bash
   git clone https://github.com/ameer-alwadiya/cancer-cell-classification-using-machine-learning.git
   cd cancer-cell-classification-using-machine-learning
   ```

## Contributing

Feel free to contribute to this project by submitting issues or pull requests. For any questions or suggestions, please open an issue in the repository.
