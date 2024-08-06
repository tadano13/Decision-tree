# Decision Tree

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Description

This project implements decision tree algorithms to classify and predict data. It includes data preprocessing, model training, and evaluation metrics. Decision trees are a popular machine learning model for classification and regression tasks due to their interpretability and simplicity.

## Features

- **Data Loading and Preprocessing**: Handles missing values, encodes categorical variables, and normalizes numerical features.
- **Decision Tree Implementation**: Utilizes scikit-learn's `DecisionTreeClassifier` for model training.
- **Model Evaluation**: Includes accuracy, precision, recall, F1 score, and confusion matrix.
- **Visualization**: Decision tree structure visualization and feature importance.
- **Interactive Streamlit App**: `app.py` is deployed using Streamlit, allowing users to interact with the model and explore predictions.

## Installation

Follow these steps to set up the project on your local machine:

### Prerequisites

- Python 3.7+
- Jupyter Notebook
- Streamlit
- Necessary Python packages (see `requirements.txt`)

### Installation Steps

1. **Clone the repository**:
    ```bash
    git clone https://github.com/tadano13/Decision-tree.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd Decision-tree
    ```

3. **Create a virtual environment** (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

4. **Install the dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To use the project:

1. **Run the Jupyter Notebook**:
    ```bash
    jupyter notebook notebooks/decision_tree.ipynb
    ```

2. **Run the Streamlit App**:
    ```bash
    streamlit run app.py
    ```
   This will open a web interface where you can interact with the decision tree model, input data, and view predictions.

3. **Explore the Notebook**:
   - The notebook includes sections for data exploration, model training, and evaluation. Follow the step-by-step instructions provided in the notebook cells.

## Project Structure

Decision-tree/
│
├── app.py # Streamlit app for interaction
├── data/
│ ├── dataset.csv # Raw dataset
│ └── processed_data.csv # Processed dataset
│
├── notebooks/
│ └── decision_tree.ipynb # Main notebook
│
├── src/
│ ├── data_preprocessing.py # Data preprocessing scripts
│ ├── model.py # Model training and evaluation scripts
│ └── visualization.py # Visualization utilities
│
├── requirements.txt # List of dependencies
├── LICENSE # License file
└── README.md # Project README
