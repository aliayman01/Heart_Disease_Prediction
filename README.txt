# Heart Disease Prediction — Binary Classification

## Overview

This project was developed as a group project during our second year at university for the Artificial Intelligence (AI) course.

The goal of the project is to explore **binary classification techniques** by building machine learning models to predict the presence or absence of heart disease based on patient data.

We implemented and evaluated multiple classification algorithms to compare their performance and understand how different machine learning approaches perform on the same dataset.

## Objectives

- Apply machine learning concepts to a real-world classification problem.
- Explore data preprocessing and feature scaling.
- Train and evaluate multiple classification models.
- Compare model performance using standard evaluation metrics.
- Visualize and interpret classification results.

## Machine Learning Models

The project explores the following classification algorithms:

- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Decision Tree Classifier**

## Technologies Used

- Python
- Jupyter Notebook
- Pandas — data manipulation and analysis
- NumPy — numerical computing
- Matplotlib — data visualization
- Seaborn — statistical visualization
- Scikit-learn — preprocessing, model training, and evaluation

## Project Workflow

1. **Data Loading:** Load the training and testing datasets.
2. **Data Exploration:** Examine the dataset and explore the distribution of the target variable.
3. **Preprocessing:** Prepare the data and apply feature scaling where appropriate.
4. **Model Training:** Train the selected classification algorithms.
5. **Model Evaluation:** Evaluate the models using accuracy, precision, recall, F1-score, and confusion matrices.
6. **Model Comparison:** Compare the results to understand the strengths and limitations of each approach.

## Repository Structure

```text
Heart-Disease-Prediction/
├── AI project.ipynb
├── train_data.csv
├── test_data.csv
└── README.md
```

*The filenames above are illustrative; adjust them to match the files in your repository.*

## Getting Started

### Prerequisites

Python 3 and Jupyter Notebook or JupyterLab are required.

### Installation

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Running the Project

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd <repository-folder>
   ```

3. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open the project notebook and run the cells in order.

Ensure that the training and testing CSV files are available in the location specified by the notebook.

## Evaluation Metrics

The models are evaluated using:

- **Accuracy:** The proportion of correctly classified observations.
- **Precision:** The proportion of positive predictions that are correct.
- **Recall:** The proportion of actual positive cases correctly identified.
- **F1-score:** The harmonic mean of precision and recall.
- **Confusion Matrix:** A breakdown of correct and incorrect predictions for each class.

## Key Learning Outcomes

Through this project, we gained practical experience with:

- Data preprocessing and feature scaling.
- Implementing supervised machine learning algorithms.
- Evaluating binary classification models.
- Comparing machine learning model performance.
- Using Python's data science and machine learning libraries.

## Team Project

This project was completed collaboratively as part of our second-year Artificial Intelligence course at university.

## Disclaimer

This project is intended for educational purposes only. Its predictions are not intended for medical diagnosis or clinical decision-making.

## License

This project was developed for academic learning. No specific open-source license is granted unless one is added to the repository.
