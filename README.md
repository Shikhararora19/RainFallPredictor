# Rainfall Predictor

![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-blue?style=for-the-badge)
![Python](https://img.shields.io/badge/Language-Python-brightgreen?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Data%20Analysis-Pandas-orange?style=for-the-badge)
![NumPy](https://img.shields.io/badge/Numerical%20Computing-NumPy-orange?style=for-the-badge)
![Matplotlib](https://img.shields.io/badge/Visualization-Matplotlib-blue?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Visualization-Seaborn-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=for-the-badge)

## Project Overview

The **Rainfall Predictor** is a machine learning-based solution for predicting the likelihood of rainfall using historical weather data. It focuses on leveraging statistical analysis and machine learning models to make predictions based on key weather parameters such as temperature, humidity, wind speed, and pressure.

This project is implemented as a standalone Python program, using Jupyter Notebook for analysis and visualization. It demonstrates the application of supervised machine learning techniques for meteorological predictions.

---

## Features

- **Rainfall Prediction**: Uses machine learning models to predict the probability of rainfall based on input weather parameters.
- **Data Visualization**: Provides detailed visualizations of the dataset using Matplotlib and Seaborn to uncover patterns and trends.
- **Machine Learning Models**: Implements and evaluates multiple models, such as Logistic Regression, Random Forest, and Gradient Boosting.
- **Interactive Analysis**: Uses Jupyter Notebook for interactive exploration and execution.

---

## Tech Stack

### **Programming Language**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### **Machine Learning**
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

### **Data Analysis**
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

### **Data Visualization**
![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)

---

## Dataset

The model is trained on a dataset containing historical weather data, including features like temperature, humidity, pressure, wind speed, and rainfall status. Preprocessing steps include:

- **Handling Missing Values**: Imputation of missing data.
- **Feature Scaling**: Normalization of numerical features.
- **Encoding**: Conversion of categorical variables into numerical form.

---

## Model Architecture

The project employs supervised machine learning models built using **Scikit-Learn**. Key highlights include:

- **Algorithm**: Experiments with models such as Logistic Regression, Random Forest, and Gradient Boosting.
- **Feature Engineering**: Selection and transformation of features to improve model performance.
- **Evaluation Metrics**: Uses metrics such as accuracy, precision, recall, and F1-score to evaluate model performance.

---

## Installation

Follow these steps to run the project locally:

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook or any IDE supporting `.ipynb` files

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Shikhararora19/RainFallPredictor.git
   cd RainFallPredictor
   ```

2. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook RainfallPredictor.ipynb
   ```

5. Run the cells in the notebook to execute the analysis and prediction pipeline.

---

## Usage

1. Load the Jupyter Notebook file `RainfallPredictor.ipynb`.
2. Follow the step-by-step instructions within the notebook to:
   - Load and preprocess the dataset.
   - Visualize the data using Matplotlib and Seaborn.
   - Train machine learning models.
   - Make predictions and evaluate the results.



---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- **Dataset**: Historical weather data from public or simulated sources.
- **Frameworks**: Scikit-Learn.
- **Libraries**: Pandas, NumPy, Matplotlib, and Seaborn.

---

### Author

- **Shikhar Arora**
- GitHub: [Shikhararora19](https://github.com/Shikhararora19)
