
# Data Quality Assessment Using a Tree-Based Model

This repository contains a Jupyter notebook that illustrates basic data quality assessment for the classification of images in the MNIST dataset using a Random Forest model. The project demonstrates the process of training the model, evaluating its performance, and analyzing the quality of the predictions.

## Project Overview

- **Dataset**: MNIST (a large database of handwritten digits commonly used for training image processing systems).
- **Model**: Random Forest Classifier from scikit-learn.
- **Objective**: Assess the data quality by analyzing the model's performance in classifying the MNIST dataset.

## Contents

- `data_quality.ipynb`: The main Jupyter notebook that walks through the following steps:
  1. **Downloading the MNIST Dataset**: Load the dataset using scikit-learn's `fetch_openml` method.
  2. **Model Training**: Train a Random Forest model on the MNIST dataset.
  3. **Performance Evaluation**: Evaluate the model's accuracy and other metrics to determine its effectiveness.
  4. **Data Quality Analysis**: Analyze the errors made by the model to assess the quality of the data and the model's predictions.

## Getting Started

To run the notebook on your local machine, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/data-quality-assessment.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd data-quality-assessment
   ```
3. **Install the necessary dependencies**:
   - It's recommended to use a virtual environment:
     ```bash
     python -m venv env
     source env/bin/activate  # On Windows use `env\Scripts\activate`
     ```
   - Install the dependencies:
     ```bash
     pip install -r requirements.txt
     ```
4. **Run the Jupyter notebook**:
   ```bash
   jupyter notebook data_quality.ipynb
   ```

## Dependencies

- Python 3.x
- Jupyter Notebook
- scikit-learn
- pandas
- matplotlib

You can install the necessary dependencies by running:
```bash
pip install -r requirements.txt
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The MNIST dataset is a benchmark in the field of machine learning and has been provided by the National Institute of Standards and Technology.
