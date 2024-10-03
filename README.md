# Linear-Regression-SVM-Naive-Bayes-Models

## Project Overview
This repository includes a project which utilizes machine learning models to predict the likelihood of heart disease in individuals. This project employs Logistic Regression, Support Vector Machine (SVM), and Naive Bayes classifiers to analyze clinical data and assess heart disease risk efficiently.

**Note**: This repository includes implementations for three different machine learning models which I developed. Other potential models are not shared here.

## Motivation
The goal of this project is to provide an automated tool for predicting heart disease, aiding medical professionals and individuals by delivering swift and accurate assessments of cardiovascular health risks.

## Dataset
The dataset used in this project, known as the "Heart Disease Dataset," includes 303 samples with 13 clinical features. It is designed to support the prediction of heart disease occurrence based on various physiological and medical tests. You can find more about the dataset [here](https://archive.ics.uci.edu/dataset/45/heart+disease).

**Features**:
- Age, Sex, Chest pain type, Resting blood pressure
- Serum cholesterol in mg/dl, Fasting blood sugar > 120 mg/dl
- Resting electrocardiographic results, Maximum heart rate achieved
- Exercise induced angina, ST depression induced by exercise relative to rest
- The slope of the peak exercise ST segment
- Number of major vessels colored by flourosopy
- Thalassemia: 0 = normal; 1 = fixed defect; 2 = reversible defect

**Target Variable**:
- Heart Disease: 0= less chance of heart attack; 1= more chance of heart attack

**Note**: Due to privacy and licensing reasons, the dataset is not included in this repository.

## Technologies Used
- Python
- Scikit-Learn
- Pandas
- NumPy
- Matplotlib

## Features
- Comprehensive data preprocessing including handling missing values and feature standardization.
- Application of three different machine learning algorithms to assess their performance.
- Evaluation of model performance using accuracy, precision, and confusion matrices.

## Results
We evaluated the performance of three models: Logistic Regression, SVM, and Naive Bayes. The results showed notable differences in accuracy and precision, highlighting the strengths and weaknesses of each model under various configurations.

## Installation
To set up this project for use or development, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/spymavro/Linear-Regression-SVM-Naive-Bayes-Models.git
   cd Linear-Regression-SVM-Naive-Bayes-Models
2. **Install the required Python packages**:

- Ensure you have Python installed on your system. If not, download and install it from [python.org](https://www.python.org/downloads/).
- It's recommended to create a virtual environment to keep dependencies required by different projects separate and to avoid conflicts:
  ```bash
  python -m venv venv
  source venv/bin/activate  # On Windows use `venv\Scripts\activate`
- Install the required packages:
  ```bash
  pip install numpy pandas scikit-learn matplotlib

3. **Proceed with project setup and usage as required**:
### Explanation:
- **Step 1**: Cloning the repository is straightforward; make sure to replace `spymavro` with your actual GitHub username.
- **Step 2**: This step covers:
  - Checking for Python installation.
  - Setting up a virtual environment, which is optional but recommended.
  - Direct installation of each required Python package using `pip`.

## Usage
- Navigate to the cloned directory in your terminal and execute the Logistic Regression, SVM and Naive Bayes models script by running:
  ```bash
  python lr_svm_nb.py 

## Contact
For any inquiries or collaboration requests, please reach out via GitHub or email at spyros.mauromatis@gmail.com.



