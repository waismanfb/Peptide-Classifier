# Machine Learning-Based Classification of Peptides Considering Amino Acid and Dipeptide Composition

This project involves training and evaluating multiple machine learning models on a given dataset. The models used in this project include RandomForest, SVC, and LogisticRegression.

## Files

- `main.ipynb`: This is the main script that orchestrates the loading of data, preprocessing, training models, evaluating performance, and displaying results.

- `data.csv`: This is the dataset used in the project. It contains features and labels for training and testing the machine learning models.

## Data

The data used in this project is stored in `data.csv`. This file contains several features that are used to predict the target variable. The data has been preprocessed and split into training and testing sets within the `main.ipynb` script.

## Functions

- `build_model_pipeline(model)`: Constructs a machine learning pipeline that includes preprocessing steps and the specified model.

- `evaluate_model(model, X_test, y_test)`: Evaluates the performance of a trained model on the test data and computes various performance metrics.

- `plot_metrics(metrics)`: Visualizes the performance metrics of a trained model.

- `main()`: The entry point of the program. It contains the primary logic of the script.

## Usage

To run the script, navigate to the project directory and run the following command:

```bash
python main.ipynb
