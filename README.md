# Stroke Prediction Model Project

This repository hosts all files and datasets for the Stroke Prediction Model project, designed as part of "AWS Cloud Platforms" by Team 1. This initiative aims to harness machine learning for predicting stroke risk based on health data, utilizing AWS SageMaker for the model's training and deployment.

## Project Structure

- `/datasets`: This directory contains the initial dataset alongside the cleaned training and testing sets.
  - `initial_data.csv` - The raw dataset prior to preprocessing.
  - `train_set.csv` - The cleaned dataset for training.
  - `test_set.csv` - The cleaned dataset for testing.

- `/notebooks`: Jupyter notebooks for data preprocessing, analysis, model invocation, and evaluation.
  - `data_preprocessing.ipynb` - Notebook for data cleaning and preparation.
  - `model_evaluation.ipynb` - Notebook for invoking the AWS model endpoint, making predictions, and evaluating the model using the test dataset.

## Getting Started

To explore or replicate our project, start by cloning this repository to your local environment:

```
git clone https://github.com/datasxienxe/FinalProject-AWS-Team1b.git
```

### Prerequisites

- Jupyter Notebook or JupyterLab for running notebook files.
- Python 3 for script execution.
- AWS CLI and boto3 for AWS service interactions, specifically with SageMaker.

### Installation

1. Install the required Python libraries:

```bash
pip install pandas scikit-learn boto3 jupyter
```

2. Set up your AWS CLI with necessary credentials to access AWS resources:

```bash
aws configure
```

## Usage

- **Data Exploration**: Visit the `/datasets` folder to access both the raw and processed datasets.
- **Data Preprocessing**: Run the `data_preprocessing.ipynb` notebook to prepare your data for modeling.
- **Model Invocation and Evaluation**: The `model_evaluation.ipynb` notebook details how to call the SageMaker model endpoint for predictions and evaluate its performance based on the processed test data.

## Contributing

Feedback and contributions are highly appreciated. Feel free to fork the repository, submit pull requests, or open issues for discussion.

## Authors

- Jacob Jentoft
- Rohan Gupta
- Marta Peregrin
- Szymon Choma
- Simon Berheider
- Thalia Hsu

## Acknowledgments

- Thanks to Prof. Guerris for the invaluable advice and oversight provided.
- AWS services, which were instrumental in developing and deploying our machine learning model.
