# Credit Score Classification

This repository contains the implementation of a **Credit Score Classification** project. The project demonstrates an end-to-end pipeline to classify credit scores into categories, helping financial institutions assess creditworthiness efficiently.

## Project Overview

Credit scoring is a crucial tool for financial decision-making. This project utilizes machine learning models to classify individuals based on their credit score using relevant features. The focus is on building an accurate and interpretable model to assist in lending decisions.

### Key Highlights:
- **Data Preprocessing**: Managing missing values, scaling, and encoding categorical data.
- **Exploratory Data Analysis (EDA)**: Deriving insights and relationships among features through visualizations.
- **Model Training and Evaluation**: Comparison of multiple classification algorithms to identify the best-performing model.
- **Performance Metrics**: Metrics like Accuracy and F1 Score are used to measure the effectiveness of the models.

## Results

The models achieved the following metrics:
- **Model 1**:  
  - Accuracy: **77.38%**  
  - F1 Score: **67.18%**
- **Model 2**:  
  - Accuracy: **71.06%**
- **Model 3**:  
  - Accuracy: **78.39%**

## Requirements

Ensure the following dependencies are installed:
- Python 3.x
- Libraries:
  - NumPy
  - Pandas
  - Scikit-learn
  - Matplotlib
  - Seaborn

Install dependencies using:
```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/anujstats/credit_score_classification.git
   cd credit_score_classification
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Credit\ Score\ Classification\ final.ipynb
   ```
3. Follow the steps in the notebook to:
   - Preprocess the data.
   - Train and tune machine learning models.
   - Evaluate results using performance metrics.

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue for suggestions and improvements.
