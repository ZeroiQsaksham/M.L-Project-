# Rock vs. Mine Prediction using Machine Learning

## Overview

This project is focused on classifying objects as either rocks or mines using machine learning algorithms. The dataset used for this project contains sonar signals collected from objects to identify whether the object is a rock or a mine. The goal is to build a predictive model that can accurately classify objects based on the features of the sonar data.

## Project Structure

- **`ML_Project.py`**: The main Python script containing the workflow for data preprocessing, model training, and evaluation.
- **`data/`**: Directory where the dataset is stored.
- **`models/`**: Directory to store trained models.
- **`results/`**: Directory for storing evaluation metrics and visualizations.
- **`scripts/`**: Additional Python scripts for preprocessing and model-related tasks.

## Dataset

The dataset used for this project is the **Sonar, Mines vs. Rocks Dataset**, which contains 60 features of sonar signals and a label identifying whether the object is a rock or a mine.

- **Features**: 60 continuous attributes representing sonar signal data.
- **Target**: Binary classification of 'Rock' (0) or 'Mine' (1).



## Requirements

To run this project, you will need the following libraries:

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn (for visualization)

Install the required dependencies using pip:

```bash
pip install -r requirements.txt
